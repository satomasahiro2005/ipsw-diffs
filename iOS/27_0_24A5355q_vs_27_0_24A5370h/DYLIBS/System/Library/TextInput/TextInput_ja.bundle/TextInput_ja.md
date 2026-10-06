## TextInput_ja

> `/System/Library/TextInput/TextInput_ja.bundle/TextInput_ja`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e448` | `0x1e4c0` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0xf7` | `0x144` | **`+0x4d`** |
| `__TEXT.__unwind_info` | `0x960` | `0x968` | **`+0x8`** |

### Other Changes

```diff

-3557.12.1.0.0
+3557.15.100.0.0

-  Functions: 744
-  Symbols:   1312
-  CStrings:  323
+  Functions: 745
+  Symbols:   1314
+  CStrings:  324
Symbols:
+ _TIInputManagerOSLogFacility
+ _TIShouldLogCandidateRequestLifecycle
+ __ZNSt3__119__shared_weak_count16__release_sharedB9fon220106Ev
- __ZNSt3__119__shared_weak_count16__release_sharedB9fon220100Ev
Functions:
~ +[Romakana splitRomaji:at:] : 1328 -> 1324
~ -[TIKeyboardInputManager_ja_Kana calculateGeometryForInput:] : 1616 -> 1620
~ -[TIKeyboardInputManager_ja_Kana geometryDataWithSubstitutedMultitapKeys:] : 328 -> 336
~ -[TIKeyboardInputManager_ja_Kana addInput:withContext:] : 2872 -> 2880
~ -[TIKeyboardInputManagerLiveConversion_ja shouldShowPredictionCandidate:] : 392 -> 388
~ +[TIKeyboardInputManager_ja_Romaji _convertToKana:] : 756 -> 752
~ -[TIKeyboardInputManager_ja_Romaji updateState] : 1976 -> 1972
~ -[TIKeyboardInputManager_ja_Romaji addInput:withContext:] : 1584 -> 1580
~ -[TIKeyboardInputManager_ja_Romaji deleteFromInput:] : 3452 -> 3448
~ -[TIMarkedTextBuffer_ja_Romaji updateStateWithInputIndex:] : 744 -> 740
~ -[TIKeyboardInputManagerLiveConversion_ja_Romaji addInput:withContext:] : 1184 -> 1180
~ -[TIKeyboardInputManagerLiveConversion_ja_Romaji updateState] : 632 -> 628
~ -[TIKeyboardInputManager_ja_Candidates indexFromTransliterationType:] : 48 -> 44
~ -[TIKeyboardInputManager_ja_Candidates candidateResultSetFromCandidates:proactiveTriggers:] : 648 -> 652
~ -[TIKeyboardInputManager_ja_Candidates sortingMethods] : 380 -> 392
~ +[TIKeyboardInputManager_ja addFullwidthAnnotationToResultSet:] : 720 -> 712
~ -[TIKeyboardInputManager_ja _notifyUpdateCandidates:forOperation:] : 824 -> 876
~ -[TIKeyboardInputManager_ja lockAnyDrawInputResults] : 568 -> 564
~ -[TIKeyboardInputManager_ja didAcceptCandidate:] : 2524 -> 2520
~ -[TICandidateSorter init] : 652 -> 648
~ -[TICandidateSorter hasCandidatesSortedByRadicalFromCandidates:] : 392 -> 388
~ -[TICandidateSorter candidatesSortedByRadicalFromCandidates:] : 1296 -> 1284
~ -[TICandidateSorter candidatesSortedByYomiFromCandidates:inputString:] : 1792 -> 1780
~ -[TICandidateSorter hasCandidatesSortedByFacemarkCategoryFromCandidates:] : 288 -> 284
~ -[TICandidateSorter hasCandidatesSortedByEmojiCategoryFromCandidates:] : 260 -> 256
~ -[TIKeyboardInputManagerLiveConversion_ja_Kana addInput:withContext:] : 1196 -> 1192
+ -[TIKeyboardInputManager_ja _notifyUpdateCandidates:forOperation:].cold.1
CStrings:
+ "[Japanese] Dropping candidates: shouldSkipCandidateSelection is set. mode=%@"
```
