## HealthServicesPlatformDiagnosticExtensionPlugin

> `/System/Library/Health/DiagnosticExtensionPlugins/HealthServicesPlatformDiagnosticExtensionPlugin.bundle/HealthServicesPlatformDiagnosticExtensionPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f48` | `0x12ac4` | **`+0xfb7c`** |
| `__TEXT.__auth_stubs` | `0x400` | `0x1390` | **`+0xf90`** |
| `__TEXT.__cstring` | `0x900` | `0x1454` | **`+0xb54`** |
| `__DATA_CONST.__const` | `0x178` | `0xb70` | **`+0x9f8`** |
| `__DATA_CONST.__auth_got` | `0x210` | `0x9d8` | **`+0x7c8`** |
| `__TEXT.__eh_frame` | `—` | `0x7c0` | **`+0x7c0`** |
| `__TEXT.__unwind_info` | `0x110` | `0x3d8` | **`+0x2c8`** |
| `__TEXT.__swift5_capture` | `—` | `0x2b8` | **`+0x2b8`** |
| `__DATA_CONST.__got` | `0xc0` | `0x2c0` | **`+0x200`** |
| `__TEXT.__const` | `0xb2` | `0x272` | **`+0x1c0`** |
| `__TEXT.__swift5_typeref` | `0x14` | `0x19c` | **`+0x188`** |
| `__TEXT.__objc_stubs` | `0xdc0` | `0xf00` | **`+0x140`** |
| `__DATA.__data` | `0x90` | `0x1b0` | **`+0x120`** |
| `__TEXT.__objc_methname` | `0xac2` | `0xbce` | **`+0x10c`** |
| `__DATA.__objc_data` | `0x100` | `0x1c8` | **`+0xc8`** |
| `__DATA.__objc_const` | `0xf0` | `0x178` | **`+0x88`** |
| `__DATA_CONST.__auth_ptr` | `0x8` | `0x88` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x38` | `0xa8` | **`+0x70`** |
| `__TEXT.__objc_classname` | `0xae` | `0x10e` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x398` | `0x3f0` | **`+0x58`** |
| `__TEXT.__swift_as_cont` | `—` | `0x50` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x184` | `0x1bc` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x10` | `0x48` | **`+0x38`** |
| `__TEXT.__swift_as_entry` | `—` | `0x2c` | **`+0x2c`** |
| `__TEXT.__swift_as_ret` | `—` | `0x2c` | **`+0x2c`** |
| `__TEXT.__swift5_reflstr` | `—` | `0x27` | **`+0x27`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x10` | `0x18` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x4` | `0xc` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x79` | `0x7a` | **`+0x1`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/PrivateFrameworks/HealthContent.framework/HealthContent
+  - /System/Library/PrivateFrameworks/HealthContentDaemon.framework/HealthContentDaemon

+  - /usr/lib/swift/libswiftAVFoundation.dylib
+  - /usr/lib/swift/libswiftAccelerate.dylib

+  - /usr/lib/swift/libswiftCoreAudio.dylib

+  - /usr/lib/swift/libswiftCoreImage.dylib

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

+  - /usr/lib/swift/libswiftMetal.dylib
+  - /usr/lib/swift/libswiftOSLog.dylib

+  - /usr/lib/swift/libswiftQuartzCore.dylib

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 42
-  Symbols:   101
-  CStrings:  223
+  - /usr/lib/swift/libswiftsimd.dylib
+  Functions: 225
+  Symbols:   171
+  CStrings:  298
Symbols:
+ _NSCocoaErrorDomain
+ _OBJC_CLASS_$_NSFileManager
+ _OBJC_CLASS_$_NSUserDefaults
+ __swiftImmortalRefCount
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftAccelerate
+ __swift_FORCE_LOAD_$_swiftCoreAudio
+ __swift_FORCE_LOAD_$_swiftCoreImage
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ __swift_FORCE_LOAD_$_swiftMetal
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftQuartzCore
+ __swift_FORCE_LOAD_$_swiftsimd
+ _kHDSQLiteQueryNoLimit
+ _malloc_size
+ _memcpy
+ _memmove
+ _objc_retainAutoreleasedReturnValue
+ _objc_retain_x23
+ _objc_retain_x26
+ _objc_retain_x27
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_allocObject
+ _swift_arrayInitWithCopy
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_beginAccess
+ _swift_bridgeObjectRetain
+ _swift_deallocObject
+ _swift_deletedMethodError
+ _swift_dynamicCastClass
+ _swift_errorRelease
+ _swift_errorRetain
+ _swift_getEnumCaseMultiPayload
+ _swift_getErrorValue
+ _swift_getExistentialMetatypeMetadata
+ _swift_getExistentialTypeMetadata
+ _swift_getForeignTypeMetadata
+ _swift_getWitnessTable
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_release
+ _swift_release_x19
+ _swift_release_x20
+ _swift_release_x21
+ _swift_release_x22
+ _swift_release_x23
+ _swift_release_x24
+ _swift_release_x25
+ _swift_release_x26
+ _swift_release_x27
+ _swift_release_x28
+ _swift_release_x8
+ _swift_retain_x19
+ _swift_retain_x22
+ _swift_retain_x24
+ _swift_retain_x25
+ _swift_retain_x26
+ _swift_retain_x27
+ _swift_retain_x28
+ _swift_retain_x8
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_switch
+ _swift_unknownObjectRelease
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
+ _swift_willThrow
CStrings:
+ "  (Overridden from default)"
+ " Key Value Domain"
+ "(not set — using 24hr default)"
+ ".cxx_destruct"
+ ": could not connect to healthcontentd (connection interrupted/invalid) — check sandbox mach-lookup exceptions and entitlements for com.apple.healthcontentd. Underlying error: "
+ "Content Database"
+ "Content Database Host URL"
+ "Content Database Registry"
+ "Content Feature Evaluator Statuses"
+ "Content Store Inventory"
+ "Content Store Inventory: unavailable"
+ "Content Tag Entries"
+ "ContentDatabase.txt"
+ "Cookie Enabled: "
+ "Current Active URL: "
+ "Current Anchor: "
+ "Current Country/Region: "
+ "Current Language: "
+ "Current Locale: "
+ "Default Environment: "
+ "Error retrieving current URL"
+ "Error retrieving feature statuses"
+ "Experience Identifier Mappings: "
+ "Failed to enumerate content database shard registry entries"
+ "Failed to extract KeyValue domain data for "
+ "HealthContentDatabase.db"
+ "HealthContentDatabase_secure.db"
+ "ITFE Preferences State"
+ "ITFE Preferences State: unavailable"
+ "ITFE Preferences State: unavailable (not backed by HealthContentStore)"
+ "In Custom Features: "
+ "Journal directory not present: "
+ "Journal directory: "
+ "Language Script: "
+ "Localized Resource Entries"
+ "Localized Resource Entries: unavailable"
+ "No feature evaluators to report"
+ "Prefetch Summary"
+ "Prefetch Summary: unavailable"
+ "Prefetcher KVD Entries"
+ "Queued journal files: "
+ "Region code (if any): "
+ "Secure Content Database (Class B)"
+ "Secure Database Journal (queued writes while locked)"
+ "Simulate MediaAPI 404"
+ "Supports Content Database Updates: YES \n"
+ "Supports Content Database: YES \n"
+ "T@\"NSString\",N,R"
+ "Timed out attempting to get ITFE preferences state"
+ "Timed out attempting to get KeyValue domain data for "
+ "Timed out attempting to get content store inventory"
+ "Timed out attempting to get feature evaluator statuses"
+ "Timed out attempting to get localized resource entries"
+ "Timed out attempting to get prefetch summary"
+ "Timed out attempting to get the content database host URL"
+ "Timed out attempting to read video takedown testing state"
+ "Unable to open database at "
+ "Video Takedown Testing State"
+ "Video Takedown Testing State: unavailable"
+ "WARNING: Simulate MediaAPI 404 is ENABLED. Video metadata fetches will fail until disabled."
+ "_TtC47HealthServicesPlatformDiagnosticExtensionPlugin36HDContentDatabaseDiagnosticOperation"
+ "code"
+ "contentStore"
+ "contentsOfDirectoryAtPath:error:"
+ "defaultManager"
+ "delegate"
+ "diagnosticOperation:logMessage:"
+ "domain"
+ "fileExistsAtPath:"
+ "healthcontentd User Defaults"
+ "initWithSuiteName:"
+ "isAppleInternalInstall"
+ "prefetchStartDate"
+ "stringForKey:"
+ "typically because the device is locked — Class B files require unlock"
```
