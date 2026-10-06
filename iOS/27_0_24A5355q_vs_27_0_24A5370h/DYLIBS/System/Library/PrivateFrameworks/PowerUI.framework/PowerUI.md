## PowerUI

> `/System/Library/PrivateFrameworks/PowerUI.framework/PowerUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd82a0` | `0xd980c` | **`+0x156c`** |
| `__TEXT.__oslogstring` | `0xe8ba` | `0xf09d` | **`+0x7e3`** |
| `__AUTH_CONST.__objc_const` | `0x39d98` | `0x39f68` | **`+0x1d0`** |
| `__TEXT.__objc_methlist` | `0x1d57c` | `0x1d6d4` | **`+0x158`** |
| `__TEXT.__cstring` | `0xf634` | `0xf733` | **`+0xff`** |
| `__DATA_CONST.__objc_selrefs` | `0x5d50` | `0x5e40` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0xdaa0` | `0xdb60` | **`+0xc0`** |
| `__DATA.__data` | `0x728` | `0x788` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x1b80` | `0x1bd0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x16d8` | `0x1700` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x21d8` | `0x2200` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x5d0` | `0x5e8` | **`+0x18`** |
| `__DATA.__bss` | `0xe0` | `0xf8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x580` | `0x598` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x3ec0` | `0x3ecc` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x3d0` | `0x3d8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x98` | `0xa0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x398` | `0x3a0` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x10c4` | `0x10c0` | **`-0x4`** |

### Other Changes

```diff

-752.0.0.0.0
+753.0.5.0.0

+  - /System/Library/PrivateFrameworks/MicroLocation.framework/MicroLocation

