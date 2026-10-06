## bluetoothd

> `/usr/sbin/bluetoothd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x904e90` | `0x909504` | **`+0x4674`** |
| `__TEXT.__oslogstring` | `0xc0f13` | `0xc1891` | **`+0x97e`** |
| `__TEXT.__cstring` | `0xc7dbe` | `0xc8287` | **`+0x4c9`** |
| `__TEXT.__gcc_except_tab` | `0x70b58` | `0x70f5c` | **`+0x404`** |
| `__DATA_CONST.__const` | `0x342d0` | `0x344f0` | **`+0x220`** |
| `__TEXT.__unwind_info` | `0x26298` | `0x26408` | **`+0x170`** |
| `__TEXT.__objc_methname` | `0x1f6d6` | `0x1f7b1` | **`+0xdb`** |
| `__TEXT.__objc_stubs` | `0x19c20` | `0x19ce0` | **`+0xc0`** |
| `__DATA.__objc_const` | `0x109a8` | `0x10a58` | **`+0xb0`** |
| `__TEXT.__auth_stubs` | `0x5270` | `0x52e0` | **`+0x70`** |
| `__TEXT.__objc_methtype` | `0x5a56` | `0x5ac0` | **`+0x6a`** |
| `__DATA_CONST.__cfstring` | `0x27a00` | `0x27a60` | **`+0x60`** |
| `__DATA.__objc_data` | `0x1e20` | `0x1e70` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x2950` | `0x2988` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x77a0` | `0x77d0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x9bf4` | `0x9c24` | **`+0x30`** |
| `__DATA.__common` | `0x17c78` | `0x17ca0` | **`+0x28`** |
| `__DATA_CONST.__got` | `0xe48` | `0xe70` | **`+0x28`** |
| `__DATA.__bss` | `0x76c52` | `0x76c72` | **`+0x20`** |
| `__TEXT.__const` | `0x25ea0` | `0x25ec0` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x158` | `0x176` | **`+0x1e`** |
| `__TEXT.__swift5_capture` | `0xd8` | `0xbc` | **`-0x1c`** |
| `__TEXT.__objc_classname` | `0xa32` | `0xa45` | **`+0x13`** |
| `__DATA_CONST.__auth_ptr` | `0x258` | `0x268` | **`+0x10`** |
| `__DATA.__data` | `0x4f28` | `0x4f30` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x2f8` | `0x300` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x11d4` | `0x11d8` | **`+0x4`** |
| `__TEXT.__init_offsets` | `0x6c` | `0x70` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2701.3.0.0.0
+2701.7.0.0.0

-  Functions: 37393
-  Symbols:   1804
-  CStrings:  43068
+  Functions: 37463
+  Symbols:   1818
+  CStrings:  43138
Symbols:
+ _$s10ObjectiveC8ObjCBoolVMn
+ _$s14ProductKitCore0A5ErrorO13assetNotFoundyA2CmFWC
+ _$s14ProductKitCore9ProxSetupO11EnvironmentO10productionyA2EmFWC
+ _$s14ProductKitCore9ProxSetupO11EnvironmentO7sandboxyA2EmFWC
+ _$s14ProductKitCore9ProxSetupO6ServerO10productionyA2EmFWC
+ _$s14ProductKitCore9ProxSetupO6ServerO7stagingyA2EmFWC
+ _$s14ProductKitCore9ProxSetupO6ServerOMa
+ _$s14ProductKitCore9ProxSetupO7ManagerC6serverAeC6ServerO_tcfc
+ _$ss5ErrorMp
+ _swift_dynamicCast
+ _swift_errorRetain
+ _swift_getObjCClassMetadata
+ _swift_once
+ _swift_release_x27
CStrings:
+ "%{public}s %p"
+ "01:32:13"
+ "AppMigrationHelper"
+ "AppMigrationHelper: %{public}@ supersedes %{public}@ — substituting for privilege check"
+ "AppMigrationHelper: LSBundleRecord lookup failed for %{public}@ (%{public}@)"
+ "AppMigrationHelper: malformed superseded entry for %{public}@"
+ "AppMigrationHelper: skipping LS lookup for %{public}@ — device not unlocked since boot"
+ "AppMigrationHelper: superseded entry \"%{public}@\" missing TEAMID.bundleID separator"
+ "BTAppMigrationMsgHandler: received migration event source=\"%{public}s\" dest=\"%{public}s\" entityType=%llu"
+ "BTAppMigrationMsgHandler: rejecting migration event — SecTaskCopySigningIdentifier failed"
+ "BTAppMigrationMsgHandler: rejecting migration event — SecTaskCreateWithAuditToken failed"
+ "BTAppMigrationMsgHandler: rejecting migration event — args=%p sourceBundleID=%p destBundleID=%p"
+ "BTAppMigrationMsgHandler: rejecting migration event — caller signing identity is \"%{public}@\", expected \"com.apple.BTAppDataMigration\""
+ "Channel Sounding role 0x%llx needs the EnableCsPreWarm default set"
+ "Channel Sounding role 0x%llx needs the EnableCsRunProceduresOnly default set"
+ "Channel sounding not supported for country code: %{public}@"
+ "Creation of WRMXPCMsg failed"
+ "DOWNGRADE has active link requirement hint (%d pps) for lmhandle 0x%4x, but peer version %d predates refusal support, obeying"
+ "DOWNGRADE refused, active link requirement hint (%d pps) for lmhandle 0x%4x"
+ "DOWNGRADE_CFM refused (%s) but no alternate handle to unstall."
+ "Duplicate request; replying with requested params to avoid silent-drop"
+ "ERROR_CONTROLLER"
+ "ERROR_LINK_REQUIREMENT"
+ "EnableCSReadPHYDebugBuffer"
+ "EnableCsPreWarm"
+ "EnableCsRunProceduresOnly"
+ "HomeKitProxAccessory skipping ProductKit fetch, retry backoff active for beacon %@"
+ "LE_CsProcedureEnableComplete: peer-initiated start, re-arming coex"
+ "LE_CsProcedureEnableComplete: peer-initiated stop, holding session"
+ "LeChannelSoundingAgent EnableCSReadPHYDebugBuffer set to %d"
+ "LeChannelSoundingAgent EnableCsPreWarm set to %d"
+ "LeChannelSoundingAgent EnableCsRunProceduresOnly set to %d"
+ "MusicHandoffScan"
+ "NANDP setup state changed: %s -> %s"
+ "OI_STATUS _ACI_HCIPPGenericCmdV2(uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t *, BT_VSC_BYTESTREAM_CB)"
+ "PHY_Debug_Data"
+ "Peer refused downgrade (%s) for lmhandle 0x%4x, staying on current transport"
+ "Procedure-only chain: csSetProcedureParams on configId=%u"
+ "Procedure-only mode: stopping procedures, keeping the agent"
+ "Procedure-only start has no CS config to run against: handle=%p"
+ "Q16@?0Q8"
+ "Q32@0:8@?16Q24"
+ "Q36@0:8Q16B24Q28"
+ "Sep 28 2026"
+ "Session now registering for deviceAccess DADaemonSession with bundle ID %@(%@) restorationID:%@"
+ "Setup-only chain complete: holding configId=%u, agent stays alive"
+ "Setup-only chain: peripheral, continue with csSetDefaultSettings"
+ "Setup-only chain: starting with csReadRemoteSupportedCapabilities"
+ "Stalled DOWNGRADE refused, link requirement hint became active while draining for lmhandle 0x%4x"
+ "T{?=CSSSCCCCCC[160C][160C][160C][25600C]CCSBdICC[224C]},N,V_procedureResults"
+ "WCM not enabled, skipping processing UseCases"
+ "Warning: csPhyDebugBufferNotify: chunk_bytes(%u) exceeds the %u usable bytes; dropping PHY data"
+ "Warning: csPhyDebugBufferNotify: response too short (%u bytes)"
+ "Warning: handleLeConnectionParametersUpdateRequest: handle went invalid between HCI event and dispatch (id=%d requested %d-%d latency=%d timeout=%d) — race with disconnect, no Reply/Neg-Reply will be sent"
+ "_nandpSetupActive"
+ "applyTransform:timeoutUsec:"
+ "com.apple.BTAppDataMigration"
+ "com.apple.bluetooth.PurpleLocation.countryCode"
+ "com.apple.developer.superseded-application-identifiers"
+ "csPhyDebugBufferNotify: chunk=%u steps=%u remaining=%u dropped=%u valid=%u for %zu saved procedure(s)"
+ "effectivePrivilegeBundleIDFor:"
+ "fHeader is not valid for Reset"
+ "kCBCSPhyDebugData"
+ "kCBCSPhyDebugNumSteps"
+ "kCBMsgArgAppMigrationDestBundleID"
+ "kCBMsgArgAppMigrationEntityType"
+ "kCBMsgArgAppMigrationSourceBundleID"
+ "kCBMsgIdAppMigrationEventMsg"
+ "kWCMBTMusicHandoffActive"
+ "proximityServiceProductKitBackoffTicks"
+ "rangeOfString:"
+ "sendMusicHandoffState: %s"
+ "setActivityFlag:enabled:timeoutUsec:"
+ "setProximityServiceProductKitBackoffTicks:"
+ "v26360@0:8{?=CSSSCCCCCC[160C][160C][160C][25600C]CCSBdICC[224C]}16"
+ "v28@?0@\"CBHomeKitProxAccessoryMetadata\"8@\"NSError\"16B24"
+ "virtual BTAppMigrationMsgHandler::~BTAppMigrationMsgHandler()"
+ "virtual void BTAppMigrationMsgHandler::handleDisconnection(xpc_connection_t, bool)"
+ "{?=\"configId\"C\"startAclConnEvent\"S\"procedureCounter\"S\"frequencyCompensation\"S\"referencePowerLevel\"C\"procedureDoneStatus\"C\"subEventDoneStatus\"C\"abortReason\"C\"numAntennaPath\"C\"numStepsReported\"C\"stepMode\"[160C]\"stepChannel\"[160C]\"stepDataLength\"[160C]\"stepData\"[25600C]\"currentStepIndex\"C\"currentStepDataLength\"C\"currentStepDataIndex\"S\"returnTonesData\"B\"distance\"d\"numSubeventsReported\"I\"phyDebugNumSteps\"C\"phyDebugNumBytes\"C\"phyDebugData\"[224C]}"
+ "{?=CSSSCCCCCC[160C][160C][160C][25600C]CCSBdICC[224C]}16@0:8"
- "20:59:16"
- "OI_STATUS _ACI_HCIPPGenericCmdV2(uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t *, BT_VSC_COMPLETE_CB)"
- "Sep 14 2026"
- "Session now registering for deviceAccess DASession with bundle ID %@(%@) restorationID:%@"
- "T{?=CSSSCCCCCC[160C][160C][160C][25600C]CCSBdI},N,V_procedureResults"
- "countryCodes_regV5.0_sarV1.14.plist"
- "v24@?0@\"CBHomeKitProxAccessoryMetadata\"8@\"NSError\"16"
- "v26136@0:8{?=CSSSCCCCCC[160C][160C][160C][25600C]CCSBdI}16"
- "{?=\"configId\"C\"startAclConnEvent\"S\"procedureCounter\"S\"frequencyCompensation\"S\"referencePowerLevel\"C\"procedureDoneStatus\"C\"subEventDoneStatus\"C\"abortReason\"C\"numAntennaPath\"C\"numStepsReported\"C\"stepMode\"[160C]\"stepChannel\"[160C]\"stepDataLength\"[160C]\"stepData\"[25600C]\"currentStepIndex\"C\"currentStepDataLength\"C\"currentStepDataIndex\"S\"returnTonesData\"B\"distance\"d\"numSubeventsReported\"I}"
- "{?=CSSSCCCCCC[160C][160C][160C][25600C]CCSBdI}16@0:8"
```
