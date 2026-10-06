## ThreatNotificationUI

> `/System/Library/PrivateFrameworks/ThreatNotificationUI.framework/ThreatNotificationUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29bd4` | `0x2b394` | **`+0x17c0`** |
| `__TEXT.__eh_frame` | `0xcf8` | `0xd98` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x4ee` | `0x55e` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0xd08` | `0xd50` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0xb70` | `0xb88` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x3e8` | `0x3f8` | **`+0x10`** |
| `__TEXT.__const` | `0x1e46` | `0x1e56` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x13fc` | `0x140c` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x270` | `0x268` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x90` | `0x98` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x40` | `0x44` | **`+0x4`** |

### Other Changes

```diff

-46.0.0.0.0
+46.0.1.0.0

-  Functions: 1064
-  Symbols:   3155
-  CStrings:  101
+  Functions: 1069
+  Symbols:   3174
+  CStrings:  103
Symbols:
+ _$s10Foundation4DateV11FormatStyleV6SymbolV7WeekdayV4wideAIvgZ
+ _$s10Foundation4DateV11FormatStyleV6SymbolV7WeekdayVMa
+ _$s10Foundation4DateV11FormatStyleV7weekdayyA2E6SymbolV7WeekdayVF
+ _$s10Foundation4DateV21timeIntervalSince1970ACSd_tcfC
+ _$s20ThreatNotificationUI15TNUICoordinatorC11synchronize4withySDys11AnyHashableVypGSg_tYaKFZTQ3_
+ _$s20ThreatNotificationUI15TNUICoordinatorC11synchronize4withySDys11AnyHashableVypGSg_tYaKFZTY4_
+ _$s20ThreatNotificationUI15TNUICoordinatorC11synchronize4withySDys11AnyHashableVypGSg_tYaKFZTY5_
+ _$s20ThreatNotificationUI15TNUICoordinatorC16notificationDate4from10Foundation0F0VSgSDys11AnyHashableVypGSg_tFZ
+ _$s22ThreatNotificationCore14TNCLDMManagingP03setaB4Dateyy10Foundation0F0VSgYaKFTj
+ _$s22ThreatNotificationCore14TNCLDMManagingP03setaB4Dateyy10Foundation0F0VSgYaKFTjTu
+ _$s22ThreatNotificationCore15TNCFollowUpItemV11UserInfoKeyO10clientDataSSvgZ
+ _$s22ThreatNotificationCore15TNCFollowUpItemV11UserInfoKeyO12cfuTimestampSSvgZ
+ _$sSD11descriptionSSvg
+ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCs11AnyHashableV_ypTt0g5Tf4g_n
+ _$sSo13os_log_type_ta0A0E4infoABvgZ
+ _$ss11AnyHashableVSHsWP
+ _$ss18_DictionaryStorageCys11AnyHashableVypGMR
+ _$ss18_DictionaryStorageCys11AnyHashableVypGMd
+ _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.31TQ0_
+ _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.31Tu
+ _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.44TQ0_
+ _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.44Tu
+ _symbolic _____y_____ypG s18_DictionaryStorageC s11AnyHashableV
- _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.30TQ0_
- _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.30Tu
- _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.43TQ0_
- _$sxIeAgHr_xs5Error_pIegHrzo_s8SendableRzs5NeverORs_r0_lTRyt_Tg5TA.43Tu
CStrings:
+ "Failed to forward threat notification date to LockdownMode: %@"
+ "Will synchronize CFU with userInfo: %s"
```
