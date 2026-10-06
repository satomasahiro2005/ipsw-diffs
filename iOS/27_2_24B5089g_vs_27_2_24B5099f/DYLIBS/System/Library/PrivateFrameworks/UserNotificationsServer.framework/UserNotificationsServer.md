## UserNotificationsServer

> `/System/Library/PrivateFrameworks/UserNotificationsServer.framework/UserNotificationsServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3cc0c` | `0x3ce18` | **`+0x20c`** |
| `__TEXT.__oslogstring` | `0x68b5` | `0x6985` | **`+0xd0`** |
| `__AUTH.__objc_data` | `0x170` | `0x120` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x7d0` | `0x820` | **`+0x50`** |
| `__TEXT.__const` | `0x4f4` | `0x504` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xe10` | `0xe18` | **`+0x8`** |

### Other Changes

```diff

-720.2.6.0.0
+720.2.7.0.0

-  Functions: 1146
-  Symbols:   2047
-  CStrings:  535
+  Functions: 1147
+  Symbols:   2048
+  CStrings:  536
Symbols:
+ -[UNSSettingsGateway copySectionSettingsFromSectionID:toSectionID:destinationCapabilities:withCompletion:]
+ _BBSectionSettingsCapabilitiesFromUNCNotificationSourceDescription
+ ___106-[UNSSettingsGateway copySectionSettingsFromSectionID:toSectionID:destinationCapabilities:withCompletion:]_block_invoke
- -[UNSSettingsGateway copySectionSettingsFromSectionID:toSectionID:withCompletion:]
- ___82-[UNSSettingsGateway copySectionSettingsFromSectionID:toSectionID:withCompletion:]_block_invoke
CStrings:
+ "UNSNotificationSettingsService [%{public}@] Destination capabilities 0x%lx [ allowCriticalAlerts: %{BOOL}d, allowTimeSensitive: %{BOOL}d, supportsTimeSensitive: %{BOOL}d, allowMessages: %{BOOL}d ]"
```
