# iSH

In lamence terms, iSH emulates a Linux shell on your Apple device.
iSH is, IMHO, the best shell for iOS device. There are several SSH apps in the AppStore, but when one has not a machine to log onto or desires to code in their own environment without the need for a network or Wi-Fi, iSH is the answer.

> "iSH is a project to get a Linux shell environment running locally on your iOS device, using a usermode x86 emulator." ~ iSH's description of iSH

## Intro

iSH uses a package manager called `apk`. Common apk commands include:

- `apk add <package name>` installs the package

- `apk del` <package name> deletes it

- `apk --help` loads a help document

- `apk info` shows whats installed within iSH

- `apk fix` repairs or upgrades a package

**For your first time setup,** it behooves to update the Alpine repositories. Therefore, run `apk update`. Next, look at the packages below in the sections that interest your needs. **Don't forget to have fun!**

## Useful Packages

- **[cmatrix]**(https://github.com/abishekvashok/cmatrix)
  - cmatrix runs Matrix on your phone!
  - To install, run: `apk add cmatrix`
  - To se it in action, run: `cmatrix`

## Packages for Software Engineering

- **[git]**(https://git-scm.com/)  
  - `git` is the powerful tool for managing text, including versioning and conflict handling. Created by the powerful Mr. Linus Torvalds.
  - To install, run: `apk add git`
  - To view git's commands, run: `git`
- **[Vim]**(https://www.vim.org/)
  - `vim` is a very powerful text-editor. Though you can manage all your code editing through it, its power is only matched by its requirement to memorize certain commands. And it's better than Emacs (jk)
  - To install, run: `apk add vim`
  - To open it, run: `vim`
  - To exit it, press: `Esc` or `Ctrl` + `C`, write `:q` on the vim command board, and voila, your first full vim interaction that surpasses most!
- **[NodeJS]**()
- **[Tmux]**()
  - A beautiful terminal splitter. Easy as `nano`, powerful as `vim`.
