## OnBoardingKit

> `/System/Library/PrivateFrameworks/OnBoardingKit.framework/OnBoardingKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x47140` | `0x47a54` | **`+0x914`** |
| `__TEXT.__objc_methlist` | `0x6024` | `0x60ec` | **`+0xc8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3e38` | `0x3ef0` | **`+0xb8`** |
| `__AUTH_CONST.__objc_const` | `0xd940` | `0xd9c8` | **`+0x88`** |
| `__TEXT.__cstring` | `0x18f9` | `0x1949` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0xfb8` | `0xfe0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x2080` | `0x20a0` | **`+0x20`** |
| `__TEXT.__const` | `0x4e4` | `0x4f4` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x658` | `0x664` | **`+0xc`** |
| `__TEXT.__oslogstring` | `0x1360` | `0x1361` | **`+0x1`** |

### Other Changes

```diff

-3977.0.14.0.0
+3977.0.17.0.0

-  Functions: 1843
-  Symbols:   3400
-  CStrings:  377
+  Functions: 1859
+  Symbols:   3422
+  CStrings:  378
Symbols:
+ +[OBWelcomeController isViewSizeEligibleForTwoColumnLayout:safeAreaInsets:traitCollection:]
+ -[OBButtonTray setCaptionAccessibilityIdentifier:]
+ -[OBHeaderView _hasNoVisibleHeaderText]
+ -[OBStableContentSizeScrollView _obkScrollGestureStateChanged:]
+ -[OBStableContentSizeScrollView initWithFrame:]
+ -[OBTableWelcomeController _applyContentInsetAdjustmentBehaviorToTableView]
+ -[OBTableWelcomeController _hasVisibleHostingNavigationBar]
+ -[OBTableWelcomeController _horizontalFooterLayoutMargins]
+ -[OBTableWelcomeController _horizontalLayoutMarginsIncludingSafeArea]
+ -[OBTableWelcomeController _horizontalSafeAreaInsets]
+ -[OBTableWelcomeController adoptedTableViewUsesAutomaticContentInsetAdjustment]
+ -[OBTableWelcomeController cachedHasContentForTwoColumnLayout]
+ -[OBTableWelcomeController setAdoptedTableViewUsesAutomaticContentInsetAdjustment:]
+ -[OBTableWelcomeController setCachedHasContentForTwoColumnLayout:]
+ -[OBWelcomeController _navigationBarHeightIfPresent]
+ -[UIButton(InfoIcon) updateInfoIconForCurrentFont]
+ _OBBaseWelcomeControllerVerticalPadding
+ _OBJC_IVAR_$_OBStableContentSizeScrollView._layoutChangedDuringGesture
+ _OBJC_IVAR_$_OBTableWelcomeController._adoptedTableViewUsesAutomaticContentInsetAdjustment
+ _OBJC_IVAR_$_OBTableWelcomeController._cachedHasContentForTwoColumnLayout
+ __OBJC_$_CLASS_METHODS_OBWelcomeController
+ __OBJC_$_INSTANCE_VARIABLES_OBStableContentSizeScrollView
CStrings:
+ "Two-column layout disabled: invalid view size"
+ "Two-column layout disabled: view too narrow or too tall"
+ "setCaptionAccessibilityIdentifier: must be called after setCaptionText:style:"
- "Not showing landscape layout due to invalid view size"
- "Not showing two column layout due to view size"
```
