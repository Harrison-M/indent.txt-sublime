# Indent.txt Sublime
Turn your indented notes into HTML in Sublime Text 2

## How to use

### Sublime Text 2
1. Place this repository's folder in your Sublime Packages folder or install using [Sublime Package Control](http://wbond.net/sublime_packages/package_control)
2. Run the "Indent.txt: Parse" command from the command palette (Ctrl-Shift-P) on a file or selection from a file
3. The resulting HTML will open in a new tab.

## Formatting
Examples of most formatting marks can be found in test.txt with the results in [output.html](https://github.com/Harrison-M/indent.txt/blob/master/output.html) in the main [Indent.txt](https://github.com/Harrison-M/indent.txt) repository

* Prefixing a line with a single asterisk (*) will wrap the item in an &lt;em&gt; tag
* Prefixing a line with two asterisks (**) will wrap the item in a &lt;strong&gt; tag
* Prefixing a line with two forward slashes (//) indicates a comment, excluding the line from the results.  This will eventually be used for metadata and parser instructions.

## Like Indent.txt?

[![endorse](http://api.coderwall.com/harrisonm/endorsecount.png)](http://coderwall.com/harrisonm)

## License
MIT

## Coming soon:
* More formatting
* Automatic table of contents
* Mark lines as Todo.txt items
