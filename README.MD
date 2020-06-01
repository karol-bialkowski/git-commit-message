# Git commit message with Gitlab issue number

This is simply a script to auto prepend your commit message with issue number:

**aa/1234-name-of-branch** -> "#1234 added new feature"

# Features

- commit by your favorite IDE
- commit by command line
- skip autocomplete by `--no-verify` 

# Getting started

1. Go to hooks: `cd .git/hooks`
2. Rename file, from `commit-msg.sample` to `commit-msg`
3. Replace `commit-msg` content to script from this repository. 
4. That's it all :)

# Docs

`BRANCHES_TO_SKIP` - branches with default commit message

Sometimes, you should re-init your repository ( `git init` )

You can disable run hooks by unselecting option PHPStorm option "Run git hooks" or by `git commit --no-verify` 

# How to use

https://vimeo.com/424898839