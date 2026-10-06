## VisualLogger

> `/System/Library/PrivateFrameworks/VisualLogger.framework/VisualLogger`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x700b3c` | `0x70d98c` | **`+0xce50`** |
| `__TEXT.__const` | `0x671f0` | `0x68980` | **`+0x1790`** |
| `__TEXT.__gcc_except_tab` | `0x648b8` | `0x653e0` | **`+0xb28`** |
| `__AUTH_CONST.__const` | `0x32640` | `0x330e0` | **`+0xaa0`** |
| `__TEXT.__unwind_info` | `0x1c060` | `0x1c418` | **`+0x3b8`** |
| `__TEXT.__cstring` | `0x1674e` | `0x16804` | **`+0xb6`** |
| `__DATA.__bss` | `0x2740` | `0x27c0` | **`+0x80`** |
| `__DATA.__common` | `0x338` | `0x2e8` | **`-0x50`** |
| `__AUTH_CONST.__auth_got` | `0xdf8` | `0xde8` | **`-0x10`** |

### Other Changes

```diff

-9.26.6.16.5
+9.26.7.9.0

-  Functions: 16895
-  Symbols:   1149
-  CStrings:  2205
+  Functions: 17047
+  Symbols:   1147
+  CStrings:  2204
Symbols:
- _CFBundleCopyBundleURL
- _CFURLGetString
CStrings:
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::cv::CVImageBuffer<img::Format::Two16u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::iosimg::IOSurfaceImageBuffer<img::Format::Two16u>]"
- "Failed to convert bundle URL to string"
- "bundle_url"
- "file://"
```
