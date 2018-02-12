# AdituV/dotfiles

Various configuration files for my OS X setup

## Neovim

Requires [Vundle][vundle] to install the plugins.  [Intero][intero] requires
`stack` [haskell-lang.org][haskell-stack] to be installed.

After copying the config across, run `:VundleInstall` to grab all the plugins
then restart Neovim.

You will also need to get a patched font for both Neovim and the zsh theme:
I use [Menlo][menlo].

## zsh

I use [oh-my-zsh][oh-my-zsh].  Follow its installation instructions then copy
the .zshrc over the top of the one it installs.

To use the special symbols in the powerlevel9k, you will need a powerline font
and extra fallback fonts for the further symbols.  As above, I use
[Menlo][menlo] for the main font, and [awesome-terminal-fonts][atf] for the
fallback fonts.  See the [OS X installation instructions][atf-install].

Remember to change `DEFAULT_USER` to the name of your user account, too.

[atf]: https://github.com/gabrielelana/awesome-terminal-fonts
[atf-install]: https://github.com/gabrielelana/awesome-terminal-fonts/wiki/OS-X
[haskell-stack]: https://haskell-lang.org/get-started/osx
[intero]: https://github.com/parsonsmatt/intero-neovim
[menlo]: https://github.com/abertsch/Menlo-for-Powerline
[oh-my-zsh]: https://github.com/robbyrussell/oh-my-zsh
[vundle]: https://github.com/VundleVim/Vundle.vim


