## OnBoardingKit

> `/System/Library/PrivateFrameworks/OnBoardingKit.framework/OnBoardingKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48830` | `0x48f28` | **`+0x6f8`** |
| `__AUTH_CONST.__objc_const` | `0xdb38` | `0xdcd8` | **`+0x1a0`** |
| `__TEXT.__objc_methlist` | `0x61bc` | `0x62b4` | **`+0xf8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3fb0` | `0x4040` | **`+0x90`** |
| `__TEXT.__cstring` | `0x1939` | `0x19a9` | **`+0x70`** |
| `__AUTH.__objc_data` | `0xfa0` | `0xff0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x708` | `0x758` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x2060` | `0x20a0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1000` | `0x1040` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x136c` | `0x139e` | **`+0x32`** |
| `__AUTH_CONST.__objc_intobj` | `0x1f8` | `0x228` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x684` | `0x69c` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x2d8` | `0x2e0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x290` | `0x298` | **`+0x8`** |

### Other Changes

```diff

-3977.0.23.0.0
+3977.1.3.1.0

-  Functions: 1874
-  Symbols:   3448
-  CStrings:  375
+  Functions: 1896
+  Symbols:   3483
+  CStrings:  380
Symbols:
+ -[OBHeaderBadgeLabel intrinsicContentSize]
+ -[OBPrivacyLinkButton _isLaidOutEdgeToEdgeWithWindow]
+ -[OBPrivacyLinkButton _setSafeAreaAnchoringTrustedForContentGutter:]
+ -[OBPrivacyLinkButton _textLeadingContainerConstraintForTesting]
+ -[OBSetupAssistantSpinnerController _accessibilityLayoutTopOffset]
+ -[OBSetupAssistantSpinnerController _titleTextStyle]
+ -[OBTextAccessoryButton intrinsicContentSize]
+ -[OBTextAccessoryButton lastIntrinsicContentSizeWidth]
+ -[OBTextAccessoryButton layoutSubviews]
+ -[OBTextAccessoryButton setLastIntrinsicContentSizeWidth:]
+ -[OBTextBulletedListItem dotSize]
+ -[OBTrayButton .cxx_destruct]
+ -[OBTrayButton _restoreStashedTitles]
+ -[OBTrayButton _stashTitles]
+ -[OBTrayButton setStashedAttributedTitles:]
+ -[OBTrayButton setStashedTitles:]
+ -[OBTrayButton stashedAttributedTitles]
+ -[OBTrayButton stashedTitles]
+ -[OBWelcomeController forceHeaderInLeadingColumn]
+ -[OBWelcomeController leadingColumnHeaderCenterYConstraint]
+ -[OBWelcomeController setForceHeaderInLeadingColumn:]
+ -[OBWelcomeController setLeadingColumnHeaderCenterYConstraint:]
+ _OBJC_CLASS_$_OBHeaderBadgeLabel
+ _OBJC_IVAR_$_OBPrivacyLinkButton._safeAreaAnchoringTrustedForContentGutter
+ _OBJC_IVAR_$_OBTextAccessoryButton._lastIntrinsicContentSizeWidth
+ _OBJC_IVAR_$_OBTrayButton._stashedAttributedTitles
+ _OBJC_IVAR_$_OBTrayButton._stashedTitles
+ _OBJC_IVAR_$_OBWelcomeController._forceHeaderInLeadingColumn
+ _OBJC_IVAR_$_OBWelcomeController._leadingColumnHeaderCenterYConstraint
+ _OBJC_METACLASS_$_OBHeaderBadgeLabel
+ _OBRectIsFlushHorizontally
+ __OBJC_$_INSTANCE_METHODS_OBHeaderBadgeLabel
+ __OBJC_CLASS_RO_$_OBHeaderBadgeLabel
+ __OBJC_METACLASS_RO_$_OBHeaderBadgeLabel
+ ___37-[OBTrayButton _restoreStashedTitles]_block_invoke
+ ___37-[OBTrayButton _restoreStashedTitles]_block_invoke_2
+ ___block_descriptor_40_e8_32s_e35_v32?0"NSNumber"8"NSString"16^B24ls32l8
+ ___block_descriptor_40_e8_32s_e45_v32?0"NSNumber"8"NSAttributedString"16^B24ls32l8
- -[OBPrivacyLinkButton _isLaidOutEdgeToEdgeWithSuperview]
- -[OBSetupAssistantSpinnerController _updateTextColor]
- -[OBTableWelcomeController _setAdditionalTopInsetForColumnLayout]
CStrings:
+ "-seed"
+ "HideFromCombinedListForGMECHINA"
+ "HideFromCombinedListForGMECHINA must be a boolean"
+ "v32@?0@\"NSNumber\"8@\"NSAttributedString\"16^B24"
+ "v32@?0@\"NSNumber\"8@\"NSString\"16^B24"
```
