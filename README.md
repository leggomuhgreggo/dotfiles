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

### yabai & skhd

https://www.notion.so/Yabai-8da3b829872d432fac43181b7ff628fc

## Future Considerations

### Automatically commit and push changes to your repo [#](https://www.chezmoi.io/docs/how-to/#automatically-commit-and-push-changes-to-your-repo)

> chezmoi can automatically commit and push changes to your source directory to your repo. This feature is disabled by default. To enable it, add the following to your config file:

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

https://blog.arkey.fr/2020/04/01/manage_dotfiles_with_chezmoi/

https://cli.github.com/manual/gh_ssh-key_add

```
ssh-keygen -t ed25519 -C "greg.westneat@gmail.com""
gh ssh-key add ~/.ssh/id_ed25519.pub -t "work laptop (21.07)"
```

---

Helpful References

- [Bash Techniques Reference](https://linuxize.com/post/bash-check-if-file-exists/)
-

bootstrap

Installs standard tools and applications w/ Homebrew
Updates macos system config
configures development environment

- Ruby and Node
- VSCode
- Browser
- AWS CLI

setup project environment

<!--
## FEATURE CONSIDERATIONS

### Export macOS system config??
https://apple.stackexchange.com/a/305540
> I wrote some scripts to backup and restore Mac preferences. It does both System and Application preferences.
> You can grab them here: https://github.com/clintmod/mac-preferences-backup



### Remove pre-packaged apps (might be destructive)
```
# sudo rm -rf /Applications/GarageBand.app
# sudo rm -rf /Applications/iMovie.app
# sudo rm -rf /Applications/Keynote.app
# sudo rm -rf /Applications/Numbers.app
# sudo rm -rf /Applications/Pages.app
```

### Improve hostname/computername
```
#
# Sharing - Computer name
#
sudo scutil --set ComputerName "lapta"
sudo scutil --set HostName "lapta"
sudo scutil --set LocalHostName "lapta"
sudo defaults write /Library/Preferences/SystemConfiguration/com.apple.smb.server NetBIOSName -string "lapta"
```



 -->

## VSCode

after brew install

```
# # It turns out that this is packaged with VSCode so no need to install
# code --install-extension <ext>

# We can enable sync like this...
code --sync on

# ...But I can't find an obvious way to establish the GH authentication.
# Needs further investigation. Manual process for now.
# Maybe we can open a "new file" in VSCode with instructions
```
