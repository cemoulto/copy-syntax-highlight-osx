# Copy Syntax Highlight for OS X

Copy Syntax Highlight for OS X is an OS X service which copies the selected text to the clipboard, with proper syntax highlighting for the given language.

![](/img/syntax_highlight.gif)

## Usage

The intended primary use case is to Paste the copied syntax highlighted-text into productivity applications such as [Microsoft Word](https://products.office.com/en-us/word) and [Keynote](http://www.apple.com/mac/keynote/), keeping the code highlighting intact. Such highlighting can then be used in documents for publication and presentations for more spark, so to speak.

![](/img/hello-world.gif)

To use the tool, install the the [pygments](http://pygments.org) Python package. Then [download the Service](https://github.com/minimaxir/copy-syntax-highlight-osx/blob/master/Copy%20Syntax%20Highlight.zip) from this repository and install. On any text in any application, select the text and context-click, and the "Copy Syntax Highlight" menu item will be available. A prompt will appear asking for the language to lex the syntax highlight.

## To-do

* Input validation for copied text
* Theming (Dark/Solarized)

## Author/Maintainer

Max Woolf ([@minimaxir](http://minimaxir.com))

## Credits

Idea was inspired by comments on [this GitHub Gist](https://gist.github.com/jimbojsb/1630790), which linked to [this Stack Overflow](http://apple.stackexchange.com/questions/94222/how-to-get-automator-to-treat-text-as-rtf/94246#94246) answer.

Example GIF uses code sourced from [learnpython.org](http://www.learnpython.org/en/Hello,_World!). GIFs are rendered using the [Video to GIF OS X tool](https://github.com/minimaxir/video-to-gif-osx).

## License

MIT