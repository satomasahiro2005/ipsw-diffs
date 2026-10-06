## HangTracer

> `/System/Library/PrivateFrameworks/HangTracer.framework/HangTracer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17524` | `0x1837c` | **`+0xe58`** |
| `__AUTH_CONST.__objc_const` | `0x1a98` | `0x1cb8` | **`+0x220`** |
| `__TEXT.__objc_methlist` | `0x9fc` | `0xb6c` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x2bf4` | `0x2d1c` | **`+0x128`** |
| `__TEXT.__cstring` | `0x45aa` | `0x469d` | **`+0xf3`** |
| `__DATA_CONST.__objc_selrefs` | `0xa58` | `0xb48` | **`+0xf0`** |
| `__DATA.__data` | `0x220` | `0x30c` | **`+0xec`** |
| `__AUTH_CONST.__cfstring` | `0x5c60` | `0x5d20` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x17f8` | `0x1890` | **`+0x98`** |
| `__AUTH_CONST.__const` | `0x540` | `0x5c0` | **`+0x80`** |
| `__DATA.__bss` | `0xe0` | `0x138` | **`+0x58`** |
| `__TEXT.__lazy_helpers` | `—` | `0x54` | **`+0x54`** |
| `__AUTH.__objc_data` | `0x140` | `0x190` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x5d0` | `0x618` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0x5f0` | `0x610` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__const` | `0x268` | `0x258` | **`-0x10`** |
| `__AUTH_CONST.__lazy_load_got` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1f0` | `0x1f8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x30` | **`+0x8`** |

### Other Changes

```diff

-424.0.0.0.0
+426.0.0.0.0

-  Functions: 589
-  Symbols:   1315
-  CStrings:  1001
+  Functions: 606
+  Symbols:   1368
+  CStrings:  1012
Symbols:
+ -[HTBacklightHostObserver backlight:didCompleteUpdateToState:forEvent:]
+ GCC_except_table47
+ GCC_except_table49
+ GCC_except_table51
+ GCC_except_table54
+ GCC_except_table75
+ GCC_except_table85
+ _HTHangEventCreateWithBundleID.__htBacklight
+ _HTHangEventCreateWithBundleID.__htBacklightHostObserver
+ _HTHangEventCreateWithBundleID.sbBacklightHostObserverOnce
+ _HTHangEventCreateWithBundleID.sbLegacyDisplayComparisonOnce
+ _HTScreenOffAssertionQueue._htScreenOffAssertionQueue
+ _HTScreenOffAssertionQueue.onceToken
+ _HTTrackDisplayStateForMonitorComparison
+ _HTTrackDisplayStateForMonitorComparison.populateSystemDisplayStatusArrayToken
+ _HTTrackDisplayStateForMonitorComparison.prevDisplayState
+ _HTTrackDisplayStateForMonitorComparison.prevTransitionTime
+ _MCTU_TO_MS
+ _OBJC_CLASS_$_BLSBacklight
+ _OBJC_CLASS_$_BLSBacklight$lazyGOT
+ _OBJC_CLASS_$_BLSBacklight$lazyGOT$loadHelper_x8
+ _OBJC_CLASS_$_HTBacklightHostObserver
+ _OBJC_METACLASS_$_HTBacklightHostObserver
+ __OBJC_$_INSTANCE_METHODS_HTBacklightHostObserver
+ __OBJC_$_PROP_LIST_HTBacklightHostObserver
+ __OBJC_$_PROP_LIST_NSObject
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSObject
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_BLSBacklightStateObserving
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_NSObject
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BLSBacklightStateObserving
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSObject
+ __OBJC_$_PROTOCOL_REFS_BLSBacklightStateObserving
+ __OBJC_CLASS_PROTOCOLS_$_HTBacklightHostObserver
+ __OBJC_CLASS_RO_$_HTBacklightHostObserver
+ __OBJC_LABEL_PROTOCOL_$_BLSBacklightStateObserving
+ __OBJC_LABEL_PROTOCOL_$_NSObject
+ __OBJC_METACLASS_RO_$_HTBacklightHostObserver
+ __OBJC_PROTOCOL_$_BLSBacklightStateObserving
+ __OBJC_PROTOCOL_$_NSObject
+ ___71-[HTBacklightHostObserver backlight:didCompleteUpdateToState:forEvent:]_block_invoke
+ ___HTScreenOffAssertionQueue_block_invoke
+ ___HTTrackDisplayStateForMonitorComparison_block_invoke
+ ___HTTrackDisplayStateForMonitorComparison_block_invoke_2
+ ___HTTrackDisplayStateForMonitorComparison_block_invoke_3
+ ___block_descriptor_121_e8_32s40s_e8_v16?0q8ls32l8s40l8
+ ___block_descriptor_44_e19_"NSDictionary"8?0l
+ ___block_descriptor_44_e8_32bs_e5_v8?0ls32l8
+ ___block_descriptor_52_e19_"NSDictionary"8?0l
+ ___block_descriptor_64_e8_32bs_e5_v8?0ls32l8
+ __dyld_lazy_load
+ _dispatch_after
+ _dispatch_time
+ _gHTDisplayMonitorComparisonLock
+ _gHTScreenOffAssertion
+ _hasOpenScreenOffAssertionOverlappingHang
+ _kHTCAEventDisplayMonitorMissedState
+ _kHTCAEventDisplayMonitorNotifyLatency
+ _kHTCoreAnalyticsDisplayMonitorSource
+ _kHTCoreAnalyticsDisplayState
+ _kHTCoreAnalyticsNotifyLatencyMs
+ _kHTCoreAnalyticsTimeSinceDisplayChangeMs
+ _lazyLoadFlag$BacklightServices
+ _memcpy
- GCC_except_table41
- GCC_except_table43
- GCC_except_table45
- GCC_except_table48
- GCC_except_table53
- GCC_except_table64
- _HTIsDeviceRestricted
- ___block_descriptor_56_e19_"NSDictionary"8?0l
- _kHTAppActivationFailureReasonWatchdog_block_invoke.htAssertion
- _kHTAppActivationFailureReasonWatchdog_block_invoke.prevDisplayState
CStrings:
+ "BLS timestamp underflow detected (finalContinuousTime=%llu < timeDelta=%llu), using mach_absolute_time()"
+ "Hang detected: %.2fs (overlaps an open screen-off assertion; deferring classification %.0fms to recheck)"
+ "Hang detected: %.2fs (under capture threshold, emitting telemetry)"
+ "HangTracer SB: BLSBacklight host observer subscribed (sharedBacklight=%p initialState=%ld)"
+ "HangTracer SB: failed to subscribe legacy display comparison signal (notify status %u)"
+ "com.apple.hangtracer.display.comparison.notification"
+ "com.apple.hangtracer.display_monitor_missed_state"
+ "com.apple.hangtracer.display_monitor_notify_latency"
+ "com.apple.hangtracer.screenoffassertionqueue"
+ "display_state"
+ "monitor_source"
+ "notify_latency_ms"
+ "time_since_display_change_ms"
+ "v16@?0q8"
- "Display state changed %i -> %i"
- "HangTracer SB Screen State: Detected Screen ON -> OFF but an old HT Assertion still exists when we're about to create a new one"
- "com.apple.hangtracer.display.notification"
```
