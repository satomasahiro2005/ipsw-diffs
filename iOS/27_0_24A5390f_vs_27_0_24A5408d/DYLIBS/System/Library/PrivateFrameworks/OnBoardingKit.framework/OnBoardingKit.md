## OnBoardingKit

> `/System/Library/PrivateFrameworks/OnBoardingKit.framework/OnBoardingKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x47d30` | `0x48b18` | **`+0xde8`** |
| `__AUTH_CONST.__objc_const` | `0xd9c8` | `0xdb38` | **`+0x170`** |
| `__TEXT.__objc_methlist` | `0x6104` | `0x61d4` | **`+0xd0`** |
| `__DATA_CONST.__objc_selrefs` | `0x3ef8` | `0x3fc0` | **`+0xc8`** |
| `__AUTH_CONST.__cfstring` | `0x20a0` | `0x20e0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xfe0` | `0x1008` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x488` | `0x4a8` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x664` | `0x684` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1949` | `0x1969` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x4e8` | `0x4f8` | **`+0x10`** |

### Other Changes

```diff

-3977.0.19.0.0
+3977.0.22.0.0

-  Functions: 1860
-  Symbols:   3424
-  CStrings:  378
+  Functions: 1876
+  Symbols:   3454
+  CStrings:  380
Symbols:
+ -[OBButtonTray _pocketContentIsButtonsOnly]
+ -[OBHeaderView navigationBarTitle]
+ -[OBPrivacyFlow _bestStringConsideringNetworkForKeyWithPrefix:language:preferredDeviceType:withGenerativeSuffix:countryPolicySuffix:]
+ -[OBPrivacyFlow _stringForKeyWithPrefix:language:preferredDeviceType:withGenerativeSuffix:countryPolicySuffix:withNetworkSuffix:]
+ -[OBPrivacyFlow _stringKeyWithCapabilitiesFromPrefix:withNetwork:withGenerative:countryPolicySuffix:]
+ -[OBPrivacyFlow localizedButtonSecondaryCaptionForLanguage:preferredDeviceType:]
+ -[OBPrivacyLinkButton _captionAttributes]
+ -[OBPrivacyLinkButton _isLaidOutEdgeToEdgeWithSuperview]
+ -[OBPrivacyLinkButton _updateContentGutterIfNeeded]
+ -[OBPrivacyLinkButton initWithCaption:captionAttachmentImage:secondaryCaption:buttonText:symbolName:useLargeIcon:displayLanguage:]
+ -[OBPrivacyLinkButton secondaryCaptionText]
+ -[OBPrivacySplashController setUnifiedAboutButtonCenteredConstraints:]
+ -[OBPrivacySplashController setUnifiedAboutButtonLeadingConstraint:]
+ -[OBPrivacySplashController unifiedAboutButtonCenteredConstraints]
+ -[OBPrivacySplashController unifiedAboutButtonLeadingConstraint]
+ -[OBTableWelcomeController _setAdditionalTopInsetForColumnLayout]
+ -[OBWelcomeController _resolveColumnLayoutForIncomingTransitionIfNeeded]
+ -[OBWelcomeController lastAppliedSafeAreaInsets]
+ -[OBWelcomeController setLastAppliedSafeAreaInsets:]
+ _CGRectGetMaxX
+ _CGRectGetMinX
+ _CGRectGetWidth
+ _OBJC_CLASS_$_UIScrollEdgeEffectStyle
+ _OBJC_IVAR_$_OBPrivacyLinkButton._contentGutterActive
+ _OBJC_IVAR_$_OBPrivacyLinkButton._iconLeadingOverhangConstraint
+ _OBJC_IVAR_$_OBPrivacyLinkButton._secondaryCaptionText
+ _OBJC_IVAR_$_OBPrivacyLinkButton._textLeadingContainerConstraint
+ _OBJC_IVAR_$_OBPrivacyLinkButton._textTrailingContainerConstraint
+ _OBJC_IVAR_$_OBPrivacySplashController._unifiedAboutButtonCenteredConstraints
+ _OBJC_IVAR_$_OBPrivacySplashController._unifiedAboutButtonLeadingConstraint
+ _OBJC_IVAR_$_OBWelcomeController._lastAppliedSafeAreaInsets
+ _UIContentSizeCategoryIsAccessibilityCategory
+ _UITransitionContextToViewKey
- -[OBPrivacyFlow _bestStringConsideringNetworkForKeyWithPrefix:language:preferredDeviceType:withGenerativeSuffix:withGMEChinaSuffix:]
- -[OBPrivacyFlow _stringForKeyWithPrefix:language:preferredDeviceType:withGenerativeSuffix:withGMEChinaSuffix:withNetworkSuffix:]
- -[OBPrivacyFlow _stringKeyWithCapabilitiesFromPrefix:withNetwork:withGenerative:withGMEChinaSuffix:]
CStrings:
+ "BUTTON_CAPTION_SECONDARY"
+ "_NOTGMECHINA"
```
