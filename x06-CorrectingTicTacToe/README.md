#Exercise 06: Correcting Tic Tac Toe

For this exercise, you will continue with the code you have previously written for TicTacToeBoard. However, we want to store it in a new repo so first do the following:

* Go to GitHub, log in, and create a New Repo. Make it Public, do not add either a .gitignore or README, and name it *x06-FullName* but replace FullName with your name (no spaces).

* Launch the Testing VM and navigate into the TicTacToeBoard folder

* `git remote rm upstream`

* `git remote add upstream https://github.com/YourUsername/x06-FullName.git` *(but replace YourUsername and FullName, accordingly)*

## Correcting Tic Tac Toe

No matter which group ("buggy" or "correct") you were in previously, your job for this exercise is to finish a **correct implementation** for the TicTacToeBoard class (as the functions are documented) as well as **write sufficient tests to check if TicTacToeBoard implementations are correct or incorrect**.

For some insight into your previous work, you have been provided with two files:

* **test.txt** - this is the results of your tests run against a *correct* solution, showing which tests passed and which tests failed. If any tests failed, that means that particular test is *not* consistent with the expected functionality

* **gcov.txt** - this is the summary of the branch coverage of *your* tests run against a *correct* solution. To generate this summary, the command `gcov -fb TicTacToeBoard.cpp` but with the correct solution .cpp file replacing your own .cpp file. The summary includes coverage information for each function. However, function names are "mangled" such as: `_ZN14TicTacToeBoard10clearBoardEv`. You can identify the *class name* as well as the *function name* in addition to the "mangled" characters.

## Turning in your work

Your work is due by the end of the class period. Make sure that `make` will build your project without errors (warnings are okay).

Use git to add and commit both your implementation and tests.

After committing, push your work to the new upstream:

`git push upstream master`

Then, turn in your work by emailing the upstream URL to kbuffardi@csuchico.edu 
