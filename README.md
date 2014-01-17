# grunt-crane-javascript

Builder for grunt-crane, which build and compress javascript files.

## Installation

```shell
npm install grunt-crane-javascript --save-dev
```

## Usage

Once the plugin has been installed, specify your file with this builder:

```javascript
builder: [
    ["some.js", require("grunt-crane-javascript/builder/javascript")]
]
```