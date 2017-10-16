
**Prerequisites**

- Python 2 or Python 3
- SVN (should be installed by default on most operating systems?)

**Purpose**

Download subdirectories (only) from a github repository.

It is only intented to work for subdirectories.

**Installation**

Find location of git binary with `which git`. 

The result should look like `/usr/local/bin/git`.

Place `git-download` into the folder where git is located.

**Usage Example**

Locate the subdirectory (you want to download) on github. Copy link. 

Final command should look like the following (e.g. for linalg subdirectory of numpy)

```
git download https://github.com/numpy/numpy/tree/master/numpy/linalg
```
