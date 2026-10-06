## ManagedConfiguration

> `/System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf61fc` | `0xf7134` | **`+0xf38`** |
| `__TEXT.__oslogstring` | `0x94c9` | `0x9798` | **`+0x2cf`** |
| `__AUTH_CONST.__objc_const` | `0xd770` | `0xd808` | **`+0x98`** |
| `__TEXT.__objc_methlist` | `0xb2b4` | `0xb33c` | **`+0x88`** |
| `__AUTH_CONST.__const` | `0x20b0` | `0x2130` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x5db0` | `0x5e18` | **`+0x68`** |
| `__AUTH.__objc_data` | `0x23a0` | `0x23f0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x3250` | `0x3288` | **`+0x38`** |
| `__DATA.__bss` | `0xc59` | `0xc89` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x4e18` | `0x4e40` | **`+0x28`** |
| `__TEXT.__cstring` | `0x186d0` | `0x186ab` | **`-0x25`** |
| `__TEXT.__gcc_except_tab` | `0x1020` | `0x1040` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xab0` | `0xac0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x3d0` | `0x3d8` | **`+0x8`** |

### Other Changes

```diff

-2483.0.5.0.0
+2483.2.6.0.0

-  Functions: 5797
-  Symbols:   9690
-  CStrings:  4611
+  Functions: 5817
+  Symbols:   9720
+  CStrings:  4621
Symbols:
+ +[MCAppManagedFeaturesBackupExclusions appIDsAtPath:]
+ +[MCAppManagedFeaturesBackupExclusions appIDs]
+ +[MCAppManagedFeaturesBackupExclusions removeAtPath:error:]
+ +[MCAppManagedFeaturesBackupExclusions removeWithError:]
+ +[MCAppManagedFeaturesBackupExclusions setAppIDs:atPath:error:]
+ +[MCAppManagedFeaturesBackupExclusions setAppIDs:error:]
+ +[MCRestrictionUtilities boolFeatureForPayloadRestrictionKey:]
+ +[MCRestrictionUtilities boolFeaturesWithPayloadRestictionKeyAlias]
+ +[MCRestrictionUtilities boolPayloadRestrictionKeysForFeature:]
+ -[MCProfileConnection(Misc) areAppRatingExceptionsAllowedForScreenTime]
+ GCC_except_table373
+ _MCAppManagedFeaturesDoNotBackupAppIDsFilePath
+ _MCAppManagedFeaturesDoNotBackupAppIDsFilePath.once
+ _MCAppManagedFeaturesDoNotBackupAppIDsFilePath.str
+ _MCFeatureSpringBoardShouldConsiderAppAllowlistAsTransient
+ _OBJC_CLASS_$_MCAppManagedFeaturesBackupExclusions
+ _OBJC_CLASS_$_NSMutableOrderedSet
+ _OBJC_METACLASS_$_MCAppManagedFeaturesBackupExclusions
+ __OBJC_$_CLASS_METHODS_MCAppManagedFeaturesBackupExclusions
+ __OBJC_CLASS_RO_$_MCAppManagedFeaturesBackupExclusions
+ __OBJC_METACLASS_RO_$_MCAppManagedFeaturesBackupExclusions
+ ___71-[MCProfileConnection(Misc) areAppRatingExceptionsAllowedForScreenTime]_block_invoke
+ ___MCAppManagedFeaturesDoNotBackupAppIDsFilePath_block_invoke
+ ____boolAliasToFeatures_block_invoke
+ ____boolFeaturesToAlias_block_invoke
+ ___block_descriptor_40_e8_32r_e30_v24?0"NSNumber"8"NSError"16lr32l8
+ __boolAliasToFeatures.dict
+ __boolAliasToFeatures.onceToken
+ __boolFeaturesToAlias
+ __boolFeaturesToAlias.dict
+ __boolFeaturesToAlias.onceToken
+ _kMCAllowSiriAIKey
- _kSoftwareUpdatePath
- _kSoftwareUpdatePathKey
CStrings:
+ "AppManagedFeatures backup-exclusions file has a non-string entry, ignoring file"
+ "AppManagedFeatures backup-exclusions file has unexpected %{public}@ type: %{public}@"
+ "AppManagedFeatures/DoNotBackupAppIDs.plist"
+ "Cannot read AppManagedFeatures backup-exclusions: no file path"
+ "Cannot remove AppManagedFeatures backup-exclusions: no file path"
+ "Cannot write AppManagedFeatures backup-exclusions: no file path"
+ "FEATURE_SIRI_AI"
+ "Failed to check if apps rating are locked down only by Screen Time. Error: %{public}@"
+ "Failed to create AppManagedFeatures backup-exclusions directory: %{public}@"
+ "Failed to remove AppManagedFeatures backup-exclusions: %{public}@"
+ "Failed to serialize AppManagedFeatures backup-exclusions: %{public}@"
+ "Failed to write AppManagedFeatures backup-exclusions: %{public}@"
+ "PreventBackupAppIDs"
+ "SpringBoardShouldConsiderAppAllowlistAsTransient"
+ "allowSiriAI"
+ "com.apple.NanoRemote"
+ "com.apple.Remote"
- "FEATURE_DELAYED_SOFTWARE_UPDATES"
- "FEATURE_RAPID_SECURITY_RESPONSE_INSTALLATION"
- "FEATURE_RAPID_SECURITY_RESPONSE_REMOVAL"
- "FEATURE_SOFTWARE_UPDATE_DELAY"
- "RecommendationCadence"
- "SoftwareUpdateSettings"
- "com.apple.TVRemoteApp"
```
