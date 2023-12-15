# C++ Modules with CMake

```sh
mkdir -p build
cd build
CXX=clang++ CC=clang cmake -DCMAKE_EXPORT_COMPILE_COMMANDS=yes -GNinja ..
ninja -v
```
