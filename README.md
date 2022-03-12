# Dotfiles manager

Requires [chezmoi](https://www.chezmoi.io) to import the dotfiles on new machines/users

## Usage
To initialize the repo on a new machine
```bash
chezmoi init --apply Kumark95
```

To pull the latest changes
```bash
chezmoi update -v
```

To add new files
```bash
chezmoi add <file>
```

To edit and commit the changes
```bash
chezmoi edit <file>
chezmoi diff
chezmoi apply -v
```
