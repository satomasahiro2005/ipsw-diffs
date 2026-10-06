## SpotlightKnowledgeDaemon

> `/System/Library/PrivateFrameworks/SpotlightKnowledgeDaemon.framework/SpotlightKnowledgeDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ad888` | `0x4b1c98` | **`+0x4410`** |
| `__DATA_DIRTY.__data` | `0xc2f8` | `0xd608` | **`+0x1310`** |
| `__DATA_DIRTY.__bss` | `0x88f0` | `0x99f0` | **`+0x1100`** |
| `__DATA.__bss` | `0xfb80` | `0xead0` | **`-0x10b0`** |
| `__DATA.__data` | `0x3ed0` | `0x3560` | **`-0x970`** |
| `__AUTH.__data` | `0x2bb8` | `0x2478` | **`-0x740`** |
| `__TEXT.__eh_frame` | `0x152a8` | `0x15898` | **`+0x5f0`** |
| `__TEXT.__gcc_except_tab` | `0x5a58` | `0x5c6c` | **`+0x214`** |
| `__AUTH_CONST.__const` | `0x19588` | `0x19778` | **`+0x1f0`** |
| `__TEXT.__unwind_info` | `0xcba0` | `0xcd60` | **`+0x1c0`** |
| `__AUTH_CONST.__cfstring` | `0x9260` | `0x9400` | **`+0x1a0`** |
| `__DATA_CONST.__objc_arraydata` | `0x890` | `0xa30` | **`+0x1a0`** |
| `__AUTH_CONST.__objc_intobj` | `0x9a8` | `0xb40` | **`+0x198`** |
| `__TEXT.__const` | `0x178f8` | `0x17a68` | **`+0x170`** |
| `__TEXT.__oslogstring` | `0x1296e` | `0x12ace` | **`+0x160`** |
| `__AUTH_CONST.__objc_const` | `0x183c0` | `0x18508` | **`+0x148`** |
| `__TEXT.__constg_swiftt` | `0x90b8` | `0x9188` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x1622e` | `0x162f3` | **`+0xc5`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x588` | `0x630` | **`+0xa8`** |
| `__AUTH.__objc_data` | `0x16e8` | `0x1648` | **`-0xa0`** |
| `__DATA.__common` | `0xe0` | `0x58` | **`-0x88`** |
| `__DATA_CONST.__const` | `0x3570` | `0x35f8` | **`+0x88`** |
| `__DATA_DIRTY.__common` | `0x380` | `0x408` | **`+0x88`** |
| `__TEXT.__swift5_fieldmd` | `0x9130` | `0x9194` | **`+0x64`** |
| `__TEXT.__swift5_reflstr` | `0x8d1a` | `0x8d7d` | **`+0x63`** |
| `__TEXT.__swift5_typeref` | `0xedea` | `0xee46` | **`+0x5c`** |
| `__AUTH_CONST.__objc_dictobj` | `0x280` | `0x2d0` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x3f00` | `0x3f50` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x38c4` | `0x3900` | **`+0x3c`** |
| `__TEXT.__swift5_assocty` | `0x13b0` | `0x13e0` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0xb6c` | `0xb90` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0x5e60` | `0x5e80` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2338` | `0x2350` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x9600` | `0x9618` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x10ac` | `0x10c4` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x488` | `0x498` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x8e8` | `0x8f4` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x37e8` | `0x37f0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x1f8` | `0x1f0` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x4d8` | `0x4d0` | **`-0x8`** |
| `__TEXT.__swift_as_ret` | `0x4d8` | `0x4e0` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x280` | `0x284` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x578` | `0x57c` | **`+0x4`** |

### Other Changes

```diff

-2465.1.2.0.0
+2465.1.3.0.0

