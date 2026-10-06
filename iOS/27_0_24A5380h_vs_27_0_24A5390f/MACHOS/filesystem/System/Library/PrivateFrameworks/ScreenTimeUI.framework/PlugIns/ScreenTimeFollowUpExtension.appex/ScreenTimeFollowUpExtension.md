## ScreenTimeFollowUpExtension

> `/System/Library/PrivateFrameworks/ScreenTimeUI.framework/PlugIns/ScreenTimeFollowUpExtension.appex/ScreenTimeFollowUpExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b24` | `0xe30` | **`-0xcf4`** |
| `__TEXT.__auth_stubs` | `0x4a0` | `0x340` | **`-0x160`** |
| `__DATA_CONST.__auth_got` | `0x258` | `0x1a8` | **`-0xb0`** |
| `__TEXT.__oslogstring` | `0x107` | `0xbe` | **`-0x49`** |
| `__DATA_CONST.__got` | `0x58` | `0x18` | **`-0x40`** |
| `__TEXT.__objc_methname` | `0xd8` | `0x102` | **`+0x2a`** |
| `__TEXT.__unwind_info` | `0xd0` | `0xa8` | **`-0x28`** |
| `__TEXT.__objc_stubs` | `0xc0` | `0xa0` | **`-0x20`** |
| `__DATA_CONST.__const` | `0xf0` | `0xd8` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x2c` | `0x44` | **`+0x18`** |
| `__DATA.__data` | `0x50` | `0x40` | **`-0x10`** |
| `__TEXT.__objc_methtype` | `0x2b` | `0x3b` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x5b` | `0x4f` | **`-0xc`** |
| `__DATA.__objc_data` | `0xc8` | `0xd0` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x50` | `0x58` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x28` | `0x20` | **`-0x8`** |
| `__TEXT.__const` | `0x9a` | `0x92` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x58` | `0x60` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-645.1.100.0.0
+649.0.0.0.0

-  - /System/Library/Frameworks/CoreServices.framework/CoreServices

+  - /System/Library/Frameworks/SwiftUI.framework/SwiftUI

+  - /System/Library/PrivateFrameworks/ScreenTimeUI.framework/ScreenTimeUI

+  - /usr/lib/swift/libswiftAVFoundation.dylib

+  - /usr/lib/swift/libswiftIntents.dylib

-  Functions: 33
-  Symbols:   82
+  Functions: 19
+  Symbols:   68
Symbols:
+ __swift_FORCE_LOAD_$_swiftAVFoundation
+ __swift_FORCE_LOAD_$_swiftIntents
- _OBJC_CLASS_$_LSApplicationWorkspace
- __swiftEmptyArrayStorage
- __swiftEmptyDictionarySingleton
- __swiftImmortalRefCount
- _malloc_size
- _memcpy
- _memmove
- _objc_release_x27
- _swift_bridgeObjectRetain
- _swift_getObjectType
- _swift_getWitnessTable
- _swift_isUniquelyReferenced_nonNull_native
- _swift_release
- _swift_release_x20
- _swift_retain_x20
- _swift_unknownObjectRetain
CStrings:
+ "finishProcessing"
+ "presentViewController:animated:completion:"
+ "v20@0:8B16"
+ "viewDidAppear:"
+ "viewDidDisappear:"
- "Failed to open url %{public}s"
- "Successfully opened url: %{public}s"
- "defaultWorkspace"
- "openSensitiveURL:withOptions:"
- "url"
```
