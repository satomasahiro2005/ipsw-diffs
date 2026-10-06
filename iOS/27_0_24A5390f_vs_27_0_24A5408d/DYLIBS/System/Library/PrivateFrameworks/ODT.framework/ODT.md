## ODT

> `/System/Library/PrivateFrameworks/ODT.framework/ODT`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e988c` | `0x4f2558` | **`+0x8ccc`** |
| `__TEXT.__const` | `0x2c328` | `0x2ccf8` | **`+0x9d0`** |
| `__TEXT.__gcc_except_tab` | `0x23524` | `0x23ce8` | **`+0x7c4`** |
| `__AUTH_CONST.__const` | `0x19b50` | `0x1a110` | **`+0x5c0`** |
| `__TEXT.__unwind_info` | `0xd050` | `0xd2e8` | **`+0x298`** |
| `__TEXT.__cstring` | `0x11cb3` | `0x11e2d` | **`+0x17a`** |
| `__DATA.__data` | `0x280` | `0x308` | **`+0x88`** |
| `__TEXT.__oslogstring` | `0x98c` | `0xa00` | **`+0x74`** |
| `__DATA.__common` | `0x120` | `0x170` | **`+0x50`** |
| `__DATA.__bss` | `0xde8` | `0xe28` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0xff0` | `0x1018` | **`+0x28`** |

### Other Changes

```diff

-26.5.0.0.0
+30.3.0.0.0

-  Functions: 10544
-  Symbols:   743
-  CStrings:  1650
+  Functions: 10638
+  Symbols:   748
+  CStrings:  1655
Symbols:
+ __os_log_send_and_compose_impl
+ __os_signpost_emit_unreliably_with_name_impl
+ _os_signpost_enabled
+ _pthread_threadid_np
+ _timespec_get
CStrings:
+ "ODTHeatmapPose: ncand=%zu,ncams=%zu,preemptive=%u,gp3p=%u,quorum=%u,n_filtered=%zu,n_factors=%zu,required=%zu"
+ "Trace"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::cv::CVImageBuffer<img::Format::Two16u>]"
+ "static auto cv3d::esn::TypeNameHelpers::PrettyArgName() [T = cv3d::kit::iosimg::IOSurfaceImageBuffer<img::Format::Two16u>]"
+ "tracing"
```
