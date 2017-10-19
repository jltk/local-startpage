# [![local-startpage](https://u.teknik.io/w8SRz.png)](#install)

**local-startpage** is a lightweight vanilla HTML and JavaScript file to serve as dynamic web browser startpage, with editable links, stored in the browsers local storage (using [localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)).

+ **Pro:** No database needed ([Web Storage](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API))
+ **Con:** Data might get lost when clearing browser cookies (Firefox) or cache (Chrome)

I made this to get around having to edit links in my HTML file via text editor; will continuously improve and update.

---

#### Table of contents
+ [Browser support](#browser-support)
+ [Install](#install)
    + [Install via git](#install-via-git)
    + [Install via npm](#install-via-npm)
+ [Modify styles](#modify-styles)
+ [License](#license)
+ [Contribute](#contribute)
+ [Further reading](#further-reading)

---

## Browser support
Tested working as it should be with Mozilla IceCat 52.3.0 (Linux) and Mozilla Firefox 56.0, Google Chrome 63.0 (Windows).

It might work in all current web browser versions except [IE, Edge and Opera Mini](#browser-support-notes).

## Install
`startpage.html` and `startpage.js` are required. Favicon is optional.

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
$ git clone https://github.com/jltk/local-startpage.git
```

### Install via npm
```sh
$ npm install local-startpage
```

## Modify styles
Using default sans-serif font. Organized colors using CSS variables in `startpage.html`.

## License
[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html). All image files in this repository are created by me and are also licensed with GNU/GPL v3.0.

## Contribute
To contribute file an issue or send a pull request.

## Further reading
- https://de.wikipedia.org/wiki/Web_Storage
- https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API
- https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage
- Tool used to compress SVG: https://jakearchibald.github.io/svgomg/

### Browser support notes
- https://caniuse.com/#search=Web%20Storage
- https://caniuse.com/#search=flexbox
- https://caniuse.com/#search=CSS%20variables
