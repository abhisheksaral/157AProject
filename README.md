# 157A Project
## Project 1

In this project we make changes in the SQLite source code to support additional features according to the requirements.

### Build Instructions

#### Prerequisites

* Linux or macOS Build Environment
* tcl and gcc installed

To install run the following commands in terminal

```
apt-get install tcl
apt install gcc
```



To Compile the SQLite source code run the following commands

```
mkdir bld                ;#  Custom Build files will appear here
cd bld                   ;#  Change to the build directory
../sqlite/configure      ;#  Run the configure script
make                     ;#  make the custom build
```

To run the custom build, run the following command in /bld directtory

```
./sqlite3
```
