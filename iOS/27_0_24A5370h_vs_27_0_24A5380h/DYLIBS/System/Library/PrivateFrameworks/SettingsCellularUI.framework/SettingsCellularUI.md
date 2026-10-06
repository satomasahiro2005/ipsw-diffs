## SettingsCellularUI

> `/System/Library/PrivateFrameworks/SettingsCellularUI.framework/SettingsCellularUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x1db0` | `0x1718` | **`-0x698`** |
| `__DATA_DIRTY.__objc_data` | `0x1180` | `0x1818` | **`+0x698`** |
| `__DATA_DIRTY.__data` | `—` | `0x270` | **`+0x270`** |
| `__AUTH.__data` | `0x270` | `0x98` | **`-0x1d8`** |
| `__DATA_DIRTY.__bss` | `0x240` | `0x370` | **`+0x130`** |
| `__DATA.__bss` | `0x1f8` | `0xe8` | **`-0x110`** |
| `__DATA_CONST.__got` | `0xa00` | `0xac0` | **`+0xc0`** |
| `__TEXT.__text` | `0x933c8` | `0x93324` | **`-0xa4`** |
| `__DATA.__data` | `0xbe8` | `0xb50` | **`-0x98`** |
| `__AUTH_CONST.__cfstring` | `0x8780` | `0x8720` | **`-0x60`** |
| `__AUTH_CONST.__objc_const` | `0x10290` | `0x102c8` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x1370` | `0x1398` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x9c04` | `0x9c2c` | **`+0x28`** |
| `__TEXT.__cstring` | `0x910b` | `0x912e` | **`+0x23`** |
| `__DATA_CONST.__objc_selrefs` | `0x5628` | `0x5648` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x360` | `0x378` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2358` | `0x2370` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x6c56` | `0x6c4b` | **`-0xb`** |
| `__DATA_DIRTY.__objc_ivar` | `0x5ec` | `0x5f0` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0x1868` | `0x1864` | **`-0x4`** |

### Other Changes

```diff

-744.0.0.0.0
+746.0.0.0.0

-  Functions: 3341
-  Symbols:   5598
-  CStrings:  2066
+  Functions: 3349
+  Symbols:   5605
+  CStrings:  2064
Symbols:
+ -[PSUIAddCellularPlanSpecifier pendingSimSetupOptions]
+ -[PSUIAddCellularPlanSpecifier setPendingSimSetupOptions:]
+ -[PSUICoreTelephonyRadioCache checkTARandomizationSupport:]
+ -[PSUICoreTelephonyRadioCache isTARandomizationRegulatoryDisabled:]
+ -[PSUICoreTelephonyRadioCache taRandomizationSupportChanged:support:]
+ _TSUserInfoIntermediateDefaultsToQuickSwitchKey
+ ___52-[EdgeSettingsController resetAllConfiguredSettings]_block_invoke_2
+ ___56-[EdgeSettingsController showCarrierSettingsEraseAlert:]_block_invoke_2
+ ___56-[EdgeSettingsController showCarrierSettingsEraseAlert:]_block_invoke_3
+ ___60-[EdgeSettingsController didChangeDeviceManagementSettings:]_block_invoke
+ ___block_descriptor_40_e8_32o_e5_v8?0ls32l8
- -[PSUICoreTelephonyRadioCache checkTARandomizationSupported:]
- -[PSUICoreTelephonyRadioCache taRandomizationSupportChanged:supported:]
- _TSUserInfoIsSecondaryKey
- _TSUserInfoQuickSwitchFollowUpPhoneNumberKey
CStrings:
+ "Skip query and return TA Randomization support %ld"
+ "TA Randomization support changed for descriptor: %@ to: %ld"
+ "TA_RANDOMIZATION_REGULATORY_DISABLED_FOOTER_PREFIX"
+ "addCellularPlan"
+ "default"
+ "qs"
+ "qsflow"
+ "stashing Add Cellular Plan presets for cellHighlighter-driven launch"
- "Edge"
- "Skip query and return TA Randomization support %d"
- "TA Randomization support changed for descriptor: %@ to: %d"
- "flow"
- "followUp"
- "launching Quick Switch enrollment flow"
- "launching Quick Switch follow-up info flow"
- "phoneNumber"
- "quickSwitch"
- "sliding"
```
