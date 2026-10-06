## AppManagedFeaturesSettings

> `/System/Library/PreferenceBundles/AppManagedFeaturesSettings.bundle/AppManagedFeaturesSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x86ac` | `0x8c00` | **`+0x554`** |
| `__DATA.__data` | `0x400` | `0x4b0` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0x160` | `0xc0` | **`-0xa0`** |
| `__TEXT.__objc_methname` | `0xdc` | `0x63` | **`-0x79`** |
| `__TEXT.__cstring` | `0x39b` | `0x3eb` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x238` | `0x1f0` | **`-0x48`** |
| `__DATA.__objc_selrefs` | `0x58` | `0x30` | **`-0x28`** |
| `__TEXT.__const` | `0x538` | `0x54c` | **`+0x14`** |
| `__TEXT.__swift5_typeref` | `0x1930` | `0x1944` | **`+0x14`** |
| `__TEXT.__swift5_reflstr` | `0xc1` | `0xb1` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x200` | `0x210` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x184` | `0x190` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x2d8` | `0x2e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-43.0.0.0.0
+46.0.1.0.0

+  - /System/Library/Frameworks/SafariServices.framework/SafariServices

-  - /System/Library/PrivateFrameworks/HelpKit.framework/HelpKit

+  - /usr/lib/swift/libswiftCallKit.dylib
+  - /usr/lib/swift/libswiftCompression.dylib

+  - /usr/lib/swift/libswiftCoreAudio_Private.dylib

+  - /usr/lib/swift/libswiftMLCompute.dylib

+  - /usr/lib/swift/libswiftMetalKit.dylib
+  - /usr/lib/swift/libswiftModelIO.dylib
+  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  Functions: 145
-  Symbols:   111
-  CStrings:  38
+  Functions: 150
+  Symbols:   115
+  CStrings:  34
Symbols:
+ _OBJC_CLASS_$_SFSafariViewController
+ __swift_FORCE_LOAD_$_swiftCallKit
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCoreAudio_Private
+ __swift_FORCE_LOAD_$_swiftMLCompute
+ __swift_FORCE_LOAD_$_swiftMetalKit
+ __swift_FORCE_LOAD_$_swiftModelIO
+ __swift_FORCE_LOAD_$_swiftNaturalLanguage
+ _objc_release_x20
+ _objc_release_x23
+ _swift_once
- _OBJC_CLASS_$_HLPHelpViewController
- _OBJC_CLASS_$_UINavigationController
- _objc_release_x19
- _objc_release_x21
- _objc_release_x25
- _objc_release_x26
- _swift_release_x28
CStrings:
+ "ManagementProviderStore"
+ "https://support.apple.com/en-us/127036?displayMode=headerless&src=tips"
+ "initWithURL:"
- "PLACEHOLDER_TOPIC_ID"
- "init"
- "initWithRootViewController:"
- "setDisplayHelpTopicsOnly:"
- "setModalPresentationStyle:"
- "setSelectedHelpTopicID:"
- "setShowTopicViewOnLoad:"
```
