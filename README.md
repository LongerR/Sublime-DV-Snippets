DV-Snippets for [Sublime Text][sublime3]
===========================================

This is a Sublime Text package of usefull snippets for the Front-End development.

## Installation

This package is not in [Package Control][package_control] repository, so you can use Terminal and **git clone** to install it. Also you can go to `Preferences > Browse Packages...` in your editor and copy this bundle manually.

I'm using [Sublime Text 3][sublime3] and it works good.

Mac OS:

```sh
$ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/Sublime-DV-Snippets
$ git clone https://github.com/DopustimVladimir/Sublime-DV-Snippets.git
```

Windows 7:

```sh
$ cd %APPDATA%/Sublime\ Text\ 3/Packages/Sublime-DV-Snippets
$ git clone https://github.com/DopustimVladimir/Sublime-DV-Snippets.git
```

Linux:

```sh
$ cd ~/.config/sublime-text-3/Packages/Sublime-DV-Snippets
$ git clone https://github.com/DopustimVladimir/Sublime-DV-Snippets.git
```

## JavaScript

Type the snippet shortcode and then press Tab to complete the snippet.

#### cl

```js
console.log(${1:msg})${0}
```

#### fna

```js
function(${1:arguments}) {
    ${0:// body...}
}
```

#### fni

```js
(function() {
    ${0:// body...}
})();
```

[sublime3]: http://www.sublimetext.com/3
[package_control]: https://packagecontrol.io/
