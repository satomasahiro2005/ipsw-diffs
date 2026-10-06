## anomalydetectiond

> `/usr/libexec/anomalydetectiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x37ab00` | `0x37b6a8` | **`+0xba8`** |
| `__TEXT.__gcc_except_tab` | `0x10b40` | `0x10c48` | **`+0x108`** |
| `__TEXT.__objc_methtype` | `0x60f4` | `0x61dc` | **`+0xe8`** |
| `__TEXT.__cstring` | `0x1cbed` | `0x1cc93` | **`+0xa6`** |
| `__DATA_CONST.__cfstring` | `0x6a00` | `0x6aa0` | **`+0xa0`** |
| `__DATA.__objc_const` | `0x10760` | `0x107c0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0xc275` | `0xc2b8` | **`+0x43`** |
| `__TEXT.__unwind_info` | `0xca60` | `0xcaa0` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x1850` | `0x1860` | **`+0x10`** |
| `__TEXT.__const` | `0xfff6` | `0x10006` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x950` | `0x95c` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0xc40` | `0xc48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`

### Other Changes

```diff

-175.0.2.0.0
+175.0.4.0.0

-  Functions: 17329
-  Symbols:   609
-  CStrings:  9427
+  Functions: 17340
+  Symbols:   610
+  CStrings:  9438
Symbols:
+ __ZN6motion2fm6ClientC1ENSt3__16vectorINS2_12basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEENS7_IS9_EEEES9_iS9_PU28objcproto17OS_dispatch_queue8NSObject
+ _getpid
- __ZN6motion2fm6ClientC1EPU28objcproto17OS_dispatch_queue8NSObject
CStrings:
+ "AHStateAtDetection"
+ "AHStateAtEscalation"
+ "AHStateAtSessionStart"
+ "AHStateChangePreTrigger"
+ "AHStateMajority"
+ "[3I]"
+ "_ahEpochStateCounts"
+ "_ahStateAtCrashPending"
+ "_lastCrashTimestampSeen"
+ "com.apple.coremotion.crashdetection"
+ "com.apple.fm.motionanomalyfm.adapter"
+ "com.coremotion.anomalyfm.ctl.queue"
+ "v216@0:8{KappaSessionDetails=fCiiiiiiiiifffiiiiiiiiiiiiiiiiiiBiQQQBBBBqIiiiii}16"
+ "{KappaSessionDetails=\"serverConfigVersion\"f\"trigger_bitmap\"C\"numPlanarCrashes\"i\"numRolloverCrashes\"i\"numHighSpeedCrashes\"i\"numDeescalations\"i\"epochsWithStiction\"i\"epochsWithoutStiction\"i\"epochsWithInsufficientHGForStiction\"i\"maxDeltaVXYBiggestImpact\"i\"maxDeltaVXYOverEpoch\"i\"coarseLat\"f\"coarseLong\"f\"sunElevation\"f\"signalEnvironment\"i\"gpsCount\"i\"numDeescalationStatic\"i\"numDeescalationMoving\"i\"numDeescalationSteps\"i\"numDeescalationQuiescence\"i\"numDeescalationAutocorrelation\"i\"numDeescalationTriggerCluster\"i\"numDeescalationSkiingBaroAndAudio\"i\"numDeescalationSkiLift\"i\"numDeescalationUsha\"i\"numDeescalationAOI\"i\"numDeescalationTwoLevel\"i\"numDeescalationDistToRoad\"i\"numDeescalationMAP\"i\"numDeescalationJointDetection\"i\"numDeescalationCrashClassifier\"i\"numInertDeescalationCrashClassifier\"i\"latchedHighSpeedCrash\"B\"numSevereCrashes\"i\"severeCrashAOPTimestamp\"Q\"algsEndTimestamp\"Q\"crashTimestamp\"Q\"lendCompanionPunchThru\"B\"retractCompanionPunchThru\"B\"lowSenseCrashDetected\"B\"highSenseCrashDetected\"B\"ttrType\"q\"deescalationBitmap\"I\"ahStateAtSessionStart\"i\"ahStateAtDetection\"i\"ahStateAtEscalation\"i\"ahStateChangePreTrigger\"i\"ahStateMajority\"i}"
+ "{KappaSessionInfo=\"detectionDecision\"B\"isCompanionConnected\"B\"didCompanionTrigger\"B\"companionDetectionDecision\"B\"trigger_bitmap\"i\"drivingTimeStartToFirstTrigger\"i\"sessionStartTimestamp\"d\"sessionDuration\"i\"gpsDuration\"i\"numTriggers\"i\"numPlanarCrashes\"i\"numRolloverCrashes\"i\"numHighSpeedCrashes\"i\"numDeescalations\"i\"epochsWithStiction\"i\"epochsWithoutStiction\"i\"epochsWithInsufficientHGForStiction\"i\"coarseLat\"f\"coarseLong\"f\"sunElevation\"f\"signalEnvironment\"i\"maxDeltaVXYBiggestImpact\"i\"maxDeltaVXYOverEpoch\"i\"serverConfigVersion\"f\"didRaiseUI\"B\"didRaiseUI_companion\"B\"didCancelUI\"B\"didCancelUI_companion\"B\"isSOSResponseSuccess\"B\"isSOSResponseSuccessPushedToCompanion\"B\"isSOSResponseAlreadyActive\"B\"isSOSResponseFailed\"B\"isSOSResponseNotSupported\"B\"isSOSResponseNotEnabled\"B\"isSOSUserInitiated\"B\"isSOSAutoInitiated\"B\"didPlaceCall\"B\"isMicBlockedDuringEscalations\"B\"outgoingCallTimestamp\"Q\"deescalationBitmap\"I\"ahStateAtSessionStart\"i\"ahStateAtDetection\"i\"ahStateAtEscalation\"i\"ahStateChangePreTrigger\"i\"ahStateMajority\"i}"
- "com.coremotion.imufoundationmodel.ctl.queue"
- "v200@0:8{KappaSessionDetails=fCiiiiiiiiifffiiiiiiiiiiiiiiiiiiBiQQQBBBBqI}16"
- "{KappaSessionDetails=\"serverConfigVersion\"f\"trigger_bitmap\"C\"numPlanarCrashes\"i\"numRolloverCrashes\"i\"numHighSpeedCrashes\"i\"numDeescalations\"i\"epochsWithStiction\"i\"epochsWithoutStiction\"i\"epochsWithInsufficientHGForStiction\"i\"maxDeltaVXYBiggestImpact\"i\"maxDeltaVXYOverEpoch\"i\"coarseLat\"f\"coarseLong\"f\"sunElevation\"f\"signalEnvironment\"i\"gpsCount\"i\"numDeescalationStatic\"i\"numDeescalationMoving\"i\"numDeescalationSteps\"i\"numDeescalationQuiescence\"i\"numDeescalationAutocorrelation\"i\"numDeescalationTriggerCluster\"i\"numDeescalationSkiingBaroAndAudio\"i\"numDeescalationSkiLift\"i\"numDeescalationUsha\"i\"numDeescalationAOI\"i\"numDeescalationTwoLevel\"i\"numDeescalationDistToRoad\"i\"numDeescalationMAP\"i\"numDeescalationJointDetection\"i\"numDeescalationCrashClassifier\"i\"numInertDeescalationCrashClassifier\"i\"latchedHighSpeedCrash\"B\"numSevereCrashes\"i\"severeCrashAOPTimestamp\"Q\"algsEndTimestamp\"Q\"crashTimestamp\"Q\"lendCompanionPunchThru\"B\"retractCompanionPunchThru\"B\"lowSenseCrashDetected\"B\"highSenseCrashDetected\"B\"ttrType\"q\"deescalationBitmap\"I}"
- "{KappaSessionInfo=\"detectionDecision\"B\"isCompanionConnected\"B\"didCompanionTrigger\"B\"companionDetectionDecision\"B\"trigger_bitmap\"i\"drivingTimeStartToFirstTrigger\"i\"sessionStartTimestamp\"d\"sessionDuration\"i\"gpsDuration\"i\"numTriggers\"i\"numPlanarCrashes\"i\"numRolloverCrashes\"i\"numHighSpeedCrashes\"i\"numDeescalations\"i\"epochsWithStiction\"i\"epochsWithoutStiction\"i\"epochsWithInsufficientHGForStiction\"i\"coarseLat\"f\"coarseLong\"f\"sunElevation\"f\"signalEnvironment\"i\"maxDeltaVXYBiggestImpact\"i\"maxDeltaVXYOverEpoch\"i\"serverConfigVersion\"f\"didRaiseUI\"B\"didRaiseUI_companion\"B\"didCancelUI\"B\"didCancelUI_companion\"B\"isSOSResponseSuccess\"B\"isSOSResponseSuccessPushedToCompanion\"B\"isSOSResponseAlreadyActive\"B\"isSOSResponseFailed\"B\"isSOSResponseNotSupported\"B\"isSOSResponseNotEnabled\"B\"isSOSUserInitiated\"B\"isSOSAutoInitiated\"B\"didPlaceCall\"B\"isMicBlockedDuringEscalations\"B\"outgoingCallTimestamp\"Q\"deescalationBitmap\"I}"
```
