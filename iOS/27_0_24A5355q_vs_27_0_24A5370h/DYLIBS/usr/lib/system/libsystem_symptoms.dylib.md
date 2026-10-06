## libsystem_symptoms.dylib

> `/usr/lib/system/libsystem_symptoms.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5bf0` | `0x5a7c` | **`-0x174`** |
| `__TEXT.__cstring` | `0x18b3` | `0x1839` | **`-0x7a`** |
| `__DATA_CONST.__const` | `0x1c0` | `0x168` | **`-0x58`** |
| `__AUTH_CONST.__const` | `0xa0` | `0x80` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x20` | `0x10` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x118` | `0x128` | **`+0x10`** |
| `__DATA.__bss` | `0x28` | `0x20` | **`-0x8`** |

### Other Changes

```diff

-2357.0.0.0.2
+2374.0.0.0.0

-  Functions: 69
-  Symbols:   142
-  CStrings:  195
+  Functions: 67
+  Symbols:   135
+  CStrings:  185
Symbols:
- ____symptoms_is_daemon_fallback_blacklisted_block_invoke
- __block_invoke_2.kBlacklistedProcessNameList
- __symptoms_is_daemon_fallback_blacklisted.is_fallback_blacklisted
- __symptoms_is_daemon_fallback_blacklisted.is_media_play
- __symptoms_is_daemon_fallback_blacklisted.onceToken
- _strcasecmp
- _strcmp
CStrings:
- "appstored"
- "bird"
- "cloudd"
- "com.apple.mobilesafari"
- "itunescloudd"
- "itunesstored"
- "mediaplaybackd"
- "mediaserverd"
- "mstreamd"
- "nsurlsessiond"
```
