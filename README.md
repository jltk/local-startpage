# local-startpage

**local-startpage** is a responsive dynamic web browser startpage using [localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage).

+ No database needed ([Web Storage](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API))
+ One 11kb HTML file including CSS and JavaScript
+ Saved data gets lost when clearing browser cookies (Firefox) or cache (Chrome) when set to clear "Everything"
+ Stored data is browser specific

![Screenshot](https://u.teknik.io/ywcdE.PNG)

---

## Install
Only `startpage.html` is required.

```

    ┌─ README.md
    ├─ LICENSE.md
    ├─ package.json
    └─ /local-startpage
        ├─ startpage.html       // open/set this file as startpage in your browser
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
You can use ``npm install --prefix /path/to/dir local-startpage --global`` to install to a specific directory.

## Browser support
Tested with Mozilla Firefox 59.0.2 (Windows).
+ https://caniuse.com/#search=Web%20Storage
+ https://caniuse.com/#search=flexbox
+ https://caniuse.com/#search=CSS%20variables

## License
[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html). All image files in this repository are created by me and are also licensed with GNU/GPL v3.0.

## Further reading
+ https://www.w3.org/TR/webstorage/#dom-localstorage
+ https://de.wikipedia.org/wiki/Web_Storage
+ https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage
+ https://stackoverflow.com/questions/9948284/how-persistent-is-localstorage
