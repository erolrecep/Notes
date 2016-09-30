## Download appropriate file for your OsX
 - [Downloads](https://github.com/halide/Halide/releases)

## Add path for **DYLD_LIBRARY_PATH** to your halide/bin
 - export DYLD_LIBRARY_PATH=/path/to/halide/bin/library:${DYLD_LIBRARY_PATH}

## Start to compile each tutorial from [here](http://halide-lang.org/tutorials/tutorial_introduction.html)
 - You will face some problems.
 - Make sure you have [Homebrew](http://brew.sh/) on your system.
 - What you probably will install is these libraries;
 	- brew update & upgrade & cleanup & doctor
 	- brew tap homebrew/boneyard
	- brew install clang-omp
	- brew install libpng
	- brew install libiomp
	- brew install gcc --without-multilib

- Follow [these](https://clang-omp.github.io/) clang-openmp instructions on your Xcode.

**If you need any help please feel free to open issue or emaile me.**