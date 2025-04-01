# Dotfiles Requirements

## Core Dependencies
1. **Oh My Posh**  
   Terminal theming engine  
   ```bash
   brew install oh-my-posh  # macOS/Linux/WSL
   ```

2. **Nerd Font**  
   Iconic font for prompt symbols  
   - Install: [Download from nerd-fonts.com](https://www.nerdfonts.com/font-downloads)  
   - Configure in terminal settings

## Recommended Tools
3. **GNU Stow**  
   Symlink manager  
   ```bash
   sudo apt install stow    # Debian/Ubuntu
   brew install stow       # macOS
   ```

4. **Git**  
   Version control  
   ```bash
   sudo apt install git    # Linux
   brew install git       # macOS
   ```

## Verification
```bash
# Check installations
oh-my-posh --version  # Should return version ≥8.0
stow --version        # Should return GNU Stow version
echo $SHELL           # Should show /bin/bash or similar
```

## Font Setup
- Select "CaskaydiaCove Nerd Font" or other Nerd Font in terminal settings  
- Restart terminal after font installation
