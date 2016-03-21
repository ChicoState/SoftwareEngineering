#Exercise 08: Branch Coverage Introduction

This exercise continues from q02 Unit Testing
* Open the local directory where you cloned your fork of [Minefield](https://github.com/ChicoState/minefield).

* Create (and checkout) a new Git branch and call it `branchcov`

* Get the updates from the (upstream) Minefield by first setting upstream: `git branch --set-upstream-to=origin/master branchcov` and then pulling the updates

* Look over the unit tests for the `revealAdjacent()` function and see what cases have been handled. Review the function within `Field.cpp` if you want to see how the solution is implemented.

* Next, `make` the project and run the tests using `make test`. Do the tests pass? How confident are you in the solution?

* Let's look at how comprehensively we've tested the function. Run the command: `gcov -b Field.cpp`. Note that the **-b** option is short for: **--branch-probabilities**. Within the results you should find:

```
File 'Field.cpp'
Lines executed: 
Branches executed:
Taken at least once:
No calls
Field.cpp:creating 'Field.cpp.gcov'
```

* This summarizes the whole file, but we want to concentrate specifically on `revealAdjacent()` so open up **Field.cpp.gcov** in your editor. Find that function and look at the gcov analysis of it. You should see some lines that look like:

```
branch 0 taken 99%
```

* What does the branch number correspond to? What do you think "taken" percentage refers to?

* **STOP HERE AND WAIT FOR DISCUSSION**

- - -

* Now that you have a better understanding of how to read the results of gcov's branch coverage, continue testing until you have tested all the branches for revealAdjacent(). Upload your Field.cpp.gcov on Blackboard for x08.
