## SiriInstrumentation

> `/System/Library/PrivateFrameworks/SiriInstrumentation.framework/SiriInstrumentation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd5bff4` | `0xd5eb08` | **`+0x2b14`** |
| `__TEXT.__cstring` | `0x93c3b` | `0x94176` | **`+0x53b`** |
| `__AUTH_CONST.__objc_const` | `0x179730` | `0x179c20` | **`+0x4f0`** |
| `__AUTH_CONST.__cfstring` | `0x7ee00` | `0x7f220` | **`+0x420`** |
| `__TEXT.__objc_methlist` | `0x10789c` | `0x107c6c` | **`+0x3d0`** |
| `__DATA_CONST.__const` | `0x3d1c0` | `0x3d3f8` | **`+0x238`** |
| `__DATA_CONST.__objc_selrefs` | `0x41fa8` | `0x420d0` | **`+0x128`** |
| `__DATA.__bss` | `0x1f400` | `0x1f500` | **`+0x100`** |
| `__AUTH.__objc_data` | `0x28ff0` | `0x290e0` | **`+0xf0`** |
| `__TEXT.__const` | `0x17654` | `0x17714` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x33610` | `0x336d0` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x245a9` | `0x245e9` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x7e14` | `0x7e54` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x128ec` | `0x12920` | **`+0x34`** |
| `__TEXT.__swift5_builtin` | `0x4984` | `0x49ac` | **`+0x28`** |
| `__DATA.__data` | `0x3440` | `0x3458` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x6850` | `0x6868` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x6718` | `0x6730` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0x66c8` | `0x66e0` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x1e9a` | `0x1ea6` | **`+0xc`** |
| `__TEXT.__swift5_proto` | `0x136c` | `0x1374` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xf08` | `0xf10` | **`+0x8`** |

### Other Changes

```diff

-3600.79.1.0.0
+3600.80.1.0.0

