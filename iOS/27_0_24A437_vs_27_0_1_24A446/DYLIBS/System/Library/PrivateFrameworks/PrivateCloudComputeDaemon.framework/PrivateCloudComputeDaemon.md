## PrivateCloudComputeDaemon

> `/System/Library/PrivateFrameworks/PrivateCloudComputeDaemon.framework/PrivateCloudComputeDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c1028` | `0x2c2810` | **`+0x17e8`** |
| `__TEXT.__eh_frame` | `0x13004` | `0x1311c` | **`+0x118`** |
| `__TEXT.__cstring` | `0x6911` | `0x69c1` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x80f9` | `0x81a9` | **`+0xb0`** |
| `__TEXT.__swift5_reflstr` | `0x6978` | `0x6a21` | **`+0xa9`** |
| `__AUTH_CONST.__const` | `0xac30` | `0xaca0` | **`+0x70`** |
| `__TEXT.__const` | `0x171b8` | `0x17228` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x80d8` | `0x8140` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0x3f08` | `0x3f68` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x5c24` | `0x5c78` | **`+0x54`** |
| `__TEXT.__swift5_typeref` | `0x6ca4` | `0x6cf6` | **`+0x52`** |
| `__TEXT.__swift5_fieldmd` | `0x6010` | `0x605c` | **`+0x4c`** |
| `__DATA.__data` | `0x28b8` | `0x28f0` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x12e8` | `0x1314` | **`+0x2c`** |
| `__DATA.__common` | `0xa0` | `0xc0` | **`+0x20`** |
| `__DATA_DIRTY.__common` | `0x258` | `0x240` | **`-0x18`** |
| `__TEXT.__swift_as_cont` | `0xce0` | `0xcf4` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x5e4` | `0x5f0` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x6b4` | `0x6c0` | **`+0xc`** |
| `__DATA_DIRTY.__objc_data` | `0x7a0` | `0x7a8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xe80` | `0xe84` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0xb4` | `0xb8` | **`+0x4`** |

### Other Changes

