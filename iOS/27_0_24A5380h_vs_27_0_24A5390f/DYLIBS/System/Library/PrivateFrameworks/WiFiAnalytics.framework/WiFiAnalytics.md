## WiFiAnalytics

> `/System/Library/PrivateFrameworks/WiFiAnalytics.framework/WiFiAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x155a10` | `0x155bac` | **`+0x19c`** |
| `__TEXT.__gcc_except_tab` | `0x2614` | `0x2754` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x119f4` | `0x11aa0` | **`+0xac`** |
| `__TEXT.__unwind_info` | `0x2a30` | `0x2a38` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-825.56.0.0.0
+825.57.0.0.0

-  CStrings:  4075
+  CStrings:  4077
Symbols:
+ ___block_descriptor_64_e8_32s40s48bs56w_e5_v8?0ls48l8w56l8s32l8s40l8
- ___block_descriptor_56_e8_32s40s48w_e5_v8?0ls32l8w48l8s40l8
Functions:
~ -[WAClient _replyAllWithTimeoutErrorAndRemove] : 696 -> 728
~ ___46-[WAClient _replyAllWithTimeoutErrorAndRemove]_block_invoke : 436 -> 400
~ ___46-[WAClient _replyAllWithTimeoutErrorAndRemove]_block_invoke_2 : 92 -> 80
~ ___85-[AnalyticsStoreFileWriter batchedWriteAnalyticsStoreToCSVFilesWithBatchSize:maxAge:]_block_invoke : 1680 -> 2108
CStrings:
+ "%{public}s::%d:CoreData exception %@ in batchedWriteAnalyticsStoreToCSVFilesWithBatchSize:maxAge:"
+ "%{public}s::%d:analyticsStoreFileWriterDirectory nil, skipping CSV export"
+ "WiFiAnalytics-825.57 Jul 10 2026 23:31:20"
- "WiFiAnalytics-825.56 Jul  1 2026 23:27:25"
```
