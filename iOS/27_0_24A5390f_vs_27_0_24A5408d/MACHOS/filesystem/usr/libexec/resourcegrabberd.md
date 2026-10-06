## resourcegrabberd

> `/usr/libexec/resourcegrabberd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13b38` | `0x1577c` | **`+0x1c44`** |
| `__TEXT.__auth_stubs` | `0x7a0` | `0xaf0` | **`+0x350`** |
| `__DATA_CONST.__auth_got` | `0x3e0` | `0x588` | **`+0x1a8`** |
| `__DATA_CONST.__const` | `0x740` | `0x858` | **`+0x118`** |
| `__TEXT.__eh_frame` | `—` | `0x110` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x1a6e` | `0x1b7e` | **`+0x110`** |
| `__DATA.__objc_data` | `0x640` | `0x6f0` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0x610` | `0x6a0` | **`+0x90`** |
| `__TEXT.__const` | `0xb0` | `0x132` | **`+0x82`** |
| `__TEXT.__swift5_typeref` | `—` | `0x6d` | **`+0x6d`** |
| `__TEXT.__objc_stubs` | `0x2700` | `0x2760` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x379d` | `0x37f2` | **`+0x55`** |
| `__DATA.__objc_const` | `0x30d0` | `0x3118` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `—` | `0x3c` | **`+0x3c`** |
| `__DATA.__data` | `0x4e0` | `0x518` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x1f0` | `0x228` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `—` | `0x38` | **`+0x38`** |
| `__DATA_CONST.__objc_intobj` | `0x378` | `0x3a8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x1834` | `0x1864` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x2e5` | `0x313` | **`+0x2e`** |
| `__DATA.__bss` | `0x48` | `0x68` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `—` | `0x20` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xf88` | `0xfa0` | **`+0x18`** |
| `__TEXT.__cstring` | `0x924` | `0x90e` | **`-0x16`** |
| `__TEXT.__swift5_fieldmd` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x1229` | `0x1237` | **`+0xe`** |
| `__DATA_CONST.__objc_classlist` | `0xa0` | `0xa8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `—` | `0x4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_doubleobj`
- `__DATA_CONST.__objc_imageinfo`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-117.0.0.0.0
+118.0.0.0.0

+  - /System/Library/PrivateFrameworks/GenerativePartnerService.framework/GenerativePartnerService
+  - /System/Library/PrivateFrameworks/GenerativePartnerServiceUI.framework/GenerativePartnerServiceUI

