## AdServices

> `/System/Library/Frameworks/AdServices.framework/AdServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b24` | `0x17c4` | **`-0x360`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c8` | `0x268` | **`-0x60`** |
| `__TEXT.__const` | `0xc8` | `0x70` | **`-0x58`** |
| `__TEXT.__oslogstring` | `0x2cc` | `0x27d` | **`-0x4f`** |
| `__AUTH_CONST.__cfstring` | `0x1c0` | `0x180` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0x188` | `0x148` | **`-0x40`** |
| `__AUTH_CONST.__objc_const` | `0x5e8` | `0x618` | **`+0x30`** |
| `__TEXT.__cstring` | `0x195` | `0x172` | **`-0x23`** |
| `__TEXT.__unwind_info` | `0xe0` | `0xd0` | **`-0x10`** |
| `__DATA_CONST.__const` | `0xd0` | `0xc8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x68` | `0x60` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x334` | `0x32c` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x38` | `0x3c` | **`+0x4`** |

### Other Changes

```diff

-557.1.24.0.0
+557.1.26.0.0

-  Functions: 50
-  Symbols:   79
-  CStrings:  38
+  Functions: 48
+  Symbols:   74
+  CStrings:  35
Symbols:
- __os_log_default
- __os_log_fault_impl
- _objc_retain_x20
- _objc_retain_x3
- _os_variant_has_internal_content
CStrings:
+ "Outcome"
+ "outcome"
- "-"
- "Simulating crash with description: \"Unexpected token source AATokenSourceNone\""
- "com.apple.ap.AdPlatformsCommon"
- "source"
- "tokenStatus"
```
