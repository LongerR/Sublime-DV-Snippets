Sublime-DV-Snippets
===========================================

This is a Sublime Text package of usefull snippets for the Front-End development.

Languages: HTML-5, CSS-3, JavaScript, ActionScript-3

Type the snippet shortcode and then press Tab to complete the snippet.

## Installation

This package is not in [Package Control][package_control] repository, so you can use Terminal and **git clone** to install it. 

I'm using [Sublime 3][sublime3] and it works good.

#### Mac OS

    git clone https://github.com/DopustimVladimir/Sublime-DV-Snippets.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/Sublime-DV-Snippets

#### Windows 7

    git clone https://github.com/DopustimVladimir/Sublime-DV-Snippets.git %APPDATA%/Sublime\ Text\ 3/Packages/Sublime-DV-Snippets

#### Linux

    git clone https://github.com/DopustimVladimir/Sublime-DV-Snippets.git ~/.config/sublime-text-3/Packages/Sublime-DV-Snippets

You can find it by type **Ctrl+ Shift+ P > Browse Packages** in your Sublime Text.

## JavaScript

#### cl => console.log

```js
console.log(${1:msg})${0}
```

#### fna => anonymous function

```js
function(${1:arguments}) {
    ${0:// body...}
}
```

#### fni => immediately-invoked function

```js
(function() {
    ${0:// body...}
})();
```

[sublime3]: http://www.sublimetext.com/3
[package_control]: https://packagecontrol.io/
