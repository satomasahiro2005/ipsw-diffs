## nfcd

> `/usr/libexec/nfcd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e854c` | `0x1edfa8` | **`+0x5a5c`** |
| `__TEXT.__cstring` | `0x22a48` | `0x23238` | **`+0x7f0`** |
| `__DATA_CONST.__cfstring` | `0x113a0` | `0x11920` | **`+0x580`** |
| `__TEXT.__objc_methname` | `0x15a48` | `0x15f91` | **`+0x549`** |
| `__TEXT.__oslogstring` | `0x20776` | `0x20c81` | **`+0x50b`** |
| `__DATA.__objc_const` | `0x14ec8` | `0x15238` | **`+0x370`** |
| `__TEXT.__objc_stubs` | `0xe060` | `0xe3c0` | **`+0x360`** |
| `__DATA_CONST.__objc_intobj` | `0x7c20` | `0x7db8` | **`+0x198`** |
| `__TEXT.__objc_methlist` | `0x9de4` | `0x9f4c` | **`+0x168`** |
| `__TEXT.__delay_helper` | `0x172c` | `0x1878` | **`+0x14c`** |
| `__DATA.__objc_selrefs` | `0x4bc8` | `0x4cf8` | **`+0x130`** |
| `__TEXT.__auth_stubs` | `0x1880` | `0x1920` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x2c58` | `0x2cf8` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x9a50` | `0x9ae0` | **`+0x90`** |
| `__DATA.__data` | `0x2b3c` | `0x2ba0` | **`+0x64`** |
| `__TEXT.__objc_methtype` | `0x4e1f` | `0x4e81` | **`+0x62`** |
| `__DATA.__objc_data` | `0x3f20` | `0x3f70` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0xcf0` | `0xd40` | **`+0x50`** |
| `__DATA_CONST.__objc_dictobj` | `0x1040` | `0x1090` | **`+0x50`** |
| `__DATA.__objc_ivar` | `0x1138` | `0x1180` | **`+0x48`** |
| `__TEXT.__objc_classname` | `0x1d44` | `0x1d83` | **`+0x3f`** |
| `__DATA_CONST.__objc_arraydata` | `0x1e70` | `0x1ea0` | **`+0x30`** |
| `__DATA_CONST.__objc_arrayobj` | `0x360` | `0x378` | **`+0x18`** |
| `__DATA.__bss` | `0x2c0` | `0x2d0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xa08` | `0xa18` | **`+0x10`** |
| `__TEXT.__const` | `0x145c` | `0x144c` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x650` | `0x658` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x388` | `0x390` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x480` | `0x488` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-  Functions: 4281
-  Symbols:   673
-  CStrings:  11419
+  Functions: 4334
+  Symbols:   686
+  CStrings:  11583
Symbols:
+ _NFDataAsHexString
+ _NFDriverGetBootMeasurements
+ _NFDriverGetFactoryPage
+ _NFDriverGetRFState
+ _NFDriverSetRFState
+ _NFPlatformHasAlternateRFSettings
+ _NFPlatformHasBootMeasurements
+ _NFProductHasFactoryPage
+ _NFProductIsRTIDEnabledByDefault
+ _NFProductSupportsRTID
+ _OBJC_CLASS_$_ATLSecureElementFirmware
+ _OBJC_CLASS_$_CMAngleManager
+ _OBJC_CLASS_$_NFHashes
CStrings:
+ "!isLowBand || !isHighBand"
+ "%f"
+ "%{public}s:%i Allowed thresholds are %f -> %f, using %f -> %f"
+ "%{public}s:%i Angle change of interest : %f -> %f"
+ "%{public}s:%i Boot measurements are not enabled."
+ "%{public}s:%i Boot measurements for NFCC : %{public}s"
+ "%{public}s:%i Boot measurements for SE : %s - %s"
+ "%{public}s:%i Boot stop interrupt received with count: %llu"
+ "%{public}s:%i Can't get measurements - reset is prevented."
+ "%{public}s:%i Critical error : mismatched boot measurements : %@"
+ "%{public}s:%i Custom RTID setting"
+ "%{public}s:%i Error ! Failed to write to boot measurements file."
+ "%{public}s:%i Failed to validate boot measurements, marking hardware as un-available."
+ "%{public}s:%i Found stored BMs : %@"
+ "%{public}s:%i Invalid angle customization"
+ "%{public}s:%i Loaded NFCC measurements from disk."
+ "%{public}s:%i Loaded SE measurements from disk."
+ "%{public}s:%i Monitor is NULL !!"
+ "%{public}s:%i Monitor not available..."
+ "%{public}s:%i Querying boot measurement !!!!!!"
+ "%{public}s:%i Received boot-stop while running. Restarting driver"
+ "%{public}s:%i Received boot-stop while running. booting driver with VEN reset..."
+ "%{public}s:%i Registering new handler.."
+ "%{public}s:%i SWD is enabled - not resetting - boot measurements are skipped."
+ "%{public}s:%i UseRTID = %d"
+ "%{public}s:%i failed to start the driver! error=%@"
+ "-[NFAngleMonitor angleChanged:]"
+ "-[NFAngleMonitor init]"
+ "-[NFAngleMonitor registerDelegate:onQueue:]"
+ "-[NFDriverWrapper receivedBootStop]"
+ "-[NFDriverWrapper(BootMeasurements) queryNFCCBootMeasurements:]"
+ "-[NFDriverWrapper(BootMeasurements) querySEBootMeasurements:]"
+ "-[NFDriverWrapper(BootMeasurements) validateCurrentNFCCBootMeasurements]"
+ "-[NFDriverWrapper(BootMeasurements_Private) _getBootMeasurementForKey:]"
+ "-[NFDriverWrapper(BootMeasurements_Private) _queryBootMeasurementCache]"
+ "-[NFDriverWrapper(BootMeasurements_Private) _queryBootMeasurementOnDriverOpen:]"
+ "-[NFDriverWrapper(BootMeasurements_Private) _storeBootMeasurements:forKey:]"
+ "-[_NFHardwareManager handleBootStopInterrupt:]"
+ "-[_NFInternalConfigurationSession getControllerRfSettingsWithCompletion:]_block_invoke"
+ "-[_NFInternalConfigurationSession switchRfSettings:completion:]_block_invoke"
+ "/System/Library/Frameworks/CoreMotion.framework/CoreMotion"
+ "/usr/standalone/firmware/nfrestore/firmware/fury-fw-hashes/PN800V-hashes.plist"
+ "/usr/standalone/firmware/nfrestore/firmware/fw-hashes/SN450V-hashes.plist"
+ "0000000000000000000000000000000000000000000000000000000000000000"
+ "??"
+ "@\"<NFAngleMonitorDelegate>\""
+ "@\"CMAngleManager\""
+ "@\"NFAngleMonitor\""
+ "@24@0:8*16"
+ "AppleCamera"
+ "Boot measurement reset"
+ "Boot measurements"
+ "Boot stop interrupt"
+ "Boot stop interrupt occured"
+ "BootMeasurements_Private"
+ "High"
+ "InvalidNfccHash0"
+ "InvalidNfccHash1"
+ "InvalidNfccHash2"
+ "InvalidNfccHash3"
+ "InvalidNfccHash4"
+ "InvalidNfccHash5"
+ "InvalidNfccHash6"
+ "Low"
+ "N/A"
+ "NFAngleMonitor"
+ "NFAngleMonitor.m"
+ "NFAngleMonitorDelegate"
+ "NFCC_P"
+ "NFCC_S"
+ "NFDriverWrapper+BootMeasurements.m"
+ "SE Boot Measurements"
+ "SE1"
+ "SE2"
+ "SEHash1"
+ "SEHash2"
+ "SEKeyID"
+ "SEMeasurements"
+ "SEResult"
+ "T@\"<NFAngleMonitorDelegate>\",W,V_delegate"
+ "T@\"CMAngleManager\",&,V_angleManager"
+ "TB,R,N,V_hasSWDEnabled"
+ "Tf,V_highThreshold"
+ "Tf,V_lowThreshold"
+ "^{_NFDriver=i**^viii{?=iiBB}BBBBBBBBBBBB}"
+ "_angleManager"
+ "_angleMonitor"
+ "_bootMeasurementCacheQueried"
+ "_currentAngle"
+ "_currentBand"
+ "_getBootMeasurementForKey:"
+ "_hasCompleteMeasurement"
+ "_hasSWDEnabled"
+ "_highThreshold"
+ "_highThreshold < CMAngleManager.maxAngleDegrees"
+ "_highThreshold > _lowThreshold"
+ "_lastReportedAngle"
+ "_lastReportedModeDefault"
+ "_loadHashes"
+ "_lowThreshold"
+ "_lowThreshold > CMAngleManager.minAngleDegrees"
+ "_needsNFCCBootMeasurementQuery"
+ "_needsSEBootMeasurementQuery"
+ "_nfccBootMeasurements"
+ "_nfccBootMeasurements == nil"
+ "_pendingAngleChange"
+ "_previousAngleBand"
+ "_queryBootMeasurementCache"
+ "_queryBootMeasurementOnDriverOpen:"
+ "_seBootMeasurements"
+ "_snapshotReported"
+ "_storeBootMeasurements:forKey:"
+ "_useRTID"
+ "addDeviceModeDimensionsToDictionary:"
+ "angle"
+ "angleBand"
+ "angleChanged:"
+ "angleDegrees"
+ "angleManager"
+ "bootMeasurements"
+ "bootStopDetected"
+ "bucketDeviceAngle:"
+ "com.apple.nfcd.boot-measurements.plist"
+ "com.apple.nfcd.bootMeasurementEvent"
+ "dictionaryWithObjects:forKeys:"
+ "enableRTIDDebug"
+ "enableRTIDToSMCIntegration"
+ "enforceBootMeasurements"
+ "f"
+ "f16@0:8"
+ "failed to start the driver"
+ "getControllerRfSettings:"
+ "getNFCCBootMeasurementsWithCompletion:"
+ "getRFStateIndex:"
+ "getSEBootMeasurementsWithCompletion:"
+ "hasSWDEnabled"
+ "highAngleThreshold"
+ "highThreshold"
+ "isAngleValid"
+ "isAvailable"
+ "lowAngleThreshold"
+ "lowThreshold"
+ "maxAngleDegrees"
+ "minAngleDegrees"
+ "nfcDeviceModeStateChangeCount"
+ "noReference"
+ "queryNFCCBootMeasurements:"
+ "querySEBootMeasurements:"
+ "rtid"
+ "seBootMeasurements"
+ "setAngleManager:"
+ "setAngleUpdateInterval:"
+ "setHighThreshold:"
+ "setLowThreshold:"
+ "setRFStateIndex:"
+ "startAngleUpdatesToQueue:handler:"
+ "stopAngleUpdates"
+ "swdEnabled"
+ "switchRfSettings:"
+ "updateDeviceAngle:modeDefault:"
+ "v16@?0@\"CMAngle\"8"
+ "v20@0:8f16"
+ "validateCurrentNFCCBootMeasurements"
+ "validateNFCCHashes:reference:expectedVersion:hashResults:"
+ "validateSEFWMeasurements:seManifest:"
+ "\xf0\xf0\xf0\xb1"
- "^{_NFDriver=i**^viii{?=iiBB}BBBBBBBBBB}"
- "\xf0\xf0\xf0\x81"
```
