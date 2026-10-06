## AccessoryInteraction

> `/System/Library/PrivateFrameworks/AccessoryInteraction.framework/AccessoryInteraction`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x91b3c` | `0x923c4` | **`+0x888`** |
| `__AUTH_CONST.__objc_const` | `0xba50` | `0xbc38` | **`+0x1e8`** |
| `__AUTH.__objc_data` | `0x1260` | `0x13d0` | **`+0x170`** |
| `__TEXT.__objc_methlist` | `0x6f50` | `0x7010` | **`+0xc0`** |
| `__TEXT.__const` | `0x950` | `0x9f0` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0xb88` | `0xbf8` | **`+0x70`** |
| `__TEXT.__cstring` | `0x7337` | `0x73a7` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x534` | `0x59c` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x2a8a4` | `0x2a906` | **`+0x62`** |
| `__AUTH.__data` | `0x1d0` | `0x220` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x4458` | `0x44a8` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1558` | `0x15a8` | **`+0x50`** |
| `__DATA.__data` | `0xa58` | `0xa88` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x294` | `0x2c0` | **`+0x2c`** |
| `__AUTH_CONST.__cfstring` | `0x7d00` | `0x7d20` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xb00` | `0xb10` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1210` | `0x1220` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x208` | `0x218` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x295` | `0x2a5` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x3d2` | `0x3de` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x6f8` | `0x700` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x34` | `0x3c` | **`+0x8`** |

### Other Changes

