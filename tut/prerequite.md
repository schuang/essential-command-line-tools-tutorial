# Prerequite

To follow along with the class, you are expected to have completed one of the
following steps prior to attending the class:

1. (easy) Have a Hoffman2 cluster account and are able to log in
2. (work required) Have a POST-compliant computer (e.g. macOS, Linux or Windows with Cygwin,
   either as a phyaical machine or a virtual machine) and have completed the
   installation of all packages as described in "Local installation" below

Some versions of these command-line tools may be available by default on your
computer system. But we want to use newer versions to benefit from the lastest
new features. The following instructions detail how to get to these newer
versions. 

In the followings, the leading `$` is part of the command line prompt, not part
of the command, i.e. you should **not** type it when you run the command on your
computer.


## Hoffman2 Cluster

All of these command-line tools discussed in the class are available on the Hoffman2 cluster. To load
them into your environment, use the following commands.

### vim

To load into your environment:
```
module load vim
```
To check the version:

```
vim --version
```
You should see something similar to:
```
$ vim --version
VIM - Vi IMproved 8.1 (2018 May 18, compiled Jun 17 2020 10:57:58)
Included patches: 1
...
```
(The actual output is much longer, including a list of features.)
Note that some vim features are only availble in version 8.1 or newer.


### pandoc

To load pandoc into your environment:
```
module load pandoc
```

To check the version, e.g.

```
$ pandoc --version
pandoc 2.9.2
Compiled with pandoc-types 1.20, texmath 0.12.0.1, skylighting 0.8.3.2
```

### tmux

To load tmux into your environment:
```
module load tmux
```

To check the version, e.g.
```
$ tmux -V
tmux 2.6
```

### git

```
module load git
```
To check the version, e.g.

```
$ git --version
git version 2.17.1
```

## Local installation

To install these tools on your computer, either your laptop computer or the
supercomputers that you have access to, you can follow these instructions. All
of the tools are free available. After installation, you need to set up the 
environment variable (such as `PATH`), or add them to the shell initialization
file (e.g. `.bashrc`) so that they can be executed when you run the command(s)
in a terminal.

- Install vim
- Install pandoc
- Install tmux
- Install git

On your laptop computer, you might simplify the process by using the package
manager (such as ``apt`` on Ubuntu Linux, or ``brew`` on macOS). However,
the particular version you can get depends on the package manager. Some package
managers may offer only older versions.
