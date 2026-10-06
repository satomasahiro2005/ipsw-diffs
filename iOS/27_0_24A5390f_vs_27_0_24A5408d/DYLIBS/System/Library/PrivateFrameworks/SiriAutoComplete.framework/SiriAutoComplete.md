## SiriAutoComplete

> `/System/Library/PrivateFrameworks/SiriAutoComplete.framework/SiriAutoComplete`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55084` | `0x55170` | **`+0xec`** |
| `__TEXT.__cstring` | `0x9d7` | `0xa57` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x28a0` | `0x28c0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xd0` | `0xf0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xcb0` | `0xcc0` | **`+0x10`** |
| `__TEXT.__const` | `0x2b10` | `0x2b20` | **`+0x10`** |

### Other Changes

```diff

-3600.11.5.0.0
+3600.11.7.0.0

+  - /System/Library/Frameworks/ImagePlayground.framework/ImagePlayground

+  - /usr/lib/swift/libswiftGLKit.dylib

+  - /usr/lib/swift/libswiftMetalKit.dylib
+  - /usr/lib/swift/libswiftModelIO.dylib

+  - /usr/lib/swift/libswiftSceneKit.dylib

-  Functions: 2024
-  Symbols:   898
-  CStrings:  241
+  Functions: 2023
+  Symbols:   906
+  CStrings:  244
Symbols:
+ __swift_FORCE_LOAD_$_swiftGLKit
+ __swift_FORCE_LOAD_$_swiftGLKit_$_SiriAutoComplete
+ __swift_FORCE_LOAD_$_swiftMetalKit
+ __swift_FORCE_LOAD_$_swiftMetalKit_$_SiriAutoComplete
+ __swift_FORCE_LOAD_$_swiftModelIO
+ __swift_FORCE_LOAD_$_swiftModelIO_$_SiriAutoComplete
+ __swift_FORCE_LOAD_$_swiftSceneKit
+ __swift_FORCE_LOAD_$_swiftSceneKit_$_SiriAutoComplete
CStrings:
+ "com.apple.GenerativePlaygroundApp"
+ "com.apple.Posters.ImagePlaygroundPosterApp"
+ "com.apple.SiriApp"
```
