## MessagesSettingsUI

> `/System/Library/PrivateFrameworks/MessagesSettingsUI.framework/MessagesSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x339d4` | `0x33884` | **`-0x150`** |
| `__TEXT.__cstring` | `0x1ff0` | `0x1fb0` | **`-0x40`** |
| `__AUTH_CONST.__cfstring` | `0x1560` | `0x1540` | **`-0x20`** |
| `__TEXT.__const` | `0x2544` | `0x2554` | **`+0x10`** |

### Other Changes

```diff

-1481.100.29.2.9
+1483.100.10.2.4

-  CStrings:  346
+  CStrings:  345
Functions:
~ -[CKSettingsSharedWithYouController specifiers] : 540 -> 548
~ -[CKSettingsSharedWithYouController sharedWithYouEnabled:] : 208 -> 216
~ -[CKSettingsSharedWithYouController setupDefaultAppsIfRequired] : 1020 -> 776
~ -[CKSettingsSharedWithYouController getAppSpecifiers] : 692 -> 688
~ -[CKSettingsSharedWithYouController appIsEnabled:] : 412 -> 420
~ -[CKSettingsiMessageAppsViewController _iMessageOnlyAppsSpecifiers] : 448 -> 444
~ -[CKSettingsiMessageAppsViewController _appsWithiMessageAppsSpecifiers] : 500 -> 496
~ -[CKSettingsiMessageApp _stringArrayFromUserDefaults:key:] : 408 -> 404
~ -[CKSettingsiMessageAppManager deletableiMessageOnlyApps] : 368 -> 364
~ -[CKSettingsiMessageAppManager deletableAppsWithiMessageApp] : 368 -> 364
~ -[CKSettingsiMessageAppManager appWithBundleID:] : 400 -> 396
~ -[CKSettingsiMessageAppManager _loadiMessageAppsSyncronouslyForExtensionPoint:] : 580 -> 576
~ ___63-[CKSettingsiMessageAppManager _beginMonitoringExtensionPoint:]_block_invoke.94 : 424 -> 416
~ -[CKSettingsCriticalMessagesViewController specifiers] : 536 -> 532
~ -[CKSettingsCriticalMessagesApp _activeNumberCount] : 260 -> 256
~ -[CKSettingsCriticalMessagesDetailViewController specifiers] : 1200 -> 1196
~ -[CKSettingsCriticalMessagesDetailViewController numberActive:] : 460 -> 456
~ -[CKSettingsCriticalMessagesAppManager init] : 704 -> 700
~ -[CKSettingsCriticalMessagesAppManager criticalMessagesAppForBundleID:] : 340 -> 336
~ -[CKSettingsCriticalMessagesAppManager setActive:forPhoneNumber:inAppForBundle:] : 660 -> 656
~ -[CKSharedSettingsHelper isCheckInAllowedInRegion] : 796 -> 792
~ -[CKSharedSettingsHelper shouldShowSMSRelaySettings] : 408 -> 404
~ -[CKSharedSettingsHelper hasPhoneNumber] : 396 -> 392
~ -[CKSharedSettingsHelper _sharedWithYouEnabled] : 104 -> 112
~ -[CKSharedSettingsHelper systemPolicySpecifiers] : 376 -> 372
~ -[CKSettingSMSRelayController specifiers] : 1168 -> 1160
~ -[CKSettingSMSRelayController _specifiersForDevices:cellType:get:] : 516 -> 512
~ +[CKSettingSMSRelayController deviceIsAuthorized:] : 288 -> 284
~ +[CKSettingSMSRelayController isDeviceUsingMiCWithIdentifier:] : 288 -> 284
~ +[CKSettingSMSRelayController numberOfActiveDevices] : 376 -> 372
~ +[CKSettingSMSRelayController shouldShowSMSRelaySettings] : 308 -> 304
~ sub_287f086dc -> sub_2899e2598 : 380 -> 360
~ sub_287f0f2fc -> sub_2899e91a4 : 244 -> 252
~ sub_287f11d08 -> sub_2899ebbb8 : 504 -> 512
~ sub_287f1c7d0 -> sub_2899f6688 : 140 -> 136
~ sub_287f21da0 -> sub_2899fbc54 : 280 -> 276
CStrings:
- "Messages Settings: Shared With You: Adding collaboration Apps"
```
