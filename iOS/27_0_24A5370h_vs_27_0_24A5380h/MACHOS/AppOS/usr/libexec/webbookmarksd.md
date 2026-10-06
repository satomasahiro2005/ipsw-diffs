## webbookmarksd

> `/usr/libexec/webbookmarksd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x180d0` | `0x180a8` | **`-0x28`** |
| `__TEXT.__objc_stubs` | `0x3ba0` | `0x3bc0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x483a` | `0x4856` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x1178` | `0x1180` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7625.1.20.10.3
+7625.1.22.10.3

-  CStrings:  1001
+  CStrings:  1002
Symbols:
+ _OBJC_CLASS_$_WBUHistory
- _WBUHistoryDefaultItemAgeLimit
Functions:
~ sub_100011700 : 800 -> 784
~ sub_100011c7c -> sub_100011c6c : 828 -> 804
CStrings:
+ "importHistoryAgeLimitCutoff"
```
