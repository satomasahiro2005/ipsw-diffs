## MedicationsHealthAppPlugin

> `/System/Library/PrivateFrameworks/MedicationsHealthAppPlugin.framework/MedicationsHealthAppPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x4482` | `0x45f2` | **`+0x170`** |
| `__TEXT.__text` | `0x12cefc` | `0x12cdd0` | **`-0x12c`** |
| `__AUTH_CONST.__const` | `0x4070` | `0x4020` | **`-0x50`** |
| `__AUTH_CONST.__auth_got` | `0x3128` | `0x3168` | **`+0x40`** |
| `__TEXT.__const` | `0x8fd4` | `0x9014` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x57c0` | `0x57e0` | **`+0x20`** |
| `__DATA_DIRTY.__objc_data` | `0x2688` | `0x26a8` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x592c` | `0x590c` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x3ae8` | `0x3ac8` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x44a0` | `0x44b8` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x26a4` | `0x2690` | **`-0x14`** |
| `__DATA.__bss` | `0x6f80` | `0x6f90` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x14d8` | `0x14c8` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0xdc0` | `0xdb0` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x2a00` | `0x2a10` | **`+0x10`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 4737
+  Functions: 4734

-  CStrings:  611
+  CStrings:  616
Symbols:
+ _symbolic _____Sg 14HealthPlatform28PinnedContentManagerProviderC
- _symbolic ScCySo8HKSampleCSg______pG s5ErrorP
CStrings:
+ "MedicationHighlightsFeedItem:fetchLatestDoseEventChanges"
+ "MedicationHighlightsFeedItem:isValidMedicationIdentifier"
+ "MedicationsDataLoggingExecutor:getLatestSample"
+ "MedicationsLoggingSummaryFeedItem:fetchDoseEvents"
+ "MedicationsLoggingSummaryFeedItem:fetchLatestDoseEventDateInterval"
+ "MedicationsUserDomainConceptChangesInputSignal:query"
+ "SharedMedicationsModel:getMostRecentDoseEvent"
- "com.apple.Health"
- "getLatestSample(for:)"
```
