## FindingUI

> `/Applications/FindingUI.app/FindingUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5cc7c` | `0x5fc8c` | **`+0x3010`** |
| `__TEXT.__eh_frame` | `0x41d0` | `0x3370` | **`-0xe60`** |
| `__DATA.__bss` | `0x3590` | `0x3100` | **`-0x490`** |
| `__TEXT.__unwind_info` | `0x16b8` | `0x1440` | **`-0x278`** |
| `__TEXT.__oslogstring` | `0x1a3a` | `0x1c7a` | **`+0x240`** |
| `__TEXT.__cstring` | `0x639` | `0x85a` | **`+0x221`** |
| `__TEXT.__swift5_fieldmd` | `0xbdc` | `0xd94` | **`+0x1b8`** |
| `__TEXT.__objc_methname` | `0x2b7b` | `0x2d2b` | **`+0x1b0`** |
| `__TEXT.__swift5_reflstr` | `0xab9` | `0xc59` | **`+0x1a0`** |
| `__TEXT.__const` | `0x2c14` | `0x2ac4` | **`-0x150`** |
| `__TEXT.__swift_as_cont` | `0x42c` | `0x2f8` | **`-0x134`** |
| `__TEXT.__constg_swiftt` | `0xcbc` | `0xbd8` | **`-0xe4`** |
| `__DATA.__objc_data` | `0x838` | `0x8d8` | **`+0xa0`** |
| `__DATA.__objc_const` | `0x22c0` | `0x2358` | **`+0x98`** |
| `__TEXT.__auth_stubs` | `0x1d10` | `0x1d90` | **`+0x80`** |
| `__TEXT.__swift_as_entry` | `0x170` | `0x100` | **`-0x70`** |
| `__TEXT.__swift_as_ret` | `0x138` | `0xe4` | **`-0x54`** |
| `__DATA_CONST.__auth_got` | `0xe90` | `0xed0` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x13fc` | `0x1434` | **`+0x38`** |
| `__TEXT.__objc_classname` | `0x72e` | `0x6fe` | **`-0x30`** |
| `__TEXT.__swift5_assocty` | `0xa8` | `0xd8` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x530` | `0x558` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x1ac` | `0x188` | **`-0x24`** |
| `__TEXT.__swift5_typeref` | `0x1002` | `0x1026` | **`+0x24`** |
| `__DATA.__data` | `0x24c0` | `0x24e0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1ee0` | `0x1f00` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xce0` | `0xd00` | **`+0x20`** |
| `__DATA.__common` | `0x128` | `0x110` | **`-0x18`** |
| `__TEXT.__swift5_types` | `0xec` | `0xf8` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x860` | `0x868` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0xc0` | `0xb8` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x8` | `—` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-101.30.5.16.1
+103.30.6.7.1

-  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

+  - /System/Library/PrivateFrameworks/AsyncAlgorithmsInternal.framework/AsyncAlgorithmsInternal

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 1391
-  Symbols:   802
-  CStrings:  747
+  Functions: 1336
+  Symbols:   812
+  CStrings:  784
Symbols:
+ _$s10Foundation18IntegerFormatStyleV6localeACyxGAA6LocaleV_tcfC
+ _$s10Foundation18IntegerFormatStyleV6localeyACyxGAA6LocaleVF
+ _$s10Foundation18IntegerFormatStyleV9precisionyACyxGAA06NumbercD13ConfigurationO9PrecisionVF
+ _$s10Foundation18IntegerFormatStyleVMn
+ _$s10Foundation18IntegerFormatStyleVyxGAA0cD0AAMc
+ _$s10Foundation30NumberFormatStyleConfigurationO9PrecisionV13integerLengthyAESiFZ
+ _$s10Foundation30NumberFormatStyleConfigurationO9PrecisionVMa
+ _$s10Foundation4UUIDV2eeoiySbAC_ACtFZ
+ _$s10Foundation6LocaleV10FindMyBaseE11en_US_POSIXACvgZ
+ _$s10Foundation6LocaleV19autoupdatingCurrentACvgZ
+ _$s10Foundation6LocaleVMa
+ _$s11ActivityKit0A0C7endSync_15dismissalPolicyyAA0A7ContentVy0G5StateQzGSg_AA0a11UIDismissalF0VtFTj
+ _$s11ActivityKit0A17UIDismissalPolicyV9immediateACvgZ
+ _$s12FindMyLocate6HandleVs23CustomStringConvertibleAAMc
+ _$s12FindMyLocate7SessionC26addHandlesToLocationStream_8priority14reverseGeocode8clientIDySayAA6HandleVG_AA0C8PriorityOSbAA06ClientN0VtYaKF
+ _$s12FindMyLocate7SessionC26addHandlesToLocationStream_8priority14reverseGeocode8clientIDySayAA6HandleVG_AA0C8PriorityOSbAA06ClientN0VtYaKFTu
+ _$s23AsyncAlgorithmsInternal0A14Merge2SequenceV04makeA8IteratorAC0G0Vyxq__GyF
+ _$s23AsyncAlgorithmsInternal0A14Merge2SequenceV8IteratorV4next7ElementQzSgyYaKF
+ _$s23AsyncAlgorithmsInternal0A14Merge2SequenceV8IteratorV4next7ElementQzSgyYaKFTu
+ _$s23AsyncAlgorithmsInternal0A14Merge2SequenceV8IteratorVMn
+ _$s23AsyncAlgorithmsInternal0A14Merge2SequenceVMn
+ _$s23AsyncAlgorithmsInternal5mergeyAA0A14Merge2SequenceVyxq_Gx_q_ts8SendableRzSciRzsAFR_SciR_sAF7ElementRpzAGQy_AHRSr0_lF
+ _$s9FindingUI0A11DisplayModeO2eeoiySbAC_ACtFZ
+ _$s9FindingUI34PeopleFindableStateRegisterRequestV22isSkippingNearbyChecksSbvg
+ _$s9FindingUI7SessionC06peopleA14NearbyDistance10Foundation11MeasurementVySo12NSUnitLengthCGvgZ
+ _$s9FindingUI7SessionCMa
+ _$sSBss17FixedWidthInteger14RawSignificandRpzrlE8_convert4fromx5value_Sb5exacttqd___tSzRd__lFZ
+ _$sSD10FoundationE19_bridgeToObjectiveCSo12NSDictionaryCyF
+ _$sSa034_makeUniqueAndReserveCapacityIfNotB0yyFyXl_Ts5
+ _$sSa16_createNewBuffer14bufferIsUnique15minimumCapacity13growForAppendySb_SiSbtFyXl_Ts5
+ _$sSa37_appendElementAssumeUniqueAndCapacity_03newB0ySi_xntFyXl_Ts5
+ _$sScS8IteratorVyx_GScIsMc
+ _$sScSyxGScisMc
+ _$sSdN
+ _$sSdSBsMc
+ _$sSiSzsMc
+ _$sSz10FoundationE9formattedy12FormatOutputQyd__qd__0C5InputQyd__RszAA0C5StyleRd__lF
+ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtFyXl_Ts5
+ _$ss15ContinuousClockV7InstantVMn
+ _$ss16AsyncMapSequenceVMn
+ _$ss16AsyncMapSequenceV_9transformAByxq_Gx_q_7ElementQzYactcfC
+ _$ss16AsyncMapSequenceVyxq_GScisMc
+ _$ss19AsyncFilterSequenceV10isIncludedySb7ElementQzYacvg
+ _$ss19AsyncFilterSequenceV4basexvg
+ _$ss19AsyncFilterSequenceV8IteratorV04baseD00aD0QzvM
+ _$ss19AsyncFilterSequenceV8IteratorV10isIncludedySb7ElementQzYacvg
+ _$ss19AsyncFilterSequenceV8IteratorVMn
+ _$ss19AsyncFilterSequenceV8IteratorV_10isIncludedADyx_G0aD0Qz_Sb7ElementQzYactcfC
+ _$ss23AsyncCompactMapSequenceV8IteratorVMn
+ _$ss23AsyncCompactMapSequenceV8IteratorVyxq__GScIsMc
+ _$ss6Int128VN
+ _$ss6Int128VSzsMc
+ _$ss6UInt64VN
+ _$ss6UInt64Vs17FixedWidthIntegersMc
+ _AnalyticsSendEventLazy
+ _OBJC_CLASS_$_BSActionResponder
+ _OBJC_CLASS_$_LSApplicationWorkspace
+ _OBJC_CLASS_$_NSNumber
+ ___divti3
+ _objc_release_x1
+ _swift_asyncLet_get
+ _swift_isUniquelyReferenced_nonNull_bridgeObject
+ _swift_task_deinitOnExecutor
- _$s10FindMyBase10SystemInfoO15isInternalBuildSbvgZ
- _$s10Foundation4DateV3nowACvgZ
- _$s11ActivityKit0A0C3end_15dismissalPolicyyAA0A7ContentVy0F5StateQzGSg_AA0a11UIDismissalE0VtYaFTjTu
- _$s11ActivityKit0A17UIDismissalPolicyV7defaultACvgZ
- _$s11FMFindingUI21FindingViewControllerC21updateSessionDelegateyyFTj
- _$s12FindMyLocate12LocationTypeO4liveyA2CmFWC
- _$s12FindMyLocate12LocationTypeOMa
- _$s12FindMyLocate19MotionActivityStateO7unknownyA2CmFWC
- _$s12FindMyLocate19MotionActivityStateOMa
- _$s12FindMyLocate6HandleV4with10prettyName17contactIdentifier18siblingIdentifiersA2C_S2SSaySSGtcfC
- _$s12FindMyLocate8LocationV8latitude9longitude18horizontalAccuracy08verticalH05speed8altitude5floor9timestamp9placemark12locationType19motionActivityState11customLabelACSd_S5dSi10Foundation4DateVAA9PlaceMarkVSgAA0dP0OAA06MotionrS0OSSSgtcfC
- _$s12FindMyLocate8LocationVSQAAMc
- _$s12FindMyLocate9PlaceMarkVMa
- _$s12FindMyLocate9PlaceMarkVMn
- _$s13AsyncIteratorSciTl
- _$s15Synchronization5MutexVMa
- _$s15Synchronization5_CellVMn
- _$s9FindingUI19EventStreamProviderC5clearyyF
- _$sS2cEycfC
- _$sScEs5ErrorsMc
- _$sScIMp
- _$sScg4next9isolationxSgScA_pSgYi_tYaKF
- _$sScg4next9isolationxSgScA_pSgYi_tYaKFTu
- _$sScg9cancelAllyyF
- _$sSci10FindMyBaseE5first7ElementQzSgyYaKF
- _$sSci10FindMyBaseE5first7ElementQzSgyYaKFTu
- _$sSci13AsyncIteratorSci_ScITn
- _$sSciMp
- _$sSciTL
- _$ss19AsyncFilterSequenceVyxGScisMc
- _$ss21withThrowingTaskGroup2of9returning9isolation4bodyq_xm_q_mScA_pSgYiq_Scgyxs5Error_pGzYaKXEtYaKs8SendableRzr0_lF
- _$ss21withThrowingTaskGroup2of9returning9isolation4bodyq_xm_q_mScA_pSgYiq_Scgyxs5Error_pGzYaKXEtYaKs8SendableRzr0_lFTu
- _$ss24AsyncThrowingMapSequenceVMn
- _$ss24AsyncThrowingMapSequenceV_9transformAByxq_Gx_q_7ElementQzYaKctcfC
- _$ss24AsyncThrowingMapSequenceVyxq_GScisMc
- _$ss31AsyncThrowingCompactMapSequenceVMn
- _$ss31AsyncThrowingCompactMapSequenceV_9transformAByxq_Gx_q_Sg7ElementQzYaKctcfC
- _$ss31AsyncThrowingCompactMapSequenceVyxq_GScisMc
- _$ss5ErrorP10FindMyBaseE4codeSivg
- _$ss5ErrorP10FindMyBaseE6domainSSvg
- _$ss8DurationV7secondsyABSdFZ
- _OBJC_CLASS_$_NSError
- _OBJC_CLASS_$_NSUserDefaults
- _objc_retain_x28
- _swift_dynamicCastMetatype
- _swift_getAssociatedConformanceWitness
- _swift_getAssociatedTypeWitness
- _swift_getDynamicType
- _swift_getTupleTypeMetadata2
- _swift_makeBoxUnique
- _swift_release_x10
- _swift_task_isCancelledWithFlags
- _swift_unknownObjectRetain_n
CStrings:
+ "%s removed"
+ "@\"NSDictionary\"8@?0"
+ "Can't unsubscribe, missing friend location service"
+ "Discovery token for %s took %s"
+ "Dismissing without a window scene"
+ "Failed to create friend location service"
+ "Failed to create friend location service: %s"
+ "Failed to remove %s from stream: %s"
+ "Failed to subscribe to %s: %s"
+ "FindingUIAngel/FindablePersonSubscription.swift"
+ "FindingUIAngel/FriendLocationService.swift"
+ "FindingUIAngel/PersonFindingActivity.swift"
+ "FindingUIAngel/PersonFindingSession.swift"
+ "FindingUIAngel/PresentationService.swift"
+ "Friend is not available"
+ "FriendLocationMonitor failed to stop refreshing: %s"
+ "FriendLocationService deinit"
+ "Incoming request from %s failed with error: %@"
+ "Invalidating connection from %d @ %s"
+ "Missing handle ID for %s"
+ "New connection from %s"
+ "New subscriber, current state: %s"
+ "New subscriber, current state: %s - skipping nearby checks"
+ "No active finding session to dismiss"
+ "No connection found for %s, unsubscribing…"
+ "No corresponding subscription for %s"
+ "Not returning to Find My"
+ "Removing %s from stream"
+ "Returning to Find My"
+ "Send failed: No connection for %s"
+ "Subscribing to location of %s"
+ "Subscription for %s already unsubscribed (empty)"
+ "Subscription for %s already unsubscribed (no index)"
+ "Subscription for %s is not being unsubscribed!"
+ "Unrecognized source bundle %{public}s"
+ "_TtC14FindingUIAngel15LocationService"
+ "_TtC14FindingUIAngel21FriendLocationService"
+ "_TtC14FindingUIAngelP33_327BA3061A8A7D03E59A617EE29CAA8022PersonDiscoveryManager"
+ "_TtCC14FindingUIAngel21FriendLocationService12Subscription"
+ "analyticsEvent"
+ "availabilityLatency"
+ "com.apple.MobileSMS"
+ "com.apple.findmy"
+ "com.apple.findmy.FindingUI"
+ "com.apple.findmy.peoplefinding"
+ "configuration"
+ "currentState"
+ "defaultWorkspace"
+ "deinit (%s): unsubscribed friend location"
+ "deinit (%s): unsubscribing friend location"
+ "discoveryManager"
+ "discoveryTokenFailed"
+ "eventContinuation"
+ "eventTask"
+ "findButtonAvailable"
+ "friendLocationService"
+ "friendLocationSubscription"
+ "heading"
+ "id=%s: %{public}s event"
+ "id=%s: deinited"
+ "id=%s: discovered after %s."
+ "id=%s: discovery token cancelled %s"
+ "id=%s: discovery token failed for %s with error %@"
+ "id=%s: discovery token timed out for %s"
+ "id=%s: event stream ended"
+ "id=%s: failed to get discovery token"
+ "id=%s: failed to get token, cancelled"
+ "id=%s: failed to get token, trying one more time"
+ "id=%s: friend location is too old (%s). Waiting for a newer location…"
+ "id=%s: friend location removed after %s"
+ "id=%s: friend location stream ended"
+ "id=%s: friend location updated after %s"
+ "id=%s: has token, skipping nearby checks after %s."
+ "id=%s: is discovering %s"
+ "id=%s: is findable %s"
+ "id=%s: is finding %s"
+ "id=%s: not findable after %s"
+ "id=%s: person is nearby starting discovery, after %s."
+ "id=%s: person is not close enough, after %s."
+ "id=%s: person is outside of the ranging radius, after %s."
+ "id=%s: subscription ended for %s (%{mask.hash}s) after %s"
+ "id=%s: subscription starting for %s (%{mask.hash}s), isSkippingNearbyChecks=%{bool}d…"
+ "id=%s: waiting for %{public}s after %s"
+ "id=%s: waiting for token after %s"
+ "initWithBool:"
+ "initWithDouble:"
+ "initWithInteger:"
+ "isFindMy"
+ "isSkippingNearbyChecks"
+ "location"
+ "locationTask"
+ "locations"
+ "openApplicationWithBundleID:"
+ "personLocationFailed"
+ "personLocationTask"
+ "requestSceneSessionDestruction:options:errorHandler:"
+ "responderWithHandler:"
+ "runID"
+ "service"
+ "signingIdentifier"
+ "sourceBundle"
+ "startDiscoveryInstant"
+ "startInstant"
+ "startedDiscovering"
+ "subscribersSkippingNearbyChecks"
+ "subscriptionsByID"
+ "tokenTask"
+ "v16@?0@\"BSActionResponse\"8"
+ "withinNearbyRange"
+ "wrapper"
- "Already findable %s"
- "Already finding %s"
- "Already running for %s"
- "Discovery ended"
- "Discovery token timed out for %s"
- "Dismissing due to friendship removal"
- "Dismissing scene: %s"
- "Failed to get discovery token for peer %s."
- "Failed to get token, cancelled %s"
- "Failed to get token, trying one more time for %s"
- "Failed to locate friend: %@"
- "Findable task being stopped…"
- "Findable task cancelled"
- "Findable task ended"
- "Findable task failed: %s"
- "Findable task failed: %s (%{public}s, code: %ld)"
- "Findable task moving to finding stopped…"
- "Findable task moving to finding…"
- "Findable task starting…"
- "Findable task timed out"
- "FindingUIAngel/FriendLocationMonitor.swift"
- "Friend location is too old (%s). Waiting for a newer location…"
- "Friend location updated with %s"
- "FriendLocationMonitor deinit"
- "Got a discovery token for %s"
- "Incoming request failed with error: %@"
- "Location manager failed"
- "No active finding session to dimsiss"
- "No location found"
- "Not finding %s"
- "Person location stream ended"
- "Sending failed: No connection for %s"
- "Starting discovery…"
- "Starting friend location monitor for %s"
- "The scene is not a UIWindowScene: %@"
- "The scene is not foreground: %s"
- "Unexpected state: %{public}s"
- "_TtC14FindingUIAngel19LocationServiceImpl"
- "_TtC14FindingUIAngel19LocationServiceMock"
- "_TtC14FindingUIAngel25FriendLocationMonitorImpl"
- "_TtC14FindingUIAngel25FriendLocationMonitorMock"
- "_TtCC14FindingUIAngel26FindablePersonSubscriptionP33_327BA3061A8A7D03E59A617EE29CAA8013PersonMonitor"
- "_currentState"
- "boolForKey:"
- "bundleID"
- "coordinate"
- "deinit (%s): locate session did stop refreshing"
- "deinit (%s): locate session will stop refreshing"
- "doubleForKey:"
- "friendLocationMonitor"
- "iterator"
- "locationsUpdateEventStreamProvider"
- "monitor"
- "monitor sequence "
- "monitoringTasks"
- "myLocation"
- "requestLocation"
- "runTask"
- "sequence"
- "standardUserDefaults"
- "systemApertureElementViewControllerProvider"
- "✅ Person is findable, after %s."
- "❌ %s removed"
- "🏃 waiting for %{public}s, after %s"
- "💾 Using mock FriendLocationMonitor"
- "💾 Using mock Handle"
- "💾 Using mock LocationService"
- "💾 Using mock services!"
- "📍 Person is nearby starting discovery, after %s."
- "📍 Person is not close enough, after %s."
- "📍 Person is outside of the ranging radius, after %s."
- "🔌 Invalidating connection from %d @ %s"
- "🔗 New connection from %s"
```
