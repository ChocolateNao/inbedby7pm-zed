# In Bed By 7pm Theme for Zed

A port of a popular [theme](https://marketplace.visualstudio.com/items?itemName=sdras.inbedby7pm) for [Zed](https://zed.dev/) with some minor adjustments.

> [!NOTE]
> The port also includes an italic variant

<details>
<summary>Preview</summary>
Icons come from <a href="https://github.com/catppuccin/zed-icons"><i>Catppuccin Icons</i></a> extension

<img src="assets/showcase.png"/>
</details>

## Usage

### Manual Installation

1. Download the `.json` file with the theme variant of your choice from the [latest release](https://github.com/ChocolateNao/inbedby7pm-zed/releases/latest)
2. Navigate to `~/.config/zed/themes/` and place the file inside
3. Enter _theme selector: toggle_ in the command palette (<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>) and select your variant of __In Bed By 7pm__ theme in the dropdown

### Zed Extensions

1. Open Zed
2. Press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>X</kbd> to open Zed extensions menu (alternatively, you can open the menu by typing _zed: extensions_ in the command palette (<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>))
3. Search for the __In Bed By 7pm__ extension and install it

> [!TIP]
> After installation, a popup with avaliable variants will appear. You can switch to another variant at any time by entering _theme selector: toggle_ in the command palette and selecting the preferred variant of __In Bed By 7pm__ theme in the dropdown

## Development

Variants are developed in a separate file with the same top level `name` field.

To start off, simply clone the repository and install husky hooks.

<!-- Aside from the theme itself, the repository is packed with a script called `italize.js` that will automatically create an italized variant of the theme. You don't have to call it manually since there's a git hook for that. -->

```bash
# install hooks
npm i

# commit as you normally would
git add .
git commit -m "feat: my significant contribution"
```

## License

[MIT](https://github.com/ChocolateNao/inbedby7pm-zed/blob/master/LICENSE)
