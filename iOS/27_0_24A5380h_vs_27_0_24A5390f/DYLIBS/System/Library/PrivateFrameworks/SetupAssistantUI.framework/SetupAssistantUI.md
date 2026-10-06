## SetupAssistantUI

> `/System/Library/PrivateFrameworks/SetupAssistantUI.framework/SetupAssistantUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x1208` | `0x1248` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x2f8` | `0x2d8` | **`-0x20`** |
| `__TEXT.__text` | `0x237d8` | `0x237f8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2410` | `0x2428` | **`+0x18`** |
| `__DATA.__bss` | `0x140` | `0x130` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x3690` | `0x36a0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x480` | `0x488` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x110` | `0x118` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xa48` | `0xa40` | **`-0x8`** |

### Other Changes

```diff

-5407.0.0.0.0
+5409.0.0.0.0

-  Functions: 930
-  Symbols:   1980
-  CStrings:  208
+  Functions: 928
+  Symbols:   1977
+  CStrings:  209
Symbols:
+ -[BFFFinishSetupModalNavigationController viewIsAppearing:]
+ GCC_except_table29
+ _OBJC_CLASS_$_OBBaseWelcomeController
- GCC_except_table17
- GCC_except_table28
- ___isDeviceXL_block_invoke
- _isDeviceXL
- _isDeviceXL._isDeviceXL
- _isDeviceXL.onceToken
CStrings:
+ "Face ID Enroll user did cancel (Cancel button)"
+ "Face ID Enroll user did skip (Set Up Later button)"
- "Face ID Enroll user did cancel"
```
