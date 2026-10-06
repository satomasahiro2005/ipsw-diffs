## CommunicationsSetupUI

> `/System/Library/PrivateFrameworks/CommunicationsSetupUI.framework/CommunicationsSetupUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8f218` | `0x904f0` | **`+0x12d8`** |
| `__TEXT.__oslogstring` | `0x63f7` | `0x6665` | **`+0x26e`** |
| `__TEXT.__gcc_except_tab` | `0x42f0` | `0x444c` | **`+0x15c`** |
| `__TEXT.__cstring` | `0xc547` | `0xc667` | **`+0x120`** |
| `__AUTH_CONST.__cfstring` | `0xb9e0` | `0xbae0` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x89c4` | `0x8a7c` | **`+0xb8`** |
| `__DATA_CONST.__objc_selrefs` | `0x5b08` | `0x5bb0` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0x2980` | `0x29b0` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0xd880` | `0xd8a0` | **`+0x20`** |
| `__TEXT.__const` | `0x704` | `0x714` | **`+0x10`** |

### Other Changes

```diff

-1563.100.1.0.0
+1565.100.1.0.0

-  Functions: 3050
-  Symbols:   5180
-  CStrings:  1779
+  Functions: 3063
+  Symbols:   5192
+  CStrings:  1797
Symbols:
+ -[CKLazuliEnablementManager _canSetRCSEncryptionForSubscription:]
+ -[CKLazuliEnablementManager _isRCSEncryptionEnabledForSubscription:]
+ -[CKLazuliEnablementManager _setRCSEncryptionEnabledForSubscription:enabled:]
+ -[CKLazuliEnablementManager _showRCSEncryptionForSubscription:]
+ -[CKLazuliEnablementManager canSetRCSEncryption]
+ -[CKLazuliEnablementManager isRCSEncryptionEnabledForAnyActiveSubscription]
+ -[CKLazuliEnablementManager setRCSEncryptionEnabled:specifier:]
+ -[CKLazuliEnablementManager showRCSEncryption]
+ -[CKRCSController isRCSEncryptionEnabled:]
+ -[CKRCSController setRCSEncryptionEnabled:specifier:]
+ -[CKSettingSMSRelayController _headerSpecifierForQuickSwitchGroup]
+ GCC_except_table190
CStrings:
+ "%@ supports encrypted RCS"
+ "Auto-enrolling Quick Switch circle device. deviceID={%@}"
+ "CKSettingSMSRelayController_QuickSwitch"
+ "Device {%@} not matched. device.pushToken={%@}, quickSwitchPushTokens={%@}"
+ "Error enabling/disabling RCS encryption: %@"
+ "No subscriptions support encrypted RCS."
+ "QUICK_SWITCH_SMS_RELAY_GROUP"
+ "Quick Switch circle devices: {%lu}, error: {%@}"
+ "Quick Switch mode: {%ld}, active: {%@}"
+ "QuickSwitch role: %ld for %@ (carrierContextError: %@)"
+ "RCSEncryption"
+ "RCS_ENCRYPTION_BETA"
+ "RCS_ENCRYPTION_BETA_FOOTER"
+ "RCS_ENCRYPTION_FULL_SUPPORT"
+ "RCS_ENCRYPTION_PARTIAL_SUPPORT"
+ "SMS_MMS_RCS_RELAY_QUICK_SWITCH_DEVICES_FOOTER"
+ "Set RCS Encryption Enabled: %@"
+ "Show Text Message Forwarding=%{BOOL}d\naccountOperational=%{BOOL}d iMessageAccounts=%lu appleAccountSignedIn=%{BOOL}d hasPhoneNumber=%{BOOL}d supportsSMS=%{BOOL}d getsSMS=%{BOOL}d idsHasRelayDevices=%{BOOL}d"
```
