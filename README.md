# Retrofit Assistant

- [简体中文](./README.zh_CN.md)

[![Jetbrains Plugins](https://img.shields.io/badge/plugin-Retrofit_Assistant-x.svg?logo=IntelliJ%20IDEA)][plugin]

[**Retrofit Assistant**][plugin] is a good helper for you to use the Retrofit framework, making it easier, more
efficient and safer for you to use Retrofit. You can think of it as approximately：

API management tools + code tools + code inspection and quickFix + code completion

> Supported Retrofit version >= 2.6.0

## Feature List

- API list tree, speed search and navigation
- Generate API intention
- Copy API
- API templates
- Provides quick fixes for creating APIs for unresolved methods
- add/modify Retrofit annotations
- url-based completion(**To avoid confusion with the IDE's built-in completion, you need to enter 'x' at the beginning
  to invoke this feature**)
- Extensive local API code inspection and quick fixes

> API list tree, speed search and navigation
> ![navigation_tree](./screenshots/apitree.gif)

> Generate API intention
> ![generation API](./screenshots/api_generate.gif)

> Copy API
> ![copyAPI](./screenshots/copyapi.gif)

> Create API template
> ![api Templates](./screenshots/createTemplate.gif)

> use API templates
> ![use Template](./screenshots/useTemplate.gif)

> Create API quick fix for unresolved method
> ![createAPIQuickFix](./screenshots/createApiQuickFix.gif)

> add/modify Retrofit annotations
> ![apiPreview](./screenshots/add_replace_annotation.gif)

> url-based completion
>
> Since this feature is not necessarily needed by every developer, and many times the URL and method name will be
> similar, the completion that comes with the IDE and this completion will be mixed together. In order to avoid this
> situation
>
> **This feature requires an 'x' at the beginning to enable completion**。
> ![apiPreview](./screenshots/completionBaseOnUrl.gif)

> API code inspection and quick fix
> ![apiPreview](./screenshots/inspectionAndFix.gif)

## How to install

- <kbd>Settings(windows:alt+shift+S;mac:command+,)</kbd> > <kbd>Plugins</kbd> > <kbd></kbd> > <kbd>type in "
  Retrofit Assistant"</kbd> > <kbd>Install Plugin</kbd>

[plugin]:https://plugins.jetbrains.com/plugin/22726-retrofit-assistant

