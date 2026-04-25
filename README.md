# vitesse.nvim

a minimal light theme for neovim

## install

```lua
-- lazy.nvim
{
  "k1tyoodev/vitesse.nvim",
  lazy = false,
  priority = 1000,
  config = function()
    vim.cmd.colorscheme("vitesse")
  end,
}
```

## options

```lua
require("vitesse").setup({
  transparent = false,
})
```

## supported plugins

- [blink.cmp](https://github.com/Saghen/blink.cmp)
- [flash.nvim](https://github.com/folke/flash.nvim)
- [gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim)
- [mini.diff](https://github.com/nvim-mini/mini.diff)
- [mini.statusline](https://github.com/nvim-mini/mini.statusline)
- [oil.nvim](https://github.com/stevearc/oil.nvim)
- [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim)
