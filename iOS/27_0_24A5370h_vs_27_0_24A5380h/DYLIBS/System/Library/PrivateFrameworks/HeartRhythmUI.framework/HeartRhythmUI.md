## HeartRhythmUI

> `/System/Library/PrivateFrameworks/HeartRhythmUI.framework/HeartRhythmUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33fc0` | `0x341b0` | **`+0x1f0`** |
| `__AUTH_CONST.__objc_const` | `0x6c90` | `0x6cf8` | **`+0x68`** |
| `__AUTH.__objc_data` | `0xc30` | `0xbe0` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x4b0` | `0x500` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x4c80` | `0x4cd0` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x2fe8` | `0x3008` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xcb0` | `0xcc0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x4d4` | `0x4dc` | **`+0x8`** |
| `__TEXT.__cstring` | `0x3b16` | `0x3b13` | **`-0x3`** |

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

-  Functions: 1507
-  Symbols:   2678
+  Functions: 1514
+  Symbols:   2687
Symbols:
+ -[HROnboardingECG2PossibleResultsViewController _updateContinueButtonEnabledStateIfNeeded]
+ -[HROnboardingECG2PossibleResultsViewController continueButton]
+ -[HROnboardingECG2PossibleResultsViewController hasReachedScrollBottom]
+ -[HROnboardingECG2PossibleResultsViewController scrollViewDidScroll:]
+ -[HROnboardingECG2PossibleResultsViewController setContinueButton:]
+ -[HROnboardingECG2PossibleResultsViewController setHasReachedScrollBottom:]
+ -[HROnboardingECG2PossibleResultsViewController viewDidLayoutSubviews]
+ _OBJC_IVAR_$_HROnboardingECG2PossibleResultsViewController._continueButton
+ _OBJC_IVAR_$_HROnboardingECG2PossibleResultsViewController._hasReachedScrollBottom
```
