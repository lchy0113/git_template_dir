# git_template_dir
=====

# GIT COMMIT Message.

## how to setting
```
ln -s ($PWD).gitmessage.txt ~/.gitmessage.txt
git config --global commit.template ~/.gitmessage.txt
```

## check setting
```
git config --global --list
```


## change default "Change-Id" select in command 

```bash
git config --global gerrit.createchangeid true

// check
git config --bool --get gerrit.createChangeId
```

```
