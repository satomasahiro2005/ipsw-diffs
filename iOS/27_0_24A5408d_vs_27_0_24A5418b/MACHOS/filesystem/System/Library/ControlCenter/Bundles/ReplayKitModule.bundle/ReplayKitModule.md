## ReplayKitModule

> `/System/Library/ControlCenter/Bundles/ReplayKitModule.bundle/ReplayKitModule`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbf6c` | `0xbf94` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x20e0` | `0x2100` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x530` | `0x540` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x307a` | `0x3089` | **`+0xf`** |
| `__DATA.__objc_selrefs` | `0xca8` | `0xcb0` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x2a8` | `0x2b0` | **`+0x8`** |

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

-740.63.1.1.0
+740.63.1.2.0

-  Symbols:   153
+  Symbols:   154
Symbols:
+ _objc_opt_respondsToSelector
Functions:
~ sub_b56c : 140 -> 116
~ sub_b5f8 -> sub_b5e0 : 416 -> 480
CStrings:
+ "presentationInterfaceOrientation"
- "_geometryProvider"
```
