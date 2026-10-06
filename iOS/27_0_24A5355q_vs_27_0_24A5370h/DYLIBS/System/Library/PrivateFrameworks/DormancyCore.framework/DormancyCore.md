## DormancyCore

> `/System/Library/PrivateFrameworks/DormancyCore.framework/DormancyCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x277bc` | `0x2a70c` | **`+0x2f50`** |
| `__DATA.__bss` | `0x5a00` | `0x6700` | **`+0xd00`** |
| `__TEXT.__const` | `0x352c` | `0x3c1c` | **`+0x6f0`** |
| `__AUTH_CONST.__const` | `0x20b8` | `0x2570` | **`+0x4b8`** |
| `__TEXT.__swift5_fieldmd` | `0xae4` | `0xc10` | **`+0x12c`** |
| `__TEXT.__swift5_typeref` | `0xcdf` | `0xdef` | **`+0x110`** |
| `__TEXT.__cstring` | `0x6c2` | `0x7c2` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0xad8` | `0xbd0` | **`+0xf8`** |
| `__TEXT.__eh_frame` | `0xaa0` | `0xb78` | **`+0xd8`** |
| `__TEXT.__constg_swiftt` | `0xc58` | `0xd28` | **`+0xd0`** |
| `__TEXT.__swift5_reflstr` | `0x4fa` | `0x5c1` | **`+0xc7`** |
| `__DATA.__data` | `0x890` | `0x950` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0xa3d` | `0xaed` | **`+0xb0`** |
| `__TEXT.__swift5_assocty` | `0xd8` | `0x168` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x870` | `0x8f0` | **`+0x80`** |
| `__TEXT.__swift5_proto` | `0x2fc` | `0x364` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x108` | `0x168` | **`+0x60`** |
| `__AUTH.__data` | `0x690` | `0x6b8` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x190` | `0x1b8` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0xf4` | `0x10c` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x818` | `0x820` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xdc` | `0xe4` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x8` | `0xc` | **`+0x4`** |

### Other Changes

```diff

-27.0.43.0.0
+27.0.50.0.0

+  - /System/Library/PrivateFrameworks/BiomeLibrary.framework/BiomeLibrary

+  - /System/Library/PrivateFrameworks/PowerLog.framework/PowerLog

