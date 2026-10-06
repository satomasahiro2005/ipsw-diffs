## AppManagedFeatures

> `/System/Library/Frameworks/AppManagedFeatures.framework/AppManagedFeatures`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7155c` | `0x7751c` | **`+0x5fc0`** |
| `__TEXT.__eh_frame` | `0x7810` | `0x7ed8` | **`+0x6c8`** |
| `__TEXT.__const` | `0x7130` | `0x74f0` | **`+0x3c0`** |
| `__TEXT.__cstring` | `0x2533` | `0x2753` | **`+0x220`** |
| `__TEXT.__unwind_info` | `0x2690` | `0x2890` | **`+0x200`** |
| `__AUTH_CONST.__const` | `0x3390` | `0x34d8` | **`+0x148`** |
| `__TEXT.__swift5_reflstr` | `0xeac` | `0xf7c` | **`+0xd0`** |
| `__TEXT.__swift_as_cont` | `0x734` | `0x7e0` | **`+0xac`** |
| `__DATA.__bss` | `0x6f80` | `0x7000` | **`+0x80`** |
| `__TEXT.__swift_as_ret` | `0x47c` | `0x4e4` | **`+0x68`** |
| `__TEXT.__constg_swiftt` | `0x11c4` | `0x1218` | **`+0x54`** |
| `__TEXT.__swift5_acfuncs` | `0x488` | `0x4d8` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x1020` | `0x106c` | **`+0x4c`** |
| `__TEXT.__swift_as_entry` | `0x328` | `0x368` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x910` | `0x940` | **`+0x30`** |
| `__DATA.__data` | `0xb00` | `0xb30` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x172b` | `0x175b` | **`+0x30`** |
| `__AUTH.__data` | `0x4b0` | `0x4c8` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x1a4` | `0x1b8` | **`+0x14`** |
| `__DATA_DIRTY.__data` | `0x5c0` | `0x5b0` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c8` | `0x1d0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x3dc` | `0x3e0` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x130` | `0x134` | **`+0x4`** |

### Other Changes

```diff

-46.0.15.0.0
+58.40.9.0.0

-  Functions: 2138
-  Symbols:   647
-  CStrings:  262
+  Functions: 2215
+  Symbols:   654
+  CStrings:  272
Symbols:
+ ___unnamed_23
+ _associated conformance 18AppManagedFeatures22BuddyEnrollmentOutcomeO20ShowPanelsCodingKeys33_B22A383BAFBD5086520B202E8405645ELLOSHAASQ
+ _swift_asyncLet_begin
+ _swift_asyncLet_finish
+ _swift_asyncLet_get
+ _swift_retain_x1
+ _symbolic Sb22requiresSoftwareUpdate_t
+ _symbolic ScSy_____GIeghHn_Sg 18AppManagedFeatures15InstallProgressV
+ _symbolic _____ 18AppManagedFeatures0abC9ConstantsO24AccessibilityIdentifiersO20ExitLimitedModeAlertO
- ___unnamed_19
- _associated conformance 18AppManagedFeatures22BuddyEnrollmentOutcomeOSHAASQ
CStrings:
+ " is no longer restricting access to apps and functionality on your device. Restrictions may be reapplied if you miss a payment."
+ "ExitRestrictedModeAlert"
+ "ExitRestrictedModeAlert.OKButton"
+ "LaunchServicesMetadataProvider"
+ "Restricted Mode is Off"
+ "TestingManager corruptArchivedManagementProviderConfiguration()"
+ "TestingManager corruptManagementProviderConfiguration()"
+ "The required SUManagerClient could not be created."
+ "corruptArchivedManagementProviderConfiguration()"
+ "corruptManagementProviderConfiguration()"
+ "requiresSoftwareUpdate"
- "The required SUManagerClient cloud not be create.."
```
