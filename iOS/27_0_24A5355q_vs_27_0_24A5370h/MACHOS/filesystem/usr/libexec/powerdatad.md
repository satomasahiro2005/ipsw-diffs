## powerdatad

> `/usr/libexec/powerdatad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7560` | `0x7578` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2015.0.0.0.1
+2041.0.0.502.1
Functions:
~ sub_100003480 : 2704 -> 2700
~ sub_100003fe4 -> sub_100003fe0 : 1284 -> 1280
~ sub_10000580c -> sub_100005804 : 112 -> 128
~ sub_10000587c -> sub_100005884 : 92 -> 108
```
