# dotFiles

Uses GNU Stow to manage dotfiles

Install with 

`sudo dnf install stow`

To seed config files run:

`stow -t ~ <machine>` 

To remove existing symlinks run:

`stow -D -t ~ <machine>`
