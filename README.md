# Neovim Config

Personal neovim configuration built on [LazyVim](https://github.com/LazyVim/LazyVim).

## Setup on a new machine

1. Install neovim:

   ```bash
   brew install neovim
   ```

2. Clone this repo:

   ```bash
   # macOS / Linux
   git clone git@github.com:<your-username>/nvim-config.git ~/.config/nvim

   # Windows
   git clone git@github.com:<your-username>/nvim-config.git ~/AppData/Local/nvim
   ```

3. Open neovim — plugins install automatically on first launch:
   ```bash
   nvim
   ```

## Customization

| File                     | Purpose              |
| ------------------------ | -------------------- |
| `lua/config/options.lua` | Editor options       |
| `lua/config/keymaps.lua` | Custom key bindings  |
| `lua/plugins/*.lua`      | Add/override plugins |

## Key Bindings

Leader key is **Space**.

| Shortcut     | Action                 |
| ------------ | ---------------------- |
| `<leader>e`  | File explorer          |
| `<leader>ff` | Find files             |
| `<leader>sg` | Search text in project |
| `<leader>uC` | Preview color themes   |
| `<leader>ft` | Terminal               |
