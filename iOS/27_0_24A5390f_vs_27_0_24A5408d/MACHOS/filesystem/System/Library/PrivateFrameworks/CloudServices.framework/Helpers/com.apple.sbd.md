## com.apple.sbd

> `/System/Library/PrivateFrameworks/CloudServices.framework/Helpers/com.apple.sbd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x70e0` | `0x7080` | **`-0x60`** |
| `__TEXT.__text` | `0x4eff0` | `0x4ef90` | **`-0x60`** |
| `__TEXT.__objc_methname` | `0x7c49` | `0x7bf4` | **`-0x55`** |
| `__DATA_CONST.__cfstring` | `0x3d20` | `0x3d40` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x2040` | `0x2028` | **`-0x18`** |
| `__TEXT.__auth_stubs` | `0x1010` | `0x1000` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x818` | `0x810` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x10` | `0x8` | **`-0x8`** |
| `__TEXT.__cstring` | `0x43fc` | `0x43ff` | **`+0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-747.0.2.502.1
+747.0.6.0.0

-  Symbols:   511
-  CStrings:  2880
+  Symbols:   510
+  CStrings:  2878
Symbols:
- _memset
Functions:
~ sub_100015498 : 540 -> 444
CStrings:
+ "%d"
+ "appendFormat:"
- "decimalDigitCharacterSet"
- "invertedSet"
- "rangeOfCharacterFromSet:options:"
- "stringWithCharacters:length:"
```
