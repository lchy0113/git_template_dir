# git_template_dir
=====

# git config 

// git config 를 적용

```bash
ln -s $(PWD)/.gitconfig ~/.gitconfig
```

# git commit message.

## how to setting

```bash
ln -s ($PWD).gitmessage.txt ~/.gitmessage.txt
git config --global commit.template ~/.gitmessage.txt
```

## check setting

```bash
git config --global --list
```

## change default "Change-Id" select in command 

```bash
git config --global gerrit.createchangeid true

// check
git config --bool --get gerrit.createChangeId
```

