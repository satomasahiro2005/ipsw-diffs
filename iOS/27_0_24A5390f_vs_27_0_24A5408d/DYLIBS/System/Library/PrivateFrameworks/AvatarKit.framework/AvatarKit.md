## AvatarKit

> `/System/Library/PrivateFrameworks/AvatarKit.framework/AvatarKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77a28` | `0x77bb0` | **`+0x188`** |
| `__DATA_CONST.__const` | `0x27f0` | `0x2818` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0xdd38` | `0xdd58` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1df4b` | `0x1df64` | **`+0x19`** |
| `__TEXT.__unwind_info` | `0x1bd0` | `0x1be0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d70` | `0x3d78` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xddc` | `0xde4` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x54bc` | `0x54b4` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xa50` | `0xa54` | **`+0x4`** |

### Other Changes

```diff

-366.0.0.0.0
+367.0.0.0.0

-  Symbols:   4666
-  CStrings:  5159
+  Symbols:   4668
+  CStrings:  5160
Symbols:
+ -[AVTView _windowDidRotateNotification:]
+ _OBJC_IVAR_$_AVTView._windowDidRotateObserver
+ _UIWindowDidRotateNotification
+ ___26-[AVTView didMoveToWindow]_block_invoke
+ ___block_descriptor_40_e8_32w_e24_v16?0"NSNotification"8lw32l8
- -[AVTView _UIOrientationDidChangeNotification:]
- -[AVTView setupOrientation]
- _UIApplicationDidChangeStatusBarOrientationNotification
Functions:
~ ___73-[AVTAvatarPoseAnimation _initWithSceneKitScene:usdaMetadata:identifier:]_block_invoke : 360 -> 364
~ __AVTAvatarPoseImportSceneKitAnimation : 2084 -> 2168
~ -[AVTView dealloc] : 148 -> 172
~ -[AVTView didMoveToWindow] : 76 -> 360
~ -[AVTView setupOrientation] -> ___26-[AVTView didMoveToWindow]_block_invoke : 116 -> 92
~ -[AVTView updateInterfaceOrientation] -> -[AVTView _windowDidRotateNotification:] : 156 -> 4
~ -[AVTView _UIOrientationDidChangeNotification:] -> -[AVTView updateInterfaceOrientation] : 4 -> 156
~ -[AVTView .cxx_destruct] : 336 -> 356
CStrings:
+ "v16@?0@\"NSNotification\"8"
```
