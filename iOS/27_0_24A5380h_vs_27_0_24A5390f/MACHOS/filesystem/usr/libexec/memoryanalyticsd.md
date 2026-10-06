## memoryanalyticsd

> `/usr/libexec/memoryanalyticsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__got` | `0x200` | `0x228` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x35c0` | `0x35e0` | **`+0x20`** |
| `__DATA_CONST.__objc_intobj` | `0x840` | `0x858` | **`+0x18`** |
| `__TEXT.__text` | `0x19554` | `0x1956c` | **`+0x18`** |
| `__TEXT.__cstring` | `0x3478` | `0x348e` | **`+0x16`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-97.0.0.0.0
+100.0.0.0.0

-  CStrings:  1437
+  CStrings:  1438
Functions:
~ sub_10000993c : 3648 -> 3672
CStrings:
+ "SetStoreUpdateService"
```
