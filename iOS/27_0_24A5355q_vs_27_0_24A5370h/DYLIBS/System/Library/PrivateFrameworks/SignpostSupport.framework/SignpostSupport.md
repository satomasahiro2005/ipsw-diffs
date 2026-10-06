## SignpostSupport

> `/System/Library/PrivateFrameworks/SignpostSupport.framework/SignpostSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x761c4` | `0x77508` | **`+0x1344`** |
| `__AUTH_CONST.__objc_const` | `0x16a58` | `0x16d58` | **`+0x300`** |
| `__AUTH_CONST.__cfstring` | `0x1c7c0` | `0x1caa0` | **`+0x2e0`** |
| `__TEXT.__cstring` | `0x1a5b3` | `0x1a756` | **`+0x1a3`** |
| `__TEXT.__unwind_info` | `0x2410` | `0x2550` | **`+0x140`** |
| `__TEXT.__gcc_except_tab` | `0x24d0` | `0x2604` | **`+0x134`** |
| `__TEXT.__objc_methlist` | `0x9fbc` | `0xa0a4` | **`+0xe8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3b58` | `0x3bc8` | **`+0x70`** |
| `__DATA_CONST.__objc_arraydata` | `0x5070` | `0x50c8` | **`+0x58`** |
| `__DATA.__objc_ivar` | `0xef4` | `0xf38` | **`+0x44`** |
| `__AUTH_CONST.__const` | `0x1828` | `0x1868` | **`+0x40`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x3d8` | `0x408` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0xf1d` | `0xef4` | **`-0x29`** |
| `__DATA.__bss` | `0x400` | `0x410` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1438` | `0x1448` | **`+0x10`** |

### Other Changes

```diff

-197.0.0.0.0
+200.0.0.0.0

