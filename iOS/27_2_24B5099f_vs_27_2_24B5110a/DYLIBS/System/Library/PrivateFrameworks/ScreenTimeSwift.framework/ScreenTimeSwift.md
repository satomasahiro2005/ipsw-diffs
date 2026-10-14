## ScreenTimeSwift

> `/System/Library/PrivateFrameworks/ScreenTimeSwift.framework/ScreenTimeSwift`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9400c` | `0x963f4` | **`+0x23e8`** |
| `__TEXT.__eh_frame` | `0x3240` | `0x3438` | **`+0x1f8`** |
| `__DATA.__bss` | `0x7430` | `0x75b0` | **`+0x180`** |
| `__TEXT.__swift5_reflstr` | `0x1efb` | `0x202b` | **`+0x130`** |
| `__TEXT.__const` | `0x50dc` | `0x51cc` | **`+0xf0`** |
| `__AUTH_CONST.__const` | `0x2fb8` | `0x30a0` | **`+0xe8`** |
| `__TEXT.__cstring` | `0xd27` | `0xdd7` | **`+0xb0`** |
| `__TEXT.__swift5_fieldmd` | `0x166c` | `0x1710` | **`+0xa4`** |
| `__TEXT.__unwind_info` | `0x1a78` | `0x1b10` | **`+0x98`** |
| `__TEXT.__oslogstring` | `0x209f` | `0x211f` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x1b92` | `0x1c00` | **`+0x6e`** |
| `__TEXT.__constg_swiftt` | `0x1250` | `0x1294` | **`+0x44`** |
| `__DATA.__data` | `0x12e8` | `0x1320` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x14f0` | `0x1518` | **`+0x28`** |
| `__DATA_DIRTY.__data` | `0x14b8` | `0x1498` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0x190` | `0x1b0` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x1f8` | `0x210` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xde8` | `0xdf8` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0xe4` | `0xf4` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x3e0` | `0x3ec` | **`+0xc`** |
| `__TEXT.__swift5_protos` | `0x30` | `0x34` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x158` | `0x15c` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xd0` | `0xd4` | **`+0x4`** |

### Other Changes

```diff

-655.1.12.0.0
+655.1.14.1.0

-  Functions: 2451
-  Symbols:   955
-  CStrings:  206
+  Functions: 2492
+  Symbols:   963
+  CStrings:  213
Symbols:
+ ___swift_closure_destructor.65Tm
+ ___swift_memcpy25_8
+ ___swift_memcpy35_8
+ _associated conformance 15ScreenTimeSwift34MigrationSectionDismissalConstantsO09PermanentF0OSHAASQ
+ _associated conformance 15ScreenTimeSwift34MigrationSectionDismissalConstantsO09PermanentF0Os12CaseIterableAA8AllCasessAFP_Sl
+ _symbolic $s15ScreenTimeSwift0aB26SettingsMigratorJournalingP
+ _symbolic Say_____G 15ScreenTimeSwift34MigrationSectionDismissalConstantsO09PermanentF0O
+ _symbolic SbyKc
+ _symbolic _____ 15ScreenTimeSwift34MigrationSectionDismissalConstantsO09PermanentF0O
+ _symbolic ______p 15ScreenTimeSwift0aB26SettingsMigratorJournalingP
+ _symbolic ______pSg 15ScreenTimeSwift0aB26SettingsMigratorJournalingP
+ _symbolic ______pSiYaKc 14ScreenTimeCore019ExpressIntroductionaB16SettingsApplyingP
- ___swift_closure_destructor.63Tm
- ___swift_memcpy24_8
- ___swift_memcpy34_8
- _symbolic _____Sg_ABt 26ScreenTimeSettingsServices0abC0C9MigrationV5StateO
CStrings:
+ "Disabling remote management for DSID %{private}@"
+ "Failed to get isLocalUserMigrated: %{public}@"
+ "New Screen Time existing settings management policy is enabled: %{bool,public}d"
+ "NotInFamilyBannerDismissed"
+ "UnresolvableFragmentationDismissed.familySettings"
+ "UnresolvableFragmentationDismissed.screenTimeSettings"
+ "User %{private}s is managed: %{bool,public}d"
+ "isManagedInNewScreenTime"
+ "shouldOfferFamilySetUp"
- "MigrationSectionDismissalOSVersion"
- "Requested settings for a remote user, which the New Screen Time shim doesn't support; using legacy store"
```
