## HeartRateSettings

> `/System/Library/NanoPreferenceBundles/Applications/HeartRateSettings.bundle/HeartRateSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb12c` | `0xe0bc` | **`+0x2f90`** |
| `__TEXT.__auth_stubs` | `0x570` | `0xad0` | **`+0x560`** |
| `__TEXT.__cstring` | `0xbd8` | `0xf4d` | **`+0x375`** |
| `__TEXT.__objc_methname` | `0x3b6f` | `0x3ea2` | **`+0x333`** |
| `__DATA_CONST.__auth_got` | `0x2c8` | `0x578` | **`+0x2b0`** |
| `__DATA.__objc_const` | `0xf00` | `0x1080` | **`+0x180`** |
| `__TEXT.__eh_frame` | `—` | `0x170` | **`+0x170`** |
| `__TEXT.__objc_stubs` | `0x2960` | `0x2a80` | **`+0x120`** |
| `__DATA.__data` | `0x398` | `0x4a0` | **`+0x108`** |
| `__TEXT.__objc_methlist` | `0xe44` | `0xf24` | **`+0xe0`** |
| `__DATA.__objc_data` | `0x230` | `0x300` | **`+0xd0`** |
| `__TEXT.__swift5_typeref` | `0x6` | `0xca` | **`+0xc4`** |
| `__TEXT.__unwind_info` | `0x2e8` | `0x3a8` | **`+0xc0`** |
| `__TEXT.__const` | `0xb6` | `0x164` | **`+0xae`** |
| `__DATA_CONST.__const` | `0x378` | `0x420` | **`+0xa8`** |
| `__DATA_CONST.__got` | `0x378` | `0x410` | **`+0x98`** |
| `__DATA.__objc_selrefs` | `0xf50` | `0xfc8` | **`+0x78`** |
| `__TEXT.__objc_classname` | `0x241` | `0x2b1` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x10` | `0x54` | **`+0x44`** |
| `__TEXT.__oslogstring` | `0xc88` | `0xcca` | **`+0x42`** |
| `__TEXT.__constg_swiftt` | `0x50` | `0x88` | **`+0x38`** |
| `__TEXT.__objc_methtype` | `0x9e5` | `0xa19` | **`+0x34`** |
| `__TEXT.__swift5_reflstr` | `—` | `0x2c` | **`+0x2c`** |
| `__TEXT.__swift5_capture` | `—` | `0x24` | **`+0x24`** |
| `__DATA_CONST.__auth_ptr` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x40` | `0x50` | **`+0x10`** |
| `__DATA.__common` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x48` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `—` | `0x8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x74` | `0x78` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x4` | `0x8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

+  - /System/Library/PrivateFrameworks/UIFoundation.framework/UIFoundation

+  - /usr/lib/swift/libswiftAccelerate.dylib

+  - /usr/lib/swift/libswiftCoreImage.dylib
+  - /usr/lib/swift/libswiftCoreLocation.dylib
+  - /usr/lib/swift/libswiftCoreMIDI.dylib

+  - /usr/lib/swift/libswiftMetal.dylib
+  - /usr/lib/swift/libswiftOSLog.dylib

+  - /usr/lib/swift/libswiftQuartzCore.dylib
+  - /usr/lib/swift/libswiftSpatial.dylib
+  - /usr/lib/swift/libswiftUniformTypeIdentifiers.dylib

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 280
-  Symbols:   243
-  CStrings:  788
+  - /usr/lib/swift/libswiftsimd.dylib
+  Functions: 339
+  Symbols:   308
+  CStrings:  829
Symbols:
+ _OBJC_CLASS_$_HPRFHeartRatePreferencesBridgeSettingsManager
+ _OBJC_CLASS_$_NSObject
+ _OBJC_CLASS_$_PDRRegistry
+ _OBJC_METACLASS_$_HPRFHeartRatePreferencesBridgeSettingsManager
+ ___chkstk_darwin
+ __swiftEmptyArrayStorage
+ __swift_FORCE_LOAD_$_swiftAccelerate
+ __swift_FORCE_LOAD_$_swiftCoreImage
+ __swift_FORCE_LOAD_$_swiftCoreLocation
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ __swift_FORCE_LOAD_$_swiftMetal
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftQuartzCore
+ __swift_FORCE_LOAD_$_swiftSpatial
+ __swift_FORCE_LOAD_$_swiftUIKit
+ __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers
+ __swift_FORCE_LOAD_$_swiftsimd
+ _free
+ _objc_allocWithZone
+ _objc_retainAutoreleasedReturnValue
+ _objc_retain_x24
+ _objc_retain_x28
+ _objc_retain_x9
+ _swift_allocObject
+ _swift_arrayDestroy
+ _swift_arrayInitWithCopy
+ _swift_beginAccess
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_coroFrameAlloc
+ _swift_deallocObject
+ _swift_endAccess
+ _swift_getAssociatedConformanceWitness
+ _swift_getAssociatedTypeWitness
+ _swift_getObjCClassFromMetadata
+ _swift_getObjCClassMetadata
+ _swift_getObjectType
+ _swift_getOpaqueTypeConformance2
+ _swift_getOpaqueTypeMetadata2
+ _swift_getSingletonMetadata
+ _swift_getWitnessTable
+ _swift_initStackObject
+ _swift_isUniquelyReferenced_nonNull_bridgeObject
+ _swift_release
+ _swift_release_x19
+ _swift_release_x20
+ _swift_release_x21
+ _swift_release_x23
+ _swift_release_x8
+ _swift_release_x9
+ _swift_retain_x21
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_deinitOnExecutor
+ _swift_task_isCurrentExecutor
+ _swift_task_reportUnexpectedExecutor
+ _swift_task_switch
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
+ _swift_unknownObjectWeakAssign
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
+ _swift_updateClassMetadata2
CStrings:
+ "-[HPRFHeartRateSettingsController heartRatePreferencesDidChange]"
+ "?"
+ "@\"HPRFHeartRatePreferencesBridgeSettingsManager\""
+ "GREEN_LIGHT_MEASUREMENTS_ENABLED_DURING_THEATER_MODE_GROUP_FOOTER"
+ "GREEN_LIGHT_MEASUREMENTS_ENABLED_DURING_THEATER_MODE_GROUP_TITLE"
+ "GREEN_LIGHT_MEASUREMENTS_ENABLED_DURING_THEATER_MODE_TOGGLE_TITLE"
+ "GREEN_LIGHT_MEASUREMENTS_ENABLED_GROUP_FOOTER"
+ "GREEN_LIGHT_MEASUREMENTS_ENABLED_GROUP_FOOTER_LINK"
+ "GREEN_LIGHT_MEASUREMENTS_ENABLED_GROUP_TITLE"
+ "GREEN_LIGHT_MEASUREMENTS_ENABLED_TOGGLE_TITLE"
+ "GreenLightMeasurementsDuringTheaterModeGroup"
+ "GreenLightMeasurementsDuringTheaterModeToggle"
+ "GreenLightMeasurementsGroup"
+ "GreenLightMeasurementsToggle"
+ "HPRFHeartRatePreferencesBridgeSettingsManager"
+ "HPRFHeartRatePreferencesBridgeSettingsManagerDelegate"
+ "HeartRateSettings/HeartRatePreferencesBridgeSettingsManager.swift"
+ "Localizable-AllDayHeartRate"
+ "T@\"<HPRFHeartRatePreferencesBridgeSettingsManagerDelegate>\",N,W,Vdelegate"
+ "T@\"HPRFHeartRatePreferencesBridgeSettingsManager\",&,N,V_heartRatePreferencesSettingsManager"
+ "T@\"NSArray\",N,R"
+ "[%{public}@]: %{public}s: All day heart rate preferences changed."
+ "_heartRatePreferencesSettingsManager"
+ "delegate"
+ "getActivePairedDeviceExcludingAltAccount"
+ "getAreGreenLightMeasurementsEnabled"
+ "getAreGreenLightMeasurementsEnabledDuringTheaterMode"
+ "heartRatePreferencesDidChange"
+ "heartRatePreferencesSettingsManager"
+ "https://support.apple.com/120277?cid=mc-ols-watch_heart-article_120277-ios-62028160"
+ "initWithString:"
+ "localizedStandardRangeOfString:"
+ "mainBundle"
+ "observationTask"
+ "openGreenLightMeasurementsLearnMoreLink"
+ "preferenceProvider"
+ "setAreGreenLightMeasurementsEnabled:"
+ "setAreGreenLightMeasurementsEnabledDuringTheaterMode:"
+ "setDelegate:"
+ "setHeartRatePreferencesSettingsManager:"
+ "supportsCapability:"
```
