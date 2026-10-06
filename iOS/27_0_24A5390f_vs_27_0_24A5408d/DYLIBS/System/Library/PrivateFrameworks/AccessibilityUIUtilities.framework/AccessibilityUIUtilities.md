## AccessibilityUIUtilities

> `/System/Library/PrivateFrameworks/AccessibilityUIUtilities.framework/AccessibilityUIUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x62084` | `0x61ce4` | **`-0x3a0`** |
| `__TEXT.__oslogstring` | `0xe34` | `0x1155` | **`+0x321`** |
| `__AUTH_CONST.__objc_const` | `0xa1e0` | `0xa370` | **`+0x190`** |
| `__TEXT.__objc_methlist` | `0x6444` | `0x6534` | **`+0xf0`** |
| `__DATA_CONST.__objc_selrefs` | `0x50d8` | `0x51b0` | **`+0xd8`** |
| `__TEXT.__constg_swiftt` | `0x8fc` | `0x848` | **`-0xb4`** |
| `__AUTH.__data` | `0x5b0` | `0x508` | **`-0xa8`** |
| `__AUTH_CONST.__const` | `0xae0` | `0xa38` | **`-0xa8`** |
| `__AUTH.__objc_data` | `0x2260` | `0x2300` | **`+0xa0`** |
| `__TEXT.__const` | `0xda0` | `0xd38` | **`-0x68`** |
| `__TEXT.__swift5_typeref` | `0xb07` | `0xabb` | **`-0x4c`** |
| `__TEXT.__swift5_fieldmd` | `0x29c` | `0x258` | **`-0x44`** |
| `__TEXT.__cstring` | `0x5c86` | `0x5caf` | **`+0x29`** |
| `__AUTH_CONST.__cfstring` | `0x69e0` | `0x6a00` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1208` | `0x11f0` | **`-0x18`** |
| `__DATA.__data` | `0x1340` | `0x1328` | **`-0x18`** |
| `__TEXT.__swift5_capture` | `0x174` | `0x15c` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0x584` | `0x594` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x268` | `0x278` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x26c` | `0x25c` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x1190` | `0x1198` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x398` | `0x3a0` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x808` | `0x810` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x50` | `0x48` | **`-0x8`** |

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