```diff

-30.0.0.0.0
+31.0.0.0.0

-  Functions: 2628
-  Symbols:   3684
-  CStrings:  2697
+  Functions: 2660
+  Symbols:   3712
+  CStrings:  2699
Symbols:
+ +[NSError(Additions) _an_ErrorWithANCode:]
+ +[NSError(Additions) _an_ErrorWithANCode:underlyingError:]
+ +[NSError(Additions) _an_ErrorWithDomain:code:localizedDescription:underlyingError:]
+ -[ANConnectionAttempt initWithRequestContext:]
+ -[ANConnectionAttempt requestContext]
+ -[ANDeviceManager attemptConnectToDevice:onCondition:requestContext:]
+ -[ANDeviceManager beaconManager]
+ -[ANDeviceManager handleKeyFetchFailureForDevice:withError:maintReason:maintCategory:]
+ -[ANDeviceManager setBeaconManager:]
+ -[ANDeviceManager setSettings:]
+ -[ANDeviceManager settings]
+ -[ANMetricManager submitFirmwareVersionsForOwnedTag:firmwareVersion:serialNumber:productId:]
+ -[ANSettings firmwareVersionForAllTagsMetricsBackOff]
+ -[ANSettings initWithAccessor:platform:systemUtils:]
+ -[ANSettings lastFirmwareVersionForAllTagsSubmission]
+ -[ANSettings lastTravelingWithAccessoriesMetricsSubmission]
+ -[ANSettings maxPeripheralCountForForcedHeleMaintenance]
+ -[ANSettings setLastFirmwareVersionForAllTagsSubmission:]
+ -[ANSettings setTravelingWithAccessoriesMetricsSubmission:]
+ -[ANSettingsAccessor initWithSystemUtils:userName:]
+ -[ANSystemUtils cfAbsoluteTimeGetCurrent]
+ _ANErrorCodeDescription
+ _ANTriggerAutoBugCapture.onceToken
+ _ANTriggerAutoBugCapture.reporter
+ _OBJC_CLASS_$__TtC20AccessoryInteraction27ANLegacyDefaultsCoordinator
+ _OBJC_CLASS_$__TtC20AccessoryInteraction33ANConnectionAttemptRequestContext
+ _OBJC_IVAR_$_ANConnectionAttempt._requestContext
+ _OBJC_IVAR_$_ANSettings._systemUtils
+ _OBJC_METACLASS_$__TtC20AccessoryInteraction27ANLegacyDefaultsCoordinator
+ _OBJC_METACLASS_$__TtC20AccessoryInteraction33ANConnectionAttemptRequestContext
+ __ANBeaconListChangeDialogResponseHandler
+ __ANCrashDetectedDialogResponseHandler
+ __CLASS_METHODS__TtC20AccessoryInteraction27ANLegacyDefaultsCoordinator
+ __DATA__TtC20AccessoryInteraction27ANLegacyDefaultsCoordinator
+ __DATA__TtC20AccessoryInteraction33ANConnectionAttemptRequestContext
+ __INSTANCE_METHODS__TtC20AccessoryInteraction27ANLegacyDefaultsCoordinator
+ __INSTANCE_METHODS__TtC20AccessoryInteraction33ANConnectionAttemptRequestContext
+ __IVARS__TtC20AccessoryInteraction33ANConnectionAttemptRequestContext
+ __METACLASS_DATA__TtC20AccessoryInteraction27ANLegacyDefaultsCoordinator
+ __METACLASS_DATA__TtC20AccessoryInteraction33ANConnectionAttemptRequestContext
+ __PROPERTIES__TtC20AccessoryInteraction33ANConnectionAttemptRequestContext
+ ___92-[ANMetricManager submitFirmwareVersionsForOwnedTag:firmwareVersion:serialNumber:productId:]_block_invoke
+ ____ANBeaconListChangeDialogResponseHandler_block_invoke
+ ____ANCrashDetectedDialogResponseHandler_block_invoke
+ ___swift_project_boxed_opaque_existential_0
+ __beaconListChangePopupPending
+ __deviceMapLock
+ __deviceNotificationMap
+ __popupLastInteracted
+ __typeNotificationMap
+ _kANErrorDomain
+ _submitBeaconListChangeUserFeedbackEvent
+ _symbolic _____ 20AccessoryInteraction27ANLegacyDefaultsCoordinatorC
+ _symbolic _____ 20AccessoryInteraction33ANConnectionAttemptRequestContextC
- +[ANMetricManager submitFirmwareVersionsForOwnedTag:firmwareVersion:serialNumber:productId:]
- +[ANSettings(ClassProperties_DEPRECATED) firmwareVersionForAllTagsMetricsBackOff]
- +[ANSettings(ClassProperties_DEPRECATED) forceMaintenanceConnectionsOverride]
- +[ANSettings(ClassProperties_DEPRECATED) lastFirmwareVersionForAllTagsSubmission]
- +[ANSettings(ClassProperties_DEPRECATED) lastTravelingWithAccessoriesMetricsSubmission]
- +[ANSettings(ClassProperties_DEPRECATED) setLastFirmwareVersionForAllTagsSubmission:]
- +[ANSettings(ClassProperties_DEPRECATED) setTravelingWithAccessoriesMetricsSubmission:]
- -[ANConnectionAttempt init]
- -[ANDeviceManager attemptConnectToDevice:onCondition:]
- -[ANDeviceManager handleKeyFetchFailureForDevice:withError:]
- -[ANSettings floatForKey:defaultValue:]
- -[ANSettings initWithAccessor:platform:]
- -[ANSettingsAccessor initWithSystemUtils:]
- __ZL14_deviceMapLock
- __ZL20_popupLastInteracted
- __ZL20_typeNotificationMap
- __ZL22_deviceNotificationMap
- __ZL29_beaconListChangePopupPending
- __ZL37_ANCrashDetectedDialogResponseHandlerP20__CFUserNotificationm
- __ZL39submitBeaconListChangeUserFeedbackEventm
- __ZL40_ANBeaconListChangeDialogResponseHandlerP20__CFUserNotificationm
- __ZZ23ANTriggerAutoBugCaptureE8reporter
- __ZZ23ANTriggerAutoBugCaptureE9onceToken
- ___92+[ANMetricManager submitFirmwareVersionsForOwnedTag:firmwareVersion:serialNumber:productId:]_block_invoke
- ____ZL37_ANCrashDetectedDialogResponseHandlerP20__CFUserNotificationm_block_invoke
- ____ZL40_ANBeaconListChangeDialogResponseHandlerP20__CFUserNotificationm_block_invoke
CStrings:
+ "#durian #settings cleanup of stale mobile preferences ran"
+ "#durian #settings migrated CoreAnalyticsSalt90Day from mobile to root"
+ "//private/var/Managed Preferences/mobile/%@.plist"
+ "ANErrorDomain"
+ "AccessoryInteraction.ANConnectionAttemptRequestContext"
+ "DurianMaxPeripheralCountForForcedHeleMaintenance"
+ "LECAHap"
+ "LECAHapLow"
+ "LECATmap"
+ "LECATmapLow"
+ "Too many addresses for forced HELE maintenance"
+ "Unknown ANErrorCode (%ld)"
+ "root"
+ "skip:forcedhelecap"
+ "{\"msg%{public}.0s\":\"#durian #connectattempt skip forced hele maintenance cap exceeded\", \"item\":%{private, location:escape_only}@, \"attemptId\":%{private, location:escape_only}@, \"count\":%{public}d, \"cap\":%{public}d}"
- "#durian #connection no error in handleKeyFetchFailureForDevice:withError:"
- "//private/var/Managed Preferences/%@/%@.plist"
- "DurianForceMaintenanceConnections"
- "FloatKey"
- "LECA1"
- "LECA2"
- "LECA3"
- "LECA4"
- "floatForKey:'FloatKey' default:0"
- "floatForKey:'FloatKey' default:1.125"
- "floatForKey:'FloatKey' default:123456789"
- "mobile"
- "{\"msg%{public}.0s\":\"#durian #connection no error in handleKeyFetchFailureForDevice:withError:\", \"deviceId\":%{private, location:escape_only}@, \"error\":%{private, location:escape_only}@}"
```
