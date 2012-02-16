# Twitter Bootstrap bundle for TextMate

Very alpha :)

**Installation**

```
mkdir -p ~/Library/Application\ Support/TextMate/Bundles/
cd ~/Library/Application\ Support/TextMate/Bundles/
git clone git://github.com/cabgfx/bootstrap-tmbundle.git Bootstrap.tmbundle
osascript -e 'tell app "TextMate" to reload bundles'
```

At the moment, only the following snippets are available in HTML or JS flavored files (eg. Rails templates).

(scope selector: `text.html, source.js`)

* Modal box
* Accordion 
* Accordion group

When using the accordion snippets, you can tab through attributes and quickly fill in everything without missing a spot.

It is currently targeting [Bootstrap 2](http://twitter.github.com/bootstrap).