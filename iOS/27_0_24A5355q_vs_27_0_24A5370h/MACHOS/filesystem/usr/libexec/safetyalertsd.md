## safetyalertsd

> `/usr/libexec/safetyalertsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfec2c` | `0xfdd38` | **`-0xef4`** |
| `__DATA_CONST.__cfstring` | `0x7440` | `0x72c0` | **`-0x180`** |
| `__DATA_CONST.__const` | `0x8b58` | `0x89d8` | **`-0x180`** |
| `__TEXT.__oslogstring` | `0x433ae` | `0x432c5` | **`-0xe9`** |
| `__TEXT.__unwind_info` | `0x4450` | `0x43b0` | **`-0xa0`** |
| `__TEXT.__cstring` | `0x79cc` | `0x7a52` | **`+0x86`** |
| `__TEXT.__objc_stubs` | `0x36e0` | `0x3760` | **`+0x80`** |
| `__TEXT.__const` | `0x9800` | `0x9870` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0xef28` | `0xeed4` | **`-0x54`** |
| `__TEXT.__objc_methname` | `0x3e19` | `0x3e58` | **`+0x3f`** |
| `__DATA.__objc_selrefs` | `0x1240` | `0x1260` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x5d8` | `0x5b8` | **`-0x20`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-70.0.15.0.0
+70.0.17.0.0

