## CloudKitSettings

> `/System/Library/PreferenceBundles/AccountSettings/CloudKitSettings.bundle/CloudKitSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x78d4` | `0x790c` | **`+0x38`** |
| `__DATA_CONST.__cfstring` | `0x1740` | `0x1760` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1660` | `0x1680` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1b2b` | `0x1b43` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x350` | `0x360` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x6a0` | `0x6a8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__TEXT.__cstring` | `0x176e` | `0x1776` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2710.116.0.0.0
+2710.119.0.0.0

-  Symbols:   146
-  CStrings:  475
+  Symbols:   147
+  CStrings:  477
Symbols:
+ _objc_retain
Functions:
~ sub_1208 : 180 -> 236
CStrings:
+ "pathForResource:ofType:"
+ "strings"
```
