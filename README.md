# Flexoki for Typora

Four Typora themes based on [Steph Ango’s Flexoki palette](https://stephango.com/flexoki). The original light theme by Guido Vicino pairs a warm paper background with ink-black text and cyan links. The dark theme uses Flexoki’s ink background and its brighter syntax colors.

![Original Flexoki Light theme preview](thumbnail.png)

| Theme in Typora | Background | Document font |
| --- | --- | --- |
| Flexoki Light | Paper | Inter |
| Flexoki Dark | Ink | Inter |
| Flexoki Wenkai Light（浅色文楷） | Paper | LXGW WenKai Mono |
| Flexoki Wenkai Dark（深色文楷） | Ink | LXGW WenKai Mono |

The Wenkai themes use LXGW WenKai Mono for Markdown prose, headings, lists and tables. The font stack falls back to LXGW WenKai and then a system serif font. Code keeps the original monospace stack, and math uses Typora’s math fonts. The Wenkai themes hide the sidebar scrollbar and reveal the document scrollbar on hover.

## Install

1. Download and unzip `flexoki-typora.zip` from [Releases](https://github.com/YZDame/flexoki-typora/releases/latest).
2. In Typora, go to **Preferences → Appearance → Open Theme Folder**.
3. Copy all four `flexoki-*.css` files and the `flexoki/` folder into the theme folder. Keep the folder structure so the CSS imports resolve.
4. Restart Typora and select a theme from the **Themes** menu.

Install [LXGW WenKai Mono or LXGW WenKai](https://github.com/lxgw/LxgwWenKai/releases/latest) separately for the Wenkai fonts. Inter and JetBrains Mono Nerd Font are optional for the standard themes. Typora can [use separate light and dark themes](https://support.typora.io/About-Themes/#use-themes-under-light-mode-and-dark-mode) when your system appearance changes.

See [the installation guide](INSTALL.md) for upgrades and [the sample document](EXAMPLE.md) for Markdown examples.

## Credits

- [Guido Vicino](https://github.com/guidovicino/flexoki-typora) created the original Flexoki Light theme.
- [Steph Ango](https://github.com/kepano/flexoki) created the Flexoki color scheme.
- [LXGW](https://github.com/lxgw/LxgwWenKai) maintains LXGW WenKai.

The theme CSS is distributed under the [MIT license](LICENSE).
