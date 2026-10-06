## Maps

> `/System/Library/Assistant/Plugins/Maps.assistantBundle/Maps`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x18068` | `0x180d0` | **`+0x68`** |
| `__TEXT.__cstring` | `0x9ec6` | `0x9efc` | **`+0x36`** |
| `__DATA_CONST.__cfstring` | `0x8400` | `0x8420` | **`+0x20`** |
| `__TEXT.__text` | `0x14518` | `0x14524` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2972.30.6.12.54
+2972.30.6.12.58

-  Functions: 1337
-  Symbols:   1294
-  CStrings:  1974
+  Functions: 1338
+  Symbols:   1295
+  CStrings:  1975
Symbols:
+ _MapsConfig_ContaineeViewControllerReconcilePresentationOnDismiss
Functions:
~ sub_114fc : 8 -> 12
+ sub_11508
CStrings:
+ "ContaineeViewControllerReconcilePresentationOnDismiss"
```
