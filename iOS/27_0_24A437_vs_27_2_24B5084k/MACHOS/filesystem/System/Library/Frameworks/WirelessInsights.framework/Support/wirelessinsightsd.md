## wirelessinsightsd

> `/System/Library/Frameworks/WirelessInsights.framework/Support/wirelessinsightsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34ce54` | `0x34e6a0` | **`+0x184c`** |
| `__TEXT.__oslogstring` | `0x2eef2` | `0x2f242` | **`+0x350`** |
| `__TEXT.__gcc_except_tab` | `0x2a88c` | `0x2aae8` | **`+0x25c`** |
| `__TEXT.__cstring` | `0x1602b` | `0x161eb` | **`+0x1c0`** |
| `__DATA_CONST.__cfstring` | `0x74e0` | `0x75e0` | **`+0x100`** |
| `__DATA.__objc_const` | `0x14670` | `0x14720` | **`+0xb0`** |
| `__TEXT.__objc_methname` | `0x18b2c` | `0x18bac` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x17528` | `0x17570` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x10548` | `0x10580` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x5d73` | `0x5da3` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x7924` | `0x794c` | **`+0x28`** |
| `__DATA.__data` | `0x67a8` | `0x67c8` | **`+0x20`** |
| `__TEXT.__const` | `0x18113` | `0x18133` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xfc60` | `0xfc80` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x6c0` | `0x6d8` | **`+0x18`** |
| `__DATA_CONST.__objc_arrayobj` | `0x240` | `0x258` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x4160` | `0x4178` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x4588` | `0x4598` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x5000` | `0x4ff0` | **`-0x10`** |
| `__DATA.__common` | `0x610` | `0x618` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x2818` | `0x2810` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xa2c` | `0xa30` | **`+0x4`** |
| `__TEXT.__init_offsets` | `0x2b8` | `0x2bc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-350.1.0.0.0
+368.0.0.0.0

-  Functions: 14476
-  Symbols:   2063
-  CStrings:  10427
+  Functions: 14489
+  Symbols:   2062
+  CStrings:  10458
Symbols:
- __ZN3wis8asStringEj
CStrings:
+ "368"
+ "368~37"
+ "BatteryPacks"
+ "DeployedBandwidth"
+ "Failed to retrieve battery pack from packs"
+ "Failed to retrieve battery packs"
+ "Invalid sigLocationConfigs field (must be > 0): %@"
+ "NetworkCoverageMap"
+ "Pumping insight %s, config: AppID=%d (kWirelessInsights), PayloadType=%d (kDeviceConfig), size=%zu bytes"
+ "Queued the insight, %s"
+ "SatelliteCellClassifier"
+ "Sending Insights to Baseband: insight = %s"
+ "SigLocation outage criteria: oos rate %d in 0.01 percent, valid visit count %d, valid duration %lld sec"
+ "SigLocation skipping sigLocOutage cloud telemetry due to sig location exit"
+ "SigLocation[CoreData]:Attempting to clear persistent store (%s, %s)"
+ "SigLocation[CoreData]:Failed to destroy store (%s, %s): %s"
+ "SigLocation[CoreData]:No or invalid persistent store in coordinator, aborting (%s, %s)"
+ "SigLocation[CoreData]:Received notification that significant locations have been deleted, resetting database"
+ "SigLocation[CoreData]:Successfully destroyed store (%s, %s)"
+ "SigLocation[CoreData]:Unable to initialize FMCoreRoutineController, aborting"
+ "SigLocation[CoreData]:Unexpected number of stores in the coordinator: %lu"
+ "TestOne"
+ "UplinkAntennaPrediction"
+ "WISCOA:Cancel ApiRetyTimer before retry"
+ "WISCOA:Cancel ApiRetyTimer due to Registration status changed"
+ "WISCOA:Failed to create API retry timer"
+ "WISSigLocationMinimumValidDuration"
+ "WISSigLocationMinimumValidVisitCount"
+ "WISSigLocationOosRateThreshold"
+ "absoluteString"
+ "carrierName"
+ "carrierResourceLink"
+ "cellularVinylStaticInfo"
+ "intervalUntilPredictedStart"
+ "nil"
+ "profileConnectionDidReceiveAllowCloudSyncChangedNotification:userInfo:"
+ "registeredAt"
+ "sigLocationConfigs"
- "350.1"
- "350.1~193"
- "IOPMPowerSource"
- "Pumping insight config: AppID=%d (kWirelessInsights), PayloadType=%d (kDeviceConfig), size=%zu bytes"
- "Pumping the insight to Baseband"
- "Queued the insight"
- "Sending Insights to Baseband..."
```
