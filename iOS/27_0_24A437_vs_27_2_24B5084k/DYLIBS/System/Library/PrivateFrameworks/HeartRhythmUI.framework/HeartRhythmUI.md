## HeartRhythmUI

> `/System/Library/PrivateFrameworks/HeartRhythmUI.framework/HeartRhythmUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x341b0` | `0x3407c` | **`-0x134`** |
| `__AUTH_CONST.__objc_const` | `0x6cf8` | `0x6d58` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x4cd0` | `0x4d10` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3b13` | `0x3ae0` | **`-0x33`** |
| `__DATA_CONST.__const` | `0x820` | `0x7f8` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x3008` | `0x3030` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x4dc` | `0x4e4` | **`+0x8`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/PrivateFrameworks/HealthFoundationUI.framework/HealthFoundationUI

-  Functions: 1514
-  Symbols:   2687
-  CStrings:  491
+  Functions: 1522
+  Symbols:   2695
+  CStrings:  490
Symbols:
+ -[HROnboardingElectrocardiogramTakeRecordingViewController initForOnboarding:isRecordingSkippable:shouldObserveForNewRecording:]
+ -[HROnboardingElectrocardiogramTakeRecordingViewController setShouldObserveForNewRecording:]
+ -[HROnboardingElectrocardiogramTakeRecordingViewController shouldObserveForNewRecording]
+ -[HRSpeedBumpViewController _scrollToContentBottom]
+ -[HRSpeedBumpViewController needsScrollToContentBottom]
+ -[HRSpeedBumpViewController setNeedsScrollToContentBottom:]
+ -[HRSpeedBumpViewController viewDidLayoutSubviews]
+ GCC_except_table16
+ _OBJC_CLASS_$_HKRegulatoryDomainManager
+ _OBJC_IVAR_$_HROnboardingElectrocardiogramTakeRecordingViewController._shouldObserveForNewRecording
+ _OBJC_IVAR_$_HRSpeedBumpViewController._needsScrollToContentBottom
+ _OUTLINED_FUNCTION_3
+ _OUTLINED_FUNCTION_4
+ _OUTLINED_FUNCTION_5
- -[HRSpeedBumpViewController _scrollBubbleViewToVisible:]
- -[HRSpeedBumpViewController viewWillAppear:]
- _OBJC_CLASS_$_HKMobileCountryCodeManager
- ___133-[HRElectrocardiogramCurrentLocationOnboardingDeterminer isElectrocardiogramOnboardingAvailableInCurrentLocationForWatch:completion:]_block_invoke
- ___134-[HROnboardingAtrialFibrillationIntroViewController _isAtrialFibrillationDetectionOnboardingAvailableInCurrentLocationForActiveWatch:]_block_invoke
- ___block_descriptor_56_e8_32s40bs_e44_v24?0"<HKCurrentCountryCode>"8"NSError"16ls32l8s40l8
CStrings:
+ "No location determined"
- "Unable to determine location"
- "v24@?0@\"<HKCurrentCountryCode>\"8@\"NSError\"16"
```
