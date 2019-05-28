# Cogito language definition bundle

Get Cogito syntax highlighting in [TextMate](http://macromates.com/) or [Sublime Text](http://www.sublimetext.com/) with this Language Definition bundle.

## Installation

### TextMate

Clone the repository into the TextMate/Bundles directory:

```bash
[ ! -f ~/Library/Application\ Support/TextMate/Bundles ] && mkdir -p ~/Library/Application\ Support/TextMate/Bundles
cd ~/Library/Application\ Support/TextMate/Bundles
git clone git://github.com/cogito-lang/cogito.tmbundle.git
osascript -e 'tell app "TextMate" to reload bundles'
```

### Sublime

Clone the repository into the Packages directory:

```bash
cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
git clone git://github.com/cogito-lang/cogito.tmbundle.git
```

Then start Sublime Text.

### Atom

Atom users can convert the bundle using the following syntax:

    apm init --package ~/.atom/packages/language-cogito --convert https://github.com/cogito-lang/cogito.tmbundle

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/cogito-lang/cogito.tmbundle.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
