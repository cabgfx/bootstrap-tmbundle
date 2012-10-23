# TextMate bundle for [Twitter Bootstrap 2](http://twitter.github.com/bootstrap).
with optional support for Sublime Text 2.

## Installation

#### Textmate 1.5.x

```
mkdir -p ~/Library/Application\ Support/TextMate/Bundles/
cd ~/Library/Application\ Support/TextMate/Bundles/
git clone git://github.com/cabgfx/bootstrap-tmbundle.git Bootstrap.tmbundle
osascript -e 'tell app "TextMate" to reload bundles'
```

#### Sublime Text 2
Please note: this bundle is primarily targeted at Textmate, and support for Sublime Text 2 is experimental.
If you use Sublime Text 2, and see areas that can be improved for dual compatibility, pull requests are greatly appreciated.

```
mkdir -p ~/Library/Application Support/Sublime Text 2/Packages
cd ~/Library/Application Support/Sublime Text 2/Packages
git clone git://github.com/cabgfx/bootstrap-tmbundle.git Bootstrap.tmbundle
```

## Snippets

The following snippets are currently available in HTML or JS flavored files (eg. Rails templates).
When using these snippets, you can tab through attributes and quickly fill in everything without missing a spot.

More snippets will be added on an ongoing basis.

(scope selector: `text.html, source.js`)

### Scaffolding
#### Grid system
* Grid container markup (ie. `<div class="container"><div class="row"><div class="grid*">`) **[`grid⇥`]**
* Row container markup (ie. `<div class="row"><div class="grid*">`) **[`row⇥`]**

### Base CSS
#### Typography
* Page header **[`phead⇥`]**

#### Forms
* Control groups wrapper, for horizontal forms **[`cgrp⇥`]**
* Control groups wrapper, for horizontal forms (for Rails form builders `<%= f.text_field %>` etc.) **[`cgrpr⇥`]**

### Components
#### Navbar
* Basic navbar (white) **[`navb⇥`]**
* Responsive navbar (white, incl. `.btn-collapse` and `.nav-collapse` elements) **[`navbr⇥`]**

### Javascript

Note: these snippets only generate required markup for the Bootstrap JS components.

* Modal box **[`modal⇥`]**
* Accordion **[`acc⇥`]**
* Accordion group **[`accg⇥`]**

## TODO's / wishlist

* Add command(s) to open the bootstrap docs in the browser, preferably "context-aware" ie. go to JS docs when working with JavaScript.
* Add snippets for buttons incl. groups & toolbars: `btn`, `btng`, `btnt`.