# hugo-cli

[![Build Status](https://travis-ci.org/nikku/hugo-cli.svg?branch=master)](https://travis-ci.org/nikku/hugo-cli)

A simple Node wrapper around [hugo, the static site generator](http://gohugo.io). It fetches the right hugo executable before piping all provided command line arguments to it.


## Installing

The first time this is run, it installs hugo into */node_modules/.bin* (It continues to run hugo after installing)
The default version is 0.37.1, but it will install the version defined in *hugo-version.json*
Use the following inside *hugo-version.json*:

format: `{ "hugo":"version number" }`
example: `{ "hugo":"0.40.1" }`


## Usage

With yarn: `yarn run hugo`

```bash
> hugo -h
hugo not downloaded yet. attempting to grab it...
decompressing hugo...
we got it, let's go!

hugo is the main command, used to build your Hugo site.

Hugo is a Fast and Flexible Static Site Generator built with love by spf13 and friends in Go.

Complete documentation is available at http://gohugo.io

Usage:
  hugo [flags]
  hugo [command]

...
```


## License

MIT

## About
Modified by Jonathan Burns