# canjson

This is a copy of the encoding/json stdlib package with the following changes:

- Doesn't escape HTML or unicode by default
- Keys are ordered by tag name, not the order in struct
- Encode: A newline is not appended
