# Week 0

## To-Do

- [x] For Mac and Linux: Install Homebrew
- [x] Install Git
- [x] Getting familiar with CLI
- [x] Sign in to GitHub
- [x] Git CLI
- [x] Sign in to [repl.it](https://repl.it)


### Install Homebrew

- Mac: 
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

- Linux:
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
test -d ~/.linuxbrew && eval $(~/.linuxbrew/bin/brew shellenv)
test -d /home/linuxbrew/.linuxbrew && eval $(/home/linuxbrew/.linuxbrew/bin/brew shellenv)
test -r ~/.profile && echo "eval \$($(brew --prefix)/bin/brew shellenv)" >>~/.profile
echo "eval \$($(brew --prefix)/bin/brew shellenv)" >>~/.profile
```

### Install Git

- Windows: [Click Here](https://git-scm.com/download/win) and download intaller file. Then install it.
- Mac/Linux:
```bash
brew install git
```

### Common CLI

>>> You have to install Git first

- Checking current directory: `pwd`
- Creating directory: `mkdir <directory-name>`
- Changing directory: `cd <directory-name>`
- Creating file: `touch <file-name>`
- Opening file: `open <file-name>` (Mac)
- Deleting file: `rm <file-name>`
- Deleting directory: `rm -rf <directory-name>`
- Showing all files and folder (no details, excluding hidden): `ls`
- Showing all files and folder (no details, including hidden): `ls -a`
- Showing all files and folder (details, excluding hidden): `ls -l`
- Showing all files and folder (details, including hidden): `ls -la`
- Showing folder and sub-folder: `tree` (Max/Linux) ~ need `brew install tree` once

### Signing into GitHub

- Go to [GitHub](https://github.com) and create an account
- Log in to the account

### Git CLI

**Do onece in a machine:**
- Config username: `git config --global user.name "<github-username-here>"`
- Config email: `git config --global user.email "<github-email-here>"`

**For repo and folder**
- Initial git to a folder: `git init`
- Adding files to Git: `git add <file-name>`
- Adding all modified file to git: `git add -A`
- Preparing file to upload: `git commit -m "<messege-for-your-good>"`
- Connecting remote repo to folder (once): `git remote add <url-name-you-want> <repo-url>`
- Uploading files to remote: `git push -u <url-name-you-set> <branch-name>`

### repl.it

Please join week_1 for details.

### Colorful Terminal

- Only Mac/Linux: 
```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
chsh -s /bin/zsh
```