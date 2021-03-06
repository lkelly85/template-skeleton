# Skeleton Flourish template
This is an empty Flourish template that can be used when creating new templates. Use this section of the readme to explain what this template does, and add credits.

## How to run?
This project needs the Flourish SDK to get it running. For more information on how to install and use the SDK, see the [Flourish SDK repo](https://github.com/kiln/flourish-sdk#using-the-sdk).

Once you have installed Flourish, you can start this template by calling `flourish run [dir_name]`, or `flourish run` if you're already in the template directory.

## About this skeleton template
This skeleton template provides a basic starting point for making new templates, similar to how we make Flourish templates at Flourish HQ. The main source code lives in the `src` directory and is separated in a couple of files in the `src/core` directory. The `src/index.js` has a description of what each file in the `core` directory does.

### Flourish Layout
This skeleton template also uses a module called Flourish Layout. This module sets up a basic page layout and allows you to add header, footer and makes sure everything resizes accordingly. For more information on Flourish layout, check https://github.com/kiln/flourish-layout

### Other Flourish modules
We're adding more and more modules to make life of a template developer easier. We already have modules for
- [Color palettes](https://www.npmjs.com/package/@flourish/custom-colors)
- [Popups](https://www.npmjs.com/package/@flourish/data-popup)
- [Slider](https://www.npmjs.com/package/@flourish/slider)
- [Controls](https://www.npmjs.com/package/@flourish/controls)

### Less
This template uses [Less](http://lesscss.org/#overview), which is a language extension for CSS. It allows you to do mixins, nesting, variables and many other things. It compiles into `static/style.css` which is being referenced in `index.html`. If you prefer, you can remove the compiler from `package.json` and write your css in `static/style.css` directly.

## Questions?
For more information, checkout our [Developer documentation](https://flourish.studio/developers/), or check out our [help pages](https://flourish.studio/developers/help/)
