## NanoBedtimeBridgeSettings

> `/System/Library/NanoPreferenceBundles/Applications/NanoBedtimeBridgeSettings.bundle/NanoBedtimeBridgeSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1383c` | `0x1485c` | **`+0x1020`** |
| `__TEXT.__const` | `0xbb8` | `0xcb8` | **`+0x100`** |
| `__TEXT.__auth_stubs` | `0x1170` | `0x1260` | **`+0xf0`** |
| `__DATA_CONST.__const` | `0xc58` | `0xd00` | **`+0xa8`** |
| `__DATA.__bss` | `0x8e0` | `0x970` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x86` | `0x116` | **`+0x90`** |
| `__TEXT.__objc_stubs` | `0x2a0` | `0x320` | **`+0x80`** |
| `__DATA_CONST.__auth_got` | `0x8c0` | `0x938` | **`+0x78`** |
| `__DATA_CONST.__got` | `0x3e0` | `0x430` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x5cc` | `0x61c` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x4c8` | `0x514` | **`+0x4c`** |
| `__TEXT.__unwind_info` | `0x558` | `0x5a0` | **`+0x48`** |
| `__TEXT.__objc_methname` | `0x1e7` | `0x22e` | **`+0x47`** |
| `__DATA.__data` | `0x6a8` | `0x6d0` | **`+0x28`** |
| `__DATA_CONST.__auth_ptr` | `0x2a8` | `0x2d0` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0xd8` | `0xf8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x787` | `0x767` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x21c` | `0x238` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0x198` | `0x1b0` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0x133` | `0x141` | **`+0xe`** |
| `__TEXT.__swift5_proto` | `0x44` | `0x48` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x48` | `0x4c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

+  - /System/Library/PrivateFrameworks/IconServices.framework/IconServices

+  - /System/Library/PrivateFrameworks/_IconServices_SwiftUI.framework/_IconServices_SwiftUI

-  Functions: 470
-  Symbols:   137
-  CStrings:  81
+  Functions: 495
+  Symbols:   146
+  CStrings:  85
Symbols:
+ _HKSPSleepWidgetContainerBundleIdentifier
+ _OBJC_CLASS_$_ISIcon
+ _OBJC_CLASS_$_ISImageDescriptor
+ __swiftImmortalRefCount
+ _malloc_size
+ _memmove
+ _objc_retain_x28
+ _swift_getAtKeyPath
+ _swift_isUniquelyReferenced_nonNull_native
CStrings:
+ "Accessing Environment<%s>'s value outside of being installed on a View. This will always read the default value and will not update."
+ "initWithBundleIdentifier:"
+ "initWithSize:scale:"
+ "setAppearance:"
+ "setShape:"
- "sleep_glass_icon"
```
