
# standard-format

  [![Build Status](https://travis-ci.org/uber/standard-format.svg)](https://travis-ci.org/uber/standard-format)

  **experimental** auto formatter for the easier cases in [uber-standard](https://www.npmjs.com/package/uber-standard)

  [![NPM](https://nodei.co/npm/uber-standard-format.png)](https://nodei.co/npm/uber-standard-format/)

## Installation

  Install with npm

    $ npm install -g uber-standard-format

## Example Usage

  Output all formatted javascript in a directory and subdirectories to stdout

    $ standard-format

  Format all javascript files, overwriting them into standard format

    $ standard-format -w

  Format javascript over stdin

    $ standard-format < file.js > formatted-file.js

  Format and overwrite specific files

    $ standard-format -w file1.js file2.js

# Credits

This is a fork of [maxogden/standard-format](https://github.com/maxogden/standard-format)