-  Functions: 3640
-  Symbols:   474
+  Functions: 3602
+  Symbols:   470
Symbols:
+ _OBJC_CLASS_$_NSPropertyListSerialization
- _OBJC_CLASS_$_RTStoredVisitFetchOptions
- _RTVisitConfidenceHigh
- _kAppleSafetyAlert_Earthquake_Info_Key
- _kAppleSafetyAlert_Earthquake_UniqueID_Key
- _kAppleSafetyAlert_Trigger_Earthquake_Key
CStrings:
+ "URLByAppendingPathComponent:"
+ "alreadySubmittedThisPeriod"
+ "apsd_biome_collection.plist"
+ "biomeFinished"
+ "biomeStarted"
+ "bleFinished"
+ "bleStarted"
+ "com.apple.safetyalerts.efficacyYield"
+ "compare:"
+ "dataWithPropertyList:format:options:error:"
+ "efficacyRunCalled"
+ "efficacyStage"
+ "firstActionTapped"
+ "isLtAvailable"
+ "keysSortedByValueUsingComparator:"
+ "localizedDescription"
+ "locationFinished"
+ "locationStarted"
+ "manifestDownloadFailed"
+ "manifestFinished"
+ "manifestPreconditionFailed"
+ "manifestStarted"
+ "mapletLoadingStatus"
+ "prefetchComplete"
+ "prepareStarted"
+ "q24@?0@\"NSDictionary\"8@\"NSDictionary\"16"
+ "removeObjectsForKeys:"
+ "saUserTappedAction"
+ "sa_dedup.json"
+ "shouldCollect"
+ "subarrayWithRange:"
+ "timeSinceLastSubmissionSeconds"
+ "ts"
+ "userTappedActionType"
+ "userTappedAlertUid"
+ "userTappedOpenInMaps"
+ "writeToURL:options:error:"
+ "{\"msg%{public}.0s\":\"#commonUtils,getDictionaryFromNSData\", \"error\":%{private, location:escape_only}@}"
+ "{\"msg%{public}.0s\":\"#commonUtils,getDictionaryFromNSData\", \"key\":%{private, location:escape_only}@, \"value\":%{private, location:escape_only}@}"
+ "{\"msg%{public}.0s\":\"#commonUtils,getDictionaryFromNSData,null data\"}"
+ "{\"msg%{public}.0s\":\"#daemon,#warning,onSafetyAlertReceived,saAlreadyExistsInHistory\", \"uid\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#daemon,onUserTapped\", \"uid\":%{private, location:escape_only}s, \"action\":%{private}d}"
+ "{\"msg%{public}.0s\":\"#daemon,updateAPSDBiomeCollectionFlag,#warning,group container not available\"}"
+ "{\"msg%{public}.0s\":\"#daemon,updateAPSDBiomeCollectionFlag,#warning,plist serialization failed\", \"file\":%{private, location:escape_only}s, \"error\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#daemon,updateAPSDBiomeCollectionFlag,#warning,write failed\", \"file\":%{private, location:escape_only}s, \"error\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#daemon,updateAPSDBiomeCollectionFlag,wrote\", \"file\":%{private, location:escape_only}s, \"shouldCollect\":%{private}hhd}"
+ "{\"msg%{public}.0s\":\"#daemonInterfaceProd,userTappedAction\", \"uid\":%{private, location:escape_only}s, \"action\":%{private}d}"
+ "{\"msg%{public}.0s\":\"#daemonInterfaceProd,userTappedOnUI\", \"uid\":%{private, location:escape_only}s, \"userTappedTs\":\"%{private}.1f\", \"snapshotCompleteTsSeconds\":\"%{private}.1f\", \"mapletStatus\":%{private}d}"
+ "{\"msg%{public}.0s\":\"#eff,collectEfficacyMetricForAlertType,not capable, skipping\"}"
+ "{\"msg%{public}.0s\":\"#eff,efficacyYield\", \"efficacyStage\":%{public, location:escape_only}s, \"timeSinceLastSubmissionSeconds\":\"%{public}0.1f\"}"
+ "{\"msg%{public}.0s\":\"#rm,#warning,alreadySubmittedThisPeriod\"}"
+ "{\"msg%{public}.0s\":\"#rm,#warning,prepareCoreRoutineDataForMetric,coreRoutineUnavailable\"}"
+ "{\"msg%{public}.0s\":\"#rm,isParticipatingInEfficacyMetrics,not participating\", \"isIPhone\":%{private}hhd}"
+ "{\"msg%{public}.0s\":\"#saRecentAlertDB,loadFromDisk\", \"entries\":%{public}lu}"
+ "{\"msg%{public}.0s\":\"#saRecentAlertDB,loadFromDisk,#warning,deferLoadingTillFirstUnlock\"}"
+ "{\"msg%{public}.0s\":\"#saRecentAlertDB,onFirstUnlock\"}"
+ "{\"msg%{public}.0s\":\"#saRecentAlertDB,store,#warning,skipBeforeFirstUnlock\"}"
+ "{\"msg%{public}.0s\":\"#uimetrics,SAUiDisplayMetricsEntry,postToAnalytics,values\", \"bleAlertID\":%{private, location:escape_only}@, \"isFirstUnlocked\":%{private, location:escape_only}@, \"isInLOI\":%{sensitive, location:escape_only}@, \"isLocked\":%{private, location:escape_only}@, \"transport\":%{private, location:escape_only}@, \"userTapped\":%{private, location:escape_only}@, \"postToTapLatency\":%{private, location:escape_only}@, \"serverToPostingLatency\":%{private, location:escape_only}@, \"tapToDisplayLatency\":%{private, location:escape_only}@, \"serverToTapLatency\":%{private, location:escape_only}@, \"isLockedDuringPosting\":%{private, location:escape_only}@, \"isLockedDuringSubmission\":%{private, location:escape_only}@, \"isRelayedAlert\":%{private, location:escape_only}@, \"level\":%{private, location:escape_only}@, \"isActionAlert\":%{private}hhd, \"alertType\":%{private}d, \"userTappedOpenInMaps\":%{private}hhd, \"firstActionTapped\":%{private}d, \"mapletLoadingStatus\":%{private}d, \"environmentId\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#uimetrics,setActionTapped,firstAction\", \"action\":%{private}d}"
+ "{\"msg%{public}.0s\":\"#uimetrics,setActionTapped,invokedOnUninitializedObject\"}"
+ "{\"msg%{public}.0s\":\"#uimetrics,setActionTapped,openInMaps\"}"
+ "{\"msg%{public}.0s\":\"#uimetrics,setMapletLoadingStatus\", \"status\":%{private}d}"
+ "{\"msg%{public}.0s\":\"#uimetrics,setMapletLoadingStatus,alreadySet,ignored\", \"status\":%{private}d}"
+ "{\"msg%{public}.0s\":\"#uimetrics,setMapletLoadingStatus,invokedOnUninitializedObject\"}"
- "APSDBiomeCollectionEnabled"
- "Advanced Earthquake Alert"
- "AlertConfiguration"
- "AlertType"
- "AppleSafetyAlert_IgneousAlertLevel"
- "CellularDataEnabled"
- "EnabledByDefault"
- "FollowUp"
- "NotificationTitle"
- "PhoneCallIsActive"
- "Sound"
- "SoundAlertDeviceInMute"
- "SwitchName"
- "UserConfigurable"
- "Vibration"
- "cbs_local_earthquake_us.caf"
- "cbs_local_earthquake_us_action.caf"
- "cbs_vibe_ca.plist"
- "cellDataSwitch"
- "com.apple.Default"
- "fetchStoredVisitsWithOptions:handler:"
- "horizontalUncertainty"
- "initWithAscending:confidence:dateInterval:labelVisit:limit:"
- "kCTSMSCellBroadcastBundleIdentifier"
- "kCTSMSCellBroadcastString"
- "{\"msg%{public}.0s\":\"#Wifi,stopMonitoring\"}"
- "{\"msg%{public}.0s\":\"#commonUtils,convertStringToDictionary\", \"error\":%{private, location:escape_only}@}"
- "{\"msg%{public}.0s\":\"#commonUtils,convertStringToDictionary\", \"key\":%{private, location:escape_only}@, \"value\":%{private, location:escape_only}@}"
- "{\"msg%{public}.0s\":\"#commonUtils,convertStringToDictionary,null data\"}"
- "{\"msg%{public}.0s\":\"#coreRoutine,Test,fetchVisits\"}"
- "{\"msg%{public}.0s\":\"#coreRoutine,fetchVisits\", \"startTimestamp\":%{private}d, \"endTimestamp\":%{private}d}"
- "{\"msg%{public}.0s\":\"#coreRoutine,fetchVisits\"}"
- "{\"msg%{public}.0s\":\"#coreRoutine,fetchVisits,callback not init\"}"
- "{\"msg%{public}.0s\":\"#coreRoutine,fetchVisits,cb\", \"error\":%{private, location:escape_only}@}"
- "{\"msg%{public}.0s\":\"#coreRoutine,fetchVisits,cb\", \"visistsSize\":%{private}d}"
- "{\"msg%{public}.0s\":\"#coreRoutine,fetchVisits,uninitialized\"}"
- "{\"msg%{public}.0s\":\"#coreRoutine,onHistoricalVisitsReceived\", \"lat\":\"%{sensitive}0.1f\", \"lon\":\"%{sensitive}0.1f\", \"hunc\":\"%{private}0.1f\"}"
- "{\"msg%{public}.0s\":\"#ctsa,Igneous,didFailWithError\", \"errordomain\":%{public}d, \"error\":%{public}d, \"rootDict\":%{private, location:escape_only}@, \"infoDictMain\":%{private, location:escape_only}@}"
- "{\"msg%{public}.0s\":\"#ctsa,cellularWatchOrPhone\"}"
- "{\"msg%{public}.0s\":\"#ctsa,displayIgneousBleAlert invalid data\"}"
- "{\"msg%{public}.0s\":\"#ctsa,displayIgneousBleAlert sent successfully \"}"
- "{\"msg%{public}.0s\":\"#ctsa,displayIgneousBleAlert\", \"rootDict\":%{private, location:escape_only}@}"
- "{\"msg%{public}.0s\":\"#ctsa,displayIgneousBleAlert,infoDict invalid\"}"
- "{\"msg%{public}.0s\":\"#ctsa,displayIgneousBleAlert,infoDictList invalid\"}"
- "{\"msg%{public}.0s\":\"#ctsa,displayIgneousBleAlert,item1 invalid\"}"
- "{\"msg%{public}.0s\":\"#ctsa,displayIgneousBleAlert,item2 invalid\"}"
- "{\"msg%{public}.0s\":\"#ctsa,infoDictMain invalid\"}"
- "{\"msg%{public}.0s\":\"#ctsa,onCompanionNearby\", \"Companion\":%{public}d}"
- "{\"msg%{public}.0s\":\"#ctsa,onLocationChanged\"}"
- "{\"msg%{public}.0s\":\"#ctsa,preparedForCT\", \"emgAlertNotif\":%{private, location:escape_only}@}"
- "{\"msg%{public}.0s\":\"#ctsa,rootDict invalid\"}"
- "{\"msg%{public}.0s\":\"#ctsa,sendIgneousFollowUpAlert sent successfully \"}"
- "{\"msg%{public}.0s\":\"#ctsa,sendIgneousFollowUpAlert\", \"rootDict\":%{private, location:escape_only}@}"
- "{\"msg%{public}.0s\":\"#ctsa,sendIgneousFollowUpAlert,infoDict invalid\"}"
- "{\"msg%{public}.0s\":\"#ctsa,sendIgneousFollowUpAlert,infoDictList invalid\"}"
- "{\"msg%{public}.0s\":\"#ctsa,sendIgneousFollowUpAlert,item1 invalid\"}"
- "{\"msg%{public}.0s\":\"#ctsa,sendIgneousFollowUpAlert,item2 invalid\"}"
- "{\"msg%{public}.0s\":\"#ctsa,wifiOnlyWatch\"}"
- "{\"msg%{public}.0s\":\"#daemonInterfaceProd,userTappedOnUI\", \"uid\":%{private, location:escape_only}s, \"userTappedTs\":\"%{private}.1f\", \"snapshotCompleteTsSeconds\":\"%{private}.1f\"}"
- "{\"msg%{public}.0s\":\"#saBiomeProd,CellularDataStatus\", \"timestamp\":\"%{private}0.1f\", \"isStarting\":%{public}hhd}"
- "{\"msg%{public}.0s\":\"#saBiomeProd,fetch,CellularDataComplete\", \"cellDataLen\":%{private}d}"
- "{\"msg%{public}.0s\":\"#saSettingsProd,onLocationChanged\", \"isNearby\":%{public}d}"
- "{\"msg%{public}.0s\":\"#saSettingsProd,onLocationChanged\"}"
- "{\"msg%{public}.0s\":\"#uimetrics,SAUiDisplayMetricsEntry,postToAnalytics,values\", \"bleAlertID\":%{private, location:escape_only}@, \"isFirstUnlocked\":%{private, location:escape_only}@, \"isInLOI\":%{sensitive, location:escape_only}@, \"isLocked\":%{private, location:escape_only}@, \"transport\":%{private, location:escape_only}@, \"userTapped\":%{private, location:escape_only}@, \"postToTapLatency\":%{private, location:escape_only}@, \"serverToPostingLatency\":%{private, location:escape_only}@, \"tapToDisplayLatency\":%{private, location:escape_only}@, \"serverToTapLatency\":%{private, location:escape_only}@, \"isLockedDuringPosting\":%{private, location:escape_only}@, \"isLockedDuringSubmission\":%{private, location:escape_only}@, \"isRelayedAlert\":%{private, location:escape_only}@, \"level\":%{private, location:escape_only}@, \"isActionAlert\":%{private}hhd, \"alertType\":%{private}d, \"environmentId\":%{private, location:escape_only}s}"
```
