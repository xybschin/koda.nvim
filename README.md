# chiefdog.nvim

A minimalist, colorscheme for Neovim.

## Installation

Using [lazy.nvim](https://github.com/folke/lazy.nvim):

```lua
{
  "oskarnurm/chiefdog.nvim",
  lazy = false, -- make sure we load this during startup if it is your main colorscheme
  priority = 1000, -- make sure to load this before all the other start plugins
  config = function()
    vim.cmd("colorscheme chiefdog")
  end,
}
```

vim.pack

```lua
vim.pack.add({
  "https://github.com/oskarnurm/chiefdog.nvim",
})

vim.cmd("colorscheme chiefdog")
```
