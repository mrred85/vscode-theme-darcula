# IntelliJ Darcula theme for Visual Studio Code

Port of IntelliJ Darcula theme for VS Code.

## Syntax
- HTML
- XML
- Apache
- PHP
- Python
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

```JSON
"todohighlight.isCaseSensitive": false,
"todohighlight.keywords": [
    {"text": "TODO:", "color": "#FFF", "backgroundColor": "#629755", "overviewRulerColor": "#629755"},
    {"text": "@todo:", "color": "#FFF", "backgroundColor": "#629755", "overviewRulerColor": "#629755"},
    {"text": "FIXME:", "color": "#FFF", "backgroundColor": "#CC7832", "overviewRulerColor": "#CC7832"},
    {"text": "@fixme:", "color": "#FFF", "backgroundColor": "#CC7832", "overviewRulerColor": "#CC7832"},
    {"text": "NOTE:", "color": "#FFF", "backgroundColor": "#6897BB", "overviewRulerColor": "#6897BB"},
    {"text": "@note:", "color": "#FFF", "backgroundColor": "#6897BB", "overviewRulerColor": "#6897BB"},
    {"text": "BUG:", "color": "#FFF", "backgroundColor": "#B64213", "overviewRulerColor": "#B64213"},
    {"text": "@bug:", "color": "#FFF", "backgroundColor": "#B64213", "overviewRulerColor": "#B64213"},
    {"text": "IMPORTANT:", "color": "#FFF", "backgroundColor": "#CC78D1", "overviewRulerColor": "#CC78D1"},
    {"text": "@important:", "color": "#FFF", "backgroundColor": "#CC78D1", "overviewRulerColor": "#CC78D1"}
]
```

Enjoy ;)
