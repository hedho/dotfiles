Requirements for Dark mode settings:

sudo pacman -S nwg-look


Neovim clipboard+

# For XDG
doas pacman -S xclip
# For Wayland
doas pacman -S wl-clipboard


# init.lua Config
-- For init.lua (Lua)
vim.opt.clipboard = "unnamedplus"
