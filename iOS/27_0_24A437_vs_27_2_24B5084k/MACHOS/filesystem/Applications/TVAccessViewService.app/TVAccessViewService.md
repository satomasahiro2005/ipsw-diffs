## TVAccessViewService

> `/Applications/TVAccessViewService.app/TVAccessViewService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa48` | `0xa74` | **`+0x2c`** |
| `__TEXT.__objc_stubs` | `0x260` | `0x280` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x34d` | `0x367` | **`+0x1a`** |
| `__DATA_CONST.__objc_arrayobj` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__cstring` | `0x44` | `0x58` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0x220` | `0x230` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xe8` | `0xf0` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x120` | `0x128` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x60` | `0x68` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `—` | `0x8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1145.1.3.0.0
+1145.10.20.0.0

-  Symbols:   56
-  CStrings:  60
+  Symbols:   60
+  CStrings:  64
Symbols:
+ _OBJC_CLASS_$_NSConstantArray
+ _OBJC_CLASS_$_NSConstantIntegerNumber
+ _OBJC_CLASS_$_TVASCapabilityRegistryObjC
+ __os_feature_enabled_impl
Functions:
~ sub_10000163c -> sub_10000172c : 88 -> 132
CStrings:
+ "TVApp"
+ "q"
+ "registerWithCapabilities:"
+ "sp_personal"
```
