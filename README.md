# Kimbie Fountain Theme

![](https://github.com/swift502/KimbieFountain/raw/HEAD/images/preview.png)

A modification of the Kimbie Dark theme to make it work better with the [Better Fountain](https://marketplace.visualstudio.com/items?itemName=piersdeseilligny.betterfountain) extension.

Only intended for use with `.fountain` files. Any other file type is not guaranteed to be readable.

Key aims:

- improve brightness and contrast
- put emphasis on action and dialogue, while keeping them visually distinct
- de-emphasize other elements like parentheticals and transitions

## Additional styling

To get the Full experience™, I recommend switching to the Courier Prime font:

1. Download and install [Courier Prime](https://fonts.google.com/specimen/Courier+Prime)
2. Add the following line to your `settings.json`:

```json
{
  "editor.fontFamily": "Courier Prime"
}
```

## Workspace scoping

If you wish to limit the effect of this theme to a specific workspace, you can do so by setting an override in the `settings.json`:

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
