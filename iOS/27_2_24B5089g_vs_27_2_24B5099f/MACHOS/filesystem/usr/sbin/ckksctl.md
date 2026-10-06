## ckksctl

> `/usr/sbin/ckksctl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5d88` | `0x5e24` | **`+0x9c`** |
| `__TEXT.__cstring` | `0x1188` | `0x11c9` | **`+0x41`** |
| `__DATA_CONST.__cfstring` | `0x900` | `0x920` | **`+0x20`** |
| `__TEXT.__const` | `0x58` | `0x50` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-62460.40.56.502.1
+62460.40.74.0.0

-  CStrings:  317
+  CStrings:  319
Functions:
~ sub_1000023c8 : 6808 -> 6964
CStrings:
+ "lastLocalResetOperation"
+ "lastLocalResetOperation:             %s\n"
```
