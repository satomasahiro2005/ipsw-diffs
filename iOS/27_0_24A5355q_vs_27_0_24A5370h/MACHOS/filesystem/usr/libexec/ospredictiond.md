## ospredictiond

> `/usr/libexec/ospredictiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x65cec` | `0x66bb8` | **`+0xecc`** |
| `__TEXT.__oslogstring` | `0x6d52` | `0x717b` | **`+0x429`** |
| `__TEXT.__objc_methname` | `0x14d53` | `0x15177` | **`+0x424`** |
| `__TEXT.__objc_stubs` | `0x9440` | `0x97e0` | **`+0x3a0`** |
| `__DATA.__objc_const` | `0x10400` | `0x10600` | **`+0x200`** |
| `__TEXT.__objc_methlist` | `0x9158` | `0x92d0` | **`+0x178`** |
| `__TEXT.__cstring` | `0x5424` | `0x558f` | **`+0x16b`** |
| `__DATA_CONST.__cfstring` | `0x6160` | `0x62a0` | **`+0x140`** |
| `__DATA.__objc_selrefs` | `0x3bf0` | `0x3d10` | **`+0x120`** |
| `__TEXT.__objc_methtype` | `0x23b5` | `0x2456` | **`+0xa1`** |
| `__DATA.__data` | `0x720` | `0x780` | **`+0x60`** |
| `__DATA.__objc_data` | `0x2760` | `0x27b0` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x960` | `0x910` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x10f0` | `0x10b0` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x1448` | `0x1488` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0xdd8` | `0xe10` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x4c0` | `0x498` | **`-0x28`** |
| `__DATA.__bss` | `0x1c8` | `0x1e0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x410` | `0x428` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0xdac` | `0xdbc` | **`+0x10`** |
| `__TEXT.__const` | `0x448` | `0x458` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x3f0` | `0x3f8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x98` | `0xa0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x368` | `0x370` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x86c` | `0x868` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-269.0.0.0.0
+279.0.0.0.0

+  - /System/Library/PrivateFrameworks/MicroLocation.framework/MicroLocation

