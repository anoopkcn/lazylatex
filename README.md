# lazylatex
Because LaTeX shouldnt be boring! :tropical_fish:
lazylatex is aLaTeX package inspired by sphinx-rtd-theme. Build with tcolorbox, minted, tikz, etc,. Some of the elements are also simulating elements from the tcolorbox manual. 
# Updates 2022-April
**Breaking changes:**
- IMPORTANT: `minted` package is no longer used for code blocks(Confilics with different python environments and users were having problems installing. Problems with `shell-escape` on xelatex)
- `listings` package is used to handle code block with added github-light-theme
- Nmae changes:
  - `sidebar` -> `lsidebar`
  - `lazytable` -> `ltable`
  
## Some Features
ℹ️ IMPORTANT! **Please see `docs/example.pdf` and the source `docs/example.tex` for a list of all features and how to use them.** The following is a few screenshorts from the `docs/example.pdf` document. 
### Inline Markup
![Inline-Markup](./docs/img/inline_markup.png)
### Code Blocks
![code-blocks](./docs/img/code_blocks_new.png)
### Admonitions
![admonitions](./docs/img/admonitions.png)
### Sidebar
![side-bar](./docs/img/side_bar.png)
### Field List
![field-list](./docs/img/flist.png)
### Tables
![table-1](./docs/img/table_1.png)
![table-2](./docs/img/table_2.png)
## Please report issues!!
