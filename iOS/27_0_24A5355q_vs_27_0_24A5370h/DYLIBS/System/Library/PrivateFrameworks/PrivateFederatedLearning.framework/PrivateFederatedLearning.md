## PrivateFederatedLearning

> `/System/Library/PrivateFrameworks/PrivateFederatedLearning.framework/PrivateFederatedLearning`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7ebdc` | `0x81c10` | **`+0x3034`** |
| `__TEXT.__eh_frame` | `0x46e8` | `0x4960` | **`+0x278`** |
| `__TEXT.__oslogstring` | `0x1758` | `0x1938` | **`+0x1e0`** |
| `__AUTH_CONST.__objc_const` | `0x5d40` | `0x5c68` | **`-0xd8`** |
| `__AUTH.__data` | `0x2e50` | `0x2da0` | **`-0xb0`** |
| `__AUTH_CONST.__auth_got` | `0x1110` | `0x1198` | **`+0x88`** |
| `__TEXT.__const` | `0x3b50` | `0x3ac8` | **`-0x88`** |
| `__DATA.__bss` | `0x3310` | `0x3290` | **`-0x80`** |
| `__TEXT.__swift5_reflstr` | `0x2057` | `0x20bd` | **`+0x66`** |
| `__TEXT.__unwind_info` | `0x1810` | `0x1868` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0x2380` | `0x233c` | **`-0x44`** |
| `__DATA_CONST.__got` | `0x508` | `0x540` | **`+0x38`** |
| `__TEXT.__cstring` | `0x945` | `0x975` | **`+0x30`** |
| `__DATA.__data` | `0xb98` | `0xbc0` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x10fa` | `0x111c` | **`+0x22`** |
| `__TEXT.__swift5_fieldmd` | `0x1a78` | `0x1a98` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x2641` | `0x2659` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x17d8` | `0x17f0` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x13c` | `0x154` | **`+0x18`** |
| `__DATA.__common` | `0x68` | `0x70` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1b8` | `0x1b0` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x148` | `0x140` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0xd8` | `0xe0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xbc` | `0xc4` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1ec` | `0x1e8` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0x148` | `0x144` | **`-0x4`** |

### Other Changes

```diff

-26.0.0.0.0
+31.0.0.0.0

+  - /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics
+  - /System/Library/Frameworks/ExtensionFoundation.framework/ExtensionFoundation

-  Functions: 1794
-  Symbols:   922
-  CStrings:  207
+  Functions: 1803
+  Symbols:   921
+  CStrings:  216
Symbols:
+ _OBJC_CLASS_$_NSBundle
+ _swift_release_x13
+ _symbolic SS_______pt 15PriMLFoundation25DeviceBoundCohortResolverP
+ _symbolic _____ySSShySSGG s18_DictionaryStorageC
+ _symbolic _____ySS______pG s18_DictionaryStorageC 15PriMLFoundation25DeviceBoundCohortResolverP
- __DATA__TtC24PrivateFederatedLearning15PFLTaskIdentity
- __IVARS__TtC24PrivateFederatedLearning15PFLTaskIdentity
- __METACLASS_DATA__TtC24PrivateFederatedLearning15PFLTaskIdentity
- _swift_release_x12
- _symbolic _____ 15PriMLFoundation8TaskTypeO
- _symbolic _____ 24PrivateFederatedLearning15PFLTaskIdentityC
CStrings:
+ "Cohort key '%s' not allowed for prefix '%s'"
+ "Data-bound cohort '%s' not supported in PFL yet (expected '%s' prefix)"
+ "Failed to load CohortAllowList.plist from PFL bundle"
+ "Privacy budget prefix '%s' not in CohortAllowList — cohorts not authorized for this task"
+ "Skipping Dedisco donation: skip_donation=true (local-runs)."
+ "Skipping Dedisco error donation: skip_donation=true (local-runs)."
+ "Unknown device-bound cohort key '%s'"
+ "skip_donation"
+ "userSetDeviceRegion"
```
