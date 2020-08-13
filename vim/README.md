# Vim features

## Vim basics

- screen layout
- status line
- Modes
- basic cursor movement


## Vim demos

### Browsing large code base

1. Generate tag file using `ctags`
2. Load the tag file in vim
3. Use `Ctrl-]` to view the target, `Ctrl-t` to back off.

### Working with external program

Count the number of words in file.

Open [this file](data/ucla.txt).
Use `ggVG` to select all texts, followed by `:w !wc -w`.


### git rebase (squashing multiple commits)

See: https://github.com/schuang/git-rebase-example

Use block-visual mode with c(hange) and `Esc` to replace `pick` with `squash`.

### git merge conflict

See: https://github.com/schuang/git-conflict-example

After launching the vimdiff split screen by `git mergetool`, use `:diffg R` to get the REMOTE change, `:diffg B` to get the BASE change,
`:diffg L` to get the LOCAL change. Use `]c` and `[c` to move by changes.


## Remote editing via ssh

On local computer's vim (assuming ssh for a remote server `mg` has been set up):

`:e sftp://mg/demo/` then open the remote file and edit as usual.

Note that Hoffman2 cluster's security does not allow this, but you may do this on
other remote servers.