```diff

-2570.2.1.0.0
+2570.2.2.0.0

-  Functions: 9939
-  Symbols:   2602
-  CStrings:  1237
+  Functions: 9961
+  Symbols:   2601
+  CStrings:  1243
Symbols:
+ ___swift_closure_destructor.98Tm
+ _symbolic $s25PrivateCloudComputeDaemon30VaultConfigurationUpdaterStoreP
+ _symbolic SDy__________y_________________________y__________G______________________________yAchlMGAH__________GG 25PrivateCloudComputeDaemon16TC2ResolvedSetupV AA21TrustedRequestFactoryC 0abC020DefaultConfigurationV AA17NWAsyncConnectionV AA22LegacyAttestationStoreC AA08DeferredpQ0C AA0P8VerifierV AF18FeatureFlagCheckerV 0bP012MuxValidatorV AA0R11RateLimiterC AA012ServerDrivenL0C AA10SystemInfoV AA13OSEligibilityV AA11DeviceStateV AA013TokenProviderJ0V AA011PreferencesQ0C s15ContinuousClockV
+ _symbolic _____ySDy__________y_________________________y__________G______________________________yAdimNGAI__________GGG 15Synchronization5MutexVAARi_zrlE 25PrivateCloudComputeDaemon16TC2ResolvedSetupV AD21TrustedRequestFactoryC 0cdE020DefaultConfigurationV AD17NWAsyncConnectionV AD22LegacyAttestationStoreC AD08DeferredrS0C AD0R8VerifierV AI18FeatureFlagCheckerV 0dR012MuxValidatorV AD0T11RateLimiterC AD012ServerDrivenN0C AD10SystemInfoV AD13OSEligibilityV AD11DeviceStateV AD013TokenProviderL0V AD011PreferencesS0C s15ContinuousClockV
+ _symbolic _____y______________________________G 25PrivateCloudComputeDaemon25VaultConfigurationUpdaterC AA19DeferredRateLimiterC AA011DeviceQuotaF14FetcherWrapperC 0abC007DefaultF0V AH18FeatureFlagCheckerV AA21NotificationsProducerV AA16PreferencesStoreC
+ _symbolic _____y_________________________y__________G______________________________yAbgkLGAG__________G 25PrivateCloudComputeDaemon21TrustedRequestFactoryC 0abC020DefaultConfigurationV AA17NWAsyncConnectionV AA22LegacyAttestationStoreC AA08DeferredmN0C AA0M8VerifierV AD18FeatureFlagCheckerV 0bM012MuxValidatorV AA0O11RateLimiterC AA012ServerDrivenI0C AA10SystemInfoV AA13OSEligibilityV AA11DeviceStateV AA013TokenProviderG0V AA011PreferencesN0C s15ContinuousClockV
+ _symbolic _____y__________y_________________________y__________G______________________________yAdimNGAI__________GG s18_DictionaryStorageC 25PrivateCloudComputeDaemon16TC2ResolvedSetupV AC21TrustedRequestFactoryC 0cdE020DefaultConfigurationV AC17NWAsyncConnectionV AC22LegacyAttestationStoreC AC08DeferredrS0C AC0R8VerifierV AH18FeatureFlagCheckerV 0dR012MuxValidatorV AC0T11RateLimiterC AC012ServerDrivenN0C AC10SystemInfoV AC13OSEligibilityV AC11DeviceStateV AC013TokenProviderL0V AC011PreferencesS0C s15ContinuousClockV
+ _symbolic _____y_____y______________________________GG 25PrivateCloudComputeDaemon20NotificationsMonitorC AA25VaultConfigurationUpdaterC AA19DeferredRateLimiterC AA011DeviceQuotaH14FetcherWrapperC 0abC007DefaultH0V AJ18FeatureFlagCheckerV AA0E8ProducerV AA16PreferencesStoreC
+ _symbolic _____y_____y______________________________GG 25PrivateCloudComputeDaemon34UpdateVaultConfigScheduledActivityC AA0F20ConfigurationUpdaterC AA19DeferredRateLimiterC AA011DeviceQuotaJ14FetcherWrapperC 0abC007DefaultJ0V AJ18FeatureFlagCheckerV AA21NotificationsProducerV AA16PreferencesStoreC
+ _symbolic _____yxq_q0_q1_q2_q3_G 25PrivateCloudComputeDaemon25VaultConfigurationUpdaterC
- ___swift_closure_destructor.35Tm
- ___swift_closure_destructor.89Tm
- _symbolic 8Duration_____Qy10_ s5ClockP
- _symbolic SDy__________y_________________________y__________G______________________________yAchlMGAH_____GG 25PrivateCloudComputeDaemon16TC2ResolvedSetupV AA21TrustedRequestFactoryC 0abC020DefaultConfigurationV AA17NWAsyncConnectionV AA22LegacyAttestationStoreC AA08DeferredpQ0C AA0P8VerifierV AF18FeatureFlagCheckerV 0bP012MuxValidatorV AA0R11RateLimiterC AA012ServerDrivenL0C AA10SystemInfoV AA13OSEligibilityV AA11DeviceStateV AA013TokenProviderJ0V s15ContinuousClockV
- _symbolic _____ySDy__________y_________________________y__________G______________________________yAdimNGAI_____GGG 15Synchronization5MutexVAARi_zrlE 25PrivateCloudComputeDaemon16TC2ResolvedSetupV AD21TrustedRequestFactoryC 0cdE020DefaultConfigurationV AD17NWAsyncConnectionV AD22LegacyAttestationStoreC AD08DeferredrS0C AD0R8VerifierV AI18FeatureFlagCheckerV 0dR012MuxValidatorV AD0T11RateLimiterC AD012ServerDrivenN0C AD10SystemInfoV AD13OSEligibilityV AD11DeviceStateV AD013TokenProviderL0V s15ContinuousClockV
- _symbolic _____y_________________________G 25PrivateCloudComputeDaemon25VaultConfigurationUpdaterC AA19DeferredRateLimiterC AA011DeviceQuotaF14FetcherWrapperC 0abC007DefaultF0V AH18FeatureFlagCheckerV AA21NotificationsProducerV
- _symbolic _____y_________________________y__________G______________________________yAbgkLGAG_____G 25PrivateCloudComputeDaemon21TrustedRequestFactoryC 0abC020DefaultConfigurationV AA17NWAsyncConnectionV AA22LegacyAttestationStoreC AA08DeferredmN0C AA0M8VerifierV AD18FeatureFlagCheckerV 0bM012MuxValidatorV AA0O11RateLimiterC AA012ServerDrivenI0C AA10SystemInfoV AA13OSEligibilityV AA11DeviceStateV AA013TokenProviderG0V s15ContinuousClockV
- _symbolic _____y__________y_________________________y__________G______________________________yAdimNGAI_____GG s18_DictionaryStorageC 25PrivateCloudComputeDaemon16TC2ResolvedSetupV AC21TrustedRequestFactoryC 0cdE020DefaultConfigurationV AC17NWAsyncConnectionV AC22LegacyAttestationStoreC AC08DeferredrS0C AC0R8VerifierV AH18FeatureFlagCheckerV 0dR012MuxValidatorV AC0T11RateLimiterC AC012ServerDrivenN0C AC10SystemInfoV AC13OSEligibilityV AC11DeviceStateV AC013TokenProviderL0V s15ContinuousClockV
- _symbolic _____y_____y_________________________GG 25PrivateCloudComputeDaemon20NotificationsMonitorC AA25VaultConfigurationUpdaterC AA19DeferredRateLimiterC AA011DeviceQuotaH14FetcherWrapperC 0abC007DefaultH0V AJ18FeatureFlagCheckerV AA0E8ProducerV
- _symbolic _____y_____y_________________________GG 25PrivateCloudComputeDaemon34UpdateVaultConfigScheduledActivityC AA0F20ConfigurationUpdaterC AA19DeferredRateLimiterC AA011DeviceQuotaJ14FetcherWrapperC 0abC007DefaultJ0V AJ18FeatureFlagCheckerV AA21NotificationsProducerV
- _symbolic _____yxq_q0_q1_q2_G 25PrivateCloudComputeDaemon25VaultConfigurationUpdaterC
CStrings:
+ "\n    isVaultConfigurationOutdated: "
+ "%s VAULT configuration (rate limits) is outdated, scheduling a fetch"
+ "fetchVaultConfigurationIfAllowed"
+ "handleFetchVaultConfigurationIfAllowed()"
+ "lastVaultConfigurationFetchTime"
+ "received a request to fetch VAULT configuration (rate limits) but it is too soon"
```
