## `color:linear_rgba()`

*Since: nightly builds only*

Returns a tuple of the colors converted to linear RGBA and
expressed as floating point numbers in the range `0.0-1.0`:

```
> r, g, b, a = wezterm.color.parse("purple"):linear_rgba()
> print(r, g, b, a)
07:32:17.734 INFO logging > lua: 0.2158605307340622 0 0.2158605307340622 1
```

