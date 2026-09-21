# introduction
Just my introduction.


Hi My name is Deepak Chopra.
This is my journey to become a software engineer.

#August 20, 2026
Day 1


~/.config/nvim/lua/plugins/theme.lua

```
return {
  {
    "olimorris/onedarkpro.nvim",
    priority = 1000, -- load before everything else
    opts = {
      theme = "onedark",
      colors = {
        -- Absolute black everywhere
        bg = "#000000",
        bg_subtle = "#000000",
        bg_subtle_dark = "#000000",
        cursorline = "#121212", -- faint line so you can still see the cursor row
        black = "#000000",
        statusline_bg = "#000000",
        statusline_bg_bold = "#000000",
        statusline_bg_inactive = "#000000",
        tabline_bg = "#000000",
        visual = "#262B37",
      },
      highlights = {
        Normal = { bg = "#000000" },
        NormalFloat = { bg = "#000000" },
        NormalNC = { bg = "#000000" },
        FloatBorder = { bg = "#000000" },
        WinSeparator = { bg = "#000000" },
        Pmenu = { bg = "#000000" },
        PmenuSel = { bg = "#2C313A" },
        StatusLine = { bg = "#000000" },
        StatusLineNC = { bg = "#000000" },
        TabLine = { bg = "#000000" },
        TabLineFill = { bg = "#000000" },
        TabLineSel = { bg = "#000000" },
        SignColumn = { bg = "#000000" },
        Folded = { bg = "#000000" },
        EndOfBuffer = { bg = "#000000" },
        LineNr = { bg = "#000000" },
        CursorLineNr = { bg = "#000000" },
        VertSplit = { bg = "#000000" },
      },
      options = {
        cursorline = true,
        transparency = false,
        terminal_colors = true,
        highlight_inactive_windows = false,
      },
    },
  },

  -- Tell LazyVim which colorscheme to use
  {
    "LazyVim/LazyVim",
    opts = {
      colorscheme = "onedark",
    },
  },
}
```
