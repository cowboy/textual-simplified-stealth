# Simplified Stealth: a Textual IRC Style

A few years ago, I created a visual style called [Simplified](http://benalman.com/projects/simplified-style/) for the [Linkinus](http://conceitedsoftware.com/products/linkinus) OS X IRC app. Some time later, the creator of the [Textual](http://www.codeux.com/textual/) OS X IRC app asked me if he could modify it for use there. Of course, I said yes.

Some time therafter, I created a Linkinus Simplified variant called "Stealth" that made use of the excellent [M+ 2m font](http://mplus-fonts.sourceforge.jp/mplus-outline-fonts/index-en.html), but it was never ported over to Textual. Well, now I'm using Textual... so I've decided to port it over.

## Notes

 * This is a work in progress. Meaning that it's not fully tested, so YMMV. That being said, it works great for me.
 * The included fonts must be installed and the font is hard-coded, meaning that you can't change it via the in-app controls. You can, however change the font size via those controls.

## Installation
Textual themes are installed into the `~/Library/Containers/com.codeux.irc.textual/Data/Library/Application Support/Textual IRC/Styles` directory. This theme should be installed in a subdirectory, under that directory, called `Simplified Stealth`.

If you have git installed, you can run these commands in the terminal:

```bash
mkdir -p ~/Library/Containers/com.codeux.irc.textual/Data/Library/Application\ Support/Textual\ IRC/Styles
cd ~/Library/Containers/com.codeux.irc.textual/Data/Library/Application\ Support/Textual\ IRC/Styles
git clone https://github.com/cowboy/textual-simplified-stealth.git 'Simplified Stealth'
```

Then install the fonts in the `Simplified Stealth/fonts` subdirectory into OS X, and restart the app.

## Screenshot
If the theme installed correctly, you should see something like this, when you select it in the app:

![simplified stealth](http://benalman.com/grab/b008d0.png)

## Todos

 * Get `@font-face` working properly so that the font doesn't need to be installed.
 * Ensure all the visual styles are accounted for.
 * Look into other possible app UI styling options.

## License
Copyright (c) 2012 "Cowboy" Ben Alman  
Licensed under the MIT license  
http://benalman.com/about/license/
