# Change Log

## [NEXT VERSION]

## [v1.2.2] - [18 MAR 2021]

[FIXED]
- JS enhancement, turned all `let` to `const` and used YODA condition check.
- Cleaned `package.json`, removed some unnecessary packages, set version to stable.
- Calling the `init()` methods of the modules after applying filter. Fixes [#24](https://github.com/codemascot/fnugg/issues/24).

## [v1.2.1] - [16 MAR 2021]

[FIXED]
- Using JSON in stead of whole HTML caching in frontend.

## [v1.2.0] - [11 MAR 2021]

[ADDED]
- Unit testing added through `WP_Mock`.

[FIXED]
- `.editorconfig` coding styles fix.
- Applied bracket spacing in JS coding style.
- Cherry picked `DIRECTORY_SEPARATOR` fix.

## [v1.1.1] - [04 MAR 2021]

[FIXED]
- PHP and JS coding style fix

## [v1.1.0] - [04 MAR 2021]

[FIXED]
- Fnugg API URL is placed under `Api()::constructor()` method.
- `DIRECTORY_SEPARATOR` predefined PHP constant used instead of slash(`/`).
- `empty()` check added to `Helpers::trans_id()` method.

[UPDATE]
- Fronent example elaborated in [README.md](README.md) file.

## [v1.0.0] - [03 MAR 2021]

[FEATURE]
- Introduced caching mechanism for API's as well as for the frontend.
- Used hash function to create transient key, see `Helpers::trans_id()` method.

[FIXED]
- Fixed return type for `render()` method.

## [v0.0.2] - [02 MAR 2021]

[FEATURE]
- Introduced `fnugg_frontend_self_api_search_params` filter hook in `Block\Block::render()`.
- Introduced `fnugg_frontend_render_html` action hook in `Block\Block::render()`.

[FIXED]
- Admin namespace changed to `Block`.
- Multiple instance issue fixed.
- Removed unnecessary packages.
- Added some CSS in editor CSS.
- Removed default frontend part.

## [v0.0.1] - [01 MAR 2021]

- Initial release.
