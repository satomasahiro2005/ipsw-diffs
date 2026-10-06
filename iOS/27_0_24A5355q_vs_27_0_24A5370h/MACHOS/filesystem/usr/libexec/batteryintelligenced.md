## batteryintelligenced

> `/usr/libexec/batteryintelligenced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x367bc` | `0x3d7b4` | **`+0x6ff8`** |
| `__TEXT.__oslogstring` | `0x63f5` | `0x7425` | **`+0x1030`** |
| `__DATA.__objc_const` | `0x6430` | `0x6d50` | **`+0x920`** |
| `__TEXT.__objc_methname` | `0x5039` | `0x5868` | **`+0x82f`** |
| `__TEXT.__objc_stubs` | `0x3ba0` | `0x4140` | **`+0x5a0`** |
| `__DATA_CONST.__cfstring` | `0x33e0` | `0x3900` | **`+0x520`** |
| `__TEXT.__objc_methlist` | `0x2844` | `0x2bc4` | **`+0x380`** |
| `__TEXT.__cstring` | `0x2ecc` | `0x322b` | **`+0x35f`** |
| `__TEXT.__objc_methtype` | `0x109b` | `0x1396` | **`+0x2fb`** |
| `__DATA.__objc_selrefs` | `0x1328` | `0x1520` | **`+0x1f8`** |
| `__TEXT.__auth_stubs` | `0x920` | `0xa70` | **`+0x150`** |
| `__TEXT.__unwind_info` | `0xa30` | `0xb28` | **`+0xf8`** |
| `__DATA_CONST.__auth_got` | `0x4a0` | `0x548` | **`+0xa8`** |
| `__DATA.__objc_data` | `0x11d0` | `0x1270` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0xb38` | `0xbc8` | **`+0x90`** |
| `__TEXT.__const` | `0x298` | `0x320` | **`+0x88`** |
| `__TEXT.__gcc_except_tab` | `0x280` | `0x2d4` | **`+0x54`** |
| `__DATA.__objc_ivar` | `0x27c` | `0x2c8` | **`+0x4c`** |
| `__DATA_CONST.__objc_intobj` | `0xd50` | `0xd80` | **`+0x30`** |
| `__DATA_CONST.__objc_arraydata` | `0xca8` | `0xcd0` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x774` | `0x792` | **`+0x1e`** |
| `__DATA.__data` | `0x3f0` | `0x408` | **`+0x18`** |
| `__DATA_CONST.__objc_arrayobj` | `0x570` | `0x558` | **`-0x18`** |
| `__DATA.__bss` | `0x230` | `0x220` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x270` | `0x280` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1c8` | `0x1d8` | **`+0x10`** |
| `__DATA_CONST.__objc_doubleobj` | `0x50` | `0x60` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x1a8` | `0x1b8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-208.0.0.0.0
+214.0.0.0.1

+  - /usr/lib/libSMC.dylib

