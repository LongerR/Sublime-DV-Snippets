DV-Snippets for [Sublime Text][sublime]
===========================================

This is a package of usefull snippets for the Front-End development.

I'm using Sublime Text 3 and it works good.

## Installation

This package is not in [Package Control][package_control] repository, so you can use Terminal and **git clone** to install it. Also you can go to `Preferences > Browse Packages...` in your editor and copy this bundle manually.

**Mac OS:**

```sh
$ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages
$ git clone https://github.com/DopustimVladimir/Sublime-DV-Snippets.git
```

**Windows 7:**

```sh
$ cd %APPDATA%/Sublime\ Text\ 3/Packages
$ git clone https://github.com/DopustimVladimir/Sublime-DV-Snippets.git
```

**Linux:**

```sh
$ cd ~/.config/sublime-text-3/Packages
$ git clone https://github.com/DopustimVladimir/Sublime-DV-Snippets.git
```

## JavaScript

Type the snippet shortcode and then press Tab to complete the snippet.

#### [con] console.log

```js
console.log(${1:msg})${0}
```

#### [fun] function

```js
function ${1:methodName}(${2:arguments}) {
    ${3}
}
```

#### [add] addEventListener

```js
${1:document}.addEventListener('${2:event}', function(e) {
    ${3}
});
```

#### [cre] createElement

```js
${1:document}.createElement(${2:elem});
```

#### [app] appendChild

```js
${1:document}.appendChild(${2:elem});
```

#### [rem] removeChild

```js
${1:document}.removeChild(${2:elem});
```

#### [inn] innerHTML

```js
${1:document}.innerHTML = '${2:elem}';
```

[sublime]: http://www.sublimetext.com/
[package_control]: https://packagecontrol.io/
