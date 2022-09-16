# AstroNvim User Configuration

My personal AstroNvim user configuration

## Installation

- Install AstroNvim

```sh
git clone https://github.com/AstroNvim/AstroNvim.git ~/.config/nvim
```

- Install these user settings

```sh
git clone https://github.com/RealAtix/astronvim-config.git ~/.config/nvim/lua/user
```

- Initialize AstroVim

```sh
nvim --headless -c 'autocmd User PackerComplete quitall' -c 'PackerSync'
```
