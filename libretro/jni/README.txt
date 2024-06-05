To build the GLES2 version

export GLES3=0
ndk-build clean
ndk-build -j4


To build the GLES3 version

export GLES3=1
ndk-build clean
ndk-build -j4
