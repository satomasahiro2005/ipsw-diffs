## AccessibilityUtilities

> `/System/Library/PrivateFrameworks/AccessibilityUtilities.framework/AccessibilityUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20fc6c` | `0x210e7c` | **`+0x1210`** |
| `__AUTH_CONST.__objc_const` | `0x1c570` | `0x1c828` | **`+0x2b8`** |
| `__TEXT.__objc_methlist` | `0xff2c` | `0x10124` | **`+0x1f8`** |
| `__AUTH_CONST.__cfstring` | `0x13cc0` | `0x13ea0` | **`+0x1e0`** |
| `__DATA_CONST.__objc_selrefs` | `0xa330` | `0xa498` | **`+0x168`** |
| `__TEXT.__cstring` | `0x1e024` | `0x1e15a` | **`+0x136`** |
| `__TEXT.__ustring` | `0x68` | `0x18c` | **`+0x124`** |
| `__AUTH_CONST.__objc_intobj` | `0x16e0` | `0x17a0` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0x2a40` | `0x2a90` | **`+0x50`** |
| `__DATA_CONST.__objc_arraydata` | `0x9d8` | `0xa20` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x9c20` | `0x9c58` | **`+0x38`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x330` | `0x360` | **`+0x30`** |
| `__AUTH_CONST.__objc_dictobj` | `0x2f8` | `0x320` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0xa620` | `0xa640` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0xc00` | `0xc20` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x13dc` | `0x13f0` | **`+0x14`** |
| `__AUTH_CONST.__objc_doubleobj` | `0x70` | `0x80` | **`+0x10`** |
| `__DATA.__bss` | `0x9010` | `0x9020` | **`+0x10`** |
| `__DATA.__data` | `0x52c8` | `0x52d8` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x5c20` | `0x5c30` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x6ee4` | `0x6ef3` | **`+0xf`** |
| `__DATA_CONST.__objc_classlist` | `0x4d0` | `0x4d8` | **`+0x8`** |

### Other Changes

