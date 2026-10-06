## PrivacyDisclosureCore

> `/System/Library/PrivateFrameworks/PrivacyDisclosureCore.framework/PrivacyDisclosureCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e14` | `0x3f0c` | **`+0xf8`** |
| `__TEXT.__oslogstring` | `0x244` | `0x2d0` | **`+0x8c`** |
| `__AUTH_CONST.__cfstring` | `0x1a0` | `0x180` | **`-0x20`** |
| `__DATA.__bss` | `0xb1` | `0xc1` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x28` | `0x18` | **`-0x10`** |
| `__TEXT.__cstring` | `0x444` | `0x43a` | **`-0xa`** |
| `__TEXT.__const` | `0x80` | `0x88` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1e8` | `0x1e0` | **`-0x8`** |

### Other Changes

```diff

-49.0.1.0.0
+53.0.0.0.0

-  - /usr/lib/libMobileGestalt.dylib

-  Functions: 133
+  Functions: 134

-  CStrings:  55
+  CStrings:  56
Symbols:
+ ___isTennessineEligible_block_invoke
+ _isTennessineEligible.once
+ _isTennessineEligible.result
+ _os_eligibility_get_domain_answer
- _MGGetBoolAnswer
- ___isGreenTea_block_invoke
- _isGreenTea.once
- _isGreenTea.result
Functions:
- ___isGreenTea_block_invoke
+ ___isTennessineEligible_block_invoke
+ ___isTennessineEligible_block_invoke.cold.1
CStrings:
+ "Failed to query OS_ELIGIBILITY_DOMAIN_TENNESSINE: %{darwin.errno}d"
+ "OS_ELIGIBILITY_DOMAIN_TENNESSINE answered %llu, treating as not eligible"
- "green-tea"
```
