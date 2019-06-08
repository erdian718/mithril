# Mithril.js

[Mithril.js](https://mithril.js.org/) bindings for [Lua](https://github.com/ofunc/lua).

## Usage

```lua
local m = require 'mithril'
local js = require 'js'

m:render(js.global.document.body, 'Hello world')
```

Please Refer to [Mithril.js](https://mithril.js.org/).

NOTE: You can use `Promise.ok` instead of `Promise.then`.

## Dependencies

* [ofunc/lua](https://github.com/ofunc/lua)
* [Mithril.js](https://mithril.js.org/)
