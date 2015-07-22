timed-tape
==========

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](http://ipn.io) [![](https://img.shields.io/badge/freenode-%23ipfs-blue.svg?style=flat-square)](http://webchat.freenode.net/?channels=%23ipfs)

> Prints the time each test took

# Usage

```
var tape = require('./timed-tape')(require('tape'))
```

Returns a tape instance that will print the time that each test took
