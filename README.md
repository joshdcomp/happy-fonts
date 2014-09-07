happy-fonts
===========

A quick boilerplate framework for fontcustom to make font integration with your project more seamless

Usage
=====

I haven't had a chance to write helpful docs yet, but the main points to know are:
- You'll need to install [font custom](http://fontcustom.com/)
- Run `fontcustom compile` from `/in`\*
- You can symlink to `/out/sass/templates`\* to include the compiled `.sass` files in your framework
- A JSON array of all icon classnames is created in `/out/templates/icon-array.json`\*
- You can make your own custom templates in `/in/templates`—just add a compile output path in fontcustom.yml
- And you can change the font-face name/classname prefix for your font name/icon classnames in `in/fontcustom.yml`

\* I know it's counterintuitive, but that's the way things are until [this bug](https://github.com/FontCustom/fontcustom/issues/195#issuecomment-38879690) gets fixed y'dig?

Credits
=======

Thanks to @jaydenseric for [his](http://jaydenseric.com/blog/fun-with-sass-and-font-icons) [tutorials](http://jaydenseric.com/blog/font-icons-like-a-boss-with-sass-and-font-custom) which spurred this idea along. 
