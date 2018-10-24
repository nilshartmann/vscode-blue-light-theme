# VS Code theme "blue-light"

This is a light theme for Visual Studio Code with mostly
blue colors.

I tried to make it very simple to remove distractions as much as possbible:

- use only a few colors, both for UI and syntax coloring
- do _not_ use red colors for other things as errors

_Note_: I only tested for Java, JavaScript/TypeScript, React, CSS/SASS. There might be "strange" colors in other languages (and even in the mentioned ones).

**Example:** TypeScript Editor
![TypeScript](https://raw.githubusercontent.com/nilshartmann/vscode-blue-light-theme/master/screenshot_01.png)

In addition to this theme I set the following settings:

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

**Bracket matching**
For bracket matching I use [Subtle Match Brackets](https://marketplace.visualstudio.com/items?itemName=rafamel.subtle-brackets) with following settings:

```
  // use subtle brackets instead
  "editor.matchBrackets": false,
	"subtleBrackets.style": {
		"borderColor": "#795e26",
		"borderStyle": "none none solid none",
		"borderWidth": "1px"
	},
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
	"editor.wordBasedSuggestions": false,
	"breadcrumbs.enabled": false,
	"workbench.editor.enablePreview": false,
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
