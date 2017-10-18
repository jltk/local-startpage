# [![local-startpage](test.png)](https://linktoreleasedl)

## Overview

**local-startpage** is a ultra-lightweight vanilla HTML and JavaScript file, to serve as dynamic web browser startpage to organize links, with editable entries, stored in the browsers local storage, using [localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage).

+ No database needed ([Web Storage](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API))
+ Data doesn't get deleted when closing your browser or clearing browser cache

I made this to get around having to edit links in my HTML file via text editor.

---

#### Table of contents
+ [Browser support](#browser-support)
+ [Install]()
    + [Install via git]()
    + [Install via npm]()
+ [Modify styles]()
+ [License & contribute]()
+ [Further reading]()

---

## Browser support
Tested working as it should be on Mozilla IceCat 52.3.0, Mozilla Firefox 56.0, Google Chrome 63.0 on Linux and Windows.

It should work in all current web browser versions except maybe [IE, Edge and Opera Mini][1].

caniuse.

## Install
Only `startpage.html` and `startpage.js` are required.

```



    ┌─ README.md
    ├─ package.json
    └─ /local-startpage         // relevant folder
        ├─ startpage.html       // set this file as startpage in your browser
        ├─ functions.js         // required by startpage.html
        └─ favicon.ico          // optional

```

### Install via git
```sh
$ git clone https://
```

### Install via npm
```sh
$ npm install local-startpage
```

### How to set browser homepage
- Mozilla
- Chrome
- Safari
- Android

## Modify styles
Using default fonts. Organized colors using [CSS variables][3] in `startpage.html`.

## License & contribute
open all. 
pull requests.
all images by me.

## Further reading
- https://de.wikipedia.org/wiki/Web_Storage
- https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API
- https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage
- Tool used to compress SVGs: svg compressor

Browser support:
[1]: http://caniuse.com/#search=Web%20Storage
[2]: http://caniuse.com/#search=flexbox
[3]: http://caniuse.com/#search=CSS%20variables

---

**TO-DO:** editable headlines, add multiple boxes, edit set links, online, sessionStorage mode, enhance readme file, sync files