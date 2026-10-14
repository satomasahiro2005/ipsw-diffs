## AirPlaySender

> `/System/Library/PrivateFrameworks/AirPlaySender.framework/AirPlaySender`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x247e9c` | `0x24857c` | **`+0x6e0`** |
| `__TEXT.__cstring` | `0x8ff1c` | `0x901d6` | **`+0x2ba`** |
| `__AUTH_CONST.__cfstring` | `0x14a60` | `0x14aa0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x77c8` | `0x77e8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xb58` | `0xb78` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x23c0` | `0x23d0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x5980` | `0x5990` | **`+0x10`** |

### Other Changes

```diff

-1005.12.1.0.0
+1005.13.1.1.0

-  Functions: 11501
-  Symbols:   8711
-  CStrings:  11672
+  Functions: 11508
+  Symbols:   8721
+  CStrings:  11689
Symbols:
+ GCC_except_table129
+ _APSIsHomeAccessory
+ _OBJC_CLASS_$_CUSystemMonitor
+ ___endpoint_startPowerSourceMonitorIfNeeded_block_invoke
+ ___endpoint_startPowerSourceMonitorIfNeeded_block_invoke_2
+ ___endpoint_startPowerSourceMonitorIfNeeded_block_invoke_3
+ _airPlayDescription_isAppleHomeAccessory
+ _endpoint_startPowerSourceMonitorIfNeeded
+ _endpoint_stopPowerSourceMonitor
+ _endpoint_updateInactivityTimer
+ _kAPSDynamicLatencyManagerVariantIdentifier_B525
+ _kFigEndpointSubType_HomeAccessory
- GCC_except_table128
- _endpoint_startInactivityTimer
CStrings:
+ "1005.13.1.1"
+ "APEndpointInactivityTimeoutType endpoint_determineInactivityTimeoutBehavior(FigEndpointRef, FigEndpointFeatures, CFDictionaryRef)"
+ "AudioAccessory11"
+ "HomeAccessory"
+ "NoIdleTimeout activation option"
+ "P2POnly"
+ "P2POnlyOnBattery"
+ "[%{ptr}] Inactivity timeout type: %s%?{end} (%s)\n"
+ "[%{ptr}] Monitoring power source for inactivity timer\n"
+ "[%{ptr}] Power source changed: now on %s power\n"
+ "[%{ptr}] Power source monitor creation fail"
+ "[%{ptr}] Stopped monitoring power source\n"
+ "[%{ptr}] Using inactivity timeout? %s%?{end} (type: %s)\n"
+ "battery"
+ "no platform-specific policy"
+ "void endpoint_handlePowerSourceChanged(FigEndpointRef)"
+ "void endpoint_startPowerSourceMonitorIfNeeded(FigEndpointRef)"
+ "void endpoint_stopPowerSourceMonitor(FigEndpointRef)"
+ "void endpoint_updateInactivityTimer(FigEndpointRef, Boolean)"
+ "wall"
- "1005.12.1"
- "[%{ptr}] Using inactivity timeout? %d\n"
- "void endpoint_startInactivityTimer(FigEndpointRef)"
```
