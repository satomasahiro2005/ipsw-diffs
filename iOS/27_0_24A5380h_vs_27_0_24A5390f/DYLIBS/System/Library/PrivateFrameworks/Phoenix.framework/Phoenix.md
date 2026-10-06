## Phoenix

> `/System/Library/PrivateFrameworks/Phoenix.framework/Phoenix`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x3a70` | `0x3b10` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x249f` | `0x242d` | **`-0x72`** |
| `__DATA.__data` | `0x548` | `0x5a8` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x1d5c` | `0x1dac` | **`+0x50`** |
| `__TEXT.__text` | `0x22b94` | `0x22bd4` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1340` | `0x1370` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x1ecb` | `0x1eaf` | **`-0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x348` | `0x330` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x2e8` | `0x2f8` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x70` | `0x78` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x8a8` | `0x8b0` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x150` | `0x14c` | **`-0x4`** |

### Other Changes

```diff

-3234.5.0.0.0
+3237.1.0.0.0

+  - /System/Library/PrivateFrameworks/BacklightServices.framework/BacklightServices

-  Functions: 622
-  Symbols:   1369
-  CStrings:  465
+  Functions: 624
+  Symbols:   1376
+  CStrings:  461
Symbols:
+ -[AXPhoenixDisplayStatusMonitor _startObservingAggregateBacklight]
+ -[AXPhoenixDisplayStatusMonitor _stopObservingAggregateBacklight]
+ -[AXPhoenixDisplayStatusMonitor aggregateBacklight]
+ -[AXPhoenixDisplayStatusMonitor backlight:didCompleteUpdateToState:forEvent:]
+ -[AXPhoenixDisplayStatusMonitor setAggregateBacklight:]
+ GCC_except_table479
+ GCC_except_table539
+ _BLSBacklightStateIsActive
+ _NSStringFromBLSBacklightState
+ _OBJC_CLASS_$_BLSBacklight
+ _OBJC_CLASS_$_BLSDisplayReference
+ _OBJC_IVAR_$_AXPhoenixDisplayStatusMonitor._aggregateBacklight
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_BLSBacklightStateObserving
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BLSBacklightStateObserving
+ __OBJC_$_PROTOCOL_REFS_BLSBacklightStateObserving
+ __OBJC_CLASS_PROTOCOLS_$_AXPhoenixDisplayStatusMonitor
+ __OBJC_LABEL_PROTOCOL_$_BLSBacklightStateObserving
+ __OBJC_PROTOCOL_$_BLSBacklightStateObserving
+ ___77-[AXPhoenixDisplayStatusMonitor backlight:didCompleteUpdateToState:forEvent:]_block_invoke
+ ___block_descriptor_48_e8_32w_e5_v8?0lw32l8
+ ___os_log_helper_16_2_3_8_32_8_66_8_66
+ ___os_log_helper_16_2_4_8_32_8_66_8_66_8_66
- -[AXPhoenixDisplayStatusMonitor _queryIsDisplayOn]
- -[AXPhoenixDisplayStatusMonitor _registerForSpringboardNotificationsWithQueue:]
- -[AXPhoenixDisplayStatusMonitor _unregisterForSpringboardNotifications]
- -[AXPhoenixDisplayStatusMonitor notifyToken]
- -[AXPhoenixDisplayStatusMonitor setNotifyToken:]
- GCC_except_table481
- GCC_except_table537
- _OBJC_IVAR_$_AXPhoenixDisplayStatusMonitor._notifyToken
- ___79-[AXPhoenixDisplayStatusMonitor _registerForSpringboardNotificationsWithQueue:]_block_invoke
- ___block_descriptor_40_e8_32w_e8_v12?0i8lw32l8
- _notify_cancel
- _notify_get_state
- _notify_is_valid_token
- _notify_register_dispatch
- _objc_retainBlock
CStrings:
+ "-[AXPhoenixDisplayStatusMonitor _startObservingAggregateBacklight]"
+ "-[AXPhoenixDisplayStatusMonitor backlight:didCompleteUpdateToState:forEvent:]_block_invoke"
+ "[PHOENIX] %s Aggregate backlight update, state=%{public}@ -> display %{public}@ (was %{public}@)"
+ "[PHOENIX] %s Observing aggregate backlight, initial state=%{public}@ -> display %{public}@"
- "-[AXPhoenixDisplayStatusMonitor _queryIsDisplayOn]"
- "-[AXPhoenixDisplayStatusMonitor _registerForSpringboardNotificationsWithQueue:]"
- "-[AXPhoenixDisplayStatusMonitor _registerForSpringboardNotificationsWithQueue:]_block_invoke"
- "[PHOENIX] %s Display status ambiguous: notify_get_state status %@ != NOTIFY_STATUS_OK and state == %@"
- "[PHOENIX] %s Fail to register for screen state change"
- "[PHOENIX] %s notify_get_state status %@ != NOTITY_STATUS_OK"
- "com.apple.springboard.hasBlankedScreen"
- "v12@?0i8"
```