-  Functions: 557
-  Symbols:   202
-  CStrings:  1061
+  - /usr/lib/swift/libswiftAccelerate.dylib
+  - /usr/lib/swift/libswiftCore.dylib
+  - /usr/lib/swift/libswiftCoreAudio.dylib
+  - /usr/lib/swift/libswiftCoreFoundation.dylib
+  - /usr/lib/swift/libswiftCoreImage.dylib
+  - /usr/lib/swift/libswiftCoreLocation.dylib
+  - /usr/lib/swift/libswiftCoreMIDI.dylib
+  - /usr/lib/swift/libswiftDispatch.dylib
+  - /usr/lib/swift/libswiftIntents.dylib
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
+  Functions: 595
+  Symbols:   289
+  CStrings:  1069
Symbols:
+ _$s10Foundation4DataV19_bridgeToObjectiveCSo6NSDataCyF
+ _$s10Foundation4DataV36_unconditionallyBridgeFromObjectiveCyACSo6NSDataCSgFZ
+ _$s10Foundation4DataVMn
+ _$s24GenerativePartnerService016ExternalProviderC0C0abC2UIE13IconSizeClassO6inlineyA2FmFWC
+ _$s24GenerativePartnerService016ExternalProviderC0C0abC2UIE13IconSizeClassOMa
+ _$s24GenerativePartnerService016ExternalProviderC0C0abC2UIE9getIconV28bundleId13iconSizeClassSo7UIImageCSgSS_AcDE0hmN0OtYaF
+ _$s24GenerativePartnerService016ExternalProviderC0C0abC2UIE9getIconV28bundleId13iconSizeClassSo7UIImageCSgSS_AcDE0hmN0OtYaFTu
+ _$s24GenerativePartnerService016ExternalProviderC0C6sharedACvgZ
+ _$s24GenerativePartnerService016ExternalProviderC0CMa
+ _$s2os6LoggerV9logObjectSo03OS_a1_C0Cvg
+ _$s2os6LoggerV9subsystem8categoryACSS_SStcfC
+ _$s2os6LoggerVMa
+ _$s8Dispatch0A13TimeoutResultO2eeoiySbAC_ACtFZ
+ _$s8Dispatch0A4TimeV3nowACyFZ
+ _$s8Dispatch0A4TimeVMa
+ _$s8Dispatch1poiyAA0A4TimeVAD_SdtF
+ _$sBOWV
+ _$sSS10FoundationE36_unconditionallyBridgeFromObjectiveCySSSo8NSStringCSgFZ
+ _$sSS8UTF8ViewV13_foreignCountSiyF
+ _$sScP8rawValues5UInt8Vvg
+ _$sScPMa
+ _$sScT6cancelyyF
+ _$sSo13os_log_type_ta0A0E5errorABvgZ
+ _$sSo21OS_dispatch_semaphoreC8DispatchE4wait7timeoutAC0D13TimeoutResultOAC0D4TimeV_tF
+ _$sSo21OS_dispatch_semaphoreC8DispatchE6signalSiyF
+ _$ss11_StringGutsV16_foreignCopyUTF84intoSiSgSrys5UInt8VG_tF
+ _$ss11_StringGutsVN
+ _$ss13_StringObjectV10sharedUTF8SRys5UInt8VGvg
+ _$ss20__StaticArrayStorageCN
+ _$ss23_ContiguousArrayStorageCMn
+ _$ss5NeverON
+ _$ss5NeverOs5ErrorsWP
+ _$ss5UInt8VMn
+ _$sytN
+ _UIImagePNGRepresentation
+ ___chkstk_darwin
+ __swiftEmptyArrayStorage
+ __swiftImmortalRefCount
+ __swift_FORCE_LOAD_$_swiftAccelerate
+ __swift_FORCE_LOAD_$_swiftCoreAudio
+ __swift_FORCE_LOAD_$_swiftCoreFoundation
+ __swift_FORCE_LOAD_$_swiftCoreImage
+ __swift_FORCE_LOAD_$_swiftCoreLocation
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ __swift_FORCE_LOAD_$_swiftDispatch
+ __swift_FORCE_LOAD_$_swiftFoundation
+ __swift_FORCE_LOAD_$_swiftIntents
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
+ _malloc_size
+ _memcpy
+ _memmove
+ _objc_allocWithZone
+ _objc_opt_self
+ _swift_allocObject
+ _swift_beginAccess
+ _swift_bridgeObjectRelease
+ _swift_bridgeObjectRetain
+ _swift_deallocObject
+ _swift_getObjectType
+ _swift_getTypeByMangledNameInContext2
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_once
+ _swift_release
+ _swift_release_x21
+ _swift_release_x27
+ _swift_release_x28
+ _swift_release_x8
+ _swift_retain
+ _swift_retain_x27
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_switch
+ _swift_unknownObjectRelease
+ _swift_unknownObjectRetain
CStrings:
+ "@32@0:8@16d24"
+ "External provider catalog returned no icon for %{public}@, falling back to IconServices"
+ "NRGSiriExternalProviderIconFetcher"
+ "Served Siri provider icon for %{public}@ from external provider catalog"
+ "Timed out fetching Siri external provider icon for %{public}s"
+ "containsObject:"
+ "iconDataForBundleID:timeout:"
+ "liIconVariantsSyncedToPhone"
+ "liIconVariantsSyncedToWatch"
+ "requesting icon sync for %lu variants: %@"
- "nrgIconVariants"
- "v32@?0@\"NSNumber\"8Q16^B24"
```
