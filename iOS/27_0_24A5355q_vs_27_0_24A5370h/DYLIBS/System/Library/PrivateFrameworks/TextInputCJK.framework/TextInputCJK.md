## TextInputCJK

> `/System/Library/PrivateFrameworks/TextInputCJK.framework/TextInputCJK`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e5a4` | `0x1edd8` | **`+0x834`** |
| `__TEXT.__oslogstring` | `0x134` | `0x3b4` | **`+0x280`** |
| `__TEXT.__cstring` | `0xe89` | `0xfbc` | **`+0x133`** |
| `__AUTH_CONST.__auth_got` | `0x508` | `0x530` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c58` | `0x1c68` | **`+0x10`** |
| `__TEXT.__const` | `0xb0` | `0xc0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x6b0` | `0x6c0` | **`+0x10`** |

### Other Changes

```diff

-3557.12.1.0.0
+3557.15.100.0.0

-  Functions: 689
-  Symbols:   1417
-  CStrings:  365
+  Functions: 691
+  Symbols:   1424
+  CStrings:  373
Symbols:
+ _TIInputManagerOSLogFacility
+ _TIShouldLogCandidateRequestLifecycle
+ __ZNSt3__132__internal_log_hardening_failureEPKc
+ __ZNSt3__16__treeINS_12__value_typeIfiEENS_19__map_value_compareIfNS_4pairIKfiEENS_4lessIfEEEENS_9allocatorIS6_EEE14__tree_deleterclB9fon220106EPNS_11__tree_nodeIS2_PvEE
+ __ZNSt3__16vectorItNS_9allocatorItEEE11__vallocateB9fon220106Em
+ __ZNSt3__16vectorItNS_9allocatorItEEE20__throw_length_errorB9fon220106Ev
+ _abort
+ _bzero
- __ZNSt3__16__treeINS_12__value_typeIfiEENS_19__map_value_compareIfNS_4pairIKfiEENS_4lessIfEEEENS_9allocatorIS6_EEE14__tree_deleterclB9fon220100EPNS_11__tree_nodeIS2_PvEE
Functions:
~ -[TIKeyboardInputManagerChinese hasIdeographicCandidates] : 312 -> 308
~ -[TIKeyboardInputManagerChinese wordSearchEngineDidFindPredictionCandidates:] : 556 -> 792
~ -[TIKeyboardInputManagerChinese completionCandidateResultSetForKeyHint:] : 792 -> 788
~ +[TIKeyboardInputManagerChinese GB18030CandidateFromString:] : 332 -> 324
~ +[TIKeyboardInputManagerChinese shouldEnableHalfWidthPunctuationForDocumentContext:composedText:] : 464 -> 460
~ -[TIKeyboardInputManagerWubi notifyUpdateCandidates:forOperation:] : 720 -> 848
~ ___66-[TIKeyboardInputManagerWubi notifyUpdateCandidates:forOperation:]_block_invoke : 220 -> 456
~ -[TIKeyboardInputManagerShapeBased didAcceptCandidate:] : 588 -> 584
~ +[CIMCandidateData shouldShowZhuyinSortingMethod] : 472 -> 468
~ -[CIMCandidateData wordPropertyDictionaryForCandidates:isSimplified:] : 368 -> 364
~ -[CIMCandidateData sortCharactersByStrokeCount:wordPropertiesDictionary:] : 556 -> 552
~ -[CIMCandidateData candidateGroupsFromDictionary:sortedKeys:] : 644 -> 640
~ -[CIMCandidateData candidatesSortedByRadical:simplified:collationLocale:] : 496 -> 492
~ -[CIMCandidateData candidatesSortedByStrokes:simplified:] : 564 -> 560
~ -[CIMCandidateData candidatesSortedByPinyinOrZhuyin:simplified:zhuyin:] : 1128 -> 1120
~ -[NSString(CIMCandidateController) traditionalChineseZhuyinCompare:] : 372 -> 380
~ -[TIKeyboardInputManagerCangjie notifyUpdateCandidates:forOperation:] : 228 -> 364
~ ___69-[TIKeyboardInputManagerCangjie notifyUpdateCandidates:forOperation:]_block_invoke : 216 -> 452
~ -[TIWordSearchHandwriting createMecabraContextFromCandidateContext:stringContext:] : 372 -> 368
~ -[TIWordSearchHandwriting_ja generatePredictionsWithCandidateContext:stringContext:option:] : 568 -> 564
~ -[TIKeyboardInputManagerChinesePhonetic inputContinuesGB18030OrUnicodeLookupKey:] : 448 -> 444
~ ___88-[TIKeyboardInputManagerChinesePhonetic wordSearchEngineDidFindCandidates:forOperation:]_block_invoke : 2656 -> 3208
~ ___70-[TIKeyboardInputManagerWubixing notifyUpdateCandidates:forOperation:]_block_invoke : 284 -> 552
~ -[GeneratePredictionsOperation main] : 1268 -> 1264
~ -[TIInputManagerHandwriting defaultCandidate] : 440 -> 436
~ -[TIInputManagerHandwriting facemarkCandidates] : 504 -> 500
~ -[TIInputManagerHandwriting mainThreadUpdateCandidates:] : 836 -> 832
~ -[TIInputManagerHandwriting updateCompletionCandidatesIfAppropriate] : 1368 -> 1360
~ ___68-[TIInputManagerHandwriting updateCompletionCandidatesIfAppropriate]_block_invoke_6 : 856 -> 844
~ -[TIInputManagerHandwriting processCandidates:stickers:] : 2900 -> 2860
~ -[CHRecognitionResult(TIAdditions) mecabraHandwritingCandidate] : 696 -> 680
~ -[TIWordSearchChinesePhonetic chaiziCandidatesWithOperation:candidateResultSet:] : 1852 -> 2232
~ -[TIWordSearchChinesePhonetic uncachedCandidatesForOperation:] : 5004 -> 4988
+ __ZNSt3__16vectorItNS_9allocatorItEEE11__vallocateB9fon220106Em
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "[Chinese] Dropping Cangjie candidates: shouldSkipCandidateSelection is set. mode=%@"
+ "[Chinese] Dropping Wubi candidates: shouldSkipCandidateSelection is set. mode=%@"
+ "[Chinese] Updating Cangjie candidates: mode=%@ input=%{private}@ count=%lu topCandidate=%{private}@"
+ "[Chinese] Updating Wubi candidates: mode=%@ input=%{private}@ count=%lu topCandidate=%{private}@"
+ "[Chinese] Updating Wubixing candidates: mode=%@ input=%{private}@ count=%lu topCandidate=%{private}@"
+ "[Chinese] Updating candidates: mode=%@ input=%{private}@ count=%lu topCandidate=%{private}@"
+ "[Chinese] Updating prediction candidates: mode=%@ count=%lu topCandidate=%{private}@"
```
