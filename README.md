# Cogito Language Definition Bundle

Get Cogito syntax highlighting in [TextMate](http://macromates.com/) or [Sublime Text](http://www.sublimetext.com/) with this Language Definition bundle.

## Installation for TextMate

Clone this bundle into your TextMate/Bundles directory:

```bash
[ ! -f ~/Library/Application\ Support/TextMate/Bundles ] && mkdir -p ~/Library/Application\ Support/TextMate/Bundles
cd ~/Library/Application\ Support/TextMate/Bundles
git clone git://github.com/localytics/cogito.tmbundle.git
osascript -e 'tell app "TextMate" to reload bundles'
```

## Installation for Sublime Text 2

Sublime Text users can do similarly by cloning the repository into the Packages directory:

```bash
cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
git clone git://github.com/localytics/cogito.tmbundle.git
```

Then start Sublime Text.

## Installation for Atom

Atom users can convert the bundle using the following syntax:

    apm init --package ~/.atom/packages/language-cogito --convert https://github.com/localytics/cogito.tmbundle
