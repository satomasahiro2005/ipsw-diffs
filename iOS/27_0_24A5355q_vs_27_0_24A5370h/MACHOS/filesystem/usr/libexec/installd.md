## installd

> `/usr/libexec/installd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x67154` | `0x6da34` | **`+0x68e0`** |
| `__TEXT.__auth_stubs` | `0x1000` | `0x16e0` | **`+0x6e0`** |
| `__TEXT.__cstring` | `0x17efd` | `0x18303` | **`+0x406`** |
| `__TEXT.__objc_methname` | `0xcd9b` | `0xd133` | **`+0x398`** |
| `__DATA_CONST.__auth_got` | `0x810` | `0xb80` | **`+0x370`** |
| `__TEXT.__objc_stubs` | `0x8ac0` | `0x8dc0` | **`+0x300`** |
| `__DATA.__objc_const` | `0x5e48` | `0x6138` | **`+0x2f0`** |
| `__DATA_CONST.__const` | `0x1478` | `0x16d0` | **`+0x258`** |
| `__TEXT.__unwind_info` | `0x1268` | `0x1430` | **`+0x1c8`** |
| `__TEXT.__objc_methlist` | `0x35cc` | `0x3774` | **`+0x1a8`** |
| `__TEXT.__eh_frame` | `—` | `0x158` | **`+0x158`** |
| `__DATA.__data` | `0xa78` | `0xb90` | **`+0x118`** |
| `__DATA.__objc_data` | `0xc80` | `0xd60` | **`+0xe0`** |
| `__TEXT.__swift5_typeref` | `—` | `0xd2` | **`+0xd2`** |
| `__TEXT.__objc_methtype` | `0x22ac` | `0x2375` | **`+0xc9`** |
| `__DATA.__objc_selrefs` | `0x2788` | `0x2840` | **`+0xb8`** |
| `__DATA_CONST.__got` | `0x390` | `0x448` | **`+0xb8`** |
| `__TEXT.__const` | `0x120` | `0x1c8` | **`+0xa8`** |
| `__TEXT.__swift5_capture` | `—` | `0xa8` | **`+0xa8`** |
| `__TEXT.__objc_classname` | `0x5ee` | `0x64f` | **`+0x61`** |
| `__TEXT.__gcc_except_tab` | `0x3b04` | `0x3b64` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `—` | `0x54` | **`+0x54`** |
| `__DATA_CONST.__auth_ptr` | `0x18` | `0x68` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x14ee` | `0x14a7` | **`-0x47`** |
| `__DATA.__bss` | `0x1a0` | `0x1e0` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0xa4e0` | `0xa520` | **`+0x40`** |
| `__DATA_CONST.__objc_protolist` | `0xc8` | `0xe0` | **`+0x18`** |
| `__DATA_CONST.__objc_protorefs` | `0x18` | `0x30` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x140` | `0x150` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__swift5_types` | `—` | `0x8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_imageinfo`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1655.0.0.0.0
+1660.0.0.0.0

