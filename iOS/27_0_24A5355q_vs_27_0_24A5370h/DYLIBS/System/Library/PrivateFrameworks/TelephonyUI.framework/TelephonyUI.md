## TelephonyUI

> `/System/Library/PrivateFrameworks/TelephonyUI.framework/TelephonyUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x659f4` | `0x66620` | **`+0xc2c`** |
| `__AUTH_CONST.__cfstring` | `0x2500` | `0x28a0` | **`+0x3a0`** |
| `__TEXT.__cstring` | `0x2a91` | `0x2d01` | **`+0x270`** |
| `__TEXT.__gcc_except_tab` | `0x214` | `0x370` | **`+0x15c`** |
| `__DATA_CONST.__const` | `0xbe0` | `0xca0` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x1db8` | `0x1d78` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x1ba0` | `0x1bd0` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x1190` | `0x11a8` | **`+0x18`** |
| `__DATA.__bss` | `0x2800` | `0x2810` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3120` | `0x3130` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x3c5c` | `0x3c64` | **`+0x8`** |

### Other Changes

```diff

-139.100.27.2.9
+143.100.11.2.1

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 3009
-  Symbols:   3172
-  CStrings:  498
+  Functions: 3014
+  Symbols:   3187
+  CStrings:  528
Symbols:
+ +[UIAlertController(TelephonyUI) _addActionWithType:alertID:toAlertController:]
+ GCC_except_table0
+ GCC_except_table14
+ GCC_except_table7
+ _AnalyticsSendEventLazy
+ __TPRegisterActionName
+ __TPSendWirelessAlertAnalytics
+ ___79+[UIAlertController(TelephonyUI) _addActionWithType:alertID:toAlertController:]_block_invoke
+ ____TPSendWirelessAlertAnalytics_block_invoke
+ ___block_descriptor_48_e8_32s40w_e23_v16?0"UIAlertAction"8lw40l8s32l8
+ ___block_descriptor_56_e8_32s40bs48w_e23_v16?0"UIAlertAction"8lw48l8s32l8s40l8
+ ___block_descriptor_56_e8_32s40s48s_e19_"NSDictionary"8?0ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48bs56w_e23_v16?0"UIAlertAction"8lw56l8s32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48bs56w_e23_v16?0"UIAlertAction"8lw56l8s32l8s48l8s40l8
+ _kTPAlertActionNamesKey
+ _objc_getAssociatedObject
+ _objc_setAssociatedObject
- ___block_descriptor_40_e8_32bs_e23_v16?0"UIAlertAction"8ls32l8
- ___block_descriptor_48_e8_32s40bs_e23_v16?0"UIAlertAction"8ls40l8s32l8
CStrings:
+ "@\"NSDictionary\"8@?0"
+ "alert_action"
+ "alert_available_actions"
+ "alert_id"
+ "alert_id_domain"
+ "bundle"
+ "call"
+ "call_end_stewie"
+ "cancel"
+ "carrier_details"
+ "com.apple.wireless.alertsAndActions"
+ "confirmed_carrier_outage_wifi_enabled"
+ "confirmed_carrier_outage_wifi_not_enabled"
+ "dial"
+ "enable_wifi_calling"
+ "network_unavailable"
+ "ok"
+ "phonefacetime.telephonyui"
+ "potential_service_interruption_wifi_enabled"
+ "potential_service_interruption_wifi_not_enabled"
+ "select_identity"
+ "settings_airplane_mode"
+ "settings_allow_wifi"
+ "settings_carrier_outage_learn_more"
+ "settings_cellular"
+ "settings_wifi"
+ "settings_wifi_calling"
+ "settings_wifi_calling_v2"
+ "telephony_account_unavailable"
+ "unknown"
```
