# chiefdog.nvim
A minimalistic theme for Neovim, written in Lua.

There are others like this. I just wanted to make something specifically for myself.

Supports a few plugins, may add support for more later if needed. 

## Example:
<img width="1487" height="916" alt="image" src="https://github.com/user-attachments/assets/5c118fcf-b30a-4606-8200-fdfaba4d3993" />

> [!NOTE]
> Developed on a 14" XDR retina display, your mileage may vary depending on the quality and brightness of the screen you use. 

## Installation:

**lazy.nvim**:

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

**vim.pack**:

```lua
vim.pack.add({
  "https://github.com/oskarnurm/chiefdog.nvim",
})

vim.cmd("colorscheme chiefdog")
```

## Plugin support:
- [blink.cmp](https://github.com/saghen/blink.cmp)
- [gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim)
- [mini.pick](https://github.com/nvim-mini/mini.pick)
- [oil.nvim](https://github.com/stevearc/oil.nvim)
- [snacks.nvim](https://github.com/folke/snacks.nvim)

## Alternatives:
- [vim-dark](https://github.com/thiago-negri/vim-dark)
