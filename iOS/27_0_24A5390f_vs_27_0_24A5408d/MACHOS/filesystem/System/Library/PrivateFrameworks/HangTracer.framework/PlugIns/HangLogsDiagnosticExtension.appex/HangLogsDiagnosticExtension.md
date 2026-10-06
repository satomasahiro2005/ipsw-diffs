## HangLogsDiagnosticExtension

> `/System/Library/PrivateFrameworks/HangTracer.framework/PlugIns/HangLogsDiagnosticExtension.appex/HangLogsDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x133b0` | `0x14a70` | **`+0x16c0`** |
| `__TEXT.__oslogstring` | `0x1cb8` | `0x2145` | **`+0x48d`** |
| `__TEXT.__objc_methname` | `0x447c` | `0x46b9` | **`+0x23d`** |
| `__DATA.__objc_const` | `0x1fa8` | `0x21c8` | **`+0x220`** |
| `__TEXT.__objc_methtype` | `0x852` | `0xa29` | **`+0x1d7`** |
| `__TEXT.__objc_methlist` | `0xbbc` | `0xd2c` | **`+0x170`** |
| `__TEXT.__cstring` | `0x26e5` | `0x281c` | **`+0x137`** |
| `__DATA.__data` | `0x10c` | `0x204` | **`+0xf8`** |
| `__DATA_CONST.__const` | `0xd58` | `0xe48` | **`+0xf0`** |
| `__DATA_CONST.__cfstring` | `0x2680` | `0x2760` | **`+0xe0`** |
| `__DATA.__objc_selrefs` | `0xbe8` | `0xcc0` | **`+0xd8`** |
| `__TEXT.__auth_stubs` | `0xa30` | `0xab0` | **`+0x80`** |
| `__DATA.__bss` | `0xf0` | `0x150` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x1cc0` | `0x1d20` | **`+0x60`** |
| `__DATA.__objc_data` | `0x2d0` | `0x320` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x400` | `0x448` | **`+0x48`** |
| `__DATA_CONST.__auth_got` | `0x528` | `0x568` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0xa2` | `0xde` | **`+0x3c`** |
| `__TEXT.__const` | `0x260` | `0x280` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `—` | `0x10` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x50` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-424.0.0.0.0
+426.0.0.0.0

-  Functions: 456
-  Symbols:   478
-  CStrings:  1206
+  Functions: 484
+  Symbols:   503
+  CStrings:  1284
Symbols:
+ _HTEndNonResponsiveTaskAtTime
+ _MCTU_TO_MS
+ _OBJC_CLASS_$_HTBacklightHostObserver
+ _OBJC_METACLASS_$_HTBacklightHostObserver
+ __dyld_lazy_load
+ _assertionSignpost
+ _dispatch_after
+ _dispatch_time
+ _getEventFromPid
+ _getTimeBetweenAbsoluteAndContinuousTime
+ _getpid
+ _hasOpenScreenOffAssertionOverlappingHang
+ _kHTCAEventDisplayMonitorMissedState
+ _kHTCAEventDisplayMonitorNotifyLatency
+ _kHTCoreAnalyticsDisplayMonitorSource
+ _kHTCoreAnalyticsDisplayState
+ _kHTCoreAnalyticsNotifyLatencyMs
+ _kHTCoreAnalyticsTimeSinceDisplayChangeMs
+ _kHTScreenOffAssertionName
+ _legacySignpost
+ _mach_continuous_time
+ _memcpy
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _strncpy
CStrings:
+ "#16@0:8"
+ "%{public, signpost.description:end_time}llu missedTimeout=%{public, signpost.telemetry:number2}i"
+ "@\"NSString\"16@0:8"
+ "@24@0:8:16"
+ "@32@0:8:16@24"
+ "@40@0:8:16@24@32"
+ "B24@0:8#16"
+ "B24@0:8:16"
+ "B24@0:8@\"Protocol\"16"
+ "B24@0:8@16"
+ "BLS timestamp underflow detected (finalContinuousTime=%llu < timeDelta=%llu), using mach_absolute_time()"
+ "BLSBacklightStateObserving"
+ "HTAssertion: HTBeginAssertion: track assertionId=%llu assertionname=(%s) starttime=%llu expirationTime=%llu"
+ "HTAssertion: desired timeout (%f) is greater than max allowed timeout (%f), using max allowed timeout"
+ "HTAssertions: HTEndAssertion: assertionId not found in recent array"
+ "HTAssertions: HTEndAssertion: assertionId=%llu assertionname=(%s) missed timeout (endTime was %fms after timeout)!"
+ "HTAssertions: HTEndAssertion: update assertionId=%llu assertionname=(%s) endTime is now=%llu"
+ "HTAssertions: HTEndAssertion:assertionCounter is 0"
+ "HTBacklightHostObserver"
+ "HTNonResponsiveTaskAssertion"
+ "Hang detected: %.2fs (overlaps an open screen-off assertion; deferring classification %.0fms to recheck)"
+ "Hang detected: %.2fs (under capture threshold, emitting telemetry)"
+ "NSObject"
+ "T#,R"
+ "T@\"NSString\",?,R,C"
+ "T@\"NSString\",R,C"
+ "TQ,R"
+ "Vv16@0:8"
+ "^{_NSZone=}16@0:8"
+ "autorelease"
+ "backlight:activatingWithEvent:"
+ "backlight:deactivatingWithEvent:"
+ "backlight:didChangeAlwaysOnEnabled:"
+ "backlight:didCompleteUpdateToState:forEvent:"
+ "backlight:didCompleteUpdateToState:forEvents:abortedEvents:"
+ "backlight:performingEvent:"
+ "changeRequest"
+ "class"
+ "com.apple.hangtracer.display_monitor_missed_state"
+ "com.apple.hangtracer.display_monitor_notify_latency"
+ "com.apple.hangtracer.screenoffassertionqueue"
+ "com.apple.springboard"
+ "conformsToProtocol:"
+ "debugDescription"
+ "display_state"
+ "hash"
+ "isKindOfClass:"
+ "isMemberOfClass:"
+ "isProxy"
+ "missedTimeout=%{public, signpost.telemetry:number2}i"
+ "monitor_source"
+ "name=%s timeout=%f screenOffAssertion=%{BOOL}i noTimeout=%{BOOL}i"
+ "name=%{public, signpost.description:attribute}s appliedTimeoutSecs=%{public, signpost.telemetry:number1}f"
+ "non_responsive_assertion"
+ "notify_latency_ms"
+ "numberWithInteger:"
+ "performSelector:"
+ "performSelector:withObject:"
+ "performSelector:withObject:withObject:"
+ "release"
+ "respondsToSelector:"
+ "retain"
+ "retainCount"
+ "self"
+ "signpost_hang"
+ "superclass"
+ "system_screen_off"
+ "time_since_display_change_ms"
+ "v16@?0q8"
+ "v28@0:8@\"<BLSBacklightStateObservable>\"16B24"
+ "v28@0:8@16B24"
+ "v32@0:8@\"<BLSBacklightStateObservable>\"16@\"BLSBacklightChangeEvent\"24"
+ "v32@0:8@16@24"
+ "v40@0:8@\"<BLSBacklightStateObservable>\"16q24@\"BLSBacklightChangeEvent\"32"
+ "v40@0:8@16q24@32"
+ "v48@0:8@\"<BLSBacklightStateObservable>\"16q24@\"NSArray\"32@\"NSArray\"40"
+ "v48@0:8@16q24@32@40"
+ "zone"
```
