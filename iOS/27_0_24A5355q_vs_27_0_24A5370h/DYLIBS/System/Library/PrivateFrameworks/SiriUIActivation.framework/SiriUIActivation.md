## SiriUIActivation

> `/System/Library/PrivateFrameworks/SiriUIActivation.framework/SiriUIActivation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x4bdb` | `0x4d7b` | **`+0x1a0`** |
| `__TEXT.__text` | `0x2f390` | `0x2f2e4` | **`-0xac`** |
| `__TEXT.__cstring` | `0x4bab` | `0x4c2b` | **`+0x80`** |
| `__AUTH_CONST.__objc_const` | `0x28f8` | `0x2928` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x6ec` | `0x6d0` | **`-0x1c`** |
| `__TEXT.__objc_methlist` | `0x26b8` | `0x26d0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x5e8` | `0x5d8` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1fd0` | `0x1fe0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xaa8` | `0xab0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xdf0` | `0xde8` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x1b8` | `0x1bc` | **`+0x4`** |

### Other Changes

```diff

-3600.49.31.1.6
+3600.55.10.0.0

-  Functions: 1075
-  Symbols:   1657
-  CStrings:  615
+  Functions: 1074
+  Symbols:   1660
+  CStrings:  621
Symbols:
+ -[SASUICampoResumableSession initWithSessionIdentifier:expiryDate:lockState:]
+ -[SASUICampoResumableSession lockState]
+ -[SASUICampoSessionCoordinator cacheSessionIdentifier:lockState:]
+ -[SASUICampoSessionCoordinator getResumableSessionIdentifierForLockState:]
+ -[SiriPresentationViewController _cacheCampoSessionIdentifierIfNeededForDismissalOptions:]
+ GCC_except_table126
+ GCC_except_table131
+ GCC_except_table133
+ GCC_except_table135
+ GCC_except_table137
+ GCC_except_table139
+ GCC_except_table145
+ GCC_except_table154
+ GCC_except_table169
+ GCC_except_table174
+ GCC_except_table193
+ GCC_except_table195
+ GCC_except_table217
+ GCC_except_table220
+ GCC_except_table229
+ GCC_except_table249
+ GCC_except_table276
+ GCC_except_table283
+ GCC_except_table288
+ GCC_except_table300
+ GCC_except_table302
+ GCC_except_table304
+ GCC_except_table312
+ _AFIsLinwoodEnabledAndWasEverAvailable
+ _OBJC_IVAR_$_SASUICampoResumableSession._lockState
- -[SASUICampoResumableSession initWithSessionIdentifier:expiryDate:]
- -[SASUICampoSessionCoordinator cacheSessionIdentifier:]
- -[SASUICampoSessionCoordinator getResumableSessionIdentifier]
- GCC_except_table125
- GCC_except_table129
- GCC_except_table132
- GCC_except_table134
- GCC_except_table136
- GCC_except_table138
- GCC_except_table144
- GCC_except_table153
- GCC_except_table168
- GCC_except_table173
- GCC_except_table192
- GCC_except_table194
- GCC_except_table216
- GCC_except_table218
- GCC_except_table227
- GCC_except_table248
- GCC_except_table274
- GCC_except_table282
- GCC_except_table287
- GCC_except_table299
- GCC_except_table301
- GCC_except_table303
- GCC_except_table311
- _AFIsLinwoodEnabledAndAvailable
CStrings:
+ "%s #Campo Caching session identifer: %@ lockState: %zd"
+ "%s #Campo Lock state mismatch: cached %zd, current %zd. Not resuming."
+ "%s #activation #campo Skipping cached session resumption for identifier already set"
+ "%s #activation #campo Skipping cached session resumption for new conversation request"
+ "%s #activation #campo Skipping cached session resumption for preprocess request"
+ "%s #activation #campo Skipping sessionIdentifier cache due to preprocess preemption"
+ "-[SASUICampoSessionCoordinator cacheSessionIdentifier:lockState:]"
+ "-[SASUICampoSessionCoordinator getResumableSessionIdentifierForLockState:]"
+ "-[SiriPresentationViewController _cacheCampoSessionIdentifierIfNeededForDismissalOptions:]"
- "%s #Campo Caching session identifer: %@"
- "-[SASUICampoSessionCoordinator cacheSessionIdentifier:]"
- "-[SASUICampoSessionCoordinator getResumableSessionIdentifier]"
```
