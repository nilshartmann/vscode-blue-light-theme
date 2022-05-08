# VS Code theme "blue-light"

This is a light theme for Visual Studio Code with mostly
blue colors.

I tried to keep it very simple in order to remove and avoid distractions as much as possbible:

- use only a few colors, both for UI and syntax coloring
- do _not_ use red colors for other things than errors

_Note_: I only tested language support for Java, JavaScript/TypeScript, React, CSS/SASS. There might be "strange" colors in other languages (and even in the mentioned ones). If you encounter any problems please feel free to create an issue in the GitHub repository.

**Example:** TypeScript Editor
![TypeScript](https://raw.githubusercontent.com/nilshartmann/vscode-blue-light-theme/master/screenshot_01.png)

In addition to this theme, I set the following user settings in my VS Code instance:

**File Icons**

- Seti (Visual Studio Code)

**Font**

```
	"editor.fontFamily": "Fira Code",
	"editor.fontSize": 14,
	"editor.lineHeight": 21,
	"editor.fontWeight": "400",
	"editor.fontLigatures": true,
 	"terminal.integrated.fontSize": 13,
	"terminal.integrated.lineHeight": 1.2,
	"terminal.integrated.fontWeightBold": "400",
```

**Hide elements from the UI**

```
	"editor.minimap.enabled": false,
	"explorer.openEditors.visible": 0,
	"editor.quickSuggestions": {
		"other": true,
		"comments": false,
		"strings": false
	},
  "editor.suggest.showWords": false,
	"breadcrumbs.enabled": false,
	"workbench.editor.enablePreview": false,
  "editor.cursorStyle": "line",
  "editor.hideCursorInOverviewRuler": true,
	"editor.occurrencesHighlight": false,
	"editor.overviewRulerBorder": false,
	"editor.renderIndentGuides": false,
	"editor.renderLineHighlight": "none",
	"workbench.activityBar.visible": false,
	"workbench.editor.showIcons": false,
	"editor.suggestOnTriggerCharacters": false,
  // use shortcut Cmd+Shift+Space insteadt open parameter hints if needed
	"editor.parameterHints.enabled": false,
	"editor.parameterHints.cycle": true
```

**Example:** Java Editor
![Java](https://raw.githubusercontent.com/nilshartmann/vscode-blue-light-theme/master/screenshot_02-java.png)

**Credits**

This theme is inspired by the great [Kary Pro Colors](https://marketplace.visualstudio.com/items?itemName=karyfoundation.theme-karyfoundation-themes) (light) theme.

**Contact, Feedback, Questions**

- If you have any feedback to give, questions to ask or issues to raise, please feel free to use the GitHub [issue tracker](https://github.com/nilshartmann/vscode-blue-light-theme/issues).

- You can follow me on twitter for updates and other things: [@nilshartmann](https://twitter.com/nilshartmann)
