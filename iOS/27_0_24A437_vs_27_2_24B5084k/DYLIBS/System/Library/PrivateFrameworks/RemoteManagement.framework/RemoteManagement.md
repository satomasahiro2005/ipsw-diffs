## RemoteManagement

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/RemoteManagement`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4bce8` | `0x4c764` | **`+0xa7c`** |
| `__AUTH_CONST.__objc_const` | `0x2eb8` | `0x3358` | **`+0x4a0`** |
| `__TEXT.__objc_methlist` | `0x1bf0` | `0x1e98` | **`+0x2a8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1418` | `0x1588` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x492b` | `0x49fb` | **`+0xd0`** |
| `__DATA.__data` | `0x6c8` | `0x788` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0x568` | `0x608` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x41c` | `0x4b0` | **`+0x94`** |
| `__TEXT.__unwind_info` | `0xf60` | `0xf98` | **`+0x38`** |
| `__DATA.__objc_ivar` | `0xc8` | `0xf4` | **`+0x2c`** |
| `__AUTH_CONST.__const` | `0xbf0` | `0xc10` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x598` | `0x5b0` | **`+0x18`** |
| `__DATA.__bss` | `0x2400` | `0x2410` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x160` | `0x170` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x20` | `0x30` | **`+0x10`** |
| `__TEXT.__cstring` | `0x2397` | `0x23a7` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xb68` | `0xb70` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x68` | `0x70` | **`+0x8`** |

### Other Changes