-  Functions: 3269
-  Symbols:   287
-  CStrings:  4689
+  Functions: 3299
+  Symbols:   285
+  CStrings:  4763
Symbols:
+ _OBJC_CLASS_$_ULConfiguration
+ _OBJC_CLASS_$_ULConnection
+ _OBJC_CLASS_$__OSIBLMitigation
+ _ULLocationTypeToString
+ _ULServiceStateToString
+ _ULServiceSuspendReasonToString
- _CFArrayGetCount
- _CFArrayGetTypeID
- _CFArrayGetValueAtIndex
- _CFDictionaryGetTypeID
- _CFDictionaryGetValue
- _CFGetTypeID
- _CFNumberGetTypeID
- _CFNumberGetValue
CStrings:
+ "%@: %u mW"
+ "%@_"
+ "%@_Battery0_%@"
+ "<nil>"
+ "@24@0:8r*16"
+ "AppleSmartBatteryBank"
+ "AppleSmartBatteryPack"
+ "Battery power consumption data not available for key %@"
+ "BatteryData not found on IOService '%{public}s'"
+ "CPMS snapshot timestamp (idx %@): %@"
+ "Cached microlocation snapshot fresh (pluginDate=%@, isAtKnownLOI=%@)"
+ "Daemon starting unplugged; clearing any stale microlocation cache"
+ "Extracting iPad thresholds from Trial Namespace %@"
+ "Failed to create properties for IOService '%{public}s'"
+ "Failed to find IOService '%{public}s'"
+ "Falling back to framework bundle: %{public}@"
+ "Loading iPad engage model from Trial: %{public}@"
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
+ "No fresh microlocation cache available. Falling back to TimeZone check"
+ "No snapshot timestamps available in CPMS control state snapshot"
+ "OSIMicrolocationConnectionDelegate"
+ "OutputPpFiltered (mW)"
+ "PMU10s"
+ "Plug-in detected; snapshotting microlocation"
+ "SnapshotTimestamp"
+ "System capability not available in Pmax state"
+ "T@\"NSObject<OS_dispatch_semaphore>\",&,N,V_firstPushSemaphore"
+ "TB,GhasReceivedFirstPush,V_receivedFirstPush"
+ "Triggering snapshot collection"
+ "ULConnectionDelegate"
+ "Unplug detected; clearing microlocation cache"
+ "_batteryDataForServiceName:"
+ "_firstPushSemaphore"
+ "_receivedFirstPush"
+ "absoluteBatteryLevel: AbsoluteCapacity not found or invalid in Pack BatteryData"
+ "absoluteBatteryLevel: Failed to get Bank BatteryData"
+ "absoluteBatteryLevel: Failed to get Pack BatteryData"
+ "absoluteBatteryLevel: Qmax array is empty or first element is not a number"
+ "absoluteBatteryLevel: Qmax has unexpected type"
+ "absoluteBatteryLevel: Qmax not found in Bank BatteryData"
+ "batteryBankBatteryData"
+ "batteryPackBatteryData"
+ "clearMicrolocationCache"
+ "collectAndPersistSnapshot: Failed to read Pack BatteryData — DesignCapacity will be 0"
+ "collectStaticTTEFeatures: Failed to read Bank BatteryData — WeightedRa will be 0"
+ "collectStaticTTEFeatures: Failed to read Pack BatteryData — DesignCapacity, NominalChargeCapacity will be 0"
+ "com.apple.osintelligence.debug.collectTelemetrySnapshot"
+ "com.apple.osintelligence.debug.socChangeCallback"
+ "com.apple.osintelligence.debug.testTTE"
+ "com.apple.osintelligence.locationMonitor"
+ "com.apple.osintelligence.locationMonitor.pluginChange"
+ "com.apple.system.game_mode_status_changed"
+ "componentsJoinedByString:"
+ "connection:didEnableMicrolocationAtCurrentLocationWithError:"
+ "connection:didFailWithError:"
+ "connection:didUpdatePrediction:"
+ "connection:didUpdateServiceStatus:"
+ "connectionDidUpdateMap:"
+ "connectionDidUpdatePredictionContext:"
+ "createServiceIdentifierForToken:"
+ "currentMap"
+ "ensureMicrolocationConnection"
+ "firstPushSemaphore"
+ "handlePluginStatusChange"
+ "handleStartupReconciliation"
+ "hasReceivedFirstPush"
+ "iPadChunkEngageDuration"
+ "iPadConfidenceThreshold"
+ "iPadInactivityEngageModel"
+ "iPadMaxChunksPerSession"
+ "initWithContextLayers:"
+ "initWithContextStore:"
+ "initWithDelegate:serviceIdentifier:"
+ "initWithLog:"
+ "isAtKnownLOI"
+ "isCurrentLocationAtKnownLOI"
+ "isCurrentlyPluggedIn"
+ "isMapValid"
+ "locationOfInterest"
+ "locationOfInterestType"
+ "locationOfInterestUUID"
+ "pluginAtKnownMicrolocationCache"
+ "receivedFirstPush"
+ "registerForPluginStatusChanges"
+ "runWithConfiguration:"
+ "serviceState"
+ "serviceState=%@ isMapValid=%@ suspendReasons=[%@]"
+ "serviceSuspendReasons"
+ "set"
+ "setFirstPushSemaphore:"
+ "setLevel:"
+ "setReceivedFirstPush:"
+ "snapshotMicrolocationToCache"
+ "substringFromIndex:"
+ "suspendReasonEnum"
+ "sysCap2_cpms (1s capability) via Pmax outputPpFiltered: %u mW"
+ "v24@0:8@\"ULConnection\"16"
+ "v32@0:8@\"ULConnection\"16@\"NSError\"24"
+ "v32@0:8@\"ULConnection\"16@\"ULPrediction\"24"
+ "v32@0:8@\"ULConnection\"16@\"ULServiceStatus\"24"
- "Battery power consumption data not available"
- "CPMS Pmax state check: error code = %d, state available = %@"
- "CPMS snapshot timestamp: %@"
- "CPMSPPMBatteryPowerConsumptionPMU10s: %u mW"
- "Error getting KML in signalMonitor: %s"
- "Extracting thresholds from Trial Namespace %@"
- "Loading iPad duration model from %{public}@"
- "Loading iPad engage model from %{public}@"
- "Location"
- "MicroLocationVisit"
- "Microlocation event near pluggedIn time"
- "Microlocation event near pluggedIn time %@"
- "No matching microlocation found"
- "No microlocations found. Falling back to TimeZone check"
- "OSIntelligence framework bundle not loaded, using hardcoded path"
- "System capability data not available"
- "absoluteBatteryLevel: AbsoluteCapacity is not a CFNumber"
- "absoluteBatteryLevel: AbsoluteCapacity not found"
- "absoluteBatteryLevel: BatteryData is not a CFDictionary"
- "absoluteBatteryLevel: BatteryData not found"
- "absoluteBatteryLevel: Failed to create properties dictionary"
- "absoluteBatteryLevel: Failed to get IOPMPowerSource"
- "absoluteBatteryLevel: First element of Qmax array is not a CFNumber"
- "absoluteBatteryLevel: Qmax array is empty"
- "absoluteBatteryLevel: Qmax has unexpected type (typeID=%ld)"
- "absoluteBatteryLevel: Qmax not found in BatteryData"
- "batteryPowerConsumption"
- "chunk_engage_duration"
- "com.apple.osintelligence.socChangeCallback"
- "com.apple.osintelligence.testTTE"
- "com.apple.system.console.mode.changed"
- "durationModel_iPad.mlmodelc"
- "engageModel_iPad.mlmodelc"
- "fileExistsAtPath:"
- "iPad duration model not found at %{public}@, falling back to Trial default"
- "iPad engage model not found at %{public}@, falling back to framework bundle at %{public}@"
- "max_chunks"
- "sysCap2_cpms (1s capability): %u mW"
- "systemCapability"
- "working on event - plugin: %@ - event timestamp: %@ - diff: %f"
```
