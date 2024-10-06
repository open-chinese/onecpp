# about onecpp
You can always run a python program in 10 minutes from scratch, while that's not such easy for c/c++, especially on Windows.

This project is a minimum project to setup the env and run a cpp program with VS Code.


# support envs

- [x] Windows + MSYS2 + VS Code

- [ ] Mac + VS Code


# setup

## 1 install VS Code

First install VS Code from here

https://code.visualstudio.com/

## 2 install MSYS2

download and install msys2 from here:

https://www.msys2.org/


config with following tutorial

https://code.visualstudio.com/docs/cpp/config-mingw


Notice:

add the gcc/g++ bin path to the PATH env, it should be

```
C:\msys64\ucrt64\bin
```

the make executable file is named "mingw32-make.exe", copy and rename to "make.exe"


## 3 build and run

for debugging: Run --> Start Debugging

for building: Terminal --> Run Task --> Select "build"

for runing: Terminal --> Run Task --> Select "run"

