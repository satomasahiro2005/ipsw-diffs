## ScreenTimeSettingsUI

> `/System/Library/PrivateFrameworks/ScreenTimeSettingsUI.framework/ScreenTimeSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12a4e8` | `0x12b160` | **`+0xc78`** |
| `__AUTH_CONST.__cfstring` | `0xbd40` | `0xbea0` | **`+0x160`** |
| `__TEXT.__cstring` | `0xe475` | `0xe5d5` | **`+0x160`** |
| `__AUTH_CONST.__objc_const` | `0x26128` | `0x26230` | **`+0x108`** |
| `__TEXT.__objc_methlist` | `0xc7e4` | `0xc84c` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x6173` | `0x61d3` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x52c8` | `0x5278` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x27c0` | `0x2808` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x7080` | `0x70c8` | **`+0x48`** |
| `__AUTH_CONST.__objc_intobj` | `0x918` | `0x930` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x3dc8` | `0x3de0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x18e8` | `0x18d8` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x14e0` | `0x14d0` | **`-0x10`** |
| `__TEXT.__const` | `0x3db4` | `0x3da4` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x7b8` | `0x7b0` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x618` | `0x610` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xd18` | `0xd1c` | **`+0x4`** |

### Other Changes

```diff

-655.0.107.0.0
+655.1.6.1.0

-  Functions: 6333
-  Symbols:   8516
-  CStrings:  2240
+  Functions: 6344
+  Symbols:   8522
+  CStrings:  2252
Symbols:
+ -[STContentPrivacyAccessibilityRestrictionsDetailController viewDidAppear:]
+ -[STContentPrivacyListController _labelNameForItem:]
+ -[STContentPrivacyListController showAccessibilityRestrictionsPane]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _accessibilityAskBypassCapabilityForItem:newValue:viewModel:]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _openAccessibilityRestrictions]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _showAccessibilityAskBypassAlertForCapability:]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _showAccessibilityAskBypassAlertIfNeededForCapabilityNumber:]
+ -[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _userStateWarrantsAccessibilityAskBypassAlertForViewModel:]
+ -[STContentPrivacyViewModel setUserIsChildOrTeenInFamily:]
+ -[STContentPrivacyViewModel userIsChildOrTeenInFamily]
+ GCC_except_table123
+ GCC_except_table40
+ GCC_except_table5
+ _OBJC_IVAR_$_STContentPrivacyViewModel._userIsChildOrTeenInFamily
+ ___113-[STContentPrivacySiriAndIntelligenceRestrictionsDetailController _showAccessibilityAskBypassAlertForCapability:]_block_invoke
+ ___block_descriptor_134_e8_32s40s48s56s64s72s80s88s96s104s112bs_e20_v20?0B8"NSError"12ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s112l8
+ ___block_descriptor_147_e8_32s40s48s56s64s72s80s88s96s104s112s120bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s120l8s112l8
+ ___block_descriptor_56_e8_32s40s_e17_v16?0"NSError"8ls32l8s40l8
- -[STDevicePINPane layoutSubviews]
- GCC_except_table121
- GCC_except_table18
- _OBJC_CLASS_$_STDevicePINPane
- _OBJC_METACLASS_$_DevicePINPane
- _OBJC_METACLASS_$_STDevicePINPane
- _PSHeaderDetailTextGroupKey
- __OBJC_$_INSTANCE_METHODS_STDevicePINPane
- __OBJC_CLASS_RO_$_STDevicePINPane
- __OBJC_METACLASS_RO_$_STDevicePINPane
- ___block_descriptor_133_e8_32s40s48s56s64s72s80s88s96s104s112bs_e20_v20?0B8"NSError"12ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s112l8
- ___block_descriptor_146_e8_32s40s48s56s64s72s80s88s96s104s112s120bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s120l8s112l8
CStrings:
+ "-[STContentPrivacyListController showAccessibilityRestrictionsPane]: no Accessibility specifier, ignoring."
+ "AccessibilityAskBypassAlertChangeSettings"
+ "AccessibilityAskBypassAlertMessage_%@%@"
+ "AccessibilityAskBypassAlertOK"
+ "AccessibilityAskBypassAlertTitle_"
+ "ExplicitLanguage"
+ "MathAssistance"
+ "SiriAI"
+ "UserTrackingDataLinkingSpecifierName"
+ "WritingAssistance"
+ "_Named"
+ "settings-navigation://com.apple.Settings.ScreenTime/CONTENT_PRIVACY/ACCESSIBILITY_RESTRICTIONS"
```
