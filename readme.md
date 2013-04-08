# voxel-client

client for voxel-server

# setup

Don't install the npm modules; they are included because voxel-client uses a custom version of duplex-emitter. 
TODO: create a fork of duplex-emitter to avoid including the node_modules.
Manually updated JSONStream version to work around Unexpected "\u0000" at position 0 error. Refer to
https://github.com/pgte/duplex-emitter/issues/4#issuecomment-15699928
Also added Buffer to the Window scope to make it visible to jsonparse.
That feels wrong.

This is used in [voxel-hello-client](https://github.com/chrisekelley/voxel-hello-client).


BSD LICENSE