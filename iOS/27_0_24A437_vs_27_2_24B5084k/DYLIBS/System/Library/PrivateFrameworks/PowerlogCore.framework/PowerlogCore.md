## PowerlogCore

> `/System/Library/PrivateFrameworks/PowerlogCore.framework/PowerlogCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe8af4` | `0xe96d4` | **`+0xbe0`** |
| `__TEXT.__oslogstring` | `0x8a24` | `0x8bc8` | **`+0x1a4`** |
| `__AUTH_CONST.__cfstring` | `0x6cf60` | `0x6d100` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x4387e` | `0x43920` | **`+0xa2`** |
| `__DATA_CONST.__objc_arraydata` | `0x45e58` | `0x45ef8` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x97a8` | `0x9828` | **`+0x80`** |
| `__AUTH_CONST.__objc_dictobj` | `0xfcf8` | `0xfd48` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x59a0` | `0x59f0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x2600` | `0x2640` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x3108` | `0x3138` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x2a38` | `0x2a58` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x4cb0` | `0x4cc8` | **`+0x18`** |
| `__TEXT.__const` | `0x1c38` | `0x1c30` | **`-0x8`** |

### Other Changes

```diff

-3486.2.4.0.0
+3486.40.92.0.0

-  Functions: 4953
-  Symbols:   7265
-  CStrings:  15273
+  Functions: 4966
+  Symbols:   7274
+  CStrings:  15295
Symbols:
+ +[PLDefaults(Submission) addActiveTaskingRequest:]
+ +[PLDefaults(Submission) removeActiveTaskingRequest:]
+ +[PLDefaults(Submission) removeAllActiveTaskingRequests]
+ +[PLDefaults(Submission) setLastUploadDate:ForSubmitReason:]
+ -[PLSubmissionConfig getSubmitReasonTypeToDefaultsKey]
+ -[PLSubmissionFilePLL declaredRetentionIsExactly24HoursForLegacyEntryKeyConfig:]
+ -[PLSubmissionFilePLL declaredRetentionIsExactly24HoursForTimeToLiveInDays:]
+ -[PLSubmissionFilePLL tableHas24HourRetention:]
+ -[PLSubmissionFilePLL trialsTaskingTrimFiltersForTables:beforeDate:]
+ -[PLSubmissions shouldNotifyTaskingReceivedAndCompletedForConfig:]
+ __OBJC_$_CLASS_METHODS_PLDefaults(Submission)
- GCC_except_table73
- __OBJC_$_CLASS_METHODS_PLDefaults
CStrings:
+ "Abandoning '%@' task after %lu stalled retries with no progress..."
+ "CollectionSummary"
+ "DistinctCategoryCount"
+ "InternalOTA"
+ "InternalSafeguardOTA"
+ "Notify of powerlog tasking request received: %@"
+ "PLDefaults: Attempted to add duplicate tasking request: %@"
+ "PLLastUploadDate"
+ "PLTaskingRequests"
+ "PPSSignpostControllerStalledRetryCount"
+ "Powerlog tasking completed: %@"
+ "Powerlog tasking request received: %@"
+ "Powerlog tasking submit reason: (%d) %@"
+ "RunDuration"
+ "Send notification of tasking completed (%@)"
+ "SignpostServiceMetrics"
+ "TaskedOTA"
+ "TaskedUpgradeOTA"
+ "TotalSignpostCount"
+ "Trimming %lu trials tasking tables to 24h window (cutoff=%@)"
+ "Updated last upload date for %@"
+ "com.apple.powerlog.tasking_completed"
+ "com.apple.powerlog.tasking_received"
+ "displayX_apl"
- "timestamp is NULL OR timestamp < %f"
- "timestamp is NULL OR timestamp < (SELECT max(timestamp) FROM 'PLConfigAgent_EventNone_Config' WHERE timestamp < %f)"
```
