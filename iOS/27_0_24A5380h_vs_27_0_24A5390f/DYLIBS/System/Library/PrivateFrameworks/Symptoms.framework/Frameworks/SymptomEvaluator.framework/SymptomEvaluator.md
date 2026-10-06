## SymptomEvaluator

> `/System/Library/PrivateFrameworks/Symptoms.framework/Frameworks/SymptomEvaluator.framework/SymptomEvaluator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29f910` | `0x2a0800` | **`+0xef0`** |
| `__AUTH.__objc_data` | `0x1448` | `0x1178` | **`-0x2d0`** |
| `__DATA_DIRTY.__objc_data` | `0x42b8` | `0x4588` | **`+0x2d0`** |
| `__TEXT.__oslogstring` | `0x47b65` | `0x47e15` | **`+0x2b0`** |
| `__TEXT.__cstring` | `0x27620` | `0x27840` | **`+0x220`** |
| `__DATA_DIRTY.__bss` | `0x1760` | `0x18d0` | **`+0x170`** |
| `__DATA.__bss` | `0x1030` | `0xed0` | **`-0x160`** |
| `__AUTH_CONST.__objc_const` | `0x41918` | `0x41a08` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0x1f280` | `0x1f360` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x18c20` | `0x18c80` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0xd4a8` | `0xd4f0` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x7a60` | `0x7a98` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x6f98` | `0x6fc0` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x3184` | `0x31a0` | **`+0x1c`** |
| `__DATA.__data` | `0x1f30` | `0x1f20` | **`-0x10`** |
| `__DATA_DIRTY.__data` | `0x1e0` | `0x1f0` | **`+0x10`** |
| `__TEXT.__const` | `0x1268` | `0x1278` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x52b8` | `0x52c8` | **`+0x10`** |

### Other Changes

```diff

-2385.0.0.0.0
+2394.0.0.0.0

