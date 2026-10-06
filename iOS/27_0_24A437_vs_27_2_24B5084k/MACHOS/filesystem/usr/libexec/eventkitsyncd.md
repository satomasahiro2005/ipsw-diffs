## eventkitsyncd

> `/usr/libexec/eventkitsyncd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0xcc20` | `0xcc40` | **`+0x20`** |
| `__TEXT.__text` | `0x761dc` | `0x761f8` | **`+0x1c`** |
| `__TEXT.__objc_methname` | `0xfcc5` | `0xfcd6` | **`+0x11`** |
| `__DATA.__objc_selrefs` | `0x3f78` | `0x3f80` | **`+0x8`** |

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
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-431.0.0.0.0
+432.0.0.0.0

-  CStrings:  4641
+  CStrings:  4642
Functions:
~ sub_10001d914 : 1212 -> 1240
CStrings:
+ "== Started EventKitSync-432"
+ "emptyMeltedCache"
- "== Started EventKitSync-431"
```
