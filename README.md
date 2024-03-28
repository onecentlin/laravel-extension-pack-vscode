# Laravel Extension Pack for Visual Studio Code

Includes the basic extensions to get started with [Laravel](https://laravel.com) development in Visual Studio Code.

## Laravel Extensions

Extension | Objective |
--------- | --------- |
[Laravel Blade Snippets](https://marketplace.visualstudio.com/items?itemName=onecentlin.laravel-blade) | Laravel blade snippets and syntax highlight support |
[Laravel Snippets](https://marketplace.visualstudio.com/items?itemName=onecentlin.laravel5-snippets) | Laravel snippets |
[Laravel Artisan](https://marketplace.visualstudio.com/items?itemName=ryannaddy.laravel-artisan) | Laravel Artisan |
[Laravel Extra Intellisense](https://marketplace.visualstudio.com/items?itemName=amiralizadeh9480.laravel-extra-intellisense) | Laravel intellisense enhancement |
[Laravel goto view](https://marketplace.visualstudio.com/items?itemName=codingyu.laravel-goto-view) | Laravel blade view easy targeting |
[laravel-jump-controller](https://marketplace.visualstudio.com/items?itemName=pgl.laravel-jump-controller) | Laravel controller easy navigating from route file |
[laravel-goto-components](https://marketplace.visualstudio.com/items?itemName=naoray.laravel-goto-components) | Navigating to blade component file |
[Laravel Blade formatter](https://marketplace.visualstudio.com/items?itemName=shufo.vscode-blade-formatter) | Blade formatter |
[Laravel Create View](https://marketplace.visualstudio.com/items?itemName=glitchbl.laravel-create-view) | Create laravel view using dot notation |
[Laravel Blade Wrapper](https://marketplace.visualstudio.com/items?itemName=IHunte.laravel-blade-wrapper) | An extension to wrap Blade directives |
[DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv) | .env syntax highlighting |
[DevDb](https://marketplace.visualstudio.com/items?itemName=damms005.devdb) | Zero-config extension that auto-loads your database and displays the data right inside the IDE |

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