-  Functions: 10613
-  Symbols:   15708
-  CStrings:  3168
+  Functions: 10641
+  Symbols:   15757
+  CStrings:  3200
Symbols:
+ +[PowerUISmartChargeUtilities bankBatteryProperties]
+ +[PowerUISmartChargeUtilities packBatteryProperties]
+ -[PowerUIDemoCECManager averageForecastRate:overInterval:]
+ -[PowerUILocationSignalMonitor clearMicrolocationCache]
+ -[PowerUILocationSignalMonitor ensureMicrolocationConnection]
+ -[PowerUILocationSignalMonitor handlePluginStatusChange]
+ -[PowerUILocationSignalMonitor handleStartupReconciliation]
+ -[PowerUILocationSignalMonitor isCurrentLocationAtKnownLOI]
+ -[PowerUILocationSignalMonitor isCurrentlyPluggedIn]
+ -[PowerUILocationSignalMonitor registerForPluginStatusChanges]
+ -[PowerUILocationSignalMonitor snapshotMicrolocationToCache]
+ -[PowerUIMicrolocationConnectionDelegate .cxx_destruct]
+ -[PowerUIMicrolocationConnectionDelegate connection:didFailWithError:]
+ -[PowerUIMicrolocationConnectionDelegate connectionDidUpdatePredictionContext:]
+ -[PowerUIMicrolocationConnectionDelegate firstPushSemaphore]
+ -[PowerUIMicrolocationConnectionDelegate hasReceivedFirstPush]
+ -[PowerUIMicrolocationConnectionDelegate initWithLog:]
+ -[PowerUIMicrolocationConnectionDelegate log]
+ -[PowerUIMicrolocationConnectionDelegate setFirstPushSemaphore:]
+ -[PowerUIMicrolocationConnectionDelegate setLog:]
+ -[PowerUIMicrolocationConnectionDelegate setReceivedFirstPush:]
+ GCC_except_table21
+ GCC_except_table60
+ GCC_except_table79
+ GCC_except_table85
+ GCC_except_table89
+ _OBJC_CLASS_$_PowerUIMicrolocationConnectionDelegate
+ _OBJC_CLASS_$_ULConfiguration
+ _OBJC_CLASS_$_ULConnection
+ _OBJC_IVAR_$_PowerUIMicrolocationConnectionDelegate._firstPushSemaphore
+ _OBJC_IVAR_$_PowerUIMicrolocationConnectionDelegate._log
+ _OBJC_IVAR_$_PowerUIMicrolocationConnectionDelegate._receivedFirstPush
+ _OBJC_METACLASS_$_PowerUIMicrolocationConnectionDelegate
+ _ULLocationTypeToString
+ _ULServiceStateToString
+ _ULServiceSuspendReasonToString
+ __OBJC_$_INSTANCE_METHODS_PowerUIMicrolocationConnectionDelegate
+ __OBJC_$_INSTANCE_VARIABLES_PowerUIMicrolocationConnectionDelegate
+ __OBJC_$_PROP_LIST_PowerUIMicrolocationConnectionDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_ULConnectionDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_ULConnectionDelegate
+ __OBJC_$_PROTOCOL_REFS_ULConnectionDelegate
+ __OBJC_CLASS_PROTOCOLS_$_PowerUIMicrolocationConnectionDelegate
+ __OBJC_CLASS_RO_$_PowerUIMicrolocationConnectionDelegate
+ __OBJC_LABEL_PROTOCOL_$_ULConnectionDelegate
+ __OBJC_METACLASS_RO_$_PowerUIMicrolocationConnectionDelegate
+ __OBJC_PROTOCOL_$_ULConnectionDelegate
+ ___58-[PowerUIDemoCECManager averageForecastRate:overInterval:]_block_invoke
+ ___61-[PowerUILocationSignalMonitor ensureMicrolocationConnection]_block_invoke
+ ___62-[PowerUILocationSignalMonitor registerForPluginStatusChanges]_block_invoke
+ ___62-[PowerUILocationSignalMonitor registerForPluginStatusChanges]_block_invoke_2
+ ___79-[PowerUILocationSignalMonitor initWithDelegate:trialManager:withContextStore:]_block_invoke
+ ___block_descriptor_40_e8_32w_e35_v24?0"NSString"8"NSDictionary"16lw32l8
+ ___block_descriptor_52_e8_32s_e19_"NSDictionary"8?0ls32l8
+ _ensureMicrolocationConnection.onceToken
+ _sMicrolocationConnection
+ _sMicrolocationDelegate
- GCC_except_table10
- GCC_except_table18
- GCC_except_table32
- GCC_except_table83
- GCC_except_table87
- ___44-[PowerUIDemoCECManager prevDayCECAnalytics]_block_invoke
- ___52-[PowerUILocationSignalMonitor inKnownMicrolocation]_block_invoke
- ___block_descriptor_64_e8_32s40r48r_e22_v16?0"BMStoreEvent"8lr40l8s32l8r48l8
CStrings:
+ "<nil>"
+ "Accumulated system load decreased over interval ending %@ (delta: %f mWs). Accumulator likely reset. Excluding this interval from SL emissions."
+ "Accumulated wall energy decreased over interval ending %@ (delta: %f uWh). Accumulator likely reset. Excluding this interval from WE emissions."
+ "AppleSmartBatteryBank"
+ "AppleSmartBatteryPack"
+ "Cached microlocation snapshot fresh (pluginDate=%@, isAtKnownLOI=%@)"
+ "Charging history arrays have mismatched lengths. Stored history corrupt; not computing analytics"
+ "Daemon starting unplugged; clearing any stale microlocation cache"
+ "Debug: forcing _authorizationStatus from %@ to kCLAuthorizationStatusDenied"
+ "Failed to create AppleSmartBatteryPack service"
+ "MiLo: ULConnection built and runWithConfiguration: invoked"
+ "MiLo: at known LOI, type=%@. loiUUID=%@ %{public}@"
+ "MiLo: building ULConnection with token %@"
+ "MiLo: connection unavailable (token may not be allowlisted)"
+ "MiLo: createServiceIdentifierForToken returned nil for token %@ (not allowlisted for this signing identity?)"
+ "MiLo: currentMap has no locationOfInterest (not at a known location). %{public}@"
+ "MiLo: locationOfInterestType is None. loiUUID=%@ %{public}@"
+ "MiLo: received first predictionContext push; SPI is now ready"
+ "MiLo: timed out waiting for first push; treating SPI as unavailable"
+ "MiLo: waiting up to %llds for first connectionDidUpdatePredictionContext push"
+ "MicroLocation connection failed: %@. SPI will be unavailable until daemon restart."
+ "Microlocation SPI unavailable; not updating cache"
+ "Microlocation cache cleared"
+ "Microlocation cache miss while plugged in; bootstrapping snapshot"
+ "Microlocation cache updated: isAtKnownLOI=%@, pluginDate=%@"
+ "Missing accumulator data for %lu of %lu entries (> %.0f%%). Emissions metrics are too incomplete; marking data invalid."
+ "Missing accumulator data for %lu of %lu entries; tolerating it (emissions slightly understated, day still considered valid)."
+ "No fresh microlocation cache available. Falling back to TimeZone check"
+ "Plug-in detected; snapshotting microlocation"
+ "Stored charging history is missing/extra keys or has mismatched array lengths. Resetting history to the current entry to avoid misaligned arrays"
+ "Unplug detected; clearing microlocation cache"
+ "com.apple.powerui.locationSignalMonitor"
+ "com.apple.powerui.locationSignalMonitor.denyAuth"
+ "com.apple.powerui.locationSignalMonitor.pluginChange"
+ "current timezone (%@) != previous timezone (%@) - plugin event (%@) "
+ "dischargeEndTTEPctError"
+ "isAtKnownLOI"
+ "last time prediciton at %@, trying to update at %@ (timegap=%.0fs, dSOC=%.2f)"
+ "pluginAtKnownMicrolocationCache"
+ "predictionTTEPctError"
+ "serviceState=%@ isMapValid=%@ suspendReasons=[%@]"
+ "skip evaluation event: invalid session data (sessionActive=%d, TTE=%.2f, paverage=%.2f, predPower=%.2f, initialTrueTTE=%.2f)"
+ "skip session update: timegap %.0fs < %.0fs AND dSOC %.2f < %.2f"
- "Error getting KML in signalMonitor: %s"
- "Failed to create IOPMPowerSource service"
- "Microlocation event near pluggedIn time"
- "Microlocation event near pluggedIn time %@"
- "No matching microlocation found"
- "No microlocations found. Falling back to TimeZone check"
- "One or more entries had invalid accum. data. Emissions metrics may be incomplete; marking data invalid."
- "dischargeEndTTE"
- "last time prediciton at %@, trying to update at %@"
- "timegapHr is less than kminMonitoringGap, skip session update"
- "working on event - plugin: %@ - event timestamp: %@ - diff: %f"
```
