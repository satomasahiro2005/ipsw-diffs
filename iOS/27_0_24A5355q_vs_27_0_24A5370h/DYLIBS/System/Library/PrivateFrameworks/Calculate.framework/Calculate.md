## Calculate

> `/System/Library/PrivateFrameworks/Calculate.framework/Calculate`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd6f6c` | `0xd7348` | **`+0x3dc`** |
| `__AUTH_CONST.__auth_got` | `0xf40` | `0xf38` | **`-0x8`** |

### Other Changes

```diff

-  Symbols:   2762
+  Symbols:   2761
Symbols:
- _objc_retain_x11
Functions:
~ sub_1c7369a38 -> sub_1c7b77a38 : 1300 -> 1276
~ sub_1c736a33c -> sub_1c7b78324 : 832 -> 856
~ sub_1c736a8dc -> sub_1c7b788dc : 428 -> 424
~ sub_1c736ba34 -> sub_1c7b79a30 : 248 -> 272
~ sub_1c736bb2c -> sub_1c7b79b40 : 248 -> 272
~ sub_1c736bc24 -> sub_1c7b79c50 : 236 -> 256
~ sub_1c736d398 -> sub_1c7b7b3d8 : 428 -> 424
~ sub_1c736f0d8 -> sub_1c7b7d114 : 6792 -> 6796
~ sub_1c7370b60 -> sub_1c7b7eba0 : 512 -> 508
~ sub_1c737125c -> sub_1c7b7f298 : 1460 -> 1456
~ sub_1c73720b8 -> sub_1c7b800f0 : 244 -> 268
~ sub_1c737375c -> sub_1c7b817ac : 280 -> 292
~ sub_1c737406c -> sub_1c7b820c8 : 896 -> 892
~ -[NSNumberFormatter(FormatString) formatString:usesGroupingSeparator:groupingSeparator:decimalSeparator:maximumIntegerDigits:maximumFractionDigits:localizeDigits:] : 916 -> 912
~ sub_1c7377a5c -> sub_1c7b85ab0 : 564 -> 572
~ -[UnitsInfo initWithDictionary:] : 4092 -> 4072
~ ___bid128_from_string : 2792 -> 2748
~ -[UnitsInfo populateSubunitIDs:forUnit:visited:] : 448 -> 444
~ +[Localize systemLocales] : 396 -> 392
~ +[Localize locales:withDefault:] : 508 -> 504
~ -[CalculateTokenizer setVariables:] : 404 -> 400
~ -[CalculateTokenizer _findNextToken] : 7244 -> 7248
~ -[CalculateTokenizer update] : 1392 -> 1388
~ ___35-[CalculateTokenizer _loadIfNeeded]_block_invoke : 1116 -> 1112
~ -[AvailableUnitRanks ranksWithLocales:cachedOnly:] : 1036 -> 1032
~ +[Localize keyForLocales:] : 344 -> 340
~ +[CalculateTokenizer addSymbols:] : 2120 -> 2116
~ +[CalculateTokenizer _addSymbols:normalized:tokenType:isLaTeX:trie:] : 820 -> 812
~ -[TrieNode visit:create:] : 172 -> 188
~ -[TrieNode updateForByte:leaf:create:] : 800 -> 788
~ +[CalculateTokenizer addUnits:builtIn:] : 712 -> 708
~ ___39+[CalculateTokenizer addUnits:builtIn:]_block_invoke : 460 -> 456
~ +[Localize enumerateLocales:withBlock:] : 412 -> 408
~ ___50+[CalculateTokenizer addLocalizedSymbols:locales:]_block_invoke : 548 -> 544
~ sub_1c73864c0 -> sub_1c7b944a8 : 4980 -> 4956
~ sub_1c7387970 -> sub_1c7b95940 : 12516 -> 12548
~ sub_1c738ae6c -> sub_1c7b98e5c : 788 -> 800
~ sub_1c738b1d0 -> sub_1c7b991cc : 4532 -> 4652
~ sub_1c738c384 -> sub_1c7b9a3f8 : 220 -> 232
~ sub_1c738c460 -> sub_1c7b9a4e0 : 2784 -> 2764
~ sub_1c738db24 -> sub_1c7b9bb90 : 248 -> 268
~ sub_1c739038c -> sub_1c7b9e40c : 1172 -> 1196
~ sub_1c7391bcc -> sub_1c7b9fc64 : 1452 -> 1476
~ -[CalculateCurrencyCache _consumerSecret] : 140 -> 148
~ -[CalculateCurrencyCache updateCurrencyCacheWithData:] : 1204 -> 1200
~ _newUnitNode : 252 -> 260
~ _newUnitIDNode : 216 -> 224
~ _functionVariable : 340 -> 332
~ _UnitCountHasNonAngleUnits : 120 -> 128
~ _UnitCountConvert : 528 -> 560
~ _UnitCountMultiply : 388 -> 392
~ _UnitCountNextSmallestID : 276 -> 312
~ _UnitCountDecompose : 880 -> 872
~ _UnitCountCompose : 2916 -> 2928
~ _addUnitToSuggestions : 452 -> 448
~ ___functionUnit_block_invoke : 956 -> 968
~ ____functionMultiply_block_invoke : 1060 -> 1084
~ ___functionDivide_block_invoke : 1484 -> 1508
~ ___functionPercentIncrease_block_invoke : 1024 -> 1040
~ ___functionPercentDecrease_block_invoke : 1024 -> 1040
~ ___functionSameCurrency_block_invoke : 976 -> 960
~ ___functionSqrRoot_block_invoke : 592 -> 612
~ ___functionCubeRoot_block_invoke : 1708 -> 1720
~ ___functionExp_block_invoke : 524 -> 532
~ ___functionLn_block_invoke : 516 -> 524
~ ___functionLog_block_invoke : 524 -> 532
~ ___functionLogBase_block_invoke : 904 -> 916
~ ___functionASin_block_invoke : 444 -> 460
~ ___functionACos_block_invoke : 712 -> 728
~ ___functionATan_block_invoke : 444 -> 460
~ ___functionASinD_block_invoke : 724 -> 740
~ ___functionACosD_block_invoke : 732 -> 748
~ ___functionATanD_block_invoke : 700 -> 716
~ ___functionSinH_block_invoke : 1680 -> 1696
~ ___functionCosH_block_invoke : 1452 -> 1468
~ ___functionTanH_block_invoke : 852 -> 868
~ ___functionASinH_block_invoke : 1152 -> 1168
~ ___functionACosH_block_invoke : 1576 -> 1592
~ ___functionATanH_block_invoke : 696 -> 712
~ ___functionRoundNearest_block_invoke : 1112 -> 1128
~ ___functionJ0_block_invoke : 324 -> 340
~ ___functionJ1_block_invoke : 324 -> 340
~ ___functionY0_block_invoke : 324 -> 340
~ ___functionY1_block_invoke : 324 -> 340
~ ___functionLGamma_block_invoke : 508 -> 516
~ ___functionFactorial_block_invoke : 1512 -> 1520
~ ___functionPow_block_invoke : 1352 -> 1412
~ ___functionRoot_block_invoke : 1196 -> 1228
~ ___functionFMod_block_invoke : 1488 -> 1520
~ ___functionHypot_block_invoke : 2616 -> 2648
~ ___functionRem_block_invoke : 2276 -> 2308
~ ___functionMin_block_invoke : 1116 -> 1128
~ ___functionMax_block_invoke : 1116 -> 1128
~ ___functionAND_block_invoke : 368 -> 400
~ ___functionOR_block_invoke : 368 -> 400
~ ___functionNOR_block_invoke : 372 -> 404
~ ___functionXOR_block_invoke : 368 -> 400
~ ___functionLeftShift_block_invoke : 448 -> 480
~ ___functionRightShift_block_invoke : 448 -> 480
~ ___functionLeftRotate_block_invoke : 372 -> 404
~ ___functionRightRotate_block_invoke : 368 -> 400
~ ___functionFlip_block_invoke : 544 -> 560
~ ___36+[Localize numberingSystemForDigit:]_block_invoke : 440 -> 436
~ ___39+[Localize numberingSystemCharacterSet]_block_invoke : 324 -> 320
~ ___45+[Localize numberingSystemOutputCharacterSet]_block_invoke : 392 -> 388
~ +[Localize localizeString:withNumberingSystem:locale:] : 968 -> 956
~ _CalculateExpressionError : 692 -> 684
~ -[CalculateUnitCategory _findPreferredSIUnit:metric:US:UK:] : 604 -> 596
~ -[CalculateUnitCategory preferredUnits] : 1008 -> 1004
~ -[CalculateUnitCategory findUnitWithName:] : 340 -> 336
~ -[CalculateUnitCategory findUnitsWithQuery:] : 328 -> 324
~ -[CalculateUnitCategory initWithTypeInfo:unitsInfo:collection:] : 472 -> 468
~ -[CalculateUnitCollection initWithLocales:] : 480 -> 476
~ -[CalculateUnitCollection findUnitWithName:] : 312 -> 308
~ -[CalculateUnitCollection findCategoryWithName:] : 340 -> 336
~ -[CalculateTerm primaryUnit] : 332 -> 328
~ -[CalculateTerm localizedNameForValue:locale:retainingFormat:unit:] : 284 -> 280
~ -[CalculateTerm formattedUnitReplacingFirstNumerator:] : 1412 -> 1456
~ -[CalculateTerm formattedResultBeforeNumberingSystem] : 784 -> 780
~ +[CalculateResult resultWithResultTree:parseTree:locales:numberFormatter:unitsInfo:unitType:unitExponent:expression:isTrivial:isPartialExpression:variableLookups:variableResultTrees:variableResultTreesCount:resolvedUnitFormats:forceResult:assumeDegrees:localizeUnit:unitFormat:matchLocale:numberingSystem:autoScientificNotation:scientificNotationFormat:flexibleFractionDigits:isSimpleVerticalMath:minimumFractionDigits:hasStaleCurrencyData:] : 1296 -> 1304
~ -[CalculateResult _setConversions:] : 280 -> 276
~ -[CalculateResult dealloc] : 168 -> 164
~ -[CalculateResult formattedResult] : 344 -> 340
~ -[CalculateResult conversionsForMetric:US:UK:] : 652 -> 648
~ -[CalculateResult bestConversion] : 2876 -> 2804
~ -[CalculateResult localizedConversions] : 1612 -> 1588
~ ___39-[CalculateResult localizedConversions]_block_invoke : 332 -> 328
~ -[CalculateResult convertedTree:from:needsUpdate:] : 768 -> 780
~ -[CalculateResult updateVariables:] : 900 -> 896
~ +[Calculate evaluate:options:error:needsUpdate:] : 21228 -> 21212
~ ___48+[Calculate evaluate:options:error:needsUpdate:]_block_invoke_35 : 444 -> 436
~ ___48+[Calculate evaluate:options:error:needsUpdate:]_block_invoke_36 : 520 -> 524
~ ___48+[Calculate evaluate:options:error:needsUpdate:]_block_invoke_37 : 404 -> 400
~ ___48+[Calculate evaluate:options:error:needsUpdate:]_block_invoke_38 : 452 -> 448
~ ___48+[Calculate evaluate:options:error:needsUpdate:]_block_invoke_39 : 484 -> 496
~ ___49+[Calculate(CalculateScanner) scan:options:stop:]_block_invoke.102 : 664 -> 660
~ ___50-[AvailableUnitRanks ranksWithLocales:cachedOnly:]_block_invoke_3 : 704 -> 700
~ ___50-[AvailableUnitRanks ranksWithLocales:cachedOnly:]_block_invoke_4 : 1100 -> 1092
~ _calc_yyparse : 9976 -> 9824
~ _yy_get_previous_state : 220 -> 212
~ _calc_yy_scan_bytes : 392 -> 388
~ sub_1c73c8adc -> sub_1c7bd6e30 : 772 -> 796
~ sub_1c73c8e60 -> sub_1c7bd71cc : 1412 -> 1436
~ sub_1c73c96b4 -> sub_1c7bd7a38 : 524 -> 508
~ sub_1c73cabd4 -> sub_1c7bd8f48 : 1240 -> 1264
~ sub_1c73cbfc8 -> sub_1c7bda354 : 180 -> 192
~ sub_1c73cc07c -> sub_1c7bda414 : 504 -> 520
~ sub_1c73cc380 -> sub_1c7bda728 : 180 -> 192
~ sub_1c73cc528 -> sub_1c7bda8dc : 24 -> 20
~ sub_1c73cc540 -> sub_1c7bda8f0 : 84 -> 80
~ sub_1c73cc594 -> sub_1c7bda940 : 60 -> 56
~ sub_1c73cc5d0 -> sub_1c7bda978 : 80 -> 76
~ sub_1c73cc628 -> sub_1c7bda9cc : 28 -> 24
~ sub_1c73ccf90 -> sub_1c7bdb330 : 2700 -> 2716
~ sub_1c73cecbc -> sub_1c7bdd06c : 732 -> 744
~ sub_1c73cefc8 -> sub_1c7bdd384 : 19900 -> 19912
~ sub_1c73d524c -> sub_1c7be3614 : 3588 -> 3592
~ sub_1c73d6280 -> sub_1c7be464c : 132 -> 144
~ sub_1c73d6450 -> sub_1c7be4828 : 6964 -> 6976
~ sub_1c73d8df8 -> sub_1c7be71dc : 380 -> 376
~ sub_1c73d9158 -> sub_1c7be7538 : 1400 -> 1424
~ sub_1c73d96d0 -> sub_1c7be7ac8 : 1420 -> 1444
~ sub_1c73db2f8 -> sub_1c7be9708 : 344 -> 340
~ sub_1c73db6bc -> sub_1c7be9ac8 : 248 -> 252
~ sub_1c73dc058 -> sub_1c7bea468 : 272 -> 276
~ sub_1c73dc168 -> sub_1c7bea57c : 236 -> 256
~ sub_1c73dc254 -> sub_1c7bea67c : 256 -> 264
~ sub_1c73e6048 -> sub_1c7bf4478 : 504 -> 488
~ sub_1c73e6240 -> sub_1c7bf4660 : 792 -> 812
~ sub_1c73ecf7c -> sub_1c7bfb3b0 : 364 -> 356
~ sub_1c73ed0e8 -> sub_1c7bfb514 : 252 -> 276
~ sub_1c73ef1f8 -> sub_1c7bfd63c : 3564 -> 3544
~ sub_1c73f0edc -> sub_1c7bff30c : 516 -> 524
~ sub_1c73f1338 -> sub_1c7bff770 : 1312 -> 1276
~ sub_1c73f1cc0 -> sub_1c7c000d4 : 456 -> 512
~ sub_1c73f685c -> sub_1c7c04ca8 : 276 -> 256
~ sub_1c73faee8 -> sub_1c7c09320 : 884 -> 888
~ sub_1c73fb408 -> sub_1c7c09844 : 248 -> 272
~ sub_1c73fdec8 -> sub_1c7c0c31c : 208 -> 220
~ sub_1c73fe024 -> sub_1c7c0c484 : 208 -> 220
~ sub_1c73fe240 -> sub_1c7c0c6ac : 24 -> 20
~ sub_1c73fe258 -> sub_1c7c0c6c0 : 84 -> 80
~ sub_1c73fe2ac -> sub_1c7c0c710 : 60 -> 56
~ sub_1c73fe2e8 -> sub_1c7c0c748 : 80 -> 76
~ sub_1c73fe340 -> sub_1c7c0c79c : 28 -> 24
~ sub_1c73fe938 -> sub_1c7c0cd90 : 1824 -> 1816
~ sub_1c7401a94 -> sub_1c7c0fee4 : 704 -> 700
~ sub_1c7403880 -> sub_1c7c11ccc : 376 -> 384
~ sub_1c74082d4 -> sub_1c7c16728 : 2680 -> 2696
~ sub_1c740a880 -> sub_1c7c18ce4 : 716 -> 724
~ sub_1c740b44c -> sub_1c7c198b8 : 1336 -> 1340
~ sub_1c740b984 -> sub_1c7c19df4 : 2496 -> 2516
~ sub_1c740c344 -> sub_1c7c1a7c8 : 164 -> 176
~ sub_1c740c440 -> sub_1c7c1a8d0 : 704 -> 720
~ sub_1c740d804 -> sub_1c7c1bca4 : 948 -> 956
~ sub_1c740dc88 -> sub_1c7c1c130 : 2112 -> 2120
~ sub_1c7412530 -> sub_1c7c209e0 : 360 -> 352
~ sub_1c7412698 -> sub_1c7c20b40 : 368 -> 360
~ sub_1c7413c88 -> sub_1c7c22128 : 112 -> 124
~ sub_1c741a5b4 -> sub_1c7c28a60 : 1224 -> 1232
~ sub_1c741ae50 -> sub_1c7c29304 : 924 -> 920
~ sub_1c741c83c -> sub_1c7c2acec : 364 -> 356
~ sub_1c741caac -> sub_1c7c2af54 : 1332 -> 1312
~ sub_1c741cfe0 -> sub_1c7c2b474 : 272 -> 288
~ sub_1c741d0f0 -> sub_1c7c2b594 : 652 -> 672
~ sub_1c741e3b0 -> sub_1c7c2c868 : 328 -> 332
~ sub_1c741ef1c -> sub_1c7c2d3d8 : 96 -> 92
~ sub_1c7421290 -> sub_1c7c2f748 : 2592 -> 2496
~ ___dpml_bid_exception : 172 -> 176
~ ___dpml_bid_ux_cmp__ : 152 -> 144
~ ___dpml_bid_ux_asin_acos__ : 432 -> 428
~ _bid_f128_lgamma : 1412 -> 1372
~ ___dpml_bid_addsub__ : 468 -> 480
~ ___dpml_bid_unpack_x_or_y__ : 520 -> 524
~ ___dpml_bid_evaluate_packed_poly__ : 208 -> 204
~ ___dpml_bid_evaluate_rational__ : 560 -> 552
~ ___eval_neg_poly : 704 -> 720
~ ___eval_pos_poly : 816 -> 844
~ ___dpml_bid_ux_degree_reduce__ : 672 -> 668
~ ___bid128_div : 5532 -> 5536
~ _bid128_ext_fma : 18300 -> 18232
~ _bid_bid_nr_digits256 : 376 -> 368
~ ___bid128_pow : 11608 -> 11604
~ ___bid128_to_string : 2888 -> 2912
~ ___bid128_to_int32_int : 1432 -> 1416
~ ___bid128_to_binary64 : 1600 -> 1588
~ ___bid128_to_binary128 : 1720 -> 1700
~ _bid128_to_binary128_2part : 1712 -> 1692
```
