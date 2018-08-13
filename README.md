# hugo-cli (Custom branch)

A simple Node wrapper around [hugo, the static site generator](http://gohugo.io). It fetches the right hugo executable before piping all provided command line arguments to it.

### Add to a project
With `yarn add https://github.com/UXSoc/hugo-cli/archive/0.6.2.tar.gz` in terminal

or `npm install --save-dev https://github.com/UXSoc/hugo-cli/archive/0.6.2.tar.gz`

## Installing Hugo

The first time this is run, it installs hugo into */node_modules/.bin* (It continues to run hugo after installing)

The default version is 0.37.1, but it will install the version defined in *hugo-version.json* which should be placed in the same directory as *package.lock*. The hugo config file is from source_location, the default is the same location as yarn.
Use the following inside *hugo-version.json*:

format: `{ "hugo":"version number", "source_location": "path" }`
example: `{ "hugo":"0.40.1", "source_location": "../../" }`


## Usage

With yarn: `yarn hugo`

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
Modified by Jonathan Burns: https://github.com/jhburns.
For UX Society and general use.
