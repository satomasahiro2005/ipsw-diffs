## Diagnostic-8357

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8357.appex/Diagnostic-8357`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b50` | `0xa978` | **`+0x8e28`** |
| `__TEXT.__auth_stubs` | `0x270` | `0x8f0` | **`+0x680`** |
| `__TEXT.__objc_stubs` | `0xa20` | `0x3c0` | **`-0x660`** |
| `__TEXT.__objc_methname` | `0x8ba` | `0x506` | **`-0x3b4`** |
| `__DATA_CONST.__const` | `0x198` | `0x518` | **`+0x380`** |
| `__DATA_CONST.__auth_got` | `0x148` | `0x480` | **`+0x338`** |
| `__TEXT.__eh_frame` | `—` | `0x308` | **`+0x308`** |
| `__TEXT.__const` | `0x10` | `0x2d4` | **`+0x2c4`** |
| `__TEXT.__swift5_typeref` | `—` | `0x2b3` | **`+0x2b3`** |
| `__DATA_CONST.__cfstring` | `0x240` | `—` | **`-0x240`** |
| `__DATA.__data` | `0xc0` | `0x2c8` | **`+0x208`** |
| `__TEXT.__unwind_info` | `0xf0` | `0x280` | **`+0x190`** |
| `__DATA.__objc_selrefs` | `0x350` | `0x1d0` | **`-0x180`** |
| `__DATA.__objc_const` | `0x3d0` | `0x298` | **`-0x138`** |
| `__TEXT.__swift5_capture` | `—` | `0x10c` | **`+0x10c`** |
| `__DATA.__bss` | `0x10` | `0x100` | **`+0xf0`** |
| `__DATA.__objc_data` | `0xa0` | `0x190` | **`+0xf0`** |
| `__TEXT.__swift5_fieldmd` | `—` | `0xec` | **`+0xec`** |
| `__TEXT.__cstring` | `0x155` | `0x83` | **`-0xd2`** |
| `__TEXT.__constg_swiftt` | `—` | `0xd0` | **`+0xd0`** |
| `__TEXT.__swift5_reflstr` | `—` | `0xc6` | **`+0xc6`** |
| `__TEXT.__objc_methlist` | `0x284` | `0x1c4` | **`-0xc0`** |
| `__DATA_CONST.__auth_ptr` | `—` | `0x98` | **`+0x98`** |
| `__TEXT.__gcc_except_tab` | `0x94` | `—` | **`-0x94`** |
| `__DATA_CONST.__got` | `0x88` | `0x100` | **`+0x78`** |
| `__DATA_CONST.__objc_intobj` | `0x60` | `—` | **`-0x60`** |
| `__TEXT.__objc_methtype` | `0x152` | `0x121` | **`-0x31`** |
| `__DATA_CONST.__objc_arrayobj` | `0x30` | `—` | **`-0x30`** |
| `__TEXT.__swift_as_cont` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `—` | `0x20` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x18` | `—` | **`-0x18`** |
| `__TEXT.__swift5_types` | `—` | `0x14` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `—` | `0x14` | **`+0x14`** |
| `__DATA_CONST.__objc_arraydata` | `0x10` | `—` | **`-0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x10` | `0x20` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0x56` | `0x5f` | **`+0x9`** |
| `__TEXT.__swift5_proto` | `—` | `0x8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_imageinfo`

### Other Changes