-  Functions: 4066
-  Symbols:   7232
-  CStrings:  3901
+  Functions: 4114
+  Symbols:   7305
+  CStrings:  3922
Symbols:
+ -[SSHighCadenceAggregation _hasPstrData]
+ -[SSHighCadenceAggregation _pstrMilliJoulesAccumulated]
+ -[SSHighCadenceAggregation averagePstrMilliWatts]
+ -[SSHighCadenceAggregation pstrMilliJoules]
+ -[SSHighCadenceAggregation sampledTcmbCelsius]
+ -[SSHighCadenceAggregation sampledXpptMilliWatts]
+ -[SSHighCadenceAggregation setSampledTcmbCelsius:]
+ -[SSHighCadenceAggregation setSampledXpptMilliWatts:]
+ -[SSHighCadenceAggregation set_hasPstrData:]
+ -[SSHighCadenceAggregation set_pstrMilliJoulesAccumulated:]
+ -[SSHighCadenceSystemMetrics averagePstrMilliWatts]
+ -[SSHighCadenceSystemMetrics pstrMilliJoules]
+ -[SSHighCadenceSystemMetrics sampledTcmbCelsius]
+ -[SSHighCadenceSystemMetrics sampledXpptMilliWatts]
+ -[SSPSMHighCadenceBuffer averagePstrMw]
+ -[SSPSMHighCadenceBuffer hasAveragePstrMw]
+ -[SSPSMHighCadenceBuffer hasSampledTcmbDc]
+ -[SSPSMHighCadenceBuffer hasSampledXpptMw]
+ -[SSPSMHighCadenceBuffer sampledTcmbDc]
+ -[SSPSMHighCadenceBuffer sampledXpptMw]
+ -[SSPSMHighCadenceBufferBuilder setAveragePstrMw:]
+ -[SSPSMHighCadenceBufferBuilder setSampledTcmbDc:]
+ -[SSPSMHighCadenceBufferBuilder setSampledXpptMw:]
+ -[SSPSMHighCadenceBufferChanges changeTypeAveragePstrMw]
+ -[SSPSMHighCadenceBufferChanges changeTypeSampledTcmbDc]
+ -[SSPSMHighCadenceBufferChanges changeTypeSampledXpptMw]
+ -[SSPSMHighCadenceBufferChanges omitAveragePstrMw]
+ -[SSPSMHighCadenceBufferChanges omitSampledTcmbDc]
+ -[SSPSMHighCadenceBufferChanges omitSampledXpptMw]
+ -[SSPSMHighCadenceBufferChanges preserveAveragePstrMw]
+ -[SSPSMHighCadenceBufferChanges preserveSampledTcmbDc]
+ -[SSPSMHighCadenceBufferChanges preserveSampledXpptMw]
+ -[SSPSMHighCadenceBufferChanges replaceAveragePstrMw:]
+ -[SSPSMHighCadenceBufferChanges replaceSampledTcmbDc:]
+ -[SSPSMHighCadenceBufferChanges replaceSampledXpptMw:]
+ -[SSPSMHighCadenceBufferChanges replacementAveragePstrMw]
+ -[SSPSMHighCadenceBufferChanges replacementSampledTcmbDc]
+ -[SSPSMHighCadenceBufferChanges replacementSampledXpptMw]
+ -[SSReportedStateProcessor initWithTransitionBlock:volatileUpdateBlock:rateLimitStartBlock:rateLimitEndBlock:stateHeartbeatBlock:monitorHeartbeats:errorOut:]
+ -[SSReportedStateProcessor stateHeartbeatBlock]
+ -[SignpostFrameStatistics renderCostEstimate]
+ -[SignpostGPURenderInterval initWithInterval:frameSeed:renderCostEstimate:]
+ -[SignpostGPURenderInterval renderCostEstimate]
+ -[SignpostSupportObjectExtractor setStateHeartbeatBlock:]
+ -[SignpostSupportObjectExtractor stateHeartbeatBlock]
+ GCC_except_table100
+ GCC_except_table103
+ GCC_except_table109
+ GCC_except_table110
+ GCC_except_table111
+ GCC_except_table112
+ GCC_except_table121
+ GCC_except_table138
+ GCC_except_table139
+ GCC_except_table167
+ GCC_except_table170
+ GCC_except_table172
+ GCC_except_table176
+ GCC_except_table177
+ GCC_except_table198
+ GCC_except_table205
+ GCC_except_table208
+ GCC_except_table210
+ GCC_except_table215
+ GCC_except_table236
+ GCC_except_table240
+ GCC_except_table248
+ GCC_except_table250
+ GCC_except_table252
+ GCC_except_table265
+ GCC_except_table266
+ GCC_except_table273
+ GCC_except_table314
+ GCC_except_table321
+ GCC_except_table322
+ GCC_except_table324
+ GCC_except_table326
+ GCC_except_table359
+ GCC_except_table389
+ GCC_except_table399
+ GCC_except_table409
+ GCC_except_table419
+ GCC_except_table429
+ GCC_except_table439
+ GCC_except_table449
+ GCC_except_table459
+ GCC_except_table469
+ GCC_except_table72
+ GCC_except_table77
+ GCC_except_table83
+ GCC_except_table86
+ GCC_except_table91
+ GCC_except_table93
+ GCC_except_table99
+ _OBJC_IVAR_$_SSHighCadenceAggregation.__hasPstrData
+ _OBJC_IVAR_$_SSHighCadenceAggregation.__pstrMilliJoulesAccumulated
+ _OBJC_IVAR_$_SSHighCadenceAggregation._sampledTcmbCelsius
+ _OBJC_IVAR_$_SSHighCadenceAggregation._sampledXpptMilliWatts
+ _OBJC_IVAR_$_SSHighCadenceSystemMetrics._averagePstrMilliWatts
+ _OBJC_IVAR_$_SSHighCadenceSystemMetrics._sampledTcmbCelsius
+ _OBJC_IVAR_$_SSHighCadenceSystemMetrics._sampledXpptMilliWatts
+ _OBJC_IVAR_$_SSPSMHighCadenceBufferChanges._changeTypeAveragePstrMw
+ _OBJC_IVAR_$_SSPSMHighCadenceBufferChanges._changeTypeSampledTcmbDc
+ _OBJC_IVAR_$_SSPSMHighCadenceBufferChanges._changeTypeSampledXpptMw
+ _OBJC_IVAR_$_SSPSMHighCadenceBufferChanges._replacementAveragePstrMw
+ _OBJC_IVAR_$_SSPSMHighCadenceBufferChanges._replacementSampledTcmbDc
+ _OBJC_IVAR_$_SSPSMHighCadenceBufferChanges._replacementSampledXpptMw
+ _OBJC_IVAR_$_SSReportedStateProcessor._stateHeartbeatBlock
+ _OBJC_IVAR_$_SignpostFrameStatistics._renderCostEstimate
+ _OBJC_IVAR_$_SignpostGPURenderInterval._renderCostEstimate
+ _OBJC_IVAR_$_SignpostSupportObjectExtractor._stateHeartbeatBlock
+ _OUTLINED_FUNCTION_20
+ _OUTLINED_FUNCTION_21
+ _SignpostReporterCrossPlatformMADHKSVGenerativeProcessingAllowlist
+ _SignpostReporterCrossPlatformMADHKSVGenerativeProcessingAllowlist.allowlistArray
+ _SignpostReporterCrossPlatformMADHKSVGenerativeProcessingAllowlist.onceToken
+ __ZN14PSMHighCadence24HighCadenceBufferBuilder19add_sampled_tcmb_dcEs
+ __ZN5apple4aiml12flatbuffers217FlatBufferBuilder10AddElementIjEEvtT_
+ __ZN5apple4aiml12flatbuffers217FlatBufferBuilder11PushElementIsEEjT_
+ __ZNKSt9type_infoeqB9fqe220106ERKS_
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__110__function12__value_funcIFN5apple4aiml12flatbuffers26OffsetIvEEmEED2B9fqe220106Ev
+ __ZNSt3__110__function12__value_funcIFvmPN14PSMHighCadence13ClusterDeltasEEED2B9fqe220106Ev
+ __ZNSt3__110__function12__value_funcIFvmPN14PSMHighCadence13LostPerfEntryEEED2B9fqe220106Ev
+ __ZNSt3__110__function12__value_funcIFvmPN14PSMHighCadence16CLPCPackageStatsEEED2B9fqe220106Ev
+ __ZNSt3__110__function12__value_funcIFvmPN14PSMHighCadence8QoSEntryEEED2B9fqe220106Ev
+ __ZNSt3__110__function12__value_funcIFvmPN16PSMMediumCadence17GpuPerfStateEntryEEED2B9fqe220106Ev
+ __ZNSt3__110__function12__value_funcIFvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEED2B9fqe220106Ev
+ __ZNSt3__110__function12__value_funcIFvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEED2B9fqe220106Ev
+ __ZNSt3__110__function12__value_funcIFvmPN16PSMMediumCadence7VMStatsEEED2B9fqe220106Ev
+ __ZNSt3__119__allocate_at_leastB9fqe220106INS_9allocatorIN5apple4aiml12flatbuffers26OffsetIvEEEENS_16allocator_traitsIS7_EEEENS_19__allocation_resultINT0_7pointerENSB_9size_typeEEERT_m
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__125__throw_bad_function_callB9fqe220106Ev
+ __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetIvEENS_9allocatorIS5_EEE11__vallocateB9fqe220106Em
+ __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetIvEENS_9allocatorIS5_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetIvEENS_9allocatorIS5_EEEC2B9fqe220106Em
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ ___SignpostReporterCrossPlatformMADHKSVGenerativeProcessingAllowlist_block_invoke
+ _kSSCAIOMFBContextProcessExecutablePathName_block_invoke_9
+ _kSSFrameUpdateRenderCostEstimateKey
- -[SSReportedStateProcessor initWithTransitionBlock:volatileUpdateBlock:rateLimitStartBlock:rateLimitEndBlock:monitorHeartbeats:errorOut:]
- GCC_except_table106
- GCC_except_table114
- GCC_except_table115
- GCC_except_table122
- GCC_except_table136
- GCC_except_table144
- GCC_except_table148
- GCC_except_table152
- GCC_except_table153
- GCC_except_table174
- GCC_except_table182
- GCC_except_table186
- GCC_except_table191
- GCC_except_table192
- GCC_except_table199
- GCC_except_table212
- GCC_except_table224
- GCC_except_table228
- GCC_except_table241
- GCC_except_table242
- GCC_except_table249
- GCC_except_table278
- GCC_except_table297
- GCC_except_table298
- GCC_except_table300
- GCC_except_table333
- GCC_except_table351
- GCC_except_table373
- GCC_except_table383
- GCC_except_table393
- GCC_except_table403
- GCC_except_table413
- GCC_except_table423
- GCC_except_table433
- GCC_except_table443
- GCC_except_table65
- GCC_except_table66
- GCC_except_table68
- GCC_except_table69
- GCC_except_table73
- GCC_except_table76
- GCC_except_table78
- GCC_except_table80
- GCC_except_table84
- GCC_except_table85
- GCC_except_table88
- GCC_except_table97
- __ZN14PSMHighCadence24HighCadenceBufferBuilder35add_ecpu_util_controller_engaged_msEj
- __ZNKSt9type_infoeqB9fqe220100ERKS_
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__110__function12__value_funcIFN5apple4aiml12flatbuffers26OffsetIvEEmEED2B9fqe220100Ev
- __ZNSt3__110__function12__value_funcIFvmPN14PSMHighCadence13ClusterDeltasEEED2B9fqe220100Ev
- __ZNSt3__110__function12__value_funcIFvmPN14PSMHighCadence13LostPerfEntryEEED2B9fqe220100Ev
- __ZNSt3__110__function12__value_funcIFvmPN14PSMHighCadence16CLPCPackageStatsEEED2B9fqe220100Ev
- __ZNSt3__110__function12__value_funcIFvmPN14PSMHighCadence8QoSEntryEEED2B9fqe220100Ev
- __ZNSt3__110__function12__value_funcIFvmPN16PSMMediumCadence17GpuPerfStateEntryEEED2B9fqe220100Ev
- __ZNSt3__110__function12__value_funcIFvmPN16PSMMediumCadence19GpuSwPerfStateEntryEEED2B9fqe220100Ev
- __ZNSt3__110__function12__value_funcIFvmPN16PSMMediumCadence28GpuPowerControllerStateEntryEEED2B9fqe220100Ev
- __ZNSt3__110__function12__value_funcIFvmPN16PSMMediumCadence7VMStatsEEED2B9fqe220100Ev
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorIN5apple4aiml12flatbuffers26OffsetIvEEEENS_16allocator_traitsIS7_EEEENS_19__allocation_resultINT0_7pointerENSB_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__125__throw_bad_function_callB9fqe220100Ev
- __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetIvEENS_9allocatorIS5_EEE11__vallocateB9fqe220100Em
- __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetIvEENS_9allocatorIS5_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorIN5apple4aiml12flatbuffers26OffsetIvEENS_9allocatorIS5_EEEC2B9fqe220100Em
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
CStrings:
+ "\nAverage PSTR:\t%@ mW (%.4f mJ)"
+ "\nSampled TCMb:\t%@ C"
+ "\nSampled xPPT:\t%@ mW"
+ "EndToEnd"
+ "Heartbeat monitoring block provided but not monitoring heartbeats"
+ "No processing blocks provided"
+ "ReceiveResultsFromAgent"
+ "RunRequest"
+ "SendRequestToAgent"
+ "VideoCaption"
+ "VideoDecode"
+ "VideoEmbedding"
+ "VideoGate"
+ "averagePstrMilliWatts"
+ "cost"
+ "mW"
+ "pass_cost"
+ "pstrMilliJoules"
+ "renderCostEstimate"
+ "render_cost_estimate"
+ "sampledTcmbCelsius"
+ "sampledXpptMilliWatts"
- "Using string allowlist with %lu elements"
```
