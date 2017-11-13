# fa-icon Custom Element

[![npm version](https://badge.fury.io/js/fa-icon-element.svg)](https://badge.fury.io/js/fa-icon-element)

**FontAwesome Version:** v4.7.0

Vanilla custom element that displays
[FontAwesome icons](http://fontawesome.io/icons/) in your page.

---

  - [Installation](#installation)
  - [Usage](#usage)
  - [Known Issues, Potential Gotchas](#known-issues-potential-gotchas)
  - [Legal](#legal)

## Installation

To install, run:

```
npm i fa-icon-element
```

Then, either import the file directly with:

```HTML
<script src="path/to/node_modules/fa-icon-element/src/fa-icon.js" defer></script>
```

or, include it in your webpack (or similar) build:

```Javascript
import "fa-icon-element";
```

## Usage

Once installed, simply use with:

```HTML
<fa-icon name="fa-plus"></fa-icon>
```

Where the `name` attribute is any valid FontAwesome icon name. See
[here](http://fontawesome.io/icons/) for a list of icons.

## Known Issues, Potential Gotchas

  - The FontAwesome font face is loaded from the FontAwesome CDN. It is currently not possible to load a local instance of the FontAwesome set. Please [open an issue](https://github.com/aeolingamenfel/fa-icon/issues) if you need this feature.
  - Due to a potential bug, the `@font-face` for FontAwesome is elevated to the global CSS scope. See [this article by Rob Dodson](http://robdodson.me/at-font-face-doesnt-work-in-shadow-dom/) for more information.

## Legal

Font Awesome by Dave Gandy - [fontawesome.io](http://fontawesome.io)
([License Info](http://fontawesome.io/license/))


