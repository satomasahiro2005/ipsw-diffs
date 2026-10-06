## MultitouchSessionFilter

> `/System/Library/HIDPlugins/SessionFilters/MultitouchSessionFilter.plugin/MultitouchSessionFilter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e2c` | `0xf800` | **`+0xb9d4`** |
| `__DATA.__bss` | `0x40` | `0x980` | **`+0x940`** |
| `__TEXT.__auth_stubs` | `0x3b0` | `0xa00` | **`+0x650`** |
| `__TEXT.__const` | `0xa0` | `0x66a` | **`+0x5ca`** |
| `__DATA_CONST.__const` | `0x168` | `0x623` | **`+0x4bb`** |
| `__DATA_CONST.__auth_got` | `0x1e8` | `0x510` | **`+0x328`** |
| `__TEXT.__swift5_typeref` | `—` | `0x31f` | **`+0x31f`** |
| `__DATA.__objc_data` | `0x140` | `0x408` | **`+0x2c8`** |
| `__TEXT.__constg_swiftt` | `—` | `0x278` | **`+0x278`** |
| `__TEXT.__unwind_info` | `0x160` | `0x390` | **`+0x230`** |
| `__DATA.__objc_const` | `0xaa0` | `0xcb0` | **`+0x210`** |
| `__DATA.__data` | `0x120` | `0x328` | **`+0x208`** |
| `__TEXT.__swift5_fieldmd` | `—` | `0x1a0` | **`+0x1a0`** |
| `__TEXT.__swift5_reflstr` | `—` | `0x16e` | **`+0x16e`** |
| `__TEXT.__objc_methname` | `0xfa2` | `0x10c0` | **`+0x11e`** |
| `__TEXT.__cstring` | `0x140` | `0x24f` | **`+0x10f`** |
| `__DATA_CONST.__auth_ptr` | `—` | `0xe0` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x6e4` | `0x784` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0xc80` | `0xd20` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0x48` | `0xd8` | **`+0x90`** |
| `__TEXT.__swift5_assocty` | `—` | `0x90` | **`+0x90`** |
| `__TEXT.__objc_classname` | `0xa6` | `0xea` | **`+0x44`** |
| `__TEXT.__swift5_proto` | `—` | `0x44` | **`+0x44`** |
| `__DATA_CONST.__cfstring` | `0x160` | `0x1a0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x358` | `0x389` | **`+0x31`** |
| `__TEXT.__swift5_capture` | `—` | `0x30` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x338` | `0x354` | **`+0x1c`** |
| `__TEXT.__swift5_types` | `—` | `0x1c` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x480` | `0x498` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x20` | `0x30` | **`+0x10`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_imageinfo`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-9170.34.1.0.0
+10100.39.0.0.0

-  Functions: 141
-  Symbols:   407
-  CStrings:  306
+  - /usr/lib/swift/libswiftCore.dylib
+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftOSLog.dylib
+  - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftXPC.dylib
+  - /usr/lib/swift/libswift_Builtin_float.dylib
+  - /usr/lib/swift/libswiftos.dylib
+  Functions: 364
+  Symbols:   586
+  CStrings:  331
Symbols:
+ _AnalyticsSendEventLazy
+ _OBJC_CLASS_$_MTDigitizerHeatmapManager
+ _OBJC_CLASS_$_MTInputSessionManager
+ _OBJC_CLASS_$_NSMutableDictionary
+ _OBJC_METACLASS_$_MTDigitizerHeatmapManager
+ _OBJC_METACLASS_$_MTInputSessionManager
+ __Block_copy
+ __Block_release
+ __DATA_MTDigitizerHeatmapManager
+ __DATA_MTInputSessionManager
+ __INSTANCE_METHODS_MTDigitizerHeatmapManager
+ __INSTANCE_METHODS_MTInputSessionManager
+ __IVARS_MTDigitizerHeatmapManager
+ __IVARS_MTInputSessionManager
+ __METACLASS_DATA_MTDigitizerHeatmapManager
+ __METACLASS_DATA_MTInputSessionManager
+ __PROPERTIES_MTDigitizerHeatmapManager
+ __PROPERTIES_MTInputSessionManager
+ ___chkstk_darwin
+ ___swift_closure_destructor
+ ___swift_destroy_boxed_opaque_existential_0
+ ___swift_instantiateConcreteTypeFromMangledNameAbstractV2
+ ___swift_instantiateConcreteTypeFromMangledNameV2
+ ___swift_memcpy1_1
+ ___swift_memcpy2_1
+ ___swift_noop_void_return
+ ___swift_reflection_version
+ __swiftEmptyArrayStorage
+ __swiftEmptyDictionarySingleton
+ __swiftImmortalRefCount
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftCoreFoundation_$_MultitouchSessionFilter
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftDispatch_$_MultitouchSessionFilter
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftFoundation_$_MultitouchSessionFilter
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftOSLog_$_MultitouchSessionFilter
+ __swift_FORCE_LOAD_$_swiftObjectiveC
+ __swift_FORCE_LOAD_$_swiftObjectiveC_$_MultitouchSessionFilter
+ __swift_FORCE_LOAD_$_swiftXPC
+ __swift_FORCE_LOAD_$_swiftXPC_$_MultitouchSessionFilter
+ __swift_FORCE_LOAD_$_swift_Builtin_float
+ __swift_FORCE_LOAD_$_swift_Builtin_float_$_MultitouchSessionFilter
+ __swift_FORCE_LOAD_$_swiftos
+ __swift_FORCE_LOAD_$_swiftos_$_MultitouchSessionFilter
+ __swift_dead_method_stub
+ __swift_stdlib_malloc_size
+ _associated conformance 23MultitouchSessionFilter10DeviceType021_F4F32EDA989F136000A2J10ECE5BFF4A0LLOSHAASQ
+ _associated conformance 23MultitouchSessionFilter10DeviceType021_F4F32EDA989F136000A2J10ECE5BFF4A0LLOs12CaseIterableAA8AllCasessAEP_Sl
+ _associated conformance 23MultitouchSessionFilter10DeviceType33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLOSHAASQ
+ _associated conformance 23MultitouchSessionFilter10DeviceType33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLOs12CaseIterableAA8AllCasessAEP_Sl
+ _associated conformance 23MultitouchSessionFilter10HeatmapKey33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLVSHAASQ
+ _associated conformance 23MultitouchSessionFilter9TouchType33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLOSHAASQ
+ _associated conformance 23MultitouchSessionFilter9TouchType33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLOs12CaseIterableAA8AllCasessAEP_Sl
+ _block_copy_helper
+ _block_descriptor
+ _block_destroy_helper
+ _bzero
+ _free
+ _malloc_size
+ _memcpy
+ _memmove
+ _objc_allocWithZone
+ _objc_msgSend$copy
+ _objc_msgSend$debug
+ _objc_msgSend$init
+ _objc_msgSend$isEqualToString:
+ _objc_msgSend$setObject:forKeyedSubscript:
+ _objc_opt_self
+ _objc_retain
+ _objc_retainAutoreleasedReturnValue
+ _objc_retain_x23
+ _objc_retain_x26
+ _objc_retain_x28
+ _swift_allocObject
+ _swift_arrayDestroy
+ _swift_arrayInitWithCopy
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_beginAccess
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_bridgeObjectRetain_n
+ _swift_coroFrameAlloc
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithCopy
+ _swift_cvw_initWithTake
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_deallocObject
+ _swift_deletedMethodError
+ _swift_dynamicCast
+ _swift_endAccess
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getObjCClassMetadata
+ _swift_getObjectType
+ _swift_getSingletonMetadata
+ _swift_getTypeByMangledNameInContext2
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_getWitnessTable
+ _swift_initStackObject
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_release
+ _swift_release_x19
+ _swift_release_x20
+ _swift_release_x21
+ _swift_release_x23
+ _swift_release_x24
+ _swift_release_x25
+ _swift_release_x26
+ _swift_release_x8
+ _swift_retain_x2
+ _swift_retain_x20
+ _swift_setDeallocating
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _swift_stdlib_random
+ _swift_storeEnumTagSinglePayloadGeneric
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
+ _swift_updateClassMetadata2
+ _symbolic $sSY
+ _symbolic $ss12CaseIterableP
+ _symbolic SDy_____SaySaySuGGG 23MultitouchSessionFilter10HeatmapKey33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLV
+ _symbolic SDy_____SaySi3col_Si3rowtGG 23MultitouchSessionFilter10DeviceType33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLO
+ _symbolic SDy_____SdG 23MultitouchSessionFilter10DeviceType021_F4F32EDA989F136000A2J10ECE5BFF4A0LLO
+ _symbolic SDy__________G 23MultitouchSessionFilter10DeviceType021_F4F32EDA989F136000A2J10ECE5BFF4A0LLO AA0B0ACLLV
+ _symbolic SDy__________G 23MultitouchSessionFilter10DeviceType33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLO s6UInt32V
+ _symbolic SDy__________G 23MultitouchSessionFilter10HeatmapKey33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLV 10Foundation4DateV
+ _symbolic SDy__________G s6UInt64V 23MultitouchSessionFilter10DeviceType021_F4F32EDA989F136000A2K10ECE5BFF4A0LLO
+ _symbolic SDy__________G s6UInt64V 23MultitouchSessionFilter10DeviceType33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLO
+ _symbolic SS_So8NSObjectCt
+ _symbolic SS_ypt
+ _symbolic Say_____G 23MultitouchSessionFilter0B0021_F4F32EDA989F136000A2H10ECE5BFF4A0LLV
+ _symbolic Say_____G 23MultitouchSessionFilter10DeviceType021_F4F32EDA989F136000A2J10ECE5BFF4A0LLO
+ _symbolic Say_____G 23MultitouchSessionFilter10DeviceType33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLO
+ _symbolic Say_____G 23MultitouchSessionFilter9TouchType33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLO
+ _symbolic Si
+ _symbolic So22MTSessionFilterManagerC
+ _symbolic _____ 10Foundation4DateV
+ _symbolic _____ 23MultitouchSessionFilter07MTInputB7ManagerC
+ _symbolic _____ 23MultitouchSessionFilter0B0021_F4F32EDA989F136000A2H10ECE5BFF4A0LLV
+ _symbolic _____ 23MultitouchSessionFilter10DeviceType021_F4F32EDA989F136000A2J10ECE5BFF4A0LLO
+ _symbolic _____ 23MultitouchSessionFilter10DeviceType33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLO
+ _symbolic _____ 23MultitouchSessionFilter10HeatmapKey33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLV
+ _symbolic _____ 23MultitouchSessionFilter11DeviceTypes021_F4F32EDA989F136000A2J10ECE5BFF4A0LLV
+ _symbolic _____ 23MultitouchSessionFilter25MTDigitizerHeatmapManagerC
+ _symbolic _____ 23MultitouchSessionFilter9TouchType33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLO
+ _symbolic _____ 2os6LoggerV
+ _symbolic _____3key______5valuet 23MultitouchSessionFilter10DeviceType021_F4F32EDA989F136000A2J10ECE5BFF4A0LLO AA0B0ACLLV
+ _symbolic _____Sg 10Foundation4DateV
+ _symbolic _____Sg 23MultitouchSessionFilter0B0021_F4F32EDA989F136000A2H10ECE5BFF4A0LLV
+ _symbolic ___________t 23MultitouchSessionFilter10DeviceType021_F4F32EDA989F136000A2J10ECE5BFF4A0LLO AA0B0ACLLV
+ _symbolic ___________t 23MultitouchSessionFilter10HeatmapKey33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLV 10Foundation4DateV
+ _symbolic _____m 23MultitouchSessionFilter07MTInputB7ManagerC
+ _symbolic _____m 23MultitouchSessionFilter25MTDigitizerHeatmapManagerC
+ _symbolic _____ySSSo8NSObjectCG s18_DictionaryStorageC
+ _symbolic _____ySS_So8NSObjectCtG s23_ContiguousArrayStorageC
+ _symbolic _____ySS_yptG s23_ContiguousArrayStorageC
+ _symbolic _____ySSypG s18_DictionaryStorageC
+ _symbolic _____ySi3col_Si3rowtG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 23MultitouchSessionFilter0E0021_F4F32EDA989F136000A2K10ECE5BFF4A0LLV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 23MultitouchSessionFilter10DeviceType021_F4F32EDA989F136000A2M10ECE5BFF4A0LLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5UInt8V
+ _symbolic _____y_____SaySaySuGGG s18_DictionaryStorageC 23MultitouchSessionFilter10HeatmapKey33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLV
+ _symbolic _____y_____SaySi3col_Si3rowtGG s18_DictionaryStorageC 23MultitouchSessionFilter10DeviceType33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLO
+ _symbolic _____y_____SdG s18_DictionaryStorageC 23MultitouchSessionFilter10DeviceType021_F4F32EDA989F136000A2L10ECE5BFF4A0LLO
+ _symbolic _____y__________G s18_DictionaryStorageC 23MultitouchSessionFilter10DeviceType021_F4F32EDA989F136000A2L10ECE5BFF4A0LLO AC0D0AELLV
+ _symbolic _____y__________G s18_DictionaryStorageC 23MultitouchSessionFilter10DeviceType33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLO s6UInt32V
+ _symbolic _____y__________G s18_DictionaryStorageC 23MultitouchSessionFilter10HeatmapKey33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLV 10Foundation4DateV
+ _symbolic _____y__________G s18_DictionaryStorageC s6UInt64V 23MultitouchSessionFilter10DeviceType021_F4F32EDA989F136000A2M10ECE5BFF4A0LLO
+ _symbolic _____y__________G s18_DictionaryStorageC s6UInt64V 23MultitouchSessionFilter10DeviceType33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLO
+ _symbolic _____y______pG s23_ContiguousArrayStorageC s7CVarArgP
+ _symbolic _____y_____ypG s18_DictionaryStorageC s11AnyHashableV
+ _symbolic ypSg
+ _type_layout_string 23MultitouchSessionFilter10HeatmapKey33_4FAA1CE3482D4E1E94F33257A0AEC4E4LLV
CStrings:
+ "@\"NSDictionary\"8@?0"
+ "ActiveSessionCount"
+ "Class"
+ "CompletedSessionCount"
+ "MTDigitizerHeatmapManager"
+ "MTInputSessionManager"
+ "MonitoredServiceCount"
+ "Registered %{public}s service %{public}s"
+ "SessionFilterDebug"
+ "T@\"NSDictionary\",N,R"
+ "activeSessions"
+ "com.apple.Multitouch"
+ "com.apple.hid.DigitizerHeatMap"
+ "com.apple.hid.InputDeviceUsageMetrics"
+ "completedSessions"
+ "copy"
+ "heatmaps"
+ "isEqualToString:"
+ "lastCAEvent"
+ "logger"
+ "monitoredServices"
+ "otherDeviceTypeOverlap"
+ "setObject:forKeyedSubscript:"
+ "touchChangedEvents"
+ "touchedChangedPathId"
```
