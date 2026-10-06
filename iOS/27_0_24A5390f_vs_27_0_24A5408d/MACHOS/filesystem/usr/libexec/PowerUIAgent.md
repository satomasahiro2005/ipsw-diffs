## PowerUIAgent

> `/usr/libexec/PowerUIAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x828` | `0x858` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x173` | `0x193` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x260` | `0x280` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x98` | `0xa0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x90` | `0x98` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-753.0.15.0.0
+753.0.17.0.0

-  Symbols:   59
-  CStrings:  43
+  Symbols:   60
+  CStrings:  44
Symbols:
+ _kIBLMUnusualDrainNotification
Functions:
~ sub_100000b38 : 380 -> 428
CStrings:
+ "displayUnusualDrainNotification"
```
