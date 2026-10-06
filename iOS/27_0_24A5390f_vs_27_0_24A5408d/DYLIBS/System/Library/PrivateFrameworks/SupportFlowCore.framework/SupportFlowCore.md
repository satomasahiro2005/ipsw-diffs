## SupportFlowCore

> `/System/Library/PrivateFrameworks/SupportFlowCore.framework/SupportFlowCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24564` | `0x24674` | **`+0x110`** |
| `__TEXT.__cstring` | `0x10cf` | `0x110f` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x3cf` | `0x3ef` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x1dc8` | `0x1de0` | **`+0x18`** |
| `__DATA_CONST.__const` | `0xf8` | `0x110` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x6dc` | `0x6e8` | **`+0xc`** |

### Other Changes

```diff

-37.0.28.0.0
+37.0.34.0.0

+  - /usr/lib/swift/libswiftAccelerate.dylib

+  - /usr/lib/swift/libswiftCoreAudio.dylib

+  - /usr/lib/swift/libswiftQuartzCore.dylib

-  Functions: 1152
-  Symbols:   379
-  CStrings:  175
+  Functions: 1155
+  Symbols:   385
+  CStrings:  177
Symbols:
+ __swift_FORCE_LOAD_$_swiftAccelerate
+ __swift_FORCE_LOAD_$_swiftAccelerate_$_SupportFlowCore
+ __swift_FORCE_LOAD_$_swiftCoreAudio
+ __swift_FORCE_LOAD_$_swiftCoreAudio_$_SupportFlowCore
+ __swift_FORCE_LOAD_$_swiftQuartzCore
+ __swift_FORCE_LOAD_$_swiftQuartzCore_$_SupportFlowCore
CStrings:
+ "com.apple.BusinessActionSheet"
+ "safariBusinessChatSuggestion"
```
