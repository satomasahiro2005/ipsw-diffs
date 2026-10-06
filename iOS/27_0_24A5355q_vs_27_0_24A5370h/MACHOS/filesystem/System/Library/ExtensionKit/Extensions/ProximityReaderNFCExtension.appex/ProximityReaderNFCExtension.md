## ProximityReaderNFCExtension

> `/System/Library/ExtensionKit/Extensions/ProximityReaderNFCExtension.appex/ProximityReaderNFCExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3fd8` | `0x4624` | **`+0x64c`** |
| `__TEXT.__eh_frame` | `0x2d8` | `0x348` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x17b` | `0x1db` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x140` | `0x188` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x150` | `0x178` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x630` | `0x650` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x30` | `0x50` | **`+0x20`** |
| `__TEXT.__const` | `0x1a2` | `0x1ba` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x320` | `0x330` | **`+0x10`** |
| `__TEXT.__cstring` | `0x196` | `0x1a6` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x10` | `0x14` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x10` | `0x14` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-150.26.1.0.0
+150.28.1.0.0

+  - /System/Library/PrivateFrameworks/_NearField_ExtensionFoundation.framework/_NearField_ExtensionFoundation

-  - /usr/lib/swift/libswiftCoreAudio.dylib

-  Functions: 52
+  Functions: 59

-  CStrings:  117
+  CStrings:  119
Symbols:
+ _objc_release_x22
+ _objc_release_x25
+ _swift_retain_x8
- __swift_FORCE_LOAD_$_swiftCoreAudio
- _objc_release_x26
- _swift_retain_x24
CStrings:
+ "Device model does not support WiFi Aware — using Web"
+ "WiFi Aware reported unavailable despite supported model"
+ "device is locked"
- "Device does not support WiFi Aware"
```
