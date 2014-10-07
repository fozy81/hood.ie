hoodie-website-css
==================

## Getting started

To get started check out the recent version and type npm install.
The default task (just type 'grunt') will fire up a local server at localhost:1337 with livereload and dev Sass compiling (including sourcemap and nested output).
There's also a production task ('grunt build') which at this point just spits out a compressed CSS file, without sourcemap in a dedicated folder(css/build).

## Editorconfig

Please use the .editorsconfig file with your editor of choice to ensure consistent coding styles. Plugins are available at [http://editorconfig.org/#download](http://editorconfig.org/#download title="editorconfig download").

## Rem-calc

We use rem units instead of pixels. There is a Sass function called "rem-calc" to simplify this. Just use rem-calc(px-value). You can also provide multiple values like you would do with a CSS shorthand e.g. margin: rem-calc(20 0 20).
If you're using Sublime Text you can add this handy snippet to your user directory(user/Library/Apllication\ Support/Sublime\ Text\ 3/Packages/User:

    <snippet>
      <content><![CDATA[
    rem-calc($1)
    ]]></content>

    <tabTrigger>rem</tabTrigger>
    </snippet>

Save it as name.sublime-snippet. After you've done that restart Sublime Text. Now you just have to type rem(tab) and you'll get rem-calc(cursor here).

## gh-pages branch

This branch will be developed parallel to the main brach to set up the page structure and functionality. To start your local Jekyll environment just follow this guide: [https://help.github.com/articles/using-jekyll-with-pages/](https://help.github.com/articles/using-jekyll-with-pages/ title="github pages and jekyll").


## How to use

### Colours

###### Orange theme
$orange: #e94e1b;<br >/
$orange-l: #f9c4b3;

###### Blue theme
$blue: #312783;<br >/
$blue-l: #bfbcd8;

###### Green theme
$green: #0b8e36;<br >/
$green-l: #a9d6b8;

###### Yellow theme
$yellow: #f9b233;<br >/
$yellow-l: #fce3b6;

###### Lilac theme
$lilac: #520644;<br >/
$lilac-l: #c1a7bc;

###### Gray theme
$gray-1: #282828;<br >/
$gray-5: #b3b3b3;

###### Font colours
$gray-2: #404040;<br >/
$gray-3: #606060;<br >/
$gray-4: #999;

###### Background
$gray-6: #fdfdfd;