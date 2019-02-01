[![Build Status](https://travis-ci.org/NYUGP17/Assignment_1.svg?branch=master)](https://travis-ci.org/NYUGP17/Assignment_1)
# Assignment 1

This repository contains the viewer code and data files you'll need for parts
2-5 of assignment 1.

## Getting Started
To begin, follow the link from Assitant to create the repository in this organization.

Next, please refer to the [General Rules and Instructions](https://github.com/danielepanozzo/gp/raw/master/guidelines.pdf)
handout for instructions on installing LIBIGL and its dependencies.

## Building and Completing the Assignment
You
should be able to build the viewer code:
```
mkdir build && cd build && cmake ..
make
```
Please report any problems you run into on this repository's Issues tab on
GitHub.

When the build completes successfully, begin implementing the missing blocks in
src/main.cpp as described by the assignment PDF.

## Submitting
When you finish the assignment, you will submit it by pushing it to a the
repository on our organization.

1. Follow the link sent out by Assistant
2. Push your code to the repository:
```
git push https://github.com/NYUGeometricModeling/Geometric_Modeling_Assignment1_USER
```

## Travis-CI
Every submission must build on Linux before it can be graded/considered
complete. To check this, you will use Travis-CI, a tool for automatically
rebuilding your code each time you push it to GitHub.

We've already configured Travis-CI for this repository: Travis-CI works by
running the script in '.travis.yml' each time new commits are pushed. You will
need to follow the [getting started
instructions](https://travis-ci.com/getting_started) to sign into Travis-CI with
your GitHub account, grant it permission, and enable builds on your private
assignment repositories. Finally, you need to change the URL at the top of
this README.md file to point to your repository's status.
