# The Berm

A highly functional [Ghost](https://github.com/TryGhost/Ghost) theme that adapts to the reader's preferences. Let them read, search, subscribe, navigate, and more with ease.

# Instructions

1. Download this theme (**link tbd**)
2. Log into Ghost, and go to the `Design` settings area to upload the zip file

# Theme Development

Styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally (which you will get automatically if you have devbox setup). After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/the-berm.zip`, which you can then upload to your site.

```bash
yarn zip
```

# Site Development

To actually develop the site and not just the theme:

1. `cd site && npx ghost install`
1. ????????????
1. Give up?????

# Contribution

This repo is synced automatically with [TryGhost/Themes](https://github.com/TryGhost/Themes) monorepo. If you're looking to contribute or raise an issue, head over to the main repository [TryGhost/Themes](https://github.com/TryGhost/Themes) where our official themes are developed.

# Copyright & License

Copyright (c) 2013-2023 Ghost Foundation - Released under the [MIT license](LICENSE).
