# tr100.vim
a vim/neovim scheme based on the tr100 aesthetic
![alt text](https://github.com/l-snq/tr100.vim/blob/main/img/screenshot.png)

Based off of [this](https://x.com/usgraphics/status/1977780917059137735/photo/1) screenshot post from US graphics.

## Installation:

Download via your favourite package manager, for example w/ Lazy: 
```
{
  'l-snq/tr100.vim',
  lazy = false,
  priority = 1000,
  config = function()
    vim.cmd('colorscheme tr100')
  end,
}
```

With packer: 
```
use {
  'yourusername/tr100.vim',
  config = function()
    vim.cmd('colorscheme tr100')
  end
}
```
