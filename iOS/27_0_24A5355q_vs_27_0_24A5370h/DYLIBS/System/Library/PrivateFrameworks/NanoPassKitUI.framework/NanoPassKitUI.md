## NanoPassKitUI

> `/System/Library/PrivateFrameworks/NanoPassKitUI.framework/NanoPassKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25268` | `0x2621c` | **`+0xfb4`** |
| `__AUTH_CONST.__objc_const` | `0x4508` | `0x4728` | **`+0x220`** |
| `__TEXT.__objc_methlist` | `0x2584` | `0x267c` | **`+0xf8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1e80` | `0x1f38` | **`+0xb8`** |
| `__DATA.__objc_ivar` | `0x2e0` | `0x314` | **`+0x34`** |
| `__TEXT.__unwind_info` | `0x870` | `0x898` | **`+0x28`** |
| `__TEXT.__cstring` | `0x1611` | `0x1621` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0xfa4` | `0xf9a` | **`-0xa`** |
| `__DATA_CONST.__got` | `0x610` | `0x618` | **`+0x8`** |

### Other Changes

```diff

-1329.0.0.0.0
+1334.0.0.0.0

-  Functions: 924
-  Symbols:   1730
+  Functions: 945
+  Symbols:   1765
Symbols:
+ -[NPKCardPassHeaderFieldStackView _configureConstraintsForFieldView:logoImageView:layoutGuide:constraintsToActivate:constraintsToDeactivate:]
+ -[NPKCardPassHeaderFieldStackView _configureConstraintsForFieldViewVerticalAlignment:logoImageView:hasLogoText:constraintsToActivate:constraintsToDeactivate:]
+ -[NPKCardPassHeaderFieldStackView _configureConstraintsForLogoTextLabel:logoImageView:layoutGuide:constraintsToActivate:constraintsToDeactivate:]
+ -[NPKCardPassHeaderFieldStackView _configureLogoTextLabel:withLayoutGuide:]
+ -[NPKCardPassHeaderStackLayoutGuide logoTextHorizontalSpacing]
+ -[NPKCardPassHeaderStackLayoutGuide setLogoTextHorizontalSpacing:]
+ -[NPKCardPassHeaderStackLayoutGuide setShouldTopAlignLogoText:]
+ -[NPKCardPassHeaderStackLayoutGuide shouldTopAlignLogoText]
+ -[NPKCardPassLayoutGuideProvider _createStripImageLayoutGuideWithPrimaryField:]
+ -[NPKCardPassStripImageFieldsStackView _configurePrimaryFieldViewWithLayoutGuide:]
+ -[NPKCardPassStripImageFieldsStackView primaryFieldView]
+ -[NPKCardPassStripImageFieldsStackView setPrimaryFieldView:]
+ -[NPKCardPassStripImageLayoutGuide primaryFieldBottomPadding]
+ -[NPKCardPassStripImageLayoutGuide primaryFieldLabelAttributes]
+ -[NPKCardPassStripImageLayoutGuide primaryFieldTopPadding]
+ -[NPKCardPassStripImageLayoutGuide primaryFieldValueAttributes]
+ -[NPKCardPassStripImageLayoutGuide primaryField]
+ -[NPKCardPassStripImageLayoutGuide setPrimaryField:]
+ -[NPKCardPassStripImageLayoutGuide setPrimaryFieldBottomPadding:]
+ -[NPKCardPassStripImageLayoutGuide setPrimaryFieldLabelAttributes:]
+ -[NPKCardPassStripImageLayoutGuide setPrimaryFieldTopPadding:]
+ -[NPKCardPassStripImageLayoutGuide setPrimaryFieldValueAttributes:]
+ -[NPKDynamicFaceViewAdapter handleSceneForegrounded]
+ -[NPKPaymentPassView _refreshAppleCardOnSceneForeground:]
+ -[NPKPaymentPassView didMoveToWindow]
+ GCC_except_table18
+ _OBJC_IVAR_$_NPKCardPassHeaderFieldStackView._fieldViewCenterYConstraint
+ _OBJC_IVAR_$_NPKCardPassHeaderFieldStackView._fieldViewHorizontalConstraints
+ _OBJC_IVAR_$_NPKCardPassHeaderFieldStackView._fieldViewLeadingConstraint
+ _OBJC_IVAR_$_NPKCardPassHeaderFieldStackView._fieldViewTopConstraint
+ _OBJC_IVAR_$_NPKCardPassHeaderFieldStackView._fieldViewTrailingConstraint
+ _OBJC_IVAR_$_NPKCardPassHeaderFieldStackView._logoTextCenterYConstraint
+ _OBJC_IVAR_$_NPKCardPassHeaderFieldStackView._logoTextHorizontalConstraints
+ _OBJC_IVAR_$_NPKCardPassHeaderFieldStackView._logoTextLabel
+ _OBJC_IVAR_$_NPKCardPassHeaderFieldStackView._logoTextLeadingConstraint
+ _OBJC_IVAR_$_NPKCardPassHeaderFieldStackView._logoTextTopConstraint
+ _OBJC_IVAR_$_NPKCardPassHeaderFieldStackView._logoTextTrailingConstraint
+ _OBJC_IVAR_$_NPKCardPassHeaderStackLayoutGuide._logoTextHorizontalSpacing
+ _OBJC_IVAR_$_NPKCardPassHeaderStackLayoutGuide._shouldTopAlignLogoText
+ _OBJC_IVAR_$_NPKCardPassStripImageFieldsStackView._primaryFieldView
+ _OBJC_IVAR_$_NPKCardPassStripImageLayoutGuide._primaryField
+ _OBJC_IVAR_$_NPKCardPassStripImageLayoutGuide._primaryFieldBottomPadding
+ _OBJC_IVAR_$_NPKCardPassStripImageLayoutGuide._primaryFieldLabelAttributes
+ _OBJC_IVAR_$_NPKCardPassStripImageLayoutGuide._primaryFieldTopPadding
+ _OBJC_IVAR_$_NPKCardPassStripImageLayoutGuide._primaryFieldValueAttributes
+ _UIFontWeightMedium
+ _UISceneWillEnterForegroundNotification
- -[NPKCardPassHeaderFieldStackView _configureConstraintsForFieldView:logoImageView:layoutGuide:isUsingLogoText:constraintsToActivate:constraintsToDeactivate:]
- -[NPKCardPassLayoutGuideProvider _createStripImageLayoutGuide]
- -[NPKDynamicFaceViewAdapter handleAppForegrounded]
- -[NPKPaymentPassView _refreshAppleCardOnAppForeground:]
- GCC_except_table17
- _OBJC_IVAR_$_NPKCardPassHeaderFieldStackView._constraintsIsNotUsingLogoText
- _OBJC_IVAR_$_NPKCardPassHeaderFieldStackView._constraintsIsUsingLogoText
- _OBJC_IVAR_$_NPKCardPassHeaderFieldStackView._fieldViewLeftAlignLeadingConstraint
- _OBJC_IVAR_$_NPKCardPassHeaderFieldStackView._fieldViewLeftAlignTrailingConstraint
- _OBJC_IVAR_$_NPKCardPassHeaderFieldStackView._fieldViewRightAlignLeadingConstraint
- _OBJC_IVAR_$_NPKCardPassHeaderFieldStackView._fieldViewRightAlignTrailingConstraint
- _UIApplicationWillEnterForegroundNotification
CStrings:
+ "Notice: [DynamicCardArt: %p] refreshing on scene foreground"
+ "Notice: [DynamicPassView] registering for UISceneWillEnterForegroundNotification %p"
+ "Notice: [DynamicPassView] unregistering for UISceneWillEnterForegroundNotification %p"
- "Notice: [DynamicCardArt: %p] refreshing on app foreground"
- "Notice: [DynamicPassView] registering for UIApplicationWillEnterForegroundNotification %p"
- "Notice: [DynamicPassView] unregistering for UIApplicationWillEnterForegroundNotification %p"
```
