# Laravel Extension Pack for Visual Studio Code

Includes the basic extensions to get started with [Laravel](https://laravel.com) development in Visual Studio Code.

## Laravel Extensions

Extension | Version | Objective
--------- | ------- | ---------
[Laravel Blade Snippets](https://marketplace.visualstudio.com/items?itemName=onecentlin.laravel-blade) | ![Latest Release](https://vsmarketplacebadge.apphb.com/version-short/onecentlin.laravel-blade.svg) | Laravel blade snippets and syntax highlight support
[Laravel Snippets](https://marketplace.visualstudio.com/items?itemName=onecentlin.laravel5-snippets) | ![Latest Release](https://vsmarketplacebadge.apphb.com/version-short/onecentlin.laravel5-snippets.svg) | Laravel snippets
[Laravel Artisan](https://marketplace.visualstudio.com/items?itemName=ryannaddy.laravel-artisan) | ![Latest Release](https://vsmarketplacebadge.apphb.com/version-short/ryannaddy.laravel-artisan.svg) | Laravel Artisan
[Laravel Extra Intellisense](https://marketplace.visualstudio.com/items?itemName=amiralizadeh9480.laravel-extra-intellisense) | ![Latest Release](https://vsmarketplacebadge.apphb.com/version-short/amiralizadeh9480.laravel-extra-intellisense.svg) | Laravel intellisense enhancement
[Laravel goto view](https://marketplace.visualstudio.com/items?itemName=codingyu.laravel-goto-view) | ![Latest Release](https://vsmarketplacebadge.apphb.com/version-short/codingyu.laravel-goto-view.svg) | Laravel blade view easy targeting
[Laravel goto controller](https://marketplace.visualstudio.com/items?itemName=stef-k.laravel-goto-controller) | ![Latest Release](https://vsmarketplacebadge.apphb.com/version-short/stef-k.laravel-goto-controller.svg) | Laravel controller easy navigating from route file
[DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv) | ![Latest Release](https://vsmarketplacebadge.apphb.com/version-short/mikestead.dotenv.svg) | .env syntax highlighting
[laravel-goto-components](https://marketplace.visualstudio.com/items?itemName=naoray.laravel-goto-components) | ![Latest Release](https://vsmarketplacebadge.apphb.com/version-short/naoray.laravel-goto-components.svg) | Navigating to blade component file
[Laravel Blade formatter](https://marketplace.visualstudio.com/items?itemName=shufo.vscode-blade-formatter) | ![Latest Release](https://vsmarketplacebadge.apphb.com/version-short/shufo.vscode-blade-formatter.svg) | Blade formatter
[Laravel Create View](https://marketplace.visualstudio.com/items?itemName=glitchbl.laravel-create-view) | ![Latest Release](https://vsmarketplacebadge.apphb.com/version-short/glitchbl.laravel-create-view.svg) | Create laravel view using dot notation
[Laravel Blade Wrapper](https://marketplace.visualstudio.com/items?itemName=IHunte.laravel-blade-wrapper) | ![Latest Release](https://vsmarketplacebadge.apphb.com/version-short/IHunte.laravel-blade-wrapper.svg) | An extension to wrap Blade directives

### Blade formatter settings

Open `File` -> `Preferences` -> `Settings`

Using `Laravel Blade Snippet` and enable blade formatter

```json
"blade.format.enable": true,
"[blade]": {
    "editor.autoClosingBrackets": "always",
    "editor.defaultFormatter": "onecentlin.laravel-blade",
},
```

**Alternative**: Using `Laravel Blade formatter` as blade formatter

```json
"bladeFormatter.format.enabled": true,
"[blade]": {
    "editor.defaultFormatter": "shufo.vscode-blade-formatter",
},
```

## Collaboration

Extension | Objective
--------- | ---------
[EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) | EditorConfig helps developers define and maintain consistent coding styles between different editors and IDEs.

## PHP Development

Recommended extension: [PHP Productive Pack](https://marketplace.visualstudio.com/items?itemName=onecentlin.php-productive-pack)

## Contact

Please file any [issues](https://github.com/onecentlin/laravel-extension-pack-vscode/issues) or have a suggestion please tweet me [@onecentlin](https://twitter.com/onecentlin).
