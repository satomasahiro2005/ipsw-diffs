## GenerativePartnerServiceUI

> `/System/Library/PrivateFrameworks/GenerativePartnerServiceUI.framework/GenerativePartnerServiceUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcbc44` | `0xc6df8` | **`-0x4e4c`** |
| `__TEXT.__swift5_typeref` | `0x11383` | `0x10da1` | **`-0x5e2`** |
| `__TEXT.__const` | `0x6d2c` | `0x693c` | **`-0x3f0`** |
| `__AUTH_CONST.__const` | `0x5400` | `0x50a8` | **`-0x358`** |
| `__DATA.__data` | `0x28dc` | `0x26b4` | **`-0x228`** |
| `__TEXT.__constg_swiftt` | `0x2144` | `0x1fd8` | **`-0x16c`** |
| `__TEXT.__unwind_info` | `0x3218` | `0x30f8` | **`-0x120`** |
| `__DATA.__bss` | `0x43a8` | `0x4298` | **`-0x110`** |
| `__TEXT.__swift5_fieldmd` | `0x17e4` | `0x16f0` | **`-0xf4`** |
| `__DATA_CONST.__objc_selrefs` | `0x6c0` | `0x5e0` | **`-0xe0`** |
| `__DATA_DIRTY.__objc_data` | `0x848` | `0x768` | **`-0xe0`** |
| `__AUTH_CONST.__objc_const` | `0x1448` | `0x1398` | **`-0xb0`** |
| `__TEXT.__eh_frame` | `0x4910` | `0x4860` | **`-0xb0`** |
| `__AUTH.__objc_data` | `0x1f8` | `0x168` | **`-0x90`** |
| `__AUTH.__data` | `0xaf8` | `0xa78` | **`-0x80`** |
| `__DATA_CONST.__got` | `0xd20` | `0xca8` | **`-0x78`** |
| `__TEXT.__objc_methlist` | `0x3d4` | `0x364` | **`-0x70`** |
| `__TEXT.__swift5_reflstr` | `0x1994` | `0x1924` | **`-0x70`** |
| `__AUTH_CONST.__auth_got` | `0x1bf0` | `0x1b88` | **`-0x68`** |
| `__TEXT.__oslogstring` | `0x1e7d` | `0x1ed6` | **`+0x59`** |
| `__DATA_DIRTY.__data` | `0x1e20` | `0x1de0` | **`-0x40`** |
| `__TEXT.__swift5_builtin` | `0x8c` | `0x50` | **`-0x3c`** |
| `__TEXT.__swift5_assocty` | `0x448` | `0x418` | **`-0x30`** |
| `__TEXT.__swift5_types` | `0x1d8` | `0x1b4` | **`-0x24`** |
| `__TEXT.__cstring` | `0x3673` | `0x3693` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0xb8` | `0xa8` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x14a4` | `0x14b0` | **`+0xc`** |
| `__DATA.__common` | `0x150` | `0x148` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x27c` | `0x274` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x2a4` | `0x2a0` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x154` | `0x150` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x13c` | `0x138` | **`-0x4`** |

### Other Changes

```diff

-287.0.6.0.0
+291.1.0.5.0

-  - /System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices

-  Functions: 5106
-  Symbols:   323
-  CStrings:  403
+  Functions: 4991
+  Symbols:   312
+  CStrings:  399
Symbols:
+ _swift_task_getMainExecutor
+ _swift_task_isCurrentExecutor
- _OBJC_CLASS_$_IFColor
- _OBJC_CLASS_$_NSMutableArray
- _OBJC_CLASS_$_NSNumber
- _OBJC_CLASS_$_PSSpecifier
- _OBJC_CLASS_$_PSTableCell
- _OBJC_CLASS_$_SBSHomeScreenService
- _OBJC_CLASS_$_UITraitCollection
- _OBJC_METACLASS_$_PSTableCell
- _PSFooterTextGroupKey
- _PSIDKey
- _objc_retain_x9
- _swift_cvw_instantiateLayoutString
- _swift_retain_x10
CStrings:
+ "GenerativePartnerServiceUI/OBKSheetsManager.swift"
+ "Incorrect actor executor assumption; Expected same executor as "
+ "Settings Voice Selection"
+ "Siri Cached Voice"
+ "Siri Cached Voice Display Name"
+ "Voice Settings Underlying Values"
+ "When settingsVoiceSelection is empty, Siri will selected an appropriate \"opposite\" voice and write to the cache. When settingsVoiceSelection gets cleared (user chooses \"Default\" voice), we clear the Siri cache."
+ "[DEPRECATED] GPSUI.ProviderDeclarations: Loaded %{public}ld providers"
+ "[DEPRECATED] GPSUI.ProviderDeclarations: Returning available providers filtered by .isChina=%{bool,public}d: %{public}s"
- " to extend Apple Intelligence."
- "BackgroundProminence"
- "Extensions to Apple Intelligence are currently unavailable."
- "GenerativePartnerServiceUI.GPSAppRoomManager"
- "Loaded %{public}ld providers"
- "Returning available providers filtered by .isChina=%{bool,public}d: %{public}s"
- "com.apple.siri.generativeassistantsettings"
- "com.apple.springboard.homeScreenIconStyle"
- "com.appleinternal.Pacifica"
- "forcedRateLimitState"
- "shouldResetConsecutiveLLMConfirmationDates"
- "shouldResetDeclineCounts"
- "useConfirmationPrompts"
```
