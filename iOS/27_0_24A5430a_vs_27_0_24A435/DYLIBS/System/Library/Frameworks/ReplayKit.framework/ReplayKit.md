## ReplayKit

> `/System/Library/Frameworks/ReplayKit.framework/ReplayKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36608` | `0x36c8c` | **`+0x684`** |
| `__TEXT.__cstring` | `0x816a` | `0x81db` | **`+0x71`** |
| `__DATA_CONST.__objc_selrefs` | `0x2140` | `0x21a0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xab8` | `0xae0` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x3658` | `0x3680` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1ec0` | `0x1ee0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xbe0` | `0xc00` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x4d0` | `0x4e0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x5c0` | `0x5c8` | **`+0x8`** |
| `__TEXT.__const` | `0x158` | `0x160` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 1413
-  Symbols:   2230
-  CStrings:  1093
+  Functions: 1418
+  Symbols:   2239
+  CStrings:  1096
Symbols:
+ -[RPPipViewController _updatePipVideoOrientationFromScene]
+ -[RPPipViewController viewIsAppearing:]
+ -[RPPipViewController viewWillTransitionToSize:withTransitionCoordinator:]
+ -[RPScreenRecorder windowSceneToCapture]
+ _MGGetProductType
+ _OBJC_CLASS_$_UIWindowScene
+ _UIWindowSceneSessionRoleApplication
+ ___74-[RPPipViewController viewWillTransitionToSize:withTransitionCoordinator:]_block_invoke
+ ___block_descriptor_40_e8_32s_e56_v16?0"<UIViewControllerTransitionCoordinatorContext>"8ls32l8
CStrings:
+ "-[RPPipViewController viewIsAppearing:]"
+ "Localizable-V68"
+ "v16@?0@\"<UIViewControllerTransitionCoordinatorContext>\"8"
```
