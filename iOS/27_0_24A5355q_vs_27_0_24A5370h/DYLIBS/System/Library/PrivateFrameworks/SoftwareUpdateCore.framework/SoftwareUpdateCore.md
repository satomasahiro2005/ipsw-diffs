## SoftwareUpdateCore

> `/System/Library/PrivateFrameworks/SoftwareUpdateCore.framework/SoftwareUpdateCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xae190` | `0xaed2c` | **`+0xb9c`** |
| `__AUTH_CONST.__cfstring` | `0x13460` | `0x13760` | **`+0x300`** |
| `__TEXT.__cstring` | `0x15f3d` | `0x1618d` | **`+0x250`** |
| `__DATA_CONST.__const` | `0x2628` | `0x26b8` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0xbab8` | `0xbb28` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x8384` | `0x83e4` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0xcf53` | `0xcef3` | **`-0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x4a10` | `0x4a30` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1928` | `0x1910` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0x6e0` | `0x6f0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xae8` | `0xaf8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xaa8` | `0xab0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1f8` | `0x200` | **`+0x8`** |

### Other Changes

```diff

-2717.0.0.0.0
+2718.0.2.0.0

-  Functions: 3278
-  Symbols:   5698
-  CStrings:  3274
+  Functions: 3285
+  Symbols:   5733
+  CStrings:  3298
Symbols:
+ +[SUCoreScanPSUSDetermine isPreSUStagingEnabledForUpdate:policy:error:]
+ -[SUCoreBiomeEventPayloadBase .cxx_destruct]
+ -[SUCoreBiomeEventPayloadBase addInfo:forKey:]
+ -[SUCoreBiomeEventPayloadBase additionalInfo]
+ -[SUCoreBiomeEventPayloadBase init]
+ -[SUCoreBiomeEventPayloadPSUSState addError:]
+ -[SUCoreScanPSUSDetermine _isPrecisePreSUStagingEnabledForUpdate:policy:error:]
+ -[SUCoreScanPSUSDetermine _reportPSUSDetermineFinishedEvent:duration:noPrecisePSUSError:]
+ -[SUCoreScanPSUSDetermine noPrecisePSUSError]
+ -[SUCoreScanPSUSDetermine setNoPrecisePSUSError:]
+ -[SUCoreUpdateDownloader _isPreSUStagingEnabledForOptionalAssets:]
+ -[SUCoreUpdateDownloader _isPreSUStagingEnabled]
+ -[SUCoreUpdateDownloader _reportPSUSFinishedEvent:byGroupTotalStagedBytes:byGroupAssetsSuccessfullyStaged:]
+ _$s26AppleIntelligenceReporting0aB7UseCaseV03useE10Identifier10parametersACSS_SDyS2SGtcfC
+ _$sSD10FoundationE36_unconditionallyBridgeFromObjectiveCySDyxq_GSo12NSDictionaryCSgFZ
+ _$sSSN
+ _$sSSSHsWP
+ _OBJC_IVAR_$_SUCoreBiomeEventPayloadBase._additionalInfo
+ _OBJC_IVAR_$_SUCoreScanPSUSDetermine._noPrecisePSUSError
+ __OBJC_$_INSTANCE_METHODS_SUCoreBiomeEventPayloadBase
+ __OBJC_$_INSTANCE_VARIABLES_SUCoreBiomeEventPayloadBase
+ __OBJC_$_PROP_LIST_SUCoreBiomeEventPayloadBase
+ ___107-[SUCoreUpdateDownloader _reportPSUSFinishedEvent:byGroupTotalStagedBytes:byGroupAssetsSuccessfullyStaged:]_block_invoke
+ ___89-[SUCoreScanPSUSDetermine _reportPSUSDetermineFinishedEvent:duration:noPrecisePSUSError:]_block_invoke
+ ___block_descriptor_48_e8_32s40s_e34_v24?0"NSDictionary"8"NSError"16ls32l8s40l8
+ _kSUCoreBiomeKeyNoPrecisePreSUStagingReason
+ _kSUCoreBiomeKeyPreSUStagingEnabledForOptionalPolicy
+ _kSUCoreBiomeKeyPreSUStagingEnabledForOptionalServer
+ _kSUCoreBiomeKeyPreSUStagingEnabledPolicy
+ _kSUCoreBiomeKeyPreSUStagingEnabledServer
+ _kSUCoreBiomeKeyPreSUStagingMaxAllowedSize
+ _kSUCoreBiomeKeyPreSUStagingMaxAllowedSpaceForOptional
+ _kSUCoreBiomeKeyPreSUStagingMinFreeSpacePostStageOptional
+ _kSUCoreBiomeKeyPreSUStagingOptionalDeterminedBytes
+ _kSUCoreBiomeKeyPreSUStagingOptionalDeterminedCount
+ _kSUCoreBiomeKeyPreSUStagingOptionalStagedBytes
+ _kSUCoreBiomeKeyPreSUStagingOptionalStagedCount
+ _kSUCoreBiomeKeyPreSUStagingRequiredDeterminedBytes
+ _kSUCoreBiomeKeyPreSUStagingRequiredDeterminedCount
+ _kSUCoreBiomeKeyPreSUStagingRequiredStagedBytes
+ _kSUCoreBiomeKeyPreSUStagingRequiredStagedCount
+ _kSUCoreBiomeKeyTargetBuildVersion
+ _kSUCoreBiomeKeyUUID
+ _kSUCoreControllerNoPrecisePreSUStagingReason
+ _kSUDefaultPSUSMaxSize
- +[SUCoreScanPSUSDetermine isPreSUStagingEnabledForUpdate:policy:reason:]
- -[SUCoreBiomeEventPayloadPSUSState setErrors:]
- -[SUCoreScanPSUSDetermine _reportPSUSDetermineFinishedEvent:duration:]
- -[SUCoreUpdateDownloader _isPreSUStagingEnabled:]
- -[SUCoreUpdateDownloader _reportPSUSFinishedEvent:]
- -[SUCoreUpdateDownloader _shouldStageOptionalPSUSAssets:]
- ___51-[SUCoreUpdateDownloader _reportPSUSFinishedEvent:]_block_invoke
- ___70-[SUCoreScanPSUSDetermine _reportPSUSDetermineFinishedEvent:duration:]_block_invoke
- ___NSArray0__struct
- ___block_descriptor_49_e8_32s40bs_e5_v8?0ls32l8s40l8
CStrings:
+ "%@:%ld"
+ "%llu"
+ "-[SUCoreScanPSUSDetermine _isPrecisePreSUStagingEnabledForUpdate:policy:error:]"
+ "EnabledByPolicy"
+ "EnabledByServer"
+ "MaxAllowedSize"
+ "MaxAllowedSpaceForOptional"
+ "MinFreeSpacePostStageOptional"
+ "NoPreciseReason"
+ "OptionalDeterminedBytes"
+ "OptionalDeterminedCount"
+ "OptionalEnabledByPolicy"
+ "OptionalEnabledByServer"
+ "OptionalStagedBytes"
+ "OptionalStagedCount"
+ "RequiredDeterminedBytes"
+ "RequiredDeterminedCount"
+ "RequiredStagedBytes"
+ "RequiredStagedCount"
+ "[PSUS-Determine] %s: PrecisePSUS is disabled by policy"
+ "[PSUS-Determine] %s: PrecisePSUS is enabled for testing"
+ "[PreSUStaging] %{public}@: %{public}@"
+ "[PreSUStaging] No need to remove PSUS assets (disabled)"
+ "[PreSUStaging] No optional assets to download"
+ "[PreSUStaging] disabled; skip downloading assets"
+ "[SCAN] PrecisePSUS"
+ "failed to create query"
+ "no config asset found"
+ "no platform asset path"
+ "no psus result"
+ "req=%llu,opt=%llu,max=%llu(default=%llu)"
+ "unexpected no psus result"
+ "|enablePrecisePSUS"
- "[PSUS-Determine] %s: enable precise PSUS (enabled by policy)"
- "[PSUS-Determine] %s: enable precise PSUS (enabled by testing control)"
- "[PSUS-Determine] %s: will not use precise PSUS (disabled)"
- "[PSUS-Determine] %{public}@ (not-performing reason: %{public}@)"
- "[PreSUStaging] No need to remove PSUS assets (%@)"
- "[PreSUStaging] disabled (%@); skip downloading assets"
- "no optional assets to stage"
- "required=%llu, optional=%llu, max=%llu"
- "|enablePPSUS"
```
