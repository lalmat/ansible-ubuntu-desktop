# Ansible Playbook - Lalmat's Gnome Desktop

This playbook install my prefered tools available under Ubuntu.

## Stuff
- [Powerline Fonts](https://github.com/powerline/fonts)
- [ZSH](https://fr.wikipedia.org/wiki/Z_Shell) - as default shell
- [Oh-My-Zsh](https://ohmyz.sh/) - with Agnoster theme by default
- [Gnome Desktop](https://www.gnome.org/) - with dark theme enabled
- [Tilix](https://gnunn1.github.io/tilix-web/) - as default terminal
- [Chromium](https://fr.wikipedia.org/wiki/Chromium)

## Requirements

You need to have theses packages already installed (use apt to install them) :
- git
- ansible
- software-properties-common

## Installation

Just run this command :

`sudo ansible-pull -U https://github.com/lalmat/ansible-ubuntu-desktop.git`

Done.