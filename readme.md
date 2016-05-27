# PLS
Programming Language Statistics.

## Installation
Either fork or [npm](http://npmjs.org) install:
```
npm install -g pls-js
```

## Usage
After installation, go into your project's directory and run `pls` to see language statistics.
```
pls [-options]
```

## Parameters
- `-ignore` (short: `-i`)
- `...`

#### -ignore
To speed things up, you might want to provide a directory path to ignore. If you need to ignore multiple, just pass the param again. Example:
```
pls -ignore=node_modules -i=vendor
```

## Contribute
Feel free to send pull requests if you have ideas on how to further improve the project.

## License
[MIT](https://opensource.org/licenses/MIT).
