## dasd

> `/usr/libexec/dasd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x175bc4` | `0x1779b8` | **`+0x1df4`** |
| `__TEXT.__objc_methname` | `0x2e0ad` | `0x2e49d` | **`+0x3f0`** |
| `__DATA.__objc_const` | `0x33c08` | `0x33ed8` | **`+0x2d0`** |
| `__TEXT.__oslogstring` | `0x16949` | `0x16be9` | **`+0x2a0`** |
| `__DATA_CONST.__cfstring` | `0x11740` | `0x118e0` | **`+0x1a0`** |
| `__TEXT.__objc_stubs` | `0x1ade0` | `0x1af80` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x103d6` | `0x10566` | **`+0x190`** |
| `__TEXT.__objc_methlist` | `0x13024` | `0x131b4` | **`+0x190`** |
| `__TEXT.__gcc_except_tab` | `0x4ecc` | `0x4f78` | **`+0xac`** |
| `__DATA.__objc_selrefs` | `0x9c28` | `0x9cc0` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x4ff0` | `0x5050` | **`+0x60`** |
| `__DATA.__objc_data` | `0x48b8` | `0x4908` | **`+0x50`** |
| `__DATA.__objc_ivar` | `0x1608` | `0x1630` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x4ed8` | `0x4f00` | **`+0x28`** |
| `__DATA_CONST.__objc_dictobj` | `0x230` | `0x208` | **`-0x28`** |
| `__TEXT.__auth_stubs` | `0x2210` | `0x2230` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x1c88` | `0x1ca8` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x41a1` | `0x41c1` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xe20` | `0xe38` | **`+0x18`** |
| `__DATA.__bss` | `0x1240` | `0x1250` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1118` | `0x1128` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x480` | `0x470` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x700` | `0x708` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x5b8` | `0x5c0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
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

-2467.0.23.502.1
+2467.2.1.0.0

-  Functions: 8302
-  Symbols:   1010
-  CStrings:  12387
+  Functions: 8343
+  Symbols:   1014
+  CStrings:  12437
Symbols:
+ _BMDeviceKeybagLockedIdentifier
+ _IOObjectRelease
+ _NSFileHandleOperationException
+ _objc_exception_rethrow
CStrings:
+ "%@::DeviceNotIdle"
+ "%@::UserAbsentWithDisplay"
+ "/device/keybagLocked"
+ "@\"_CDContextualChangeRegistration\""
+ "Device Active"
+ "Getting distinct PPSTimeSeries for subsystem: %@ category: %@ with valueFilter: %@ & metrics: %@ & timeFilter:%@"
+ "RequiredMinimumBatteryLevel"
+ "T@\"MLModel\",&,V_model"
+ "T@\"_CDContextualChangeRegistration\",&,N,V_batteryStatusRegistration"
+ "T@\"_CDContextualChangeRegistration\",&,N,V_pluginRegistration"
+ "T@\"_DASDataProtectionStateMonitor\",&,N,V_dataProtectionMonitor"
+ "TB,N,V_prohibitTasksOnTLC"
+ "TB,V_hitTLCDuringCurrentSession"
+ "TLC hit during current plugged-in session"
+ "Trigger: %{public}@ is now [%@]"
+ "Unable to create stream for %@: %@"
+ "_DASChargingSessionMonitor"
+ "_batteryStatusRegistration"
+ "_hitTLCDuringCurrentSession"
+ "_pluginRegistration"
+ "_prohibitTasksOnTLC"
+ "auxiliaryType"
+ "batteryLevel == %@ AND temperature == %@"
+ "batteryStatusRegistration"
+ "chargingSessionMonitor"
+ "com.apple.das.chargingSession.batteryStatus"
+ "com.apple.das.chargingSession.plugin"
+ "com.apple.dasd.chargingSessionMonitorQueue"
+ "com.apple.duetactivityscheduler.chargingSession"
+ "convertKeybagLockedStream:toKnowledgeStoreStream:"
+ "deviceWarm == %@"
+ "getDistinctPPSTimeSeries: metrics must be non-empty for %@/%@"
+ "getDistinctPPSTimeSeries:category:valueFilter:metrics:timeFilter:filepath:error:"
+ "handleBatteryStatusChange"
+ "handlePluginStatusChange"
+ "hitTLCDuringCurrentSession"
+ "initWithMetrics:predicate:timeFilter:limitCount:offsetCount:readDirection:returnsDistinctEntities:"
+ "isPrioritizedIdleStackTask"
+ "markTLCHit"
+ "performWriteExperiments:atFileName:withTask:"
+ "pluginRegistration"
+ "prohibitTasksOnTLC"
+ "prohibitTasksOnTLC is %{BOOL}u"
+ "refreshStaleStringInterning: %lu active StringIDs from %lu successful queries (%lu failed)"
+ "refreshStaleStringInterning: all stale StringIDs confirmed active, skipping remaining categories"
+ "refreshStaleStringInterning: error querying array columns for %{public}@: %{public}@"
+ "refreshStaleStringInterning: error querying scalar columns for %{public}@: %{public}@"
+ "refreshStaleTaskMetadata: %{public}@ returned %lu events, %lu TaskIDs still pending"
+ "refreshStaleTaskMetadata: all stale TaskIDs confirmed active, skipping remaining categories"
+ "registerForContextChanges"
+ "setBatteryStatusRegistration:"
+ "setDataProtectionMonitor:"
+ "setHitTLCDuringCurrentSession:"
+ "setPluginRegistration:"
+ "setProhibitTasksOnTLC:"
+ "unfailActivityForIdentifier:"
+ "writeExperiments: file I/O aborted (%{public}@: %{public}@); dropping partial write"
- "T@\"MLModel\",&,N,V_model"
- "Trigger: %@ is now [%@]"
- "Unable create stream for %@: %@"
- "isPrioritizedIdleStackTasks"
- "refreshStaleStringInterning: %lu active StringIDs from %lu categories (%lu failed)"
- "refreshStaleStringInterning: error querying %{public}@: %{public}@"
- "refreshStaleTaskMetadata: %{public}@ returned %lu events"
```
