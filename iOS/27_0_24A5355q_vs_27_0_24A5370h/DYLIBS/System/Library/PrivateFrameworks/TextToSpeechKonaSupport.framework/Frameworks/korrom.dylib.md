## korrom.dylib

> `/System/Library/PrivateFrameworks/TextToSpeechKonaSupport.framework/Frameworks/korrom.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8578` | `0x8530` | **`-0x48`** |
| `__TEXT.__gcc_except_tab` | `0x390` | `0x3a0` | **`+0x10`** |

### Other Changes

```diff

-675.1.0.0.0
+676.0.0.0.0

-  Functions: 395
-  Symbols:   521
+  Functions: 396
+  Symbols:   522
Symbols:
+ _OUTLINED_FUNCTION_6
Functions:
~ __ZN7han2Rom11getCharTypeEPKc : 616 -> 620
~ __ZN7han2Rom15johabCode2RomanEtPc : 180 -> 172
~ _OUTLINED_FUNCTION_1 : 20 -> 12
+ _OUTLINED_FUNCTION_2
~ __ZN15korTextAnalysis14lookupUserDictEPKcPcPt : 460 -> 464
~ __ZN15korTextAnalysis9parseTextEPKctPt : 572 -> 568
~ __ZN15korTextAnalysis14convertSpecialEPKc : 128 -> 132
~ __ZN7rom2Han9translateEPKcPc : 184 -> 180
~ __ZN7rom2Han7getSyllEPKcaP8Syllable : 312 -> 320
~ __ZN7rom2Han23romanCode2JohabTableIdxEP8SyllablePt : 368 -> 392
- _OUTLINED_FUNCTION_0
~ __ZN11RomUserDict7makeKeyEPhlPcPl : 252 -> 248
~ __ZN16UnicodeConverter10MBCSToUCS2EPKcPPt : 292 -> 296
~ __ZN12InputManager7getTextEPPcPjPKcj : 404 -> 400
~ _dynaBufAddString : 208 -> 204
~ _dynaBufAddDynaBuf : 236 -> 220
~ _dynaBufDeleteChars : 84 -> 80
~ _dynaBufChar : 48 -> 40
~ _dynaBufExtract : 104 -> 96
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
