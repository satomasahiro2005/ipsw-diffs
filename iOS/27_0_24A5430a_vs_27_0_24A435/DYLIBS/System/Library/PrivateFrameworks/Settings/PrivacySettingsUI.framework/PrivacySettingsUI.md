## PrivacySettingsUI

> `/System/Library/PrivateFrameworks/Settings/PrivacySettingsUI.framework/PrivacySettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x677dc` | `0x67720` | **`-0xbc`** |
| `__AUTH_CONST.__cfstring` | `0x6fc0` | `0x6f80` | **`-0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x3368` | `0x3380` | **`+0x18`** |
| `__DATA.__bss` | `0x5f0` | `0x600` | **`+0x10`** |
| `__TEXT.__cstring` | `0x8344` | `0x8334` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1828` | `0x1838` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x12a8` | `0x12b0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x4284` | `0x428c` | **`+0x8`** |

### Other Changes

```diff

-2027.0.6.103.0
+2027.0.6.104.0

-  Functions: 2127
-  Symbols:   3698
-  CStrings:  1409
+  Functions: 2131
+  Symbols:   3702
+  CStrings:  1408
Symbols:
+ -[PUIProblemReportingController _isSiriAIDataSharing]
+ GCC_except_table115
+ GCC_except_table122
+ GCC_except_table125
+ GCC_except_table127
+ GCC_except_table131
+ GCC_except_table139
+ GCC_except_table143
+ GCC_except_table145
+ GCC_except_table149
+ GCC_except_table164
+ GCC_except_table98
+ _AssistantServicesLibrary
+ ___getAFPreferencesClass_block_invoke
+ _getAFPreferencesClass.softClass
- GCC_except_table107
- GCC_except_table114
- GCC_except_table121
- GCC_except_table124
- GCC_except_table126
- GCC_except_table130
- GCC_except_table137
- GCC_except_table141
- GCC_except_table144
- GCC_except_table148
- GCC_except_table161
CStrings:
+ "ABOUT_IMPROVE_SIRI_AI"
+ "AFPreferences"
+ "IMPROVE_SIRI_AI"
+ "IMPROVE_SIRI_AI_EXPLANATION"
+ "com.apple.onboarding.improveintelligence"
- "AUTOMATED_FEEDBACK"
- "AUTOMATED_FEEDBACK_FOOTER"
- "AUTOMATED_FEEDBACK_GROUP"
- "AUTOMATED_FEEDBACK_LINK"
- "automatedFeedbackLinkTapped"
- "telephony"
```
