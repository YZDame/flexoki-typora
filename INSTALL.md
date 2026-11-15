# Installing Flexoki for Typora

Open Typora and select **Preferences → Appearance → Open Theme Folder**. Extract `flexoki-typora.zip` from [Releases](https://github.com/YZDame/flexoki-typora/releases/latest) and copy the four CSS files and the `flexoki/` folder into the theme folder. The layout should look like this:

```text
themes/
├── flexoki-light.css
├── flexoki-dark.css
├── flexoki-wenkai-light.css
├── flexoki-wenkai-dark.css
└── flexoki/
    └── wenkai.css
```

Restart Typora. Open the **Themes** menu and select a Flexoki theme. On macOS and Windows, you can choose a separate dark theme in **Preferences → Appearance**.

## Fonts

For the Wenkai variants, install [LXGW WenKai Mono or LXGW WenKai](https://github.com/lxgw/LxgwWenKai/releases/latest), then restart Typora. Either font works. If neither is installed, the document uses a system serif font.

The standard themes use Inter when installed. All four variants use the original monospace font stack for Markdown code and source mode.

## Upgrading from a local Wenkai setup

Back up any edited theme files before replacing them. The Wenkai variants include their own font and scrollbar rules. Typora still applies any existing `base.user.css` and theme-specific `*.user.css` overrides after the theme loads.
