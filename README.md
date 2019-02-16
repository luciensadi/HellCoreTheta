# HellCoreTheta
Source code for the HellCoreTheta project, a fork of HellCore, which is in turn a fork of LambdaMOO.
This particular fork of the HellCore server includes various additions I've come to find useful over the years, for a complete or possibly incomplete list of changes, see the additions section.

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

If you are unable to build despite having working and recent versions of these
installed, please file a bug report on this repository.

### Building

Simply run
```shell
./build.sh
```

The moo binary will be located as `src/moo`.

If you are familiar with the standard Linux/Unix build process, you can instead
run
```shell
./autogen.sh && ./configure && make

#### Additions

The following is a (hopefully) complete list of what has been added/changed in this fork:
