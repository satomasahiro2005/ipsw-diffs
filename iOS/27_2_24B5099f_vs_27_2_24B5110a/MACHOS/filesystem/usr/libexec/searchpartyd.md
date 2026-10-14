## searchpartyd

> `/usr/libexec/searchpartyd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19b9f2c` | `0x19dd388` | **`+0x2345c`** |
| `__TEXT.__eh_frame` | `0xff734` | `0x101c1c` | **`+0x24e8`** |
| `__TEXT.__oslogstring` | `0x5193e` | `0x5219e` | **`+0x860`** |
| `__DATA_CONST.__const` | `0x74210` | `0x74920` | **`+0x710`** |
| `__DATA.__bss` | `0xb3a80` | `0xb4180` | **`+0x700`** |
| `__TEXT.__const` | `0x9afc8` | `0x9b628` | **`+0x660`** |
| `__TEXT.__unwind_info` | `0x4c820` | `0x4ccd8` | **`+0x4b8`** |
| `__DATA.__data` | `0x458d0` | `0x45c20` | **`+0x350`** |
| `__TEXT.__cstring` | `0x33a2c` | `0x33d6c` | **`+0x340`** |
| `__TEXT.__swift_as_cont` | `0xe7dc` | `0xea38` | **`+0x25c`** |
| `__TEXT.__constg_swiftt` | `0x23828` | `0x23a50` | **`+0x228`** |
| `__TEXT.__swift5_capture` | `0x1afc4` | `0x1b1d4` | **`+0x210`** |
| `__TEXT.__swift5_reflstr` | `0x27281` | `0x27481` | **`+0x200`** |
| `__TEXT.__swift_as_ret` | `0x8308` | `0x847c` | **`+0x174`** |
| `__TEXT.__swift5_fieldmd` | `0x2849c` | `0x2860c` | **`+0x170`** |
| `__TEXT.__objc_methname` | `0x1aa48` | `0x1ab88` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0x25c53` | `0x25d93` | **`+0x140`** |
| `__TEXT.__auth_stubs` | `0x9f10` | `0xa010` | **`+0x100`** |
| `__DATA.__objc_const` | `0x1f7b0` | `0x1f8a0` | **`+0xf0`** |
| `__DATA_CONST.__got` | `0x3db8` | `0x3e78` | **`+0xc0`** |
| `__TEXT.__swift_as_entry` | `0x3e54` | `0x3ee8` | **`+0x94`** |
| `__DATA_CONST.__auth_got` | `0x4f90` | `0x5010` | **`+0x80`** |
| `__TEXT.__objc_methtype` | `0x5d3e` | `0x5dbe` | **`+0x80`** |
| `__DATA.__objc_data` | `0x47a0` | `0x47f0` | **`+0x50`** |
| `__DATA_CONST.__auth_ptr` | `0x4db0` | `0x4df0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x4aec` | `0x4b2c` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x8620` | `0x8660` | **`+0x40`** |
| `__TEXT.__swift5_proto` | `0x5e18` | `0x5e50` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x3948` | `0x3968` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x2e28` | `0x2e40` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x213c` | `0x2154` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x974` | `0x988` | **`+0x14`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-449.31.6.16.25
+449.31.6.16.29

