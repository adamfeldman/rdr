# rdr

A handy cli interface to searching and opening books from your calibre library or recently read titles from your library.

## Installation

Download from releases. Building requires oracles new AOT compiler for jvm based languages [graal](http://www.graalvm.org) Be advised that it is extremely memory hungry.

## Usage

At present

-q [query] wherein query can be anything that calibre would accept. Searches library for items matching query narrowing down selection with rofi or dmenu and opens choice. This is intended to be with the reader of choice but at present it is hard coded to zathura.

-r chose from the 30 most recently read titles from calibre library. Please note that recent reads are recorded by the app not calibre.

-l open most recently opened book

-o [file] open file then record metadata from calibre in recent reads rdr -o is intended to be made the default reader for ebook files so that opening books properly records them in recent reads

See rdr.org for coming development.

## Options

## Examples

### Bugs

Calibre returns incorrect results when you talk to the running process so this wont work with calibre running until this is fixed.
...


## License

GPL 3.0 or later.
Copyright © 2019 Michael Rose
