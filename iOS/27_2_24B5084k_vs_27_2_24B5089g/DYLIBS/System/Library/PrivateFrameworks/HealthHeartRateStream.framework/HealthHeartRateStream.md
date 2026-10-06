## HealthHeartRateStream

> `/System/Library/PrivateFrameworks/HealthHeartRateStream.framework/HealthHeartRateStream`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5eb14` | `0x60ddc` | **`+0x22c8`** |
| `__DATA_DIRTY.__data` | `—` | `0xee0` | **`+0xee0`** |
| `__AUTH.__data` | `0x1c18` | `0x1188` | **`-0xa90`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x5f0` | **`+0x5f0`** |
| `__AUTH.__objc_data` | `0x898` | `0x2b8` | **`-0x5e0`** |
| `__DATA.__data` | `0x12d8` | `0xee8` | **`-0x3f0`** |
| `__DATA_DIRTY.__bss` | `—` | `0x380` | **`+0x380`** |
| `__DATA.__bss` | `0x2430` | `0x2190` | **`-0x2a0`** |
| `__TEXT.__oslogstring` | `0x2084` | `0x2324` | **`+0x2a0`** |
| `__AUTH_CONST.__const` | `0x3500` | `0x3690` | **`+0x190`** |
| `__TEXT.__eh_frame` | `0x2504` | `0x263c` | **`+0x138`** |
| `__TEXT.__cstring` | `0xaa2` | `0xb22` | **`+0x80`** |
| `__TEXT.__const` | `0x3850` | `0x38c0` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x1262` | `0x12ca` | **`+0x68`** |
| `__TEXT.__swift5_fieldmd` | `0x15b0` | `0x1614` | **`+0x64`** |
| `__AUTH_CONST.__objc_const` | `0x2648` | `0x26a8` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x720` | `0x770` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x150a` | `0x154a` | **`+0x40`** |
| `__DATA.__common` | `0x50` | `0x18` | **`-0x38`** |
| `__DATA_DIRTY.__common` | `—` | `0x38` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x19c0` | `0x19f4` | **`+0x34`** |
| `__TEXT.__unwind_info` | `0x1b68` | `0x1b98` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0xa68` | `0xa78` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x2d0` | `0x2e0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x338` | `0x340` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x330` | `0x338` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1d8` | `0x1e0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x174` | `0x178` | **`+0x4`** |

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

-  Functions: 2419
-  Symbols:   824
-  CStrings:  189
+  Functions: 2459
+  Symbols:   832
+  CStrings:  193
Symbols:
+ ___swift_closure_destructor.12Tm
+ _associated conformance 21HealthHeartRateStream17MockRapportClientC12RegistrationOSHAASQ
+ _swift_getFunctionTypeMetadata0
+ _symbolic So11PDRRegistryC
+ _symbolic _____ 21HealthHeartRateStream17MockRapportClientC12RegistrationO
+ _symbolic _____ySaySSGSgG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____ySay_____GG 15Synchronization5MutexVAARi_zrlE 21HealthHeartRateStream17MockRapportDeviceC
+ _symbolic _____yShy_____GG 15Synchronization5MutexVAARi_zrlE 21HealthHeartRateStream17MockRapportClientC12RegistrationO
+ _symbolic _____ySiG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____y_____SgG 15Synchronization5MutexVAARi_zrlE So14RPControlFlagsV
+ _symbolic _____yyyYbcSgG 15Synchronization5MutexVAARi_zrlE
+ _symbolic ytIeghr_
- ___swift_assign_boxed_opaque_existential_1
- ___swift_closure_destructor.15Tm
- _symbolic Say_____G 21HealthHeartRateStream17MockRapportDeviceC
- _symbolic _____ySDySS______pGG 15Synchronization5MutexVAARi_zrlE 21HealthHeartRateStream22RapportDeviceInterfaceP
CStrings:
+ "HealthHeartRateStream.RegistryPairedWatchMonitor"
+ "Rapport interrupted; snapshot now"
+ "Rapport snapshot:"
+ "RemoteHeartRateStreamListener with identifier %s received filtered heart rate: { timestamp: %{public}s, bpm: %{private}f, confidence: %{public}s, deviceType: %{public}s }"
+ "RemoteHeartRateStreamListener with identifier %s received unfiltered heart rate: { timestamp: %{public}s, bpm: %{private}f, confidence: %{public}s, deviceType: %{public}s }"
+ "[%{public}s] Received handleFilteredHeartRate { timestamp: %{public}s, bpm: %{private}f, confidence: %{public}s, deviceType: %{public}s }"
+ "[%{public}s] Received handleOneSecondStreamingHeartRate { timestamp: %{public}s, bpm: %{private}f, confidence: %{public}s, deviceType: %{public}s }"
+ "[%{public}s] sessionId %s Received filtered heart rate: { timestamp: %{public}s, bpm: %{private}f, confidence: %{public}s, deviceType: %{public}s }"
+ "[%{public}s] sessionId %s Received request %{public}s with keys: %{public}s."
+ "[%{public}s] sessionId %s Received unfiltered heart rate: { timestamp: %{public}s, bpm: %{private}f, confidence: %{public}s, deviceType: %{public}s }"
+ "[HeartRateDeviceProvider-AirPods] Received device: %{private}s"
+ "[HeartRateDeviceProvider-AudioAccessory] Active HRM device at activation: %{private}s"
+ "[HeartRateDeviceProvider-AudioAccessory] Received device: %{private}s from AASystemStateMonitor - aaActiveHRMDeviceChangedHandler"
+ "[HeartRateDeviceProvider-BLE] HRCBluetoothLESourceObserverDelegate: Device list received. Devices: %{private}s"
+ "[HeartRateDeviceProvider-Discovery] %{public}s %ld watch(es) — %{private}s"
+ "[HeartRateDeviceProvider] %{public}s devices updated: %ld device(s) - %{private}s"
+ "[HeartRateDeviceProvider] Apple Watch change detected, active device: %{private}s"
- "RemoteHeartRateStreamListener with identifier %s received filtered heart rate: %s."
- "RemoteHeartRateStreamListener with identifier %s received unfiltered heart rate: %s."
- "[%{public}s] Received handleFilteredHeartRate %@."
- "[%{public}s] Received handleOneSecondStreamingHeartRate %@."
- "[%{public}s] sessionId %s Received filtered heart rate: %s."
- "[%{public}s] sessionId %s Received request requestDictionary: %s."
- "[%{public}s] sessionId %s Received unfiltered heart rate: %s."
- "[HeartRateDeviceProvider-AirPods] Received device: %s"
- "[HeartRateDeviceProvider-AudioAccessory] Active HRM device at activation: %s"
- "[HeartRateDeviceProvider-AudioAccessory] Received device: %s from AASystemStateMonitor - aaActiveHRMDeviceChangedHandler"
- "[HeartRateDeviceProvider-BLE] HRCBluetoothLESourceObserverDelegate: Device list received. Devices: %s"
- "[HeartRateDeviceProvider] %s devices updated: %ld device(s) - %s"
- "[HeartRateDeviceProvider] Apple Watch change detected, active device: %s"
```
