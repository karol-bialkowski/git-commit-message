# Git commit message with Gitlab issue number

This is simply a script to auto prepend your commit message with issue number:

**aa/1234-name-of-branch** -> "#1234 added new feature" or 

**aa/14-name-of-branch** -> "#14 added new feature" or 

**aa/123456-name-of-branch** -> "#123456 added new feature"

# Features

- commit by your favorite IDE
- commit by command line
- manually skip autocomplete by `--no-verify` 
- auto skip on branches: master, test, dev,live or beta
- supporting 1 or 9 numbers in branch name

# Getting started

1. Go to hooks: `cd .git/hooks`
2. Rename file, from `commit-msg.sample` to `commit-msg`. Make this file executable.
3. Replace `commit-msg` content to script from this repository. 
4. That's it all :)

# Docs

`BRANCHES_TO_SKIP` - branches with default commit message

Sometimes, you should re-init your repository ( `git init` ). 

You can disable run hooks by unselecting option PHPStorm option "Run git hooks" or by `git commit --no-verify` 

# How to use

https://vimeo.com/424898839

# Source

https://medium.com/@nicklee1/prepending-your-git-commit-messages-with-user-story-ids-3bfea00eab5a
