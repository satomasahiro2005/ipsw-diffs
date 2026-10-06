## GenericURLProcessor

> `/System/Library/ExtensionKit/Extensions/GenericURLProcessor.appex/GenericURLProcessor`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__objc_const` | `0x4d8` | `0x420` | **`-0xb8`** |
| `__DATA.__data` | `0x190` | `0xe0` | **`-0xb0`** |
| `__TEXT.__cstring` | `0x405` | `0x445` | **`+0x40`** |
| `__TEXT.__text` | `0x1bbc` | `0x1bfc` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0x95` | `0x63` | **`-0x32`** |
| `__TEXT.__constg_swiftt` | `0x50` | `0x28` | **`-0x28`** |
| `__TEXT.__eh_frame` | `0x70` | `0x48` | **`-0x28`** |
| `__TEXT.__const` | `0x140` | `0x150` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x36a` | `0x35e` | **`-0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x20` | `0x18` | **`-0x8`** |
| `__TEXT.__objc_methtype` | `0x129` | `0x128` | **`-0x1`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-370.33.1.0.0
+370.37.0.0.0

-  - /System/Library/Frameworks/UIKit.framework/UIKit

-  - /System/Library/PrivateFrameworks/NearFieldUI.framework/NearFieldUI

+  - /System/Library/PrivateFrameworks/_NearField_ExtensionFoundation.framework/_NearField_ExtensionFoundation

-  - /usr/lib/swift/libswiftCoreAudio.dylib

-  - /usr/lib/swift/libswiftCoreImage.dylib
-  - /usr/lib/swift/libswiftCoreLocation.dylib

-  - /usr/lib/swift/libswiftSpatial.dylib

-  Symbols:   112
-  CStrings:  122
+  Symbols:   104
+  CStrings:  121
Symbols:
+ _$s19ExtensionFoundation03AppA5PointV10IdentifierVMa
+ _$s19ExtensionFoundation03AppA5PointV10IdentifierVyAEs12StaticStringVcfC
+ _$s19ExtensionFoundation03AppA5PointV4BindV10buildBlockyA2C10IdentifierVFZ
+ _$s30_NearField_ExtensionFoundation023NFCBackgroundTagReadingC0Mp
+ _$s30_NearField_ExtensionFoundation023NFCBackgroundTagReadingC0P0cD003AppC0Tb
+ _$s30_NearField_ExtensionFoundation023NFCBackgroundTagReadingC0P11processNDEF_3tagySo13NFNdefMessage_p_So5NFTag_ptKFTq
+ _$s30_NearField_ExtensionFoundation023NFCBackgroundTagReadingC0PAAE13configurationQrvg
+ _$s30_NearField_ExtensionFoundation023NFCBackgroundTagReadingC0PAAE13configurationQrvpQOMQ
+ _$sBOWV
- _$s11NearFieldUI32NFCBackgroundTagReadingExtensionMp
- _$s11NearFieldUI32NFCBackgroundTagReadingExtensionP0G10Foundation03AppG0Tb
- _$s11NearFieldUI32NFCBackgroundTagReadingExtensionP11processNDEF_3tagySo13NFNdefMessage_p_So5NFTag_ptKFTq
- _$s11NearFieldUI32NFCBackgroundTagReadingExtensionPAAE13configurationQrvg
- _$s11NearFieldUI32NFCBackgroundTagReadingExtensionPAAE13configurationQrvpQOMQ
- _$s19ExtensionFoundation03AppA0PAAE14extensionPointAA0caE0Vvg
- _$sBoWV
- _OBJC_CLASS_$__TtCs12_SwiftObject
- _OBJC_METACLASS_$__TtCs12_SwiftObject
- __swift_FORCE_LOAD_$_swiftCoreAudio
- __swift_FORCE_LOAD_$_swiftCoreImage
- __swift_FORCE_LOAD_$_swiftCoreLocation
- __swift_FORCE_LOAD_$_swiftSpatial
- __swift_FORCE_LOAD_$_swiftUIKit
- _objc_opt_self
- _swift_deallocClassInstance
- _swift_deletedMethodError
CStrings:
+ "com.apple.nfcd.background.tag.reading.nonui.extension"
- "_TtC19GenericURLProcessor19GenericURLProcessor"
- "appLauncher"
```
