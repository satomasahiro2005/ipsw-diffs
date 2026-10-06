## SpeechRecognitionCore

> `/System/Library/PrivateFrameworks/SpeechRecognitionCore.framework/SpeechRecognitionCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ba88` | `0x1baec` | **`+0x64`** |

### Other Changes

```diff

-39.0.0.0.0
+40.1.0.0.0
Symbols:
+ -[SRDBuiltInLMMatchingCache hasLinguisticExtensionForItem:forIdentifier:]
+ -[SRDCommandMatcher _matchCacheSegment:segments:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:]
+ -[SRDCommandMatcher _matchDictationSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:]
+ -[SRDCommandMatcher _matchLiteralSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:]
+ -[SRDCommandMatcher _matchSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:]
+ -[SRDCommandMatcher _segmentMatchForTranscription:withTemplate:isSpellingMode:checkLinguisticPrefix:]
- -[SRDBuiltInLMMatchingCache hasAmbiguousPrefixForItem:forIdentifier:]
- -[SRDCommandMatcher _matchCacheSegment:segments:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:]
- -[SRDCommandMatcher _matchDictationSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:]
- -[SRDCommandMatcher _matchLiteralSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:]
- -[SRDCommandMatcher _matchSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:]
- -[SRDCommandMatcher _segmentMatchForTranscription:withTemplate:isSpellingMode:]
Functions:
~ -[SRDCommandMatcher matchWithTranscriptionResult:] : 5348 -> 5352
~ -[SRDCommandMatcher _matchLiteralSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:] -> -[SRDCommandMatcher _matchLiteralSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:] : 920 -> 908
~ -[SRDCommandMatcher _matchDictationSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:] -> -[SRDCommandMatcher _matchDictationSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:] : 1160 -> 1172
~ -[SRDCommandMatcher _matchCacheSegment:segments:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:] -> -[SRDCommandMatcher _matchCacheSegment:segments:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:] : 3412 -> 3444
~ -[SRDCommandMatcher _matchSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:] -> -[SRDCommandMatcher _matchSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:] : 720 -> 764
~ -[SRDCommandMatcher _segmentMatchForTranscription:withTemplate:isSpellingMode:] -> -[SRDCommandMatcher _segmentMatchForTranscription:withTemplate:isSpellingMode:checkLinguisticPrefix:] : 236 -> 252
~ -[SRDCommandMatcher prefixMatchStatusForTranscription:isSpellingMode:] : 960 -> 964
```
