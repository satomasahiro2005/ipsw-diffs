## WorkflowKit

> `/System/Library/PrivateFrameworks/WorkflowKit.framework/WorkflowKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8a88a0` | `0x8bd7d4` | **`+0x14f34`** |
| `__AUTH_CONST.__const` | `0x3aee0` | `0x3dc20` | **`+0x2d40`** |
| `__TEXT.__swift5_capture` | `0x42f4` | `0x53c0` | **`+0x10cc`** |
| `__TEXT.__oslogstring` | `0x20714` | `0x21577` | **`+0xe63`** |
| `__DATA.__bss` | `0x2cee8` | `0x2dcd8` | **`+0xdf0`** |
| `__TEXT.__const` | `0x22a08` | `0x234d8` | **`+0xad0`** |
| `__TEXT.__cstring` | `0x8b049` | `0x8babc` | **`+0xa73`** |
| `__TEXT.__eh_frame` | `0x22644` | `0x21da8` | **`-0x89c`** |
| `__AUTH_CONST.__objc_const` | `0x541a8` | `0x54740` | **`+0x598`** |
| `__TEXT.__swift5_typeref` | `0xc58e` | `0xcb16` | **`+0x588`** |
| `__TEXT.__constg_swiftt` | `0x90f8` | `0x93f0` | **`+0x2f8`** |
| `__TEXT.__swift5_fieldmd` | `0x715c` | `0x7400` | **`+0x2a4`** |
| `__DATA.__data` | `0xcfe8` | `0xd278` | **`+0x290`** |
| `__TEXT.__unwind_info` | `0x1b0c8` | `0x1b320` | **`+0x258`** |
| `__AUTH.__data` | `0x6d58` | `0x6f88` | **`+0x230`** |
| `__TEXT.__objc_methlist` | `0x2df58` | `0x2e15c` | **`+0x204`** |
| `__TEXT.__swift5_reflstr` | `0x5d38` | `0x5ed8` | **`+0x1a0`** |
| `__AUTH.__objc_data` | `0x109e8` | `0x10b00` | **`+0x118`** |
| `__DATA_CONST.__objc_selrefs` | `0x13338` | `0x13440` | **`+0x108`** |
| `__TEXT.__swift_as_cont` | `0x1474` | `0x13cc` | **`-0xa8`** |
| `__AUTH_CONST.__auth_got` | `0x4ef8` | `0x4f78` | **`+0x80`** |
| `__DATA_CONST.__const` | `0xefe8` | `0xef70` | **`-0x78`** |
| `__TEXT.__swift5_proto` | `0x195c` | `0x19d0` | **`+0x74`** |
| `__TEXT.__swift5_assocty` | `0x2230` | `0x2290` | **`+0x60`** |
| `__TEXT.__swift_as_ret` | `0xc54` | `0xc00` | **`-0x54`** |
| `__AUTH_CONST.__cfstring` | `0x2b460` | `0x2b4a0` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x4c90` | `0x4cd0` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x5ac8` | `0x5a98` | **`-0x30`** |
| `__TEXT.__swift5_types` | `0xaa0` | `0xacc` | **`+0x2c`** |
| `__DATA_CONST.__objc_classlist` | `0x2390` | `0x23b0` | **`+0x20`** |
| `__DATA_DIRTY.__objc_data` | `0x8d70` | `0x8d90` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0xacc` | `0xab0` | **`-0x1c`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x978` | `0x960` | **`-0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0xf78` | `0xf90` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x20ec` | `0x2104` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x654` | `0x668` | **`+0x14`** |
| `__DATA_CONST.__objc_arraydata` | `0x16e0` | `0x16d8` | **`-0x8`** |
| `__DATA_CONST.__objc_catlist` | `0x3e0` | `0x3e8` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1348` | `0x1350` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x12c` | `0x134` | **`+0x8`** |

### Other Changes

