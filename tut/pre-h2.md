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
