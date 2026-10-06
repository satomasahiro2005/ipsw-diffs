## SpeakerRecognition

> `/System/Library/PrivateFrameworks/SpeakerRecognition.framework/SpeakerRecognition`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xba138` | `0xba538` | **`+0x400`** |
| `__TEXT.__oslogstring` | `0xee41` | `0xef0c` | **`+0xcb`** |
| `__TEXT.__cstring` | `0x10fa9` | `0x11068` | **`+0xbf`** |
| `__TEXT.__objc_methlist` | `0x6d90` | `0x6dd0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x3f18` | `0x3f40` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0xbc68` | `0xbc88` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2280` | `0x2290` | **`+0x10`** |
| `__DATA.__bss` | `0x708` | `0x700` | **`-0x8`** |
| `__DATA_DIRTY.__bss` | `0x68` | `0x70` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x874` | `0x878` | **`+0x4`** |

### Other Changes

```diff

-3605.23.1.0.0
+3605.25.1.0.0

-  Functions: 3096
-  Symbols:   5000
-  CStrings:  2650
+  Functions: 3102
+  Symbols:   5007
+  CStrings:  2657
Symbols:
+ -[CSVTUITrainingSession hasLiveSpeechTranscriber]
+ -[CSVTUITrainingSession hasUsableRecognizer]
+ -[CSVTUITrainingSessionWithPayload _deferCloseForTranscriberFinal]
+ -[CSVTUITrainingSessionWithPayload _firedTranscriberFinalTimeout]
+ -[CSVTUITrainingSessionWithPayload _registerTranscriberFinalTimeout]
+ GCC_except_table1661
+ GCC_except_table1766
+ GCC_except_table1781
+ GCC_except_table1791
+ GCC_except_table1801
+ GCC_except_table1806
+ GCC_except_table1822
+ GCC_except_table1826
+ GCC_except_table1836
+ GCC_except_table1844
+ GCC_except_table1908
+ GCC_except_table1912
+ GCC_except_table1973
+ GCC_except_table2008
+ GCC_except_table2074
+ GCC_except_table2084
+ GCC_except_table2093
+ GCC_except_table2104
+ GCC_except_table2113
+ GCC_except_table2132
+ GCC_except_table2194
+ _OBJC_IVAR_$_CSVTUITrainingSessionWithPayload._awaitingTranscriberFinal
+ ___68-[CSVTUITrainingSessionWithPayload _registerTranscriberFinalTimeout]_block_invoke
- GCC_except_table1657
- GCC_except_table1754
- GCC_except_table1775
- GCC_except_table1785
- GCC_except_table1795
- GCC_except_table1800
- GCC_except_table1816
- GCC_except_table1820
- GCC_except_table1824
- GCC_except_table1838
- GCC_except_table1902
- GCC_except_table1906
- GCC_except_table1967
- GCC_except_table2002
- GCC_except_table2068
- GCC_except_table2078
- GCC_except_table2087
- GCC_except_table2098
- GCC_except_table2107
- GCC_except_table2126
- GCC_except_table2188
CStrings:
+ "%s Finalizing speech transcriber; awaiting final result"
+ "%s No usable recognizer; using no-SpeechAPI EOS timeout"
+ "%s Transcriber final result did not arrive; closing session"
+ "%s Using SpeechAPI EOS timeout"
+ "-[CSVTUITrainingSessionWithPayload _deferCloseForTranscriberFinal]"
+ "-[CSVTUITrainingSessionWithPayload _firedTranscriberFinalTimeout]"
+ "-[CSVTUITrainingSessionWithPayload _getSessionEOSTimeout]"
```
