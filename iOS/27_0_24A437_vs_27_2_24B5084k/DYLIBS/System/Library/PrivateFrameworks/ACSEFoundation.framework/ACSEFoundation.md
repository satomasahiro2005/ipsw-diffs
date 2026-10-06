## ACSEFoundation

> `/System/Library/PrivateFrameworks/ACSEFoundation.framework/ACSEFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24710` | `0x24b28` | **`+0x418`** |
| `__TEXT.__eh_frame` | `0x18c8` | `0x1998` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0x9c2` | `0x9f2` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0xa48` | `0xa78` | **`+0x30`** |
| `__DATA.__data` | `0x3f8` | `0x408` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x260` | `0x270` | **`+0x10`** |
| `__TEXT.__const` | `0x14f8` | `0x1508` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x19c` | `0x1a8` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x148` | `0x150` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x218` | `0x220` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xa0` | `0xa4` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x9c` | `0xa0` | **`+0x4`** |

### Other Changes

```diff

-301.24.0.12.0
+301.24.1.1.0

+  - /System/Library/PrivateFrameworks/MobileStoreDemoKit.framework/MobileStoreDemoKit

-  Functions: 749
-  Symbols:   510
-  CStrings:  137
+  - /usr/lib/swift/libswiftsimd.dylib
+  Functions: 757
+  Symbols:   513
+  CStrings:  138
Symbols:
+ _OBJC_CLASS_$_MSDKDemoState
+ __swift_FORCE_LOAD_$_swiftsimd
+ __swift_FORCE_LOAD_$_swiftsimd_$_ACSEFoundation
CStrings:
+ "Failed to check isPressDemoDevice: %@"
+ "Failed to create URL from key: %s, baseURL: %s, path: %s"
+ "MSDKDemoState instance unavailable, treating as non-press demo device"
- "Failed to create base URL from key: %s, baseURL: %s"
- "Failed to resolve path against base URL from key: %s, baseURL: %s, path: %s"
```
