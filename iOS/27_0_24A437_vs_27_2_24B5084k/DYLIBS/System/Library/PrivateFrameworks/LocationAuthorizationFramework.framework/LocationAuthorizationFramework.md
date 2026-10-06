## LocationAuthorizationFramework

> `/System/Library/PrivateFrameworks/LocationAuthorizationFramework.framework/LocationAuthorizationFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6787c` | `0x67c44` | **`+0x3c8`** |
| `__TEXT.__cstring` | `0x292d` | `0x2b39` | **`+0x20c`** |
| `__AUTH_CONST.__cfstring` | `0x1560` | `0x1720` | **`+0x1c0`** |
| `__TEXT.__oslogstring` | `0x7312` | `0x7432` | **`+0x120`** |
| `__DATA_CONST.__objc_arraydata` | `0x80` | `0xe8` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0xed0` | `0xef8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x1330` | `0x1358` | **`+0x28`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x48` | `0x60` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1668` | `0x1678` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x1060` | `0x1054` | **`-0xc`** |
| `__DATA_CONST.__const` | `0x870` | `0x868` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x368` | `0x370` | **`+0x8`** |

### Other Changes

```diff

-3185.0.6.0.3
+3186.0.12.0.0

-  Functions: 1922
-  Symbols:   439
-  CStrings:  563
+  Functions: 1926
+  Symbols:   440
+  CStrings:  589
Symbols:
+ _OBJC_CLASS_$_NSSet
CStrings:
+ "#RegisterClientKeyPath passed a known-invalid identity that must not be its own client. Returning #nullCKP."
+ "AllowedAlways"
+ "AllowedAlwaysProvisionally"
+ "AllowedWhenInUse"
+ "AuthContext InUse:%d  RegResult Transient:%s Effective:%s  EffectiveMask:%d  ProvisionalMask:%d  DiagnosticMask:%d"
+ "FailedBlocklisted"
+ "FailedUnavailable"
+ "FailedUnverified"
+ "FailedUserDenied"
+ "Missing"
+ "RegistrationResultString"
+ "RequiresAgent"
+ "TransientAwareRegistrationResultString"
+ "UNKNOWN"
+ "com.apple.Carousel"
+ "com.apple.Home.HomeControlService"
+ "com.apple.Home.HomeUIService"
+ "com.apple.HomeKit.homeutil"
+ "com.apple.MusicUIService"
+ "com.apple.NanoPassbook"
+ "com.apple.PassbookUIService"
+ "com.apple.PeopleViewService"
+ "com.apple.SiriApp"
+ "com.apple.Spotlight"
+ "com.apple.campo"
+ "com.apple.siri"
+ "{\"msg%{public}.0s\":\"#RegisterClientKeyPath passed a known-invalid identity that must not be its own client. Returning #nullCKP.\", \"ClientKeyPath\":%{public, location:escape_only}@}"
- "AuthContext InUse:%d  RegResult:%d(%d) EffectiveMask:%d  ProvisionalMask:%d  DiagnosticMask:%d"
```
