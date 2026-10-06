## AppDistributionUI

> `/System/Library/PrivateFrameworks/AppDistributionUI.framework/AppDistributionUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x167b8` | `0x168f0` | **`+0x138`** |
| `__TEXT.__oslogstring` | `0x15a` | `0x18a` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x1618` | `0x1640` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x378` | `0x398` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x660` | `0x650` | **`-0x10`** |
| `__TEXT.__cstring` | `0x743` | `0x753` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x128` | `0x138` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x7e8` | `0x7f0` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x7ac` | `0x7b0` | **`+0x4`** |

### Other Changes

```diff

-4.0.44.0.0
+4.1.9.0.0

-  Functions: 712
+  Functions: 714

-  CStrings:  47
+  CStrings:  48
Symbols:
+ _swift_isEscapingClosureAtFileLocation
+ _swift_retain_x22
+ _symbolic Ig_
- ___stack_chk_fail
- ___stack_chk_guard
- _swift_errorRelease
CStrings:
+ "[%{public}s] No image data provided"
```
