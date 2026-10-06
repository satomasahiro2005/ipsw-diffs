## AppleIDSetup

> `/System/Library/PrivateFrameworks/AppleIDSetup.framework/AppleIDSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x214344` | `0x215bec` | **`+0x18a8`** |
| `__TEXT.__oslogstring` | `0x64d0` | `0x66b0` | **`+0x1e0`** |
| `__TEXT.__eh_frame` | `0x10df8` | `0x10f14` | **`+0x11c`** |
| `__TEXT.__const` | `0x2c140` | `0x2c250` | **`+0x110`** |
| `__AUTH.__data` | `0x3378` | `0x3418` | **`+0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x6ed8` | `0x6f68` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x8600` | `0x8674` | **`+0x74`** |
| `__AUTH_CONST.__auth_got` | `0x14b0` | `0x1510` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x95bc` | `0x961c` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0xa140` | `0xa190` | **`+0x50`** |
| `__DATA.__data` | `0x9648` | `0x9678` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x920` | `0x948` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x8064` | `0x8084` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xf20` | `0xf38` | **`+0x18`** |
| `__AUTH.__objc_data` | `0x1ee0` | `0x1ef0` | **`+0x10`** |
| `__AUTH_CONST.__const` | `0x16088` | `0x16098` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xb14` | `0xb20` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x7b0` | `0x7bc` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x77c` | `0x788` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x1c8` | `0x1d0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x2794` | `0x2798` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0xdc` | `0xe0` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0xa5c` | `0xa60` | **`+0x4`** |

### Other Changes

```diff

-120.0.0.0.0
+122.0.0.0.0

-  Functions: 13869
-  Symbols:   4708
-  CStrings:  866
+  Functions: 13889
+  Symbols:   4720
+  CStrings:  870
Symbols:
+ _AKOSEDomainUnverifiedAdultBackgroundRestrictionRequired
+ _AKOSEDomainUnverifiedAdultBackgroundRestrictionRequiredMiniBuddy
+ _OBJC_CLASS_$_STMutableRestrictions
+ __DATA__TtC12AppleIDSetup17AISScreenTimeShim
+ __METACLASS_DATA__TtC12AppleIDSetup17AISScreenTimeShim
+ _symbolic $s12AppleIDSetup25AISScreenTimeShimProtocolP
+ _symbolic _____ 12AppleIDSetup17AISScreenTimeShimC
+ _symbolic _____Sg 15ScreenTimeSwift21STExpressIntroductionO0A16DistanceSettingsV
+ _symbolic _____Sg 15ScreenTimeSwift21STExpressIntroductionO27CommunicationLimitsSettingsV
+ _symbolic _____Sg 15ScreenTimeSwift21STExpressIntroductionO27CommunicationSafetySettingsV
+ _symbolic _____Sg 15ScreenTimeSwift21STExpressIntroductionO27ContentRestrictionsSettingsV
+ _symbolic _____Sg 15ScreenTimeSwift21STExpressIntroductionO29AppAndWebsiteActivitySettingsV
CStrings:
+ "Age assurance check - flowType: %s, verificationRequired: %{bool}d, restrictionsRequired: %{bool}d, shouldPresent: %{bool}d"
+ "Age assurance is not required (no verification or unverified-adult restriction domains enabled) - not showing age assurance"
+ "Age assurance required check passed"
+ "Applied background restrictions (web content filter + communication safety) to local user"
+ "isAgeVerificationDomainEnabled - flowType: %s, verificationRequired: %{bool}d"
+ "isUnverifiedAdultBackgroundRestrictionsDomainEnabled - flowType: %s, restrictionsRequired: %{bool}d"
- "Age verification is not required - not showing age assurance"
- "Age verification required check passed"
```
