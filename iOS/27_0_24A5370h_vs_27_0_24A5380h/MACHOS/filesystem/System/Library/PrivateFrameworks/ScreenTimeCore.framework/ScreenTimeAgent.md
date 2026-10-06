## ScreenTimeAgent

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14ec70` | `0x150aa4` | **`+0x1e34`** |
| `__TEXT.__oslogstring` | `0x162a0` | `0x16660` | **`+0x3c0`** |
| `__TEXT.__objc_methname` | `0x1e9b1` | `0x1eba1` | **`+0x1f0`** |
| `__TEXT.__objc_stubs` | `0x134c0` | `0x13680` | **`+0x1c0`** |
| `__DATA_CONST.__got` | `0x14f0` | `0x15f8` | **`+0x108`** |
| `__DATA_CONST.__const` | `0xb7f0` | `0xb8e8` | **`+0xf8`** |
| `__TEXT.__constg_swiftt` | `0x3bb4` | `0x3c94` | **`+0xe0`** |
| `__TEXT.__swift5_typeref` | `0x3386` | `0x3460` | **`+0xda`** |
| `__TEXT.__const` | `0x5f30` | `0x5fe0` | **`+0xb0`** |
| `__DATA.__data` | `0x81e0` | `0x8250` | **`+0x70`** |
| `__DATA.__objc_selrefs` | `0x59d8` | `0x5a48` | **`+0x70`** |
| `__TEXT.__cstring` | `0xb2ae` | `0xb2ee` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x4c58` | `0x4c90` | **`+0x38`** |
| `__TEXT.__objc_methtype` | `0x60d2` | `0x6102` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xa6d4` | `0xa6fc` | **`+0x28`** |
| `__TEXT.__swift5_assocty` | `0x318` | `0x338` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x1b9c` | `0x1bbc` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1eec` | `0x1f00` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0x2bd0` | `0x2be0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x27a8` | `0x27b8` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x2689` | `0x2699` | **`+0x10`** |
| `__DATA.__objc_data` | `0x52e8` | `0x52f0` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x15f8` | `0x1600` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x6950` | `0x6958` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x308` | `0x310` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0xd8` | `0xe0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-640.0.100.0.0
+645.1.100.0.0

+  - /System/Library/PrivateFrameworks/DeviceRecovery.framework/DeviceRecovery

-  Functions: 6764
-  Symbols:   1546
-  CStrings:  7602
+  Functions: 6794
+  Symbols:   1549
+  CStrings:  7629
Symbols:
+ _$s15ScreenTimeSwift0aB16SettingsMigratorV21persistenceControllerACSo013STPersistenceG8Protocol_p_tcfC
+ _DREIsRunningInDeviceRecoveryEnvironment
+ _MOWebContentOverridePolicyUnverifiedAdultLegacyScreenTime
+ _OBJC_CLASS_$_STRegulatoryIntelligenceSiriPolicy
+ _STUserDefaultsKeyUpgradeEligibilityCheckIntervalSeconds
+ _swift_unknownObjectRetain_n
- _$s15ScreenTimeSwift0aB16SettingsMigratorV7contextACSo22NSManagedObjectContextC_tcfC
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "@\"STRegulatoryIntelligenceSiriPolicy\"8@?0"
+ "@64@0:8@16@24@32@40@48^@56"
+ "Applying Web Content Filter: isForced=%{bool,public}d, shieldVariant=%{public}ld"
+ "Applying realistic image generation: allowed=%{bool,public}d"
+ "Applying sensitive topics: allowed=%{bool,public}d"
+ "Failed to fetch Realistic Image Generation restriction: %{public}@. Applying Don't Allow as a fallback."
+ "Failed to fetch Sensitive Topics restriction: %{public}@. Applying Reduce as a fallback."
+ "Failed to fetch Siri AI restriction: %{public}@. Applying Don't Allow as a fallback."
+ "IntelligenceStore"
+ "Not applying Siri AI restriction due to user being migrated"
+ "Not applying realistic image generation restriction due to user being migrated"
+ "Not applying sensitive topics restriction due to user being migrated"
+ "Setting Web Content overridePolicy to unverifiedAdultLegacyScreenTime"
+ "Skipping Siri AI application (APPLE_FEATURE_LINWOOD not enabled): allowed=%{bool,public}d"
+ "Using internal eligibility check interval override: %{public}fs (subject to the scheduler's minimum)"
+ "_requestFromBlueprints:forUser:regulatoryPolicy:persistenceController:migrationProvider:error:"
+ "_transactionCountByRequest:forStore:inManagedObjectContext:error:"
+ "applyRealisticImageGenerationAllowed:"
+ "applySensitiveTopicsAllowed:"
+ "applySiriAIAllowed:"
+ "doubleForKey:"
+ "fetchRestrictionsForUserDSID:persistenceController:organizationSettingsRestrictionUtility:completionHandler:"
+ "initWithPersistenceController:restrictionPayloadUtility:regulatoryIntelligenceSiriPolicyProvider:"
+ "intelligence"
+ "intelligenceSiri"
+ "isRealisticImageGenerationAllowedForUserDSID:error:"
+ "isSensitiveTopicsAllowedForUserDSID:error:"
+ "isSiriAIAllowedForUserDSID:error:"
+ "performShadowMigrationWithPersistenceController:error:"
+ "resetWithPersistenceController:"
+ "restrictionsForUserDSID:persistenceController:regulatoryPolicyProvider:completionHandler:"
+ "setDenyPhotorealisticImageGeneration:"
+ "setForceSiriReduceSensitiveContent:"
+ "setOverridePolicy:"
+ "shieldVariant"
+ "siri"
- "@56@0:8@16@24@32@40^@48"
- "Applying Web Content Filter: isForced=%{bool,public}d"
- "_requestFromBlueprints:forUser:regulatoryPolicy:migrationProvider:error:"
- "_transactionsFoundByRequest:forStore:inManagedObjectContext:error:"
- "fetchRestrictionsForUserDSID:persistenceController:completionHandler:"
- "initWithPersistenceController:restrictionPayloadUtility:"
- "performShadowMigrationWithContext:error:"
- "resetWithContext:"
- "restrictionsForUserDSID:persistenceController:completionHandler:"
```
