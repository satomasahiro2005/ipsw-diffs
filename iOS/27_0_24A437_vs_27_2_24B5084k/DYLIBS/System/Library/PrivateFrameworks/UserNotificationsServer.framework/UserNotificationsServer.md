## UserNotificationsServer

> `/System/Library/PrivateFrameworks/UserNotificationsServer.framework/UserNotificationsServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3c3c0` | `0x3cc0c` | **`+0x84c`** |
| `__AUTH_CONST.__cfstring` | `0xdc0` | `0xe80` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x16b8` | `0x1758` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x12b0` | `0x1320` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x6865` | `0x68b5` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x24d4` | `0x2504` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c10` | `0x2c30` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xdf8` | `0xe10` | **`+0x18`** |
| `__TEXT.__const` | `0x4e4` | `0x4f4` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xa30` | `0xa38` | **`+0x8`** |
| `__AUTH_CONST.__objc_const` | `0x5f28` | `0x5f30` | **`+0x8`** |

### Other Changes

```diff

-720.0.0.0.0
+720.2.6.0.0

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 1138
-  Symbols:   2035
-  CStrings:  527
+  Functions: 1146
+  Symbols:   2047
+  CStrings:  535
Symbols:
+ -[UNSNotificationSettingsService copyNotificationSettingsFromSourceIdentifier:toSourceIdentifier:withCompletionHandler:]
+ -[UNSSettingsGateway copySectionSettingsFromSectionID:toSectionID:withCompletion:]
+ -[UNSSettingsGateway setSectionInfo:forSectionID:source:]
+ -[UNSUserNotificationServerSettingsConnectionListener copyNotificationSettingsFromSourceIdentifier:toSourceIdentifier:withCompletionHandler:]
+ GCC_except_table22
+ GCC_except_table25
+ GCC_except_table30
+ _AnalyticsSendEventLazy
+ ___120-[UNSNotificationSettingsService copyNotificationSettingsFromSourceIdentifier:toSourceIdentifier:withCompletionHandler:]_block_invoke
+ ___57-[UNSSettingsGateway setSectionInfo:forSectionID:source:]_block_invoke
+ ___82-[UNSSettingsGateway copySectionSettingsFromSectionID:toSectionID:withCompletion:]_block_invoke
+ ___UNSSendAuthorizationPromptAnalytics_block_invoke
+ ___block_descriptor_40_e8_32bs_e8_v12?0B8ls32l8
+ ___block_descriptor_58_e19_"NSDictionary"8?0l
+ ___block_descriptor_64_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_81_e8_32s40s48s56s64bs_e8_v16?0q8ls32l8s40l8s48l8s56l8s64l8
- GCC_except_table21
- GCC_except_table23
- GCC_except_table28
- ___block_descriptor_72_e8_32s40s48s56bs_e8_v16?0q8ls32l8s40l8s48l8s56l8
CStrings:
+ "@\"NSDictionary\"8@?0"
+ "UNSNotificationSettingsService [%{public}@] Copying notification settings from %{public}@"
+ "com.apple.usernotifications.settings.authorizationPrompt"
+ "hasUsageDescription"
+ "outcome"
+ "promptKind"
+ "requestedOptions"
+ "showedDeliveryOptions"
```
