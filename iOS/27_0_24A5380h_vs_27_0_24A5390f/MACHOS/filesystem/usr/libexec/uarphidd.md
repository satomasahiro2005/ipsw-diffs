## uarphidd

> `/usr/libexec/uarphidd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x720` | `0x740` | **`+0x20`** |
| `__TEXT.__text` | `0x4844` | `0x485c` | **`+0x18`** |
| `__TEXT.__cstring` | `0x6e2` | `0x6f7` | **`+0x15`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1587.0.21.0.0
+1587.0.27.0.0

-  CStrings:  350
+  CStrings:  351
Functions:
~ sub_100001b60 : 352 -> 376
CStrings:
+ "Bluetooth Low Energy"
```
