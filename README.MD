#Git commit message with Gitlab issue number

This is simply a script to auto prepend your commit message. 


# Getting started

1. Go to hooks: `cd .git/hooks`
2. Rename file, from `commit-msg.sample` to `commit-msg`
3. Replace `commit-msg` content to script from this repository. 
4. That's it all :)

# Docs

`BRANCHES_TO_SKIP` - branches with default commit message

Sometimes, you should re-init your repository ( `git init` )