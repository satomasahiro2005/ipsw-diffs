## PhotosDestructiveChangeConfirmation

> `/System/Library/ExtensionKit/Extensions/PhotosDestructiveChangeConfirmation.appex/PhotosDestructiveChangeConfirmation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12e8` | `0x14ac` | **`+0x1c4`** |
| `__TEXT.__oslogstring` | `0x4a` | `0x108` | **`+0xbe`** |
| `__TEXT.__objc_stubs` | `0x820` | `0x8a0` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x88f` | `0x8c5` | **`+0x36`** |
| `__TEXT.__gcc_except_tab` | `0x60` | `0x90` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x2d0` | `0x2f0` | **`+0x20`** |
| `__TEXT.__const` | `0x20` | `0x30` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-910.21.101.0.0
+910.27.103.0.0

-  CStrings:  143
+  CStrings:  150
Functions:
~ sub_1000012c4 : 436 -> 820
~ sub_100001478 -> sub_1000015f8 : 224 -> 292
CStrings:
+ "Image for asset: %@, width: %tu, height: %tu, MP: %.3f, isRaw: %d, deferredProcessingNeeded: %d"
+ "Image for asset: Fallback to fast mode"
+ "Image for asset: overriding delivery mode for 48MP RAW"
+ "deferredProcessingNeeded"
+ "isRAW"
+ "pixelHeight"
+ "pixelWidth"
```
