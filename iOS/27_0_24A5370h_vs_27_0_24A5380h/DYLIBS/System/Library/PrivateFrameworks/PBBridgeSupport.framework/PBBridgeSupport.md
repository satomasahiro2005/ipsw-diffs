## PBBridgeSupport

> `/System/Library/PrivateFrameworks/PBBridgeSupport.framework/PBBridgeSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x19a0` | `—` | **`-0x19a0`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x19a0` | **`+0x19a0`** |
| `__DATA.__bss` | `0x1c0` | `0x130` | **`-0x90`** |
| `__DATA_DIRTY.__bss` | `—` | `0x90` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x7188` | `0x71b0` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x2568` | `0x2570` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x513c` | `0x5144` | **`+0x8`** |
| `__TEXT.__text` | `0x435d4` | `0x435d8` | **`+0x4`** |

### Other Changes

```diff

-1355.0.0.1.0
+1359.0.0.0.0

-  Functions: 1859
-  Symbols:   3263
+  Functions: 1860
+  Symbols:   3265
Symbols:
+ +[PBBridgeWatchAttributeController sharedController]
+ __OBJC_$_CLASS_PROP_LIST_PBBridgeWatchAttributeController
+ ___52+[PBBridgeWatchAttributeController sharedController]_block_invoke
+ _sharedController.__shared
+ _sharedController.onceToken
- ___58+[PBBridgeWatchAttributeController sharedDeviceController]_block_invoke
- _sharedDeviceController.__material
- _sharedDeviceController.onceToken
Functions:
~ +[PBBridgeWatchAttributeController sharedDeviceController] : 68 -> 4
+ +[PBBridgeWatchAttributeController sharedController]
```
