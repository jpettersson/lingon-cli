# lingon-cli

The command line interface to [lingon](http://github.com/jpettersson/lingon), a minimal static site generator inspired by Middleman and Sprockets.

# Installation

Install the lingon cli globally:

``
npm install -g lingon-cli
``

# Usage

This package will add a `lingon` binary to your path. It functions as a proxy to the lingon.js file and supports the exact same arguments.

```
Show version: 
lingon -v

Show help: 
lingon -h

Build once and quit:
lingon build

Start the server: 
lingon

Start the server on a custom port:
lingon server -p 1111
```
