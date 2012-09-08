__Note: These templates are not compatible with Xcode 4.x.__

<hr>

### About The Templates ###

These templates were derived from the default ones supplied with Xcode, with a few changes to suit my personal taste:

Projects

* All of the source files are contained in a `src` subdirectory.
* All of the resource files (nibs, localizations, `Info.plist`, etc.) are contained in a `rsrc` subdirectory.
* The prefix header includes `<iso646.h>`, which provides C++-style human-readable operators. (I've come to like these a lot.)
* The name of the project is not included in the `Prefix.h` or `Info.plist` filenames.

Files

* The boilerplate file comments have been removed. (That means you, `__MyCompanyName__`).
* Code is formatted in what is apparently known as the "One True Brace Style", [according to Wikipedia][1].

[1]: http://en.wikipedia.org/wiki/Indent_style#Variant:_1TBS


### Usage ###

To use the file and project templates, symlink the directories into:

    ~/Library/Application\ Support/Developer/Shared/Xcode/
