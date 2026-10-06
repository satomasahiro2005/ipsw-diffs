## BiometricKitUI

> `/System/Library/PrivateFrameworks/BiometricKitUI.framework/BiometricKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x70b1c` | `0x70e88` | **`+0x36c`** |
| `__TEXT.__oslogstring` | `0x6963` | `0x6a83` | **`+0x120`** |
| `__AUTH_CONST.__cfstring` | `0x3400` | `0x3440` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x72e0` | `0x7300` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x4918` | `0x4928` | **`+0x10`** |
| `__TEXT.__cstring` | `0x3026` | `0x3036` | **`+0x10`** |

### Other Changes

```diff

-684.100.0.0.0
+685.1.2.0.0

-  Functions: 2875
-  Symbols:   4582
-  CStrings:  1078
+  Functions: 2878
+  Symbols:   4586
+  CStrings:  1083
Symbols:
+ -[BKUIHostedDynamicallySizedJindoPresentable _sweepStalePresentablesFromBannerSource:]
+ -[BKUIPearlEnrollView _resetPreviewLayerBlur]
+ -[BKUIPearlJindoEnrollViewController endEnrollFlowWithError:]
+ GCC_except_table20
+ GCC_except_table34
+ GCC_except_table72
+ GCC_except_table96
- GCC_except_table71
- GCC_except_table95
- ___61-[BKUIPearlJindoEnrollViewController nextStateButtonPressed:]_block_invoke_2
Functions:
+ -[BKUIPearlJindoEnrollViewController endEnrollFlowWithError:]
~ -[BKUIPearlJindoEnrollViewController _postBannerToDestinationWithInitialStateCollapsed:enrollViewStateConfiguration:] : 664 -> 708
~ -[BKUIPearlJindoEnrollViewController nextStateButtonPressed:] : 480 -> 524
~ ___61-[BKUIPearlJindoEnrollViewController nextStateButtonPressed:]_block_invoke : 116 -> 308
~ -[BKUIPearlMovieLoopView selfPortrait] : 284 -> 260
~ -[BKUIPearlEnrollViewController _updateLeftBarButtonItem] : 1072 -> 1120
~ -[BKUIPearlEnrollViewController returnToEnroll] : 76 -> 196
~ -[BKUIPearlEnrollView preEnrollActivate] : 40 -> 92
~ -[BKUIPearlEnrollView _endAndCleanupEnrollSessionIfNeeded] : 148 -> 156
+ -[BKUIPearlEnrollView _resetPreviewLayerBlur]
~ -[BKUIFingerPrintEnrollTutorialViewController _contentViewTopOffset] : 304 -> 64
~ -[BKUIHostedDynamicallySizedJindoPresentable revoke] : 300 -> 336
+ -[BKUIHostedDynamicallySizedJindoPresentable _sweepStalePresentablesFromBannerSource:]
CStrings:
+ "Error revoking presentables %{public}@"
+ "Pearl: skipping Jindo banner post as enrollment is no longer active"
+ "Resetting preview layer blur"
+ "Returning to enroll from partial capture, target state %i"
+ "Revoking current presentable"
+ "Swept %{public}lu orphaned presentable(s) after a stale request identifier"
+ "com.apple.biometrickitui.revoke"
+ "com.apple.biometrickitui.staleIdentifierSweep"
- "-[BKUIPearlMovieLoopView selfPortrait]"
- "BKUIPearlMovieLoopView.m"
- "false"
```
