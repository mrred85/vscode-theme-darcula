# IntelliJ Darcula theme for Visual Studio Code

Port of IntelliJ Darcula theme for VS Code.

## Syntax
- HTML
- XML
- Apache
- PHP
- Python
- Ruby
- Java
- JavaScript
- TypeScript
- CSS / SCSS
- SQL
- XML
- Markdown
- and so on

### How to install
Download files and place in `~/.vscode/extensions` folder.
Go to `Preferences > Color Theme` and select `Darcula` to load it.

### Indenticator plugin

If you use *Indenticator* plugin set below values in user settings, `settings.json`, to activate gutters colors.

```JSON
"indenticator.color.dark": "#999999",
"indenticator.color.light": "#999999"
```

### TODO Highlight plugin

If you use *TODO Highlight* set below values in user settings, `settings.json` to integrate `TODO:`, `@todo:` and `@TODO:` background colors with this theme.
This setting remove case sensitive check for a better integration with existing code syntaxes.
To color the whole line set `todohighlight.highlightWholeLine` to `true`.

```JSON
"todohighlight.isCaseSensitive": false,
"todohighlight.highlightWholeLine": false,
"todohighlight.keywords": [
    {"text": "TODO:", "color": "#FAFAFA", "backgroundColor": "#629755", "overviewRulerColor": "#629755"},
    {"text": "@TODO:", "color": "#FAFAFA", "backgroundColor": "#629755", "overviewRulerColor": "#629755"},
    {"text": "FIXME:", "color": "#FAFAFA", "backgroundColor": "#CC7832", "overviewRulerColor": "#CC7832"},
    {"text": "@FIXME:", "color": "#FAFAFA", "backgroundColor": "#CC7832", "overviewRulerColor": "#CC7832"},
    {"text": "NOTE:", "color": "#FAFAFA", "backgroundColor": "#6897BB", "overviewRulerColor": "#6897BB"},
    {"text": "@NOTE:", "color": "#FAFAFA", "backgroundColor": "#6897BB", "overviewRulerColor": "#6897BB"},
    {"text": "BUG:", "color": "#FAFAFA", "backgroundColor": "#B64213", "overviewRulerColor": "#B64213"},
    {"text": "@BUG:", "color": "#FAFAFA", "backgroundColor": "#B64213", "overviewRulerColor": "#B64213"},
    {"text": "IMPORTANT:", "color": "#FAFAFA", "backgroundColor": "#CC78D1", "overviewRulerColor": "#CC78D1"},
    {"text": "@IMPORTANT:", "color": "#FAFAFA", "backgroundColor": "#CC78D1", "overviewRulerColor": "#CC78D1"}
]
```

### Git Lens plugin

If you use *Git Lens* set below values in user settings, `settings.json` to integrate with this theme.

```JSON
"gitlens.insiders": true,
"gitlens.theme.annotations.file.gutter.dark.backgroundColor": "rgba(169, 183, 198, 0.075)",
"gitlens.theme.annotations.file.gutter.dark.foregroundColor": "rgb(169, 183, 198)",
"gitlens.theme.annotations.file.gutter.dark.uncommittedForegroundColor": "rgba(67, 158, 184, 0.9)",
"gitlens.theme.annotations.line.trailing.dark.backgroundColor": "",
"gitlens.theme.annotations.line.trailing.dark.foregroundColor": "rgba(67, 158, 184, 0.9)",
"gitlens.theme.lineHighlight.dark.backgroundColor": "rgba(55, 71, 82, 0.6)",
"gitlens.theme.lineHighlight.dark.overviewRulerColor": "rgba(55, 71, 82, 0.6)"
```

Enjoy ;)
