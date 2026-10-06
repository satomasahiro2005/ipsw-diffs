## IntelligencePlatformCore

> `/System/Library/PrivateFrameworks/IntelligencePlatformCore.framework/IntelligencePlatformCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb3e69c` | `0xb41984` | **`+0x32e8`** |
| `__TEXT.__oslogstring` | `0x1fd6b` | `0x1fe0a` | **`+0x9f`** |
| `__TEXT.__eh_frame` | `0x60088` | `0x60000` | **`-0x88`** |
| `__AUTH_CONST.__cfstring` | `0x360` | `0x320` | **`-0x40`** |
| `__TEXT.__cstring` | `0x311ff` | `0x311bf` | **`-0x40`** |
| `__TEXT.__const` | `0x7d5a0` | `0x7d578` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x29030` | `0x29018` | **`-0x18`** |
| `__TEXT.__swift5_reflstr` | `0x2655f` | `0x2656f` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x4618` | `0x4620` | **`+0x8`** |

### Other Changes

```diff

-193.0.0.0.0
+194.0.0.0.0

+  - /System/Library/PrivateFrameworks/TCC.framework/TCC

-  Functions: 67614
-  Symbols:   1005
+  Functions: 67596
+  Symbols:   1007
Symbols:
+ _GDSiriCanLearnFromApp
+ _TCCAccessCopyBundleIdentifiersDisabledForService
+ _kTCCServiceSiriAccess
- _CFPreferencesCopyAppValue
CStrings:
+ "GDSiriCanLearnFromApp: bundleID=%{public}@ canLearn=%{public}d"
+ "Now playing progress token %f is in the future, ingesting from the start of the stream instead"
- "SiriCanLearnFromAppBlacklist"
- "com.apple.suggestions"
```
