## SiriAppIntentsRuntime

> `/System/Library/PrivateFrameworks/SiriAppIntentsRuntime.framework/SiriAppIntentsRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7c728` | `0x815b4` | **`+0x4e8c`** |
| `__AUTH_CONST.__const` | `0x4378` | `0x4648` | **`+0x2d0`** |
| `__TEXT.__oslogstring` | `0x32dd` | `0x348d` | **`+0x1b0`** |
| `__TEXT.__eh_frame` | `0x4670` | `0x4818` | **`+0x1a8`** |
| `__TEXT.__swift5_capture` | `0x1758` | `0x1880` | **`+0x128`** |
| `__TEXT.__unwind_info` | `0x1a10` | `0x1ac0` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x12f3` | `0x1385` | **`+0x92`** |
| `__TEXT.__cstring` | `0x1431` | `0x14b1` | **`+0x80`** |
| `__TEXT.__const` | `0x2798` | `0x2808` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0x1888` | `0x18e8` | **`+0x60`** |
| `__DATA.__data` | `0x7e8` | `0x828` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x2cc` | `0x2ec` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x3e8` | `0x404` | **`+0x1c`** |
| `__DATA_DIRTY.__objc_data` | `0x9c0` | `0x9d8` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x1c0` | `0x1cc` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x170` | `0x17c` | **`+0xc`** |
| `__AUTH_CONST.__objc_const` | `0xcc8` | `0xcd0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x438` | `0x440` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0xc9c` | `0xca4` | **`+0x8`** |

### Other Changes

```diff

-3600.82.15.0.0
+3600.82.20.0.0

-  Functions: 2792
-  Symbols:   214
-  CStrings:  330
+  Functions: 2905
+  Symbols:   216
+  CStrings:  337
Symbols:
+ _swift_projectBox
+ _swift_release_x1
CStrings:
+ "Failed to fetch raw inference event data batch: %@"
+ "Fetched raw inference event data batch: %ld success, %ld errors"
+ "Fetching raw inference event data batch for %ld plannerIDs"
+ "TimeInterval.from: kind=clampedAnomalousTimestamp machContinuousTime=%llu"
+ "fetchEventsBatch(plannerIDs:windowStart:windowEnd:)"
+ "fetchRawInferenceEventDataBatch(plannerIDs:plannerTimestamps:with:)"
+ "kind=summary TokenGenerationStreamHandler.fetchEventsBatch plannerIDsRequested=%ld matched=%ld bucketsReturned=%ld"
+ "kind=summary fetchRawInferenceEventDataBatch requested=%ld payloads=%ld errors=%ld windowSeconds=%ld"
+ "kind=summary fetchRawInferenceEventDataBatch status=noValidInputs requested=%ld errors=%ld"
+ "plannerID is not a valid UUID"
- "TokenGenerationStreamHandler.fetchEvents: kind=summary plannerID=%s matched=%ld"
- "TokenGenerationStreamHandler.fetchEvents: kind=summary status=failed plannerID=%s error=%s"
- "fetchEvents(plannerID:requestTimestamp:)"
```
