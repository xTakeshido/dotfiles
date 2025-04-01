# Terminal Configs 🖥️

My personalized terminal setup with Oh My Posh theming and Bash customizations.

![Terminal Preview](./prompt.png)

## Quick Install
```bash
git clone https://github.com/xTakeshido/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
stow bash oh-my-posh
source ~/.bashrc

## Customization
Edit bash/.bashrc for colors/aliases
Replace theme file in oh-my-posh/themes/

Ensure this line exists in .bashrc:
```bash 
eval "$(oh-my-posh init bash --config ~/.poshthemes/your-theme.omp.json)"

## Backup First!
```bash
mv ~/.bashrc ~/.bashrc.bak  # Backup existing
