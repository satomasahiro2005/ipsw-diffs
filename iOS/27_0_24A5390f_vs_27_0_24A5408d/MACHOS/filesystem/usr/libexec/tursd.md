## tursd

> `/usr/libexec/tursd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x84a4` | `0x843c` | **`-0x68`** |
| `__TEXT.__objc_stubs` | `0x1ba0` | `0x1b40` | **`-0x60`** |
| `__TEXT.__objc_methname` | `0x3b38` | `0x3b0c` | **`-0x2c`** |
| `__DATA_CONST.__cfstring` | `0x820` | `0x800` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0xd18` | `0xd00` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x260` | `0x258` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x320` | `0x318` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1157.0.0.0.0
+1160.0.0.0.0

-  Symbols:   199
-  CStrings:  760
+  Symbols:   198
+  CStrings:  756
Symbols:
- _OBJC_CLASS_$_NSLocale
Functions:
~ sub_1000049dc : 124 -> 20
CStrings:
- "currentLocale"
- "en"
- "isEqualToString:"
- "languageCode"
```
