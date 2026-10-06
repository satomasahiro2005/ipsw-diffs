## DAEAS

> `/System/Library/PrivateFrameworks/ExchangeSync.framework/Frameworks/DAEAS.framework/DAEAS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x941e0` | `0x94f0c` | **`+0xd2c`** |
| `__TEXT.__cstring` | `0x93c9` | `0x9554` | **`+0x18b`** |
| `__AUTH_CONST.__cfstring` | `0x7480` | `0x75e0` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x5714` | `0x5834` | **`+0x120`** |
| `__TEXT.__gcc_except_tab` | `0xb70` | `0xc34` | **`+0xc4`** |
| `__TEXT.__objc_methlist` | `0xa5c4` | `0xa684` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0x16a78` | `0x16af8` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x4890` | `0x4908` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x1a10` | `0x1a70` | **`+0x60`** |
| `__DATA_CONST.__const` | `0xa80` | `0xaa8` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0xe0` | `0x100` | **`+0x20`** |
| `__DATA.__bss` | `0x42e` | `0x43e` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xad0` | `0xae0` | **`+0x10`** |
| `__TEXT.__const` | `0x700` | `0x708` | **`+0x8`** |

### Other Changes

```diff

-2079.0.1.0.0
+2079.200.31.0.0

-  Functions: 3436
-  Symbols:   6090
-  CStrings:  1845
+  Functions: 3455
+  Symbols:   6122
+  CStrings:  1859
Symbols:
+ -[ASAccount _resetServerBackoffStateLocked]
+ -[ASAccount _serverBackoffHeaderDelayForError:]
+ -[ASAccount _serverBackoffHeaderDelayFromUserInfo:]
+ -[ASAccount clearServerBackoff]
+ -[ASAccount isInServerBackoff]
+ -[ASAccount noteServerThrottleFromError:]
+ -[ASAccount noteServerThrottleFromThrottleHeaders:]
+ -[ASAccount recordFanOutReadHoldForWindowUntil:]
+ -[ASAccount recordServerThrottleTelemetryForNewWindow:reason:delaySeconds:until:]
+ -[ASAccount resetServerThrottleFallback]
+ -[ASAccount scheduleServerBackoffDrainAfter:]
+ -[ASAccount serverBackoffUserInfo]
+ -[ASClientAccount recordFanOutReadHoldForWindowUntil:]
+ -[ASFolderItemsSyncTask containsOnlyFanOutReadActions]
+ -[ASItemOperationsFetchAttachmentTask containsOnlyFanOutReadActions]
+ -[ASItemOperationsTask containsOnlyFanOutReadActions]
+ -[ASTask containsOnlyFanOutReadActions]
+ GCC_except_table16
+ GCC_except_table3
+ GCC_except_table42
+ GCC_except_table53
+ OBJC_IVAR_$_ASAccount._serverBackoffAccumulator
+ OBJC_IVAR_$_ASAccount._serverBackoffLastDelay
+ OBJC_IVAR_$_ASAccount._serverBackoffUntil
+ _ASHTTPThrottleBackoffDurationKey
+ _ASHTTPThrottleReasonKey
+ _ASHTTPThrottleRetryAfterKey
+ _ASServerBackoffSecondsKey
+ _ASServerBackoffUntilKey
+ _CalCalendarSetIsAffectingAvailability
+ _OBJC_IVAR_$_ASClientAccount._lastLoggedFanOutReadHoldDeadline
+ ___51-[ASAccount _serverBackoffHeaderDelayFromUserInfo:]_block_invoke
+ __serverBackoffHeaderDelayFromUserInfo:.imfFormatter
+ __serverBackoffHeaderDelayFromUserInfo:.onceToken
- GCC_except_table59
- GCC_except_table88
CStrings:
+ "#EASTraffic #AccountID: %{public}@ Holding mail Sync until %{public}@; this process is in a server-throttle backoff."
+ "503 for an ungated command while already in a server-throttle backoff (until %@); does not extend the window."
+ "ASHTTPThrottleBackoffDurationKey"
+ "ASHTTPThrottleReasonKey"
+ "ASHTTPThrottleRetryAfterKey"
+ "ASServerBackoffSecondsKey"
+ "ASServerBackoffUntilKey"
+ "Clearing server throttle backoff (was until %@)"
+ "EEE, dd MMM yyyy HH:mm:ss 'GMT'"
+ "Holding fan-out read task %@; account is in a server-throttle backoff."
+ "Retry-After"
+ "Server sent a non-empty Retry-After we couldn't parse as seconds or an HTTP-date (%{public}@); using the backoff fallback."
+ "X-MS-ASThrottle"
+ "X-MS-BackOffDuration"
```
