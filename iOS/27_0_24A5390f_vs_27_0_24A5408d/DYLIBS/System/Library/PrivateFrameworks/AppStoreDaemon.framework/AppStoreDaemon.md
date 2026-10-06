## AppStoreDaemon

> `/System/Library/PrivateFrameworks/AppStoreDaemon.framework/AppStoreDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x83b58` | `0x8a818` | **`+0x6cc0`** |
| `__DATA.__bss` | `0x310` | `0x1f90` | **`+0x1c80`** |
| `__TEXT.__const` | `0x3d8` | `0x12a8` | **`+0xed0`** |
| `__AUTH_CONST.__const` | `0x8e0` | `0xf68` | **`+0x688`** |
| `__TEXT.__swift5_typeref` | `0x61` | `0x338` | **`+0x2d7`** |
| `__DATA.__data` | `0x18f8` | `0x1bc8` | **`+0x2d0`** |
| `__TEXT.__unwind_info` | `0x27c8` | `0x2a20` | **`+0x258`** |
| `__TEXT.__swift5_fieldmd` | `0x5c` | `0x278` | **`+0x21c`** |
| `__AUTH_CONST.__auth_got` | `0x610` | `0x7e8` | **`+0x1d8`** |
| `__AUTH_CONST.__cfstring` | `0x6e00` | `0x6ca0` | **`-0x160`** |
| `__TEXT.__constg_swiftt` | `0x7c` | `0x1d4` | **`+0x158`** |
| `__TEXT.__swift5_proto` | `0x18` | `0xfc` | **`+0xe4`** |
| `__TEXT.__objc_methlist` | `0xb3cc` | `0xb494` | **`+0xc8`** |
| `__TEXT.__eh_frame` | `—` | `0xa8` | **`+0xa8`** |
| `__TEXT.__cstring` | `0x5960` | `0x58bf` | **`-0xa1`** |
| `__AUTH_CONST.__objc_const` | `0x164d8` | `0x16560` | **`+0x88`** |
| `__AUTH.__objc_data` | `0x1680` | `0x16f0` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x9b` | `0x10b` | **`+0x70`** |
| `__DATA_CONST.__got` | `0x630` | `0x698` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x45d0` | `0x4638` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x4d86` | `0x4d41` | **`-0x45`** |
| `__TEXT.__swift5_types` | `0xc` | `0x3c` | **`+0x30`** |
| `__AUTH.__data` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x600` | `0x608` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x8` | `0x10` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xdfc` | `0xe00` | **`+0x4`** |

### Other Changes

