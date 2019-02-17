# HellCoreTheta
Source code for the HellCoreTheta project, a fork of HellCore, which is in turn a fork of LambdaMOO.

This particular fork of the HellCore server includes various additions I've come to find useful over the years. for a complete or possibly incomplete list of changes, see the additions section.

## Dependencies:

* autoconf
* automake
* bison
* gcc
* gperf
* libstdc++
* libgdbm3-dev
* zlib1g-dev
* make
* sed

### Building

Simply run
```shell
./build.sh
```

The moo binary will be located in `src/moo`.

If you are familiar with the standard Linux/Unix build process, you can instead
run
```shell
./autogen.sh && ./configure && make

### Additions

The following is a (hopefully) complete list of what has been added/changed in this fork:

* Martian's MOO extensions: This also includes listutils, zlib, and gdbm.
* Goblin's extension pack
* Handle Argstr patch
* Syntax update, so var = var+1 becomes ++var, var = var -1 becomes --var etc.
* get_pid: Easily get the process ID of the server.
* server_shutdown: Behaves as an opposite to server_started, that is that if a verb on $sysobj called server_shutdown, it'll be executed upon a server shutdown.
