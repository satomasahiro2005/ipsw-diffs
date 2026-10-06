## ScreenReaderOutput

> `/System/Library/PrivateFrameworks/ScreenReaderOutput.framework/ScreenReaderOutput`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9cbf4` | `0x9dc3c` | **`+0x1048`** |
| `__TEXT.__objc_methlist` | `0x9008` | `0x9200` | **`+0x1f8`** |
| `__AUTH_CONST.__objc_const` | `0xbc58` | `0xbd48` | **`+0xf0`** |
| `__DATA_CONST.__objc_selrefs` | `0x4780` | `0x4850` | **`+0xd0`** |
| `__AUTH_CONST.__cfstring` | `0x5680` | `0x5740` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x5b79` | `0x5c0c` | **`+0x93`** |
| `__TEXT.__unwind_info` | `0x28b8` | `0x2908` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x1270` | `0x1298` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x32a0` | `0x3280` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x193c` | `0x1950` | **`+0x14`** |
| `__DATA.__bss` | `0x1100` | `0x10f0` | **`-0x10`** |
| `__DATA.__data` | `0x1680` | `0x1690` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x8c8` | `0x8d4` | **`+0xc`** |
| `__TEXT.__oslogstring` | `0x287d` | `0x287a` | **`-0x3`** |

### Other Changes

