# alkhioz.Dots

My personal dotfiles repo.  
This includes a simple Neovim setup using `init.lua` + `lazy.nvim`.

## Neovim Setup

### Install language servers
Required for LSP and autocompletion:

```bash
brew install lua-language-server
npm install -g pyright
npm install -g typescript typescript-language-server
```


```bash
mkdir -p ~/.config/nvim
cp init.lua ~/.config/nvim/init.lua
# or
# ln -s $(pwd)/init.lua ~/.config/nvim/init.lua
```
