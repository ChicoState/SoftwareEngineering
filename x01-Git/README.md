# Exercise 01 - Accelerated Git Review

For this exercise, you will be asked to complete a very small programming task in C++ and to use command line git controls to manage the project's version control.

If you need help remembering some git commands, you may reference:

* [Git Cheat Sheet](https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf)(PDF)
* [Full git reference](https://git-scm.com/docs)

## Step 1 - Getting your own

The initial project files are available at: https://github.com/ChicoState/GameDie

However, you do not own this repository, so first you need to create your own **fork** of it.

Once you have forked the repo(sitory), you want to work on it on your personal computer. Pull up a terminal (command line) and navigate to the location on your computer where the GameDie project should be stored.

Now, you want to **clone** your fork of the project. To do so, you will need the URI for your fork, which should be something like: https://github.com/ *username* /GameDie.git This creates a local copy of the repository.

Once you have cloned the project, confirm you have the files **GameDie.cpp** and **GameDie.h** within a **GameDie** folder.

## Step 2 - Workflow tree

Now you want to complete the GameDie class. However, since you are adding something new, you should explore your work in a new **branch**. Create a branch called **roll-display**. Make sure you **checkout** that branch so you are working in a separate space, not in your local Master.

To implement the class, you will need to edit **GameDie.cpp** and implement the necessary code for the constructor and for the roll class.

Once you've made the necessary additions, make sure to *stage* the file(s) you edit by **add**ing them to your version control. In addition, make a **commit** along with a commit message that describes succinctly what's new in your revisions.

## Step 3 - Check your work

Before sharing your code with the community, you want to make sure it works first! Create a new file, *main.cpp*, and in it, include GameDie.h and write a short program in int main() that creates a die and rolls it. Compile the program and run it **however, since this file is not part of the GameDie library, do not stage or commit it to the repository**.

Found an error? Go back and fix your code and then stage and commit your changes once you fix them.

## Step 4 - Sharing your work

Once you are confident in your work and have written an appropriate commit message, you can **checkout** and **merge** back into your master branch.

However, before you upload your changes back to the online repositories, you want to make sure that your code is up-to-date. Sync with the "upstream" repository with the command:
`git remote add upstream https://github.com/ChicoState/GameDie.git

To sync with the upstream repo, **fetch upstream**.

Uh oh, are there any conflicts? If so, open the file(s) with conflicts and resolve them. Make sure to remove the markers that look like:
```
<<<<<<< 
=======
>>>>>>>
```

Once you've made all your updates, stage your changes, commit, and push your changes to your (forked) repo.

Visit your fork on GitHub and press the Pull Request button to ask for your changes to be added to the upstream repo. However, when you write a pull request message, make sure to say that it `resolves #` follwed by the number of the **Issue** you have fixed.

Once you've completed your pull request, visit the upstream repo on GitHub and verify that your pull request is shown in the list of pull requests.
