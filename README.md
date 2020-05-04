# yaya
Yet Another Yet Another Markup Language

Yaya is JSON but with support for trailing commas and comments.

## Example:

This is a valid Yaya file:

```yaya
// example.yaya
{"key": "value",/* and now, an array */"key2": ["value1", "value2",]}, // trailing comment
```

## Parsers

### JavaScript

- [@rgrove/parse-yaya](https://github.com/rgrove/parse-yaya)
