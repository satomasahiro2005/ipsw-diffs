## ReplayKitModule

> `/System/Library/ControlCenter/Bundles/ReplayKitModule.bundle/ReplayKitModule`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbf94` | `0xc064` | **`+0xd0`** |
| `__TEXT.__objc_stubs` | `0x2100` | `0x2120` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x3089` | `0x309e` | **`+0x15`** |
| `__TEXT.__auth_stubs` | `0x540` | `0x550` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xcb0` | `0xcb8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x2b0` | `0x2b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   154
-  CStrings:  829
+  Symbols:   155
+  CStrings:  830
Symbols:
+ _MGGetProductType
Functions:
~ sub_b55c : 16 -> 224
CStrings:
+ "interfaceOrientation"
```
