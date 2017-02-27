#Exercise 05: Covering TicTacToe

This exercise continues from the previous exercise, *Testing TicTacToe*.

On GitHub, create a new GitHub repo and name it **x05**

Boot up your Testing VM and make a copy of the work you did for the previous lab. For example, if your previous exercise is in a subfolder called x04, then do the following commands:

```
cp -r x04 x05
cd x05
git remote rm upstream
git remote add upstream https://github.com/YOURUSERNAME/x05.git
```

This usually isn't how related repos are handled, but we are going to store future work in the x05 repo for the course's purposes.

##Evaluating Coverage

To find the coverage of your tests, first, build the project:

`make`

If there are any compilation errors, the project will not build. Fix the errors and build again. Once it builds, execute the test runner:

`./TicTacToeBoardTest`

Then, run the [gcov coverage tool](https://gcc.gnu.org/onlinedocs/gcc/Gcov.html):

`gcov TicTacToeBoard.cpp`

This will tell you the overall percentage of lines run by your tests. To see *which* lines have been covered, open up the coverage report:

`vim TicTacToeBoard.cpp.gcov`
