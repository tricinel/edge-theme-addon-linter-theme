# Edge Theme Addon for SublimeLinter

This Edge Theme addon will enable you to change the appearance of the [SublimeLinter][linter] Gutter Theme.

![Edge Sublime Linter Theme][img-linter]

## Get It

### Package Control

The easiest way to install is using [Package Control][pc], where Edge is listed as `Edge Theme Addon - Linter Theme`.

1. Open `Command Palette` using menu item `Tools → Command Palette...`
2. Choose `Package Control: Install Package`
3. Find `Edge Theme Addon - Linter Theme` and hit `Enter`

## Activation

Activate the SublimeLinter gutter theme by modifying the plugin's preferences file, which you can find using the menu item `Preferences → Package Settings → SublimeLinter → Settings - User`.

![SublimeLinter Theme Activation][img-linter-activation]

```js
"gutter_theme": "Packages/Edge Theme Addon - Linter Theme/Edge.gutter-theme",
```

<!-- Links -->

[pc]: https://sublime.wbond.net
[releases]: https://github.com/tricinel/edge-theme-addon-linter/releases
[linter]: https://github.com/SublimeLinter/SublimeLinter3

<!-- Images -->

[img-linter]: https://raw.githubusercontent.com/tricinel/edge-theme-addon-linter-theme/master/assets/edge-theme-addon-linter-theme-preview.png
[img-linter-activation]: https://raw.githubusercontent.com/tricinel/edge-theme-addon-linter-theme/master/assets/linter-theme-activation.png