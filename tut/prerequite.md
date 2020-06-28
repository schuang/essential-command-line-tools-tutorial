# Prerequite

To follow along with the class, you are expected to have completed one of the
following steps prior to attending the class:

1. (easy) Have a Hoffman2 cluster account and are able to log in.  For more
   details, see: [Using the packages on Hoffman2 cluster](pre-h2.md)
2. (work required) Have a POST-compliant computer (e.g. macOS, Linux or Windows
   with Cygwin, either as a phyaical machine or a virtual machine) and have
   completed the installation of all packages. For more details, see:
   [Installation on Local computer](pre-local-install.md)

Some versions of these command-line tools may be available by default on your
computer system. But we want to use newer versions to benefit from the lastest
new features. The following instructions detail how to get to these newer
versions. 

In the followings, the leading `$` is part of the command line prompt, not part
of the command, i.e. you should **not** type it when you run the command on your
computer.



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
