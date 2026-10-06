## assetsd

> `/System/Library/Frameworks/AssetsLibrary.framework/Support/assetsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17fec` | `0x180a4` | **`+0xb8`** |
| `__TEXT.__objc_methname` | `0x54c7` | `0x554b` | **`+0x84`** |
| `__TEXT.__objc_stubs` | `0x4a00` | `0x4a60` | **`+0x60`** |
| `__DATA.__objc_const` | `0x2c98` | `0x2cd0` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0xdc4` | `0xdec` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x1450` | `0x1468` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x906` | `0x91d` | **`+0x17`** |
| `__TEXT.__auth_stubs` | `0xb30` | `0xb40` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x5a8` | `0x5b0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x6f8` | `0x700` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x7c` | `0x80` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-910.21.101.0.0
+910.27.103.0.0

+  - /System/Library/PrivateFrameworks/MediaConversionService.framework/MediaConversionService

-  Functions: 354
-  Symbols:   415
-  CStrings:  1241
+  Functions: 357
+  Symbols:   416
+  CStrings:  1247
Symbols:
+ _objc_opt_respondsToSelector
CStrings:
+ "@\"<PLMaintenanceTask>\""
+ "T@\"<PLMaintenanceTask>\",&,V_currentMaintenanceTask"
+ "_currentMaintenanceTask"
+ "cancel"
+ "currentMaintenanceTask"
+ "setCurrentMaintenanceTask:"
```
