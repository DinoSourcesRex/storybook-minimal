# Storybook issues

When running `npm run build-storybook` on a fairly fresh project the following errors are given

```
info => Using angular project "squads:build" for configuring Storybook
ERR! Error: The projects/squads/src/favicon.ico asset path must start with the project source root.
ERR!     at F:\repos\.play\squads\node_modules\@angular-devkit\build-angular\src\utils\normalize-asset-patterns.js:33:23
ERR!     at Proxy.map (<anonymous>)
ERR!     at normalizeAssetPatterns (F:\repos\.play\squads\node_modules\@angular-devkit\build-angular\src\utils\normalize-asset-patterns.js:26:26)
ERR!     at normalizeBrowserSchema (F:\repos\.play\squads\node_modules\@angular-devkit\build-angular\src\utils\normalize-builder-schema.js:23:71)
ERR!     at generateBrowserWebpackConfigFromContext (F:\repos\.play\squads\node_modules\@angular-devkit\build-angular\src\utils\webpack-browser-config.js:122:66)
ERR!     at async generateI18nBrowserWebpackConfigFromContext (F:\repos\.play\squads\node_modules\@angular-devkit\build-angular\src\utils\webpack-browser-config.js:70:20)
ERR!  MissingAssetSourceRootException [Error]: The projects/squads/src/favicon.ico asset path must start with the project source root.
ERR!     at F:\repos\.play\squads\node_modules\@angular-devkit\build-angular\src\utils\normalize-asset-patterns.js:33:23
ERR!     at Proxy.map (<anonymous>)
ERR!     at normalizeAssetPatterns (F:\repos\.play\squads\node_modules\@angular-devkit\build-angular\src\utils\normalize-asset-patterns.js:26:26)
ERR!     at normalizeBrowserSchema (F:\repos\.play\squads\node_modules\@angular-devkit\build-angular\src\utils\normalize-builder-schema.js:23:71)
ERR!     at generateBrowserWebpackConfigFromContext (F:\repos\.play\squads\node_modules\@angular-devkit\build-angular\src\utils\webpack-browser-config.js:122:66)
ERR!     at async generateI18nBrowserWebpackConfigFromContext (F:\repos\.play\squads\node_modules\@angular-devkit\build-angular\src\utils\webpack-browser-config.js:70:20)
```