-  Functions: 1192
-  Symbols:   242
-  CStrings:  2000
+  Functions: 1350
+  Symbols:   265
+  CStrings:  2244
Symbols:
+ _CFArrayCreate
+ _CFArrayGetTypeID
+ _CFDataGetTypeID
+ _CFDictionaryGetValue
+ _CFEqual
+ _CFNumberGetValue
+ _CFRetain
+ _IOIteratorNext
+ _IOServiceGetMatchingServices
+ _OBJC_CLASS_$_NSCharacterSet
+ _SMCCloseConnection
+ _SMCGetKeyInfo
+ _SMCMakeUInt32Key
+ _SMCOpenConnectionWithDefaultService
+ _SMCReadKey
+ _SMCReadKeyAsNumericWithKnownKeyInfo
+ _SMCWriteKey
+ _SMCWriteKeyAsNumeric
+ _dispatch_activate
+ _dispatch_after
+ _exp
+ _kCFTypeArrayCallBacks
+ _strcmp
CStrings:
+ "%@: %llu"
+ "%@_pack%u"
+ "%K == %u"
+ "%u"
+ "%u key is not an integer type (%d %d)"
+ "(subsystem == 'BatteryDataCollection' AND category == 'BDC_OBC_Pack')"
+ "(subsystem == 'BatteryDataCollection' AND category == 'BDC_SBC_Pack')"
+ "-%u"
+ "@\"SMCAccessManager\""
+ "@20@0:8I16"
+ "@28@0:8@16I24"
+ "@44@0:8I16{?=ii(?={?=iBSC}[5c])I}20"
+ "@52@0:8I16{?=ii(?={?=iBSC}[5c])I}20@44"
+ "Accuracy logging already running"
+ "Algorithm %@ enabled for pack %u"
+ "Ambient"
+ "AppleSmartBatteryBank"
+ "AppleSmartBatteryPack"
+ "B28@0:8@16I24"
+ "B28@0:8@16f24"
+ "B32@0:8@16Q24"
+ "Battery pack count: %u"
+ "BatteryIndex"
+ "BatteryIndex == %u"
+ "BatteryPackCount"
+ "BatteryPower"
+ "CRate"
+ "C_th"
+ "ChargerIndex"
+ "Current temp in history is invalid, skipping accuracy evaluation"
+ "Data to log to PPS: %@"
+ "Design capacity is zero — c-rate computation will be unavailable"
+ "Design capacity is zero, cannot compute c-rate"
+ "Device already charging at launch — starting logging session"
+ "Device charging — starting/resuming logging session"
+ "Device disconnected — clearing session and stopping logging"
+ "Device no longer charging — skipping sample collection"
+ "Device not actively charging (status=%@) — stopping logging session"
+ "Done BatteryAlgorithmsInit for pack %u"
+ "FF: ThermalModel %s"
+ "Failed to allocate PPS request for accuracy evaluation"
+ "Failed to initialize SMC manager"
+ "Failed to open SMC connection"
+ "Failed to register for charging state notification: %d"
+ "Failed to resolve indexed SMC key for %@ pack %u"
+ "Full init data already populated for pack %u, skipping"
+ "ID"
+ "Insufficient history (%lu samples), skipping accuracy evaluation"
+ "Invalid inputs at s=%lu step %lu, skipping rollout"
+ "Invalid key name"
+ "Invalid start temp at s=%lu, skipping"
+ "Key %@ does not exist or not accessible, error: %d"
+ "Key %@ exists, type: 0x%08X"
+ "Loaded thermal params: R=%.3f C=%.3f etaPkg=%.3f etaBatt=%.3f"
+ "No SMC connection available"
+ "No bank data available."
+ "Not a valid key name"
+ "PPS accuracy query error: %@"
+ "PackID"
+ "Package power %f from SMC key %@ is out of reasonable range"
+ "PackagePower"
+ "Q"
+ "R_th"
+ "Read %u bytes from SMC key %@"
+ "Read SMC key %@: %@"
+ "Read battery power from ASB: %f W"
+ "Read c-rate: %.3f C (amperage=%.0f mA, designCap=%u mAh)"
+ "Read package power from SMC: %f W"
+ "Read system power from ASB: %f W"
+ "Read virtual temp from SMC: %f°C"
+ "Received override params for inference: %@"
+ "SMC connection opened successfully: %p"
+ "SMCAccessManager"
+ "SMCGetKeyInfo error: %d for key: %@"
+ "SMCMakeUInt32Key error for key: %@"
+ "SMCReadKey error %d reading %u bytes for key %@"
+ "SMCReadKey error: %d for flag type"
+ "SMCReadKey error: %d for hex type"
+ "SMCReadKey error: %d for ioft type"
+ "SMCReadKey error: %d for key: %@"
+ "SMCReadKeyAsNumeric error: %d for key: %@"
+ "SMCWriteKey error: %d for key: %@"
+ "SMCWriteKeyAsNumeric error: %d for key: %@"
+ "Skipping thermal sample — temp unavailable, cannot seed rollout"
+ "Started accuracy logging — %.0f seconds remaining this session (generation %lu)"
+ "Started monitoring charge status for thermal sample logging"
+ "Starting BatteryAlgorithmsInit for pack %u"
+ "Stopped accuracy logging"
+ "SystemPower"
+ "T@\"NSObject<OS_dispatch_queue>\",&,N,V_accuracyQueue"
+ "T@\"NSObject<OS_dispatch_queue>\",&,N,V_monitorQueue"
+ "T@\"NSObject<OS_dispatch_source>\",&,N,V_accuracyTimer"
+ "T@\"SMCAccessManager\",&,N,V_smcManager"
+ "TI,N,V_designCapacityMah"
+ "TI,N,V_packIndex"
+ "TI,R,V_packCount"
+ "TI,R,V_packIndex"
+ "TQ,N,V_sessionGeneration"
+ "TVRM"
+ "T^{?=IB^{SMCAccumPlatformInfo}[4{?=I{?=ii(?={?=iBSC}[5c])I}(?=Qqd)(?=Qqd)(?=Qqd)}][4{?=I{?=ii(?={?=iBSC}[5c])I}(?=Qqd)(?=Qqd)(?=Qqd)}]CCBBB{?=[4I][4I]CC}BB},N,V_smcConnection"
+ "Td,N,V_deviceCth"
+ "Td,N,V_deviceEtaBatt"
+ "Td,N,V_deviceEtaPackage"
+ "Td,N,V_deviceRth"
+ "Temp"
+ "Temperature estimate after %.1f mins: %.2f"
+ "Thermal logging already completed for this charging session, skipping"
+ "ThermalLoggingSessionStartTime"
+ "ThermalModel"
+ "ThermalModelParameters.plist"
+ "ThermalModelParameters.plist not found — using global defaults"
+ "ThermalModel_Sample"
+ "Unable to get power telemetry table from ASB data, returning"
+ "Unable to load battery data."
+ "Unable to load battery/charging data, returning"
+ "Unable to produce temperature estimate with one or more missing input values."
+ "Unable to read SMC key %@ for package power"
+ "Unable to read SMC key %@ for virtual temp"
+ "Unable to read battery power (%@) from ASB data"
+ "Unable to read battery voltage (%@) from ASB data"
+ "Unable to read system power (%@) from ASB data"
+ "Unknown non-numeric SMC type: %s"
+ "Unknown numeric SMC type: %d for key: %@"
+ "Unsupported key size %d for SMC key %@"
+ "Unsupported key size %d for SMC key %@ with Array attribute"
+ "UpdateTime"
+ "Using updated params loaded from device: %@"
+ "V1"
+ "Virtual temp %f from SMC key %@ is out of reasonable range"
+ "Wrote SMC key %@: %f"
+ "Wrote SMC key %@: %u (ui32)"
+ "[%@] pack %u: Algorithm found"
+ "[%@] pack %u: Algorithm is enabled"
+ "[%@] pack %u: Call Algorithm init"
+ "[%@] pack %u: Fresh init needed"
+ "[%@] pack %u: Init done already. Skipping init"
+ "[%@] packIndex %u out of bounds (packInitObjs.count=%lu), skipping"
+ "[Migration] Old flat plist at %@, adopting as pack 0 data"
+ "^{?=IB^{SMCAccumPlatformInfo}[4{?=I{?=ii(?={?=iBSC}[5c])I}(?=Qqd)(?=Qqd)(?=Qqd)}][4{?=I{?=ii(?={?=iBSC}[5c])I}(?=Qqd)(?=Qqd)(?=Qqd)}]CCBBB{?=[4I][4I]CC}BB}"
+ "^{?=IB^{SMCAccumPlatformInfo}[4{?=I{?=ii(?={?=iBSC}[5c])I}(?=Qqd)(?=Qqd)(?=Qqd)}][4{?=I{?=ii(?={?=iBSC}[5c])I}(?=Qqd)(?=Qqd)(?=Qqd)}]CCBBB{?=[4I][4I]CC}BB}16@0:8"
+ "_accuracyQueue"
+ "_accuracyTimer"
+ "_designCapacityMah"
+ "_deviceCth"
+ "_deviceEtaBatt"
+ "_deviceEtaPackage"
+ "_deviceRth"
+ "_monitorQueue"
+ "_packCount"
+ "_packIndex"
+ "_sessionGeneration"
+ "_smcConnection"
+ "_smcManager"
+ "accuracyQueue"
+ "accuracyTimer"
+ "algorithmPackIndex"
+ "ambient"
+ "ambientTemp"
+ "batteryPower"
+ "batteryPowerWFromASBData:"
+ "batteryProperties"
+ "batteryVoltageVFromASBData:"
+ "cRate"
+ "chargerLossesFromSystemPowerW:"
+ "chargingCRateFromASBData:"
+ "collectSampleAndEvaluate"
+ "com.apple.batteryintelligenced.thermalmodel.accuracy"
+ "com.apple.batteryintelligenced.thermalmodel.monitor"
+ "currentTemp"
+ "d24@0:8@16"
+ "d24@0:8d16"
+ "d48@0:8d16d24d32d40"
+ "d56@0:8d16d24d32d40d48"
+ "dataWithBytes:length:"
+ "decimalDigitCharacterSet"
+ "designCapacityMah"
+ "deviceCth"
+ "deviceEtaBatt"
+ "deviceEtaPackage"
+ "deviceRth"
+ "dictionaryWithContentsOfURL:"
+ "dtMins"
+ "eta_batt"
+ "eta_package"
+ "evaluateHistoricalAccuracyWithSamples:"
+ "evaluateModelAccuracy"
+ "executablePath"
+ "flag"
+ "fusedBankData"
+ "fusedBankDataFromPacks: not doing fusion as there is bank count mismatch: pack 0 has %lu banks, pack %lu has %lu banks"
+ "fusedPackData"
+ "fusedScalarBatteryDataFromPacks: pack %lu missing key %{public}@"
+ "getBatteryData: UpdateTime changed during read (before=%@ after=%@), retry %u/%u"
+ "getBatteryData: UpdateTime unstable after %u retries"
+ "getBatteryData: pack %lu — cycles=%@ ncc=%@ voltage=%@ amperage=%@ temp=%@ chargeAccum=%@"
+ "getBatteryData: packCount=%u fusedPackData=%lu keys fusedBankData=%lu banks"
+ "getPerPackBatteryDataFromRegistry: Failed to match AppleSmartBatteryPack"
+ "getPerPackBatteryDataFromRegistry: No battery packs found"
+ "handleNonNumericKey:keyInfo:"
+ "handleNumericKey:keyInfo:keyName:"
+ "hex_"
+ "initWithPackIndex:"
+ "initialTemp"
+ "invertedSet"
+ "ioft"
+ "kIOPMPSInstantAmperageKey missing from power source data"
+ "keyExists:"
+ "loadDeviceParams"
+ "mainBundle"
+ "monitorChargeScenario"
+ "monitorQueue"
+ "numberWithUnsignedLong:"
+ "numberWithUnsignedLongLong:"
+ "numberWithUnsignedShort:"
+ "packCount"
+ "packIndex"
+ "packagePower"
+ "perPackBatteryData"
+ "q24@?0@\"NSArray\"8@\"NSArray\"16"
+ "rangeOfCharacterFromSet:"
+ "readAllBankBatteryDataForPack: failed to match AppleSmartBatteryBank"
+ "readAllBankBatteryDataForPack: pack %u — %lu banks found"
+ "readSMCKey:"
+ "readSMCKeyData: invalid arguments for key %@"
+ "readSMCKeyData: malloc failed for %u bytes, key %@"
+ "readSMCKeyData:dataSize:"
+ "recordThermalSampleWithTemp:packagePower:batteryPower:systemPower:cRate:voltage:ambient:"
+ "sessionGeneration"
+ "setAccuracyQueue:"
+ "setAccuracyTimer:"
+ "setDesignCapacityMah:"
+ "setDeviceCth:"
+ "setDeviceEtaBatt:"
+ "setDeviceEtaPackage:"
+ "setDeviceRth:"
+ "setMonitorQueue:"
+ "setPackIndex:"
+ "setSessionGeneration:"
+ "setSmcConnection:"
+ "setSmcManager:"
+ "sharedManager"
+ "smc-access"
+ "smcConnection"
+ "smcManager"
+ "startLoggingSession"
+ "stopLoggingSession"
+ "subsystem == 'BatteryIntelligence' AND category == %@"
+ "systemPowerFromASBData:"
+ "tempEstimates"
+ "thermal-predictor"
+ "thermalModelAtTime:withInitialTemp:ambientTemp:pPackage:pBatt:"
+ "thermalModelAtTime:withInitialTemp:ambientTemp:power:"
+ "thermal_model"
+ "v20@0:8I16"
+ "v24@0:8Q16"
+ "v24@0:8^{?=IB^{SMCAccumPlatformInfo}[4{?=I{?=ii(?={?=iBSC}[5c])I}(?=Qqd)(?=Qqd)(?=Qqd)}][4{?=I{?=ii(?={?=iBSC}[5c])I}(?=Qqd)(?=Qqd)(?=Qqd)}]CCBBB{?=[4I][4I]CC}BB}16"
+ "v72@0:8d16d24d32d40d48d56d64"
+ "writeSMCKey:floatValue:"
+ "writeSMCKey:floatValue: invalid arguments for key %@"
+ "writeSMCKey:uint32Value:"
+ "writeSMCKey:uint64Value:"
+ "xDPE"
- "%@"
- "Algorithms %@ enabled"
- "ChargerData"
- "Done BatteryAlgorithmsInit"
- "PresentDOD array was empty."
- "Qmax array was empty."
- "Starting BatteryAlgorithmsInit"
- "Unable to get any Battery data from IOPMPS"
- "Unable to get any charger data from IOPMPS"
- "Unable to get any data from IOPMPS"
- "Unable to get any lifeTimeData data from IOPMPS"
- "Unable to load battery data table."
- "Unexpected wRa type %@"
- "[%@] Algorithm found"
- "[%@] Algorithm is enabled"
- "[%@] Call Algorithm init"
- "[%@] Fresh init needed"
- "[%@] Init done already. Skipping init"
```
