## PrivateMLClientInferenceProvider

> `/System/Library/PrivateFrameworks/PrivateMLClientInferenceProvider.framework/PrivateMLClientInferenceProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8f73c` | `0x909f8` | **`+0x12bc`** |
| `__DATA_DIRTY.__data` | `0x8a0` | `0x928` | **`+0x88`** |
| `__DATA.__data` | `0x568` | `0x4f8` | **`-0x70`** |
| `__AUTH_CONST.__auth_got` | `0x1960` | `0x19b8` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x3d6b` | `0x3dab` | **`+0x40`** |
| `__TEXT.__const` | `0x1e38` | `0x1e58` | **`+0x20`** |
| `__TEXT.__cstring` | `0xd9b` | `0xdbb` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0xb02` | `0xb20` | **`+0x1e`** |
| `__TEXT.__unwind_info` | `0xcc8` | `0xcc0` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x210` | `0x20c` | **`-0x4`** |

### Other Changes

```diff

-204.0.2.0.0
+207.0.3.0.0

-  Functions: 874
-  Symbols:   504
-  CStrings:  377
+  Functions: 873
+  Symbols:   509
+  CStrings:  379
Symbols:
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _symbolic _____Sg 29GenerativeFunctionsFoundation0A5ErrorV06PromptD0V0D4TypeO013AbuseRejectedD4InfoV5LevelO
+ _symbolic _____Sg 29GenerativeFunctionsFoundation0A5ErrorV06PromptD0V0D4TypeO013AbuseRejectedD4InfoV6ReasonO
+ _symbolic ___________t 29GenerativeFunctionsFoundation0A5ErrorV06PromptD0V0D4TypeO013AbuseRejectedD4InfoV 15TokenGeneration0jkD0O7ContextV
CStrings:
+ "%{private}s failed due to abuse rejection"
+ "Abuse rejected: reason="
+ "Failure alert already shown this session, skipping tap to radar prompt"
- "Radar already filed this session, skipping tap to radar prompt"
```
