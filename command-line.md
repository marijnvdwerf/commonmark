---
layout: default
title: Command Line
permalink: /command-line/
---

Command Line
============

Markdown can be converted at the command line using the `./bin/commonmark` script.

## Usage

    ./bin/commonmark [OPTIONS] [FILE]
    
* `-h`, `--help`: Shows help and usage information

If no file is given, input will be read from STDIN.

Output will be written to STDOUT.

## Examples

### Converting a file named document.md

    ./bin/commonmark document.md

### Converting a file and saving its output

    ./bin/commonmark document.md > output.html

### Converting from STDIN

    echo -e '# Hello World!' | ./bin/commonmark

### Converting from STDIN and saving the output

    echo -e '# Hello World!' | ./bin/commonmark > output.html