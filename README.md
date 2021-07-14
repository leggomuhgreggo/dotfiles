# Dotfiles

```
sh -c "$(curl -fsLS git.io/chezmoi)" -- init --apply leggomuhgreggo
```

I started by following the instructions in this [blog post](https://www.moncefbelyamani.com/automating-the-setup-of-a-new-mac-with-all-your-apps-preferences-and-development-tools/).

## Currently Supports

### Chezmoi Data

Will prompt for email

### Git Config

Accepts email

### Brewfile

[Brew Bundle Brewfile Tips](https://gist.github.com/ChristopherA/a579274536aab36ea9966f301ff14f3f)

## Future Considerations

### Automatically commit and push changes to your repo [#](https://www.chezmoi.io/docs/how-to/#automatically-commit-and-push-changes-to-your-repo)

> chezmoi can automatically commit and push changes to your source directory to your repo. This feature is disabled by default. To enable it, add the following to your config file:

<!--
TODO:

- setup node
- ssh
- aliases
- VSCode

Aliases
https://github.com/renemarc/dotfiles/blob/master/dot_bash_aliases

macos
https://github.com/twpayne/dotfiles/blob/master/run_once_after_90-configure-darwin.sh.tmpl
https://github.com/mathiasbynens/dotfiles/blob/main/.macos
https://github.com/paulmillr/dotfiles/blob/master/etc/macos-settings.sh




# Reference Implementations
https://github.com/renemarc/dotfiles
https://github.com/mathiasbynens/dotfiles
https://github.com/twpayne/dotfiles/
https://github.com/Amar1729/dotfiles

# Apps to try
https://github.com/asdf-vm/asdf
https://github.com/koekeishiya/yabai



-->

https://support.1password.com/command-line-getting-started/#learn-more

```
op get totp [item query]



```

ZShell and Oh-my-zshell

https://ohmyz.sh/#install
https://github.com/ohmyzsh/ohmyzsh/wiki

# Vim

~/.vimrc
https://github.com/VundleVim/Vundle.vim
macvim

https://www.nerdfonts.com/font-downloads

---

### ssh [TODO]

https://cli.github.com/manual/gh_ssh-key_add

```
ssh-keygen -t ed25519 -C "greg.westneat@gmail.com""
gh ssh-key add ~/.ssh/id_ed25519.pub -t "work laptop (21.07)"
```

## asdf

https://asdf-vm.com/#/core-configuration
https://github.com/asdf-vm/asdf-nodejs#default-npm-packages

- brew install gpg
- brew install gawk
- asdf plugin add nodejs

---

Helpful References

- [Bash Techniques Reference](https://linuxize.com/post/bash-check-if-file-exists/)
-
