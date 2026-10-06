## SurveyKitAppPlugin

> `/System/Library/Health/FeedItemPlugins/SurveyKitAppPlugin.healthplugin/SurveyKitAppPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14d34` | `0x30238` | **`+0x1b504`** |
| `__TEXT.__eh_frame` | `0x8a4` | `0x183c` | **`+0xf98`** |
| `__TEXT.__const` | `0x6a2` | `0xeb0` | **`+0x80e`** |
| `__DATA.__bss` | `0x558` | `0xd18` | **`+0x7c0`** |
| `__TEXT.__unwind_info` | `0x4f0` | `0xad0` | **`+0x5e0`** |
| `__AUTH_CONST.__auth_got` | `0xb00` | `0x1078` | **`+0x578`** |
| `__AUTH.__data` | `0x2c0` | `0x7e0` | **`+0x520`** |
| `__DATA.__data` | `0x520` | `0xa40` | **`+0x520`** |
| `__AUTH_CONST.__objc_const` | `0x120` | `0x518` | **`+0x3f8`** |
| `__TEXT.__swift5_typeref` | `0x3e9` | `0x713` | **`+0x32a`** |
| `__TEXT.__oslogstring` | `0x1e0` | `0x460` | **`+0x280`** |
| `__AUTH_CONST.__const` | `0x339` | `0x5a9` | **`+0x270`** |
| `__TEXT.__swift5_fieldmd` | `0x164` | `0x3c8` | **`+0x264`** |
| `__TEXT.__constg_swiftt` | `0x29c` | `0x4f8` | **`+0x25c`** |
| `__TEXT.__swift5_reflstr` | `0x141` | `0x35b` | **`+0x21a`** |
| `__TEXT.__cstring` | `0x2c6` | `0x4d5` | **`+0x20f`** |
| `__AUTH.__objc_data` | `0x50` | `0x1f0` | **`+0x1a0`** |
| `__TEXT.__swift5_capture` | `0xd4` | `0x1cc` | **`+0xf8`** |
| `__DATA_DIRTY.__data` | `0xb0` | `0x18` | **`-0x98`** |
| `__TEXT.__swift_as_cont` | `0x4c` | `0xe0` | **`+0x94`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x68` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `—` | `0x64` | **`+0x64`** |
| `__TEXT.__swift5_assocty` | `0x98` | `0xf8` | **`+0x60`** |
| `__TEXT.__swift_as_ret` | `0x24` | `0x80` | **`+0x5c`** |
| `__DATA_CONST.__objc_selrefs` | `0x48` | `0x98` | **`+0x50`** |
| `__TEXT.__swift_as_entry` | `0x24` | `0x70` | **`+0x4c`** |
| `__TEXT.__swift5_proto` | `0x30` | `0x6c` | **`+0x3c`** |
| `__TEXT.__swift5_types` | `0x20` | `0x44` | **`+0x24`** |
| `__DATA_CONST.__objc_classlist` | `0x10` | `0x30` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `—` | `0x10` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `—` | `0x8` | **`+0x8`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

+  - /System/Library/PrivateFrameworks/UIFoundation.framework/UIFoundation

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 366
-  Symbols:   138
-  CStrings:  29
+  Functions: 779
+  Symbols:   190
+  CStrings:  45
Symbols:
+ _OBJC_CLASS_$_HKHealthFactSample
+ _OBJC_CLASS_$_HKHealthFactSampleType
+ _OBJC_CLASS_$_HKSample
+ _OBJC_CLASS_$_NSBundle
+ _OBJC_CLASS_$_NSPredicate
+ _OBJC_CLASS_$_UICollectionViewListCell
+ _OBJC_CLASS_$_UIColor
+ _OBJC_CLASS_$_UIFont
+ _OBJC_CLASS_$_UIImage
+ _OBJC_METACLASS_$_NSObject
+ _OBJC_METACLASS_$_UICollectionViewListCell
+ _UIFontTextStyleBody
+ _UIFontWeightSemibold
+ __swiftEmptyDictionarySingleton
+ __swiftEmptySetSingleton
+ _bzero
+ _objc_autoreleaseReturnValue
+ _objc_msgSendSuper2
+ _objc_release_x24
+ _objc_release_x25
+ _objc_release_x26
+ _objc_release_x28
+ _objc_retain_x20
+ _objc_retain_x22
+ _objc_retain_x24
+ _objc_retain_x25
+ _objc_retain_x26
+ _objc_retain_x28
+ _objc_retain_x8
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_coroFrameAlloc
+ _swift_deallocPartialClassInstance
+ _swift_defaultActor_deallocate
+ _swift_defaultActor_destroy
+ _swift_defaultActor_initialize
+ _swift_dynamicCast
+ _swift_dynamicCastObjCClass
+ _swift_getEnumCaseMultiPayload
+ _swift_getErrorValue
+ _swift_getObjCClassFromMetadata
+ _swift_getTupleTypeMetadata3
+ _swift_release_x12
+ _swift_retain_x21
+ _swift_retain_x23
+ _swift_retain_x24
+ _swift_retain_x25
+ _swift_retain_x26
+ _swift_retain_x27
+ _swift_retain_x28
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
- _swift_bridgeObjectRetain_n
CStrings:
+ "SurveyDataListViewModel:load"
+ "SurveyKitAppPlugin/HealthFactDetailRows.swift"
+ "SurveyKitAppPlugin/HealthFactScoreDetailView.swift"
+ "SurveyKitAppPlugin/SurveyDataListView.swift"
+ "SurveyKitAppPlugin/SurveyKitAppPluginHealthPluginDelegate.swift"
+ "SurveyKitAppPlugin/SurveyMeasureSearchCell.swift"
+ "Surveys data list appeared"
+ "View.task @ SurveyKitAppPlugin/HealthFactScoreDetailView.swift:"
+ "View.task @ SurveyKitAppPlugin/SurveyDataListView.swift:"
+ "[%{public}s] Actions plugin cannot perform work without a HealthPlatformOrchestrationContext, ignoring context: %{private}s"
+ "[%{public}s] Actions plugin cannot perform work without a health store, ignoring context: %{private}s"
+ "[%{public}s] Actions plugin requires primary profile, ignoring context: %{private}s"
+ "[%{public}s] Could not open the room for %{private}s: %{public}s"
+ "[%{public}s] Failed to delete facts with ids %{private}s, error: %{public}@"
+ "[%{public}s] Failed to fetch facts associated with %{private}ld, error: %{public}@"
+ "[%{public}s] Failed to fetch facts for identifier %{private}s, error: %{public}@"
+ "[%{public}s] Failed to fetch health fact samples, error: %{public}@"
+ "[%{public}s] Failed to force a surveys content update, error: %{public}@"
+ "[%{public}s] No MeasureUI for %{public}s; leaving it out of search results"
+ "[%{public}s] Survey content did not arrive within %{public}s; charting %{public}ld without bands"
+ "[%{public}s] Unable to map measure %{public}s to an ontology concept identifier"
+ "waitForSurveyContent(timeout:)"
- "[%s] Actions plugin cannot perform work without a HealthPlatformOrchestrationContext, ignoring context: %s"
- "[%s] Actions plugin cannot perform work without a health store, ignoring context: %s"
- "[%s] Actions plugin requires primary profile, ignoring context: %s"
- "[%s] Failed to delete facts with ids %s, error: %@"
- "[%s] Failed to fetch facts for identifier %s, error: %@"
- "[%s] Unable to map measure %s to an ontology concept identifier"
```
