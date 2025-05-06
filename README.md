# Kimbie Fountain Theme

![](https://github.com/swift502/KimbieFountain/raw/HEAD/images/preview.png)

A modification of the Kimbie Dark theme to make it work better with the [Better Fountain](https://marketplace.visualstudio.com/items?itemName=piersdeseilligny.betterfountain) extension.

Only intended for use with `.fountain` files. Any other file type is not guaranteed to be readable.

Key aims:

- improve brightness and contrast
- put emphasis on action and dialogue, while keeping them visually distinct
- de-emphasize other elements like parentheticals and transitions

## Additional styling

Here's some optional styling I recommend adding to your `.vscode/settings.json`:

1. Changing the font to Courier or Courier Prime:

```json
{
  "editor.fontFamily": "Courier Prime"
}
```

2. Disabling matching word highlighting, since it doesn't serve much purpose in screenwriting, and can be distracting:

```json
{
  "editor.occurrencesHighlight": "off",
  "editor.selectionHighlight": false,
}
```

## Workspace scoping

If you wish to limit the effect of this theme to a specific workspace, you can do so by enabling this override in `settings.json`:

```json
{
  "workbench.colorTheme": "Kimbie Fountain"
}
```

<!--

Setup:
  - npm install -g vsce
  - vsce login jan-blaha
  - vsce publish

Inspect textmate tokens:
  - F1 > Developer: Inspect Editor Tokens and Scopes

Extension admin: https://marketplace.visualstudio.com/manage/
Tokens: https://swift502.visualstudio.com/_usersSettings/tokens

-->
