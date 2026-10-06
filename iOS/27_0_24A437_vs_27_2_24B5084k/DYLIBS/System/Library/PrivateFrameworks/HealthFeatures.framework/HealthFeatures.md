## HealthFeatures

> `/System/Library/PrivateFrameworks/HealthFeatures.framework/HealthFeatures`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf02c` | `0x1e488` | **`+0xf45c`** |
| `__AUTH_CONST.__cfstring` | `—` | `0xe60` | **`+0xe60`** |
| `__DATA.__bss` | `0x1290` | `0x1ba0` | **`+0x910`** |
| `__TEXT.__const` | `0x1224` | `0x1998` | **`+0x774`** |
| `__TEXT.__cstring` | `0x233` | `0x981` | **`+0x74e`** |
| `__AUTH_CONST.__const` | `0x850` | `0xe28` | **`+0x5d8`** |
| `__AUTH_CONST.__objc_const` | `0x2e8` | `0x808` | **`+0x520`** |
| `__TEXT.__eh_frame` | `0x478` | `0x8c8` | **`+0x450`** |
| `__AUTH_CONST.__objc_arrayobj` | `—` | `0x408` | **`+0x408`** |
| `__DATA.__data` | `0x348` | `0x748` | **`+0x400`** |
| `__TEXT.__unwind_info` | `0x580` | `0x910` | **`+0x390`** |
| `__AUTH.__data` | `0x30` | `0x318` | **`+0x2e8`** |
| `__AUTH_CONST.__auth_got` | `0x5c0` | `0x8a0` | **`+0x2e0`** |
| `__TEXT.__constg_swiftt` | `0x404` | `0x65c` | **`+0x258`** |
| `__DATA_CONST.__objc_arraydata` | `—` | `0x238` | **`+0x238`** |
| `__TEXT.__swift5_typeref` | `0x3e2` | `0x5c8` | **`+0x1e6`** |
| `__TEXT.__swift5_fieldmd` | `0x2bc` | `0x490` | **`+0x1d4`** |
| `__TEXT.__swift5_capture` | `0x2c` | `0x194` | **`+0x168`** |
| `__TEXT.__oslogstring` | `0x191` | `0x2f1` | **`+0x160`** |
| `__TEXT.__swift5_reflstr` | `0x1fc` | `0x357` | **`+0x15b`** |
| `__AUTH.__objc_data` | `0xc8` | `0x220` | **`+0x158`** |
| `__DATA_CONST.__objc_selrefs` | `0x268` | `0x3b0` | **`+0x148`** |
| `__TEXT.__objc_methlist` | `0x2ac` | `0x374` | **`+0xc8`** |
| `__DATA_CONST.__objc_protolist` | `0x40` | `0x90` | **`+0x50`** |
| `__TEXT.__swift5_proto` | `0x10c` | `0x15c` | **`+0x50`** |
| `__TEXT.__swift5_assocty` | `0x98` | `0xc8` | **`+0x30`** |
| `__DATA_CONST.__objc_classlist` | `0x8` | `0x30` | **`+0x28`** |
| `__DATA_CONST.__objc_protorefs` | `0x20` | `0x48` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0x58` | `0x80` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x78` | `0x90` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x78` | `0x8c` | **`+0x14`** |
| `__DATA_DIRTY.__data` | `0x4c0` | `0x4d0` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x24` | `0x30` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0xc` | `0x18` | **`+0xc`** |
| `__DATA_CONST.__objc_catlist` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x4` | `0xc` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xc` | `0x14` | **`+0x8`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /usr/lib/swift/libswiftObservation.dylib
+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 476
-  Symbols:   296
-  CStrings:  22
+  Functions: 785
+  Symbols:   516
+  CStrings:  144
Symbols:
+ _HKAliasesByFeatureIdentifier
+ _HKAllFeatureIdentifiers
+ _HKCreateSerialDispatchQueue
+ _HKFeatureAvailabilityContextAdvertisableFeature
+ _HKFeatureAvailabilityContextBackgroundDelivery
+ _HKFeatureAvailabilityContextOmitPregnancyContent
+ _HKFeatureAvailabilityContextOnboardingInitiation
+ _HKFeatureAvailabilityContextOnboardingPromotion
+ _HKFeatureAvailabilityContextPregnancyAdjustmentEligibility
+ _HKFeatureAvailabilityContextWalkingSteadinessClassification
+ _HKFeatureAvailabilityContextWalkingSteadinessEventSubmission
+ _HKFeatureAvailabilityContextWalkingSteadinessNotOnboardedHealthChecklist
+ _HKFeatureAvailabilityContextWalkingSteadinessNotificationSettingsVisibility
+ _HKFeatureAvailabilityContextWalkingSteadinessOnboardedHealthChecklist
+ _HKFeatureAvailabilityContextWalkingSteadinessPromotionFeatureTag
+ _HKFeatureAvailabilityContextWalkingSteadinessShouldNotShowPregnancyContent
+ _HKFeatureIdentifierAFibBurden
+ _HKFeatureIdentifierBloodPressureJournal
+ _HKFeatureIdentifierCardioFitness
+ _HKFeatureIdentifierDepressionAndAnxietyAssessments
+ _HKFeatureIdentifierElectrocardiogramRecording
+ _HKFeatureIdentifierElectrocardiogramRecordingV1
+ _HKFeatureIdentifierElectrocardiogramRecordingV2
+ _HKFeatureIdentifierExampleFeature
+ _HKFeatureIdentifierGlucoseEnhancedCharting
+ _HKFeatureIdentifierHealthAge
+ _HKFeatureIdentifierHealthAssessment
+ _HKFeatureIdentifierHearingAid
+ _HKFeatureIdentifierHearingAidV2
+ _HKFeatureIdentifierHearingProtection
+ _HKFeatureIdentifierHearingProtectionPPE
+ _HKFeatureIdentifierHearingTest
+ _HKFeatureIdentifierHighHeartRateNotifications
+ _HKFeatureIdentifierHypertensionNotifications
+ _HKFeatureIdentifierHypertensionNotificationsV1
+ _HKFeatureIdentifierHypertensionNotificationsV2
+ _HKFeatureIdentifierIrregularRhythmNotifications
+ _HKFeatureIdentifierIrregularRhythmNotificationsV1
+ _HKFeatureIdentifierIrregularRhythmNotificationsV2
+ _HKFeatureIdentifierLabKit
+ _HKFeatureIdentifierLowHeartRateNotifications
+ _HKFeatureIdentifierMenstrualCycles
+ _HKFeatureIdentifierMenstrualCyclesDeviationDetection
+ _HKFeatureIdentifierMenstrualCyclesHeartRateInput
+ _HKFeatureIdentifierMenstrualCyclesMenopause
+ _HKFeatureIdentifierMenstrualCyclesWristTemperatureInput
+ _HKFeatureIdentifierMovementEvaluations
+ _HKFeatureIdentifierOxygenSaturationRecording
+ _HKFeatureIdentifierOxygenSaturationRecordingCompanionAnalysis
+ _HKFeatureIdentifierPeriodicDepressionAndAnxietyAssessmentPrompts
+ _HKFeatureIdentifierRespiratoryRateMeasurements
+ _HKFeatureIdentifierSleepActions
+ _HKFeatureIdentifierSleepApneaNotifications
+ _HKFeatureIdentifierSleepCoaching
+ _HKFeatureIdentifierSleepTracking
+ _HKFeatureIdentifierSleepingSampleAnalysis
+ _HKFeatureIdentifierSleepingWristTemperatureMeasurements
+ _HKFeatureIdentifierStateOfMindLogging
+ _HKFeatureIdentifierStateOfMindLoggingPatternEscalations
+ _HKFeatureIdentifierWalkingSteadinessClassifications
+ _HKFeatureIdentifierWalkingSteadinessNotifications
+ _HKIsAgeGatedUserDefaultsWalkingSteadinessKey
+ _HKLogInfrastructure
+ _NSStringFromHKFeatureIdentifier
+ _OBJC_CLASS_$_HKFeatureAvailabilityContextConstraint
+ _OBJC_CLASS_$_HKFeatureAvailabilityRequirementEvaluationDataSource
+ _OBJC_CLASS_$_HKFeatureAvailabilityRequirementSet
+ _OBJC_CLASS_$_HKFeatureAvailabilityRequirements
+ _OBJC_CLASS_$_HKFeatureStatusManager
+ _OBJC_CLASS_$_NSConstantArray
+ _OBJC_CLASS_$_NSDictionary
+ _OBJC_CLASS_$_NSMutableArray
+ _OBJC_CLASS_$_OS_dispatch_queue
+ _OBJC_CLASS_$__HKBehavior
+ _OBJC_CLASS_$__TtCs12_SwiftObject
+ _OBJC_METACLASS_$__TtC14HealthFeaturesP33_34D76AE191C7E75638E61BDDCFBB7FE827_ChildFeatureStatusObserver
+ _OBJC_METACLASS_$__TtCs12_SwiftObject
+ __CATEGORY_CLASS_METHODS_HKFeatureAvailabilityRequirementSet_$_HealthFeatures
+ __CATEGORY_CLASS_PROPERTIES_HKFeatureAvailabilityRequirementSet_$_HealthFeatures
+ __CATEGORY_HKFeatureAvailabilityRequirementSet_$_HealthFeatures
+ __DATA__TtC14HealthFeatures23FeatureStatusSetManager
+ __DATA__TtC14HealthFeatures26ObservableFeatureStatusSet
+ __DATA__TtC14HealthFeatures32FeatureStatusSetObservationToken
+ __DATA__TtC14HealthFeatures33_FeatureStatusSetCallbackObserver
+ __DATA__TtC14HealthFeaturesP33_34D76AE191C7E75638E61BDDCFBB7FE827_ChildFeatureStatusObserver
+ __INSTANCE_METHODS__TtC14HealthFeaturesP33_34D76AE191C7E75638E61BDDCFBB7FE827_ChildFeatureStatusObserver
+ __IVARS__TtC14HealthFeatures23FeatureStatusSetManager
+ __IVARS__TtC14HealthFeatures26ObservableFeatureStatusSet
+ __IVARS__TtC14HealthFeatures32FeatureStatusSetObservationToken
+ __IVARS__TtC14HealthFeatures33_FeatureStatusSetCallbackObserver
+ __IVARS__TtC14HealthFeaturesP33_34D76AE191C7E75638E61BDDCFBB7FE827_ChildFeatureStatusObserver
+ __METACLASS_DATA__TtC14HealthFeatures23FeatureStatusSetManager
+ __METACLASS_DATA__TtC14HealthFeatures26ObservableFeatureStatusSet
+ __METACLASS_DATA__TtC14HealthFeatures32FeatureStatusSetObservationToken
+ __METACLASS_DATA__TtC14HealthFeatures33_FeatureStatusSetCallbackObserver
+ __METACLASS_DATA__TtC14HealthFeaturesP33_34D76AE191C7E75638E61BDDCFBB7FE827_ChildFeatureStatusObserver
+ __OBJC_$_CLASS_PROP_LIST_HKFeatureAvailabilityRequirement
+ __OBJC_$_CLASS_PROP_LIST_NSSecureCoding
+ __OBJC_$_PROP_LIST_HKFeatureAvailabilityRequirement
+ __OBJC_$_PROTOCOL_CLASS_METHODS_HKFeatureAvailabilityRequirement
+ __OBJC_$_PROTOCOL_CLASS_METHODS_NSSecureCoding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HKFeatureAvailabilityRequirement
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HKFeatureAvailabilityRequirementsProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSCoding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSCopying
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HKFeatureAvailabilityRequirement
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HKFeatureAvailabilityRequirementsProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSCoding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSCopying
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSSecureCoding
+ __OBJC_$_PROTOCOL_REFS_HKFeatureAvailabilityRequirement
+ __OBJC_$_PROTOCOL_REFS_NSSecureCoding
+ __OBJC_LABEL_PROTOCOL_$_HKFeatureAvailabilityRequirement
+ __OBJC_LABEL_PROTOCOL_$_HKFeatureAvailabilityRequirementsProviding
+ __OBJC_LABEL_PROTOCOL_$_NSCoding
+ __OBJC_LABEL_PROTOCOL_$_NSCopying
+ __OBJC_LABEL_PROTOCOL_$_NSSecureCoding
+ __OBJC_PROTOCOL_$_HKFeatureAvailabilityRequirement
+ __OBJC_PROTOCOL_$_HKFeatureAvailabilityRequirementsProviding
+ __OBJC_PROTOCOL_$_NSCoding
+ __OBJC_PROTOCOL_$_NSCopying
+ __OBJC_PROTOCOL_$_NSSecureCoding
+ __PROTOCOLS__TtC14HealthFeaturesP33_34D76AE191C7E75638E61BDDCFBB7FE827_ChildFeatureStatusObserver
+ ___CFConstantStringClassReference
+ ___swift_closure_destructor.16Tm
+ ___swift_closure_destructorTm
+ ___swift_destroy_boxed_opaque_existential_1
+ ___swift_memcpy18_8
+ _associated conformance 14HealthFeatures16FeatureStatusSetV10CodingKeys33_41665B65CCEA570468CFAC25B8246A8BLLOSHAASQ
+ _associated conformance 14HealthFeatures16FeatureStatusSetV10CodingKeys33_41665B65CCEA570468CFAC25B8246A8BLLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 14HealthFeatures16FeatureStatusSetV10CodingKeys33_41665B65CCEA570468CFAC25B8246A8BLLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14HealthFeatures16FeatureStatusSetVSHAASQ
+ _associated conformance 14HealthFeatures20FeatureStatusRequestVSHAASQ
+ _associated conformance So19HKFeatureIdentifieraSHSCSQ
+ _associated conformance So19HKFeatureIdentifieras20_SwiftNewtypeWrapperSCSY
+ _associated conformance So19HKFeatureIdentifieras20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _dispatch_async_and_wait
+ _kHKHealthAppBundleIdentifier
+ _keypath_get.1Tm
+ _objc_alloc_init
+ _objc_retain_x24
+ _objc_retain_x26
+ _objc_retain_x27
+ _objc_retain_x28
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_bridgeObjectRelease_n
+ _swift_bridgeObjectRetain_n
+ _swift_deallocClassInstance
+ _swift_dynamicCastMetatype
+ _swift_dynamicCastObjCProtocolConditional
+ _swift_errorRelease
+ _swift_errorRetain
+ _swift_getErrorValue
+ _swift_getFunctionTypeMetadata0
+ _swift_getMetatypeMetadata
+ _swift_isEscapingClosureAtFileLocation
+ _swift_isUniquelyReferenced_nonNull_bridgeObject
+ _swift_lookUpClassMethod
+ _swift_release_n
+ _swift_release_x1
+ _swift_release_x22
+ _swift_release_x23
+ _swift_release_x26
+ _swift_release_x27
+ _swift_release_x28
+ _swift_retain
+ _swift_retain_x1
+ _swift_retain_x23
+ _swift_retain_x25
+ _swift_retain_x26
+ _swift_retain_x27
+ _swift_retain_x28
+ _swift_retain_x8
+ _swift_task_getMainExecutor
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
+ _swift_weakAssign
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
+ _symbolic $s14HealthFeatures24FeatureStatusSetObserverP
+ _symbolic $s14HealthFeatures25FeatureStatusSetProvidingP
+ _symbolic Iegh_
+ _symbolic Iegh_______pIeggr_ 15HealthUtilities10DebouncingP
+ _symbolic SDy__________G So19HKFeatureIdentifiera 14HealthFeatures13FeatureStatusO
+ _symbolic SDy________________pG So19HKFeatureIdentifiera 14HealthFeatures22FeatureStatusProvidingP So0afG0P
+ _symbolic Sb
+ _symbolic Shy_____G 14HealthFeatures20FeatureStatusRequestV
+ _symbolic Shy_____GSg So28HKFeatureAvailabilityContexta
+ _symbolic So17OS_dispatch_queueC
+ _symbolic _____ 11Observation0A9RegistrarV
+ _symbolic _____ 14HealthFeatures16FeatureStatusSetV
+ _symbolic _____ 14HealthFeatures16FeatureStatusSetV10CodingKeys33_41665B65CCEA570468CFAC25B8246A8BLLO
+ _symbolic _____ 14HealthFeatures20FeatureStatusRequestV
+ _symbolic _____ 14HealthFeatures23FeatureStatusSetManagerC
+ _symbolic _____ 14HealthFeatures23FeatureStatusSetManagerC5State33_34D76AE191C7E75638E61BDDCFBB7FE8LLV
+ _symbolic _____ 14HealthFeatures26ObservableFeatureStatusSetC
+ _symbolic _____ 14HealthFeatures27_ChildFeatureStatusObserver33_34D76AE191C7E75638E61BDDCFBB7FE8LLC
+ _symbolic _____ 14HealthFeatures32FeatureStatusSetObservationTokenC
+ _symbolic _____ 14HealthFeatures33_FeatureStatusSetCallbackObserverC
+ _symbolic _____ So19HKFeatureIdentifiera
+ _symbolic _____Sg 14HealthFeatures16FeatureStatusSetV
+ _symbolic _____Sg 14HealthFeatures32FeatureStatusSetObservationTokenC
+ _symbolic _____SgXw 14HealthFeatures23FeatureStatusSetManagerC
+ _symbolic _____SgXw 14HealthFeatures26ObservableFeatureStatusSetC
+ _symbolic _____XDXMT 14HealthFeatures23FeatureStatusSetManagerC
+ _symbolic ______p 14HealthFeatures25FeatureStatusSetProvidingP
+ _symbolic ______p 15HealthUtilities10DebouncingP
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 14HealthFeatures23FeatureStatusSetManagerC5State33_34D76AE191C7E75638E61BDDCFBB7FE8LLV
+ _symbolic _____y______pG 9HealthKit11ObserverSetV 0A8Features013FeatureStatusdC0P
+ _symbolic _____yyyYbcSgG 15Synchronization5MutexVAARi_zrlE
+ _symbolic y_____Ybc 14HealthFeatures16FeatureStatusSetV
+ _symbolic ytIeghr_
+ _symbolic ytSg______pIgrzo_ s5ErrorP
+ _type_layout_string 14HealthFeatures16FeatureStatusSetV
+ _type_layout_string 14HealthFeatures20FeatureStatusRequestV
+ _type_layout_string 14HealthFeatures23FeatureStatusSetManagerC5State33_34D76AE191C7E75638E61BDDCFBB7FE8LLV
+ _type_layout_string So19HKFeatureIdentifiera
- _type_layout_string So42HKFeatureAvailabilityRequirementIdentifiera
CStrings:
+ "AFib Burden"
+ "Blood Oxygen"
+ "Blood Oxygen Companion Analysis"
+ "Blood Pressure Journal"
+ "Cardio Fitness"
+ "Cycle Tracking"
+ "Cycle Tracking Deviations"
+ "Cycle Tracking Heart Rate Input"
+ "Cycle Tracking Menopause"
+ "Cycle Tracking Wrist Temperature Input"
+ "Depression and Anxiety Assessments"
+ "ECG (Combined)"
+ "ECG 1.0"
+ "ECG 2.0"
+ "Glucose Experience"
+ "Health Age"
+ "HealthFeatures/ObservableFeatureStatusSet.swift"
+ "Hearing Aid"
+ "Hearing Aid v2"
+ "Hearing Protection"
+ "Hearing Protection PPE"
+ "Hearing Test"
+ "High Heart Rate Notifications"
+ "Hypertension Notifications"
+ "Hypertension Notifications 1.0"
+ "Hypertension Notifications 2.0"
+ "HypertensionNotificationsV1"
+ "IRN (Combined)"
+ "IRN 1.0"
+ "IRN 2.0"
+ "Incorrect actor executor assumption; Expected same executor as "
+ "LabKit"
+ "Low Heart Rate Notifications"
+ "Movement Evaluations"
+ "Periodic Depression and Anxiety Assessments Prompts"
+ "Respiratory Rate"
+ "Sleep"
+ "Sleep Apnea Notifications"
+ "Sleep Wind Down Shortcuts"
+ "Sleep on Watch Tracking"
+ "Sleeping Sample Analysis"
+ "Sleeping Wrist Temperature"
+ "State of Mind Logging"
+ "State of Mind Logging Pattern Escalations"
+ "Walking Steadiness Classifications"
+ "Walking Steadiness Notifications"
+ "WristTemperatureMeasurements"
+ "[%{public}s] Could not evaluate a snapshot; staying registered: %{public}s"
+ "[%{public}s] No status present for feature '%{public}s'; ensure the feature was requested of the provider"
+ "[FeatureStatusSetManager] Could not resolve an availability provider for '%{public}s'; it will evaluate against its own data source rather than the shared one"
+ "assessments"
+ "be"
+ "berry"
+ "blood_oxygen"
+ "blood_oxygen_companion_analysis"
+ "cf"
+ "chamomile_logging"
+ "ct"
+ "ctd"
+ "cthr"
+ "ctm"
+ "ctwt"
+ "ecg"
+ "ecg1"
+ "ecg2"
+ "glucose"
+ "ha"
+ "harmonia"
+ "health-age"
+ "health-assessment"
+ "hearing-aid"
+ "hearing-aid-v2"
+ "hearing-protection"
+ "hearing-protection-ppe"
+ "hearing-test"
+ "hermit"
+ "hermit1"
+ "hermit2"
+ "hhr"
+ "hhrn"
+ "irn"
+ "irn1"
+ "irn2"
+ "kali"
+ "kepler"
+ "kepler_classifications"
+ "kepler_notifications"
+ "key value "
+ "labkit"
+ "lhr"
+ "lhrn"
+ "luna"
+ "mc"
+ "mcd"
+ "mchr"
+ "mcm"
+ "mcwt"
+ "me"
+ "menopause"
+ "nebula"
+ "nebula-notifications"
+ "ota"
+ "pattern_based_escalations"
+ "pbe"
+ "periodic_assessments"
+ "rr"
+ "san"
+ "scandium"
+ "selene"
+ "sleep"
+ "sleep-actions"
+ "sleep-apnea-notifications"
+ "sleep-shortcuts"
+ "sleep-watch"
+ "statusesByFeature"
+ "time_based_assessments"
+ "vela"
+ "vitals"
+ "yodel"
+ "yodel-protection"
+ "yodel-protection-ppe"
+ "yodel-test"
```
