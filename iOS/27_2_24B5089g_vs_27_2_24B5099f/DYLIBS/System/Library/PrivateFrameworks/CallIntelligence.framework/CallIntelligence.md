## CallIntelligence

> `/System/Library/PrivateFrameworks/CallIntelligence.framework/CallIntelligence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7be90` | `0x7c848` | **`+0x9b8`** |
| `__TEXT.__oslogstring` | `0xeb0` | `0xfa0` | **`+0xf0`** |
| `__TEXT.__eh_frame` | `0x3af4` | `0x3b34` | **`+0x40`** |
| `__TEXT.__cstring` | `0xbd1` | `0xbf1` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xc18` | `0xc20` | **`+0x8`** |
| `__AUTH_CONST.__const` | `0x5248` | `0x5250` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xae8` | `0xaf0` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x1a54` | `0x1a5c` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x504` | `0x50c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2310` | `0x2318` | **`+0x8`** |

### Other Changes

```diff

-156.200.88.2.3
+156.200.120.0.0

+  - /System/Library/PrivateFrameworks/TCC.framework/TCC

-  Functions: 3066
-  Symbols:   1396
-  CStrings:  159
+  Functions: 3070
+  Symbols:   1398
+  CStrings:  162
Symbols:
+ _OBJC_CLASS_$_NSArray
+ _TCCAccessCopyBundleIdentifiersDisabledForService
+ ___swift_closure_destructor.83Tm
+ _kTCCServiceSiriAccess
- ___swift_closure_destructor.82Tm
- _swift_retain_x28
CStrings:
+ "%ld bundle identifier(s) excluded from Siri learning"
+ "Dropping item from bundle source excluded from Siri learning: %{private}s"
+ "kTCCServiceSiriAccess is unavailable, treating no apps as excluded from Siri learning"
+ "runQuery(queryString:atTime:disableMinimumFieldRequirements:queryContainsName:searchedBusinessNames:excludedBundleIdentifiers:flags:)"
- "runQuery(queryString:atTime:disableMinimumFieldRequirements:queryContainsName:searchedBusinessNames:flags:)"
```