```diff

-465.0.0.0.0
+467.3.0.0.0

-  Functions: 3974
-  Symbols:   5771
-  CStrings:  1077
+  Functions: 4010
+  Symbols:   5812
+  CStrings:  1081
Symbols:
+ -[SCROBrailleClient setTabularFocusRow:col:]
+ -[SCROBrailleClient setTabularZoomLevel:]
+ -[SCROBrailleClientXPC setTabularFocusRow:col:]
+ -[SCROBrailleClientXPC setTabularZoomLevel:]
+ -[SCROBrailleDisplay handleCommandTabularZoomInEvent:forDispatcher:]
+ -[SCROBrailleDisplay handleCommandTabularZoomOutEvent:forDispatcher:]
+ -[SCROBrailleDisplayCommandDispatcher _handleTabularZoomInEvent:]
+ -[SCROBrailleDisplayCommandDispatcher _handleTabularZoomOutEvent:]
+ -[SCROBrailleDisplayManager _eventQueue_stepTabularZoomIn:]
+ -[SCROBrailleDisplayManager brailleDisplay:structuredBrailleRouterHitTabularCellWithKey:tableRow:tableCol:appToken:]
+ -[SCROBrailleDisplayManager brailleDisplay:structuredBrailleRouterHitTabularFocusedCellWithKey:appToken:]
+ -[SCROBrailleDisplayManager brailleDisplay:structuredBrailleRouterHitTabularStatusLineWithKey:appToken:]
+ -[SCROBrailleDisplayManager brailleDisplay:tabularZoomInWithKey:]
+ -[SCROBrailleDisplayManager brailleDisplay:tabularZoomOutWithKey:]
+ -[SCROBrailleDisplayManager setTabularFocusRow:col:]
+ -[SCROBrailleDisplayManager setTabularZoomLevel:]
+ -[SCROBrailleDisplayManager tabularZoomDidChange:]
+ -[SCROBrailleHandler handleTabularZoomDidChange:]
+ -[SCROBrailleHandlerXPC handleTabularZoomDidChange:]
+ -[SCROBrailleHandlerXPC setTabularFocusRow:col:]
+ -[SCROBrailleHandlerXPC setTabularZoomLevel:]
+ -[SCROBrailleKey _resetTabularCellRoute]
+ -[SCROBrailleKey isTabularCellRoute]
+ -[SCROBrailleKey setIsTabularCellRoute:]
+ -[SCROBrailleKey setTabularCellCol:]
+ -[SCROBrailleKey setTabularCellRow:]
+ -[SCROBrailleKey tabularCellCol]
+ -[SCROBrailleKey tabularCellRow]
+ GCC_except_table1020
+ GCC_except_table1084
+ GCC_except_table1086
+ GCC_except_table1088
+ GCC_except_table1090
+ GCC_except_table1152
+ GCC_except_table1180
+ GCC_except_table1185
+ GCC_except_table1189
+ GCC_except_table1192
+ GCC_except_table1194
+ GCC_except_table1225
+ GCC_except_table1232
+ GCC_except_table128
+ GCC_except_table129
+ GCC_except_table132
+ GCC_except_table1362
+ GCC_except_table1571
+ GCC_except_table1693
+ GCC_except_table1832
+ GCC_except_table1834
+ GCC_except_table1842
+ GCC_except_table1852
+ GCC_except_table1936
+ GCC_except_table1981
+ GCC_except_table1985
+ GCC_except_table2097
+ GCC_except_table2118
+ GCC_except_table2123
+ GCC_except_table2129
+ GCC_except_table2228
+ GCC_except_table2415
+ GCC_except_table2433
+ GCC_except_table2549
+ GCC_except_table2550
+ GCC_except_table2551
+ GCC_except_table2555
+ GCC_except_table2560
+ GCC_except_table2561
+ GCC_except_table2562
+ GCC_except_table2563
+ GCC_except_table2564
+ GCC_except_table2566
+ GCC_except_table2567
+ GCC_except_table2568
+ GCC_except_table2572
+ GCC_except_table2577
+ GCC_except_table2579
+ GCC_except_table2582
+ GCC_except_table2942
+ GCC_except_table2961
+ GCC_except_table2962
+ GCC_except_table2963
+ GCC_except_table3026
+ GCC_except_table3028
+ GCC_except_table3030
+ GCC_except_table3031
+ GCC_except_table3033
+ GCC_except_table3035
+ GCC_except_table440
+ GCC_except_table451
+ GCC_except_table483
+ GCC_except_table484
+ GCC_except_table506
+ GCC_except_table507
+ GCC_except_table517
+ GCC_except_table519
+ GCC_except_table537
+ GCC_except_table538
+ GCC_except_table544
+ GCC_except_table547
+ GCC_except_table557
+ GCC_except_table577
+ GCC_except_table579
+ GCC_except_table580
+ GCC_except_table588
+ GCC_except_table590
+ GCC_except_table596
+ GCC_except_table610
+ GCC_except_table612
+ GCC_except_table613
+ GCC_except_table619
+ GCC_except_table620
+ GCC_except_table626
+ GCC_except_table64
+ GCC_except_table645
+ GCC_except_table648
+ GCC_except_table846
+ GCC_except_table887
+ GCC_except_table889
+ OBJC_IVAR_$_SCROBrailleKey._isTabularCellRoute
+ OBJC_IVAR_$_SCROBrailleKey._tabularCellCol
+ OBJC_IVAR_$_SCROBrailleKey._tabularCellRow
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_BRLLayoutManagerDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_SCROBrailleDisplayDelegate
+ ___104-[SCROBrailleDisplayManager brailleDisplay:structuredBrailleRouterHitTabularStatusLineWithKey:appToken:]_block_invoke
+ ___104-[SCROBrailleDisplayManager brailleDisplay:structuredBrailleRouterHitTabularStatusLineWithKey:appToken:]_block_invoke_2
+ ___105-[SCROBrailleDisplayManager brailleDisplay:structuredBrailleRouterHitTabularFocusedCellWithKey:appToken:]_block_invoke
+ ___105-[SCROBrailleDisplayManager brailleDisplay:structuredBrailleRouterHitTabularFocusedCellWithKey:appToken:]_block_invoke_2
+ ___116-[SCROBrailleDisplayManager brailleDisplay:structuredBrailleRouterHitTabularCellWithKey:tableRow:tableCol:appToken:]_block_invoke
+ ___116-[SCROBrailleDisplayManager brailleDisplay:structuredBrailleRouterHitTabularCellWithKey:tableRow:tableCol:appToken:]_block_invoke_2
+ ___49-[SCROBrailleDisplayManager setTabularZoomLevel:]_block_invoke
+ ___52-[SCROBrailleDisplayManager setTabularFocusRow:col:]_block_invoke
+ ___52-[SCROBrailleHandlerXPC handleTabularZoomDidChange:]_block_invoke
+ ___59-[SCROBrailleDisplayManager _eventQueue_stepTabularZoomIn:]_block_invoke
+ ___block_descriptor_80_e8_32s40s48s56s_e5_v8?0ls32l8s40l8s48l8s56l8
+ _kSCROBraillePrintTextRowsAttribute
- GCC_except_table1062
- GCC_except_table1064
- GCC_except_table1066
- GCC_except_table1068
- GCC_except_table1130
- GCC_except_table1158
- GCC_except_table1163
- GCC_except_table1167
- GCC_except_table1170
- GCC_except_table1172
- GCC_except_table1203
- GCC_except_table1210
- GCC_except_table126
- GCC_except_table127
- GCC_except_table130
- GCC_except_table1332
- GCC_except_table1537
- GCC_except_table1657
- GCC_except_table1796
- GCC_except_table1798
- GCC_except_table1806
- GCC_except_table1816
- GCC_except_table1900
- GCC_except_table1945
- GCC_except_table1949
- GCC_except_table2061
- GCC_except_table2082
- GCC_except_table2087
- GCC_except_table2093
- GCC_except_table2192
- GCC_except_table2379
- GCC_except_table2397
- GCC_except_table2513
- GCC_except_table2514
- GCC_except_table2515
- GCC_except_table2519
- GCC_except_table2524
- GCC_except_table2525
- GCC_except_table2526
- GCC_except_table2527
- GCC_except_table2528
- GCC_except_table2530
- GCC_except_table2531
- GCC_except_table2532
- GCC_except_table2536
- GCC_except_table2541
- GCC_except_table2543
- GCC_except_table2546
- GCC_except_table2890
- GCC_except_table2906
- GCC_except_table2925
- GCC_except_table2927
- GCC_except_table2990
- GCC_except_table2992
- GCC_except_table2994
- GCC_except_table2995
- GCC_except_table2997
- GCC_except_table2999
- GCC_except_table438
- GCC_except_table449
- GCC_except_table481
- GCC_except_table482
- GCC_except_table502
- GCC_except_table503
- GCC_except_table513
- GCC_except_table515
- GCC_except_table533
- GCC_except_table534
- GCC_except_table536
- GCC_except_table539
- GCC_except_table553
- GCC_except_table573
- GCC_except_table575
- GCC_except_table576
- GCC_except_table584
- GCC_except_table586
- GCC_except_table592
- GCC_except_table606
- GCC_except_table607
- GCC_except_table608
- GCC_except_table609
- GCC_except_table616
- GCC_except_table618
- GCC_except_table62
- GCC_except_table640
- GCC_except_table641
- GCC_except_table824
- GCC_except_table865
- GCC_except_table867
- GCC_except_table998
- ___isBrailleXPCOn_block_invoke
- _isBrailleXPCOn
- _isBrailleXPCOn.brailleXPCOn
- _isBrailleXPCOn.onceToken
CStrings:
+ "SCROBraillePrintTextRowsAttribute"
+ "VOTEventCommandBrailleTabularZoomIn"
+ "VOTEventCommandBrailleTabularZoomOut"
+ "_isTabularCellRoute"
+ "_tabularCellCol"
+ "_tabularCellRow"
+ "setTabularFocusRow requires XPC"
+ "setTabularZoomLevel ignoring out-of-range level"
+ "setTabularZoomLevel requires XPC"
- "Braille_XPC"
- "SCROBrailleClient using Mach"
- "SCROBrailleClient using XPC"
- "SCROBrailleHandler using Mach"
- "SCROBrailleHandler using XPC"
```
