## mDNSResponder

> `/usr/sbin/mDNSResponder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10b36c` | `0x10b364` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3111.40.42.0.0
+3111.40.45.0.0
Functions:
~ _BuildQuestion : 680 -> 672
CStrings:
+ "mDNSResponder-3111.40.45"
- "mDNSResponder-3111.40.42"
```
