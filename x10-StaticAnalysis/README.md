#Exercise 10: Introduction to Static Analysis

In this exercise, we will set up and start exploring a static analysis tool packaged with the Clang compiler.

##Downloading Clang and dependencies

###For **OSX**: 

1. You already have Clang and all the other dependencies installed. However, you need to install the *Static Analyzer* by downloading the [packaged build of checker here](http://clang-analyzer.llvm.org/installation). 

2. After fully downloaded, I recommend then extracting the files from the tarball (checker-278.tar.bz2) as a new directory in your `/usr/local` folder, such as `/usr/local/checker`

3. * If you are using sh, ksh, or bash shell, type the command: `export PATH=$PATH:/usr/local/checker-278/bin` but replace `/usr/local/checker-278/bin` with the location of where the static analyzer was installed, followed by `/bin` since that is where the binary (executable) files are

###For 'nix: 

1. You will have to first download and build Clang and LLVM by following [these directions](http://clang.llvm.org/get_started.html#build). 

2. Once you are done, follow the instructions to [build the analyzer from source](http://clang-analyzer.llvm.org/installation#OtherPlatforms).

##Running scan-build

* Navigate to where you stored your *ConnectX* code (from quiz 3)

* To start with a fresh build, first `make clean`

* Run: `scan-build make`

* If you get a *command not found* error, your PATH is not correctly set (see instructions above).

* Once run, it should take a moment to analyze the code. Does it identify any bugs? What does the scan-build output results means?


