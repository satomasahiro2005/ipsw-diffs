## ndoagent

> `/System/Library/PrivateFrameworks/NewDeviceOutreach.framework/ndoagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7a98c` | `0x79584` | **`-0x1408`** |
| `__DATA.__objc_const` | `0x33e0` | `0x3088` | **`-0x358`** |
| `__DATA_CONST.__const` | `0x41b8` | `0x3fe0` | **`-0x1d8`** |
| `__TEXT.__const` | `0x8618` | `0x84f8` | **`-0x120`** |
| `__TEXT.__cstring` | `0x1f80` | `0x2070` | **`+0xf0`** |
| `__DATA.__data` | `0x2148` | `0x2088` | **`-0xc0`** |
| `__TEXT.__oslogstring` | `0x2efb` | `0x2e5b` | **`-0xa0`** |
| `__TEXT.__eh_frame` | `0x2318` | `0x2288` | **`-0x90`** |
| `__TEXT.__objc_methname` | `0x29d3` | `0x2a5f` | **`+0x8c`** |
| `__TEXT.__swift5_typeref` | `0x1810` | `0x1792` | **`-0x7e`** |
| `__TEXT.__swift5_fieldmd` | `0x1308` | `0x1294` | **`-0x74`** |
| `__DATA_CONST.__cfstring` | `0xf80` | `0xfe0` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x8e4` | `0x888` | **`-0x5c`** |
| `__TEXT.__constg_swiftt` | `0xfe4` | `0xf98` | **`-0x4c`** |
| `__TEXT.__unwind_info` | `0x1d40` | `0x1cf8` | **`-0x48`** |
| `__TEXT.__auth_stubs` | `0x2d50` | `0x2d80` | **`+0x30`** |
| `__TEXT.__swift5_builtin` | `0x8c` | `0x64` | **`-0x28`** |
| `__TEXT.__objc_methtype` | `0x932` | `0x912` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x6e0` | `0x6c0` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x16b8` | `0x16d0` | **`+0x18`** |
| `__DATA.__bss` | `0xb550` | `0xb560` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0x492` | `0x482` | **`-0x10`** |
| `__TEXT.__swift5_mpenum` | `0x3c` | `0x2c` | **`-0x10`** |
| `__DATA_CONST.__got` | `0xbb8` | `0xbc0` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xdc` | `0xe4` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x194` | `0x18c` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0xb4` | `0xac` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x7c` | `0x74` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x90` | `0x8c` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-624.0.4.0.0
+624.0.13.0.0

-  Functions: 2547
-  Symbols:   1231
-  CStrings:  1044
+  Functions: 2508
+  Symbols:   1235
+  CStrings:  1050
Symbols:
+ _$s10Foundation4DateV3nowACvgZ
+ __dispatch_source_type_timer
+ _dispatch_activate
+ _dispatch_source_cancel
+ _dispatch_source_create
+ _dispatch_source_set_event_handler
+ _dispatch_source_set_timer
+ _dispatch_time
- _$sScS12ContinuationV13onTerminationyAB0C0Oyx__GYbcSgvs
- _$sScSMa
- _$sScS_15bufferingPolicy_ScSyxGxm_ScS12ContinuationV09BufferingB0Oyx__GyADyx_GXEtcfC
- _$ss10_HashTableV12previousHole6beforeAB6BucketVAF_tF
CStrings:
+ "%s Apple audio device: %{private}s"
+ "%s Enumeration complete, %ld Apple accessory device(s) found"
+ "%s.%s: %s"
+ "%s.%s: starting loadWarranty for serial %{private}s"
+ "%s: loadWarranty completed with %{private}s"
+ "Clearing cache before check-in (--no-cache)"
+ "Dismissing all follow-up items"
+ "Hardware keyboard availability changed — scheduling debounced check-in"
+ "Internal command action result: %s"
+ "Internal command check-in failed: %@"
+ "Internal command check-in succeeded. Actions: %ld"
+ "Keyboard debounce timer fired — triggering check-in"
+ "Triggering immediate check-in with trigger: %s"
+ "com.apple.ndoagent.keyboardDebounce"
+ "com.apple.ndoagent.pairingFilter"
+ "dismissAllFollowUps"
+ "enumeratePairedAccessories()"
+ "getCoverageInfoForSerialNumber: received XPC request for serial %{private}@ with policy %lu"
+ "getCoverageInfoForSerialNumber: warranty fetch completed for serial %{private}@ (data=%@, error=%{private}@)"
+ "hasKnownAppleAccessories()"
+ "maybeCheckInAfterBluetoothPairingDetection(_:)"
+ "maybeCheckInAfterBluetoothPairingDetectionWithHandler:"
+ "ndoagent/NDOAgentSwiftHelpers.swift"
+ "ndoagent/NDODevicePairingFilter.swift"
+ "ndoagent/NDOWarrantyPropertiesLoader.swift"
+ "nil"
+ "non-nil"
+ "none"
- "%s Apple audio device found: %{private}s serial=%{private}s"
- "%s Apple audio device lost: %{private}s"
- "%s Apple audio device unpaired, triggering check-in"
- "%s CBDiscovery activation failed: %s"
- "%s CBDiscovery active"
- "%s Device already known, skipping check-in"
- "%s Device found with no identifier, skipping"
- "%s Device lost with no identifier, skipping"
- "%s Device was not tracked, skipping check-in"
- "%s Event stream ended"
- "%s Initial enumeration complete, %ld Apple audio device(s) known"
- "%s New Apple audio device paired, triggering check-in"
- "%s Still enumerating existing devices, skipping check-in"
- "%s Still enumerating, skipping check-in for lost device"
- "%s.%s DeviceEvent continuation terminated. Invalidating CBDiscovery"
- "%s.%s Found device is not an Apple audio accessory, skipping"
- "%s.%s Lost device is not an Apple audio accessory, skipping"
- "Hardware keyboard availability changed — triggering check-in"
- "activateDiscovery()"
- "com.apple.ndoagent.pairingMonitor"
- "ndoagent/NDOPairingMonitor.swift"
- "startAccessoryPairingObserverWithCheckInHandler:"
```
