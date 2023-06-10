# windows-default-manifest

Cygwin's [windows-default-manifest](./ORIGINAL_README) packaged for esy to fix long paths issue on Windows.

1. Places an esy manifest
2. Uses longPathAware element

While this is a regular esy package that can be built inside esy
sandbox, we, however, pre-build the =default-manifest.o= so that users
installing esy don't have to wait for this package to build from
source.

Users however can build this package from source if they're willing to
set this up themselves.