```diff

-5025.0.25.103.0
+5028.0.21.0.0

-  Functions: 42262
-  Symbols:   34700
-  CStrings:  17619
+  Functions: 42712
+  Symbols:   34847
+  CStrings:  17718
Symbols:
+ +[NSUserDefaults(Workflow) summarizeShortcutEnabled]
+ +[NSUserDefaults(Workflow) toolKitImmediateIndexingStaleRunTimeout]
+ +[WFCloudKitStoredValue inlineItemSizeLimit]
+ +[WFCloudKitStoredValue inlineTotalSizeLimit]
+ +[WFTriggerMetricsEmitter trackTriggeredAutomationForKey:shouldPrompt:triggerClassName:]
+ +[WFWorkflow keyPathsForValuesAffectingEligibleForAutomaticDeletion]
+ +[WFWorkoutType activityTypeNameForActivityType:]
+ -[LNActionMetadata(Workflow) wf_isDeletionAction]
+ -[LNActionSideEffect(Workflow) wf_isDeletion]
+ -[WFBackgroundShortcutRunner hydrateEncodedRemoteHydrationRequest:completionHandler:]
+ -[WFDatabase(RunEvents) latestRunEventForLegacyTriggerIdentifier:]
+ -[WFDatabase(RunEvents) sortedRunEventsForWorkflowID:triggerID:]
+ -[WFDatabase(TrackedFilesystemNode) trackedFilesystemNodeForTriggerKey:]
+ -[WFDatabase(Triggers) createTriggerEventForTriggerKey:eventInfo:confirmed:paused:error:]
+ -[WFDatabase(Triggers) triggerEventsForUnifiedTrigger:]
+ -[WFEnumerationParameter variableProviderForDialogResponse]
+ -[WFFiniteRepeatAction .cxx_destruct]
+ -[WFInterchangeAppRegistry init]
+ -[WFLinkDynamicOptionsEnumerationParameter variableProviderForDialogResponse]
+ -[WFLinkShortcutsDeleteAlbumAction runAsynchronouslyWithInput:]
+ -[WFTriggerEvent initWithIdentifier:triggerID:workflowID:eventInfo:confirmed:paused:dateCreated:]
+ -[WFTriggerEvent workflowID]
+ -[WFTriggerInputVariable .cxx_destruct]
+ -[WFTriggerInputVariable icon]
+ -[WFTriggerInputVariable initWithDictionary:variableProvider:]
+ -[WFTriggerInputVariable initWithVariableProvider:aggrandizements:]
+ -[WFTriggerInputVariable initWithVariableProvider:triggerIdentifier:aggrandizements:]
+ -[WFTriggerInputVariable isAvailable]
+ -[WFTriggerInputVariable name]
+ -[WFTriggerInputVariable possibleContentClasses]
+ -[WFTriggerInputVariable retrieveContentCollectionWithVariableSource:completionHandler:]
+ -[WFTriggerInputVariable supportsCoercion]
+ -[WFTriggerInputVariable triggerIdentifier]
+ -[WFTriggerInputVariable variableProvider]
+ -[WFVariable supportsCoercion]
+ -[WFWorkflow databaseResultDidChange:]
+ -[WFWorkflow hasStoredValues]
+ -[WFWorkflow insertTrigger:atIndex:]
+ -[WFWorkflow setHasStoredValues:]
+ -[WFWorkflow setStoredValuesResult:]
+ -[WFWorkflow storedValuesResult]
+ -[WFWorkflow updateStoredValuesObserver]
+ -[WFWorkflowImportQuestion initWithSerializedRepresentation:workflowActions:workflowTriggers:]
+ -[WFWorkflowImportQuestion initWithTrigger:parameter:question:defaultState:]
+ -[WFWorkflowImportQuestion trigger]
+ GCC_except_table10095
+ GCC_except_table10114
+ GCC_except_table10279
+ GCC_except_table10314
+ GCC_except_table10387
+ GCC_except_table10389
+ GCC_except_table10391
+ GCC_except_table10431
+ GCC_except_table10436
+ GCC_except_table10476
+ GCC_except_table10479
+ GCC_except_table10482
+ GCC_except_table10485
+ GCC_except_table10672
+ GCC_except_table10774
+ GCC_except_table10791
+ GCC_except_table10807
+ GCC_except_table10853
+ GCC_except_table11097
+ GCC_except_table11124
+ GCC_except_table11127
+ GCC_except_table11143
+ GCC_except_table11203
+ GCC_except_table11346
+ GCC_except_table11455
+ GCC_except_table11458
+ GCC_except_table11461
+ GCC_except_table11469
+ GCC_except_table11474
+ GCC_except_table11481
+ GCC_except_table11516
+ GCC_except_table11519
+ GCC_except_table11522
+ GCC_except_table11628
+ GCC_except_table11783
+ GCC_except_table11799
+ GCC_except_table11993
+ GCC_except_table12008
+ GCC_except_table12014
+ GCC_except_table12016
+ GCC_except_table12021
+ GCC_except_table12053
+ GCC_except_table12066
+ GCC_except_table12073
+ GCC_except_table12128
+ GCC_except_table1215
+ GCC_except_table12167
+ GCC_except_table12181
+ GCC_except_table12183
+ GCC_except_table12185
+ GCC_except_table12276
+ GCC_except_table12292
+ GCC_except_table12397
+ GCC_except_table12449
+ GCC_except_table12504
+ GCC_except_table12533
+ GCC_except_table12589
+ GCC_except_table12600
+ GCC_except_table12645
+ GCC_except_table12647
+ GCC_except_table12842
+ GCC_except_table12876
+ GCC_except_table1292
+ GCC_except_table12995
+ GCC_except_table13023
+ GCC_except_table13029
+ GCC_except_table13078
+ GCC_except_table13119
+ GCC_except_table13132
+ GCC_except_table13137
+ GCC_except_table13158
+ GCC_except_table13159
+ GCC_except_table13169
+ GCC_except_table13180
+ GCC_except_table13335
+ GCC_except_table13371
+ GCC_except_table13376
+ GCC_except_table13378
+ GCC_except_table13381
+ GCC_except_table13441
+ GCC_except_table13453
+ GCC_except_table13457
+ GCC_except_table13692
+ GCC_except_table13760
+ GCC_except_table13959
+ GCC_except_table1397
+ GCC_except_table14000
+ GCC_except_table1402
+ GCC_except_table14129
+ GCC_except_table14232
+ GCC_except_table14237
+ GCC_except_table14246
+ GCC_except_table14249
+ GCC_except_table14314
+ GCC_except_table14348
+ GCC_except_table14350
+ GCC_except_table14363
+ GCC_except_table14477
+ GCC_except_table14615
+ GCC_except_table14636
+ GCC_except_table14647
+ GCC_except_table14661
+ GCC_except_table14664
+ GCC_except_table14851
+ GCC_except_table14878
+ GCC_except_table14973
+ GCC_except_table1578
+ GCC_except_table1582
+ GCC_except_table1584
+ GCC_except_table1586
+ GCC_except_table1657
+ GCC_except_table1676
+ GCC_except_table1678
+ GCC_except_table1680
+ GCC_except_table1945
+ GCC_except_table2021
+ GCC_except_table2104
+ GCC_except_table2114
+ GCC_except_table2323
+ GCC_except_table2333
+ GCC_except_table2338
+ GCC_except_table2366
+ GCC_except_table249
+ GCC_except_table253
+ GCC_except_table2537
+ GCC_except_table2564
+ GCC_except_table2635
+ GCC_except_table264
+ GCC_except_table2671
+ GCC_except_table273
+ GCC_except_table2779
+ GCC_except_table2782
+ GCC_except_table2796
+ GCC_except_table2863
+ GCC_except_table2890
+ GCC_except_table2907
+ GCC_except_table2913
+ GCC_except_table2965
+ GCC_except_table2991
+ GCC_except_table3019
+ GCC_except_table3062
+ GCC_except_table3364
+ GCC_except_table3395
+ GCC_except_table3396
+ GCC_except_table3397
+ GCC_except_table3398
+ GCC_except_table3422
+ GCC_except_table3426
+ GCC_except_table3451
+ GCC_except_table3456
+ GCC_except_table3489
+ GCC_except_table3505
+ GCC_except_table3509
+ GCC_except_table3569
+ GCC_except_table3580
+ GCC_except_table3582
+ GCC_except_table3585
+ GCC_except_table3695
+ GCC_except_table3699
+ GCC_except_table3701
+ GCC_except_table3705
+ GCC_except_table3706
+ GCC_except_table375
+ GCC_except_table3845
+ GCC_except_table3971
+ GCC_except_table3975
+ GCC_except_table4353
+ GCC_except_table4354
+ GCC_except_table4472
+ GCC_except_table4559
+ GCC_except_table4572
+ GCC_except_table4591
+ GCC_except_table4599
+ GCC_except_table4748
+ GCC_except_table4944
+ GCC_except_table5005
+ GCC_except_table5019
+ GCC_except_table5077
+ GCC_except_table5148
+ GCC_except_table5175
+ GCC_except_table5179
+ GCC_except_table5223
+ GCC_except_table5283
+ GCC_except_table5292
+ GCC_except_table5314
+ GCC_except_table5354
+ GCC_except_table5410
+ GCC_except_table5415
+ GCC_except_table5417
+ GCC_except_table5521
+ GCC_except_table5543
+ GCC_except_table558
+ GCC_except_table5870
+ GCC_except_table6016
+ GCC_except_table6049
+ GCC_except_table6123
+ GCC_except_table6135
+ GCC_except_table6246
+ GCC_except_table6324
+ GCC_except_table6392
+ GCC_except_table6393
+ GCC_except_table6394
+ GCC_except_table6494
+ GCC_except_table650
+ GCC_except_table6541
+ GCC_except_table6559
+ GCC_except_table6580
+ GCC_except_table680
+ GCC_except_table685
+ GCC_except_table691
+ GCC_except_table6918
+ GCC_except_table6931
+ GCC_except_table6940
+ GCC_except_table6972
+ GCC_except_table7023
+ GCC_except_table7024
+ GCC_except_table7030
+ GCC_except_table7033
+ GCC_except_table7039
+ GCC_except_table7050
+ GCC_except_table7089
+ GCC_except_table7152
+ GCC_except_table7163
+ GCC_except_table7226
+ GCC_except_table7227
+ GCC_except_table7436
+ GCC_except_table7446
+ GCC_except_table7523
+ GCC_except_table7533
+ GCC_except_table7596
+ GCC_except_table7773
+ GCC_except_table7816
+ GCC_except_table7863
+ GCC_except_table7864
+ GCC_except_table7904
+ GCC_except_table8035
+ GCC_except_table8172
+ GCC_except_table8177
+ GCC_except_table8188
+ GCC_except_table8302
+ GCC_except_table8309
+ GCC_except_table8320
+ GCC_except_table8378
+ GCC_except_table8389
+ GCC_except_table8391
+ GCC_except_table8393
+ GCC_except_table852
+ GCC_except_table8915
+ GCC_except_table8964
+ GCC_except_table8966
+ GCC_except_table8968
+ GCC_except_table8997
+ GCC_except_table9039
+ GCC_except_table9137
+ GCC_except_table9189
+ GCC_except_table926
+ GCC_except_table935
+ GCC_except_table9401
+ GCC_except_table9407
+ GCC_except_table9409
+ GCC_except_table9413
+ GCC_except_table9415
+ GCC_except_table9417
+ GCC_except_table9419
+ GCC_except_table9423
+ GCC_except_table9425
+ GCC_except_table9437
+ GCC_except_table9441
+ GCC_except_table9454
+ GCC_except_table9467
+ GCC_except_table9473
+ GCC_except_table9481
+ GCC_except_table9528
+ GCC_except_table9534
+ GCC_except_table9540
+ GCC_except_table9676
+ GCC_except_table968
+ GCC_except_table9735
+ GCC_except_table9762
+ GCC_except_table9770
+ GCC_except_table9772
+ GCC_except_table9774
+ GCC_except_table9781
+ GCC_except_table9802
+ GCC_except_table9803
+ GCC_except_table9804
+ GCC_except_table9806
+ GCC_except_table9811
+ GCC_except_table9919
+ _CFAbsoluteTimeGetCurrent
+ _OBJC_CLASS_$_BMAppInFocus
+ _OBJC_CLASS_$_BMContextSyncWorkout
+ _OBJC_CLASS_$_BMHealthWorkout
+ _OBJC_CLASS_$_LNActionSideEffect
+ _OBJC_CLASS_$_WFTriggerInputVariable
+ _OBJC_CLASS_$_WFUnifiedTriggerKey
+ _OBJC_IVAR_$_WFFiniteRepeatAction._countParameterAttributionSet
+ _OBJC_IVAR_$_WFTriggerEvent._workflowID
+ _OBJC_IVAR_$_WFTriggerInputVariable._variableProvider
+ _OBJC_IVAR_$_WFWorkflow._hasStoredValues
+ _OBJC_IVAR_$_WFWorkflow._storedValuesResult
+ _OBJC_IVAR_$_WFWorkflowImportQuestion._trigger
+ _OBJC_METACLASS_$_WFLegacyStoredValueItemLocation
+ _OBJC_METACLASS_$_WFLegacyStoredValueManifestEntry
+ _OBJC_METACLASS_$_WFTriggerInputVariable
+ _OBJC_METACLASS_$_WFUnifiedTriggerKey
+ _OUTLINED_FUNCTION_442
+ _OUTLINED_FUNCTION_443
+ _OUTLINED_FUNCTION_444
+ _OUTLINED_FUNCTION_445
+ _OUTLINED_FUNCTION_446
+ _OUTLINED_FUNCTION_447
+ _OUTLINED_FUNCTION_448
+ _OUTLINED_FUNCTION_449
+ _OUTLINED_FUNCTION_450
+ _OUTLINED_FUNCTION_451
+ _OUTLINED_FUNCTION_452
+ _OUTLINED_FUNCTION_453
+ _OUTLINED_FUNCTION_454
+ _OUTLINED_FUNCTION_455
+ _OUTLINED_FUNCTION_456
+ _OUTLINED_FUNCTION_457
+ _OUTLINED_FUNCTION_458
+ _OUTLINED_FUNCTION_459
+ _OUTLINED_FUNCTION_460
+ _OUTLINED_FUNCTION_461
+ _OUTLINED_FUNCTION_462
+ _OUTLINED_FUNCTION_463
+ _OUTLINED_FUNCTION_464
+ _OUTLINED_FUNCTION_465
+ _OUTLINED_FUNCTION_466
+ _OUTLINED_FUNCTION_467
+ _OUTLINED_FUNCTION_468
+ _OUTLINED_FUNCTION_469
+ _OUTLINED_FUNCTION_470
+ _OUTLINED_FUNCTION_471
+ _OUTLINED_FUNCTION_472
+ _OUTLINED_FUNCTION_473
+ _OUTLINED_FUNCTION_474
+ _WFClipboardItemBaseName
+ _WFResourceRequiredResourcesKey
+ _WFSummarizeShortcutEnabledKey
+ _WFSystemNotificationIdentifierIsForTrigger
+ _WFToolKitImmediateIndexingStaleRunTimeoutKey
+ _WFTriggerInputVariableTriggerIdentifierKey
+ _WFTriggerKeyFromNotificationUserInfo
+ _WFTriggerKeysToDisableFromNotificationUserInfo
+ _WFTriggerSystemNotificationIdentifier
+ _WFVariableTypeTriggerInput
+ __CLASS_METHODS_WFLegacyStoredValueItemLocation
+ __CLASS_METHODS_WFLegacyStoredValueManifestEntry
+ __CLASS_PROPERTIES_WFLegacyStoredValueItemLocation
+ __CLASS_PROPERTIES_WFLegacyStoredValueManifestEntry
+ __DATA_WFLegacyStoredValueItemLocation
+ __DATA_WFLegacyStoredValueManifestEntry
+ __DATA_WFUnifiedTriggerKey
+ __DATA__TtC11WorkflowKit24AppIntentsRemoteHydrator
+ __DATA__TtC11WorkflowKit27ImmediateIndexingController
+ __INSTANCE_METHODS_WFLegacyStoredValueItemLocation
+ __INSTANCE_METHODS_WFLegacyStoredValueManifestEntry
+ __INSTANCE_METHODS_WFUnifiedTriggerKey
+ __IVARS_WFLegacyStoredValueItemLocation
+ __IVARS_WFLegacyStoredValueManifestEntry
+ __IVARS_WFUnifiedTriggerKey
+ __IVARS__TtC11WorkflowKit27ImmediateIndexingController
+ __METACLASS_DATA_WFLegacyStoredValueItemLocation
+ __METACLASS_DATA_WFLegacyStoredValueManifestEntry
+ __METACLASS_DATA_WFUnifiedTriggerKey
+ __METACLASS_DATA__TtC11WorkflowKit24AppIntentsRemoteHydrator
+ __METACLASS_DATA__TtC11WorkflowKit27ImmediateIndexingController
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_LNActionSideEffect_$_Workflow
+ __OBJC_$_CATEGORY_LNActionSideEffect_$_Workflow
+ __OBJC_$_CLASS_METHODS_WFTriggerInputVariable(WorkflowKit)
+ __OBJC_$_INSTANCE_METHODS_WFAppInFocusTrigger
+ __OBJC_$_INSTANCE_METHODS_WFTimeZonePickerParameter(WorkflowKit)
+ __OBJC_$_INSTANCE_METHODS_WFTriggerInputVariable(WorkflowKit)
+ __OBJC_$_INSTANCE_METHODS_WFWorkoutTrigger
+ __OBJC_$_INSTANCE_METHODS__TtC11WorkflowKit12WFNewTrigger(WorkflowKit|WorkflowKit1|WorkflowKit2|WorkflowKit3|WorkflowKit4|SourceExport|CatalogEntryProviderDelegate)
+ __OBJC_$_INSTANCE_VARIABLES_WFTriggerInputVariable
+ __OBJC_$_PROP_LIST_LNActionSideEffect_$_Workflow
+ __OBJC_CLASS_PROTOCOLS_$__TtC11WorkflowKit12WFNewTrigger(WorkflowKit|WorkflowKit1|WorkflowKit2|WorkflowKit3|WorkflowKit4|SourceExport|CatalogEntryProviderDelegate)
+ __OBJC_CLASS_RO_$_WFTriggerInputVariable
+ __OBJC_METACLASS_RO_$_WFTriggerInputVariable
+ __PROPERTIES_WFUnifiedTriggerKey
+ __PROTOCOLS_WFLegacyStoredValueItemLocation
+ __PROTOCOLS_WFLegacyStoredValueManifestEntry
+ __PROTOCOLS_WFUnifiedTriggerKey
+ ___43-[WFWorkflow setUnifiedAutomationTriggers:]_block_invoke_2
+ ___66-[WFDatabase(RunEvents) latestRunEventForLegacyTriggerIdentifier:]_block_invoke
+ ___89-[WFDatabase(Triggers) createTriggerEventForTriggerKey:eventInfo:confirmed:paused:error:]_block_invoke
+ ___WFTriggerKeysToDisableFromNotificationUserInfo_block_invoke
+ ___block_descriptor_32_e46_"WFUnifiedTriggerKey"24?0"NSDictionary"8Q16l
+ ___block_descriptor_56_e8_32s_e26_"NSMutableDictionary"8?0ls32l8
+ ___block_descriptor_72_e8_32s40s48s56bs_e82_v40?0"NSData"8"PBSecurityScopedURLWrapper"16"PBResponseMetadata"24"NSError"32ls32l8s40l8s48l8s56l8
+ ___block_descriptor_80_e8_32s40s_e26_"NSMutableDictionary"8?0ls32l8s40l8
+ ___getCNContactImageDataKeySymbolLoc_block_invoke
+ ___swift_closure_destructor.11Tm
+ ___swift_closure_destructor.136Tm
+ ___swift_closure_destructor.51Tm
+ ___swift_closure_destructor.70Tm
+ ___swift_closure_destructor.81Tm
+ ___swift_closure_destructor.88Tm
+ ___swift_exist.box.addr_destructor.166Tm
+ ___swift_exist.box.addr_destructor.195Tm
+ ___swift_exist.box.addr_destructor.208Tm
+ ___swift_memcpy66_8
+ _associated conformance 11WorkflowKit12WFNewTriggerC22EnablementParameterKeyOSHAASQ
+ _associated conformance 11WorkflowKit12WFNewTriggerC22EnablementParameterKeyOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 11WorkflowKit19StoredValueManifestV11DecodeErrorOSHAASQ
+ _associated conformance 11WorkflowKit20DateFilterComparisonO27LessThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLOs0K3KeyAAs23CustomStringConvertible
+ _associated conformance 11WorkflowKit20DateFilterComparisonO27LessThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLOs0K3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 11WorkflowKit20DateFilterComparisonO30GreaterThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLOs0K3KeyAAs23CustomStringConvertible
+ _associated conformance 11WorkflowKit20DateFilterComparisonO30GreaterThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLOs0K3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 11WorkflowKit32RowTemplateDateOrderedComparisonO27LessThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLOs0M3KeyAAs23CustomStringConvertible
+ _associated conformance 11WorkflowKit32RowTemplateDateOrderedComparisonO27LessThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLOs0M3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 11WorkflowKit32RowTemplateDateOrderedComparisonO30GreaterThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLOs0M3KeyAAs23CustomStringConvertible
+ _associated conformance 11WorkflowKit32RowTemplateDateOrderedComparisonO30GreaterThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLOs0M3KeyAAs28CustomDebugStringConvertible
+ _associated conformance So13WFResourceKeyaSHSCSQ
+ _associated conformance So13WFResourceKeyas20_SwiftNewtypeWrapperSCSY
+ _associated conformance So13WFResourceKeyas20_SwiftNewtypeWrapperSCs35_HasCustomAnyHashableRepresentation
+ _associated conformance So14WFAlarmTriggerC11WorkflowKitE013registerAlarmB07trigger3key5storeAC0B12RegistrationOAC05WFNewB0C_So09WFUnifiedB3KeyCAC0bJ5Store_ptKFZySo12BMStoreEventCySo07BMClockF0CGcfU_0F4TypeL_OSHACSQ
+ _getCNContactImageDataKeySymbolLoc.ptr
+ _get_enum_tag_for_layout_string 11WorkflowKit12WFNewTriggerCSo09WFUnifiedD3KeyCSo10WFDatabaseCSbIeggggd_Sg
+ _get_type_metadata 15Synchronization5MutexVy11WorkflowKit13RunnerIndexerC0cE8Delegate33_A6249030EA81EF6713EE32E4D497DC1DLLC5StateOG noncopyable
+ _get_type_metadata 15Synchronization5MutexVySay11WorkflowKit12WFNewTriggerCGG noncopyable
+ _get_type_metadata 15Synchronization5MutexVySo32WFOutOfProcessWorkflowControllerCSgG noncopyable
+ _init_HKWorkoutActivityNameForActivityType
+ _softLink_HKWorkoutActivityNameForActivityType
+ _symbolic $s11WorkflowKit17WFResourceContentP
+ _symbolic $s11WorkflowKit25AppShortcutBundleProviderP
+ _symbolic $s11WorkflowKit27AppIntentsIndexingReadinessP
+ _symbolic SDySSSdGz_Xx
+ _symbolic SDySo19WFUnifiedTriggerKeyCSSG
+ _symbolic SDySo19WFUnifiedTriggerKeyCSo31_CDContextualChangeRegistrationCG
+ _symbolic SDySo19WFUnifiedTriggerKeyCSo7BPSSinkCyyXlGG
+ _symbolic SDy_____ypG So13WFResourceKeya
+ _symbolic SS______So19WFUnifiedTriggerKeyCSo10WFDatabaseCtc 11WorkflowKit12WFNewTriggerC
+ _symbolic SaySDy_____ypGG So13WFResourceKeya
+ _symbolic SaySo14WFResourceNodeCG
+ _symbolic SaySo20WFFileRepresentationCG
+ _symbolic Say_____2id_ScCyyt______pG12continuationtG s6UInt64V s5ErrorP
+ _symbolic Say_____G 10Foundation4DataV
+ _symbolic Say_____G 11WorkflowKit12WFNewTriggerC22EnablementParameterKeyO
+ _symbolic Say_____G 11WorkflowKit23StoredValueItemLocationV
+ _symbolic Say_____G 11WorkflowKit24StoredValueManifestEntryV
+ _symbolic Say_____G 11WorkflowKit29LegacyStoredValueItemLocation33_B7209B6CAE1CA3931692A2FD2B1DA6E5LLC
+ _symbolic Say_____G 11WorkflowKit30LegacyStoredValueManifestEntry33_B7209B6CAE1CA3931692A2FD2B1DA6E5LLC
+ _symbolic Say______pG 11WorkflowKit17WFResourceContentP
+ _symbolic Sb______So19WFUnifiedTriggerKeyCSo10WFDatabaseCtcSg 11WorkflowKit12WFNewTriggerC
+ _symbolic SdIegd_
+ _symbolic Shy_____GIegr_ 16GenerativeModels0aB12AvailabilityV0C0O15UnavailableInfoV0D6ReasonO
+ _symbolic So10CKRecordIDC
+ _symbolic So12BMStoreEventCySo12BMAppInFocusCGIegg_
+ _symbolic So12BMStoreEventCySo15BMHealthWorkoutCGIegg_
+ _symbolic So12BMStoreEventCySo20BMContextSyncWorkoutCGIegg_
+ _symbolic So18LNMetadataProviderC
+ _symbolic So19WFUnifiedTriggerKeyC
+ _symbolic So27WFAppShortcutNamedQueryInfoCSg3key_Say_____ySo015WFExecutableAppB0CGG5valuet 11WorkflowKit18RunnableCollectionV
+ _symbolic So32WFOutOfProcessWorkflowControllerCSg
+ _symbolic _____ 11WorkflowKit12WFNewTriggerC22EnablementParameterKeyO
+ _symbolic _____ 11WorkflowKit13RunnerIndexerC0aC8Delegate33_A6249030EA81EF6713EE32E4D497DC1DLLC5StateO
+ _symbolic _____ 11WorkflowKit19StoredValueManifestV
+ _symbolic _____ 11WorkflowKit19StoredValueManifestV11DecodeErrorO
+ _symbolic _____ 11WorkflowKit20DateFilterComparisonO27LessThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLO
+ _symbolic _____ 11WorkflowKit20DateFilterComparisonO30GreaterThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLO
+ _symbolic _____ 11WorkflowKit23StoredValueItemLocationV
+ _symbolic _____ 11WorkflowKit24AppIntentsRemoteHydratorC
+ _symbolic _____ 11WorkflowKit24StoredValueManifestEntryV
+ _symbolic _____ 11WorkflowKit27ImmediateIndexingControllerC
+ _symbolic _____ 11WorkflowKit29LegacyStoredValueItemLocation33_B7209B6CAE1CA3931692A2FD2B1DA6E5LLC
+ _symbolic _____ 11WorkflowKit30LegacyStoredValueManifestEntry33_B7209B6CAE1CA3931692A2FD2B1DA6E5LLC
+ _symbolic _____ 11WorkflowKit32RowTemplateDateOrderedComparisonO27LessThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLO
+ _symbolic _____ 11WorkflowKit32RowTemplateDateOrderedComparisonO30GreaterThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLO
+ _symbolic _____ 11WorkflowKit35LNMetadataProviderIndexingReadinessV
+ _symbolic _____ 16GenerativeModels0aB12AvailabilityV0C0O15UnavailableInfoV
+ _symbolic _____ 2os12OSSignposterV
+ _symbolic _____ 2os6LoggerV
+ _symbolic _____ So13WFResourceKeya
+ _symbolic _____ So14WFAlarmTriggerC11WorkflowKitE013registerAlarmB07trigger3key5storeAC0B12RegistrationOAC05WFNewB0C_So09WFUnifiedB3KeyCAC0bJ5Store_ptKFZySo12BMStoreEventCySo07BMClockF0CGcfU_0F4TypeL_O
+ _symbolic _____ So24BMHealthWorkoutEventTypeV
+ _symbolic _____ s5UInt8V
+ _symbolic _____ s6UInt64V
+ _symbolic _____2id_ScCyyt______pG12continuationt s6UInt64V s5ErrorP
+ _symbolic _____Sg 11WorkflowKit14IndexingResultV
+ _symbolic _____SgXw 11WorkflowKit04ToolB13IndexingQueueC
+ _symbolic _____SgXw 11WorkflowKit27ImmediateIndexingControllerC
+ _symbolic _____SgXwz_Xx 11WorkflowKit04ToolB13IndexingQueueC
+ _symbolic _____SgXwz_Xx 11WorkflowKit27ImmediateIndexingControllerC
+ _symbolic _____So19WFUnifiedTriggerKeyCSo10WFDatabaseCSSIeggggo_ 11WorkflowKit12WFNewTriggerC
+ _symbolic _____So19WFUnifiedTriggerKeyCSo10WFDatabaseCSSIegnnnr_ 11WorkflowKit12WFNewTriggerC
+ _symbolic _____So19WFUnifiedTriggerKeyCSo10WFDatabaseCSbIeggggd_ 11WorkflowKit12WFNewTriggerC
+ _symbolic _____So19WFUnifiedTriggerKeyCSo10WFDatabaseCSbIegnnnr_ 11WorkflowKit12WFNewTriggerC
+ _symbolic _____So19WFUnifiedTriggerKeyC______p___________pIegggnrzo_ 11WorkflowKit12WFNewTriggerC AA0D17RegistrationStoreP AA0dE0O s5ErrorP
+ _symbolic _____So19WFUnifiedTriggerKeyC______p___________pIegnnnrzo_ 11WorkflowKit12WFNewTriggerC AA0D17RegistrationStoreP AA0dE0O s5ErrorP
+ _symbolic ______AAt So14WFAlarmTriggerC11WorkflowKitE013registerAlarmB07trigger3key5storeAC0B12RegistrationOAC05WFNewB0C_So09WFUnifiedB3KeyCAC0bJ5Store_ptKFZySo12BMStoreEventCySo07BMClockF0CGcfU_0F4TypeL_O
+ _symbolic ___________So19WFUnifiedTriggerKeyC______ptKc 11WorkflowKit19TriggerRegistrationO AA05WFNewC0C AA0cD5StoreP
+ _symbolic ___________pIeghHyzo_ s6UInt64V s5ErrorP
+ _symbolic ______p 11WorkflowKit17WFResourceContentP
+ _symbolic ______p 11WorkflowKit25AppShortcutBundleProviderP
+ _symbolic ______p 11WorkflowKit27AppIntentsIndexingReadinessP
+ _symbolic _____ySDy_____ypGG s23_ContiguousArrayStorageC So13WFResourceKeya
+ _symbolic _____ySS_____G s17_NativeDictionaryV 11WorkflowKit36WFUnifiedAutomationTriggerEnablementO
+ _symbolic _____ySay_____GG 15Synchronization5MutexVAARi_zrlE 11WorkflowKit12WFNewTriggerC
+ _symbolic _____yScCy___________pGG s23_ContiguousArrayStorageC 11WorkflowKit14IndexingResultV s5ErrorP
+ _symbolic _____ySo19WFUnifiedTriggerKeyCSSG s17_NativeDictionaryV
+ _symbolic _____ySo19WFUnifiedTriggerKeyCSo31_CDContextualChangeRegistrationCG s17_NativeDictionaryV
+ _symbolic _____ySo19WFUnifiedTriggerKeyCSo31_CDContextualChangeRegistrationCG s18_DictionaryStorageC
+ _symbolic _____ySo19WFUnifiedTriggerKeyCSo7BPSSinkCG s17_NativeDictionaryV
+ _symbolic _____ySo19WFUnifiedTriggerKeyCSo7BPSSinkCG s18_DictionaryStorageC
+ _symbolic _____ySo27WFAppShortcutNamedQueryInfoCSg3key_Say_____ySo015WFExecutableAppB0CGG5valuetG s23_ContiguousArrayStorageC 11WorkflowKit18RunnableCollectionV
+ _symbolic _____ySo32WFOutOfProcessWorkflowControllerCSgG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____y_____2id_ScCyyt______pG12continuationtG s23_ContiguousArrayStorageC s6UInt64V s5ErrorP
+ _symbolic _____y_____G 11WorkflowKit25OrderedComparisonOperatorV AA49RowTemplateCompoundNumberMeasurementUnitValueTypeV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 11WorkflowKit13RunnerIndexerC0cE8Delegate33_A6249030EA81EF6713EE32E4D497DC1DLLC5StateO
+ _symbolic _____y_____G 15Synchronization5_CellVAARi_zrlE 11WorkflowKit13RunnerIndexerC0cE8Delegate33_A6249030EA81EF6713EE32E4D497DC1DLLC5StateO
+ _symbolic _____y_____G s11_SetStorageC So14WFAlarmTriggerC11WorkflowKitE013registerAlarmD07trigger3key5storeAE0D12RegistrationOAE05WFNewD0C_So09WFUnifiedD3KeyCAE0dL5Store_ptKFZySo12BMStoreEventCySo07BMClockH0CGcfU_0H4TypeL_O
+ _symbolic _____y_____G s22KeyedDecodingContainerV 11WorkflowKit20DateFilterComparisonO27LessThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 11WorkflowKit20DateFilterComparisonO30GreaterThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 11WorkflowKit32RowTemplateDateOrderedComparisonO27LessThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 11WorkflowKit32RowTemplateDateOrderedComparisonO30GreaterThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 11WorkflowKit20DateFilterComparisonO27LessThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 11WorkflowKit20DateFilterComparisonO30GreaterThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 11WorkflowKit32RowTemplateDateOrderedComparisonO27LessThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 11WorkflowKit32RowTemplateDateOrderedComparisonO30GreaterThanOrEqualToCodingKeys33_38B4027C60F536FCA9E0DB1CA583622FLLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 11WorkflowKit23StoredValueItemLocationV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 11WorkflowKit24StoredValueManifestEntryV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So14WFAlarmTriggerC11WorkflowKitE013registerAlarmE07trigger3key5storeAE0E12RegistrationOAE05WFNewE0C_So09WFUnifiedE3KeyCAE0eM5Store_ptKFZySo12BMStoreEventCySo07BMClockI0CGcfU_0I4TypeL_O
+ _symbolic _____y___________pG s18_DictionaryStorageC So15WFNewTriggerKeya So20WFPropertyListObjectP
+ _symbolic _____y______pG s23_ContiguousArrayStorageC 11WorkflowKit17WFResourceContentP
+ _symbolic _____y______yptG s23_ContiguousArrayStorageC So13WFResourceKeya
+ _symbolic _____yyt______pG s6ResultOsRi_zRi0_zrlE s5ErrorP
+ _symbolic ytSgIeAgHr_
+ _type_layout_string 11WorkflowKit24StoredValueManifestEntryV
- +[WFCloudKitStoredValue inlineDataSizeThreshold]
- +[WFTriggerMetricsEmitter trackTriggeredAutomationForTriggerIdentifier:shouldPrompt:triggerClassName:]
- +[WFTriggerMetricsEmitter trackTriggeredAutomationWithConfiguredTrigger:]
- -[WFAppInFocusTrigger(CoreDuetContext) contextStoreKeyPathForCurrentState]
- -[WFAppInFocusTrigger(CoreDuetContext) contextStorePredicate]
- -[WFAppInFocusTrigger(CoreDuetContext) contextStoreQualityOfService]
- -[WFAppInFocusTrigger(CoreDuetContext) onBackgroundIgnoredLaunchReasons]
- -[WFAppInFocusTrigger(CoreDuetContext) onFocusIgnoredLaunchReasons]
- -[WFAppInFocusTrigger(CoreDuetContext) shouldFireTriggerWithEventInfo:error:]
- -[WFDatabase(RunEvents) sortedRunEventsForTriggerID:]
- -[WFDatabase(TrackedFilesystemNode) trackedFilesystemNodeForTriggerIdentifier:]
- -[WFDatabase(Triggers) createTriggerEventWithTriggerID:eventInfo:confirmed:paused:error:]
- -[WFDatabase(Triggers) triggerEventsForTriggerIdentifier:]
- -[WFTriggerEvent initWithIdentifier:triggerID:eventInfo:confirmed:paused:dateCreated:]
- -[WFWorkflow setIcon:]
- -[WFWorkflowImportQuestion initWithSerializedRepresentation:workflowActions:]
- -[WFWorkoutTrigger(CoreDuetContext) contextStoreKeyPathForCurrentState]
- -[WFWorkoutTrigger(CoreDuetContext) contextStorePredicate]
- -[WFWorkoutTrigger(CoreDuetContext) contextStoreQualityOfService]
- -[WFWorkoutTrigger(CoreDuetContext) contextStoreRegistrationIsForWatch]
- GCC_except_table10083
- GCC_except_table10108
- GCC_except_table10273
- GCC_except_table10308
- GCC_except_table10373
- GCC_except_table10382
- GCC_except_table10384
- GCC_except_table10424
- GCC_except_table10429
- GCC_except_table10469
- GCC_except_table10472
- GCC_except_table10475
- GCC_except_table10478
- GCC_except_table10665
- GCC_except_table10767
- GCC_except_table10784
- GCC_except_table10800
- GCC_except_table10846
- GCC_except_table11090
- GCC_except_table11117
- GCC_except_table11120
- GCC_except_table11136
- GCC_except_table11196
- GCC_except_table11337
- GCC_except_table11428
- GCC_except_table11434
- GCC_except_table11440
- GCC_except_table11456
- GCC_except_table11460
- GCC_except_table11472
- GCC_except_table11477
- GCC_except_table11480
- GCC_except_table11483
- GCC_except_table11619
- GCC_except_table11774
- GCC_except_table11790
- GCC_except_table11984
- GCC_except_table11999
- GCC_except_table12005
- GCC_except_table12007
- GCC_except_table12012
- GCC_except_table12044
- GCC_except_table12057
- GCC_except_table12064
- GCC_except_table1208
- GCC_except_table12119
- GCC_except_table12158
- GCC_except_table12172
- GCC_except_table12174
- GCC_except_table12176
- GCC_except_table12267
- GCC_except_table12283
- GCC_except_table12388
- GCC_except_table12440
- GCC_except_table12495
- GCC_except_table12524
- GCC_except_table12580
- GCC_except_table12591
- GCC_except_table12636
- GCC_except_table12638
- GCC_except_table12833
- GCC_except_table1285
- GCC_except_table12867
- GCC_except_table12986
- GCC_except_table13014
- GCC_except_table13020
- GCC_except_table13069
- GCC_except_table13110
- GCC_except_table13123
- GCC_except_table13128
- GCC_except_table13142
- GCC_except_table13149
- GCC_except_table13150
- GCC_except_table13171
- GCC_except_table13326
- GCC_except_table13362
- GCC_except_table13367
- GCC_except_table13369
- GCC_except_table13372
- GCC_except_table13432
- GCC_except_table13444
- GCC_except_table13448
- GCC_except_table13683
- GCC_except_table13751
- GCC_except_table1390
- GCC_except_table1395
- GCC_except_table13950
- GCC_except_table13991
- GCC_except_table14120
- GCC_except_table14221
- GCC_except_table14226
- GCC_except_table14235
- GCC_except_table14238
- GCC_except_table14303
- GCC_except_table14326
- GCC_except_table14339
- GCC_except_table14352
- GCC_except_table14466
- GCC_except_table14600
- GCC_except_table14621
- GCC_except_table14632
- GCC_except_table14646
- GCC_except_table14649
- GCC_except_table14836
- GCC_except_table14863
- GCC_except_table14958
- GCC_except_table1571
- GCC_except_table1575
- GCC_except_table1577
- GCC_except_table1579
- GCC_except_table1650
- GCC_except_table1664
- GCC_except_table1669
- GCC_except_table1673
- GCC_except_table1937
- GCC_except_table2013
- GCC_except_table2096
- GCC_except_table2106
- GCC_except_table2315
- GCC_except_table2325
- GCC_except_table2330
- GCC_except_table2358
- GCC_except_table248
- GCC_except_table252
- GCC_except_table2529
- GCC_except_table2556
- GCC_except_table2627
- GCC_except_table263
- GCC_except_table2663
- GCC_except_table272
- GCC_except_table2771
- GCC_except_table2774
- GCC_except_table2788
- GCC_except_table2855
- GCC_except_table2882
- GCC_except_table2899
- GCC_except_table2905
- GCC_except_table2957
- GCC_except_table2967
- GCC_except_table3011
- GCC_except_table3054
- GCC_except_table3355
- GCC_except_table3378
- GCC_except_table3379
- GCC_except_table3386
- GCC_except_table3389
- GCC_except_table3413
- GCC_except_table3417
- GCC_except_table3442
- GCC_except_table3447
- GCC_except_table3480
- GCC_except_table3496
- GCC_except_table3500
- GCC_except_table3560
- GCC_except_table3571
- GCC_except_table3573
- GCC_except_table3576
- GCC_except_table3686
- GCC_except_table369
- GCC_except_table3690
- GCC_except_table3692
- GCC_except_table3696
- GCC_except_table3697
- GCC_except_table3836
- GCC_except_table3962
- GCC_except_table3966
- GCC_except_table4344
- GCC_except_table4345
- GCC_except_table4462
- GCC_except_table4549
- GCC_except_table4562
- GCC_except_table4581
- GCC_except_table4589
- GCC_except_table4738
- GCC_except_table4962
- GCC_except_table5011
- GCC_except_table5025
- GCC_except_table5083
- GCC_except_table5154
- GCC_except_table5181
- GCC_except_table5185
- GCC_except_table5229
- GCC_except_table5289
- GCC_except_table5298
- GCC_except_table5320
- GCC_except_table5360
- GCC_except_table5416
- GCC_except_table5421
- GCC_except_table5423
- GCC_except_table5533
- GCC_except_table5549
- GCC_except_table555
- GCC_except_table5876
- GCC_except_table6022
- GCC_except_table6055
- GCC_except_table6129
- GCC_except_table6141
- GCC_except_table6252
- GCC_except_table6330
- GCC_except_table6398
- GCC_except_table6399
- GCC_except_table6400
- GCC_except_table646
- GCC_except_table6500
- GCC_except_table6547
- GCC_except_table6565
- GCC_except_table6586
- GCC_except_table676
- GCC_except_table679
- GCC_except_table681
- GCC_except_table6924
- GCC_except_table6937
- GCC_except_table6946
- GCC_except_table6977
- GCC_except_table7028
- GCC_except_table7034
- GCC_except_table7035
- GCC_except_table7038
- GCC_except_table7054
- GCC_except_table7055
- GCC_except_table7099
- GCC_except_table7157
- GCC_except_table7168
- GCC_except_table7231
- GCC_except_table7232
- GCC_except_table7441
- GCC_except_table7451
- GCC_except_table7528
- GCC_except_table7599
- GCC_except_table7776
- GCC_except_table7819
- GCC_except_table7866
- GCC_except_table7867
- GCC_except_table7907
- GCC_except_table8038
- GCC_except_table8175
- GCC_except_table8180
- GCC_except_table8191
- GCC_except_table8305
- GCC_except_table8312
- GCC_except_table8323
- GCC_except_table8381
- GCC_except_table8392
- GCC_except_table8396
- GCC_except_table8397
- GCC_except_table848
- GCC_except_table8910
- GCC_except_table8951
- GCC_except_table8959
- GCC_except_table8963
- GCC_except_table8992
- GCC_except_table9034
- GCC_except_table9132
- GCC_except_table9184
- GCC_except_table921
- GCC_except_table930
- GCC_except_table9396
- GCC_except_table9402
- GCC_except_table9404
- GCC_except_table9408
- GCC_except_table9410
- GCC_except_table9412
- GCC_except_table9414
- GCC_except_table9418
- GCC_except_table9420
- GCC_except_table9432
- GCC_except_table9436
- GCC_except_table9449
- GCC_except_table9462
- GCC_except_table9468
- GCC_except_table9476
- GCC_except_table9523
- GCC_except_table9529
- GCC_except_table9535
- GCC_except_table963
- GCC_except_table9671
- GCC_except_table9730
- GCC_except_table9756
- GCC_except_table9758
- GCC_except_table9766
- GCC_except_table9768
- GCC_except_table9775
- GCC_except_table9796
- GCC_except_table9797
- GCC_except_table9798
- GCC_except_table9800
- GCC_except_table9805
- GCC_except_table9913
- _OBJC_CLASS_$__TtC11WorkflowKit23StoredValueItemLocation
- _OBJC_CLASS_$__TtC11WorkflowKit24StoredValueManifestEntry
- _OBJC_METACLASS_$__TtC11WorkflowKit23StoredValueItemLocation
- _OBJC_METACLASS_$__TtC11WorkflowKit24StoredValueManifestEntry
- _WFDaemonTaskOutcomeCancelled
- _WFDaemonTaskOutcomeFailed
- _WFDaemonTaskOutcomeFinished
- _WFDaemonTaskOutcomeNotFound
- _WFDaemonTransactionBehaviorConcurrent
- _WFDaemonTransactionBehaviorSuspending
- _WFDeviceCapabilityHomeButton
- _WFRunActionFailReasonModelGeneratedHandleWithCareV2
- _WFTriggerIDFromNotificationUserInfo
- _WFTriggerIDsToDisableFromNotificationUserInfo
- _WFTriggerSystemNotificationIdentifierPrefix
- __CLASS_METHODS__TtC11WorkflowKit23StoredValueItemLocation
- __CLASS_METHODS__TtC11WorkflowKit24StoredValueManifestEntry
- __CLASS_PROPERTIES__TtC11WorkflowKit23StoredValueItemLocation
- __CLASS_PROPERTIES__TtC11WorkflowKit24StoredValueManifestEntry
- __DATA__TtC11WorkflowKit23StoredValueItemLocation
- __DATA__TtC11WorkflowKit24StoredValueManifestEntry
- __INSTANCE_METHODS__TtC11WorkflowKit23StoredValueItemLocation
- __INSTANCE_METHODS__TtC11WorkflowKit24StoredValueManifestEntry
- __IVARS__TtC11WorkflowKit23StoredValueItemLocation
- __IVARS__TtC11WorkflowKit24StoredValueManifestEntry
- __METACLASS_DATA__TtC11WorkflowKit23StoredValueItemLocation
- __METACLASS_DATA__TtC11WorkflowKit24StoredValueManifestEntry
- __OBJC_$_INSTANCE_METHODS_WFAppInFocusTrigger(CoreDuetContext)
- __OBJC_$_INSTANCE_METHODS_WFTimeZonePickerParameter
- __OBJC_$_INSTANCE_METHODS_WFWorkoutTrigger(CoreDuetContext)
- __OBJC_$_INSTANCE_METHODS__TtC11WorkflowKit12WFNewTrigger(WorkflowKit|WorkflowKit1|WorkflowKit2|WorkflowKit3|SourceExport|CatalogEntryProviderDelegate)
- __OBJC_$_PROP_LIST_WFTimeZonePickerParameter
- __OBJC_CLASS_PROTOCOLS_$__TtC11WorkflowKit12WFNewTrigger(WorkflowKit|WorkflowKit1|WorkflowKit2|WorkflowKit3|SourceExport|CatalogEntryProviderDelegate)
- __PROPERTIES__TtC11WorkflowKit23StoredValueItemLocation
- __PROPERTIES__TtC11WorkflowKit24StoredValueManifestEntry
- __PROTOCOLS__TtC11WorkflowKit23StoredValueItemLocation
- __PROTOCOLS__TtC11WorkflowKit24StoredValueManifestEntry
- ___77-[WFAppInFocusTrigger(CoreDuetContext) shouldFireTriggerWithEventInfo:error:]_block_invoke
- ___77-[WFAppInFocusTrigger(CoreDuetContext) shouldFireTriggerWithEventInfo:error:]_block_invoke_2
- ___89-[WFDatabase(Triggers) createTriggerEventWithTriggerID:eventInfo:confirmed:paused:error:]_block_invoke
- ___WFTriggerIDsToDisableFromNotificationUserInfo_block_invoke
- ___block_descriptor_40_e8_32bs_e25_v16?0"WFDialogRequest"8ls32l8
- ___block_descriptor_56_e8_32s40s48s_e5_B8?0ls32l8s40l8s48l8
- ___block_descriptor_56_e8_32s40s_e26_"NSMutableDictionary"8?0ls32l8s40l8
- ___block_descriptor_64_e8_32s40s48bs_e82_v40?0"NSData"8"PBSecurityScopedURLWrapper"16"PBResponseMetadata"24"NSError"32ls32l8s40l8s48l8
- ___block_descriptor_80_e8_32s40s48s56s_e26_"NSMutableDictionary"8?0ls32l8s40l8s48l8s56l8
- ___swift_closure_destructor.113Tm
- ___swift_closure_destructor.13Tm
- ___swift_closure_destructor.16Tm
- ___swift_closure_destructor.22Tm
- ___swift_closure_destructor.72Tm
- ___swift_exist.box.addr_destructor.161Tm
- ___swift_exist.box.addr_destructor.171Tm
- ___swift_exist.box.addr_destructor.193Tm
- _associated conformance So14WFAlarmTriggerC11WorkflowKitE013registerAlarmB07trigger10workflowID5storeAC0B12RegistrationOAC05WFNewB0C_SSAC0bK5Store_ptKFZySo12BMStoreEventCySo07BMClockF0CGcfU_0F4TypeL_OSHACSQ
- _get_enum_tag_for_layout_string 11WorkflowKit12WFNewTriggerCSbIeggd_Sg
- _get_enum_tag_for_layout_string 11WorkflowKit24TypedValueHydrationErrorO
- _symbolic $s11WorkflowKit20TypedValueHydratableP
- _symbolic SDySSSo31_CDContextualChangeRegistrationCG
- _symbolic SDySSSo7BPSSinkCyyXlGG
- _symbolic SS3key______5valuetSg 7ToolKit10TypedValueO
- _symbolic SS______tSg 7ToolKit10TypedValueO
- _symbolic SS_____c 11WorkflowKit12WFNewTriggerC
- _symbolic SaySo18LNEntityIdentifierCG
- _symbolic Say_____G 11WorkflowKit23StoredValueItemLocationC
- _symbolic Say_____G 11WorkflowKit24StoredValueManifestEntryC
- _symbolic Say_____G 7ToolKit10TypedValueO
- _symbolic Say_____G 7ToolKit10TypedValueO016EntityIdentifierD0V
- _symbolic Say_____G 7ToolKit25EnumerationCaseDefinitionV
- _symbolic Sb_____cSg 11WorkflowKit12WFNewTriggerC
- _symbolic _____ 11WorkflowKit16HydrationRequest33_B05D137C8343081B6AF522EDD425C3A8LLV
- _symbolic _____ 11WorkflowKit22RemoteHydrationRequest33_B05D137C8343081B6AF522EDD425C3A8LLV
- _symbolic _____ 11WorkflowKit23StoredValueItemLocationC
- _symbolic _____ 11WorkflowKit24StoredValueManifestEntryC
- _symbolic _____ 11WorkflowKit24TypedValueHydrationErrorO
- _symbolic _____ 11WorkflowKit26TypedValueHydrationContextV
- _symbolic _____ 7ToolKit14TypeIdentifierO010AttributedcD0V
- _symbolic _____ 7ToolKit26TypedValueHydrationOptionsV
- _symbolic _____ 7ToolKit30DatabaseTypeDefinitionProviderC
- _symbolic _____ So14WFAlarmTriggerC11WorkflowKitE013registerAlarmB07trigger10workflowID5storeAC0B12RegistrationOAC05WFNewB0C_SSAC0bK5Store_ptKFZySo12BMStoreEventCySo07BMClockF0CGcfU_0F4TypeL_O
- _symbolic _____10entityType______18instanceIdentifierSS11propertyKey_____Sg0A4Datat 7ToolKit14TypeIdentifierO AA014EntityInstanceD0O 10Foundation4DataV
- _symbolic _____SSIeggo_ 11WorkflowKit12WFNewTriggerC
- _symbolic _____SSIegnr_ 11WorkflowKit12WFNewTriggerC
- _symbolic _____SS______p___________pIegggnrzo_ 11WorkflowKit12WFNewTriggerC AA0D17RegistrationStoreP AA0dE0O s5ErrorP
- _symbolic _____SS______p___________pIegnnnrzo_ 11WorkflowKit12WFNewTriggerC AA0D17RegistrationStoreP AA0dE0O s5ErrorP
- _symbolic _____SbIeggd_ 11WorkflowKit12WFNewTriggerC
- _symbolic _____SbIegnr_ 11WorkflowKit12WFNewTriggerC
- _symbolic _____Sg 11WorkflowKit16HydrationRequest33_B05D137C8343081B6AF522EDD425C3A8LLV
- _symbolic _____Sg 11WorkflowKit22RemoteHydrationRequest33_B05D137C8343081B6AF522EDD425C3A8LLV
- _symbolic _____Sg 11WorkflowKit27CoreDuetTriggerRegistrationV
- _symbolic _____Sg 7ToolKit14TypeIdentifierO010AttributedcD0V
- _symbolic _____SgIgr_ 11WorkflowKit36WFUnifiedAutomationTriggerDescriptorC
- _symbolic _____Sg_ABt 7ToolKit10TypedValueO
- _symbolic _____Sg_ABt 7ToolKit14TypeIdentifierO010AttributedcD0V
- _symbolic _____Sg_ABt 7ToolKit21DisplayRepresentationV
- _symbolic ______AAt So14WFAlarmTriggerC11WorkflowKitE013registerAlarmB07trigger10workflowID5storeAC0B12RegistrationOAC05WFNewB0C_SSAC0bK5Store_ptKFZySo12BMStoreEventCySo07BMClockF0CGcfU_0F4TypeL_O
- _symbolic ______So7LNValueCt 7ToolKit10TypedValueO016EntityIdentifierD0V
- _symbolic ___________SS______ptKc 11WorkflowKit19TriggerRegistrationO AA05WFNewC0C AA0cD5StoreP
- _symbolic _____ySSSo31_CDContextualChangeRegistrationCG s17_NativeDictionaryV
- _symbolic _____ySSSo7BPSSinkCG s17_NativeDictionaryV
- _symbolic _____ySS_____G s18_DictionaryStorageC 7ToolKit10TypedValueO
- _symbolic _____yScCyyt______pGSgG 2os21OSAllocatedUnfairLockV s5ErrorP
- _symbolic _____yScCyyt______pGSg_____G s13ManagedBufferCsRi__rlE s5ErrorP So16os_unfair_lock_sV
- _symbolic _____ySo18LNEntityIdentifierCG 7ToolKit016LinkValueToTypedD15ResolutionErrorO
- _symbolic _____ySo32WFOutOfProcessWorkflowControllerCSgG 2os21OSAllocatedUnfairLockV
- _symbolic _____ySo32WFOutOfProcessWorkflowControllerCSg_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
- _symbolic _____ySo8LNEntityCG 19VoiceShortcutClient13SecureCodableV
- _symbolic _____ySo8LNEntityCG 7ToolKit13SecureCodableV
- _symbolic _____ySo8LNEntityCGSg 7ToolKit13SecureCodableV
- _symbolic _____ySo8NSNumberCG s11_SetStorageC
- _symbolic _____y_____G s11_SetStorageC So14WFAlarmTriggerC11WorkflowKitE013registerAlarmD07trigger10workflowID5storeAE0D12RegistrationOAE05WFNewD0C_SSAE0dM5Store_ptKFZySo12BMStoreEventCySo07BMClockH0CGcfU_0H4TypeL_O
- _symbolic _____y_____G s23_ContiguousArrayStorageC 11WorkflowKit22RemoteHydrationRequest33_B05D137C8343081B6AF522EDD425C3A8LLV
- _symbolic _____y_____G s23_ContiguousArrayStorageC 7ToolKit10TypedValueO010CollectionG0V
- _symbolic _____y_____G s23_ContiguousArrayStorageC 7ToolKit10TypedValueO011EnumerationG0V
- _symbolic _____y_____G s23_ContiguousArrayStorageC 7ToolKit10TypedValueO016EntityIdentifierG0V
- _symbolic _____y_____G s23_ContiguousArrayStorageC 7ToolKit10TypedValueO06EntityG0V
- _symbolic _____y_____G s23_ContiguousArrayStorageC So14WFAlarmTriggerC11WorkflowKitE013registerAlarmE07trigger10workflowID5storeAE0E12RegistrationOAE05WFNewE0C_SSAE0eN5Store_ptKFZySo12BMStoreEventCySo07BMClockI0CGcfU_0I4TypeL_O
- _symbolic _____y_____Say_____GG s17_NativeDictionaryV 7ToolKit14TypeIdentifierO AC25EnumerationCaseDefinitionV
- _symbolic _____y_____So11LNValueTypeCG s17_NativeDictionaryV 7ToolKit14TypeIdentifierO
- _symbolic _____y__________G s17_NativeDictionaryV 7ToolKit14TypeIdentifierO 08WorkflowD016HydrationRequest33_B05D137C8343081B6AF522EDD425C3A8LLV
- _symbolic _____y__________G s17_NativeDictionaryV 7ToolKit14TypeIdentifierO 08WorkflowD022RemoteHydrationRequest33_B05D137C8343081B6AF522EDD425C3A8LLV
- _symbolic _____y__________G s17_NativeDictionaryV 7ToolKit14TypeIdentifierO AE010AttributedeF0V
- _type_layout_string 11WorkflowKit24TypedValueHydrationErrorO
CStrings:
+ "%@%@:%@"
+ "%@%@:%@:%@"
+ "%K == %@ AND %K == %@"
+ "%s Core Data Optimistic Locking: Found coherence library conflict: %@"
+ "%s Could not cast groupedOpenAction to WFFiniteRepeatAction, which is unexpected"
+ "%s Count parameter did not have an attribution set"
+ "%s Delete Albums: no albums to delete (empty/missing input); finishing without performing the delete intent"
+ "%s Import Question unable to find parameter %{public}@ on trigger %{public}@"
+ "%s No count parameter found for tainting"
+ "%s wf_contentCollectionFromLinkValue: IFCastIfClass failed — linkValue.value is %@ (expected NSArray), valueType: %@, appBundleIdentifier: %@"
+ "%s wf_contentCollectionFromLinkValue: hydrated array has %lu items, memberValueType: %@, appBundleIdentifier: %@"
+ "%s wf_contentCollectionFromLinkValue: produced %lu content items from %lu hydrated values"
+ "%s wf_contentCollectionFromLinkValue: wf_contentItemFromLinkValue returned nil for item at index %lu, valueType: %@"
+ "%s wf_contentItemFromLinkValue: itemWithObject returned nil for class %@, linkValue.value: %@, appBundleIdentifier: %@"
+ "(unifiedTrigger.shortcut.workflowID == %@ AND unifiedTrigger.uuid == %@) OR (trigger.shortcut.workflowID == %@ AND trigger.identifier == %@)"
+ ") is also referenced as a standalone asset"
+ "**Private Cloud Compute Models**\nUse large server-based models on Private Cloud Compute to handle complex requests while protecting your privacy.\n\n**On-Device Model**\nUse the on-device model to handle simple requests without the need for a network connection."
+ "-[LNArrayValueType(ContentItem) wf_contentCollectionFromLinkValue:appBundleIdentifier:displayedBundleIdentifier:disclosureLevel:]"
+ "-[LNArrayValueType(ContentItem) wf_contentCollectionFromLinkValue:appBundleIdentifier:displayedBundleIdentifier:disclosureLevel:]_block_invoke"
+ "-[WFFiniteRepeatAction runWithInput:error:]"
+ "-[WFLinkShortcutsDeleteAlbumAction runAsynchronouslyWithInput:]"
+ "-[WFWorkflowImportQuestion initWithTrigger:parameter:question:defaultState:]"
+ "5028"
+ "<WFUnifiedTriggerKey: workflowID: "
+ "@\"WFUnifiedTriggerKey\"24@?0@\"NSDictionary\"8Q16"
+ "ActiveRun"
+ "App.InFocus: BundleID: %s, isStarting: %{bool}d, launchReason: %s"
+ "App.InFocus: Ignoring event with missing bundleID."
+ "App.InFocus: No eventBody received for trigger; not firing."
+ "App.InFocus: Received App.InFocus event"
+ "App.InFocus: Selected app bundleIDs: %s"
+ "App.InFocus: Trigger firing. bundleID: %s, isStarting: %{bool}d"
+ "App.InFocus: Trigger not firing - ignoring empty launch reason on focus."
+ "App.InFocus: Trigger not firing: ignoring screen-off launch reason on background."
+ "App.InFocus: bundle id is not contained in selected list; not firing."
+ "AppIntentsGate"
+ "Attempted to insert trigger %@ that was already on workflow %@"
+ "Automatically runs this shortcut when Low Power Mode is turned on or off."
+ "Automation Input"
+ "AwaitActiveRun"
+ "Biome trigger (remote) fired with identifier: %@, input: %s"
+ "Biome trigger fired with identifier: %@, input: %s"
+ "CNContactImageDataKey"
+ "Cancelling Biome trigger registration with identifier: %@"
+ "Cancelling CoreDuet trigger registration with identifier: %@"
+ "Cancelling remote Biome trigger registration with identifier: %@"
+ "Cascade.Pull"
+ "Cascade.PullSet"
+ "Cascade.Push"
+ "Cascade.PushPartition.Communal"
+ "Cascade.PushPartition.Personal"
+ "CoherenceContext.db NOT readable at "
+ "CoherenceContext.db not readable at %{public}s: %{public}s (exists: %{bool,public}d, process: %{public}s)"
+ "Confirm Before Run"
+ "ContextSync.Health.Workout"
+ "Coordinator: ignoring stale indexingDidError for superseded workID"
+ "Coordinator: ignoring stale indexingDidFinish for superseded workID"
+ "CoreData library conflict (persisted: %lu bytes, %lu shortcuts; snapshot: %lu bytes, %lu shortcuts; process: %@)"
+ "CoreData library conflict result: %lu shortcuts, %lu folders"
+ "CoreDuet trigger callback fired with identifier: %@, input: %s"
+ "Dedup: existing %{public}s wins over incoming %{public}s for stored value '%{public}s'"
+ "Dedup: incoming %{public}s wins over existing %{public}s for stored value '%{public}s'"
+ "EnsureIndexed"
+ "Error grabbing App Shortcuts for bundle identifier %s and locale %s: %@"
+ "Failed to archive packed inline items"
+ "Failed to create file representation for packed asset"
+ "Failed to unarchive packed asset data"
+ "Health.Workout: Found BMHealthWorkout event."
+ "Health.Workout: Found ContextSyncWorkout event."
+ "Health.Workout: Ignoring third-party BMContextSyncWorkout event; not firing."
+ "Health.Workout: Ignoring third-party BMHealthWorkout event; not firing."
+ "Health.Workout: No activity type in workout event; not firing."
+ "Health.Workout: Received workout event. activityType: %s; eventType: %d"
+ "Health.Workout: Skipping duplicate workout event for activityUUID: %s"
+ "Health.Workout: Workout activity type %s does not match selected types; not firing."
+ "Health.Workout: Workout event type does not match trigger configuration; not firing."
+ "Health.Workout:No workout event received for trigger; not firing."
+ "Hiding Montara from TopHits: Montara availability: %s"
+ "If you reconnect to any WLAN network within 3 minutes of being disconnected, this automation will run again."
+ "Ignoring stale finishTask for superseded generation %llu"
+ "ImmediateIndexingController.awaitActiveIndexRun"
+ "Invalid packed asset item index: "
+ "Legacy Montara from TopHits marked unavailable for reasons: %s"
+ "Library tree removal: "
+ "Manifest references packed asset but assetItems is empty"
+ "NSDictionary * _Nonnull WFTriggerNotificationUserInfo(WFUnifiedTriggerKey * _Nonnull __strong, NSArray<WFIcon *> * _Nullable __strong, NSArray<NSString *> * _Nullable __strong)"
+ "NSString *getCNContactImageDataKey(void)"
+ "No dedicated contextSync identifier for stream %s, falling back to com.apple.shortcuts — add a unique identifier to avoid subscription collisions"
+ "Notify"
+ "Packed-asset blob slot ("
+ "Primary account is managed"
+ "Received LNAppShortcutsChanged notification, reloading App Shortcuts for bundle identifiers %s"
+ "Registering Biome trigger with identifier: %@, stream: %@"
+ "Registering CoreDuet trigger with identifier: %@, registration: %@"
+ "Registering remote Biome trigger with identifier: %@, stream: %@"
+ "Reindex.RemoteIndex"
+ "Reloading App Shortcuts for %s with reason: %s"
+ "Reloading App Shortcuts for bundle identifiers %s"
+ "Responses are automatically optimized for the actions they're passed into — for example, if the response is passed into the 'Repeat with Each' action, the model creates a list.\n\nTo manually specify the model's output, select an output type using the 'Output' parameter."
+ "RunImmediately"
+ "Shortcut from category "
+ "Shortcut from folder "
+ "Staged stored value upload %{public}s: inlineDataBytes=%{public}ld manifestBytes=%{public}ld combinedPayloadBytes=%{public}ld ceiling=%{public}ld packed=%{bool,public}d inlineItemCount=%{public}ld assetCount=%{public}ld"
+ "Stored value %{public}s manifest is %{public}ld bytes — over the %{public}ld ceiling on its own. Packing inline items cannot prevent record overflow at this scale; manifest compaction is required."
+ "Stored value item file name is not a UUID: "
+ "Successfully registered for updates with context sync client for stream: %s"
+ "Successfully unregistered from context sync client for stream: %s"
+ "Trigger %@ fired with event info: %s"
+ "Trigger for workflow %@ with ID %@ does not exist"
+ "Trigger localization drift detected: %{public}s in ToolLocalizationRecord but not in current run's contexts %{public}s. Localizing triggers for the union."
+ "Trigger-dependent resource %s is embedded inside the trigger definition. Please use a dictionary definition instead."
+ "TriggerIdentifier"
+ "TriggerOutput"
+ "TriggerShowConfirmationLabel"
+ "TriggerUUID"
+ "WFSummarizeShortcutEnabled"
+ "WFToolKitImmediateIndexingStaleRunTimeout"
+ "WFTriggerKeyFromNotificationUserInfo"
+ "WFTriggerKeysToDisableFromNotificationUserInfo"
+ "When a specified WLAN network is connected"
+ "When a specified WLAN network is disconnected"
+ "WorkflowKit.LegacyStoredValueItemLocation"
+ "WorkflowKit.LegacyStoredValueManifestEntry"
+ "WorkflowKit.WFUnifiedTriggerKey"
+ "[ImmediateIndexing] LNMetadataProvider.waitForInitialIndexing failed: %@"
+ "[ImmediateIndexing] calling runImmediately"
+ "[ImmediateIndexing] id=%llu %s"
+ "[ImmediateIndexing] piggybacked on coordinator's active run"
+ "[ImmediateIndexing] resuming %ld waiter(s)"
+ "[ImmediateIndexing] runImmediately failed: %@"
+ "[ImmediateIndexing] stale-run timeout — cancelling and running fresh"
+ "[ToolKitImmediateIndexing] cancelActiveAndReset called (hasActive=%{bool}d)"
+ "[ToolKitImmediateIndexing] cancelAndReset: resetting queue"
+ "[ToolKitImmediateIndexing] cancelAndReset: resuming %ld stale continuations with CancellationError"
+ "[ToolKitImmediateIndexing] runImmediately: queueing immediate index (activeIndexRun=%{bool}d)"
+ "_HKWorkoutActivityNameForActivityType"
+ "__enabled__"
+ "__notify__"
+ "__show_confirmation__"
+ "capsuleData time"
+ "changeset: %s, force: %{bool}d"
+ "com.apple.shortcuts.walletlistener"
+ "com.apple.shortcuts.workoutlistener"
+ "ensureIndexed(request:)"
+ "fromBookmark: %{bool}d, force: %{bool}d"
+ "full city name (e.g., 'Los Angeles', 'Tokyo')"
+ "getting latest run event for legacy trigger"
+ "hasStoredValues"
+ "id=%llu"
+ "invalid"
+ "is on or after"
+ "is on or before"
+ "joining in-flight activeTask"
+ "managedAccount"
+ "partition: %s, fromBookmark: %{bool}d"
+ "partition: communal"
+ "partition: personal, persona: %s"
+ "process: siriactionsd, sets: %ld"
+ "registerAppInFocusTrigger, %s, key: %@"
+ "runImmediately(request:)"
+ "setSharedContextURL"
+ "shortcut.workflowID == %@ AND identifier == %@"
+ "shortcut.workflowID == %@ AND uuid == %@"
+ "starting fresh activeTask"
+ "trigger.identifier == %@"
+ "unifiedTrigger.shortcut.workflowID == %@ AND unifiedTrigger.uuid == %@"
+ "waitForInitialIndexing()"
+ "waited=%{bool}d"
- "%s Failed to fetch existing trigger with UUID %@: %{public}@"
- "%s Found coherence library conflict: %@"
- "%s Found existing trigger entity in database for UUID: %@"
- "5012"
- "All entity values are transient, returning as-is"
- "App in focus trigger not firing. (selectedBundleIdentifiers: %s, onFocus: %{bool}d, onBackground: %{bool}d)"
- "Automatically runs this shortcut when a Low Power Mode is turned on or off."
- "B8@?0"
- "Biome trigger (remote) fired with identifier: %s, input: %s"
- "Biome trigger fired with identifier: %s, input: %s"
- "Built %ld local hydration request(s) and %ld remote hydration request(s) for %ld non-transient identifier(s)"
- "Cancelling Biome trigger registration with identifier: %s"
- "Cancelling CoreDuet trigger registration with identifier: %s"
- "Cancelling remote Biome trigger registration with identifier: %s"
- "CoreDuet trigger callback fired with identifier: %s, input: %s"
- "Failed to encode manifest"
- "Failed to fetch trigger with ID: %s - %@"
- "Failed to resolve LNValueType for type: %s"
- "Failed to resolve attribution for type: %s"
- "Failed to transform entity from %s: %@"
- "Hiding Montara from TopHits: not enabled"
- "Hydrating %ld entity identifier(s)"
- "Hydrating %ld entity value(s)"
- "Hydrating %ld entity value(s) in collection"
- "Hydrating %ld non-transient entity value(s)"
- "Hydrating collection with %ld value(s)"
- "Hydrating entity identifier: %s"
- "Hydrating entity value: %s"
- "Hydrating local request: %ld identifier(s) for %s from %s"
- "Hydration failed, returning originals: %@"
- "Hydration result count mismatch for %s from %s: expected %ld, got %ld"
- "Injecting %ld deferred property wrapper(s) for %s"
- "Inserted en/languageModel in preferred localizations."
- "Local hydration failed for %s: %@"
- "NOT (SELF.%@.value.%K IN %@) AND NOT (SELF.%@.value.%K IN %@)"
- "NOT (SELF.value.%K IN %@) AND NOT (SELF.value.%K IN %@)"
- "NSDictionary * _Nonnull WFTriggerNotificationUserInfo(NSString * _Nonnull __strong, NSArray<WFIcon *> * _Nullable __strong, NSArray<NSString *> * _Nullable __strong)"
- "No entity metadata for %s in %s"
- "Notify When Run"
- "Passing through %ld non-hydratable value(s) in collection"
- "Passing through %ld transient entity identifier(s) as these cannot be queried"
- "Passing through %ld transient entity value(s)"
- "Received LNAppShortcutsChanged notification, reloading App Shortcuts"
- "Registering Biome trigger with identifier: %s, stream: %@"
- "Registering CoreDuet trigger with identifier: %s, registration: %@"
- "Registering remote Biome trigger with identifier: %s, stream: %@"
- "Remote hydration failed for %s: %@"
- "Responses are automatically optimized for the actions they're passed into — for example, if the response is passed into the 'Repeat with Each' action, the model creates a list.\n\nTo manually specify the model's output, select an output type using the 'Output' parameter.\n\n**Private Cloud Compute Models**\nUse large server-based models on Private Cloud Compute to handle complex requests while protecting your privacy.\n\n**On-Device Model**\nUse the on-device model to handle simple requests without the need for a network connection."
- "RunActionFailReasonModelGeneratedHandleWithCareV2"
- "SBFullScreenSwitcherSceneLiveContentOverlay"
- "SELF.%@.value.%K IN %@ AND NOT (SELF.%@.value.%K IN %@)"
- "SELF.value.%K IN %@ AND SELF.value.%K IN %@"
- "Successfully registered for updates with context sync client"
- "Successfully unregistered from context sync client"
- "Trigger %s fired with event info: %s"
- "Trigger with ID %@ does not exist"
- "WFTriggerIDFromNotificationUserInfo"
- "WFTriggerIDsToDisableFromNotificationUserInfo"
- "cancelled"
- "com.apple.CoreAuthUI"
- "concurrent"
- "finished"
- "get trigger reference"
- "notFound"
- "pdf"
- "suspending"
- "trigger.identifier == %@ OR unifiedTrigger.uuid == %@"
- "use_model_web_search_via_pcc"
- "uuid == %@"
```
