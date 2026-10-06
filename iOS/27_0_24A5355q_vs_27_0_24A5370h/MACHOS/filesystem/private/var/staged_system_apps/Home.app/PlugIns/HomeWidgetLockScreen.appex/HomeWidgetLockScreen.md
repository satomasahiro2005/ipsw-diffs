## HomeWidgetLockScreen

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeWidgetLockScreen.appex/HomeWidgetLockScreen`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6573c` | `0x660a8` | **`+0x96c`** |
| `__TEXT.__eh_frame` | `0x2984` | `0x2b9c` | **`+0x218`** |
| `__DATA_CONST.__const` | `0xfe0` | `0x10d0` | **`+0xf0`** |
| `__TEXT.__swift5_typeref` | `0x31f8` | `0x328a` | **`+0x92`** |
| `__TEXT.__unwind_info` | `0x13d0` | `0x1448` | **`+0x78`** |
| `__TEXT.__cstring` | `0x1f5f` | `0x1fbf` | **`+0x60`** |
| `__DATA.__data` | `0x1ef8` | `0x1f30` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x1fb0` | `0x1fd0` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x6b4` | `0x6d4` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x1e4` | `0x200` | **`+0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0x86c` | `0x884` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0xfe0` | `0xff0` | **`+0x10`** |
| `__TEXT.__const` | `0x36f4` | `0x3704` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x5c8` | `0x5d0` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x298` | `0x2a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-1216.4.0.1.11
+1227.0.0.0.1

+  - /System/Library/Frameworks/_AppIntents_UIKit.framework/_AppIntents_UIKit

+  - /System/Library/PrivateFrameworks/HomeUI2.framework/HomeUI2

+  - /usr/lib/swift/libswiftCoreAudio_Private.dylib

+  - /usr/lib/swift/libswiftMLCompute.dylib

+  - /usr/lib/swift/libswiftMetalKit.dylib
+  - /usr/lib/swift/libswiftModelIO.dylib
+  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  Functions: 1451
-  Symbols:   202
-  CStrings:  372
+  Functions: 1462
+  Symbols:   207
+  CStrings:  374
Symbols:
+ __swift_FORCE_LOAD_$_swiftCoreAudio_Private
+ __swift_FORCE_LOAD_$_swiftMLCompute
+ __swift_FORCE_LOAD_$_swiftMetalKit
+ __swift_FORCE_LOAD_$_swiftModelIO
+ __swift_FORCE_LOAD_$_swiftNaturalLanguage
+ _objc_retain_x26
- _swift_retain_x8
CStrings:
+ "HomeDataError_SignificantChangeApprovalRequired"
+ "SignificantChangeApprovalRequired"
```
