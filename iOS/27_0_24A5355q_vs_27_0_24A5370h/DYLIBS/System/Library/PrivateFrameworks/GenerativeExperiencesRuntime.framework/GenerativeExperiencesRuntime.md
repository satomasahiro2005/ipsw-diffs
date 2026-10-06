## GenerativeExperiencesRuntime

> `/System/Library/PrivateFrameworks/GenerativeExperiencesRuntime.framework/GenerativeExperiencesRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe1934` | `0xe5084` | **`+0x3750`** |
| `__AUTH_CONST.__const` | `0x7ae8` | `0x7d80` | **`+0x298`** |
| `__TEXT.__oslogstring` | `0x85c0` | `0x8770` | **`+0x1b0`** |
| `__TEXT.__eh_frame` | `0x8c9c` | `0x8e1c` | **`+0x180`** |
| `__TEXT.__const` | `0x59fc` | `0x5afc` | **`+0x100`** |
| `__TEXT.__swift5_capture` | `0x2414` | `0x24c8` | **`+0xb4`** |
| `__AUTH.__data` | `0x560` | `0x5f8` | **`+0x98`** |
| `__AUTH_CONST.__objc_const` | `0x3078` | `0x3108` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x32a0` | `0x3330` | **`+0x90`** |
| `__TEXT.__cstring` | `0x1e55` | `0x1ed5` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x1ec4` | `0x1f1c` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0x2886` | `0x28dc` | **`+0x56`** |
| `__DATA.__data` | `0xcb0` | `0xd00` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x2728` | `0x2770` | **`+0x48`** |
| `__TEXT.__swift5_reflstr` | `0xfbd` | `0xfed` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x1450` | `0x147c` | **`+0x2c`** |
| `__DATA.__common` | `0xb8` | `0xd8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x6a8` | `0x6c0` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x698` | `0x6b0` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x2fe0` | `0x2ff0` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x314` | `0x324` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x2f8` | `0x304` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x21c` | `0x228` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x330` | `0x33c` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x1c8` | `0x1d0` | **`+0x8`** |

### Other Changes

```diff

-279.0.15.0.0
+284.0.7.0.0

+  - /System/Library/PrivateFrameworks/MobileInstallation.framework/MobileInstallation

-  Functions: 4941
-  Symbols:   280
-  CStrings:  643
+  Functions: 5048
+  Symbols:   283
+  CStrings:  650
Symbols:
+ _MobileInstallationGetSystemAppMigrationStatus
+ _NSStringFromAFSiriUnavailabilityReasons
+ _OBJC_CLASS_$_GMAvailabilityWrapper
CStrings:
+ "AssetsArePresent"
+ "Did set enhancedSiriUnifiedReasons: %{public}s"
+ "Enhanced Siri computed state: available=%{bool,public}d, codes=%{public}s, missingDesiredCapabilities=%{public}s, unavailabilityReasons=%{public}s, unifiedReasons=%{public}s"
+ "Enhanced Siri update applied: available=%{bool,public}d, reasons=%{public}s, bootUUID=%{public}s, didChange[availability=%{bool,public}d, reasons=%{bool,public}d, unifiedReasons=%{bool,public}d, bootUUID=%{bool,public}d]"
+ "EnhancedSiriVisibility: %{public}s, skipping Campo installation for sensitive region"
+ "EnhancedSiriVisibility: refusing Campo install (%{public}s) — isUseCaseAccessNotGrantedSecure returned true for %{public}s"
+ "EnterpriseAllowed"
+ "Failed to encode enhancedSiriUnifiedReasons: %{public}@"
+ "GenerativeAppsVisibility: could not read system app migration status; treating as incomplete."
+ "GenerativeAppsVisibility: deferring install of %{public}s; system app migration is not complete."
+ "GenerativeAppsVisibility: system app migration complete = %{bool,public}d"
+ "UseCaseNotDisabled"
+ "com.apple.GenerativeFunctions.PeriodicTasks.SystemAppInstall.PostBuddy"
+ "forceWaitlistStatus: oldValue=%{public}s newValue=%{public}s notificationFired=%{bool,public}d"
- "Enhanced Siri computed state: available=%{bool,public}d, reasons=%{public}s"
- "Enhanced Siri update applied: available=%{bool,public}d, reasons=%{public}s, bootUUID=%{public}s, didChange[availability=%{bool,public}d, reasons=%{bool,public}d, bootUUID=%{bool,public}d]"
- "VisualGeneration.GenerativePlayground"
- "isUseCaseAccessNotGrantedSecure: failing closed; %{public}s is strict-asset-availability and not yet initialized by CSF"
- "isUseCaseAccessNotGrantedSecure: input=%{public}s, initializedUseCases=%{public}s"
- "isUseCaseAccessNotGrantedSecure: returning %{bool,public}d; forcedWaitlistStatus=%{public}s"
- "isUseCaseAccessNotGrantedSecure: returning granted; secure unifiedReasons is nil"
```
