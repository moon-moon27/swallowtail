## Another *phork* of [phocus](https://github.com/phocus/gtk)
![ "emergency food" ](/assets/food.webp)
## Installation From source
Make sure to install the following dependency:

- [npm](https://www.npmjs.com/)

Clone the swallowtail repository and build/install it using make

```bash
git clone https://github.com/pansy27/swallowtail.git
cd swallowtail
make
sudo make install
```
Install its npm dependencies:
```bash
cd ~/.local/share/themes/swallowtail
npm install
```

### Build
Build the theme by running its build script:
```bash
npm run build
```

### Watch
Start a watcher that automatically builds when you modify a file:
```bash
cd ~/.local/share/themes/swallowtail
npm run watch
```

### Reload GTK Theme
Make all open GTK applications reload the phocus theme by running:
```bash
npm run reload_gtk_theme
```

This requires you to have [xsettingsd](https://github.com/derat/xsettingsd) installed.

### Watch and reload - *ultimate comfort*
Automatically build on modifications, and make all open GTK applications reload the phocus theme:
```bash
npm run watch_and_reload
```
## Preview:
![ "example image" ](/assets/example.png)
