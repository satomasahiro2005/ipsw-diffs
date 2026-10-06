## chtrom.dylib

> `/System/Library/PrivateFrameworks/TextToSpeechKonaSupport.framework/Frameworks/chtrom.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10160` | `0x10178` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x4f0` | `0x504` | **`+0x14`** |

### Other Changes

```diff

-675.1.0.0.0
+676.0.0.0.0

-  Functions: 618
+  Functions: 621
Functions:
~ _isPinYin : 424 -> 440
~ _isChiSentSeptor : 140 -> 160
~ __ZN6PinYin11Code2PinyinEPKcPci : 244 -> 264
~ __Z15getAnsiCharTypePKc : 176 -> 180
~ _isAnsiSentSeptor : 120 -> 128
~ _binarySearch : 204 -> 220
~ __ZN7ChiDict9initDictsEv : 180 -> 184
~ __ZN7ChiDict10wordLookupE11ChiDictTypePKct : 376 -> 400
~ __ZN7Lexicon15getWordlistsLenEv : 56 -> 52
~ __ZN7Lexicon10setCounterEPi : 52 -> 60
~ __ZN8SpecDict12outputPinyinEP12WordPropertyPKcS3_Pcj : 780 -> 740
~ __ZN8SpecDict14kickoffBracketEPKcPi : 364 -> 356
~ __ZN8SpecDict16processConditionEP12WordPropertyPKcij : 392 -> 396
~ __ZN8SpecDict9getPinyinEP12WordPropertyPKcihj : 344 -> 348
~ __ZN8SpecDict15processBaseCondEP12WordPropertyPKcij : 960 -> 972
~ __ZN8SpecDict16processChiSpecAAEP12WordPropertyPc : 472 -> 488
~ __ZN8SpecDict16processChiSpec10EPKcP12WordProperty : 272 -> 288
~ __ZN17WordsPropertyList9nextIndexEv : 76 -> 80
~ __ZN21ThreeWordPropertyList12matchPatternEiii : 116 -> 120
~ __ZN21ThreeWordPropertyList7getWordEP12WordProperty : 248 -> 252
~ __ZN12PinYinBufferD2Ev : 72 -> 80
~ __ZN13TextProcessor19pickupECIAnnotationEPKc : 252 -> 248
~ __ZN12PinYinOutput17outputTranslationEP12WordProperty : 428 -> 448
~ __ZN13TextProcessor12processChengEPc : 192 -> 184
~ __ZN13TextProcessor15pickupAnsiDigitEPKci : 316 -> 308
~ __ZN8SpecDict16processChiSpec31EP12WordProperty : 328 -> 332
~ __ZN8SpecDict17processChiSpec712EP12WordProperty : 456 -> 452
~ __ZN8SpecDict16processChiSpec70EP12WordProperty : 348 -> 344
~ __ZN11RomUserDict9maxLookupEPKc : 436 -> 380
~ __ZN15MatchedKeysInfoC2EPKcP11Translationii : 164 -> 140
~ __ZN15MatchedKeysInfoD2Ev : 200 -> 164
+ _OUTLINED_FUNCTION_0
~ __ZN13TextProcessor12matchSrcTextEPKciPi : 144 -> 148
~ __ZN13TextProcessor14adjustPropListEv : 1132 -> 1128
~ __ZN12SentenceUtil13getInitOffsetEv : 56 -> 60
~ __ZN12SentenceUtil10reMapBytesEii : 64 -> 68
~ _OUTLINED_FUNCTION_1 : 20 -> 8
+ _OUTLINED_FUNCTION_4
~ __ZN13TextProcessor16processAsciiTextEPKci : 588 -> 584
~ __ZN13TextProcessor13findFirstWordEPKciP12WordProperty : 744 -> 748
~ __ZN13TextProcessor14findSecondWordEPKcih : 388 -> 392
~ __ZN16UnicodeConverter10MBCSToUCS2EPKcPPt : 248 -> 252
~ __ZN12InputManager7getTextEPPcPjPKcj : 404 -> 400
~ _changeExtension : 128 -> 136
~ _hasExtension : 116 -> 128
~ _stripPath : 56 -> 60
~ _fileFindInPath : 396 -> 400
~ __ZN13ArrayListNode4dumpEv : 148 -> 144
~ __ZN3Key4dumpEv : 104 -> 100
~ __ZN12SkipListNodeC2Ei : 132 -> 128
~ __ZN8SkipList4saveEPKc : 560 -> 536
~ __ZN8SkipList4loadEPKc : 900 -> 908
~ __ZN8SkipList6insertEP3KeyP11Translation : 356 -> 344
~ __ZN8SkipList11multiSearchEP3Key : 392 -> 408
~ __ZN8SkipList6searchEP3Key : 140 -> 148
~ __ZN8SkipList6removeEP3Key : 328 -> 308
~ _OUTLINED_FUNCTION_0 : 60 -> 12
~ _OUTLINED_FUNCTION_1 : 36 -> 12
~ _OUTLINED_FUNCTION_2 : 16 -> 64
~ _OUTLINED_FUNCTION_3 : 20 -> 36
~ _OUTLINED_FUNCTION_4 : 24 -> 20
~ _OUTLINED_FUNCTION_5 : 24 -> 16
+ _OUTLINED_FUNCTION_6
~ __ZN11Translation4dumpEv : 192 -> 180
~ __ZN13IniFileWriter12stringSearchEPKcll : 308 -> 272
~ __ZN13IniFileWriter13writeToMemoryEPKcS1_S1_ : 292 -> 304
~ __ZN13IniFileWriter12goEndSectionEv : 80 -> 84
~ __ZN13IniFileWriter9goEndDataEPl : 52 -> 56
~ __ZN13IniFileWriter13deleteSectionEPKc : 292 -> 284
```
