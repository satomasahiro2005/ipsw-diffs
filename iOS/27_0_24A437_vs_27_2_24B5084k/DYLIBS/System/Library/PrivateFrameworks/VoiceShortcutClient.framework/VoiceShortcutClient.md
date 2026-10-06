## VoiceShortcutClient

> `/System/Library/PrivateFrameworks/VoiceShortcutClient.framework/VoiceShortcutClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x155528` | `0x15001c` | **`-0x550c`** |
| `__DATA.__bss` | `0x1b720` | `0x19aa0` | **`-0x1c80`** |
| `__TEXT.__const` | `0x10300` | `0xf6a0` | **`-0xc60`** |
| `__AUTH_CONST.__const` | `0xa588` | `0xa118` | **`-0x470`** |
| `__TEXT.__swift5_typeref` | `0x3af9` | `0x37d7` | **`-0x322`** |
| `__TEXT.__eh_frame` | `0x64f8` | `0x61d8` | **`-0x320`** |
| `__DATA.__data` | `0x46b0` | `0x43e0` | **`-0x2d0`** |
| `__TEXT.__swift5_fieldmd` | `0x2d80` | `0x2af4` | **`-0x28c`** |
| `__TEXT.__unwind_info` | `0x7240` | `0x7028` | **`-0x218`** |
| `__TEXT.__constg_swiftt` | `0x37f8` | `0x360c` | **`-0x1ec`** |
| `__TEXT.__swift5_reflstr` | `0x16b4` | `0x1524` | **`-0x190`** |
| `__AUTH.__data` | `0x1a80` | `0x1950` | **`-0x130`** |
| `__TEXT.__oslogstring` | `0x3f5a` | `0x4065` | **`+0x10b`** |
| `__TEXT.__swift5_proto` | `0xdd4` | `0xcf0` | **`-0xe4`** |
| `__AUTH_CONST.__cfstring` | `0x19d20` | `0x19d80` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0xceac` | `0xceec` | **`+0x40`** |
| `__TEXT.__ustring` | `0x168` | `0x1a8` | **`+0x40`** |
| `__TEXT.__swift5_types` | `0x464` | `0x430` | **`-0x34`** |
| `__AUTH_CONST.__objc_const` | `0x1a7d8` | `0x1a808` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x6148` | `0x6178` | **`+0x30`** |
| `__TEXT.__cstring` | `0x18421` | `0x183f4` | **`-0x2d`** |
| `__TEXT.__gcc_except_tab` | `0x1908` | `0x1934` | **`+0x2c`** |
| `__DATA_CONST.__const` | `0x37f0` | `0x3818` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x1e4` | `0x1c0` | **`-0x24`** |
| `__TEXT.__swift5_builtin` | `0x1cc` | `0x1e0` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x108` | `0xfc` | **`-0xc`** |
| `__TEXT.__swift_as_ret` | `0xf4` | `0xe8` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0x1e60` | `0x1e58` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1218` | `0x1210` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x84` | `0x8c` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xd14` | `0xd18` | **`+0x4`** |

### Other Changes