-  Functions: 16737
-  Symbols:   11613
-  CStrings:  3753
+  Functions: 16839
+  Symbols:   11652
+  CStrings:  3765
Symbols:
+ -[SKDAnalyticsLogger accumulateError:processor:cellKey:status:]
+ -[SKDAnalyticsLogger accumulateModelCounts:context:language:bucket:]
+ -[SKDAnalyticsLogger sendEvents:]
+ -[SKDAnalyticsLogger slotForCellKey:]
+ -[SKDAnalyticsLogger slotForModelCellKey:]
+ -[SKDAnalyticsLogger takeSnapshot:batchCells:replacementCells:]
+ -[SKDLocationResolution _logPIROutcomeWithLocations:error:]
+ -[SKDPipelineFeedback addAddressesCount:]
+ -[SKDPipelineFeedback addBreadcrumbsCount:]
+ -[SKDPipelineFeedback addLocationsCount:]
+ -[SKDPipelineFeedback addPIRCount:]
+ -[SKDPipelineFeedback addressesCount]
+ -[SKDPipelineFeedback setAddressesCount:]
+ -[SKDPipelineFeedback setPIRCount:]
+ -[SKDRecordProcessor(Internal) logBatchFailureForUpdates:info:]
+ -[SKGDataDetector _callPIRWithQuery:errorBlock:useCase:]
+ -[SKGDataDetector _retrieveLocationFromPIR:locale:errorBlock:]
+ -[SKGDataDetector enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:entityBlock:rangeBlock:errorBlock:]
+ -[SKGDataDetector enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:entityCategories:entityBlock:rangeBlock:errorBlock:]
+ -[SKGDataDetector enumerateDetectedLocationsInString:locale:entityBlock:rangeBlock:errorBlock:]
+ -[SKGDataDetector locationFromAddress:locale:errorBlock:]
+ GCC_except_table48
+ _OBJC_IVAR_$_SKDAnalyticsLogger._cellCount
+ _OBJC_IVAR_$_SKDAnalyticsLogger._cellKeys
+ _OBJC_IVAR_$_SKDAnalyticsLogger._cellOverflow
+ _OBJC_IVAR_$_SKDAnalyticsLogger._completedItemCount
+ _OBJC_IVAR_$_SKDAnalyticsLogger._errorKeyCount
+ _OBJC_IVAR_$_SKDAnalyticsLogger._erroredItemCount
+ _OBJC_IVAR_$_SKDAnalyticsLogger._modelCellCount
+ _OBJC_IVAR_$_SKDAnalyticsLogger._modelCellCounts
+ _OBJC_IVAR_$_SKDAnalyticsLogger._modelCellKeys
+ _OBJC_IVAR_$_SKDAnalyticsLogger._modelCellOverflow
+ _OBJC_IVAR_$_SKDAnalyticsLogger._resultCount
+ _OBJC_IVAR_$_SKDPipelineFeedback._addressesCount
+ __DATA__TtC24SpotlightKnowledgeDaemon29GLPInsightsEmbeddingProcessor
+ __IVARS__TtC24SpotlightKnowledgeDaemon29GLPInsightsEmbeddingProcessor
+ __METACLASS_DATA__TtC24SpotlightKnowledgeDaemon29GLPInsightsEmbeddingProcessor
+ __MergedGlobals
+ ___40-[SKDAnalyticsLogSender sendLog:domain:]_block_invoke_2
+ ___56-[SKGDataDetector _callPIRWithQuery:errorBlock:useCase:]_block_invoke
+ ___62-[SKGDataDetector _retrieveLocationFromPIR:locale:errorBlock:]_block_invoke
+ ___62-[SKGDataDetector _retrieveLocationFromPIR:locale:errorBlock:]_block_invoke_2
+ ___62-[SKGDataDetector _retrieveLocationFromPIR:locale:errorBlock:]_block_invoke_3
+ ___76-[SKGDataDetector enumerateAirportCodesInStringUsingGeoScanner:entityBlock:]_block_invoke
+ ___78-[SKDLocationResolution _collectPIRResults:forQuery:locale:completionHandler:]_block_invoke_2
+ ___83-[SKDDataDetector enumerateResultsWithInputs:options:usingBlock:completionHandler:]_block_invoke_4
+ ___89-[SKDLocationResolution enumerateResultsWithInputs:options:usingBlock:completionHandler:]_block_invoke_4
+ ___block_descriptor_112_e8_32s40bs48r56r64r72r80r88r96r_e17_v16?0"NSError"8lr48l8s32l8r56l8s40l8r64l8r72l8r80l8r88l8r96l8
+ ___block_descriptor_48_e8_32bs40r_e17_v16?0"NSError"8lr40l8s32l8
+ ___block_descriptor_64_e8_32s40bs48r56r_e17_v16?0"NSError"8ls32l8r48l8s40l8r56l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e29_v24?0"NSArray"8"NSError"16ls32l8s40l8s48l8s56l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e39_v24?0"SKDEntityLocation"8"NSError"16ls32l8s40l8s56l8s48l8
+ ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s56l8s48l8
+ ___block_descriptor_72_e8_32s40bs48r56r64r_e17_v16?0"NSError"8ls32l8r48l8s40l8r56l8r64l8
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_80_e8_32s40bs48r56r64r_e17_v16?0"NSError"8ls32l8r48l8s40l8r56l8r64l8
+ ___block_descriptor_80_e8_32s40s48bs56r64r72r_e17_v16?0"NSError"8ls32l8r56l8s48l8r64l8s40l8r72l8
+ ___block_descriptor_80_e8_32s40s48s56s64s72bs_e5_v8?0ls32l8s40l8s48l8s56l8s72l8s64l8
+ ___block_descriptor_96_e8_32s40s48bs56r64r72r80r_e17_v16?0"NSError"8ls32l8r56l8s48l8r64l8s40l8r72l8r80l8
+ ___block_descriptor_96_e8_32s40s48s56s64s72bs80r88r_e17_v16?0"NSError"8lr80l8s32l8s40l8s72l8s48l8r88l8s56l8s64l8
+ ___contextIndexFromFeedback_block_invoke
+ ___errorCodeTable_block_invoke
+ ___errorDomainTable_block_invoke
+ ___processorIndexFromIdentifier_block_invoke
+ ___reportPIRError_block_invoke
+ ___swift_exist.box.addr_destructor.789Tm
+ _associated conformance 24SpotlightKnowledgeDaemon39GLPInsightsEmbeddingProcessorDescriptorVAA07CascadefG8ProtocolAA0F0AA0fgI0P_AA0hfI0
+ _associated conformance 24SpotlightKnowledgeDaemon39GLPInsightsEmbeddingProcessorDescriptorVAA0fG8ProtocolAA0F0AaDP_AA0fH0
+ _contextIndexFromFeedback
+ _contextIndexFromFeedback.map
+ _contextIndexFromFeedback.onceToken
+ _errorDomainTable
+ _errorDomainTable.domains
+ _errorDomainTable.onceToken
+ _processorIndexFromIdentifier
+ _processorIndexFromIdentifier.map
+ _processorIndexFromIdentifier.onceToken
+ _reportPIRError
+ _reportPIRError.onceToken
+ _sPIRNoLocationFoundError
+ _sPIRServerErrorNoUnderlying
+ _symbolic $s24SpotlightKnowledgeDaemon22GLPInsightsInterfacingP
+ _symbolic _____ 24SpotlightKnowledgeDaemon20GLPInsightsInterfaceV
+ _symbolic _____ 24SpotlightKnowledgeDaemon29GLPInsightsEmbeddingProcessorC
+ _symbolic _____ 24SpotlightKnowledgeDaemon39GLPInsightsEmbeddingProcessorDescriptorV
+ _symbolic ______p 24SpotlightKnowledgeDaemon22GLPInsightsInterfacingP
- -[SKDAnalyticsErrorKey .cxx_destruct]
- -[SKDAnalyticsErrorKey code]
- -[SKDAnalyticsErrorKey copyWithZone:]
- -[SKDAnalyticsErrorKey domain]
- -[SKDAnalyticsErrorKey hash]
- -[SKDAnalyticsErrorKey initWithDomain:code:]
- -[SKDAnalyticsErrorKey isEqual:]
- -[SKDAnalyticsLogger accumulateError:]
- -[SKDBaseItem initWithIdentifier:status:info:]
- -[SKDPipelineFeedback setPirCount:]
- -[SKDRecordUpdate initWithIdentifier:status:info:]
- -[SKGDataDetector _callPIRWithQuery:hitError:useCase:]
- -[SKGDataDetector _retrieveLocationFromPIR:locale:]
- -[SKGDataDetector enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:entityBlock:rangeBlock:]
- -[SKGDataDetector enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:entityCategories:entityBlock:rangeBlock:]
- -[SKGDataDetector enumerateDetectedLocationsInString:locale:entityBlock:rangeBlock:]
- -[SKGDataDetector locationFromAddress:locale:]
- _OBJC_CLASS_$_SKDAnalyticsErrorKey
- _OBJC_IVAR_$_SKDAnalyticsErrorKey._code
- _OBJC_IVAR_$_SKDAnalyticsErrorKey._domain
- _OBJC_IVAR_$_SKDAnalyticsLogger._processTable
- _OBJC_METACLASS_$_SKDAnalyticsErrorKey
- __OBJC_$_INSTANCE_METHODS_SKDAnalyticsErrorKey
- __OBJC_$_INSTANCE_VARIABLES_SKDAnalyticsErrorKey
- __OBJC_$_PROP_LIST_SKDAnalyticsErrorKey
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSCopying
- __OBJC_$_PROTOCOL_METHOD_TYPES_NSCopying
- __OBJC_CLASS_PROTOCOLS_$_SKDAnalyticsErrorKey
- __OBJC_CLASS_RO_$_SKDAnalyticsErrorKey
- __OBJC_LABEL_PROTOCOL_$_NSCopying
- __OBJC_METACLASS_RO_$_SKDAnalyticsErrorKey
- __OBJC_PROTOCOL_$_NSCopying
- ___51-[SKGDataDetector _retrieveLocationFromPIR:locale:]_block_invoke
- ___51-[SKGDataDetector _retrieveLocationFromPIR:locale:]_block_invoke_2
- ___54-[SKGDataDetector _callPIRWithQuery:hitError:useCase:]_block_invoke
- ___block_descriptor_112_e8_32s40bs48r56r64r72r80r88r96r_e17_v16?0"NSError"8lr48l8s40l8r56l8r64l8s32l8r72l8r80l8r88l8r96l8
- ___block_descriptor_56_e8_32s40s48bs_e29_v24?0"NSArray"8"NSError"16ls32l8s40l8s48l8
- ___block_descriptor_56_e8_32s40s48bs_e39_v24?0"SKDEntityLocation"8"NSError"16ls32l8s48l8s40l8
- ___block_descriptor_64_e8_32s40bs48r56r_e17_v16?0"NSError"8ls40l8r48l8r56l8s32l8
- ___block_descriptor_72_e8_32s40bs48r56r64r_e17_v16?0"NSError"8ls40l8r48l8r56l8s32l8r64l8
- ___block_descriptor_80_e8_32s40bs48r56r64r_e17_v16?0"NSError"8ls40l8r48l8r56l8s32l8r64l8
- ___block_descriptor_80_e8_32s40s48bs56r64r72r_e17_v16?0"NSError"8ls48l8s32l8r56l8s40l8r64l8r72l8
- ___block_descriptor_96_e8_32s40s48bs56r64r72r80r_e17_v16?0"NSError"8ls48l8r56l8s32l8r64l8s40l8r72l8r80l8
- ___block_descriptor_96_e8_32s40s48s56s64s72bs80r88r_e17_v16?0"NSError"8lr80l8s72l8s32l8s40l8s48l8r88l8s56l8s64l8
- ___swift_exist.box.addr_destructor.786Tm
- _pipelineIndexFromName.map
- _pipelineIndexFromName.onceToken
CStrings:
+ "SKDAnalyticsLogger: merged cell table saturated at %{public}lu cells; some (processor, context, language, textSize) cells were not reported"
+ "SKDAnalyticsLogger: model cell table saturated at %{public}lu cells; some (model, context, language, textSize) cells were not reported"
+ "SKDDataDetectorsProcessor"
+ "SKDKeyphrasesProcessor"
+ "SKDLocationResolutionProcessor"
+ "SKDTextEmbeddingProcessor"
+ "[GLPInsightsEmbeddingProcessor] Passing through item in set %hu"
+ "[ModelCatalog] AEM version modified, %s to %ld. Requesting MD%ld. Posting notification"
+ "contextName"
+ "glpInsightsEmbedding"
+ "itemCount"
+ "languageType"
+ "modelCount"
+ "modelName"
+ "resultCount"
+ "textContentSize"
- "[ModelCatalog] AEM version modified, %ld to %ld. Posting notification"
- "skd_batch_summary"
- "skd_error_summary"
- "skd_process_summary"
```
