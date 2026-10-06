## trustdFileHelper

> `/usr/libexec/trustdFileHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x540` | `0x5c0` | **`+0x80`** |
| `__TEXT.__cstring` | `0x481` | `0x4fd` | **`+0x7c`** |
| `__TEXT.__text` | `0x1dac` | `0x1e00` | **`+0x54`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-62460.0.55.0.1
+62460.2.1.0.0

-  CStrings:  162
+  CStrings:  166
Symbols:
+ _objc_retain_x25
- _objc_retain_x24
Functions:
~ sub_100001918 : 1276 -> 1360
CStrings:
+ "private/TrustStore.sqlite3"
+ "private/TrustStore.sqlite3-journal"
+ "private/TrustStore.sqlite3-shm"
+ "private/TrustStore.sqlite3-wal"
```
