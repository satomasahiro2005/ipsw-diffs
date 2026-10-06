## MediaSuggester

> `/System/Library/PrivateFrameworks/MediaSuggester.framework/MediaSuggester`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x836f4` | `0x84ee4` | **`+0x17f0`** |
| `__AUTH_CONST.__const` | `0x5a28` | `0x6130` | **`+0x708`** |
| `__TEXT.__swift5_capture` | `0x1c58` | `0x1f28` | **`+0x2d0`** |
| `__TEXT.__oslogstring` | `0x247c` | `0x255c` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x1fe8` | `0x2030` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x40` | `—` | **`-0x40`** |
| `__TEXT.__swift5_typeref` | `0x1942` | `0x195a` | **`+0x18`** |
| `__TEXT.__const` | `0x3890` | `0x38a0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x21a4` | `0x2194` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0xc48` | `0xc50` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x630` | `0x638` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xbd0` | `0xbc8` | **`-0x8`** |

### Other Changes

```diff

-95.0.0.0.0
+98.0.0.0.0

+  - /System/Library/PrivateFrameworks/TCC.framework/TCC

-  Functions: 3871
+  Functions: 3928

-  CStrings:  405
+  CStrings:  407
Symbols:
+ _TCCAccessCopyBundleIdentifiersDisabledForService
+ _kTCCServiceSiriAccess
- _CFPreferencesCopyAppValue
- ___CFConstantStringClassReference
CStrings:
+ "No available bundleIDs after the Siri excluded apps filter, returning empty array"
+ "No installed app for bundle ID: %s"
+ "TCC gave no kTCCServiceSiriAccess exclusion list, treating each app as allowed"
+ "kTCCServiceSiriAccess exclusion list is not an array of bundle identifiers"
+ "requestIdentifierOverride"
- "No available bundleIDs that are enabled for LFTA, returning empty array"
- "SiriCanLearnFromAppBlacklist"
- "com.apple.suggestions"
```
