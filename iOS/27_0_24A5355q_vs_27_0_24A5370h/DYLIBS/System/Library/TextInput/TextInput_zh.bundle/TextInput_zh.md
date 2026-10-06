## TextInput_zh

> `/System/Library/TextInput/TextInput_zh.bundle/TextInput_zh`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc084` | `0xc0f0` | **`+0x6c`** |
| `__TEXT.__oslogstring` | `0x20` | `0x84` | **`+0x64`** |
| `__TEXT.__unwind_info` | `0x620` | `0x628` | **`+0x8`** |

### Other Changes

```diff

-3557.12.1.0.0
+3557.15.100.0.0

-  Functions: 416
-  Symbols:   769
-  CStrings:  134
+  Functions: 417
+  Symbols:   771
+  CStrings:  135
Symbols:
+ _TIInputManagerOSLogFacility
+ _TIShouldLogCandidateRequestLifecycle
Functions:
~ -[TIKeyboardInputManager_zh_SegmentAdjust handleKeyboardInput:] : 996 -> 1000
~ -[TIZhuyinPunctuationManager candidatesFor:] : 500 -> 496
~ -[TIKeyboardInputManager_zh_Toneless groupedCandidatesFromCandidates:usingSortingMethod:] : 568 -> 564
~ -[TIKeyboardInputManagerLiveConversion_zh _notifyUpdateCandidates:forOperation:] : 632 -> 628
~ -[TIKeyboardInputManagerLiveConversion_zh closeCandidateGenerationContextWithResults:] : 64 -> 148
~ -[TIKeyboardInputManager_zh_RetroCorrection groupedCandidatesFromCandidates:usingSortingMethod:] : 568 -> 564
~ -[TIKeyboardInputManager_zh_RetroCorrection updateInlineCandidate] : 836 -> 832
~ -[TIZhuyinInputManager inputStringForCharacters:] : 508 -> 504
~ -[TIKeyboardInputManager_zh_SegmentPicker markedText] : 604 -> 600
~ -[TIKeyboardInputManager_zh_Candidates candidateResultSetFromCandidateResultSet:lastCharacterCandidateResultSet:] : 1428 -> 1420
~ -[TIKeyboardInputManager_zh_Candidates punctuationCandiadtesFor:withAutoCommit:] : 540 -> 536
~ -[TIKeyboardInputManager_zh_Candidates hasIdeographicCandidates] : 544 -> 536
+ -[TIKeyboardInputManagerLiveConversion_zh closeCandidateGenerationContextWithResults:].cold.1
CStrings:
+ "[Zhuyin] Dropping passed-in candidate results: live-conversion override always passes nil to super."
```
