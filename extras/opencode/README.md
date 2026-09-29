# OpenCode themes

V2 native themes (`base` + single mode per file, standalone). Hue steps are
uniform by design: each step holds the exact bamboo palette hex, so every
`$hue.<name>.<step>` reference resolves to the true color.

| File | Bamboo variant | Mode |
| --- | --- | --- |
| `bamboo.json` | `vulgaris` | `dark` |
| `bamboo_multiplex.json` | `multiplex` | `dark` |
| `bamboo_light.json` | `light` | `light` |

To use, copy the file(s) into your themes directory and select the theme:

```sh
mkdir -p ~/.config/opencode/themes
cp extras/opencode/bamboo.json ~/.config/opencode/themes/
```

Then set `theme.name` to `bamboo` in `cli.json` (or pick it with `/themes`)
and restart the TUI.