```diff

-5037.109.0.0.0
+5110.0.8.0.0

-  Functions: 10865
-  Symbols:   11731
+  Functions: 10680
+  Symbols:   11663
Symbols:
+ -[WFExternalUIPresenter completionGuardLock]
+ -[WFExternalUIPresenter wf_tryConsumeCompletionFlag:]
+ -[WFImage(Trimming) imageByInsettingWithMarginFraction:]
+ -[WFImage(Trimming) imageByTrimmingTransparentMargins]
+ -[WFWorkflowCollection initWithIdentifier:isFolder:name:glyphCharacter:isTombstoned:]
+ -[WFWorkflowCollection isTombstoned]
+ -[WFWorkflowRunningContext didSpreadModelRequestLoad]
+ -[WFWorkflowRunningContext setDidSpreadModelRequestLoad:]
+ GCC_except_table1283
+ GCC_except_table1322
+ GCC_except_table1324
+ GCC_except_table1419
+ GCC_except_table1423
+ GCC_except_table1458
+ GCC_except_table1476
+ GCC_except_table1503
+ GCC_except_table1508
+ GCC_except_table1514
+ GCC_except_table1559
+ GCC_except_table1561
+ GCC_except_table1563
+ GCC_except_table1575
+ GCC_except_table1580
+ GCC_except_table1654
+ GCC_except_table1714
+ GCC_except_table1790
+ GCC_except_table1807
+ GCC_except_table1856
+ GCC_except_table1877
+ GCC_except_table1879
+ GCC_except_table1881
+ GCC_except_table1939
+ GCC_except_table1941
+ GCC_except_table1943
+ GCC_except_table1946
+ GCC_except_table1955
+ GCC_except_table1963
+ GCC_except_table1965
+ GCC_except_table1986
+ GCC_except_table2113
+ GCC_except_table2136
+ GCC_except_table2179
+ GCC_except_table2208
+ GCC_except_table2263
+ GCC_except_table2274
+ GCC_except_table2299
+ GCC_except_table2322
+ GCC_except_table2327
+ GCC_except_table2330
+ GCC_except_table2412
+ GCC_except_table2418
+ GCC_except_table2485
+ GCC_except_table2492
+ GCC_except_table2500
+ GCC_except_table2718
+ GCC_except_table2771
+ GCC_except_table2775
+ GCC_except_table2780
+ GCC_except_table2811
+ GCC_except_table2931
+ GCC_except_table2934
+ GCC_except_table2947
+ GCC_except_table2952
+ GCC_except_table2977
+ GCC_except_table3194
+ GCC_except_table3264
+ GCC_except_table3276
+ GCC_except_table3279
+ GCC_except_table3367
+ GCC_except_table3520
+ GCC_except_table3521
+ GCC_except_table3588
+ GCC_except_table3675
+ GCC_except_table3694
+ GCC_except_table3695
+ GCC_except_table3696
+ GCC_except_table3703
+ GCC_except_table3711
+ GCC_except_table3712
+ GCC_except_table3713
+ GCC_except_table3715
+ GCC_except_table3755
+ GCC_except_table3854
+ GCC_except_table3883
+ GCC_except_table3884
+ GCC_except_table3885
+ GCC_except_table4097
+ GCC_except_table4107
+ GCC_except_table4110
+ GCC_except_table4120
+ GCC_except_table4225
+ GCC_except_table4229
+ GCC_except_table4242
+ GCC_except_table4349
+ GCC_except_table4400
+ GCC_except_table4431
+ GCC_except_table4436
+ GCC_except_table4439
+ GCC_except_table4442
+ GCC_except_table4445
+ GCC_except_table4448
+ GCC_except_table4453
+ GCC_except_table4457
+ GCC_except_table4460
+ GCC_except_table4462
+ GCC_except_table4468
+ GCC_except_table4480
+ GCC_except_table4485
+ GCC_except_table4502
+ GCC_except_table4506
+ GCC_except_table4519
+ GCC_except_table4537
+ _OBJC_IVAR_$_WFExternalUIPresenter._completionGuardLock
+ _OBJC_IVAR_$_WFWorkflowCollection._tombstoned
+ _OBJC_IVAR_$_WFWorkflowRunningContext._didSpreadModelRequestLoad
+ __OBJC_$_CLASS_METHODS_WFImage(Named|Tinting|Convenience|Representations|Icons|Symbols|Glyphs|Resizing|Trimming)
+ __OBJC_$_INSTANCE_METHODS_WFImage(Named|Tinting|Convenience|Representations|Icons|Symbols|Glyphs|Resizing|Trimming)
+ ___64-[WFExternalUIPresenter performDialogRequest:completionHandler:]_block_invoke_2
+ ___block_descriptor_64_e8_32s40bs48r56r_e26_v16?0"WFDialogResponse"8ls32l8r48l8r56l8s40l8
+ ___block_descriptor_64_e8_32s40bs48r56r_e30_v16?0"WFSiriActionResponse"8ls32l8r48l8r56l8s40l8
+ ___swift_memcpy81_8
+ _get_enum_tag_for_layout_string 19VoiceShortcutClient0abC7RequestO
+ _type_layout_string 19VoiceShortcutClient0abC7RequestO
+ _type_layout_string 19VoiceShortcutClient0abC7RequestO11AutomationsO
- -[WFAutoShortcutContextualAction searchKeywords]
- -[WFWorkflowCollection initWithIdentifier:isFolder:name:glyphCharacter:isDeleted:]
- -[WFWorkflowCollection isDeleted]
- GCC_except_table1284
- GCC_except_table1323
- GCC_except_table1330
- GCC_except_table1420
- GCC_except_table1424
- GCC_except_table1459
- GCC_except_table1477
- GCC_except_table1504
- GCC_except_table1509
- GCC_except_table1515
- GCC_except_table1560
- GCC_except_table1562
- GCC_except_table1565
- GCC_except_table1576
- GCC_except_table1581
- GCC_except_table1656
- GCC_except_table1715
- GCC_except_table1791
- GCC_except_table1808
- GCC_except_table1857
- GCC_except_table1878
- GCC_except_table1880
- GCC_except_table1882
- GCC_except_table1940
- GCC_except_table1942
- GCC_except_table1945
- GCC_except_table1947
- GCC_except_table1956
- GCC_except_table1964
- GCC_except_table1966
- GCC_except_table1987
- GCC_except_table2114
- GCC_except_table2137
- GCC_except_table2180
- GCC_except_table2209
- GCC_except_table2264
- GCC_except_table2275
- GCC_except_table2300
- GCC_except_table2323
- GCC_except_table2328
- GCC_except_table2331
- GCC_except_table2414
- GCC_except_table2479
- GCC_except_table2486
- GCC_except_table2494
- GCC_except_table2712
- GCC_except_table2765
- GCC_except_table2769
- GCC_except_table2774
- GCC_except_table2805
- GCC_except_table2925
- GCC_except_table2928
- GCC_except_table2935
- GCC_except_table2946
- GCC_except_table2965
- GCC_except_table3188
- GCC_except_table3258
- GCC_except_table3270
- GCC_except_table3273
- GCC_except_table3349
- GCC_except_table3514
- GCC_except_table3515
- GCC_except_table3582
- GCC_except_table3669
- GCC_except_table3688
- GCC_except_table3689
- GCC_except_table3690
- GCC_except_table3697
- GCC_except_table3699
- GCC_except_table3700
- GCC_except_table3707
- GCC_except_table3709
- GCC_except_table3749
- GCC_except_table3848
- GCC_except_table3877
- GCC_except_table3878
- GCC_except_table3879
- GCC_except_table4089
- GCC_except_table4096
- GCC_except_table4099
- GCC_except_table4102
- GCC_except_table4217
- GCC_except_table4221
- GCC_except_table4234
- GCC_except_table4341
- GCC_except_table4392
- GCC_except_table4421
- GCC_except_table4426
- GCC_except_table4429
- GCC_except_table4432
- GCC_except_table4435
- GCC_except_table4438
- GCC_except_table4443
- GCC_except_table4447
- GCC_except_table4450
- GCC_except_table4452
- GCC_except_table4455
- GCC_except_table4458
- GCC_except_table4470
- GCC_except_table4492
- GCC_except_table4496
- GCC_except_table4509
- GCC_except_table4527
- _OBJC_IVAR_$_WFAutoShortcutContextualAction._searchKeywords
- _OBJC_IVAR_$_WFWorkflowCollection._deleted
- __OBJC_$_CLASS_METHODS_WFImage(Named|Tinting|Convenience|Representations|Icons|Symbols|Glyphs|Resizing)
- __OBJC_$_INSTANCE_METHODS_WFImage(Named|Tinting|Convenience|Representations|Icons|Symbols|Glyphs|Resizing)
- ___229-[WFAutoShortcutContextualAction initWithAutoShortcut:identifier:parameterlessIdentifier:phrase:alternativePhrases:bundleIdentifier:actionIdentifier:orderOfShortcut:parentAction:prominentDisplayEligibility:executableAppShortcut:]_block_invoke
- ___block_descriptor_48_e8_32bs40r_e30_v16?0"WFSiriActionResponse"8lr40l8s32l8
- ___swift_allocate_boxed_opaque_existential_2
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO07UserHasE10CodingKeys33_4C034B6054E729C093D63752F4614418LLOs0H3KeyAAs23CustomStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO07UserHasE10CodingKeys33_4C034B6054E729C093D63752F4614418LLOs0H3KeyAAs28CustomDebugStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO21FireTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLOSHAASQ
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO21FireTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0H3KeyAAs23CustomStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO21FireTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0H3KeyAAs28CustomDebugStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO23CreateTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLOSHAASQ
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO23CreateTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0H3KeyAAs23CustomStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO23CreateTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0H3KeyAAs28CustomDebugStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO23DeleteTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLOSHAASQ
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO23DeleteTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0H3KeyAAs23CustomStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO23DeleteTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0H3KeyAAs28CustomDebugStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO24RefreshTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLOSHAASQ
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO24RefreshTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0H3KeyAAs23CustomStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO24RefreshTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0H3KeyAAs28CustomDebugStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO27UnregisterTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLOSHAASQ
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO27UnregisterTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0H3KeyAAs23CustomStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO27UnregisterTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0H3KeyAAs28CustomDebugStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO31FetchScheduledTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLOSHAASQ
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO31FetchScheduledTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0I3KeyAAs23CustomStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO31FetchScheduledTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0I3KeyAAs28CustomDebugStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO32DeleteTriggerShortcutsCodingKeys33_4C034B6054E729C093D63752F4614418LLOSHAASQ
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO32DeleteTriggerShortcutsCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0I3KeyAAs23CustomStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO32DeleteTriggerShortcutsCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0I3KeyAAs28CustomDebugStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO35FetchAllScheduledTriggersCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0J3KeyAAs23CustomStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO35FetchAllScheduledTriggersCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0J3KeyAAs28CustomDebugStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO38CheckTriggerStateWithKeyPathCodingKeys33_4C034B6054E729C093D63752F4614418LLOSHAASQ
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO38CheckTriggerStateWithKeyPathCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0lJ0AAs23CustomStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO38CheckTriggerStateWithKeyPathCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0lJ0AAs28CustomDebugStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO41CheckTriggerStateWithIdentifierCodingKeys33_4C034B6054E729C093D63752F4614418LLOSHAASQ
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO41CheckTriggerStateWithIdentifierCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0K3KeyAAs23CustomStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO41CheckTriggerStateWithIdentifierCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0K3KeyAAs28CustomDebugStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO42GetConfiguredTriggerDescriptionsCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0J3KeyAAs23CustomStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO42GetConfiguredTriggerDescriptionsCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0J3KeyAAs28CustomDebugStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO43ResetAutomationConfirmationStatusCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0J3KeyAAs23CustomStringConvertible
- _associated conformance 19VoiceShortcutClient0abC7RequestO11AutomationsO43ResetAutomationConfirmationStatusCodingKeys33_4C034B6054E729C093D63752F4614418LLOs0J3KeyAAs28CustomDebugStringConvertible
- _symbolic _____ 19VoiceShortcutClient0abC7RequestO11AutomationsO07UserHasE10CodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____ 19VoiceShortcutClient0abC7RequestO11AutomationsO21FireTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____ 19VoiceShortcutClient0abC7RequestO11AutomationsO23CreateTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____ 19VoiceShortcutClient0abC7RequestO11AutomationsO23DeleteTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____ 19VoiceShortcutClient0abC7RequestO11AutomationsO24RefreshTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____ 19VoiceShortcutClient0abC7RequestO11AutomationsO27UnregisterTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____ 19VoiceShortcutClient0abC7RequestO11AutomationsO31FetchScheduledTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____ 19VoiceShortcutClient0abC7RequestO11AutomationsO32DeleteTriggerShortcutsCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____ 19VoiceShortcutClient0abC7RequestO11AutomationsO35FetchAllScheduledTriggersCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____ 19VoiceShortcutClient0abC7RequestO11AutomationsO38CheckTriggerStateWithKeyPathCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____ 19VoiceShortcutClient0abC7RequestO11AutomationsO41CheckTriggerStateWithIdentifierCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____ 19VoiceShortcutClient0abC7RequestO11AutomationsO42GetConfiguredTriggerDescriptionsCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____ 19VoiceShortcutClient0abC7RequestO11AutomationsO43ResetAutomationConfirmationStatusCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic ___________p 19VoiceShortcutClient29ScheduledTriggerConfigurationP AA0dE12IdentifiableP
- _symbolic ___________t 19VoiceShortcutClient11TriggerTypeO AA013LegacyCodableD6ActionO
- _symbolic _____ySay_____GG 19VoiceShortcutClient0aB17ResponseWithValueO AA16ScheduledTriggerV
- _symbolic _____y_____G 19VoiceShortcutClient0aB17ResponseWithValueO AA16ScheduledTriggerV
- _symbolic _____y_____G s22KeyedDecodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO07UserHasH10CodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO21FireTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO23CreateTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO23DeleteTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO24RefreshTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO27UnregisterTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO31FetchScheduledTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO32DeleteTriggerShortcutsCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO35FetchAllScheduledTriggersCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO38CheckTriggerStateWithKeyPathCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO41CheckTriggerStateWithIdentifierCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO42GetConfiguredTriggerDescriptionsCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO43ResetAutomationConfirmationStatusCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO07UserHasH10CodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO21FireTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO23CreateTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO23DeleteTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO24RefreshTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO27UnregisterTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO31FetchScheduledTriggerCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO32DeleteTriggerShortcutsCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO35FetchAllScheduledTriggersCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO38CheckTriggerStateWithKeyPathCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO41CheckTriggerStateWithIdentifierCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO42GetConfiguredTriggerDescriptionsCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 19VoiceShortcutClient0deF7RequestO11AutomationsO43ResetAutomationConfirmationStatusCodingKeys33_4C034B6054E729C093D63752F4614418LLO
- _symbolic _____y___________pG s23_ContiguousArrayStorageC 19VoiceShortcutClient29ScheduledTriggerConfigurationP AC0gH12IdentifiableP
CStrings:
+ "%s Asked to tear down runner because %@ but we're already >= tearing down. Ignoring the request."
+ "%s ToolKit client did not reply to Siri request %@ within %.0fs; forcing a failure."
+ "%s ToolKit client did not reply to dialog request %@ within %.0fs; forcing a failure."
+ "-[WFExternalUIPresenter performDialogRequest:completionHandler:]_block_invoke_2"
+ "-[WFExternalUIPresenter performSiriRequest:completionHandler:]_block_invoke_2"
+ "-[WFOutOfProcessWorkflowControllerStateMachine tearDownRunnerWithReason:]"
+ "HomePod Stereo Pair"
+ "On My Mac"
+ "The app didn’t respond in time."
+ "third_party_generative_tools"
+ "tombstoned"
+ "tool_database_auto_reopen"
+ "use_model_hide_legacy_chatgpt"
+ "v16@?0@\"WFDialogResponse\"8"
- "HomePod2"
- "actionable_icp_upsell"
- "checkTriggerStateWithIdentifier"
- "checkTriggerStateWithKeyPath"
- "deleteTriggerShortcuts"
- "enable_cascade_without_paired_watch"
- "fetchAllScheduledTriggers"
- "fetchScheduledTrigger"
- "getConfiguredTriggerDescriptions"
- "resetAutomationConfirmationStatus"
- "triggers_ie"
- "unregisterTrigger"
- "userHasAutomations"
- "watch_automation"
```
