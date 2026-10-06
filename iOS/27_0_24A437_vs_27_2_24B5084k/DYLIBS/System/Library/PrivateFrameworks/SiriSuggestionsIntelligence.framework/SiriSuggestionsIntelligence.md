## SiriSuggestionsIntelligence

> `/System/Library/PrivateFrameworks/SiriSuggestionsIntelligence.framework/SiriSuggestionsIntelligence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x85ec8` | `0x86108` | **`+0x240`** |
| `__TEXT.__oslogstring` | `0x20b3` | `0x2133` | **`+0x80`** |
| `__TEXT.__cstring` | `0xd1c` | `0xd3c` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1038` | `0x1050` | **`+0x18`** |
| `__TEXT.__const` | `0x9100` | `0x9110` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2ad0` | `0x2ae0` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x28bc` | `0x28c8` | **`+0xc`** |

### Other Changes

```diff

-3600.11.7.0.0
+3605.5.1.0.0

+  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

+  - /System/Library/PrivateFrameworks/TCC.framework/TCC

-  Functions: 4213
-  Symbols:   1695
-  CStrings:  256
+  Functions: 4219
+  Symbols:   1696
+  CStrings:  258
Symbols:
+ _TCCAccessCopyBundleIdentifiersDisabledForService
CStrings:
+ "AppIdValidator: AppExclusions FF disabled, no LFTA preference found"
+ "AppIdValidator: AppExclusions FF enabled, got %ld disabled apps from TCC"
+ "AppIdValidator: LFTA fallback, got %ld disabled apps"
+ "kTCCServiceSiriAccess"
- "Got disabledApps blocklist as: %s"
- "Unable to get disabledApps blocklist"
```
