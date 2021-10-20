# Obsidian's Wyrd

And amazing. So I'm making this theme weird, too.

Wyrd is a purple-hued, low-contrast theme for [Obsidian.md](https://obsidian.md).

## Features

- Visual balance between light and dark modes!
- Custom font selection `@import`ed through Google Fonts!
- All fonts scale with the current `--editor-font-size`!
  - Including headings (!!)

### Planned Features

- [ ] Snippet to make font selection locally available for offline use
  - Necessary, as some fonts from google contain 50+ variations, and would make the CSS file absurdly large
- [ ] Style Settings compatability
- [ ] 

## Notes

- Long headings don't have the gradient pattern repeated
  - I'm contemplating fixing this, though doing so will require making the gradient more dynamically sized

## Roadmap

### Note Content

- Text styling
  - Basic
    - [x] `**Bold**` styling
    - [x] `_Italic_` styling
    - [x] `~~Strikethrough~~` (ST) styling
    - [ ] `==Highlight==` (HL) styling
  - Repeating
    - [ ] `_*Italic + Italic*_` == ?
    - [ ] `*_Bold + Bold_*` == ?
    - [-] ~~`====HL + HL====` == ?~~ Does not render as dual highlights due to parsing
    - [-] ~~`~~~~ST + ST====` == ?~~ Renders as code block until second line of `~~~~` is reached by parser
  - Expressive
    - Bold + ...
      - [?] `**_Bold + Italic_**` == Bold & Italic (Keep? Distinguish?)
      - [ ] `**==Bold + HL==**` == ?
      - [ ] `**~~Bold + ST~~**` == ?
    - Italic + ...
      - [?] `_**Italic + Bold**_` == Bold & Italic (Keep? Distinguish?)
      - [ ] `_==Italic + HL==_` == ?
      - [ ] `_~~Italic + ST~~_` == ?
    - Highlight + ...
      - [ ] `==_HL + Italic_==` == ?
      - [ ] `==**HL + Bold**==` == ?
      - [ ] `==~~HL + ST~~==` == ?
    - Strikethrough + ...
      - [ ] `~~==ST + Italic==~~` == ?
      - [ ] `~~==ST + Bold==~~` == ?
      - [ ] `~~==ST + HL==~~` == ?
- Lists
  - [x] Unordered
  - [x] Ordered
  - [ ] Task lists
- Link styling
  - [x] Internal link
  - [x] Unresolved internal link
  - [x] External link
  - [ ] Footnotes
- Tables
  - [ ] Alternating rows
  - [ ] Row/cell highlighting
- Code
  - [ ] Code blocks
  - [ ] Inline code
  - [ ] Syntax highlighting
- Embeds
  - [ ] Notes
  - [ ] Images
    - Cap size?
  - [ ] PDFs

### UI

- Sidebars
  - [ ] Leaf containers
- Titles
  - [ ] App title bar
  - [ ] Note title bars
- Panes
- Status bar
- Graph view
- Settings window

### Plugin Support

- [ ] Style Settings
- ???

## Known Issues

- [x] Links disappear in headings
  - [ ] Heading links are not distinct
- [ ] List spacing feels a bit _too_ tight in preview mode
