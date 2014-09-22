# lingon-cli

The command line interface to [lingon](http://github.com/jpettersson/lingon), a minimal static site generator inspired by Middleman and Sprockets.

# Installation

Install the lingon cli globally:

``
npm install -g lingon-cli
``

# Usage

This package will add a `lingon` binary to your path. It functions as a proxy to the lingon.js file and supports the exact same arguments.

```bash
# Generate a lingon new lingon project:
lingon new my-project # will clone https://github.com/javoire/lingon-template-minimal
lingon new my-project -t angular # will clone https://github.com/jpettersson/lingon-ng-template

# Start the server: 
lingon

# Build once and quit:
lingon build

# Show version: 
lingon -v

# Show help: 
lingon -h

# Start the server on a custom port:
lingon server -p 1111
```