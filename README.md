## Bintools

Basic binary utils meta-package (ncp, rimraf, mkdirp) for Node.js, for use in cross-platform NPM scripts


### Installation

    npm install bintools

### Usage

Use in cross-platform NPM build scripts:

```
  "scripts": {
    "build": "mkdirp build/production && ncp config/index.html && browserify -o build/production/fido.js src/index.js"
  }

```

Should work across all major Node.js platforms, including Windows, OSX, and Linux (please file issue otherwise).

## License

* nc: MIT, copyright (C) 2011 by Charlie McConnell
* mkdirp: MIT, Copyright 2010 James Halliday (mail@substack.net)
* rimraf: The ISC License, Copyright (c) Isaac Z. Schlueter and Contributors