```diff

-3245.8.2.0.0
+3245.8.4.2.0

-  Functions: 15562
-  Symbols:   11043
-  CStrings:  4478
+  Functions: 15604
+  Symbols:   11106
+  CStrings:  4494
Symbols:
+ +[AXLiveRecognitionAskParameters current]
+ +[AXTadmorTesterDevice sharedAbsoluteInstance]
+ +[AXTripleClickHelpers _handleToggleTripleClickTriggeredFromAppIntent:completion:]
+ +[AXTripleClickHelpers _localToggleAccessibilityShortcutOption:completion:]
+ +[AXTripleClickHelpers _localToggleTripleClickOption:completion:]
+ +[AXTripleClickHelpers _toggleClassicInvertColorsOffMainThreadWithCompletion:]
+ +[AXTripleClickHelpers _toggleSmartInvertColorsOffMainThreadWithCompletion:]
+ +[AXTripleClickHelpers toggleAccessibilityShortcutOptionFromAppIntent:completion:]
+ -[AXLiveRecognitionAskParameters .cxx_destruct]
+ -[AXLiveRecognitionAskParameters activity]
+ -[AXLiveRecognitionAskParameters allowsFollowUpQuestions]
+ -[AXLiveRecognitionAskParameters automaticCaptureEnabled]
+ -[AXLiveRecognitionAskParameters defaultQuestionText]
+ -[AXLiveRecognitionAskParameters preferredInputType]
+ -[AXLiveRecognitionAskParameters setActivity:]
+ -[AXLiveRecognitionAskParameters useDefaultQuestion]
+ -[AXLiveRecognitionAskParameters volumeButtonRecaptureEnabled]
+ -[AXSettings(LegacyImplementation) liveRecognitionAskSessionUsesActivity]
+ -[AXSettings(LegacyImplementation) setLiveRecognitionAskSessionUsesActivity:]
+ -[AXSettings(LegacyImplementation) switchControlMenuItemTypeEnabled:]
+ -[AXSpringBoardServer switchNativeFocusedApplicationToProcessIdentifier:sceneIdentifier:]
+ -[AXSpringBoardServer toggleLiveRecognition]
+ -[AXTadmorTesterDevice initWithAbsolutePositioning:]
+ -[AXTadmorTesterDevice sendAbsolute1DPosition:]
+ -[AXTadmorTesterDevice sendAbsolute2DPositionX:y:]
+ -[AXVOLiveRecognitionActivity askAllowsFollowUpQuestions]
+ -[AXVOLiveRecognitionActivity askAutomaticCaptureEnabled]
+ -[AXVOLiveRecognitionActivity askDefaultQuestionText]
+ -[AXVOLiveRecognitionActivity askPreferredInputType]
+ -[AXVOLiveRecognitionActivity askUseDefaultQuestion]
+ -[AXVOLiveRecognitionActivity askVolumeButtonRecaptureEnabled]
+ -[AXVOLiveRecognitionActivity ask]
+ -[AXVOLiveRecognitionActivity isAskOnly]
+ -[AXVOLiveRecognitionActivity setAsk:]
+ -[AXVOLiveRecognitionActivity setAskAllowsFollowUpQuestions:]
+ -[AXVOLiveRecognitionActivity setAskAutomaticCaptureEnabled:]
+ -[AXVOLiveRecognitionActivity setAskDefaultQuestionText:]
+ -[AXVOLiveRecognitionActivity setAskPreferredInputType:]
+ -[AXVOLiveRecognitionActivity setAskUseDefaultQuestion:]
+ -[AXVOLiveRecognitionActivity setAskVolumeButtonRecaptureEnabled:]
+ GCC_except_table1011
+ GCC_except_table1015
+ GCC_except_table1028
+ GCC_except_table1042
+ GCC_except_table106
+ GCC_except_table1164
+ GCC_except_table126
+ GCC_except_table1272
+ GCC_except_table1363
+ GCC_except_table138
+ GCC_except_table1386
+ GCC_except_table140
+ GCC_except_table1421
+ GCC_except_table143
+ GCC_except_table1471
+ GCC_except_table1500
+ GCC_except_table154
+ GCC_except_table1563
+ GCC_except_table158
+ GCC_except_table1587
+ GCC_except_table1591
+ GCC_except_table1593
+ GCC_except_table1596
+ GCC_except_table1602
+ GCC_except_table162
+ GCC_except_table1692
+ GCC_except_table1700
+ GCC_except_table1707
+ GCC_except_table171
+ GCC_except_table1711
+ GCC_except_table1718
+ GCC_except_table1721
+ GCC_except_table1723
+ GCC_except_table1727
+ GCC_except_table1730
+ GCC_except_table1732
+ GCC_except_table178
+ GCC_except_table1866
+ GCC_except_table1881
+ GCC_except_table1902
+ GCC_except_table1903
+ GCC_except_table1904
+ GCC_except_table1906
+ GCC_except_table1907
+ GCC_except_table1908
+ GCC_except_table1909
+ GCC_except_table2247
+ GCC_except_table2250
+ GCC_except_table2253
+ GCC_except_table2255
+ GCC_except_table2257
+ GCC_except_table2259
+ GCC_except_table2261
+ GCC_except_table2349
+ GCC_except_table2387
+ GCC_except_table2454
+ GCC_except_table246
+ GCC_except_table2463
+ GCC_except_table2492
+ GCC_except_table2528
+ GCC_except_table2537
+ GCC_except_table2553
+ GCC_except_table2580
+ GCC_except_table270
+ GCC_except_table2722
+ GCC_except_table2781
+ GCC_except_table2802
+ GCC_except_table2956
+ GCC_except_table3026
+ GCC_except_table3037
+ GCC_except_table3039
+ GCC_except_table3046
+ GCC_except_table313
+ GCC_except_table3160
+ GCC_except_table3172
+ GCC_except_table3512
+ GCC_except_table3516
+ GCC_except_table3545
+ GCC_except_table3549
+ GCC_except_table3660
+ GCC_except_table3673
+ GCC_except_table3683
+ GCC_except_table3788
+ GCC_except_table3793
+ GCC_except_table3880
+ GCC_except_table429
+ GCC_except_table4399
+ GCC_except_table4407
+ GCC_except_table4408
+ GCC_except_table4416
+ GCC_except_table4417
+ GCC_except_table4425
+ GCC_except_table4429
+ GCC_except_table4431
+ GCC_except_table4538
+ GCC_except_table4551
+ GCC_except_table4764
+ GCC_except_table4768
+ GCC_except_table4773
+ GCC_except_table4795
+ GCC_except_table4967
+ GCC_except_table5001
+ GCC_except_table5044
+ GCC_except_table5063
+ GCC_except_table679
+ GCC_except_table686
+ GCC_except_table689
+ GCC_except_table691
+ GCC_except_table70
+ GCC_except_table720
+ GCC_except_table749
+ GCC_except_table766
+ GCC_except_table829
+ GCC_except_table835
+ GCC_except_table839
+ GCC_except_table888
+ GCC_except_table89
+ GCC_except_table94
+ GCC_except_table951
+ GCC_except_table999
+ _AXGenerativeModelAssetsReady
+ _AXIPCMessageKeyCarouselCanShowAppSwitcher
+ _OBJC_CLASS_$_AXLiveRecognitionAskParameters
+ _OBJC_IVAR_$_AXLiveRecognitionAskParameters._activity
+ _OBJC_IVAR_$_AXVOLiveRecognitionActivity._ask
+ _OBJC_IVAR_$_AXVOLiveRecognitionActivity._askAllowsFollowUpQuestions
+ _OBJC_IVAR_$_AXVOLiveRecognitionActivity._askAutomaticCaptureEnabled
+ _OBJC_IVAR_$_AXVOLiveRecognitionActivity._askDefaultQuestionText
+ _OBJC_IVAR_$_AXVOLiveRecognitionActivity._askPreferredInputType
+ _OBJC_IVAR_$_AXVOLiveRecognitionActivity._askUseDefaultQuestion
+ _OBJC_IVAR_$_AXVOLiveRecognitionActivity._askVolumeButtonRecaptureEnabled
+ _OBJC_METACLASS_$_AXLiveRecognitionAskParameters
+ __OBJC_$_CLASS_METHODS_AXLiveRecognitionAskParameters
+ __OBJC_$_CLASS_PROP_LIST_AXLiveRecognitionAskParameters
+ __OBJC_$_INSTANCE_METHODS_AXLiveRecognitionAskParameters
+ __OBJC_$_INSTANCE_VARIABLES_AXLiveRecognitionAskParameters
+ __OBJC_$_PROP_LIST_AXLiveRecognitionAskParameters
+ __OBJC_CLASS_RO_$_AXLiveRecognitionAskParameters
+ __OBJC_METACLASS_RO_$_AXLiveRecognitionAskParameters
+ ___46+[AXTadmorTesterDevice sharedAbsoluteInstance]_block_invoke
+ ___76+[AXTripleClickHelpers _toggleSmartInvertColorsOffMainThreadWithCompletion:]_block_invoke
+ ___78+[AXTripleClickHelpers _toggleClassicInvertColorsOffMainThreadWithCompletion:]_block_invoke
+ ___block_descriptor_57_e8_32bs40r_e5_v8?0lr40l8s32l8
+ ___block_descriptor_57_e8_32bs_e34_v24?0"NSDictionary"8"NSError"16ls32l8
+ _sharedAbsoluteInstance._sharedAbsolute
+ _sharedAbsoluteInstance.onceToken
- GCC_except_table1003
- GCC_except_table1007
- GCC_except_table102
- GCC_except_table1020
- GCC_except_table1034
- GCC_except_table1156
- GCC_except_table1264
- GCC_except_table132
- GCC_except_table134
- GCC_except_table1355
- GCC_except_table137
- GCC_except_table1378
- GCC_except_table1413
- GCC_except_table144
- GCC_except_table1458
- GCC_except_table146
- GCC_except_table148
- GCC_except_table1487
- GCC_except_table1550
- GCC_except_table1574
- GCC_except_table1578
- GCC_except_table1580
- GCC_except_table1583
- GCC_except_table1589
- GCC_except_table165
- GCC_except_table1679
- GCC_except_table1687
- GCC_except_table1694
- GCC_except_table1698
- GCC_except_table1705
- GCC_except_table1708
- GCC_except_table1710
- GCC_except_table1714
- GCC_except_table1717
- GCC_except_table1719
- GCC_except_table172
- GCC_except_table1853
- GCC_except_table1868
- GCC_except_table1889
- GCC_except_table1890
- GCC_except_table1891
- GCC_except_table1893
- GCC_except_table1894
- GCC_except_table1895
- GCC_except_table1896
- GCC_except_table2234
- GCC_except_table2237
- GCC_except_table2240
- GCC_except_table2242
- GCC_except_table2244
- GCC_except_table2246
- GCC_except_table2248
- GCC_except_table2336
- GCC_except_table2374
- GCC_except_table240
- GCC_except_table2441
- GCC_except_table2450
- GCC_except_table2479
- GCC_except_table2515
- GCC_except_table2524
- GCC_except_table2540
- GCC_except_table2567
- GCC_except_table264
- GCC_except_table2708
- GCC_except_table2767
- GCC_except_table2788
- GCC_except_table2942
- GCC_except_table3012
- GCC_except_table3023
- GCC_except_table3025
- GCC_except_table3032
- GCC_except_table307
- GCC_except_table3146
- GCC_except_table3158
- GCC_except_table3498
- GCC_except_table3502
- GCC_except_table3531
- GCC_except_table3535
- GCC_except_table3644
- GCC_except_table3657
- GCC_except_table3667
- GCC_except_table3772
- GCC_except_table3777
- GCC_except_table3863
- GCC_except_table423
- GCC_except_table4357
- GCC_except_table4365
- GCC_except_table4366
- GCC_except_table4374
- GCC_except_table4375
- GCC_except_table4383
- GCC_except_table4387
- GCC_except_table4389
- GCC_except_table4496
- GCC_except_table4509
- GCC_except_table4722
- GCC_except_table4726
- GCC_except_table4731
- GCC_except_table4753
- GCC_except_table4925
- GCC_except_table4959
- GCC_except_table5002
- GCC_except_table5021
- GCC_except_table671
- GCC_except_table678
- GCC_except_table681
- GCC_except_table683
- GCC_except_table69
- GCC_except_table712
- GCC_except_table741
- GCC_except_table758
- GCC_except_table821
- GCC_except_table827
- GCC_except_table831
- GCC_except_table85
- GCC_except_table880
- GCC_except_table90
- GCC_except_table943
- GCC_except_table991
- ___61+[AXTripleClickHelpers _toggleSmartInvertColorsOffMainThread]_block_invoke
- ___63+[AXTripleClickHelpers _toggleClassicInvertColorsOffMainThread]_block_invoke
- ___block_descriptor_41_e5_v8?0l
- ___block_descriptor_49_e34_v24?0"NSDictionary"8"NSError"16l
CStrings:
+ "ARRANGEMENT_PIN_PAIR_FULL_WIDTH"
+ "ARRANGEMENT_UNPIN_PAIR_FULL_WIDTH"
+ "AXMagnifierGenerativeModelsAvailable: partnerAllowedInRegion=%d status=%ld assetsReady=%d"
+ "AXSLiveRecognitionAskSessionUsesActivity"
+ "AXTadmorTesterDevice: could not patch the pointer Input item to Absolute — descriptor layout changed; absolute-positioning testing will not work."
+ "R"
+ "TADABS"
+ "absolute 1D"
+ "absolute 2D"
+ "animationDuration"
+ "ask"
+ "askAllowsFollowUpQuestions"
+ "askAutomaticCaptureEnabled"
+ "askDefaultQuestionText"
+ "askPreferredInputType"
+ "askUseDefaultQuestion"
+ "askVolumeButtonRecaptureEnabled"
+ "com.apple.FoundationModels"
- "AXMagnifierGenerativeModelsAvailable: partnerAllowedInRegion=%d status=%ld"
- "ask.sheet.option.detection.mode"
```
