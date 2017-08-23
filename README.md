# MD5-Hash
[![info badge](https://img.shields.io/npm/dt/md5-hash.svg)](https://npm-stat.com/charts.html?package=md5-hash)

A very small JS script for implementing md5 hashing.

## Installing

**npm**:
~~~
npm install md5-hash
~~~
**yarn**:
~~~
yarn add md5-hash
~~~
## API
`md5("String")`
- takes `String` params
- returns `32-bit` String

## Running the package

importing the package (es6 way):
~~~
import md5 from 'md5-hash'
md5("String")
~~~

with `require` statement:
~~~
var md5Hash = require("md5-hash")
md5Hash.default("String")
~~~
It will return `"27118326006d3829667a400ad23d5d98"`.

Does not work without calling default function. Thanks to [Mitul Islam](https://github.com/MitulIslam).
## License
[![GNU GPL v3.0](http://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl.html)

GNU GPL v3.0
