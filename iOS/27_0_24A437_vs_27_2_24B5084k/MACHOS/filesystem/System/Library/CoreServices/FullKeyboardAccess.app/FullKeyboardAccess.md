## FullKeyboardAccess

> `/System/Library/CoreServices/FullKeyboardAccess.app/FullKeyboardAccess`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12c50` | `0x12d08` | **`+0xb8`** |
| `__TEXT.__objc_stubs` | `0x4c60` | `0x4ca0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0xf31` | `0xf69` | **`+0x38`** |
| `__TEXT.__objc_methname` | `0x5bd9` | `0x5bf6` | **`+0x1d`** |
| `__DATA.__objc_selrefs` | `0x18c8` | `0x18d8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-147.0.0.0.0
+148.2.0.0.0

-  CStrings:  1346
+  CStrings:  1349
Functions:
~ sub_100008f98 : 300 -> 484
CStrings:
+ "Adjusting the focused element's value for %@ (RTL: %@)."
+ "displayValue"
+ "numberWithBool:"
```
