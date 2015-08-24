Sublime-DV-Snippets
===========================================

This is a Sublime Text package of usefull snippets for the Front-End development.

Languages: HTML-5, CSS-3, JavaScript, ActionScript-3

Type the snippet shortcode and then press Tab to complete the snippet.

## Installation

This package is not in [Package Control][package_control] repository, so you can use Terminal and git clone to install it. 

I'm using [Sublime 3][sublime3] and it works good.

#### Mac OS

    cd "~/Library/Application Support/Sublime Text 3/Packages"
    
#### Windows 7
    
    cd "C:\Users\YOUR_USERNAME\AppData\Roaming\Sublime Text 3\Packages"
    
#### Inside _Packages_
    
    git clone https://github.com/bitbonsai/sublime-jquery-snippets.git "jQuery-Snippets"

Just type **Ctrl+ Shift+ P > Browse Packages** in your Sublime Text.

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
