## BiometricKitUI

> `/System/Library/PrivateFrameworks/BiometricKitUI.framework/BiometricKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x70e88` | `0x70fd0` | **`+0x148`** |
| `__TEXT.__oslogstring` | `0x6a83` | `0x6b13` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x10720` | `0x10790` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x7300` | `0x7368` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x1238` | `0x1260` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x4928` | `0x4950` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1ac8` | `0x1ad8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xa00` | `0xa08` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-685.1.2.0.0
+685.1.4.0.0

-  Functions: 2878
-  Symbols:   4586
-  CStrings:  1083
+  Functions: 2887
+  Symbols:   4600
+  CStrings:  1085
Symbols:
+ +[BKUIPearlEnrollController preloadCollectingFramesForAgeVerification:completion:]
+ +[BKUIPearlEnrollViewController preloadCollectingFramesForAgeVerification:completion:]
+ -[BKUIPearlEnrollController collectsFramesForAgeVerification]
+ -[BKUIPearlEnrollController setCollectsFramesForAgeVerification:]
+ -[BKUIPearlEnrollView initWithFrame:videoCaptureSession:inSheet:positioningGuideView:squareNeedsPositionLayout:collectsFramesForAgeVerification:]
+ -[BKUIPearlEnrollViewController collectsFramesForAgeVerification]
+ -[BKUIPearlEnrollViewController setCollectsFramesForAgeVerification:]
+ -[BKUIPearlVideoCaptureSession collectsFramesForAgeVerification]
+ -[BKUIPearlVideoCaptureSession initCollectingFramesForAgeVerification:]
+ GCC_except_table41
+ GCC_except_table50
+ GCC_except_table62
+ GCC_except_table63
+ GCC_except_table73
+ GCC_except_table97
+ _OBJC_IVAR_$_BKUIPearlEnrollViewController._collectsFramesForAgeVerification
+ _OBJC_IVAR_$_BKUIPearlVideoCaptureSession._collectsFramesForAgeVerification
+ ___145-[BKUIPearlEnrollView initWithFrame:videoCaptureSession:inSheet:positioningGuideView:squareNeedsPositionLayout:collectsFramesForAgeVerification:]_block_invoke
+ ___61-[BKUIPearlJindoEnrollViewController nextStateButtonPressed:]_block_invoke_2
+ ___86+[BKUIPearlEnrollViewController preloadCollectingFramesForAgeVerification:completion:]_block_invoke
+ ___block_descriptor_57_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
- GCC_except_table40
- GCC_except_table49
- GCC_except_table60
- GCC_except_table72
- GCC_except_table96
- ___112-[BKUIPearlEnrollView initWithFrame:videoCaptureSession:inSheet:positioningGuideView:squareNeedsPositionLayout:]_block_invoke
- ___55+[BKUIPearlEnrollViewController preloadWithCompletion:]_block_invoke
CStrings:
+ "CaptureSession: Collecting frames for age verification; setting up selfie session"
+ "CaptureSession: Not collecting frames for age verification; skipping selfie session"
+ "Will collect frames for age verification: %@"
+ "\x91"
- "Pearl: skipping Jindo banner post as enrollment is no longer active"
- "\x81"
```
