## audioaccessoryd

> `/usr/libexec/audioaccessoryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x258aa8` | `0x25b990` | **`+0x2ee8`** |
| `__TEXT.__cstring` | `0x58a93` | `0x590e3` | **`+0x650`** |
| `__DATA.__objc_const` | `0x1fee8` | `0x20490` | **`+0x5a8`** |
| `__TEXT.__objc_methname` | `0x2d3c5` | `0x2d575` | **`+0x1b0`** |
| `__TEXT.__objc_stubs` | `0x1f2c0` | `0x1f420` | **`+0x160`** |
| `__DATA_CONST.__cfstring` | `0xb980` | `0xbaa0` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0xe8bc` | `0xe9dc` | **`+0x120`** |
| `__DATA_CONST.__const` | `0xcd30` | `0xce38` | **`+0x108`** |
| `__TEXT.__objc_methtype` | `0x4209` | `0x42e2` | **`+0xd9`** |
| `__TEXT.__auth_stubs` | `0x3bb0` | `0x3c80` | **`+0xd0`** |
| `__DATA.__data` | `0x5940` | `0x59e0` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x9e5a` | `0x9efa` | **`+0xa0`** |
| `__TEXT.__const` | `0x4d10` | `0x4d80` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x7250` | `0x72c0` | **`+0x70`** |
| `__DATA.__objc_data` | `0x3670` | `0x36d8` | **`+0x68`** |
| `__DATA_CONST.__auth_got` | `0x1de8` | `0x1e50` | **`+0x68`** |
| `__DATA.__objc_selrefs` | `0x9308` | `0x9358` | **`+0x50`** |
| `__TEXT.__objc_classname` | `0x1143` | `0x1193` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x2d80` | `0x2dc8` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x1130` | `0x1160` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x1884` | `0x18a0` | **`+0x1c`** |
| `__TEXT.__swift5_typeref` | `0x1ee4` | `0x1f00` | **`+0x1c`** |
| `__DATA.__bss` | `0x7630` | `0x7640` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x3d0` | `0x3e0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x228` | `0x238` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1998` | `0x19a8` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1bbb` | `0x1bab` | **`-0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x7b8` | `0x7c0` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x2114` | `0x2110` | **`-0x4`** |
| `__TEXT.__swift5_capture` | `0x1fb8` | `0x1fbc` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x120` | `0x124` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-40.36.1.0.0
+40.41.1.1.4

-  Functions: 12034
-  Symbols:   1690
-  CStrings:  16348
+  Functions: 12091
+  Symbols:   1708
+  CStrings:  16411
Symbols:
+ _$sSJ13hexDigitValueSiSgvg
+ _$sSS5index5afterSS5IndexVAD_tF
+ _$sSSySJSS5IndexVcig
+ _$sSs10uppercasedSSyF
+ _$sSs5index5afterSS5IndexVAD_tF
+ _$sSs8distance4from2toSiSS5IndexV_AEtF
+ _$sSsN
+ _$sSsySJSS5IndexVcig
+ _CFDictionaryCreateMutable
+ _CFDictionarySetValue
+ _CFRunLoopAddSource
+ _CFRunLoopGetMain
+ _CFRunLoopRemoveSource
+ _CFUserNotificationCreateRunLoopSource
+ _kCFRunLoopCommonModes
+ _kCFTypeDictionaryKeyCallBacks
+ _kCFTypeDictionaryValueCallBacks
+ _kCFUserNotificationOtherButtonTitleKey
CStrings:
+ "!"
+ "-[AccessoryDiagnosticsMonitor _fileRadarForDevice:]"
+ "-[AccessoryDiagnosticsMonitor _handleBobbleAlertResponseForNotification:flags:]_block_invoke"
+ "-[AccessoryDiagnosticsMonitor _logPropertyChangesFrom:to:]"
+ "-[AccessoryDiagnosticsMonitor _showBobbleTurnedOffNotificationForDevice:]"
+ "1540729"
+ "@\"AccessoryDiagnosticsPendingAlert\""
+ "@40@0:8^{__CFUserNotification=}16^{__CFRunLoopSource=}24@32"
+ "AccessoryDiagnosticsMonitor"
+ "AccessoryDiagnosticsPendingAlert"
+ "AirPods Head Gestures Turned Off"
+ "Bobble Turned Off - File Radar tapped for device: %@"
+ "Bobble alert cancelled without File Radar. deviceId: %@"
+ "Bobble alert create failed. deviceId: %@, error: %d"
+ "Bobble alert dismissed via Do Not Ask Again. deviceId: %@"
+ "Bobble alert presented. deviceId: %@"
+ "Bobble alert runloop source create failed. deviceId: %@"
+ "Bobble alert suppressed by user preference. deviceId: %@"
+ "Bobble alert suppressed, another alert is already pending. deviceId: %@"
+ "Bobble unexpectedly turned off on %@ at %@"
+ "BobbleAlertDisabledByUser"
+ "BobbleDebugAlert"
+ "Bug"
+ "Cancel"
+ "Connected Audio - Cloud Sync | All"
+ "Could not resolve BT MAC for writer UUID %s"
+ "Count"
+ "Do Not Ask Again"
+ "Head gesture toggle changed for device: %@, from: %s, to: %s"
+ "Head gesture unexpectedly turned off for device: %@"
+ "Head gestures were unexpectedly disabled on %@? Please file a radar."
+ "Missing deviceConfiguration"
+ "No device found for identifier: %@"
+ "No matching reader for writer UUID %s; dropping sensor data"
+ "No pending Bobble alert found for notification response"
+ "Received write sensor data message with %ld bytes from writer UUID %s"
+ "Registered read connection for device configuration: %s"
+ "SaveAllDevicesToPreference: Failed to unarchive existing devices: %@"
+ "SideToSide"
+ "SkipAccessoryUIDMatching"
+ "T@\"NSString\",R,C,N,V_deviceIdentifier"
+ "T^{__CFRunLoopSource=},R,N,V_runLoopSource"
+ "T^{__CFUserNotification=},R,N,V_notification"
+ "UpAndDown"
+ "^{__CFRunLoopSource=}"
+ "^{__CFRunLoopSource=}16@0:8"
+ "^{__CFUserNotification=}16@0:8"
+ "_deviceIdentifier"
+ "_dismissPendingBobbleAlert"
+ "_fileRadarForDevice:"
+ "_handleBobbleAlertResponseForNotification:flags:"
+ "_logPropertyChangesFrom:to:"
+ "_notification"
+ "_pendingBobbleAlert"
+ "_runLoopSource"
+ "_showBobbleTurnedOffNotificationForDevice:"
+ "acceptReplyPlayPauseConfig changed for device: %@, from: %s, to: %s"
+ "addEntriesFromDictionary:"
+ "audiogramEnrolledTimestamp changed for device: %@, from: %@, to: %@"
+ "btAddressFromBtIdentifier:"
+ "chargingReminderEnabled changed for device: %@, from: %s, to: %s"
+ "declineDismissSkipConfig changed for device: %@, from: %s, to: %s"
+ "healthKitDataWriteAllowed changed for device: %@, from: %s, to: %s"
+ "heartRateMonitorCapability changed for device: %@, from: %s, to: %s"
+ "initWithNotification:runLoopSource:deviceIdentifier:"
+ "listeningModeOffAllowed changed for device: %@, from: %s, to: %s"
+ "remoteCameraControlConfig changed for device: %@, from: %s, to: %s"
+ "runLoopSource"
+ "sharedDiagnosticsMonitor"
+ "v32@0:8^{__CFUserNotification=}16Q24"
- "IsSRConnectEligible: allowing low activity iPhone source to connect to Wx %@ which has no source connected and out of case > 5s"
- "IsSRConnectEligible: skip, iPhone source activity low and Wx already connected to a source, Wx %@"
- "IsSRConnectEligible: skip, low activity iPhone source but Wx %@ out of case <= 5s"
- "Received write sensor data message with %ld bytes"
- "Write = %s Reader = %s"
- "currentReaderConfiguration"
- "currentWriterConfiguration"
```
