## SiriAutoCompleteAPI

> `/System/Library/PrivateFrameworks/SiriAutoCompleteAPI.framework/SiriAutoCompleteAPI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2fbc0` | `0x300e0` | **`+0x520`** |
| `__TEXT.__oslogstring` | `0x11de` | `0x12be` | **`+0xe0`** |
| `__TEXT.__eh_frame` | `0x1ae8` | `0x1b20` | **`+0x38`** |
| `__TEXT.__cstring` | `0xb3c` | `0xb5c` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x9b0` | `0x9c0` | **`+0x10`** |
| `__TEXT.__const` | `0x199c` | `0x19ac` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xdc0` | `0xdd0` | **`+0x10`** |
| `__DATA.__data` | `0x248` | `0x250` | **`+0x8`** |

### Other Changes

```diff

-3600.11.7.0.0
+3605.5.1.0.0

+  - /System/Library/PrivateFrameworks/TCC.framework/TCC

-  Functions: 1430
-  Symbols:   624
-  CStrings:  148
+  Functions: 1435
+  Symbols:   625
+  CStrings:  152
Symbols:
+ _TCCAccessCopyBundleIdentifiersDisabledForService
CStrings:
+ "BlockedAppsProvider: AppExclusions FF disabled, no LFTA preference found"
+ "BlockedAppsProvider: AppExclusions FF enabled, got %ld excluded apps from TCC"
+ "BlockedAppsProvider: LFTA fallback, got %ld excluded apps"
+ "kTCCServiceSiriAccess"
```
