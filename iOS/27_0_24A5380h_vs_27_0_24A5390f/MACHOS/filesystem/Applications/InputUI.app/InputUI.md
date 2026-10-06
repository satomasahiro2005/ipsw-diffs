## InputUI

> `/Applications/InputUI.app/InputUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__objc_const` | `0x5678` | `0x5708` | **`+0x90`** |
| `__TEXT.__objc_methname` | `0x627f` | `0x62d7` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x22d4` | `0x2304` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x1750` | `0x1770` | **`+0x20`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-111.0.0.0.0
+114.0.0.0.0

-  CStrings:  1401
+  CStrings:  1405
CStrings:
+ "grammarCheckingType"
+ "preferKeyboardInput"
+ "setGrammarCheckingType:"
+ "setPreferKeyboardInput:"
```
