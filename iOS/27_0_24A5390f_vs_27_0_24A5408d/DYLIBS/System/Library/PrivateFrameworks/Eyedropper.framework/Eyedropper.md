## Eyedropper

> `/System/Library/PrivateFrameworks/Eyedropper.framework/Eyedropper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x66c4` | `0x6d5c` | **`+0x698`** |
| `__AUTH_CONST.__objc_const` | `0x1140` | `0x11a0` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0xb40` | `0xb88` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0xc8c` | `0xcd4` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x1f8` | `0x210` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x250` | `0x268` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0xa0` | `0xac` | **`+0xc`** |
| `__TEXT.__cstring` | `0x18f` | `0x190` | **`+0x1`** |

### Other Changes

```diff

-9127.0.53.0.0
+9127.0.81.0.0

-  Functions: 147
-  Symbols:   496
+  Functions: 153
+  Symbols:   511
Symbols:
+ -[EDAppDelegate _attachedSceneDelegatePreferringDisplay:]
+ -[EDAppDelegate _attachedSceneDelegate]
+ -[EDAppDelegate _performFloatEyeDropper]
+ -[EDAppDelegate _performShowEyeDropperForRequestedDisplay:]
+ -[EDAppDelegate _runDeferredEyeDropperOpsIfReady]
+ -[EDAppDelegate _sceneDidActivate:]
+ GCC_except_table18
+ GCC_except_table30
+ _OBJC_CLASS_$_UIWindowScene
+ _OBJC_IVAR_$_EDAppDelegate._hasPendingFloat
+ _OBJC_IVAR_$_EDAppDelegate._hasPendingShow
+ _OBJC_IVAR_$_EDAppDelegate._pendingShowDisplayHardwareIdentifier
+ _UISceneDidActivateNotification
+ ___59-[EDAppDelegate _performShowEyeDropperForRequestedDisplay:]_block_invoke
+ _objc_opt_class
+ _objc_opt_isKindOfClass
+ _objc_opt_self
+ _objc_retain_x9
- GCC_except_table14
- GCC_except_table26
- ___49-[EDAppDelegate beginShowingEyeDropper:settings:]_block_invoke_2
```