-  Functions: 2412
-  Symbols:   4633
-  CStrings:  1066
+  Functions: 2409
+  Symbols:   4662
+  CStrings:  1072
Symbols:
+ +[AXAssistiveTouchLargeContentHUDView defaultActivationDelay]
+ +[AXAssistiveTouchLargeContentHUDView shouldShowLargeContentViewer]
+ -[AXAlertBannerContent prefersCompactActionLayout]
+ -[AXAlertBannerContent setPrefersCompactActionLayout:]
+ -[AXAlertBannerSystemApertureTrailingButtonView .cxx_destruct]
+ -[AXAlertBannerSystemApertureTrailingButtonView button]
+ -[AXAlertBannerSystemApertureTrailingButtonView initWithButton:]
+ -[AXAlertBannerSystemApertureTrailingButtonView setButton:]
+ -[AXAlertBannerSystemApertureTrailingButtonView sizeThatFits:forLayoutMode:]
+ -[AXAlertBannerSystemApertureViewController _setupCompactTrailingView]
+ -[AXAlertBannerSystemApertureViewController compactTrailingView]
+ -[AXAlertBannerSystemApertureViewController setCompactTrailingView:]
+ -[AXAssistiveTouchLargeContentHUDView .cxx_destruct]
+ -[AXAssistiveTouchLargeContentHUDView _layoutHUDView]
+ -[AXAssistiveTouchLargeContentHUDView dismissHUD]
+ -[AXAssistiveTouchLargeContentHUDView layoutSubviews]
+ -[AXAssistiveTouchLargeContentHUDView presentHUDWithTitle:image:]
+ -[AXUISettingsSpeechRateSliderCell _playSpeechRateBounceEffectIfNeeded]
+ GCC_except_table1147
+ GCC_except_table1189
+ GCC_except_table1245
+ GCC_except_table1403
+ GCC_except_table1517
+ GCC_except_table1628
+ GCC_except_table1833
+ GCC_except_table1834
+ GCC_except_table1835
+ GCC_except_table1858
+ GCC_except_table1866
+ GCC_except_table1879
+ GCC_except_table1882
+ GCC_except_table1889
+ GCC_except_table1914
+ GCC_except_table661
+ GCC_except_table666
+ GCC_except_table677
+ GCC_except_table699
+ GCC_except_table741
+ GCC_except_table751
+ GCC_except_table771
+ GCC_except_table773
+ GCC_except_table778
+ GCC_except_table964
+ _AXAIWhiteGloveLoggingEnabled
+ _CGAffineTransformMakeScale
+ _OBJC_CLASS_$_AXAlertBannerSystemApertureTrailingButtonView
+ _OBJC_CLASS_$_AXAssistiveTouchLargeContentHUDView
+ _OBJC_CLASS_$_UIAccessibilityHUDItem
+ _OBJC_CLASS_$_UIAccessibilityHUDView
+ _OBJC_CLASS_$_UILargeContentViewerInteraction
+ _OBJC_IVAR_$_AXAlertBannerContent._prefersCompactActionLayout
+ _OBJC_IVAR_$_AXAlertBannerSystemApertureTrailingButtonView._button
+ _OBJC_IVAR_$_AXAlertBannerSystemApertureViewController._compactTrailingView
+ _OBJC_IVAR_$_AXAssistiveTouchLargeContentHUDView._hudView
+ _OBJC_METACLASS_$_AXAlertBannerSystemApertureTrailingButtonView
+ _OBJC_METACLASS_$_AXAssistiveTouchLargeContentHUDView
+ __OBJC_$_CLASS_METHODS_AXAssistiveTouchLargeContentHUDView
+ __OBJC_$_CLASS_PROP_LIST_AXAssistiveTouchLargeContentHUDView
+ __OBJC_$_INSTANCE_METHODS_AXAlertBannerSystemApertureTrailingButtonView
+ __OBJC_$_INSTANCE_METHODS_AXAssistiveTouchLargeContentHUDView
+ __OBJC_$_INSTANCE_VARIABLES_AXAlertBannerSystemApertureTrailingButtonView
+ __OBJC_$_INSTANCE_VARIABLES_AXAssistiveTouchLargeContentHUDView
+ __OBJC_$_PROP_LIST_AXAlertBannerSystemApertureTrailingButtonView
+ __OBJC_CLASS_PROTOCOLS_$_AXAlertBannerSystemApertureTrailingButtonView
+ __OBJC_CLASS_RO_$_AXAlertBannerSystemApertureTrailingButtonView
+ __OBJC_CLASS_RO_$_AXAssistiveTouchLargeContentHUDView
+ __OBJC_METACLASS_RO_$_AXAlertBannerSystemApertureTrailingButtonView
+ __OBJC_METACLASS_RO_$_AXAssistiveTouchLargeContentHUDView
+ ___49-[AXAssistiveTouchLargeContentHUDView dismissHUD]_block_invoke
- GCC_except_table1144
- GCC_except_table1188
- GCC_except_table1242
- GCC_except_table1392
- GCC_except_table1506
- GCC_except_table1617
- GCC_except_table1814
- GCC_except_table1815
- GCC_except_table1816
- GCC_except_table1839
- GCC_except_table1847
- GCC_except_table1860
- GCC_except_table1863
- GCC_except_table1870
- GCC_except_table1895
- GCC_except_table660
- GCC_except_table665
- GCC_except_table676
- GCC_except_table698
- GCC_except_table737
- GCC_except_table750
- GCC_except_table770
- GCC_except_table772
- GCC_except_table777
- GCC_except_table963
- _OBJC_CLASS_$_NSLock
- _PSDetailControllerClassKey
- __DATA__TtC24AccessibilityUIUtilitiesP33_C2DA6A1A939BCBAD338EA5ABE47A0CE024AXSwiftUIModifierStorage
- __IVARS__TtC24AccessibilityUIUtilitiesP33_C2DA6A1A939BCBAD338EA5ABE47A0CE024AXSwiftUIModifierStorage
- __METACLASS_DATA__TtC24AccessibilityUIUtilitiesP33_C2DA6A1A939BCBAD338EA5ABE47A0CE024AXSwiftUIModifierStorage
- ___80-[AXUISettingsInstructionsView textView:primaryActionForTextItem:defaultAction:]_block_invoke_6
- _get_witness_table 7SwiftUI4ViewRzlAA03AnyC0VAaBHPyHC
- _symbolic SDySS_____G 24AccessibilityUIUtilities20AXStoredViewModifierV
- _symbolic So6NSLockC
- _symbolic _____ 24AccessibilityUIUtilities20AXStoredViewModifierV
- _symbolic _____ 24AccessibilityUIUtilities24AXSwiftUIModifierStorage33_C2DA6A1A939BCBAD338EA5ABE47A0CE0LLC
- _symbolic _____ 7SwiftUI7AnyViewV
- _symbolic _____AAc 7SwiftUI7AnyViewV
- _symbolic _____ySS_____G s18_DictionaryStorageC 24AccessibilityUIUtilities20AXStoredViewModifierV
- _type_layout_string 24AccessibilityUIUtilities20AXStoredViewModifierV
CStrings:
+ "!H"
+ "SWIPE_GESTURES_MINIMUM_DISTANCE_STANDARD"
+ "rdar://157461047 AXUISettingsInstructionsView closeButtonTapped dismiss-completion moreInfoControllerNilBeforeClear=%d"
+ "rdar://157461047 AXUISettingsInstructionsView closeButtonTapped enter senderClass=%{public}@ moreInfoControllerNil=%d controllerClass=%{public}@ isBeingDismissed=%d presentingVC=%{public}@"
+ "rdar://157461047 AXUISettingsInstructionsView presenting welcome sheet rootVC=%{public}@ existingPresented=%{public}@ isBeingDismissed=%d isBeingPresented=%d"
+ "rdar://157461047 AXUISettingsInstructionsView primaryActionForTextItem prepared moreInfoController titleKey=%{public}@ symbolName=%{public}@ hadPriorController=%d moreContentCount=%lu"
+ "rdar://157461047 AXUISettingsInstructionsView primaryActionForTextItem returning customActionBlock path titleKey=%{public}@ tableIdentifier=%{public}@"
- "!G"
```
