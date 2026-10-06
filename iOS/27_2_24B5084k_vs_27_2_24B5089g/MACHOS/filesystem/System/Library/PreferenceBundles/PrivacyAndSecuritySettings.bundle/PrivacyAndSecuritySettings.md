## PrivacyAndSecuritySettings

> `/System/Library/PreferenceBundles/PrivacyAndSecuritySettings.bundle/PrivacyAndSecuritySettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8f388` | `0x97c3c` | **`+0x88b4`** |
| `__TEXT.__eh_frame` | `0x2e14` | `0x36dc` | **`+0x8c8`** |
| `__TEXT.__swift5_typeref` | `0x7d8a` | `0x85a2` | **`+0x818`** |
| `__TEXT.__const` | `0x73f4` | `0x77e4` | **`+0x3f0`** |
| `__DATA.__bss` | `0x3a98` | `0x3e18` | **`+0x380`** |
| `__DATA_CONST.__const` | `0x3928` | `0x3c38` | **`+0x310`** |
| `__TEXT.__cstring` | `0x4486` | `0x4766` | **`+0x2e0`** |
| `__TEXT.__unwind_info` | `0x1f00` | `0x2160` | **`+0x260`** |
| `__DATA.__objc_const` | `0x2f40` | `0x3178` | **`+0x238`** |
| `__TEXT.__constg_swiftt` | `0x1688` | `0x1864` | **`+0x1dc`** |
| `__DATA.__data` | `0x3e70` | `0x4038` | **`+0x1c8`** |
| `__TEXT.__objc_methname` | `0x1f75` | `0x2095` | **`+0x120`** |
| `__TEXT.__swift5_fieldmd` | `0x1718` | `0x1820` | **`+0x108`** |
| `__TEXT.__swift_as_cont` | `0x1f4` | `0x2ec` | **`+0xf8`** |
| `__TEXT.__swift5_capture` | `0xb4c` | `0xc08` | **`+0xbc`** |
| `__TEXT.__auth_stubs` | `0x2cf0` | `0x2da0` | **`+0xb0`** |
| `__TEXT.__swift5_reflstr` | `0x1ba1` | `0x1c51` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0xf60` | `0xfc0` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x1688` | `0x16e0` | **`+0x58`** |
| `__TEXT.__objc_classname` | `0xd6a` | `0xdba` | **`+0x50`** |
| `__TEXT.__swift5_assocty` | `0x430` | `0x478` | **`+0x48`** |
| `__DATA_CONST.__got` | `0xb58` | `0xb88` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0x238` | `0x260` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x670` | `0x688` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x78` | `0x8c` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0xb4` | `0xc8` | **`+0x14`** |
| `__DATA.__common` | `0xf8` | `0x108` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0xd48` | `0xd58` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0xe4` | `0xf4` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x14` | `0x20` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x164` | `0x170` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x148` | `0x150` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-2027.1.5.1.100
+2027.1.7.0.0

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 2526
-  Symbols:   360
-  CStrings:  885
+  Functions: 2660
+  Symbols:   366
+  CStrings:  913
Symbols:
+ _AnalyticsCreateSession
+ _AnalyticsEndSession
+ _AnalyticsSendEventWithSession
+ _NSFileSize
+ _objc_release_x1
+ _swift_unknownObjectWeakAssign
CStrings:
+ "PrivacySettings.ExportAllFailed"
+ "PrivacySettings.TransferLogEmptyResult"
+ "_TtC26PrivacyAndSecuritySettings31PUIAnalyticsLogTelemetrySession"
+ "activeViewCount"
+ "attributesOfItemAtPath:error:"
+ "code"
+ "com.apple.settings.view_analytics_logs.export_complete"
+ "com.apple.settings.view_analytics_logs.export_initiated"
+ "com.apple.settings.view_analytics_logs.file_opened"
+ "com.apple.settings.view_analytics_logs.filter_applied"
+ "com.apple.settings.view_analytics_logs.pane_visit"
+ "com.apple.settings.view_analytics_logs.remote_device_request_complete"
+ "com.apple.settings.view_analytics_logs.remote_device_request_initiated"
+ "deviceClass"
+ "domain"
+ "fetchLogsOnBackgroundThread(for:deviceClass:using:)"
+ "generationLatencyMs"
+ "graceSeconds"
+ "hasEnded"
+ "missingFileCount"
+ "pendingEndTask"
+ "reportType"
+ "requestLatencyMs"
+ "requestedDeviceType"
+ "sessionDomain"
+ "sessionId"
+ "telemetry"
+ "telemetryFactory"
+ "transferLog(filePath:for:deviceClass:reportType:)"
+ "transport"
- "fetchLogsOnBackgroundThread(for:using:)"
- "transferLog(filePath:for:)"
```
