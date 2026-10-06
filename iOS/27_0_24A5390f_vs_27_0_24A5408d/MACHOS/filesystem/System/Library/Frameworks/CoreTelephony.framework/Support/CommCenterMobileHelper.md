## CommCenterMobileHelper

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CommCenterMobileHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f82c` | `0x712fc` | **`+0x1ad0`** |
| `__TEXT.__const` | `0xd702` | `0xdbda` | **`+0x4d8`** |
| `__DATA_CONST.__const` | `0x6bd8` | `0x6e60` | **`+0x288`** |
| `__TEXT.__gcc_except_tab` | `0x8fb8` | `0x90e8` | **`+0x130`** |
| `__TEXT.__auth_stubs` | `0x1c00` | `0x1d20` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0x39e8` | `0x3af8` | **`+0x110`** |
| `__TEXT.__cstring` | `0x6601` | `0x66a1` | **`+0xa0`** |
| `__DATA_CONST.__auth_got` | `0xe18` | `0xea8` | **`+0x90`** |
| `__DATA.__objc_data` | `0x220` | `0x290` | **`+0x70`** |
| `__DATA_CONST.__cfstring` | `0x4620` | `0x4680` | **`+0x60`** |
| `__DATA.__objc_const` | `0xa80` | `0xac8` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x3926` | `0x3957` | **`+0x31`** |
| `__DATA.__data` | `0x420` | `0x450` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x5c4` | `0x5f4` | **`+0x30`** |
| `__DATA.__bss` | `0xeb8` | `0xee0` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0xbe` | `0xe4` | **`+0x26`** |
| `__DATA_CONST.__objc_arraydata` | `0x18d8` | `0x18f8` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2920` | `0x2940` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x8` | `0x20` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0x23b1` | `0x23c1` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `—` | `0xd` | **`+0xd`** |
| `__DATA.__objc_selrefs` | `0xb80` | `0xb88` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x4a8` | `0x4b0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x30` | `0x38` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-13482.1.0.0.0
+13487.3.0.0.0

+  - /System/Library/Frameworks/UIKit.framework/UIKit

+  - /System/Library/PrivateFrameworks/DeviceRegulatoryInfo.framework/DeviceRegulatoryInfo

+  - /usr/lib/swift/libswiftCoreImage.dylib
+  - /usr/lib/swift/libswiftCoreLocation.dylib

+  - /usr/lib/swift/libswiftMetal.dylib
+  - /usr/lib/swift/libswiftOSLog.dylib

+  - /usr/lib/swift/libswiftQuartzCore.dylib
+  - /usr/lib/swift/libswiftSpatial.dylib
+  - /usr/lib/swift/libswiftUniformTypeIdentifiers.dylib

-  Functions: 3007
-  Symbols:   623
-  CStrings:  1742
+  - /usr/lib/swift/libswiftsimd.dylib
+  Functions: 3066
+  Symbols:   656
+  CStrings:  1751
Symbols:
+ _$s20DeviceRegulatoryInfo30ChinaMIITBlueStickerAttributesO7labelIdSSSgvgZ
+ _$s2os6LoggerV9logObjectSo03OS_a1_C0Cvg
+ _$s2os6LoggerV9subsystem8categoryACSS_SStcfC
+ _$s2os6LoggerVMa
+ _$sSS8UTF8ViewV13_foreignCountSiyF
+ _$sSo13os_log_type_ta0A0E4infoABvgZ
+ _$ss11_StringGutsV16_foreignCopyUTF84intoSiSgSrys5UInt8VG_tF
+ _$ss11_StringGutsVN
+ _$ss13_StringObjectV10sharedUTF8SRys5UInt8VGvg
+ _$ss20__StaticArrayStorageCN
+ _$ss23_ContiguousArrayStorageCMn
+ _$ss5UInt8VMn
+ ___chkstk_darwin
+ __swiftImmortalRefCount
+ __swift_FORCE_LOAD_$_swiftCoreImage
+ __swift_FORCE_LOAD_$_swiftCoreLocation
+ __swift_FORCE_LOAD_$_swiftMetal
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftQuartzCore
+ __swift_FORCE_LOAD_$_swiftSpatial
+ __swift_FORCE_LOAD_$_swiftUIKit
+ __swift_FORCE_LOAD_$_swiftUniformTypeIdentifiers
+ __swift_FORCE_LOAD_$_swiftsimd
+ _malloc_size
+ _swift_allocObject
+ _swift_getObjectType
+ _swift_getTypeByMangledNameInContext2
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_once
+ _swift_release
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _swift_unknownObjectRetain
CStrings:
+ "/helper/requests/nal_label"
+ "JOURNALING_SERVICES"
+ "RegulatoryInfo NAL labelId: %{public}s"
+ "RegulatoryInfoHandler"
+ "RegulatoryInfoProvider"
+ "com.apple.MomentsUIService"
+ "com.apple.datausage.journaling"
+ "copyNAL"
+ "regulatory.handler"
```