-  Functions: 1065
-  Symbols:   545
-  CStrings:  101
+  Functions: 1183
+  Symbols:   581
+  CStrings:  114
Symbols:
+ -[DRPSDomainAccessorBridge synchronizeNanoDomainForKey:]
+ _BiomeLibrary
+ _DRBatteryUIIsEligibleForOptimizeBatteryPrompt
+ _OBJC_CLASS_$_BMDormancyRemoteUserInteraction
+ _OBJC_CLASS_$_BMDormancyUserInteraction
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_NSSet
+ _OBJC_IVAR_$_DRPSDomainAccessorBridge._npsManager
+ ___swift_memcpy144_8
+ ___swift_memcpy240_8
+ ___swift_memcpy48_8
+ _associated conformance 12DormancyCore0A7MonitorC14CandidateStateO10CodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOSHAASQ
+ _associated conformance 12DormancyCore0A7MonitorC14CandidateStateO10CodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 12DormancyCore0A7MonitorC14CandidateStateO10CodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12DormancyCore0A7MonitorC14CandidateStateO14IdleCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 12DormancyCore0A7MonitorC14CandidateStateO14IdleCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12DormancyCore0A7MonitorC14CandidateStateO27ProposedAutomaticCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 12DormancyCore0A7MonitorC14CandidateStateO27ProposedAutomaticCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12DormancyCore0A7MonitorC14CandidateStateOSHAASQ
+ _associated conformance 12DormancyCore0A7MonitorC14InactiveReasonO18InformedCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0G3KeyAAs23CustomStringConvertible
+ _associated conformance 12DormancyCore0A7MonitorC14InactiveReasonO18InformedCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0G3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12DormancyCore15StatusCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLOSHAASQ
+ _associated conformance 12DormancyCore15StatusCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLOs0dE0AAs23CustomStringConvertible
+ _associated conformance 12DormancyCore15StatusCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLOs0dE0AAs28CustomDebugStringConvertible
+ _associated conformance 12DormancyCore17ExcludedCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLOSHAASQ
+ _associated conformance 12DormancyCore17ExcludedCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLOs0dE0AAs23CustomStringConvertible
+ _associated conformance 12DormancyCore17ExcludedCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLOs0dE0AAs28CustomDebugStringConvertible
+ _associated conformance 12DormancyCore17FeatureDefinitionV7ConsentOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 12DormancyCore17InactiveCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLOSHAASQ
+ _associated conformance 12DormancyCore17InactiveCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLOs0dE0AAs23CustomStringConvertible
+ _associated conformance 12DormancyCore17InactiveCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLOs0dE0AAs28CustomDebugStringConvertible
+ _associated conformance 12DormancyCore18CandidateCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLOSHAASQ
+ _associated conformance 12DormancyCore18CandidateCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLOs0dE0AAs23CustomStringConvertible
+ _associated conformance 12DormancyCore18CandidateCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLOs0dE0AAs28CustomDebugStringConvertible
+ _associated conformance 12DormancyCore18InteractionEventIDOSHAASQ
+ _associated conformance 12DormancyCore26BiomeUserInteractionStreamOSHAASQ
+ _batteryUIIsEligibleForOptimizeBatteryPrompt
+ _objc_retainAutorelease
+ _swift_retain_x27
+ _symbolic $ss12CaseIterableP
+ _symbolic Say_____G 12DormancyCore17FeatureDefinitionV7ConsentO
+ _symbolic _____ 12DormancyCore0A7MonitorC14CandidateStateO
+ _symbolic _____ 12DormancyCore0A7MonitorC14CandidateStateO10CodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
+ _symbolic _____ 12DormancyCore0A7MonitorC14CandidateStateO14IdleCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
+ _symbolic _____ 12DormancyCore0A7MonitorC14CandidateStateO27ProposedAutomaticCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
+ _symbolic _____ 12DormancyCore0A7MonitorC14InactiveReasonO18InformedCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
+ _symbolic _____ 12DormancyCore15StatusCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLO
+ _symbolic _____ 12DormancyCore17ExcludedCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLO
+ _symbolic _____ 12DormancyCore17InactiveCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLO
+ _symbolic _____ 12DormancyCore18CandidateCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLO
+ _symbolic _____ 12DormancyCore18InteractionEventIDO
+ _symbolic _____ 12DormancyCore26BiomeUserInteractionStreamO
+ _symbolic _____Sg13lastEventDate______5statet 10Foundation4DateV 12DormancyCore0C7MonitorC14CandidateStateO
+ _symbolic _____y_____G s11_SetStorageC 12DormancyCore17FeatureDefinitionV7ConsentO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12DormancyCore0D7MonitorC14CandidateStateO10CodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12DormancyCore0D7MonitorC14CandidateStateO14IdleCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12DormancyCore0D7MonitorC14CandidateStateO27ProposedAutomaticCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12DormancyCore0D7MonitorC14InactiveReasonO18InformedCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12DormancyCore15StatusCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12DormancyCore17ExcludedCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12DormancyCore17InactiveCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12DormancyCore18CandidateCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12DormancyCore0D7MonitorC14CandidateStateO10CodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12DormancyCore0D7MonitorC14CandidateStateO14IdleCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12DormancyCore0D7MonitorC14CandidateStateO27ProposedAutomaticCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12DormancyCore0D7MonitorC14InactiveReasonO18InformedCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12DormancyCore15StatusCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12DormancyCore17ExcludedCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12DormancyCore17InactiveCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 12DormancyCore18CandidateCodingKey33_CC3020B8B543D633345D40062FA1D1DBLLO
+ _symbolic ySS_SStc
- ___swift_memcpy128_8
- ___swift_memcpy224_8
- _associated conformance 12DormancyCore0A7MonitorC6StatusO10CodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOSHAASQ
- _associated conformance 12DormancyCore0A7MonitorC6StatusO10CodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0E3KeyAAs23CustomStringConvertible
- _associated conformance 12DormancyCore0A7MonitorC6StatusO10CodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0E3KeyAAs28CustomDebugStringConvertible
- _associated conformance 12DormancyCore0A7MonitorC6StatusO16ActiveCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0F3KeyAAs23CustomStringConvertible
- _associated conformance 12DormancyCore0A7MonitorC6StatusO16ActiveCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0F3KeyAAs28CustomDebugStringConvertible
- _associated conformance 12DormancyCore0A7MonitorC6StatusO18ExcludedCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOSHAASQ
- _associated conformance 12DormancyCore0A7MonitorC6StatusO18ExcludedCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0F3KeyAAs23CustomStringConvertible
- _associated conformance 12DormancyCore0A7MonitorC6StatusO18ExcludedCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0F3KeyAAs28CustomDebugStringConvertible
- _associated conformance 12DormancyCore0A7MonitorC6StatusO18InactiveCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOSHAASQ
- _associated conformance 12DormancyCore0A7MonitorC6StatusO18InactiveCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0F3KeyAAs23CustomStringConvertible
- _associated conformance 12DormancyCore0A7MonitorC6StatusO18InactiveCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0F3KeyAAs28CustomDebugStringConvertible
- _associated conformance 12DormancyCore0A7MonitorC6StatusO19CandidateCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOSHAASQ
- _associated conformance 12DormancyCore0A7MonitorC6StatusO19CandidateCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0F3KeyAAs23CustomStringConvertible
- _associated conformance 12DormancyCore0A7MonitorC6StatusO19CandidateCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLOs0F3KeyAAs28CustomDebugStringConvertible
- _objc_autorelease
- _objc_retain_x1
- _swift_retain_x19
- _symbolic _____ 12DormancyCore0A7MonitorC6StatusO10CodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
- _symbolic _____ 12DormancyCore0A7MonitorC6StatusO16ActiveCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
- _symbolic _____ 12DormancyCore0A7MonitorC6StatusO18ExcludedCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
- _symbolic _____ 12DormancyCore0A7MonitorC6StatusO18InactiveCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
- _symbolic _____ 12DormancyCore0A7MonitorC6StatusO19CandidateCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
- _symbolic _____Sg13lastEventDate_t 10Foundation4DateV
- _symbolic _____y_____G s22KeyedDecodingContainerV 12DormancyCore0D7MonitorC6StatusO10CodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 12DormancyCore0D7MonitorC6StatusO16ActiveCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 12DormancyCore0D7MonitorC6StatusO18ExcludedCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 12DormancyCore0D7MonitorC6StatusO18InactiveCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 12DormancyCore0D7MonitorC6StatusO19CandidateCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 12DormancyCore0D7MonitorC6StatusO10CodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 12DormancyCore0D7MonitorC6StatusO16ActiveCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 12DormancyCore0D7MonitorC6StatusO18ExcludedCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 12DormancyCore0D7MonitorC6StatusO18InactiveCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 12DormancyCore0D7MonitorC6StatusO19CandidateCodingKeys33_F8D6856B5B68C23C991E3A725FE1B06ALLO
CStrings:
+ "Candidate (State: "
+ "CompanionDevicePreferences wrote key %s, syncing nano domain"
+ "Donating event: %s:%s context: %s"
+ "Missing Dormancy.feature.userInteraction Biome stream"
+ "Unknown DormancyMonitor.Status case"
+ "com.apple.NanoBooks"
+ "com.apple.dormancy.interaction.settings"
+ "feature_dormancy_opt_out"
+ "informed"
+ "lastEventDate"
+ "lastEventDate state "
+ "proposedAutomatic"
+ "reason"
+ "state"
- "Candidate (Last Event: "
```
