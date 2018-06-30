# defold-hashed

A small utility library to automatically use hashed strings.

It computes Defold hashes for strings at runtime and caches the result.

Usage:
```lua
local hashed = require('hashed')
print(hashed.hello_world)
print(hashed.any_compatible_string)
print(hashed['any string with any characters'])
```