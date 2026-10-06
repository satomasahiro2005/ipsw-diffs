## AccessorySetupDeveloperSettings

> `/System/Library/PreferenceBundles/AccessorySetupDeveloperSettings.bundle/AccessorySetupDeveloperSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x31314` | `0x4a95c` | **`+0x19648`** |
| `__TEXT.__swift5_typeref` | `0x24f2` | `0x4768` | **`+0x2276`** |
| `__TEXT.__const` | `0x1cf4` | `0x28f4` | **`+0xc00`** |
| `__DATA.__data` | `0x1640` | `0x2160` | **`+0xb20`** |
| `__DATA.__bss` | `0x1610` | `0x2030` | **`+0xa20`** |
| `__DATA_CONST.__const` | `0x1cd8` | `0x2548` | **`+0x870`** |
| `__TEXT.__constg_swiftt` | `0xda4` | `0x1300` | **`+0x55c`** |
| `__TEXT.__auth_stubs` | `0x1530` | `0x19c0` | **`+0x490`** |
| `__TEXT.__cstring` | `0xff4` | `0x1479` | **`+0x485`** |
| `__TEXT.__eh_frame` | `0x970` | `0xdd8` | **`+0x468`** |
| `__TEXT.__swift5_reflstr` | `0xde9` | `0x11b4` | **`+0x3cb`** |
| `__DATA.__objc_const` | `0xe00` | `0x1190` | **`+0x390`** |
| `__TEXT.__unwind_info` | `0x898` | `0xc20` | **`+0x388`** |
| `__TEXT.__oslogstring` | `0x1285` | `0x15d5` | **`+0x350`** |
| `__TEXT.__objc_methname` | `0x115f` | `0x146f` | **`+0x310`** |
| `__TEXT.__swift5_fieldmd` | `0xa94` | `0xd48` | **`+0x2b4`** |
| `__DATA_CONST.__auth_got` | `0xaa0` | `0xce8` | **`+0x248`** |
| `__TEXT.__swift5_capture` | `0x2b4` | `0x4c8` | **`+0x214`** |
| `__DATA.__objc_data` | `0x870` | `0x9f0` | **`+0x180`** |
| `__DATA_CONST.__got` | `0x3c8` | `0x4a8` | **`+0xe0`** |
| `__TEXT.__objc_stubs` | `0x660` | `0x720` | **`+0xc0`** |
| `__DATA_CONST.__auth_ptr` | `0x450` | `0x508` | **`+0xb8`** |
| `__TEXT.__swift5_assocty` | `0x180` | `0x1e0` | **`+0x60`** |
| `__TEXT.__swift5_proto` | `0xa4` | `0xf0` | **`+0x4c`** |
| `__TEXT.__objc_classname` | `0x33f` | `0x37f` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x328` | `0x358` | **`+0x30`** |
| `__TEXT.__swift5_types` | `0x78` | `0x98` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x6c` | `0x88` | **`+0x1c`** |
| `__DATA.__common` | `0x60` | `0x78` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x20` | `0x28` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x1c` | `0x24` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-2700.22.0.0.0
+2700.26.0.0.0

-  Functions: 803
-  Symbols:   197
-  CStrings:  420
+  Functions: 1154
+  Symbols:   205
+  CStrings:  484
Symbols:
+ _CBAdvertisementDataLocalNameKey
+ _OBJC_CLASS_$_NSISO8601DateFormatter
+ _OBJC_CLASS_$_UIColor
+ _objc_retain_x27
+ _objc_retain_x9
+ _swift_dynamicCastClass
+ _swift_makeBoxUnique
+ _swift_release_x12
+ _swift_retain_x4
- _swift_release_x10
CStrings:
+ " samples (minimum "
+ "Analysis results saved to: %{public}s"
+ "Attempted advertiserTest scan but enableHomekitSetupTesting is false. Aborting."
+ "Clear Data & Continue"
+ "Confirm Selection"
+ "Defaults read — enableHomekitSetupTesting: %{bool}d, HomeKitScanMode: %{public}s, HomeKitTargetSamplesPerChannel raw: %{public}s"
+ "Device picker scan failed: Bluetooth not powered on."
+ "Device picker scan started (timeout: %fs)."
+ "Device picker scan stopped."
+ "Discovered Proximity Pairing Data: %{public}s ch:%ld rssi:%ld txPower:%ld pathLoss:%ld"
+ "Enter threshold hex values (e.g. 0xD3) to run the live test directly without completing data collection."
+ "Error when failed to save analysis results"
+ "Failed to encode analysis result: %s"
+ "Failed to write analysis result file: %s"
+ "Filtering out peripheral %s — not target %s"
+ "Global RSSI spread ("
+ "HomeKit scan mode: %{public}s. Per-channel target: %ld."
+ "HomeKitAdvertiserTestCount"
+ "HomeKitAdvertiserTestTime"
+ "HomeKitFilterSingleDevice"
+ "HomeKitMaxRssiSpread"
+ "HomeKitRssiSpreadPerChannelOnly"
+ "HomeKitScanTimeoutOverride"
+ "HomeKitTargetSamplesPerChannel"
+ "Samples contained invalid channels (expected 37, 38, 39 only)."
+ "Scanning for FE25 devices…"
+ "Skipping global RSSI spread check (HomeKitRssiSpreadPerChannelOnly is set)."
+ "Start New Data Collection?"
+ "Suggested (25cm/1m)"
+ "Suggested RSSI Threshold"
+ "Test ended unexpectedly."
+ "The target device filter has changed since data collection started. Continuing will clear all existing measurements."
+ "Use Result Thresholds"
+ "Verify accessory advertisements by placing scanning phone and accessory in shield box/chamber at 5cm apart and start test. Do not move devices after pressing 'Start' until after the test has finished."
+ "Warning: Failed to save analysis results: %{public}s. The threshold calculation is still valid."
+ "_TtC31AccessorySetupDeveloperSettings23AdvertiserTestViewModel"
+ "_discoveredPeripherals"
+ "_isPickingDevice"
+ "_manualImmediateHex"
+ "_manualSuperImmediateHex"
+ "_manualVicinityHex"
+ "_navigateToDistanceID"
+ "_selectedPeripheral"
+ "_showingDeviceChangeAlert"
+ "_testResult"
+ "advertiserTestTargetCount"
+ "analysis.superImmediateThreshold"
+ "analysisError.failedToSave"
+ "collectionDeviceID"
+ "discoveredPeripheralsDict"
+ "discoveryContinuation"
+ "discoveryTask"
+ "integerForKey:"
+ "isFilterSingleDevice"
+ "isPerChannelMode"
+ "objectForKey:"
+ "pendingDistanceID"
+ "perChannelCounts"
+ "rssiSpreadPerChannelOnly"
+ "scanTimeoutOverride"
+ "setFormatOptions:"
+ "setLocale:"
+ "stringForKey:"
+ "targetPeripheralID"
+ "targetSamplesPerChannel"
+ "tertiaryLabelColor"
- "Discovered Proximity Pairing Data: %{public}s"
- "Suggested (20cm/1m)"
```
