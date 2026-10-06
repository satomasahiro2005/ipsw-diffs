## SearchOnDeviceAnalytics

> `/System/Library/PrivateFrameworks/SearchOnDeviceAnalytics.framework/SearchOnDeviceAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16cf70` | `0x16d2e8` | **`+0x378`** |
| `__AUTH_CONST.__const` | `0xc698` | `0xc4b8` | **`-0x1e0`** |
| `__TEXT.__swift5_capture` | `0xae4` | `0xa24` | **`-0xc0`** |
| `__TEXT.__cstring` | `0x5ef4` | `0x5f54` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0xa01` | `0xa31` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x290` | `0x2b8` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0xce64` | `0xce3c` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x8758` | `0x8730` | **`-0x28`** |
| `__DATA.__data` | `0x58c0` | `0x58d0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x17e8` | `0x17e0` | **`-0x8`** |

### Other Changes

```diff

-3600.56.16.0.0
+3600.56.21.0.0

+  - /System/Library/PrivateFrameworks/RunningBoardServices.framework/RunningBoardServices

-  Functions: 15286
-  Symbols:   3376
-  CStrings:  621
+  Functions: 15263
+  Symbols:   3379
+  CStrings:  625
Symbols:
+ _OBJC_CLASS_$_RBSAssertion
+ _OBJC_CLASS_$_RBSAttribute
+ _OBJC_CLASS_$_RBSDomainAttribute
+ _OBJC_CLASS_$_RBSTarget
- _objc_retain_x27
CStrings:
+ "Failed to acquire RBS assertion: %@"
+ "FinishTaskUninterruptable"
+ "ODLA recipe asset lookup"
+ "com.apple.common"
```
