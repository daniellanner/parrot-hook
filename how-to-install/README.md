# How to install

This README explains how to set up the script. Note that this text does not appear in the summary.

## Introduction

In your local git repository locate the folder `.git/hooks/`. Copy the `pre-commit` and `post-commit` from this repository into the hooks folder.

## git hooks

git hooks are written as sh scripts and executed in your local repository at the given commands. In this case the pre-commit generates a new `README.md` if *any* `README.md` file was changed. The post-commit adds the newly generated `README.md` to your current commit.