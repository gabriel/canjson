# json

This is a copy of the golang stdlib encoding/json package with the options:

```golang
json.Marshal(i,
    json.EscapeHTML(false),           // Disable escaping
    json.TerminateNewline(false),     // Don't append newline
    json.FieldOrder(json.NameOrder))  // Order by field name
```
