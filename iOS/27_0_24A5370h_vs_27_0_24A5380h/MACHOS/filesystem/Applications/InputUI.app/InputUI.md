## InputUI

> `/Applications/InputUI.app/InputUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x6254` | `0x627f` | **`+0x2b`** |
| `__TEXT.__objc_methlist` | `0x22c4` | `0x22d4` | **`+0x10`** |
| `__DATA.__objc_const` | `0x5670` | `0x5678` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x1748` | `0x1750` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x160` | `0x168` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-109.10.0.0.0
+111.0.0.0.0

-  CStrings:  1400
+  CStrings:  1401
CStrings:
+ "_usesContainerForSelectionHandleHitTesting"
```
