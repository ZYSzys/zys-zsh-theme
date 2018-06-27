# zys.zsh-theme
A ZSH theme similar with [agnoster.zsh-theme](https://github.com/agnoster/agnoster-zsh-theme) but just more time display.

A ZSH theme optimized for people who use:

- Solarized
- Git
- Unicode-compatible fonts and terminals (I use iTerm2 + Menlo)

For Mac users, I highly recommend iTerm 2 + Solarized Dark.

## Preinstallation
- [Powerline-patched font](https://github.com/Lokaltog/powerline-fonts)

To test if your terminal and font support it, check that all the necessary characters are supported by copying the following command to your terminal: `echo "\ue0b0 \u00b1 \ue0a0 \u27a6 \u2718 \u26a1 \u2699"`. The result should look like this:

![Character Example](/font.png)

## What does it show?

- If the previous command failed (✘)
- User @ Hostname (if user is not DEFAULT_USER, which can then be set in your profile)
- Git status
  - Branch () or detached head (➦)
  - Current branch / SHA1 in detached head state
  - Dirty working directory (±, color change)
- Working directory
- Elevated (root) privileges (⚡)

![Screenshot](/screenshot.png)

## Thanks
* [agnoster.zsh-theme](https://github.com/agnoster/agnoster-zsh-theme)

## License
[MIT](https://github.com/ZYSzys/zys-zsh-theme/blob/master/LICENSE).