-  Functions: 69263
-  Symbols:   5123
-  CStrings:  14445
+  Functions: 69643
+  Symbols:   5162
+  CStrings:  14515
Symbols:
+ _$s10AppIntents0A17NotificationEventV0D4TypeO7createdyA2EmFWC
+ _$s10AppIntents0A17NotificationEventV0D4TypeO7deletedyA2EmFWC
+ _$s10AppIntents0A17NotificationEventV0D4TypeO7updatedyA2EmFWC
+ _$s10AppIntents0A17NotificationEventV0D4TypeOMa
+ _$s10AppIntents0A17NotificationEventV0D4TypeOMn
+ _$s10AppIntents0A17NotificationEventV0D4TypeOSHAAMc
+ _$s10AppIntents0A17NotificationEventV0D4TypeOSQAAMc
+ _$s10AppIntents0A17NotificationEventV4sendyyF
+ _$s10AppIntents0A17NotificationEventVMa
+ _$s10AppIntents0A17NotificationEventVMn
+ _$s10AppIntents0A6EntityPAAE10isObservedSbyYaKFZ
+ _$s10AppIntents0A6EntityPAAE10isObservedSbyYaKFZTu
+ _$s10AppIntents0A6EntityPAAE17notificationEvent3for11identifiersAA0a12NotificationE0VAH0E4TypeO_Say2IDQzGtFZ
+ _$s10AppIntents0A6EntityPAAE17onObservedChangedAA0A28EventObservationStatusStream_pyYaKFZ
+ _$s10AppIntents0A6EntityPAAE17onObservedChangedAA0A28EventObservationStatusStream_pyYaKFZTu
+ _$s10FindMyBase8XPCAlarmV10identifier8criteriaACSS_AC8CriteriaVtYacfC
+ _$s10FindMyBase8XPCAlarmV10identifier8criteriaACSS_AC8CriteriaVtYacfCTu
+ _$s10FindMyBase8XPCAlarmV10unregister10identifierySS_tFZ
+ _$s10FindMyBase8XPCAlarmV8CriteriaV4date7optionsAE10Foundation4DateV_AE7OptionsVtcfC
+ _$s10FindMyBase8XPCAlarmV8CriteriaV7OptionsVMa
+ _$s10FindMyBase8XPCAlarmV8CriteriaV7OptionsVMn
+ _$s10FindMyBase8XPCAlarmV8CriteriaV7OptionsVs10SetAlgebraAAMc
+ _$s10FindMyBase8XPCAlarmV8CriteriaVMa
+ _$s10FindMyBase8XPCAlarmVMa
+ _$s15FindMyBluetooth14CharacteristicC6notifyScsy10Foundation4DataVs5Error_pGyYaKFTjTu
+ _$s16SPMirrorEntities25IntentSessionEntityMirrorO012ItemLocationE0V10AppIntents0iE0AAMc
+ _$s16SPMirrorEntities25IntentSessionEntityMirrorO012ItemLocationE0VMa
+ _$s16SPMirrorEntities25IntentSessionEntityMirrorO04ItemE0V10AppIntents0hE0AAMc
+ _$s19FindMyDaemonSupport0C0C20xpcAlarmEventHandlerAA08XPCAlarmgH0CSgvg
+ _$s19FindMyDaemonSupport20XPCAlarmEventHandlerC11asyncStream4nameScSySSGSS_tYaFTjTu
+ _$s19FindMyDaemonSupport20XPCAlarmEventHandlerC18addEventsToProcess4withySaySSG_tYaFTjTu
+ _$s7ElementScITl
+ _$s7FailureScITl
+ _$sSa10AppIntentsAA0A17NotificationEventVRszlE4sendyyF
+ _$sScI7FailureScI_s5ErrorTn
+ _$sScITL
+ _$sSo22SPAccessoryMotionStateV7SPOwnerE11descriptionSSvg
+ _OBJC_CLASS_$_SPFindingSessionEvent
+ _SPBeaconTaskNameBTChannelSounding
CStrings:
+ " previous "
+ "%s - %ld sessions. Remaining: %ld."
+ "%s - alarm already armed; skipping re-arm."
+ "%s - armed for %fs."
+ "%s - skipping alarm arm: no event-stream handler bound. Arming would cause UEA to hold a 30s PreventUserIdleSystemSleep assertion per fire until it times out."
+ "%s - xpcAlarmEventHandler is nil; alarm fires will not be acked."
+ "%s [%{public}s] - observers: %{public}s, sessions: %ld, wasArmed: %{bool}d."
+ "%s completed - alarm cleared."
+ "%s for %ld beacons."
+ "%{public}s: %{public}ld missing, %{public}ld stale, of %{public}ld item entities"
+ ".btChannelSounding"
+ ".disableBTCSReflector"
+ ".disableReflector"
+ ".enableBTCSReflector"
+ ".enableReflector"
+ ".motionIndication"
+ "Alarm fired - re-checking observers."
+ "Cancelled all location streams - intent session is no longer active."
+ "Cannot unregister subcriptions while sessionExpired: %{bool}d,         observedEntities: %{public}s."
+ "Device list key moved from %{private,mask.hash}s to %{private,mask.hash}s."
+ "Disconnected from %{private,mask.hash}s"
+ "Error observing device entities: %{public}@."
+ "Error observing location entities: %{public}@."
+ "Failed to read ItemEntity subscriptions: %{public}@."
+ "Failed to read ItemLocationEntity subscriptions: %{public}@."
+ "Failed to register location fetch subscriptions."
+ "IntentSessionEnabled"
+ "Keeping location streams while connections are active."
+ "Session expiry task completed."
+ "Session expiry task scheduled."
+ "Skipping location fetch upgrade: all sessions are deviceList."
+ "Started intent location stream"
+ "alarmEventHandlerBound"
+ "alarmEventTask"
+ "alarmFireDate"
+ "beaconIdentifiers: %s"
+ "btChannelSounding"
+ "com.apple.searchpartyd.IntentSessionAlarm"
+ "deviceObservedMonitorTask"
+ "deviceObserverChanged"
+ "expireSessions()"
+ "hasActiveAppIntentsObservers"
+ "initWithBeaconID:event:peripheralID:motionState:"
+ "locationObservedMonitorTask"
+ "locationObserverChanged"
+ "locationSubscriptionTask"
+ "locationUpdateContext"
+ "monitorEntityObservers()"
+ "postBeaconEntitiesChangedSinceLastSubscription()"
+ "postLocationEntitiesChanged(beaconIdentifiers:)"
+ "recomputeSubscriptions(reason:)"
+ "registerSessionRefresh()"
+ "sendDisableBTCSReflectorCommand(for:)"
+ "sendEnableBTCSReflectorCommand(for:)"
+ "sessionExpiryTask"
+ "startBTCS for beacon %{private,mask.hash}s"
+ "startBTCS for beacon %{private,mask.hash}s error: %{public}@"
+ "startBTCS:completion:"
+ "stopBTCS for beacon %{private,mask.hash}s"
+ "stopBTCS for beacon %{private,mask.hash}s error: %{public}@"
+ "stopBTCS:completion:"
+ "subscribeToAlarmEvents()"
+ "subscribeToMotionUpdateIndications: Updates failed with: %@"
+ "subscribeToMotionUpdateIndications: failed to decode command: %@"
+ "subscribeToMotionUpdateIndications: ignoring indication for opcode: %s"
+ "subscribeToMotionUpdateIndications: no macAddress provided"
+ "subscribeToMotionUpdateIndications: rawResponse is empty or part of a chain of responses, ignoring"
+ "unregisterSubscriptionsIfRequired()"
+ "unregistersubscriptions()"
+ "updateAccessoryEvent:"
+ "updateMotionActivityState: beaconID %{private,mask.hash}s updated state: %s"
+ "updateMotionActivityState: returning, beaconID is not in the beaconsToScan list."
+ "v24@0:8@\"SPFindingSessionEvent\"16"
- "%{public}s: %{public}ld of %{public}ld item entities missing, repairing"
- "Disconnected from %{private,mask.hash}s, error: %{public}@"
- "Disconnected from %{public}s, error: %{public}@"
```
