happy-fonts
===========

Making custom icon fonts happy and fun…or something

Usage
=====

Haven't had a chance to write helpful docs yet, but the main points to know are:
- You'll need to install [font custom](http://fontcustom.com/)
- Compiling should happen from `/in`
- You can symlink to `/out/sass/templates`\* to include the compiled `.sass` files in your framework
- A php array of all icon classnames is created in `/out/templates/icon-array.json`\*
- You can make your own custom templates in `/in/templates`—just add a compile output path in fontcustom.yml
- And you can change the name/prefix for your font name/icon classnames in `in/fontcustom.yml`

\* I know it's a dumb file structure, but that's the way things are until [this bug](https://github.com/FontCustom/fontcustom/issues/195#issuecomment-38879690) gets fixed y'dig?
