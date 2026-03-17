# Dotfiles Repository

This repository contains my personal dotfiles for configuring various tools and environments. The goal is to provide a consistent setup across different machines.

## Structure

The repository is organized as follows:

```
dotfiles
├── bootstrap          # Script to initialize the dotfiles setup
├── shell             # Shell configuration files
│   ├── bashrc        # Bash shell configurations
│   ├── zshrc         # Zsh shell configurations
│   └── profile       # Login shell configurations
├── git               # Git configuration files
│   └── gitconfig     # Git settings and preferences
├── .gitignore        # Files to ignore in the Git repository
└── README.md         # Project documentation
```

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone <repository-url> ~/.dotfiles
   ```

2. **Run the Bootstrap Script**:
   Navigate to the dotfiles directory and run the bootstrap script to create symlinks for the configuration files:
   ```bash
   cd ~/.dotfiles
   bash bootstrap
   ```

3. **Customize Your Configuration**:
   Edit the configuration files in the `shell`, `git`, and `config` directories to suit your preferences.

## Usage

After running the bootstrap script, your environment will be set up with the specified configurations. You can modify the dotfiles as needed, and re-run the bootstrap script if you make changes to the file locations.

## Contributing

Feel free to fork the repository and submit pull requests for any improvements or additional configurations you think would be beneficial.