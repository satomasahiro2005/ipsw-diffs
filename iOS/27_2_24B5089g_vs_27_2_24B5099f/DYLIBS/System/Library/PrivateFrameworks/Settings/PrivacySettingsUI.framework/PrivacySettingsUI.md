## PrivacySettingsUI

> `/System/Library/PrivateFrameworks/Settings/PrivacySettingsUI.framework/PrivacySettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x69c44` | `0x6a6e4` | **`+0xaa0`** |
| `__TEXT.__oslogstring` | `0x2e70` | `0x2fb0` | **`+0x140`** |
| `__TEXT.__cstring` | `0x8694` | `0x87c4` | **`+0x130`** |
| `__DATA_CONST.__const` | `0x1b48` | `0x1bc0` | **`+0x78`** |
| `__TEXT.__gcc_except_tab` | `0x130c` | `0x135c` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x18c0` | `0x18e8` | **`+0x28`** |
| `__DATA_CONST.__got` | `0xa98` | `0xab8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x3460` | `0x3480` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x360` | `0x378` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x442c` | `0x4444` | **`+0x18`** |

### Other Changes

```diff

-2027.1.7.0.0
+2027.1.9.0.0

-  Functions: 2178
-  Symbols:   3778
-  CStrings:  1452
+  Functions: 2189
+  Symbols:   3789
+  CStrings:  1463
Symbols:
+ -[PUITrackingReportManager clearTrackingHistoryForBundleIDs:completion:]
+ -[PUITrackingReportManager clearTrackingHistoryWithCompletion:]
+ GCC_except_table37
+ ___63-[PUITrackingReportManager clearTrackingHistoryWithCompletion:]_block_invoke
+ ___72-[PUITrackingReportManager clearTrackingHistoryForBundleIDs:completion:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e34_v24?0"NSDictionary"8"NSError"16ls40l8s32l8
+ ___block_descriptor_56_e8_32bs40r48w_e34_v24?0"NSDictionary"8"NSError"16lw48l8s32l8r40l8
+ ___block_descriptor_56_e8_32s40bs48w_e5_v8?0ls32l8w48l8s40l8
+ _kSymptomAnalyticsServiceDomainTrackingClearHistoryBundleIDs
+ _kSymptomAnalyticsServiceDomainTrackingClearHistoryEndDate
+ _kSymptomAnalyticsServiceDomainTrackingClearHistoryKey
+ _kSymptomAnalyticsServiceDomainTrackingClearHistoryStartDate
- ___58-[PUIReportController setRecordActivityEnabled:specifier:]_block_invoke_3
CStrings:
+ "%s: cleared tracking history, outcome: %@"
+ "%s: clearing tracking history for %lu apps"
+ "%s: could not clear the recorded tracking history"
+ "%s: failed to clear tracking history: %@"
+ "%s: failed to enumerate the apps holding tracking records: %@"
+ "%s: failed to send the clear history request"
+ "%s: no tracking records to clear"
+ "-[PUIReportController setRecordActivityEnabled:specifier:]_block_invoke_2"
+ "-[PUITrackingReportManager clearTrackingHistoryForBundleIDs:completion:]"
+ "-[PUITrackingReportManager clearTrackingHistoryForBundleIDs:completion:]_block_invoke"
+ "-[PUITrackingReportManager clearTrackingHistoryWithCompletion:]_block_invoke"
```