-  Functions: 12215
-  Symbols:   19994
-  CStrings:  12198
+  Functions: 12227
+  Symbols:   20018
+  CStrings:  12214
Symbols:
+ +[CellFallbackHandler _rnfFellbackReleaseWindowMultiplier]
+ -[CellFallbackHandler _armRnfFellbackRecomputeTimer]
+ -[CellFallbackHandler _fallbackOrMigrationCountInLastMsecs:]
+ -[CellFallbackHandler _updateRnfFellback]
+ -[NoBackhaulHandler _configurePolicyDefaults]
+ -[NoBackhaulHandler _ensureICMPProbeDictionariesAllocated]
+ -[WiFiShim isConnectivityAssistEnabled]
+ -[WiFiStateRelay isConnAssistDisabled]
+ -[WiFiStateRelay setIsConnAssistDisabled:]
+ GCC_except_table129
+ GCC_except_table148
+ GCC_except_table149
+ GCC_except_table164
+ GCC_except_table425
+ GCC_except_table50
+ GCC_except_table53
+ GCC_except_table55
+ GCC_except_table73
+ GCC_except_table92
+ _OBJC_IVAR_$_CellFallbackHandler.aonEscalationsTally
+ _OBJC_IVAR_$_CellFallbackHandler.fallbackClosedLoopCount
+ _OBJC_IVAR_$_CellFallbackHandler.fallbackClosedLoopMsecs
+ _OBJC_IVAR_$_CellFallbackHandler.fallbackEvents
+ _OBJC_IVAR_$_CellFallbackHandler.rnfFellbackRecomputeTimer
+ _OBJC_IVAR_$_NoBackhaulHandler._policyDefaults
+ _OBJC_IVAR_$_WiFiStateRelay._isConnAssistDisabled
+ ___38-[WiFiStateRelay isConnAssistDisabled]_block_invoke
+ ___42-[WiFiStateRelay setIsConnAssistDisabled:]_block_invoke
+ ___52-[CellFallbackHandler _armRnfFellbackRecomputeTimer]_block_invoke
+ ___block_descriptor_32_e47_B24?0"CellularStateRelay"8"WiFiStateRelay"16l
+ _kFallbackClosedLoopCountRNF
+ _kFallbackClosedLoopMsecsRNF
+ _kWiFiShimIsConnectivityAssistEnabled
- GCC_except_table127
- GCC_except_table132
- GCC_except_table136
- GCC_except_table137
- GCC_except_table140
- GCC_except_table145
- GCC_except_table51
- GCC_except_table72
- ___block_descriptor_32_e50_B24?0"CellularStateRelay"8"NetworkStateRelay"16l
CStrings:
+ "\t\t\t\t\tCFSM evict SKIPPED for: %@, lqm: %d, rxSigExmp: 0x%x, cell-generic: %d, bbh: %d, re-arming"
+ "\t\t\tCFSM loop eval: %s for: %@, escal: %d, wificalling: %d, rnfFellback: %d, stationary: %d, cell-active: %d, wifi-active: %d, wifi-primary: %d, wifi-assess: %d, wifi-signal-exmp: %u, tokens: %d"
+ "(active == NO) OR (primary == NO) OR (isConnAssistDisabled == YES)"
+ "(active == NO) OR (primary == NO) OR (isConnAssistDisabled == YES) OR ( (rnfPolledScore >= 25) AND (rnfFrictionThresholded == NO) AND (dnsOut == NO) AND (rnfDataStalled == NO) AND (linkAssessment > 3) AND ((rxSignalExemptions & 4) != 4) AND ((rxSignalExemptions & 8) != 8) AND ((rxSignalExemptions & 16) != 16) )"
+ "(active == NO) OR (primary == NO) OR (isConnAssistDisabled == YES) OR ( (rnfPolledScore >= 50) AND (dnsOut == NO) AND (rnfDataStalled == NO) AND (linkAssessment > 4) AND ((rxSignalExemptions & 4) != 4) AND ((rxSignalExemptions & 8) != 8) AND ((rxSignalExemptions & 16) != 16) )"
+ "(active == NO) OR (primary == NO) OR (isConnAssistDisabled == YES) OR ( (rxSignalThresholded == NO) AND (linkAssessment > 4) AND ((rxSignalExemptions & 4) != 4) AND ((rxSignalExemptions & 8) != 8) AND ((rxSignalExemptions & 16) != 16) )"
+ "(active == NO) OR (primary == NO) OR (isConnAssistDisabled == YES) OR ( (sustainedDnsOut == NO) AND ((linkAssessment <= 4) OR (((rnfPolledScore >= 50) OR (rnfFellback == NO)) AND (apsdFailure == NO))) AND (linkAssessment > 4) AND ((rxSignalThresholded == NO) OR ((rnfPolledScore >= 50) AND (rnfDataStalled == NO))) AND ((rxSignalExemptions & 4) != 4) AND ((rxSignalExemptions & 8) != 8) AND ((rxSignalExemptions & 16) != 16) )"
+ "(active == YES) AND (primary == YES) AND (isConnAssistDisabled == NO)"
+ "(active == YES) AND (primary == YES) AND (isConnAssistDisabled == NO) AND ( (rnfPolledScore < 25) OR (rnfFrictionThresholded == YES) OR (dnsOut == YES) OR (rnfDataStalled == YES) OR (linkAssessment <= 3) OR ((rxSignalExemptions & 4) == 4) OR ((rxSignalExemptions & 8) == 8) OR ((rxSignalExemptions & 16) == 16) )"
+ "(active == YES) AND (primary == YES) AND (isConnAssistDisabled == NO) AND ( (rnfPolledScore < 50) OR (dnsOut == YES) OR (rnfDataStalled == YES) OR (linkAssessment <= 4) OR ((rxSignalExemptions & 4) == 4) OR ((rxSignalExemptions & 8) == 8) OR ((rxSignalExemptions & 16) == 16) )"
+ "(active == YES) AND (primary == YES) AND (isConnAssistDisabled == NO) AND ( (rxSignalThresholded == YES) OR (linkAssessment <= 4) OR ((rxSignalExemptions & 4) == 4) OR ((rxSignalExemptions & 8) == 8) OR ((rxSignalExemptions & 16) == 16) )"
+ "(active == YES) AND (primary == YES) AND (isConnAssistDisabled == NO) AND ( (sustainedDnsOut == YES) OR ((linkAssessment > 4) AND (((rnfPolledScore < 50) AND (rnfFellback == YES)) OR (apsdFailure == YES))) OR (linkAssessment <= 4) OR ((rxSignalThresholded == YES) AND ((rnfPolledScore < 50) OR (rnfDataStalled == YES))) OR ((rxSignalExemptions & 4) == 4) OR ((rxSignalExemptions & 8) == 8) OR ((rxSignalExemptions & 16) == 16) )"
+ "AON escalations"
+ "B24@?0@\"CellularStateRelay\"8@\"WiFiStateRelay\"16"
+ "CFSM AON escalations: %llu"
+ "CFSM AlwaysOn RNF is %sabled, SSID-level %sabled"
+ "CFSM rnf fellback event event with no prior kernel inUse 0->1"
+ "CFSM rnf fellback event lag from last inUse 0->1: %.1f ms"
+ "CFSM rnf kernel inUse 0->1 edge lag from last fallback/migration event: %.1f ms"
+ "CFSM rnf kernel inUse 0->1 edge with no prior fallback/migration event"
+ "CFSM: Invalid fallbackClosedLoopCount %u, clamping to 1"
+ "CFSM: Invalid trial fallbackClosedLoopCount %u, clamping to 1"
+ "SSID-level disabled"
+ "dropping upward post (code %llu): handler administratively disabled"
+ "dsTshold: %d, dsTimeSecs: %d, dsRefreshSecs: %d, probesFailureFactor: %.2f, packetsFrictionFactor %.2f, progressTimeSecs: %d, historyProgressTimeSecs: %d, maxPreferResidencyMsecs: %llu, rnfToCellRatio: %.2f, fallbackHeavyRatio: %.2f, usePolledScore: %d, rnfPolledScoreWindowSize: %lu, useOpportunistic: %d, usePrefer: %d, fallbackClosedLoop: %d, fallbackClosedLoopCount: %u, fallbackClosedLoopMsecs: %llu, sustainedDnsOutDelaySecs: %.1f"
+ "fallbackClosedLoopCount"
+ "fallbackClosedLoopMsecs"
+ "isConnAssistDisabled"
+ "isConnectivityAssistEnabled"
+ "re-setting no_backhaul_fast_track_enabled to default: %{BOOL}d"
+ "re-setting no_backhaul_rx_recovery_enabled to default: %{BOOL}d"
+ "re-setting no_backhaul_verify_default_gateway to its platform default: %{BOOL}d"
+ "re-setting no_backhaul_wifi_friction_score_enabled to default: %{BOOL}d"
+ "set to a new value for no_backhaul_fast_track_enabled (was/is): %{BOOL}d/%{BOOL}d"
+ "set to a new value for no_backhaul_rx_recovery_enabled (was/is): %{BOOL}d/%{BOOL}d"
+ "set to a new value for no_backhaul_verify_default_gateway behavior (was/is): %{BOOL}d/%{BOOL}d"
+ "set to a new value for no_backhaul_wifi_friction_score_enabled (was/is): %{BOOL}d/%{BOOL}d"
- "\t\t\tCFSM loop eval: %s for: %@, escal: %d, wificalling: %d, stationary: %d, cell-active: %d, wifi-active: %d, wifi-primary: %d, wifi-assess: %d, wifi-signal-exmp: %u, tokens: %d"
- "(active == NO) OR (primary == NO) OR ( (rnfPolledScore >= 25) AND (rnfFrictionThresholded == NO) AND (dnsOut == NO) AND (rnfDataStalled == NO) AND (linkAssessment > 3) AND ((rxSignalExemptions & 4) != 4) AND ((rxSignalExemptions & 8) != 8) AND ((rxSignalExemptions & 16) != 16) )"
- "(active == NO) OR (primary == NO) OR ( (rnfPolledScore >= 50) AND (dnsOut == NO) AND (rnfDataStalled == NO) AND (linkAssessment > 4) AND ((rxSignalExemptions & 4) != 4) AND ((rxSignalExemptions & 8) != 8) AND ((rxSignalExemptions & 16) != 16) )"
- "(active == NO) OR (primary == NO) OR ( (rxSignalThresholded == NO) AND (linkAssessment > 4) AND ((rxSignalExemptions & 4) != 4) AND ((rxSignalExemptions & 8) != 8) AND ((rxSignalExemptions & 16) != 16) )"
- "(active == NO) OR (primary == NO) OR ( (sustainedDnsOut == NO) AND ((linkAssessment <= 4) OR (((rnfPolledScore >= 50) OR (rnfFellback == NO)) AND (apsdFailure == NO))) AND (linkAssessment > 4) AND ((rxSignalThresholded == NO) OR ((rnfPolledScore >= 50) AND (rnfDataStalled == NO))) AND ((rxSignalExemptions & 4) != 4) AND ((rxSignalExemptions & 8) != 8) AND ((rxSignalExemptions & 16) != 16) )"
- "(active == YES) AND (primary == YES)"
- "(active == YES) AND (primary == YES) AND ( (rnfPolledScore < 25) OR (rnfFrictionThresholded == YES) OR (dnsOut == YES) OR (rnfDataStalled == YES) OR (linkAssessment <= 3) OR ((rxSignalExemptions & 4) == 4) OR ((rxSignalExemptions & 8) == 8) OR ((rxSignalExemptions & 16) == 16) )"
- "(active == YES) AND (primary == YES) AND ( (rnfPolledScore < 50) OR (dnsOut == YES) OR (rnfDataStalled == YES) OR (linkAssessment <= 4) OR ((rxSignalExemptions & 4) == 4) OR ((rxSignalExemptions & 8) == 8) OR ((rxSignalExemptions & 16) == 16) )"
- "(active == YES) AND (primary == YES) AND ( (rxSignalThresholded == YES) OR (linkAssessment <= 4) OR ((rxSignalExemptions & 4) == 4) OR ((rxSignalExemptions & 8) == 8) OR ((rxSignalExemptions & 16) == 16) )"
- "(active == YES) AND (primary == YES) AND ( (sustainedDnsOut == YES) OR ((linkAssessment > 4) AND (((rnfPolledScore < 50) AND (rnfFellback == YES)) OR (apsdFailure == YES))) OR (linkAssessment <= 4) OR ((rxSignalThresholded == YES) AND ((rnfPolledScore < 50) OR (rnfDataStalled == YES))) OR ((rxSignalExemptions & 4) == 4) OR ((rxSignalExemptions & 8) == 8) OR ((rxSignalExemptions & 16) == 16) )"
- "B24@?0@\"CellularStateRelay\"8@\"NetworkStateRelay\"16"
- "CFSM AlwaysOn RNF is %sabled"
- "dsTshold: %d, dsTimeSecs: %d, dsRefreshSecs: %d, probesFailureFactor: %.2f, packetsFrictionFactor %.2f, progressTimeSecs: %d, historyProgressTimeSecs: %d, maxPreferResidencyMsecs: %llu, rnfToCellRatio: %.2f, fallbackHeavyRatio: %.2f, usePolledScore: %d, rnfPolledScoreWindowSize: %lu, useOpportunistic: %d, usePrefer: %d, fallbackClosedLoop: %d, sustainedDnsOutDelaySecs: %.1f"
- "re-setting no_backhaul_fast_track_enabled to default: %d"
- "re-setting no_backhaul_rx_recovery_enabled to default: %d"
- "re-setting no_backhaul_verify_default_gateway to a default behavior: %d"
- "re-setting no_backhaul_wifi_friction_score_enabled to default: %d"
- "set to a new value for no_backhaul_fast_track_enabled (was/is): %d/%d"
- "set to a new value for no_backhaul_rx_recovery_enabled (was/is): %d/%d"
- "set to a new value for no_backhaul_verify_default_gateway behavior (was/is): %d/%d"
- "set to a new value for no_backhaul_wifi_friction_score_enabled (was/is): %d/%d"
```
