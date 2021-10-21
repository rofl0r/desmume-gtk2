this fork preserves GTK+2 frontend and autotools build system, while back-
porting latest master from upstream from time to time.

branch gtk2 is where it's at.

patches that went into desmume but weren't merged here can be found in
unmerged-patches.

to build, go to desmume/src/frontend/posix and run `autoreconf -i` followed
by the usual `./configure`, `make`, `make install` trinity.

original readme follows.

# DeSmuME
[![AppVeyor CI Build Status](https://ci.appveyor.com/api/projects/status/abfd7jm09wnmxyvu?svg=true)](https://ci.appveyor.com/project/zeromus/desmume)

DeSmuME is a Nintendo DS emulator.

http://desmume.org/download
