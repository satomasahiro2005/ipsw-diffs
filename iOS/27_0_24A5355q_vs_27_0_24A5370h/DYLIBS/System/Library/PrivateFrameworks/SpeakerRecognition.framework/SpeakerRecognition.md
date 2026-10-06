## SpeakerRecognition

> `/System/Library/PrivateFrameworks/SpeakerRecognition.framework/SpeakerRecognition`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb7888` | `0xb83b4` | **`+0xb2c`** |
| `__TEXT.__cstring` | `0x10d7e` | `0x10eca` | **`+0x14c`** |
| `__AUTH.__objc_data` | `0x1d18` | `0x1df8` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0xece5` | `0xedc0` | **`+0xdb`** |
| `__AUTH.__data` | `0x5b0` | `0x518` | **`-0x98`** |
| `__TEXT.__objc_methlist` | `0x6d08` | `0x6d88` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x21a8` | `0x21f0` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x2928` | `0x2968` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x3ed8` | `0x3f10` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0xbbc8` | `0xbbb8` | **`-0x10`** |
| `__TEXT.__const` | `0xf88` | `0xf98` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x870` | `0x874` | **`+0x4`** |

### Other Changes

```diff

-3600.64.114.1.5
+3600.70.8.0.0

-  Functions: 3050
-  Symbols:   4973
-  CStrings:  2635
+  Functions: 3071
+  Symbols:   4991
+  CStrings:  2644
Symbols:
+ -[CSVTUITrainingSession recognizedTextPassesWERCheck:]
+ -[CSVTUITrainingSession referenceString]
+ -[CSVTUITrainingSession setReferenceString:]
+ -[SSRVTUITrainingManager _trainUtteranceLocally:shouldUseASR:mhUUID:referenceString:completionWithResult:]
+ -[SSRVTUITrainingManager trainUtteranceWithReferenceString:completionWithResult:]
+ -[SSRVTUITrainingMessageHandler trainUtteranceWithReferenceStringViaXPC:completionWithResult:]
+ -[SSRVTUITrainingServiceClient trainUtteranceWithReferenceStringViaXPC:completionWithResult:]
+ GCC_except_table1007
+ GCC_except_table1010
+ GCC_except_table1012
+ GCC_except_table1013
+ GCC_except_table1015
+ GCC_except_table1017
+ GCC_except_table1018
+ GCC_except_table1020
+ GCC_except_table1023
+ GCC_except_table1100
+ GCC_except_table1122
+ GCC_except_table1176
+ GCC_except_table1180
+ GCC_except_table1198
+ GCC_except_table1298
+ GCC_except_table1299
+ GCC_except_table1301
+ GCC_except_table1322
+ GCC_except_table1340
+ GCC_except_table1344
+ GCC_except_table1405
+ GCC_except_table1411
+ GCC_except_table1415
+ GCC_except_table1422
+ GCC_except_table1429
+ GCC_except_table1437
+ GCC_except_table1466
+ GCC_except_table1515
+ GCC_except_table1530
+ GCC_except_table1546
+ GCC_except_table1553
+ GCC_except_table1600
+ GCC_except_table1607
+ GCC_except_table1629
+ GCC_except_table1652
+ GCC_except_table1749
+ GCC_except_table1755
+ GCC_except_table1770
+ GCC_except_table1780
+ GCC_except_table1790
+ GCC_except_table1795
+ GCC_except_table1811
+ GCC_except_table1815
+ GCC_except_table1819
+ GCC_except_table1825
+ GCC_except_table1833
+ GCC_except_table1897
+ GCC_except_table1901
+ GCC_except_table1962
+ GCC_except_table1997
+ GCC_except_table2063
+ GCC_except_table2073
+ GCC_except_table2082
+ GCC_except_table2093
+ GCC_except_table2102
+ GCC_except_table2121
+ GCC_except_table2183
+ GCC_except_table446
+ GCC_except_table507
+ GCC_except_table559
+ GCC_except_table563
+ GCC_except_table578
+ GCC_except_table591
+ GCC_except_table667
+ GCC_except_table676
+ GCC_except_table682
+ GCC_except_table777
+ GCC_except_table855
+ GCC_except_table896
+ GCC_except_table901
+ GCC_except_table917
+ GCC_except_table920
+ _OBJC_CLASS_$__TtC18SpeakerRecognition26SSREnrollmentWERCalculator
+ _OBJC_IVAR_$_CSVTUITrainingSession._referenceString
+ _OBJC_METACLASS_$__TtC18SpeakerRecognition26SSREnrollmentWERCalculator
+ __INSTANCE_METHODS__TtC18SpeakerRecognition26SSREnrollmentWERCalculator
+ ___106-[SSRVTUITrainingManager _trainUtteranceLocally:shouldUseASR:mhUUID:referenceString:completionWithResult:]_block_invoke
+ ___106-[SSRVTUITrainingManager _trainUtteranceLocally:shouldUseASR:mhUUID:referenceString:completionWithResult:]_block_invoke_2
+ ___81-[SSRVTUITrainingManager trainUtteranceWithReferenceString:completionWithResult:]_block_invoke
+ ___81-[SSRVTUITrainingManager trainUtteranceWithReferenceString:completionWithResult:]_block_invoke_2
+ ___81-[SSRVTUITrainingManager trainUtteranceWithReferenceString:completionWithResult:]_block_invoke_3
+ ___93-[SSRVTUITrainingServiceClient trainUtteranceWithReferenceStringViaXPC:completionWithResult:]_block_invoke
+ ___93-[SSRVTUITrainingServiceClient trainUtteranceWithReferenceStringViaXPC:completionWithResult:]_block_invoke_2
+ ___block_descriptor_81_e8_32s40s48s56bs64w_e5_v8?0ls32l8w64l8s40l8s56l8s48l8
- GCC_except_table1000
- GCC_except_table1001
- GCC_except_table1004
- GCC_except_table1005
- GCC_except_table1091
- GCC_except_table1113
- GCC_except_table1167
- GCC_except_table1171
- GCC_except_table1189
- GCC_except_table1289
- GCC_except_table1290
- GCC_except_table1292
- GCC_except_table1313
- GCC_except_table1317
- GCC_except_table1331
- GCC_except_table1396
- GCC_except_table1402
- GCC_except_table1406
- GCC_except_table1410
- GCC_except_table1413
- GCC_except_table1420
- GCC_except_table1457
- GCC_except_table1506
- GCC_except_table1521
- GCC_except_table1537
- GCC_except_table1544
- GCC_except_table1598
- GCC_except_table1620
- GCC_except_table1737
- GCC_except_table1743
- GCC_except_table1758
- GCC_except_table1768
- GCC_except_table1778
- GCC_except_table1783
- GCC_except_table1799
- GCC_except_table1803
- GCC_except_table1807
- GCC_except_table1813
- GCC_except_table1821
- GCC_except_table1885
- GCC_except_table1889
- GCC_except_table1950
- GCC_except_table1985
- GCC_except_table2051
- GCC_except_table2061
- GCC_except_table2070
- GCC_except_table2081
- GCC_except_table2090
- GCC_except_table2109
- GCC_except_table2171
- GCC_except_table443
- GCC_except_table504
- GCC_except_table556
- GCC_except_table560
- GCC_except_table575
- GCC_except_table588
- GCC_except_table663
- GCC_except_table672
- GCC_except_table674
- GCC_except_table768
- GCC_except_table846
- GCC_except_table887
- GCC_except_table892
- GCC_except_table908
- GCC_except_table911
- GCC_except_table993
- GCC_except_table994
- GCC_except_table997
- GCC_except_table998
- GCC_except_table999
- ___82-[SSRVTUITrainingManager trainUtterance:shouldUseASR:mhUUID:completionWithResult:]_block_invoke_4
- ___82-[SSRVTUITrainingManager trainUtterance:shouldUseASR:mhUUID:completionWithResult:]_block_invoke_5
- ___block_descriptor_73_e8_32s40s48bs56w_e5_v8?0ls32l8w56l8s40l8s48l8
CStrings:
+ "%s BEGIN hasRef:%{public}d"
+ "%s WER above threshold; closing with TRYAGAIN"
+ "%s hasRef : %d"
+ "%s invalid UUID format: %{public}@"
+ "%s remote device not found for UUID: %{public}@"
+ "-[SSRVTUITrainingManager _trainUtteranceLocally:shouldUseASR:mhUUID:referenceString:completionWithResult:]"
+ "-[SSRVTUITrainingManager _trainUtteranceLocally:shouldUseASR:mhUUID:referenceString:completionWithResult:]_block_invoke"
+ "-[SSRVTUITrainingManager _trainUtteranceLocally:shouldUseASR:mhUUID:referenceString:completionWithResult:]_block_invoke_2"
+ "-[SSRVTUITrainingManager trainUtteranceWithReferenceString:completionWithResult:]"
+ "-[SSRVTUITrainingMessageHandler trainUtteranceWithReferenceStringViaXPC:completionWithResult:]"
+ "WER calculation failed, defaulting to 0.0: %@"
- "-[SSRVTUITrainingManager trainUtterance:shouldUseASR:mhUUID:completionWithResult:]_block_invoke"
- "-[SSRVTUITrainingManager trainUtterance:shouldUseASR:mhUUID:completionWithResult:]_block_invoke_5"
```
