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
"todohighlight.keywords": [
    {"text": "TODO:", "color": "#FAFAFA", "backgroundColor": "#629755", "overviewRulerColor": "#629755"},
    {"text": "FIXME:", "color": "#FAFAFA", "backgroundColor": "#CC7832", "overviewRulerColor": "#CC7832"},
    {"text": "NOTE:", "color": "#FAFAFA", "backgroundColor": "#6897BB", "overviewRulerColor": "#6897BB"},
    {"text": "BUG:", "color": "#FAFAFA", "backgroundColor": "#B64213", "overviewRulerColor": "#B64213"},
    {"text": "IMPORTANT:", "color": "#FAFAFA", "backgroundColor": "#CC78D1", "overviewRulerColor": "#CC78D1"}
]
```

### TODO Tree plugin

If you use *TODO Tree* set below values in user settings, `settings.json` to integrate "BUG", "HACK", "FIXME", "TODO", "NOTE", "IMPORTANT", "[ ]", "[x]"  background colors with this theme.

```JSON
"todo-tree.general.statusBar": "current file",
"todo-tree.general.tags": ["BUG", "HACK", "FIXME", "TODO", "NOTE", "IMPORTANT", "[ ]", "[x]"],
"todo-tree.highlights.customHighlight": {
    "BUG": {"icon": "bug", "foreground": "#FAFAFA", "background": "#B64213", "rulerColour": "#B64213", "iconColour": "#B64213"},
    "HACK": {"icon": "tools", "foreground": "#FAFAFA", "background": "#9876AA", "rulerColour": "#9876AA", "iconColour": "#9876AA"},
    "FIXME": {"icon": "flame", "foreground": "#FAFAFA", "background": "#CC7832", "rulerColour": "#CC7832", "iconColour": "#CC7832"},
    "TODO": {"icon": "check-circle", "foreground": "#FAFAFA", "background": "#629755", "rulerColour": "#629755", "iconColour": "#629755"},
    "NOTE": {"icon": "pencil", "foreground": "#FAFAFA", "background": "#6897BB", "rulerColour": "#6897BB", "iconColour": "#6897BB"},
    "IMPORTANT": {"icon": "alert", "foreground": "#FAFAFA", "background": "#CC78D1", "rulerColour": "#CC78D1", "iconColour": "#CC78D1"},
    "[ ]": {"icon": "issue-opened", "foreground": "#BBBBBB", "background": "#2F435A"},
    "[x]": {"icon": "issue-closed", "foreground": "#BBBBBB", "background": "#2F435A"}
}
```

To color the whole line (full editor width) set `whole-line`. To color line containing tag set `line`.
```JSON
"todo-tree.highlights.defaultHighlight": {"type": "whole-line"}
```

### Git Lens plugin

If you use *Git Lens* set below values in user settings, `settings.json` to integrate with this theme.

```JSON
"gitlens.insiders": true,
"workbench.colorCustomizations": {
    "gitlens.gutterBackgroundColor": "#3A3A3A70",
    "gitlens.gutterForegroundColor": "#8C8C8C",
    "gitlens.gutterUncommittedForegroundColor": "#629755",
    "gitlens.lineHighlightBackgroundColor": "#38557075",
    "gitlens.lineHighlightOverviewRulerColor": "#38557075",
    "gitlens.trailingLineForegroundColor": "#606366"
}
```

Enjoy ;)