-  Functions: 1374
-  Symbols:   384
-  CStrings:  3806
+  - /usr/lib/swift/libswiftCore.dylib
+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftXPC.dylib
+  - /usr/lib/swift/libswift_Builtin_float.dylib
+  - /usr/lib/swift/libswiftos.dylib
+  Functions: 1534
+  Symbols:   532
+  CStrings:  3869
Symbols:
+ _$s10Foundation22_convertErrorToNSErrorySo0E0Cs0C0_pF
+ _$s10Foundation22_convertNSErrorToErrorys0E0_pSo0C0CSgF
+ _$s10Foundation3URLV13DirectoryHintO03notC0yA2EmFWC
+ _$s10Foundation3URLV13DirectoryHintOMa
+ _$s10Foundation3URLV19_bridgeToObjectiveCSo5NSURLCyF
+ _$s10Foundation3URLV36_unconditionallyBridgeFromObjectiveCyACSo5NSURLCSgFZ
+ _$s10Foundation3URLV9appending4path13directoryHintACx_AC09DirectoryF0OtSyRzlF
+ _$s10Foundation3URLVMa
+ _$s10Foundation3URLVMn
+ _$s10Foundation3URLVSHAAMc
+ _$s10Foundation3URLVSQAAMc
+ _$s10Foundation4DataV19_bridgeToObjectiveCSo6NSDataCyF
+ _$s10Foundation4DataV36_unconditionallyBridgeFromObjectiveCyACSo6NSDataCSgFZ
+ _$s2os6LoggerV9logObjectSo03OS_a1_C0Cvg
+ _$s2os6LoggerV9subsystem8categoryACSS_SStcfC
+ _$s2os6LoggerVMa
+ _$s8Dispatch0A3QoSV11unspecifiedACvgZ
+ _$s8Dispatch0A3QoSVMa
+ _$s8Dispatch0A9PredicateO7onQueueyACSo17OS_dispatch_queueCcACmFWC
+ _$s8Dispatch0A9PredicateOMa
+ _$s8Dispatch25_dispatchPreconditionTestySbAA0A9PredicateOF
+ _$sBi64_WV
+ _$sSD10FoundationE19_bridgeToObjectiveCSo12NSDictionaryCyF
+ _$sSH13_rawHashValue4seedS2i_tFTj
+ _$sSQ2eeoiySbx_xtFZTj
+ _$sSS10FoundationE19_bridgeToObjectiveCSo8NSStringCyF
+ _$sSS10FoundationE36_unconditionallyBridgeFromObjectiveCySSSo8NSStringCSgFZ
+ _$sSS11utf8CStrings15ContiguousArrayVys4Int8VGvg
+ _$sSS4hash4intoys6HasherVz_tF
+ _$sSS6appendyySSF
+ _$sSS8UTF8ViewV13_foreignCountSiyF
+ _$sSSN
+ _$sSSSHsWP
+ _$sSSSysMc
+ _$sSayxGSTsMc
+ _$sSh10FoundationE19_bridgeToObjectiveCSo5NSSetCyF
+ _$sSo13os_log_type_ta0A0E5faultABvgZ
+ _$sSo17NSKeyedUnarchiverC10FoundationE16unarchivedObject7ofClass4fromxSgxm_AC4DataVtKSo8NSObjectCRbzSo8NSCodingRzlFZ
+ _$sSo17OS_dispatch_queueC8DispatchE20AutoreleaseFrequencyO8workItemyA2EmFWC
+ _$sSo17OS_dispatch_queueC8DispatchE20AutoreleaseFrequencyOMa
+ _$sSo24OS_dispatch_queue_serialC8DispatchE10AttributesVMa
+ _$sSo24OS_dispatch_queue_serialC8DispatchE10AttributesVMn
+ _$sSo24OS_dispatch_queue_serialC8DispatchE10AttributesVs10SetAlgebraACMc
+ _$sSo24OS_dispatch_queue_serialC8DispatchE5label3qos10attributes20autoreleaseFrequency6targetABSS_AC0E3QoSVAbCE10AttributesVSo0a1_b1_C0CACE011AutoreleaseJ0OANSgtcfC
+ _$sSo7NSCoderC10FoundationE12decodeObject2of6forKeyxSgxm_SStSo8NSObjectCRbzSo8NSCodingRzlF
+ _$sSuN
+ _$sSus23CustomStringConvertiblesWP
+ _$sSy10FoundationE4hashSivg
+ _$ss018_bridgeAnyObjectToB0yypyXlSgF
+ _$ss10SetAlgebraPyxqd__ncSTRd__7ElementQyd__ACRtzlufCTj
+ _$ss11_SetStorageC4copy8originalAByxGs05__RawaB0C_tFZ
+ _$ss11_SetStorageC6resize8original8capacity4moveAByxGs05__RawaB0C_SiSbtFZ
+ _$ss11_SetStorageCMn
+ _$ss11_StringGutsV16_foreignCopyUTF84intoSiSgSrys5UInt8VG_tF
+ _$ss11_StringGutsV4growyySiF
+ _$ss11_StringGutsVN
+ _$ss12StaticStringV11descriptionSSvg
+ _$ss13_StringObjectV10sharedUTF8SRys5UInt8VGvg
+ _$ss18_DictionaryStorageC4copy8originalAByxq_Gs05__RawaB0C_tFZ
+ _$ss18_DictionaryStorageC6resize8original8capacity4moveAByxq_Gs05__RawaB0C_SiSbtFZ
+ _$ss18_DictionaryStorageC8allocate8capacityAByxq_GSi_tFZ
+ _$ss18_DictionaryStorageCMn
+ _$ss20__StaticArrayStorageCN
+ _$ss23CustomStringConvertibleP11descriptionSSvgTj
+ _$ss23_ContiguousArrayStorageCMn
+ _$ss26DefaultStringInterpolationV06appendC0yyxlF
+ _$ss27_stringCompareWithSmolCheck__9expectingSbs11_StringGutsV_ADs01_G16ComparisonResultOtF
+ _$ss50ELEMENT_TYPE_OF_SET_VIOLATES_HASHABLE_REQUIREMENTSys5NeverOypXpF
+ _$ss53KEY_TYPE_OF_DICTIONARY_VIOLATES_HASHABLE_REQUIREMENTSys5NeverOypXpF
+ _$ss5ErrorMp
+ _$ss5ErrorWS
+ _$ss5UInt8VMn
+ _$ss6HasherV5_seedABSi_tcfC
+ _$ss6HasherV9_finalizeSiyF
+ _$ss6ResultOMn
+ _$sypN
+ _$sytWV
+ _OBJC_CLASS_$_OS_dispatch_queue_serial
+ __Block_copy
+ __Block_release
+ __os_log_impl
+ __swiftEmptyArrayStorage
+ __swiftEmptyDictionarySingleton
+ __swiftEmptySetSingleton
+ __swiftImmortalRefCount
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftObjectiveC
+ __swift_FORCE_LOAD_$_swiftXPC
+ __swift_FORCE_LOAD_$_swift_Builtin_float
+ __swift_FORCE_LOAD_$_swiftos
+ __swift_stdlib_reportUnimplementedInitializer
+ _malloc_size
+ _memcpy
+ _memmove
+ _objc_allocWithZone
+ _objc_opt_self
+ _swift_allocObject
+ _swift_arrayDestroy
+ _swift_beginAccess
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_deallocObject
+ _swift_deallocPartialClassInstance
+ _swift_dynamicCast
+ _swift_dynamicCastMetatypeUnconditional
+ _swift_dynamicCastObjCClass
+ _swift_endAccess
+ _swift_errorRelease
+ _swift_errorRetain
+ _swift_getErrorValue
+ _swift_getForeignTypeMetadata
+ _swift_getObjCClassFromMetadata
+ _swift_getObjCClassFromObject
+ _swift_getObjCClassMetadata
+ _swift_getObjectType
+ _swift_getTypeByMangledNameInContext2
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_getWitnessTable
+ _swift_isEscapingClosureAtFileLocation
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_once
+ _swift_release
+ _swift_release_x12
+ _swift_release_x19
+ _swift_release_x20
+ _swift_release_x21
+ _swift_release_x22
+ _swift_release_x23
+ _swift_release_x24
+ _swift_release_x25
+ _swift_release_x26
+ _swift_release_x27
+ _swift_release_x8
+ _swift_retain_x19
+ _swift_retain_x2
+ _swift_retain_x20
+ _swift_retain_x21
+ _swift_retain_x22
+ _swift_retain_x25
+ _swift_retain_x26
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
+ _swift_willThrow
+ _swift_willThrowTypedImpl
CStrings:
+ " for SYSTEM/ANY persona extension; skipping"
+ " into MIPluginDataContainer"
+ "%{public}s: %{public}s"
+ "-[MIClientConnection rebuildBuiltInContentMappingWithCompletion:]"
+ "; removing journal"
+ "; replaying operation"
+ "?"
+ "@\"OS_dispatch_queue\""
+ "@24@0:8^v16"
+ "@32@0:8Q16@24"
+ "@40@0:8Q16@24Q32"
+ "B16@?0@\"MIContainer\"8"
+ "B40@0:8Q16@24^@32"
+ "Client %@ reported persona lifecycle event (%@) for %@"
+ "Exceeded maximum number of retry attempts for journal entry "
+ "Expected to find associatedBuiltInBundleURL on data container "
+ "Failed to cast personaUniqueString into String"
+ "Failed to decode MIPersonaLifecycleEventType"
+ "Failed to deserialize MIPersonaLifecycleEventJournalEntry: "
+ "Failed to reconcile persona lifecycle event journal: "
+ "Failed to remove journal: "
+ "Failed to report persona event (%@) for %@: %@"
+ "Found journal entry "
+ "MIPersonaLifecycleEventJournalEntry"
+ "MIPersonaLifecycleEventManager"
+ "PersonaLifecycleEventJournal.plist"
+ "Rebuild built-in content mapping requested by client %@"
+ "T@\"MIPersonaLifecycleEventManager\",N,R"
+ "T@\"NSString\",N,R"
+ "T@\"OS_dispatch_queue\",N,R,VinternalQueue"
+ "TB,N,R"
+ "TQ,N,R,VeventType"
+ "TQ,N,R,VretryCount"
+ "Tq,N,R"
+ "Unexpected type of entry in journal"
+ "Unknown client %@ asked to rebuild the built-in content mapping"
+ "__ObjC.MIPersonaLifecycleEventJournalEntry"
+ "_launchServicesOperationManager"
+ "_launchServicesRegistrationQueue"
+ "_lockIdentifiers"
+ "_onQueue_reconcile()"
+ "_onQueue_reportPersonaAssociationsUnderLock(_:forPersonaUniqueString:)"
+ "_personaAssociationManager"
+ "_pluginDataContainerClass"
+ "_removeJournal"
+ "_removeJournal()"
+ "_unlockIdentifiers"
+ "associatedPersonasUsingParentPersona:didUseParentPersona:error:"
+ "com.apple.mobileinstallation.MIPersonaLifecycleEventManager.internalQueue"
+ "decodeIntegerForKey:"
+ "encodeInteger:forKey:"
+ "eventType"
+ "incrementingRetryCount"
+ "init()"
+ "init(coder:)"
+ "initWithContentsOfURL:options:error:"
+ "initWithDomain:code:userInfo:"
+ "initWithEventType:personaUniqueString:"
+ "initWithEventType:personaUniqueString:retryCount:"
+ "journalURL"
+ "q16@0:8"
+ "reScanCoreServicesApps"
+ "reScanInternalApps"
+ "reScanSystemApps"
+ "rebuildBuiltInContentMappingWithCompletion:"
+ "reconcile()"
+ "reportEvent:forPersonaUniqueString:error:"
+ "retryCount"
- "%s: Expected to find bundleURL on data container for SYSTEM/ANY persona extension %@; skipping"
- "-[MIClientConnection reportPersonaLifecycleEventForUniqueString:eventType:withCompletion:]_block_invoke"
- "B16@?0@\"MIPluginDataContainer\"8"
- "Client %@ reported persona lifecycle event %@ for %@"
- "Expected to find bundleURL on data container for SYSTEM/ANY persona extension %@; skipping"
```
