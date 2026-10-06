## mobilerepaird

> `/usr/libexec/mobilerepaird`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d29c` | `0x1de8c` | **`+0xbf0`** |
| `__TEXT.__cstring` | `0x3de6` | `0x3f89` | **`+0x1a3`** |
| `__DATA_CONST.__cfstring` | `0x3e40` | `0x3fe0` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x2cb7` | `0x2e00` | **`+0x149`** |
| `__TEXT.__objc_methname` | `0x3fb9` | `0x40f9` | **`+0x140`** |
| `__TEXT.__objc_stubs` | `0x36c0` | `0x37a0` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0xc20` | `0xcc0` | **`+0xa0`** |
| `__TEXT.__objc_methtype` | `0xce2` | `0xd1b` | **`+0x39`** |
| `__DATA.__objc_selrefs` | `0x1070` | `0x10a8` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x181c` | `0x1844` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x490` | `0x4b0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x980` | `0x9a0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x4d0` | `0x4e0` | **`+0x10`** |
| `__TEXT.__const` | `0x152` | `0x162` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x728` | `0x738` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x974` | `0x980` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1307.40.46.0.0
+1307.40.51.0.0

-  Functions: 600
-  Symbols:   292
-  CStrings:  1557
+  Functions: 609
+  Symbols:   298
+  CStrings:  1583
Symbols:
+ _OBJC_CLASS_$_CRUtils
+ _OBJC_CLASS_$_NSThread
+ _kCRNetworkRetryDelaySeconds
+ _kCRNetworkRetryMaxAttempts
+ _objc_retain_x28
+ _objc_retain_x9
CStrings:
+ "-[MRBaseComponentHandler sendFinishRepairNotificationShownAnalytics]_block_invoke"
+ "-[MRComponentHealthHandler sendDailyAnalyticsForModuleType:eventType:]_block_invoke"
+ "Attempt:     %lu/%lu\n"
+ "B56@0:8Q16d24@32@40@?48"
+ "CoreAnalyticsEvent: ModuleType(%@), EventType(FinishRepairNotificationShown)"
+ "CoreAnalyticsEvent: ModuleType(%{public}@), Event(%{public}@)"
+ "DailyPendingRepair"
+ "FinishRepairNotificationShown"
+ "NotifyServerFailure"
+ "NotifyServerSuccess"
+ "OperationScheduled_"
+ "ReachedShipModeOther"
+ "ReachedShipModeTradeIn"
+ "ShipMode"
+ "ShipModeNotify: %{public}@ transport failure on attempt %{public}lu/%{public}lu (code=%{public}ld), retrying in %{public}.0fs"
+ "ShipModeNotify: BAA issuance transport failure on attempt %{public}lu/%{public}lu (code=%{public}ld), retrying in %{public}.0fs: %{private}@"
+ "StepFailedDischarge"
+ "StepFailedErase"
+ "_dumpRequestIfEnabled:command:attempt:responseBody:httpResponse:transportError:"
+ "_issueBAAOnce:certificatePEM:error:"
+ "_performRequest:baseURL:enabled:deviceError:partnerID:attempt:startedAtClock:replyOnce:"
+ "_performStatusRequest:statusURL:attempt:startedAtClock:replyOnce:"
+ "_scheduleRetryForAttempt:startedAtClock:label:transportError:retry:"
+ "getInnermostNSError:"
+ "networkRetryClock"
+ "sendDailyAnalyticsForModuleType:eventType:"
+ "sendFinishRepairNotificationShownAnalytics"
+ "shipmode-%@-%@-attempt%lu.log"
+ "shouldRetryNetworkError:attempt:startedAtClock:"
+ "sleepForTimeInterval:"
+ "v56@0:8@16@24Q32d40@?48"
+ "v64@0:8@16@24Q32@40@48@56"
+ "v72@0:8@16@24B32B36@40Q48d56@?64"
- "-[MRComponentHealthHandler sendDailyAnalyticsForModuleType:]_block_invoke"
- "_dumpRequestIfEnabled:command:responseBody:httpResponse:transportError:"
- "_performRequest:baseURL:enabled:deviceError:partnerID:replyOnce:"
- "_performStatusRequest:statusURL:replyOnce:"
- "sendDailyAnalyticsForModuleType:"
- "v56@0:8@16@24@32@40@48"
- "v56@0:8@16@24B32B36@40@?48"
```
