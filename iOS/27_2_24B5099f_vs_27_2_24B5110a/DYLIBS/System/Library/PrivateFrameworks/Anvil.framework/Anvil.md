## Anvil

> `/System/Library/PrivateFrameworks/Anvil.framework/Anvil`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x121bfc` | `0x122710` | **`+0xb14`** |
| `__TEXT.__oslogstring` | `0x392a` | `0x39fa` | **`+0xd0`** |
| `__TEXT.__eh_frame` | `0x9a40` | `0x9a70` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0xb6e1` | `0xb6c1` | **`-0x20`** |
| `__TEXT.__cstring` | `0x353c` | `0x355c` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0xee8` | `0xed4` | **`-0x14`** |
| `__TEXT.__swift5_reflstr` | `0x2053` | `0x2063` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x3f1c` | `0x3f28` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `0x784` | `0x790` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x2fcd` | `0x2fc5` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x2cc` | `0x2d4` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x264` | `0x268` | **`+0x4`** |

### Other Changes

```diff

-110.0.0.0.0
+112.0.0.0.0

-  Functions: 5367
-  Symbols:   1678
-  CStrings:  689
+  Functions: 5374
+  Symbols:   1677
+  CStrings:  693
Symbols:
- _symbolic Sbz_Xx
CStrings:
+ "A rate limiting token fetch failed for a reason unrelated to the budget. Leaving the stored rate limit verdict unchanged."
+ "Anonymous user is rate limited."
+ "Failed to fetch token from network proxy with error %@. Leaving the stored rate limit verdict unchanged."
+ "Failed to read rate limiting: %@"
+ "privacyProxyErrorDomain"
- "Failed to fetch token from network proxy with error %@, assuming anonymous user is rate limited."
```
