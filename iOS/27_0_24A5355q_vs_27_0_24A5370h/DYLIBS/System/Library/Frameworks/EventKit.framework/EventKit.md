## EventKit

> `/System/Library/Frameworks/EventKit.framework/EventKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a13ac` | `0x1a1160` | **`-0x24c`** |
| `__TEXT.__oslogstring` | `0xede8` | `0xef48` | **`+0x160`** |
| `__TEXT.__objc_methlist` | `0x15a0c` | `0x15a4c` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x18520` | `0x18540` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xae20` | `0xae40` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x3904` | `0x3918` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x1410` | `0x1400` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0xd60` | `0xd64` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1965.0.0.0.0
+1968.0.0.0.0

-  Functions: 10651
-  Symbols:   13221
-  CStrings:  2660
+  Functions: 10661
+  Symbols:   13226
+  CStrings:  2665
Symbols:
+ +[EKAutocompletePendingSearch _pastEventRecencyCutoff]
+ +[EKAutocompletePendingSearch _searchPastEventRecencyYears]
+ -[EKCalendarNotificationReference redactedDescription]
+ -[EKDaemonConnection simulateConnectionInterruption]
+ -[EKPredicateMonitor _notifyAllPredicateUpdateCompletionCallbacksOfError:]
+ _OBJC_IVAR_$_EKPredicateMonitor._hasEverReceivedReset
+ ___74-[EKPredicateMonitor _notifyAllPredicateUpdateCompletionCallbacksOfError:]_block_invoke
+ ___block_descriptor_70_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ _objc_retain_x10
- ___block_descriptor_61_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
- _swift_release_x10
- _swift_release_x9
- _swift_retain_x9
CStrings:
+ "%p Received disabling reset with %lu new events"
+ "Received diagnostics collection result for token %u, but there is no operation with that token."
+ "Received occurrence cache search result for token %u, but there is no operation with that token."
+ "Received predicate results for token %u, but there is no operation with that token."
+ "Simulated connection interruption!"
```
