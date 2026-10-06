## SeparationAlerts

> `/System/Library/PrivateFrameworks/SeparationAlerts.framework/SeparationAlerts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x395d8` | `0x3c5c0` | **`+0x2fe8`** |
| `__TEXT.__oslogstring` | `0x9603` | `0xa3ef` | **`+0xdec`** |
| `__AUTH_CONST.__objc_const` | `0x6b18` | `0x70f0` | **`+0x5d8`** |
| `__AUTH_CONST.__cfstring` | `0x28a0` | `0x2d20` | **`+0x480`** |
| `__TEXT.__cstring` | `0x1c8c` | `0x2030` | **`+0x3a4`** |
| `__TEXT.__objc_methlist` | `0x44f4` | `0x47fc` | **`+0x308`** |
| `__DATA_CONST.__objc_selrefs` | `0x25e8` | `0x2760` | **`+0x178`** |
| `__DATA.__data` | `0xd80` | `0xe40` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0x230` | `0x2d0` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x9e0` | `0xa70` | **`+0x90`** |
| `__TEXT.__gcc_except_tab` | `0x260` | `0x2e4` | **`+0x84`** |
| `__DATA_CONST.__const` | `0x418` | `0x498` | **`+0x80`** |
| `__DATA_CONST.__got` | `0x398` | `0x3f8` | **`+0x60`** |
| `__DATA.__objc_ivar` | `0x558` | `0x5a4` | **`+0x4c`** |
| `__AUTH_CONST.__const` | `0x60` | `0xa0` | **`+0x40`** |
| `__AUTH_CONST.__objc_doubleobj` | `—` | `0x30` | **`+0x30`** |
| `__DATA.__bss` | `—` | `0x30` | **`+0x30`** |
| `__TEXT.__const` | `0x168` | `0x188` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x1c8` | `0x1e0` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x150` | `0x160` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x120` | `0x130` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x130` | `0x138` | **`+0x8`** |

### Other Changes