-  Functions: 92861
-  Symbols:   130655
-  CStrings:  17350
+  Functions: 92946
+  Symbols:   130771
+  CStrings:  17383
Symbols:
+ +[ODSIGNALSiriSchemaODSIGNALClientEvent(InnerEventContainer) getInnerTypeStringByTag:]
+ -[ASRSchemaASRStarted deleteSpeechProfileSizeBucket]
+ -[ASRSchemaASRStarted hasSpeechProfileSizeBucket]
+ -[ASRSchemaASRStarted setHasSpeechProfileSizeBucket:]
+ -[ASRSchemaASRStarted setSpeechProfileSizeBucket:]
+ -[ASRSchemaASRStarted speechProfileSizeBucket]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource cascadeFieldType]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource deleteCascadeFieldType]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource deleteNumEnrolledEntities]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource dictionaryRepresentation]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource hasCascadeFieldType]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource hasNumEnrolledEntities]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource hash]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource initWithDictionary:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource initWithJSON:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource isEqual:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource jsonData]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource numEnrolledEntities]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource readFrom:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource setCascadeFieldType:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource setHasCascadeFieldType:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource setHasNumEnrolledEntities:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource setNumEnrolledEntities:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource writeTo:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileDonatedAppEntityMetric deleteNumCandidateInteractions]
+ -[ASRSpeechProfileSchemaASRSpeechProfileDonatedAppEntityMetric hasNumCandidateInteractions]
+ -[ASRSpeechProfileSchemaASRSpeechProfileDonatedAppEntityMetric numCandidateInteractions]
+ -[ASRSpeechProfileSchemaASRSpeechProfileDonatedAppEntityMetric setHasNumCandidateInteractions:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileDonatedAppEntityMetric setNumCandidateInteractions:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileUpdateEnded addCascadeEntitySources:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileUpdateEnded cascadeEntitySourcesAtIndex:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileUpdateEnded cascadeEntitySourcesCount]
+ -[ASRSpeechProfileSchemaASRSpeechProfileUpdateEnded cascadeEntitySources]
+ -[ASRSpeechProfileSchemaASRSpeechProfileUpdateEnded clearCascadeEntitySources]
+ -[ASRSpeechProfileSchemaASRSpeechProfileUpdateEnded deleteCascadeEntitySources]
+ -[ASRSpeechProfileSchemaASRSpeechProfileUpdateEnded deleteSpeechProfileSize]
+ -[ASRSpeechProfileSchemaASRSpeechProfileUpdateEnded hasSpeechProfileSize]
+ -[ASRSpeechProfileSchemaASRSpeechProfileUpdateEnded setCascadeEntitySources:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileUpdateEnded setHasSpeechProfileSize:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileUpdateEnded setSpeechProfileSize:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileUpdateEnded speechProfileSize]
+ -[ASRSpeechProfileSchemaASRSpeechProfileUpdateStarted deleteSpeechProfileUpdateReason]
+ -[ASRSpeechProfileSchemaASRSpeechProfileUpdateStarted hasSpeechProfileUpdateReason]
+ -[ASRSpeechProfileSchemaASRSpeechProfileUpdateStarted setHasSpeechProfileUpdateReason:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileUpdateStarted setSpeechProfileUpdateReason:]
+ -[ASRSpeechProfileSchemaASRSpeechProfileUpdateStarted speechProfileUpdateReason]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded deleteExists]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded dictionaryRepresentation]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded exists]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded hasExists]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded hash]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded initWithDictionary:]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded initWithJSON:]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded isEqual:]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded jsonData]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded readFrom:]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded setExists:]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded setHasExists:]
+ -[ODSIGNALSiriSchemaODSIGNALAppForegrounded writeTo:]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent .cxx_destruct]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent appForegrounded]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent deleteAppForegrounded]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent dictionaryRepresentation]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent hasAppForegrounded]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent hash]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent initWithDictionary:]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent initWithJSON:]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent isEqual:]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent jsonData]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent qualifiedMessageName]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent readFrom:]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent setAppForegrounded:]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent setHasAppForegrounded:]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent whichEvent_Type]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent writeTo:]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent(InnerEventContainer) innerEvent]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent(InnerEventContainer) whichInnerEventType]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent(InstrumentationAdditions) getAnyEventType]
+ -[ODSIGNALSiriSchemaODSIGNALClientEvent(IsolationLevel) clockIsolationLevel]
+ OBJC_IVAR_$_ASRSchemaASRStarted._speechProfileSizeBucket
+ OBJC_IVAR_$_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource._cascadeFieldType
+ OBJC_IVAR_$_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource._has
+ OBJC_IVAR_$_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource._numEnrolledEntities
+ OBJC_IVAR_$_ASRSpeechProfileSchemaASRSpeechProfileDonatedAppEntityMetric._numCandidateInteractions
+ OBJC_IVAR_$_ASRSpeechProfileSchemaASRSpeechProfileUpdateEnded._cascadeEntitySources
+ OBJC_IVAR_$_ASRSpeechProfileSchemaASRSpeechProfileUpdateEnded._speechProfileSize
+ OBJC_IVAR_$_ASRSpeechProfileSchemaASRSpeechProfileUpdateStarted._speechProfileUpdateReason
+ OBJC_IVAR_$_ODSIGNALSiriSchemaODSIGNALAppForegrounded._exists
+ OBJC_IVAR_$_ODSIGNALSiriSchemaODSIGNALAppForegrounded._has
+ OBJC_IVAR_$_ODSIGNALSiriSchemaODSIGNALClientEvent._appForegrounded
+ _OBJC_CLASS_$_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource
+ _OBJC_CLASS_$_ODSIGNALSiriSchemaODSIGNALAppForegrounded
+ _OBJC_CLASS_$_ODSIGNALSiriSchemaODSIGNALClientEvent
+ _OBJC_IVAR_$_ODSIGNALSiriSchemaODSIGNALClientEvent._hasAppForegrounded
+ _OBJC_IVAR_$_ODSIGNALSiriSchemaODSIGNALClientEvent._whichEvent_Type
+ _OBJC_METACLASS_$_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource
+ _OBJC_METACLASS_$_ODSIGNALSiriSchemaODSIGNALAppForegrounded
+ _OBJC_METACLASS_$_ODSIGNALSiriSchemaODSIGNALClientEvent
+ __OBJC_$_CLASS_METHODS_ODSIGNALSiriSchemaODSIGNALClientEvent(InstrumentationAdditions|InnerEventContainer|IsolationLevel)
+ __OBJC_$_INSTANCE_METHODS_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource
+ __OBJC_$_INSTANCE_METHODS_ODSIGNALSiriSchemaODSIGNALAppForegrounded
+ __OBJC_$_INSTANCE_METHODS_ODSIGNALSiriSchemaODSIGNALClientEvent(InstrumentationAdditions|InnerEventContainer|IsolationLevel)
+ __OBJC_$_INSTANCE_VARIABLES_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource
+ __OBJC_$_INSTANCE_VARIABLES_ODSIGNALSiriSchemaODSIGNALAppForegrounded
+ __OBJC_$_INSTANCE_VARIABLES_ODSIGNALSiriSchemaODSIGNALClientEvent
+ __OBJC_$_PROP_LIST_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource
+ __OBJC_$_PROP_LIST_ODSIGNALSiriSchemaODSIGNALAppForegrounded
+ __OBJC_CLASS_PROTOCOLS_$_ODSIGNALSiriSchemaODSIGNALClientEvent(InstrumentationAdditions|InnerEventContainer|IsolationLevel)
+ __OBJC_CLASS_RO_$_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource
+ __OBJC_CLASS_RO_$_ODSIGNALSiriSchemaODSIGNALAppForegrounded
+ __OBJC_CLASS_RO_$_ODSIGNALSiriSchemaODSIGNALClientEvent
+ __OBJC_METACLASS_RO_$_ASRSpeechProfileSchemaASRSpeechProfileCascadeEntitySource
+ __OBJC_METACLASS_RO_$_ODSIGNALSiriSchemaODSIGNALAppForegrounded
+ __OBJC_METACLASS_RO_$_ODSIGNALSiriSchemaODSIGNALClientEvent
+ _symbolic _____ So022ASRSpeechProfileSchemaaB12UpdateReasonV
+ _symbolic _____ So35ASRSchemaASRSpeechProfileSizeBucketV
CStrings:
+ "ASRSPEECHPROFILESIZEBUCKET_128_KB_TO_256_KB"
+ "ASRSPEECHPROFILESIZEBUCKET_1_MB_TO_2_MB"
+ "ASRSPEECHPROFILESIZEBUCKET_256_KB_TO_512_KB"
+ "ASRSPEECHPROFILESIZEBUCKET_2_MB_TO_4_MB"
+ "ASRSPEECHPROFILESIZEBUCKET_32_KB_TO_64_KB"
+ "ASRSPEECHPROFILESIZEBUCKET_4_MB_TO_8_MB"
+ "ASRSPEECHPROFILESIZEBUCKET_512_KB_TO_1_MB"
+ "ASRSPEECHPROFILESIZEBUCKET_64_KB_TO_128_KB"
+ "ASRSPEECHPROFILESIZEBUCKET_8_MB_TO_16_MB"
+ "ASRSPEECHPROFILESIZEBUCKET_ABOVE_16_MB"
+ "ASRSPEECHPROFILESIZEBUCKET_UNDER_32_KB"
+ "ASRSPEECHPROFILESIZEBUCKET_UNKNOWN"
+ "ASRSPEECHPROFILEUPDATEREASON_ASSISTANT_ASSET_UPDATE"
+ "ASRSPEECHPROFILEUPDATEREASON_CASCADE_DATASET_CHANGE"
+ "ASRSPEECHPROFILEUPDATEREASON_DAILY_MAINTENANCE"
+ "ASRSPEECHPROFILEUPDATEREASON_FIRST_UNLOCK"
+ "ASRSPEECHPROFILEUPDATEREASON_MOBILE_ASSET_STARTUP_ACTIVATION"
+ "ASRSPEECHPROFILEUPDATEREASON_POST_INSTALL_MIGRATION"
+ "ASRSPEECHPROFILEUPDATEREASON_SIRI_LANGUAGE_CHANGE"
+ "ASRSPEECHPROFILEUPDATEREASON_SIRI_PREFERENCES_CHANGE"
+ "ASRSPEECHPROFILEUPDATEREASON_SYSTEM_SUBSCRIPTIONS_CHANGE"
+ "ASRSPEECHPROFILEUPDATEREASON_TRIAL_EXPERIMENT_UPDATE"
+ "ASRSPEECHPROFILEUPDATEREASON_UNKNOWN"
+ "ODSIGNAL_CLIENT_EVENT"
+ "appForegrounded"
+ "cascadeEntitySources"
+ "com.apple.aiml.siri.odsignal.ODSIGNALClientEvent"
+ "com.apple.aiml.siri.odsignal.ODSIGNALClientEvent.ODSIGNALAppForegrounded"
+ "numCandidateInteractions"
+ "numEnrolledEntities"
+ "speechProfileSize"
+ "speechProfileSizeBucket"
+ "speechProfileUpdateReason"
```
