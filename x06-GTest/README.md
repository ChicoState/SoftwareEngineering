#Exercise 06: Google Test Installation

First, you will need to install Google Test on your machine. The code is provided on [GitHub.com/google/googletest](https://github.com/google/googletest).

I suggest placing Google Test in a location where other source libraries are placed, such as **/usr/local/include**

Next, go to a different directory (such as one you use to organize your files for this course, or a folder where you store your own code). Clone this repo: [https://github.com/ChicoState/cpp-gtest](https://github.com/ChicoState/cpp-gtest).

Once cloned, edit **Makefile** find this line:

> GTEST_DIR = /usr/local/include/gtest

and change it to the directory you placed Google Test. Provide the entire path to the directory in Google Test that has the following folders/files:

> **include**     
> **internal**     
> **src**     
> gtest.h     
> gtest-typed-test.h     
> gtest-test-part.h     
> (and more .h files...)

Once you've edited the file, save it and run the command `Make`

Next, run the command `./RandoTest`

The output should show that one test has been run (and passed).

Take a screenshot of this output, convert it to PDF format and upload it as x06 on Blackboard.
