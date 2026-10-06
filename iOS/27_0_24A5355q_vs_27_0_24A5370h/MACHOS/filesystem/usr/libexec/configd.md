## configd

> `/usr/libexec/configd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x55f2` | `0x562c` | **`+0x3a`** |
| `__TEXT.__text` | `0x68bc0` | `0x68b8c` | **`-0x34`** |
| `__TEXT.__const` | `0x228` | `0x238` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xa38` | `0xa30` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1434.0.0.502.1
+1438.0.0.0.0

-  Functions: 957
+  Functions: 956
CStrings:
+ "%s : %5u : %s : %{private}@"
+ "%s : %5u : %{private}@"
+ "%s%s : %5u : %{private}@"
+ "*copy   : %5u : %{private}@"
+ "add  %s : %5u : %{private}@"
+ "list    : %5u : %s : %{private}@"
+ "open    : %5u : pid=%d"
- "%s : %5u : %@"
- "%s : %5u : %s : %@"
- "%s%s : %5u : %@"
- "*copy   : %5u : %@"
- "add  %s : %5u : %@"
- "list    : %5u : %s : %@"
- "open    : %5u : %@"
```