```diff

-107.0.22.0.0
+107.0.25.0.0

+  - /usr/lib/libMobileGestalt.dylib

-  Functions: 1273
-  Symbols:   2378
-  CStrings:  705
+  Functions: 1335
+  Symbols:   2517
+  CStrings:  779
Symbols:
+ -[SAAlertFeedbackManager .cxx_destruct]
+ -[SAAlertFeedbackManager _evaluateTrialConfiguration]
+ -[SAAlertFeedbackManager _showDeferredPopUps]
+ -[SAAlertFeedbackManager _valueForFactor:default:]
+ -[SAAlertFeedbackManager analytics]
+ -[SAAlertFeedbackManager backoffInterval]
+ -[SAAlertFeedbackManager cachedConfiguration]
+ -[SAAlertFeedbackManager clock]
+ -[SAAlertFeedbackManager currentVehicularState]
+ -[SAAlertFeedbackManager defaults]
+ -[SAAlertFeedbackManager deviceUUIDtoDeferredAlertInfo]
+ -[SAAlertFeedbackManager deviceUUIDtoFeedbackResponse]
+ -[SAAlertFeedbackManager deviceUUIDtoPendingAlertContent]
+ -[SAAlertFeedbackManager deviceUUIDtoPendingReunionContent]
+ -[SAAlertFeedbackManager feedbackEnabled]
+ -[SAAlertFeedbackManager finishFeedbackForDeviceUUID:response:]
+ -[SAAlertFeedbackManager handleAlertEventForDeviceUUID:deviceName:alertTimestamp:content:legacySuppressed:]
+ -[SAAlertFeedbackManager handleReunionEventForDeviceUUID:content:]
+ -[SAAlertFeedbackManager handleVehicularStateChange:]
+ -[SAAlertFeedbackManager ingestTAEvent:]
+ -[SAAlertFeedbackManager initWithClock:analytics:defaults:notificationPresenter:]
+ -[SAAlertFeedbackManager lastFeedbackShownDate]
+ -[SAAlertFeedbackManager notificationPresenter]
+ -[SAAlertFeedbackManager optOutDuration]
+ -[SAAlertFeedbackManager optOutStartDate]
+ -[SAAlertFeedbackManager presentFirstPopUpForDeviceUUID:deviceName:timestamp:]
+ -[SAAlertFeedbackManager presentSecondPopUpForDeviceUUID:]
+ -[SAAlertFeedbackManager samplingRate]
+ -[SAAlertFeedbackManager setAnalytics:]
+ -[SAAlertFeedbackManager setBackoffInterval:]
+ -[SAAlertFeedbackManager setCachedConfiguration:]
+ -[SAAlertFeedbackManager setClock:]
+ -[SAAlertFeedbackManager setCurrentVehicularState:]
+ -[SAAlertFeedbackManager setDefaults:]
+ -[SAAlertFeedbackManager setDeviceUUIDtoDeferredAlertInfo:]
+ -[SAAlertFeedbackManager setDeviceUUIDtoFeedbackResponse:]
+ -[SAAlertFeedbackManager setDeviceUUIDtoPendingAlertContent:]
+ -[SAAlertFeedbackManager setDeviceUUIDtoPendingReunionContent:]
+ -[SAAlertFeedbackManager setFeedbackEnabled:]
+ -[SAAlertFeedbackManager setLastFeedbackShownDate:]
+ -[SAAlertFeedbackManager setNotificationPresenter:]
+ -[SAAlertFeedbackManager setOptOutDuration:]
+ -[SAAlertFeedbackManager setOptOutStartDate:]
+ -[SAAlertFeedbackManager setSamplingRate:]
+ -[SAAlertFeedbackManager shouldShowFeedbackForDeviceUUID:]
+ -[SAAlertFeedbackManager submitPendingReunionIfNeeded:]
+ -[SADevice descriptiveName]
+ -[SAMonitoringSessionManager alertFeedbackManager]
+ -[SAMonitoringSessionManager initWithWithYouDetector:fenceRequestServicer:fenceManager:travelTypeClassifier:clock:deviceRecord:analytics:persistenceManager:audioAccessoryManager:suppressionManager:alertFeedbackManager:]
+ -[SAMonitoringSessionManager setAlertFeedbackManager:]
+ -[SAService alertFeedbackManager]
+ -[SAService initWithAnalytics:isReplay:audioAccessoryManager:defaults:]
+ -[SAService setAlertFeedbackManager:]
+ -[SATrialManager valueForFactor:inNamespace:]
+ -[SAUserNotificationPresenter presentNotificationWithOptions:flags:timeout:completion:]
+ -[TADefaults dateForKey:defaultValue:]
+ -[TADefaultsAccessor initialize]
+ -[TADefaultsSystemUtils dataWithContentsOfURL:options:error:]
+ _CFBooleanGetTypeID
+ _CFBooleanGetValue
+ _CFGetTypeID
+ _CFPropertyListCreateWithData
+ _CFRetain
+ _CFRunLoopAddSource
+ _CFRunLoopGetMain
+ _CFRunLoopSourceInvalidate
+ _CFUserNotificationCreate
+ _CFUserNotificationCreateRunLoopSource
+ _MGCopyAnswer
+ _NSCocoaErrorDomain
+ _OBJC_CLASS_$_NSConstantDoubleNumber
+ _OBJC_CLASS_$_NSDateFormatter
+ _OBJC_CLASS_$_NSNull
+ _OBJC_CLASS_$_SAAlertFeedbackManager
+ _OBJC_CLASS_$_SAUserNotificationPresenter
+ _OBJC_IVAR_$_SAAlertFeedbackManager._analytics
+ _OBJC_IVAR_$_SAAlertFeedbackManager._backoffInterval
+ _OBJC_IVAR_$_SAAlertFeedbackManager._cachedConfiguration
+ _OBJC_IVAR_$_SAAlertFeedbackManager._clock
+ _OBJC_IVAR_$_SAAlertFeedbackManager._currentVehicularState
+ _OBJC_IVAR_$_SAAlertFeedbackManager._defaults
+ _OBJC_IVAR_$_SAAlertFeedbackManager._deviceUUIDtoDeferredAlertInfo
+ _OBJC_IVAR_$_SAAlertFeedbackManager._deviceUUIDtoFeedbackResponse
+ _OBJC_IVAR_$_SAAlertFeedbackManager._deviceUUIDtoPendingAlertContent
+ _OBJC_IVAR_$_SAAlertFeedbackManager._deviceUUIDtoPendingReunionContent
+ _OBJC_IVAR_$_SAAlertFeedbackManager._feedbackEnabled
+ _OBJC_IVAR_$_SAAlertFeedbackManager._lastFeedbackShownDate
+ _OBJC_IVAR_$_SAAlertFeedbackManager._notificationPresenter
+ _OBJC_IVAR_$_SAAlertFeedbackManager._optOutDuration
+ _OBJC_IVAR_$_SAAlertFeedbackManager._optOutStartDate
+ _OBJC_IVAR_$_SAAlertFeedbackManager._samplingRate
+ _OBJC_IVAR_$_SAMonitoringSessionManager._alertFeedbackManager
+ _OBJC_IVAR_$_SAService._alertFeedbackManager
+ _OBJC_IVAR_$_TADefaultsAccessor._profileSettings
+ _OBJC_METACLASS_$_SAAlertFeedbackManager
+ _OBJC_METACLASS_$_SAUserNotificationPresenter
+ _SATrialFactorAlertFeedbackBackoffInterval
+ _SATrialFactorAlertFeedbackEnabled
+ _SATrialFactorAlertFeedbackOptOutDuration
+ _SATrialFactorAlertFeedbackSamplingRate
+ _SAUserNotificationResponseHandler
+ _TAIsInternalInstall
+ _TAIsInternalInstall.onceToken
+ _TAIsInternalInstall.sIsInternalInstall
+ __OBJC_$_INSTANCE_METHODS_SAAlertFeedbackManager
+ __OBJC_$_INSTANCE_METHODS_SAUserNotificationPresenter
+ __OBJC_$_INSTANCE_VARIABLES_SAAlertFeedbackManager
+ __OBJC_$_PROP_LIST_SAAlertFeedbackManager
+ __OBJC_$_PROP_LIST_SAUserNotificationPresenter
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SAAlertFeedbackManagerProtocol
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_SAUserNotificationPresenterProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SAAlertFeedbackManagerProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_SAUserNotificationPresenterProtocol
+ __OBJC_$_PROTOCOL_REFS_SAAlertFeedbackManagerProtocol
+ __OBJC_$_PROTOCOL_REFS_SAUserNotificationPresenterProtocol
+ __OBJC_CLASS_PROTOCOLS_$_SAAlertFeedbackManager
+ __OBJC_CLASS_PROTOCOLS_$_SAUserNotificationPresenter
+ __OBJC_CLASS_RO_$_SAAlertFeedbackManager
+ __OBJC_CLASS_RO_$_SAUserNotificationPresenter
+ __OBJC_LABEL_PROTOCOL_$_SAAlertFeedbackManagerProtocol
+ __OBJC_LABEL_PROTOCOL_$_SAUserNotificationPresenterProtocol
+ __OBJC_METACLASS_RO_$_SAAlertFeedbackManager
+ __OBJC_METACLASS_RO_$_SAUserNotificationPresenter
+ __OBJC_PROTOCOL_$_SAAlertFeedbackManagerProtocol
+ __OBJC_PROTOCOL_$_SAUserNotificationPresenterProtocol
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__117__floyd_sift_downB9fqe220106INS_17_ClassicAlgPolicyER19SAAlarmClassCompareNS_11__wrap_iterIPU8__strongP11SAAlarmTaskEEEET1_SA_OT0_NS_15iterator_traitsISA_E15difference_typeE
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIU8__strongP11SAAlarmTaskEENS_16allocator_traitsIS5_EEEENS_19__allocation_resultINT0_7pointerENS9_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorIU8__strongP11SAAlarmTaskNS_9allocatorIS3_EEE16__destroy_vectorclB9fqe220106Ev
+ __ZNSt3__16vectorIU8__strongP11SAAlarmTaskNS_9allocatorIS3_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIU8__strongP11SAAlarmTaskNS_9allocatorIS3_EEE9push_backB9fqe220106ERU8__strongKS2_
+ __ZNSt3__19__sift_upB9fqe220106INS_17_ClassicAlgPolicyER19SAAlarmClassCompareNS_11__wrap_iterIPU8__strongP11SAAlarmTaskEEEEvT1_SA_OT0_NS_15iterator_traitsISA_E15difference_typeE
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ ___58-[SAAlertFeedbackManager presentSecondPopUpForDeviceUUID:]_block_invoke
+ ___78-[SAAlertFeedbackManager presentFirstPopUpForDeviceUUID:deviceName:timestamp:]_block_invoke
+ ___78-[SAAlertFeedbackManager presentFirstPopUpForDeviceUUID:deviceName:timestamp:]_block_invoke_2
+ ___TAIsInternalInstall_block_invoke
+ ___block_descriptor_48_e8_32s40w_e11_v20?0Q8i16lw40l8s32l8
+ ___kCFBooleanTrue
+ _arc4random
+ _kCFAllocatorDefault
+ _kCFRunLoopCommonModes
+ _kCFUserNotificationAlertHeaderKey
+ _kCFUserNotificationAlertMessageKey
+ _kCFUserNotificationAlternateButtonTitleKey
+ _kCFUserNotificationDefaultButtonTitleKey
+ _kCFUserNotificationOtherButtonTitleKey
+ _presentFirstPopUpForDeviceUUID:deviceName:timestamp:.onceToken
+ _presentFirstPopUpForDeviceUUID:deviceName:timestamp:.sAlertTimestampFormatter
+ _sCurrentCompletion
+ _sCurrentSource
- -[SAMonitoringSessionManager initWithWithYouDetector:fenceRequestServicer:fenceManager:travelTypeClassifier:clock:deviceRecord:analytics:persistenceManager:audioAccessoryManager:suppressionManager:]
- -[SAService initWithAnalytics:isReplay:audioAccessoryManager:]
- -[SATrialManager boolValueForFactor:inNamespace:]
- -[SATrialManager doubleValueForFactor:inNamespace:]
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__117__floyd_sift_downB9fqe220100INS_17_ClassicAlgPolicyER19SAAlarmClassCompareNS_11__wrap_iterIPU8__strongP11SAAlarmTaskEEEET1_SA_OT0_NS_15iterator_traitsISA_E15difference_typeE
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIU8__strongP11SAAlarmTaskEENS_16allocator_traitsIS5_EEEENS_19__allocation_resultINT0_7pointerENS9_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorIU8__strongP11SAAlarmTaskNS_9allocatorIS3_EEE16__destroy_vectorclB9fqe220100Ev
- __ZNSt3__16vectorIU8__strongP11SAAlarmTaskNS_9allocatorIS3_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIU8__strongP11SAAlarmTaskNS_9allocatorIS3_EEE9push_backB9fqe220100ERU8__strongKS2_
- __ZNSt3__19__sift_upB9fqe220100INS_17_ClassicAlgPolicyER19SAAlarmClassCompareNS_11__wrap_iterIPU8__strongP11SAAlarmTaskEEEEvT1_SA_OT0_NS_15iterator_traitsISA_E15difference_typeE
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
CStrings:
+ "\f"
+ "//private/var/Managed Preferences/%@/%@.plist"
+ "AirPods - case"
+ "AirPods - left bud"
+ "AirPods - right bud"
+ "AirPods Max"
+ "Did you leave %@ behind at %@? If not, please file a radar to FindMy | iOS"
+ "DidNotSeparate"
+ "Don't ask for %ld days"
+ "DontAskAgain"
+ "FirstPopUpTimedOut"
+ "I left it behind accidentally"
+ "I left this device behind"
+ "I meant to leave it behind"
+ "InternalBuild"
+ "K"
+ "NotShown"
+ "SAUserFeedbackLastShownDate"
+ "SAUserFeedbackOptOutStartDate"
+ "SecondPopUpTimedOut"
+ "SeparatedAccidentally"
+ "SeparatedIntentionally"
+ "Thanks for answering. One last question, did you leave this item behind on purpose?"
+ "This device is still with me"
+ "[Internal Only] Find My: Notify When Left Behind"
+ "[Internal Only] Find My: Notify When Left Behind (Part 2/2)"
+ "alertFeedbackBackoffInterval"
+ "alertFeedbackEnabled"
+ "alertFeedbackOptOutDuration"
+ "alertFeedbackSamplingRate"
+ "case"
+ "content"
+ "deviceName"
+ "legacySuppressionApplied"
+ "q"
+ "reunionContent"
+ "single"
+ "userFeedbackResponse"
+ "v20@?0Q8i16"
+ "your device"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedba1ckManager user chose don't ask\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager alert deferred due to vehicular state\", \"device\":\"%{public}@\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager alert for device already pending, submitted with NotShown\", \"device\":\"%{public}@\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager alert suppressed, submitted with NotShown\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager applied Trial config\", \"feedbackEnabled\":%{public}hhd, \"backoffInterval\":\"%{public}f\", \"samplingRate\":\"%{public}f\", \"optOutDuration\":\"%{public}f\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager backoff active\", \"device\":\"%{public}@\", \"lastFeedbackShownDate\":\"%{public}@\", \"backoffInterval\":\"%{public}f\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager backoffInterval below minimum, clamping\", \"requested\":\"%{public}f\", \"minimum\":\"%{public}f\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager deferred alert already exists, submitted with NotShown\", \"device\":\"%{public}@\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager deferred pop-up on vehicular exit\", \"device\":\"%{public}@\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager factor\", \"factor\":\"%{public}@\", \"trialAvailable\":\"%{public}s\", \"result\":\"%{public}@\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager feedback completed\", \"device\":\"%{public}@\", \"response\":\"%{public}@\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager feedback disabled\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager first pop-up timed out (responseFlags)\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager first pop-up timed out or error\", \"errorCode\":%{public}d}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager reunion arrived while alert deferred, will show pop-up after driving stops\", \"device\":\"%{public}@\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager reunion deferred, alert feedback pending\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager reunion for device already pending, submitted with NotShown\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager sampled out\", \"device\":\"%{public}@\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager second pop-up timed out (responseFlags)\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager second pop-up timed out\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager showing deferred pop-up after vehicular exit\", \"device\":\"%{public}@\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager showing pop-up for device\", \"device\":\"%{public}@\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager submitted deferred reunion event\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager user confirmed separation, showing second pop-up\", \"device\":\"%{public}@\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager user did not separate\"}"
+ "{\"msg%{public}.0s\":\"#SAAlertFeedbackManager user opted out\", \"optOutStartDate\":\"%{public}@\", \"optOutDuration\":\"%{public}f\"}"
+ "{\"msg%{public}.0s\":\"#SATrialManager unexpected level type for factor\", \"factor\":\"%{public}@\", \"namespace\":\"%{public}@\", \"levelType\":%{public}lu}"
+ "{\"msg%{public}.0s\":\"#ta #defaults failed to deserialize managed defaults from file\", \"file\":\"%{public}s\"}"
+ "{\"msg%{public}.0s\":\"#ta #defaults failed to read file\", \"file\":\"%{public}s\"}"
+ "{\"msg%{public}.0s\":\"#ta #defaults found no file containing managed defaults\", \"file\":\"%{public}s\"}"
+ "{\"msg%{public}.0s\":\"#ta #defaults initialization finished\"}"
+ "{\"msg%{public}.0s\":\"#ta #defaults initialization started\", \"file\":\"%{public}s\"}"
+ "{\"msg%{public}.0s\":\"#ta #defaults loaded managed defaults from file\", \"file\":\"%{public}s\"}"
+ "{\"msg%{public}.0s\":\"#ta #defaults must initialize accessor before reading\"}"
+ "{\"msg%{public}.0s\":\"#ta #defaults must only be initialized once\"}"
- "\v"
```
