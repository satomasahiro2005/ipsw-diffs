## DisplayFilterUIServer

> `/System/Library/AccessibilityBundles/DisplayFilterUIServer.axuiservice/DisplayFilterUIServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20e4` | `0x2198` | **`+0xb4`** |
| `__DATA_CONST.__cfstring` | `0x180` | `0x1a0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xaa0` | `0xac0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0xf60` | `0xf74` | **`+0x14`** |
| `__TEXT.__cstring` | `0x160` | `0x172` | **`+0x12`** |
| `__DATA.__objc_selrefs` | `0x448` | `0x450` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x110` | `0x118` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x4b3` | `0x4b6` | **`+0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3245.8.2.0.0
+3245.8.4.2.0

-  CStrings:  231
+  CStrings:  233
Functions:
~ sub_1270 : 376 -> 392
~ sub_13e8 -> sub_13f8 : 216 -> 224
~ sub_14c0 -> sub_14d8 : 244 -> 248
~ sub_19a0 -> sub_19bc : 488 -> 552
~ sub_2804 -> sub_2860 : 328 -> 416
CStrings:
+ "_fadeDisplayForSmartInvertStartWithDuration:maskOpaqueCompletion:"
+ "animationDuration"
+ "doubleValue"
+ "objectForKeyedSubscript:"
+ "v32@0:8d16@?24"
- "_fadeDisplayForSmartInvertStartWithMaskOpaqueCompletion:"
- "objectAtIndexedSubscript:"
- "v24@0:8@?16"
```
