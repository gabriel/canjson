# json

This is a copy of the golang stdlib encoding/json package with additional options:

```golang
b, err := json.Marshal(i,
    json.EscapeHTML(false),           // Disable HTML escaping
    json.TerminateNewline(false),     // Don't append newline
    json.FieldOrder(json.NameOrder))  // Order by field name
```

For a canonical format, which uses the above options:

```golang
b, err := json.MarshalCanonical(i)
```