```diff

-13.0.43.0.0
+13.0.52.2.1

-  Functions: 4487
-  Symbols:   7813
-  CStrings:  1426
+  Functions: 4702
+  Symbols:   7922
+  CStrings:  1421
Symbols:
+ +[ASDAppQuery queryForAllAppClips]
+ +[ASDAppQuery queryForAllApps]
+ +[ASDAppQuery queryForNoApps]
+ +[ASDAppQueryExecutor _executeQueryWithConditionsData:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]
+ +[ASDFactoryInstallResult supportsSecureCoding]
+ +[ASDInstallApps beginFactoryAppInstallsWithCompletionHandler:]
+ -[ASDAppQuery _executeQueryWithConditionsData:onDeviceWithPairingID:withCompletion:]
+ -[ASDAppQuery initWithConditionsData:]
+ -[ASDAppQuery initWithConditionsData:onDeviceWithPairingID:]
+ -[ASDAppQuery initWithConditionsData:queryExecutor:serviceBroker:notificationCenter:]
+ -[ASDAppQueryExecutor executeQueryWithConditionsData:onDeviceWithPairingID:remoteDeviceID:withResultHandler:]
+ -[ASDFactoryInstallResult .cxx_destruct]
+ -[ASDFactoryInstallResult bundleID]
+ -[ASDFactoryInstallResult description]
+ -[ASDFactoryInstallResult encodeWithCoder:]
+ -[ASDFactoryInstallResult error]
+ -[ASDFactoryInstallResult initWithCoder:]
+ -[ASDFactoryInstallResult initWithItemID:bundleID:installOrder:error:]
+ -[ASDFactoryInstallResult installOrder]
+ -[ASDFactoryInstallResult isSuccess]
+ -[ASDFactoryInstallResult itemID]
+ -[ASDPurchase isDSIDlessThatUpdates]
+ -[ASDPurchase setIsDSIDlessThatUpdates:]
+ _OBJC_CLASS_$_ASDAppQueryConditions
+ _OBJC_CLASS_$_ASDFactoryInstallResult
+ _OBJC_IVAR_$_ASDAppQuery._conditions
+ _OBJC_IVAR_$_ASDFactoryInstallResult._bundleID
+ _OBJC_IVAR_$_ASDFactoryInstallResult._error
+ _OBJC_IVAR_$_ASDFactoryInstallResult._installOrder
+ _OBJC_IVAR_$_ASDFactoryInstallResult._itemID
+ _OBJC_IVAR_$_ASDPurchase._isDSIDlessThatUpdates
+ _OBJC_METACLASS_$_ASDAppQueryConditions
+ _OBJC_METACLASS_$_ASDFactoryInstallResult
+ __CLASS_METHODS_ASDAppQueryConditions
+ __CLASS_PROPERTIES_ASDAppQueryConditions
+ __DATA_ASDAppQueryConditions
+ __INSTANCE_METHODS_ASDAppQueryConditions
+ __METACLASS_DATA_ASDAppQueryConditions
+ __OBJC_$_CLASS_METHODS_ASDFactoryInstallResult
+ __OBJC_$_CLASS_PROP_LIST_ASDFactoryInstallResult
+ __OBJC_$_INSTANCE_METHODS_ASDFactoryInstallResult
+ __OBJC_$_INSTANCE_VARIABLES_ASDFactoryInstallResult
+ __OBJC_$_PROP_LIST_ASDFactoryInstallResult
+ __OBJC_CLASS_PROTOCOLS_$_ASDFactoryInstallResult
+ __OBJC_CLASS_RO_$_ASDFactoryInstallResult
+ __OBJC_METACLASS_RO_$_ASDFactoryInstallResult
+ ___109-[ASDAppQueryExecutor executeQueryWithConditionsData:onDeviceWithPairingID:remoteDeviceID:withResultHandler:]_block_invoke
+ ___162+[ASDAppQueryExecutor _executeQueryWithConditionsData:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke
+ ___162+[ASDAppQueryExecutor _executeQueryWithConditionsData:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke_2
+ ___162+[ASDAppQueryExecutor _executeQueryWithConditionsData:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke_3
+ ___162+[ASDAppQueryExecutor _executeQueryWithConditionsData:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke_4
+ ___162+[ASDAppQueryExecutor _executeQueryWithConditionsData:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke_5
+ ___162+[ASDAppQueryExecutor _executeQueryWithConditionsData:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke_6
+ ___33-[ASDExtensionMonitor invalidate]_block_invoke
+ ___63+[ASDInstallApps beginFactoryAppInstallsWithCompletionHandler:]_block_invoke
+ ___63+[ASDInstallApps beginFactoryAppInstallsWithCompletionHandler:]_block_invoke_2
+ ___63+[ASDInstallApps beginFactoryAppInstallsWithCompletionHandler:]_block_invoke_3
+ ___84-[ASDAppQuery _executeQueryWithConditionsData:onDeviceWithPairingID:withCompletion:]_block_invoke
+ ___ErrorWithUnderlyingErrorAndConditionsData
+ ___swift_instantiateConcreteTypeFromMangledNameAbstractV2
+ ___swift_instantiateConcreteTypeFromMangledNameV2
+ ___swift_memcpy17_8
+ ___swift_memcpy1_1
+ ___swift_project_boxed_opaque_existential_1
+ __swiftImmortalRefCount
+ __swift_stdlib_malloc_size
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO04BetaA10CodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO04BetaA10CodingKeysOs0M3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO04BetaA10CodingKeysOs0M3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06OcelotA10CodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06OcelotA10CodingKeysOs0M3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06OcelotA10CodingKeysOs0M3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06SystemA10CodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06SystemA10CodingKeysOs0M3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06SystemA10CodingKeysOs0M3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0A14ClipCodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0A14ClipCodingKeysOs0M3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0A14ClipCodingKeysOs0M3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0B17ItemIDsCodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0B17ItemIDsCodingKeysOs0N3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0B17ItemIDsCodingKeysOs0N3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0bA10CodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0bA10CodingKeysOs0L3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0bA10CodingKeysOs0L3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO10CodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO10CodingKeysOs0L3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO10CodingKeysOs0L3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO15NeverCodingKeysOs0M3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO15NeverCodingKeysOs0M3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO19BundleIDsCodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO19BundleIDsCodingKeysOs0N3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO19BundleIDsCodingKeysOs0N3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO20BundlePathCodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO20BundlePathCodingKeysOs0N3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO20BundlePathCodingKeysOs0N3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO26SoftwarePlatformCodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO26SoftwarePlatformCodingKeysOs0N3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO26SoftwarePlatformCodingKeysOs0N3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLOSHAASQ
+ _get_enum_tag_for_layout_string 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO
+ _malloc_size
+ _memcpy
+ _memmove
+ _swift_allocError
+ _swift_allocObject
+ _swift_arrayInitWithCopy
+ _swift_errorRelease
+ _swift_getObjCClassFromMetadata
+ _swift_getObjCClassMetadata
+ _swift_getTypeByMangledNameInContext2
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_once
+ _swift_release_x19
+ _swift_release_x20
+ _swift_release_x23
+ _swift_retain
+ _swift_unexpectedError
+ _swift_unknownObjectRelease
+ _swift_willThrow
+ _symbolic Say_____G 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO
+ _symbolic Say_____G s5Int64V
+ _symbolic Sb
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO04BetaA10CodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06OcelotA10CodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06SystemA10CodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0A14ClipCodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0B17ItemIDsCodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0bA10CodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO10CodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO15NeverCodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO19BundleIDsCodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO20BundlePathCodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO26SoftwarePlatformCodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO04BetaD10CodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06OcelotD10CodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06SystemD10CodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0D14ClipCodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0E17ItemIDsCodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0eD10CodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO10CodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO15NeverCodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO19BundleIDsCodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO20BundlePathCodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO26SoftwarePlatformCodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO04BetaD10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06OcelotD10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06SystemD10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0D14ClipCodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0E17ItemIDsCodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0eD10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO15NeverCodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO19BundleIDsCodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO20BundlePathCodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO26SoftwarePlatformCodingKeysO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5Int64V
+ _symbolic _____y______pG s23_ContiguousArrayStorageC s7CVarArgP
+ _symbolic ypXmT______t s13DecodingErrorO7ContextV
+ _type_layout_string 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO
- +[ASDAppQuery anyWithPredicate:withResultHandler:]
- +[ASDAppQuery queryDefaultPairedWatchForBetaApps]
- +[ASDAppQuery queryWithPredicate:]
- +[ASDAppQuery queryWithPredicate:onDeviceWithPairingID:]
- +[ASDAppQuery queryWithPredicate:onPairedDevice:]
- +[ASDAppQueryExecutor _executeQueryWithPredicate:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]
- +[ASDInstallApps beginSINFLessAppInstallsWithCompletionHandler:]
- +[ASDSINFLessInstallResult supportsSecureCoding]
- -[ASDAppQuery _executeQueryWithPredicate:onDeviceWithPairingID:withCompletion:]
- -[ASDAppQuery initWithPredicate:]
- -[ASDAppQuery initWithPredicate:onDeviceWithPairingID:]
- -[ASDAppQuery initWithPredicate:onPairedDevice:]
- -[ASDAppQuery initWithPredicate:queryExecutor:serviceBroker:notificationCenter:]
- -[ASDAppQuery predicate]
- -[ASDAppQueryExecutor executeQueryWithPredicate:onDeviceWithPairingID:remoteDeviceID:withResultHandler:]
- -[ASDSINFLessInstallResult .cxx_destruct]
- -[ASDSINFLessInstallResult bundleID]
- -[ASDSINFLessInstallResult description]
- -[ASDSINFLessInstallResult encodeWithCoder:]
- -[ASDSINFLessInstallResult error]
- -[ASDSINFLessInstallResult initWithCoder:]
- -[ASDSINFLessInstallResult initWithItemID:bundleID:installOrder:error:]
- -[ASDSINFLessInstallResult installOrder]
- -[ASDSINFLessInstallResult isSuccess]
- -[ASDSINFLessInstallResult itemID]
- _OBJC_CLASS_$_ASDSINFLessInstallResult
- _OBJC_IVAR_$_ASDAppQuery._predicate
- _OBJC_IVAR_$_ASDSINFLessInstallResult._bundleID
- _OBJC_IVAR_$_ASDSINFLessInstallResult._error
- _OBJC_IVAR_$_ASDSINFLessInstallResult._installOrder
- _OBJC_IVAR_$_ASDSINFLessInstallResult._itemID
- _OBJC_METACLASS_$_ASDSINFLessInstallResult
- __OBJC_$_CLASS_METHODS_ASDSINFLessInstallResult
- __OBJC_$_CLASS_PROP_LIST_ASDSINFLessInstallResult
- __OBJC_$_INSTANCE_METHODS_ASDSINFLessInstallResult
- __OBJC_$_INSTANCE_VARIABLES_ASDSINFLessInstallResult
- __OBJC_$_PROP_LIST_ASDSINFLessInstallResult
- __OBJC_CLASS_PROTOCOLS_$_ASDSINFLessInstallResult
- __OBJC_CLASS_RO_$_ASDSINFLessInstallResult
- __OBJC_METACLASS_RO_$_ASDSINFLessInstallResult
- ___104-[ASDAppQueryExecutor executeQueryWithPredicate:onDeviceWithPairingID:remoteDeviceID:withResultHandler:]_block_invoke
- ___157+[ASDAppQueryExecutor _executeQueryWithPredicate:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke
- ___157+[ASDAppQueryExecutor _executeQueryWithPredicate:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke_2
- ___157+[ASDAppQueryExecutor _executeQueryWithPredicate:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke_3
- ___157+[ASDAppQueryExecutor _executeQueryWithPredicate:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke_4
- ___157+[ASDAppQueryExecutor _executeQueryWithPredicate:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke_5
- ___157+[ASDAppQueryExecutor _executeQueryWithPredicate:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke_6
- ___50+[ASDAppQuery anyWithPredicate:withResultHandler:]_block_invoke
- ___64+[ASDInstallApps beginSINFLessAppInstallsWithCompletionHandler:]_block_invoke
- ___64+[ASDInstallApps beginSINFLessAppInstallsWithCompletionHandler:]_block_invoke_2
- ___64+[ASDInstallApps beginSINFLessAppInstallsWithCompletionHandler:]_block_invoke_3
- ___79-[ASDAppQuery _executeQueryWithPredicate:onDeviceWithPairingID:withCompletion:]_block_invoke
- ___ErrorWithUnderlyingErrorAndPredicate
CStrings:
+ " isDSIDlessThatUpdates: 1"
+ "<invalid conditions>"
+ "AppStoreDaemon/ASDAppQuery.swift"
+ "Factory app installs failed to acquire installation service: %{public}@"
+ "Invalid number of keys found, expected one."
+ "isDSIDlessThatUpdates"
+ "isStoreApp == %@"
+ "isSystemApp == %@"
+ "storeItemID IN %@"
- "+[ASDAppQuery queryDefaultPairedWatchForBetaApps:]"
- "+[ASDAppQuery queryWithPredicate:onPairedDevice:]"
- "-[ASDAppQuery initWithPredicate:onPairedDevice:]"
- "Please note that this ASDAppQuery doesn't return real results yet."
- "SINF-less app installs failed to acquire installation service: %{public}@"
- "bundleID IN %@"
- "isAppClip == NO AND isBetaApp == YES AND storeItemID IN %@"
- "isAppClip == NO AND isStoreApp == YES"
- "isAppClip == NO AND isStoreApp == YES AND storeItemID IN %@"
- "isAppClip == YES AND isStoreApp == YES AND storeItemID == %lld"
- "isBetaApp == YES"
- "isOcelot == YES"
- "isSystemApp == YES"
- "softwarePlatform == %ld"
```
