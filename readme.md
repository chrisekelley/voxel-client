# voxel-client

client for voxel-server

# setup

Voxel-client uses a custom version of duplex-emitter, which is pointed to in package.json 
and has an updated JSONStream version to work around Unexpected "\u0000" at position 0 error. Refer to
https://github.com/pgte/duplex-emitter/issues/4#issuecomment-15699928
Also added Buffer to the Window scope to make it visible to jsonparse.
That feels wrong.

This is used in [voxel-hello-client](https://github.com/chrisekelley/voxel-hello-client).

BSD LICENSE