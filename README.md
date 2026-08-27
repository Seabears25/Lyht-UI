# LYHT UI

A plain-CSS dashboard and website framework. No build step, no components to
import — just classes on top of a token system.

## View it live

Push this repo to GitHub, then in **Settings → Pages** set the source to the
`main` branch, root folder. The showcase will be live at
`https://<your-username>.github.io/<repo-name>/`.

## Files

- `lyht-ui.css` — the framework itself
- `index.html` — the showcase page: a working dashboard built with LYHT UI's
  own classes, a live "theme lab" for editing the color tokens in the browser,
  and a component reference (buttons, badges, forms, nav, feedback, layout)

## Use it in your own project

```html
<link rel="stylesheet" href="lyht-ui.css">
```

Then build with the primitives: `.dash` for grids, `.stack` for vertical
rhythm, `.split` for two-column layout, `.card` / `.stat` / `.table` for
content, `.btn` / `.badge` / `.alert` for the four semantic states
(default, primary, success, warning, danger). Toggle dark mode by setting
`data-theme="dark"` on `<html>` — every token remaps automatically.
