## SystemStatusUI

> `/System/Library/PrivateFrameworks/SystemStatusUI.framework/SystemStatusUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa05f0` | `0xa0bc0` | **`+0x5d0`** |
| `__TEXT.__objc_methlist` | `0xae64` | `0xaed4` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x2558` | `0x25a8` | **`+0x50`** |
| `__TEXT.__cstring` | `0x2a9f` | `0x2ae4` | **`+0x45`** |
| `__AUTH_CONST.__cfstring` | `0x3b00` | `0x3b40` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x13af0` | `0x13b28` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x52b0` | `0x52d8` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x1ad8` | `0x1ae8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1088` | `0x1090` | **`+0x8`** |
| `__DATA_DIRTY.__objc_ivar` | `0x52c` | `0x530` | **`+0x4`** |

### Other Changes

```diff

-274.0.0.0.0
+279.100.0.0.0

-  Functions: 4154
-  Symbols:   6879
-  CStrings:  611
+  Functions: 4166
+  Symbols:   6894
+  CStrings:  614
Symbols:
+ -[STUIStatusBar _applyAlpha:forPartWithIdentifier:]
+ -[STUIStatusBar _reapplyPartAlphas]
+ -[STUIStatusBar partAlphas]
+ -[STUIStatusBar setPartAlphas:]
+ -[STUIStatusBarMenuBarItem dependentEntryKeys]
+ -[STUIStatusBarMenuBarItem removalAnimationForDisplayItemWithIdentifier:]
+ -[STUIStatusBarVisualProvider_CarPlay displayItemIdentifiersExemptFromAlphaForPartWithIdentifier:]
+ -[STUIStatusBarVisualProvider_CarPlay regionIdentifiersForPartWithIdentifier:]
+ -[STUIStatusBarVisualProvider_Pad _updateCenterRegionForMenuBarShowing:]
+ -[STUIStatusBarVisualProvider_Pad _updateConstraintsForMenuBarShowing:updateStatusBar:]
+ -[STUIStatusBarVisualProvider_Pad removalAnimationForDisplayItemWithIdentifier:itemAnimation:]
+ -[STUIStatusBarVisualProvider_Pad willUpdateWithData:]
+ GCC_except_table130
+ _STStatusBarDataEntryMenuBarKey
+ _STUIStatusBarPartIdentifierCarPlayExternalPrivacy
+ _STUIStatusBarPartIdentifierCarPlayNonPrivacy
+ ___35-[STUIStatusBar _reapplyPartAlphas]_block_invoke
+ ___73-[STUIStatusBarMenuBarItem removalAnimationForDisplayItemWithIdentifier:]_block_invoke
+ ___87-[STUIStatusBarVisualProvider_Pad _updateConstraintsForMenuBarShowing:updateStatusBar:]_block_invoke
+ ___94-[STUIStatusBarVisualProvider_Pad removalAnimationForDisplayItemWithIdentifier:itemAnimation:]_block_invoke
- -[STUIStatusBarVisualProvider_CarPlayDualDriver createSensorRegion]
- -[STUIStatusBarVisualProvider_CarPlayDualPassenger createExternalPrivacyItemsRegion]
- -[STUIStatusBarVisualProvider_Pad _updateConstraintsForMenuBarShowing:]
- GCC_except_table127
- ___71-[STUIStatusBarVisualProvider_Pad _updateConstraintsForMenuBarShowing:]_block_invoke
CStrings:
+ "carPlayExternalPrivacyPartIdentifier"
+ "carPlayNonPrivacyPartIdentifier"
+ "\xe2a!"
```
