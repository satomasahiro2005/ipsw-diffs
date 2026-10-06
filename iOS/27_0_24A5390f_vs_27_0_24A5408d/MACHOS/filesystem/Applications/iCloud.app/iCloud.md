## iCloud

> `/Applications/iCloud.app/iCloud`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16d80` | `0x16db8` | **`+0x38`** |
| `__DATA_CONST.__cfstring` | `0x2360` | `0x2380` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x3320` | `0x3340` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x471b` | `0x4733` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x1058` | `0x1060` | **`+0x8`** |
| `__TEXT.__cstring` | `0x2ccb` | `0x2cd3` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2710.116.0.0.0
+2710.119.0.0.0

-  CStrings:  1222
+  CStrings:  1224
Functions:
~ sub_100003c10 : 180 -> 236
CStrings:
+ "pathForResource:ofType:"
+ "strings"
```