```diff

-1374.40.54.0.0
+1374.42.1.0.0

+  - /System/Library/Frameworks/UIKit.framework/UIKit

+  - /System/Library/PrivateFrameworks/CoreDiagnostics.framework/CoreDiagnostics

-  Functions: 35
-  Symbols:   73
-  CStrings:  177
+  - /usr/lib/swift/libswiftCore.dylib
+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftCoreImage.dylib
+  - /usr/lib/swift/libswiftCoreLocation.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftMetal.dylib
+  - /usr/lib/swift/libswiftOSLog.dylib
+  - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftQuartzCore.dylib
+  - /usr/lib/swift/libswiftSpatial.dylib
+  - /usr/lib/swift/libswiftUniformTypeIdentifiers.dylib
+  - /usr/lib/swift/libswiftXPC.dylib
+  - /usr/lib/swift/libswift_Builtin_float.dylib
+  - /usr/lib/swift/libswift_Concurrency.dylib
+  - /usr/lib/swift/libswiftos.dylib
+  - /usr/lib/swift/libswiftsimd.dylib
+  Functions: 190
+  Symbols:   119
+  CStrings:  96
Symbols:
+ _DiagnosticLogHandleForCategory
+ __Block_copy
+ __Block_release
+ ___chkstk_darwin
+ __swiftEmptyArrayStorage
+ __swiftEmptyDictionarySingleton
+ __swiftEmptySetSingleton
+ __swiftImmortalRefCount
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftCoreImage
+ __swift_FORCE_LOAD_$_swiftCoreLocation
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftMetal
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftObjectiveC
+ __swift_FORCE_LOAD_$_swiftQuartzCore
+ __swift_FORCE_LOAD_$_swiftSpatial
+ __swift_FORCE_LOAD_$_swiftUIKit
+ __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers
+ __swift_FORCE_LOAD_$_swiftXPC
+ __swift_FORCE_LOAD_$_swift_Builtin_float
+ __swift_FORCE_LOAD_$_swiftos
+ __swift_FORCE_LOAD_$_swiftsimd
+ _bzero
+ _malloc_size
+ _memmove
+ _objc_allocWithZone
+ _objc_msgSendSuper2
+ _objc_opt_self
+ _objc_retainAutoreleasedReturnValue
+ _objc_retain_x27
+ _objc_retain_x8
+ _swift_allocObject
+ _swift_arrayDestroy
+ _swift_arrayInitWithCopy
+ _swift_beginAccess
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_bridgeObjectRetain_n
+ _swift_cvw_assignWithCopy
+ _swift_cvw_assignWithTake
+ _swift_cvw_destroy
+ _swift_cvw_initWithCopy
+ _swift_cvw_initializeBufferWithCopyOfBuffer
+ _swift_deallocObject
+ _swift_dynamicCast
+ _swift_dynamicCastClass
+ _swift_dynamicCastObjCClassUnconditional
+ _swift_endAccess
+ _swift_getObjCClassFromMetadata
+ _swift_getObjCClassMetadata
+ _swift_getObjectType
+ _swift_getTypeByMangledNameInContext2
+ _swift_getWitnessTable
+ _swift_initStackObject
+ _swift_isClassType
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_once
+ _swift_release
+ _swift_release_x19
+ _swift_release_x20
+ _swift_release_x21
+ _swift_release_x22
+ _swift_release_x23
+ _swift_release_x24
+ _swift_release_x26
+ _swift_release_x27
+ _swift_release_x8
+ _swift_release_x9
+ _swift_retain_x19
+ _swift_retain_x2
+ _swift_retain_x20
+ _swift_retain_x24
+ _swift_retain_x8
+ _swift_setDeallocating
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_switch
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
- _OBJC_CLASS_$_NSArray
- _OBJC_CLASS_$_NSCharacterSet
- _OBJC_CLASS_$_NSConstantArray
- _OBJC_CLASS_$_NSConstantIntegerNumber
- _OBJC_CLASS_$_NSDate
- _OBJC_CLASS_$_NSDictionary
- _OBJC_CLASS_$_NSMutableArray
- _OBJC_CLASS_$_NSMutableDictionary
- _OBJC_CLASS_$_NSMutableSet
- _OBJC_CLASS_$_NSSet
- _OBJC_CLASS_$_PanicAndCrashHistoryController
- _OBJC_CLASS_$_PanicAndCrashHistoryInputs
- _OBJC_METACLASS_$_PanicAndCrashHistoryController
- _OBJC_METACLASS_$_PanicAndCrashHistoryInputs
- __Block_object_dispose
- __NSConcreteGlobalBlock
- __Unwind_Resume
- ___CFConstantStringClassReference
- ___NSDictionary0__struct
- ___objc_personality_v0
- _dispatch_once
- _objc_alloc
- _objc_autoreleaseReturnValue
- _objc_claimAutoreleasedReturnValue
- _objc_copyWeak
- _objc_destroyWeak
- _objc_enumerationMutation
- _objc_initWeak
- _objc_loadWeakRetained
- _objc_opt_class
- _objc_opt_isKindOfClass
- _objc_release_x28
- _objc_release_x9
- _objc_retainAutoreleaseReturnValue
- _objc_retain_x1
- _objc_retain_x2
- _objc_retain_x22
- _objc_storeStrong
- _objc_unsafeClaimAutoreleasedReturnValue
CStrings:
+ "Biome panic stream read failed: %@"
+ "cancel"
+ "collectionTask"
+ "dealloc"
+ "error"
+ "evaluateWithObject:"
+ "init"
+ "initWithInteger:"
+ "sinkWithCompletion:shouldContinue:"
+ "state"
+ "untitledLabelAt-"
- ""
- "%@"
- "%d"
- "*"
- ","
- "210"
- "@\"NSArray\""
- "@\"NSDictionary\""
- "@\"NSMutableSet\""
- "@\"NSSet\""
- "@\"PanicAndCrashHistoryInputs\""
- "@24@0:8@16"
- "@32@0:8@16@24"
- "AnyLogLine"
- "B16@?0@\"BMStoreEvent\"8"
- "T@\"NSArray\",&,N,V_applicationPredicates"
- "T@\"NSDictionary\",&,N,V_resultLabelFilters"
- "T@\"NSMutableSet\",&,N,V_logLineReferences"
- "T@\"NSSet\",&,N,V_applicationFilters"
- "T@\"NSSet\",&,N,V_logIds"
- "T@\"PanicAndCrashHistoryInputs\",&,N,V_inputs"
- "_applicationFilters"
- "_applicationPredicates"
- "_applyAppBundleFilters:"
- "_applyLabelsMap:"
- "_applylogLineTypes:"
- "_inputs"
- "_logIds"
- "_logLineReferences"
- "_resultLabelFilters"
- "addObject:"
- "addObjectsFromArray:"
- "allObjects"
- "appBundleFilter"
- "array"
- "arrayWithObject:"
- "componentsSeparatedByString:"
- "containsObject:"
- "copy"
- "count"
- "countByEnumeratingWithState:objects:count:"
- "dateWithTimeIntervalSinceReferenceDate:"
- "defaultLogLineLabelMap"
- "dictionary"
- "dictionaryWithObjects:forKeys:count:"
- "enumerateKeysAndObjectsUsingBlock:"
- "eventDate"
- "eventType"
- "filterWithIsIncluded:"
- "filteredArrayUsingPredicate:"
- "gatherBiomeRecords"
- "i"
- "initWithArray:"
- "intValue"
- "isEqualToString:"
- "length"
- "logLineLabelForIndex:andLogLineType:"
- "logLineReferences"
- "logLineTypes"
- "logLines"
- "null"
- "numberWithInt:"
- "objectAtIndex:"
- "objectForKey:"
- "parseLogsWithCollector:"
- "passesFilter:"
- "predicateWithFormat:"
- "processLine:"
- "q"
- "self LIKE %@"
- "set"
- "setApplicationFilters:"
- "setApplicationPredicates:"
- "setInputs:"
- "setLogIds:"
- "setLogLineReferences:"
- "setObject:forKey:"
- "setObject:forKeyedSubscript:"
- "setResultLabelFilters:"
- "setValue:forKey:"
- "setWithObjects:"
- "sinkWithCompletion:receiveInput:"
- "stringByTrimmingCharactersInSet:"
- "stringWithFormat:"
- "unsignedIntValue"
- "untitledLabelAt-%@"
- "uuidReference"
- "v16@?0@\"BMStoreEvent\"8"
- "v24@0:8@16"
- "v32@?0@\"NSString\"8@\"NSObject\"16^B24"
- "v8@?0"
- "whitespaceCharacterSet"
```
