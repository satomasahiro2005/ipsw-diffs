## BiometricKitUI

> `/System/Library/PrivateFrameworks/BiometricKitUI.framework/BiometricKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x700a0` | `0x70538` | **`+0x498`** |
| `__TEXT.__oslogstring` | `0x66a3` | `0x6853` | **`+0x1b0`** |
| `__AUTH_CONST.__objc_const` | `0x106e0` | `0x10700` | **`+0x20`** |
| `__TEXT.__cstring` | `0x2fc6` | `0x2fd6` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x48d0` | `0x48d8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x72b8` | `0x72c0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x9f8` | `0x9fc` | **`+0x4`** |

### Other Changes

```diff

-681.0.0.0.0
+684.0.0.0.0

-  Functions: 2867
-  Symbols:   4576
-  CStrings:  1061
+  Functions: 2868
+  Symbols:   4578
+  CStrings:  1068
Symbols:
+ -[BKUIPearlEnrollView resetPitchCorrection]
+ GCC_except_table71
+ GCC_except_table95
+ _OBJC_IVAR_$_BKUIPearlEnrollView._lastLoggedCenterBinCorrectedPitch
- GCC_except_table70
- GCC_except_table94
CStrings:
+ "Displaying instruction to reposition: '%s'"
+ "Init: productType: %{public}ld, isZoomEnabled: %{public}d, shouldUseUnifiedMesaEnrollment: %{public}d"
+ "LOWER"
+ "RAISE"
+ "centerBin correctedPitch %0.2f (rawPitch %0.2f - pitchCorrection %0.2f), window [%0.2f, %0.2f]"
+ "correctedPitch %0.2f (rawPitch %0.2f - pitchCorrection %0.2f) vs window [%0.2f, %0.2f] -> %s"
+ "resetPitchCorrection - clearing pitchCorrection %0.2f (samples: %lu, observedPitchRange: [%0.2f, %0.2f], state: %ld)"
+ "seeded pitchCorrection %0.2f from %d initial samples (state: %ld)"
+ "\xf0\xf0\x82"
- "Init: isZoomEnabled: %{public}d, shouldUseUnifiedMesaEnrollment: %{public}d"
- "\xf0\xf0r"
```