```diff

-624.2.3.0.0
+624.40.12.0.0

-  Functions: 1389
-  Symbols:   1623
-  CStrings:  691
+  Functions: 1421
+  Symbols:   1695
+  CStrings:  695
Symbols:
+ +[RMLog(throttlingDebounceTimer) throttlingDebounceTimer]
+ +[RMThrottlingDebounceTimer throttlingDebounceTimerWithThreshold:window:minimumInterval:maximumInterval:identifier:action:]
+ +[RMXPCUtilities doesConnection:haveEntitlement:]
+ +[RMXPCUtilities isPlatformBinaryForConnection:]
+ -[RMThrottlingDebounceTimer .cxx_destruct]
+ -[RMThrottlingDebounceTimer _pruneSignalsBefore:]
+ -[RMThrottlingDebounceTimer _releaseThrottleLocked]
+ -[RMThrottlingDebounceTimer action]
+ -[RMThrottlingDebounceTimer coalescedSignalCount]
+ -[RMThrottlingDebounceTimer debouncer]
+ -[RMThrottlingDebounceTimer identifier]
+ -[RMThrottlingDebounceTimer initWithThreshold:window:minimumInterval:maximumInterval:identifier:action:]
+ -[RMThrottlingDebounceTimer isThrottling]
+ -[RMThrottlingDebounceTimer maximumInterval]
+ -[RMThrottlingDebounceTimer minimumInterval]
+ -[RMThrottlingDebounceTimer setAction:]
+ -[RMThrottlingDebounceTimer setCoalescedSignalCount:]
+ -[RMThrottlingDebounceTimer setDebouncer:]
+ -[RMThrottlingDebounceTimer setIdentifier:]
+ -[RMThrottlingDebounceTimer setMaximumInterval:]
+ -[RMThrottlingDebounceTimer setMinimumInterval:]
+ -[RMThrottlingDebounceTimer setSignalTimestamps:]
+ -[RMThrottlingDebounceTimer setThreshold:]
+ -[RMThrottlingDebounceTimer setThrottling:]
+ -[RMThrottlingDebounceTimer setWindow:]
+ -[RMThrottlingDebounceTimer signalTimestamps]
+ -[RMThrottlingDebounceTimer threshold]
+ -[RMThrottlingDebounceTimer triggerAggregatingTimerAction]
+ -[RMThrottlingDebounceTimer trigger]
+ -[RMThrottlingDebounceTimer window]
+ _OBJC_CLASS_$_NSMutableArray
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_CLASS_$_RMThrottlingDebounceTimer
+ _OBJC_CLASS_$_RMXPCUtilities
+ _OBJC_IVAR_$_RMThrottlingDebounceTimer._action
+ _OBJC_IVAR_$_RMThrottlingDebounceTimer._coalescedSignalCount
+ _OBJC_IVAR_$_RMThrottlingDebounceTimer._debouncer
+ _OBJC_IVAR_$_RMThrottlingDebounceTimer._identifier
+ _OBJC_IVAR_$_RMThrottlingDebounceTimer._lock
+ _OBJC_IVAR_$_RMThrottlingDebounceTimer._maximumInterval
+ _OBJC_IVAR_$_RMThrottlingDebounceTimer._minimumInterval
+ _OBJC_IVAR_$_RMThrottlingDebounceTimer._signalTimestamps
+ _OBJC_IVAR_$_RMThrottlingDebounceTimer._threshold
+ _OBJC_IVAR_$_RMThrottlingDebounceTimer._throttling
+ _OBJC_IVAR_$_RMThrottlingDebounceTimer._window
+ _OBJC_METACLASS_$_RMThrottlingDebounceTimer
+ _OBJC_METACLASS_$_RMXPCUtilities
+ __OBJC_$_CLASS_METHODS_RMLog(nsdata_rm|nsdictionary_rm|accountHelper|debounceTimer|device|enrollmentController|jsonUtilities|locations|managedDevice|managedKeychainController|managedTrustStoreController|mcAdapter|mdmHelper|sandbox|sharedLock|throttlingDebounceTimer|timeddispatch|xpcEvent|xpcNotifications)
+ __OBJC_$_CLASS_METHODS_RMThrottlingDebounceTimer
+ __OBJC_$_CLASS_METHODS_RMXPCUtilities
+ __OBJC_$_INSTANCE_METHODS_RMThrottlingDebounceTimer
+ __OBJC_$_INSTANCE_VARIABLES_RMThrottlingDebounceTimer
+ __OBJC_$_PROP_LIST_NSObject
+ __OBJC_$_PROP_LIST_RMThrottlingDebounceTimer
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSObject
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSObject
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_RMDebounceTimerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSObject
+ __OBJC_$_PROTOCOL_METHOD_TYPES_RMDebounceTimerDelegate
+ __OBJC_$_PROTOCOL_REFS_RMDebounceTimerDelegate
+ __OBJC_CLASS_PROTOCOLS_$_RMThrottlingDebounceTimer
+ __OBJC_CLASS_RO_$_RMThrottlingDebounceTimer
+ __OBJC_CLASS_RO_$_RMXPCUtilities
+ __OBJC_LABEL_PROTOCOL_$_NSObject
+ __OBJC_LABEL_PROTOCOL_$_RMDebounceTimerDelegate
+ __OBJC_METACLASS_RO_$_RMThrottlingDebounceTimer
+ __OBJC_METACLASS_RO_$_RMXPCUtilities
+ __OBJC_PROTOCOL_$_NSObject
+ __OBJC_PROTOCOL_$_RMDebounceTimerDelegate
+ ___57+[RMLog(throttlingDebounceTimer) throttlingDebounceTimer]_block_invoke
+ _csops_audittoken
+ _throttlingDebounceTimer.onceToken
+ _throttlingDebounceTimer.result
- __OBJC_$_CLASS_METHODS_RMLog(nsdata_rm|nsdictionary_rm|accountHelper|debounceTimer|device|enrollmentController|jsonUtilities|locations|managedDevice|managedKeychainController|managedTrustStoreController|mcAdapter|mdmHelper|sandbox|sharedLock|timeddispatch|xpcEvent|xpcNotifications)
CStrings:
+ "Throttling engaged for %{public}@ (%lu signals within %g s)"
+ "Throttling released for %{public}@ (coalesced %lu signals into one action)"
+ "Throttling released for %{public}@ (rate subsided, coalesced %lu signals)"
+ "throttlingDebounceTimer"
```
