## PSAccessControllerHIDServicePlugin

> `/System/Library/HIDPlugins/ServicePlugins/PSAccessControllerHIDServicePlugin.plugin/PSAccessControllerHIDServicePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x46c4` | `0x4624` | **`-0xa0`** |
| `__DATA_CONST.__cfstring` | `0x200` | `0x1c0` | **`-0x40`** |
| `__TEXT.__objc_stubs` | `0x4e0` | `0x4c0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x45c` | `0x449` | **`-0x13`** |
| `__TEXT.__auth_stubs` | `0x3a0` | `0x390` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x655` | `0x64c` | **`-0x9`** |
| `__DATA.__objc_selrefs` | `0x248` | `0x240` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x1e0` | `0x1d8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x50` | `0x48` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x170` | `0x168` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-14.0.17.0.0
+14.0.19.0.0

-  Symbols:   79
-  CStrings:  223
+  Symbols:   77
+  CStrings:  220
Symbols:
- _IORegistryEntryCreateCFProperty
- _kCFAllocatorDefault
Functions:
~ sub_db8 : 216 -> 56
CStrings:
- "ProductID"
- "VendorID"
- "intValue"
```
