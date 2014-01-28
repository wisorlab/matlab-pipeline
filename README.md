Matlab Pipeline
===============

## Description

This module contains nothing more than symbolic links to the other three major modules:
  - <b>Data-Stream-Processing</b> - for working with whole data trains
  - <b>Epoch-Based-Processing</b> - for analyzing segments of data trains
  - <b>Matlab</b> - for general matlab workspace utilities and functions

The purpose of this repository is to make it easier to download, modify and update the Matlab pipeline in a more holistic manner, while still maintaining the modules' independence.

## Usage

For most users in the lab, access to github should be mainly done through the 'GitHub for Windows' client (search Github in the Windows search bar).


#### Command syntax

GitHub also supports a command line syntax. Most general use cases are described down below, with more specific information at the following links.

  - [How the Heck Do I Use Github](http://lifehacker.com/5983680/how-the-heck-do-i-use-github)
  - [Github Tutorial](http://hub.github.com/)
  - [Github Cheatsheet](http://cheat.errtheblog.com/s/git)

######Basic Commands

To download the entirety of this repository simply type

```
git clone https://github.com/wisorlab/matlab-pipeline
```


To make changes to a file in this repository, simply save changes to the file, and then type:

```
git commit -m 'message about what you changed'
git push origin master
```

To update a local version of this repository with any changes made to the files on the server, type:

```
git pull
```

