C++ Html Builder
----------------

A simple C++ HTML Generator library.

Copyright (c) 2017 Sébastien Rombauts (sebastien.rombauts@gmail.com)

## Building with CMake

This is a header only library, so just include the right folder and go on.

### Get cpplint submodule

```bash
git submodule init
git submodule update
```

### Typical generic build (see also "build.bat" or "./build.sh")

```bash
mkdir build
cd build
cmake ..        # cmake .. -G "Visual Studio 10"    # for Visual Studio 2010
cmake --build . # make
```

### Debug build for Unix Makefiles

```bash
mkdir Debug
cd Debug
cmake .. -DCMAKE_BUILD_TYPE=Debug   # -G "Unix Makefiles"
cmake --build . # make
```

### Release build

```bash
mkdir Release
cd Release
cmake .. -DCMAKE_BUILD_TYPE=Release  # -G "Unix Makefiles"
cmake --build . # make
```
