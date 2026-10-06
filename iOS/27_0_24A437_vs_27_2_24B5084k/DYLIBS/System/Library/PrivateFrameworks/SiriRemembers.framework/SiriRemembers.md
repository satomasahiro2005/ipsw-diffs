## SiriRemembers

> `/System/Library/PrivateFrameworks/SiriRemembers.framework/SiriRemembers`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb4f78` | `0xb522c` | **`+0x2b4`** |
| `__DATA_DIRTY.__data` | `0x2cc8` | `0x2c18` | **`-0xb0`** |
| `__AUTH.__data` | `0x428` | `0x4c8` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x3ed5` | `0x3f25` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x40` | `—` | **`-0x40`** |
| `__TEXT.__eh_frame` | `0x4d08` | `0x4d40` | **`+0x38`** |
| `__TEXT.__cstring` | `0x3401` | `0x33d1` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x1448` | `0x1468` | **`+0x20`** |
| `__DATA.__data` | `0x1500` | `0x1510` | **`+0x10`** |
| `__DATA_CONST.__const` | `0xf0` | `0xe0` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x25b4` | `0x25c0` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x710` | `0x718` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0x1b8` | `0x1b0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2df0` | `0x2df8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-3600.34.21.0.0
+3605.12.1.0.0

+  - /System/Library/PrivateFrameworks/TCC.framework/TCC

-  Functions: 5132
-  Symbols:   1624
-  CStrings:  549
+  Functions: 5133
+  Symbols:   1625
+  CStrings:  548
Symbols:
+ _OBJC_CLASS_$_NSLock
+ _TCCAccessCopyBundleIdentifiersDisabledForService
+ __DATA__TtC13SiriRemembers22SiriAppExclusionClient
+ __METACLASS_DATA__TtC13SiriRemembers22SiriAppExclusionClient
+ _kTCCServiceSiriAccess
+ _symbolic $s13SiriRemembers0A26AppExclusionClientProtocolP
+ _symbolic So6NSLockC
+ _symbolic _____ 13SiriRemembers0A18AppExclusionClientC
+ _symbolic ______p 13SiriRemembers0A26AppExclusionClientProtocolP
- _CFPreferencesCopyAppValue
- _SGSiriCanLearnFromApp
- __DATA__TtC13SiriRemembers21CoreSuggestionsClient
- __METACLASS_DATA__TtC13SiriRemembers21CoreSuggestionsClient
- ___CFConstantStringClassReference
- _symbolic $s13SiriRemembers29CoreSuggestionsClientProtocolP
- _symbolic _____ 13SiriRemembers21CoreSuggestionsClientC
- _symbolic ______p 13SiriRemembers29CoreSuggestionsClientProtocolP
CStrings:
+ "SiriRemembers failed to read the kTCCServiceSiriAccess exclusion list."
- "SiriCanLearnFromAppBlacklist"
- "com.apple.suggestions"
```
