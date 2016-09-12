#Exercise: Google Test Installation

First, you will need to install Google Test on your machine. The code is provided on [GitHub.com/google/googletest](https://github.com/google/googletest). If you are using Windows or an obscure operating system, I suggest setting up a Virtual Machine with a common Linux distribution, such as [Linux Mint](https://www.linuxmint.com/). 

I suggest placing Google Test in a location where other source libraries are placed, such as **/usr/local/include**

Next, go to a different directory (such as one you use to organize your files for this course, or a folder where you store your own code). Clone this repo: [https://github.com/ChicoState/cpp-gtest](https://github.com/ChicoState/cpp-gtest).

Once cloned, edit **Makefile** and find this line:

> GTEST_DIR = /usr/local/include/gtest

and change it to the directory you placed Google Test. Provide the entire path to the directory in Google Test that has the [following folders/files](https://github.com/google/googletest/tree/master/googletest/include/gtest):

> **internal**     
> gtest.h     
> gtest-typed-test.h     
> gtest-test-part.h     
> (and more .h files...)

Once you've edited the file, save it and run the command `Make`

Next, run the command `./RandoTest`

The output should show that one test has been run (and passed). You may give and receive help with classmates, but you will need this setup prepared for future assignments, so make sure you have it working on your computer.

Take a screenshot of this output, convert it to **PDF format** and upload the PDF for the exercise on Blackboard.
