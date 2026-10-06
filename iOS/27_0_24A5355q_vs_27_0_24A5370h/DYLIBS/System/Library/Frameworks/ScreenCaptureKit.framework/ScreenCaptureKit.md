## ScreenCaptureKit

> `/System/Library/Frameworks/ScreenCaptureKit.framework/ScreenCaptureKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36ad4` | `0x36770` | **`-0x364`** |
| `__TEXT.__cstring` | `0x5ad8` | `0x5bb8` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x3b72` | `0x3c42` | **`+0xd0`** |
| `__DATA_CONST.__const` | `0xb40` | `0xaf0` | **`-0x50`** |
| `__TEXT.__gcc_except_tab` | `0x544` | `0x55c` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x22e0` | `0x22d0` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x381c` | `0x380c` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xd00` | `0xcf0` | **`-0x10`** |

### Other Changes

```diff

-740.44.1.0.0
+740.48.1.0.0

-  Functions: 1451
-  Symbols:   2558
-  CStrings:  845
+  Functions: 1441
+  Symbols:   2549
+  CStrings:  855
Symbols:
+ GCC_except_table176
+ GCC_except_table179
+ GCC_except_table182
+ GCC_except_table186
+ GCC_except_table228
+ GCC_except_table230
+ GCC_except_table254
+ GCC_except_table256
- -[SCStream updateStreamConfiguration:completionHandler:]
- GCC_except_table181
- GCC_except_table187
- GCC_except_table189
- GCC_except_table191
- GCC_except_table243
- GCC_except_table245
- GCC_except_table259
- GCC_except_table261
- _OUTLINED_FUNCTION_13
- _OUTLINED_FUNCTION_14
- ___50-[SCStream updateConfiguration:completionHandler:]_block_invoke
- ___50-[SCStream updateConfiguration:completionHandler:]_block_invoke_2
- ___50-[SCStream updateContentFilter:completionHandler:]_block_invoke
- ___50-[SCStream updateContentFilter:completionHandler:]_block_invoke_2
- ___block_descriptor_64_e8_32s40s48s56bs_e17_v16?0"NSError"8ls32l8s40l8s56l8s48l8
- ___block_descriptor_72_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s64l8s56l8
CStrings:
+ " [INFO] %{public}s:%d %p: bg notification fired"
+ " [INFO] %{public}s:%d %p: bg/fg observers registered (single pair)"
+ " [INFO] %{public}s:%d %p: early-return, already running"
+ " [INFO] %{public}s:%d %p: early-return, not running"
+ " [INFO] %{public}s:%d %p: enter (isRunning=%d)"
+ " [INFO] %{public}s:%d %p: fg notification fired"
+ "-[SCVideoEffectOutput _handleDidEnterBackground:]"
+ "-[SCVideoEffectOutput _handleWillEnterForeground:]"
+ "-[SCVideoEffectOutput _pauseCameraSession]"
+ "-[SCVideoEffectOutput dealloc]"
+ "-[SCVideoEffectOutput startCameraSession]"
+ "-[SCVideoEffectOutput startCameraSession]_block_invoke"
+ "-[SCVideoEffectOutput stopCameraSession]"
+ "-[SCVideoEffectOutput stopCameraSession]_block_invoke"
- " [INFO] %{public}s:%d content filter did not change"
- " [INFO] %{public}s:%d stream configuration did not change"
- "-[SCStream updateConfiguration:completionHandler:]_block_invoke_2"
- "-[SCStream updateContentFilter:completionHandler:]_block_invoke_2"
```
