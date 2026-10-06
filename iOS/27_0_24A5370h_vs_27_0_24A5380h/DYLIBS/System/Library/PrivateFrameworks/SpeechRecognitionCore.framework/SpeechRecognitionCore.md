## SpeechRecognitionCore

> `/System/Library/PrivateFrameworks/SpeechRecognitionCore.framework/SpeechRecognitionCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b5d0` | `0x1bbc8` | **`+0x5f8`** |
| `__TEXT.__cstring` | `0x1a01` | `0x1ace` | **`+0xcd`** |
| `__AUTH_CONST.__cfstring` | `0x37c0` | `0x3880` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x1054` | `0x10a2` | **`+0x4e`** |
| `__AUTH_CONST.__objc_const` | `0x1f58` | `0x1f88` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xe14` | `0xe3c` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x5f0` | `0x610` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xa48` | `0xa60` | **`+0x18`** |
| `__TEXT.__const` | `0x132` | `0x14a` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xb18` | `0xb30` | **`+0x18`** |
| `__DATA.__bss` | `0x160` | `0x170` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x188` | `0x18c` | **`+0x4`** |

### Other Changes

```diff

-37.0.0.0.0
+38.0.0.0.0

-  Functions: 641
-  Symbols:   1461
-  CStrings:  665
+  Functions: 650
+  Symbols:   1472
+  CStrings:  671
Symbols:
+ -[SRDCommandMatcher _coverageForRecognizedText:matchedObjects:]
+ -[SRDCommandMatcher _tokenCountInString:]
+ -[SRDConnection dealloc]
+ -[SRDMatchResult coverage]
+ -[SRDMatchResult initWithCommand:transcriptionResult:matched:score:numberOfAdlibs:numberOfCachePlaceholders:asrRank:coverage:parameters:matchedObjects:displayString:closeMatchType:]
+ _OBJC_IVAR_$_SRDMatchResult._coverage
+ _OUTLINED_FUNCTION_7
+ _SRDAppendLiteralToRegexPatternWithOptionalSpace
+ _SRDShouldRelaxForKoreanNumberSlot
+ _SRDShouldRelaxForKoreanNumberSlot.sNumberSlotIdentifiers
+ _SRDShouldRelaxForKoreanNumberSlot.sNumberSlotIdentifiersOnce
+ ___SRDShouldRelaxForKoreanNumberSlot_block_invoke
- -[SRDMatchResult initWithCommand:transcriptionResult:matched:score:numberOfAdlibs:numberOfCachePlaceholders:asrRank:parameters:matchedObjects:displayString:closeMatchType:]
CStrings:
+ "  [%lu] Compiled exact match regex: '%{sensitive}@' -> '%{sensitive}@'"
+ "  [%lu] Compiled placeholder regex: '%{sensitive}@' -> '%{sensitive}@', metadata: %{public}@"
+ "  [%lu] Failed to compile placeholder regex for '%{sensitive}@': %{public}@"
+ "  [%lu] Failed to compile regex for '%{sensitive}@': %{public}@"
+ "  [%lu] Skipping invalid command string: '%{sensitive}@'"
+ "  [%lu] Using segment matching for '%{sensitive}@' (%lu cache placeholders), regex fallback: '%{sensitive}@'"
+ " ?"
+ "<%@: %p matched=%@ score=%.3f asrRank=%lu coverage=%lu closeMatchType=%lu \ncommand=%@ \ntranscription=%@ \nmatchedObjects=%@>"
+ "BuiltInLM.NumberTwoThroughNinetyNine"
+ "BuiltInLM.NumberTwoThroughNinetyNine.2"
+ "BuiltInLM.NumberZeroThroughOneHundred"
+ "BuiltInLM.ScreenDistanceCardinalNumber"
+ "BuiltInLM.TextSegmentCardinalNumber"
+ "[%{public}@] Cache hit for '%{public}@'='%{sensitive}@': %lu items"
+ "[%{public}@] Cache miss for '%{public}@'='%{sensitive}@' (key not found)"
+ "[%{public}@] Capture group %lu for '%{public}@': '%{sensitive}@'"
+ "[%{public}@] Close match check: '%{sensitive}@' (normalized)"
+ "[%{public}@] Close match found for '%{sensitive}@' (word distance=1)"
+ "[%{public}@] Dictation placeholder '%{public}@' captured: '%{sensitive}@'"
+ "[%{public}@] Segment: ambiguous cache match '%{sensitive}@' for '%{public}@'"
+ "[%{public}@] Segment: dictation found literal '%{sensitive}@' at position %lu"
+ "[%{public}@] Segment: extra text after all segments: '%{sensitive}@'"
+ "[%{public}@] Segment: literal '%{sensitive}@' matched"
+ "[%{public}@] Segment: literal '%{sensitive}@' mismatch"
+ "[%{public}@] Segment: multi-match branch for '%{public}@'='%{sensitive}@' result=%lu"
+ "[%{public}@] Segment: skipping consumed cache key '%{sensitive}@' for '%{public}@'"
+ "[%{public}@] Segment: transcription is prefix of literal '%{sensitive}@'"
+ "[%{public}@] Segment: trying '%{public}@'='%{sensitive}@'"
+ "[%{public}@] Segment: trying multi-match branch for '%{public}@'='%{sensitive}@'"
+ "[%{public}@] Trying regex for string %lu: '%{sensitive}@'"
- "  [%lu] Compiled exact match regex: '%{public}@' -> '%{public}@'"
- "  [%lu] Compiled placeholder regex: '%{public}@' -> '%{public}@', metadata: %{public}@"
- "  [%lu] Failed to compile placeholder regex for '%{public}@': %{public}@"
- "  [%lu] Failed to compile regex for '%{public}@': %{public}@"
- "  [%lu] Skipping invalid command string: '%{public}@'"
- "  [%lu] Using segment matching for '%{public}@' (%lu cache placeholders), regex fallback: '%{public}@'"
- "<%@: %p matched=%@ score=%.3f asrRank=%lu closeMatchType=%lu \ncommand=%@ \ntranscription=%@ \nmatchedObjects=%@>"
- "[%{public}@] Cache hit for '%{public}@'='%{public}@': %lu items"
- "[%{public}@] Cache miss for '%{public}@'='%{public}@' (key not found)"
- "[%{public}@] Capture group %lu for '%{public}@': '%{public}@'"
- "[%{public}@] Close match check: '%{public}@' (normalized)"
- "[%{public}@] Close match found for '%{public}@' (word distance=1)"
- "[%{public}@] Dictation placeholder '%{public}@' captured: '%{public}@'"
- "[%{public}@] Segment: ambiguous cache match '%{public}@' for '%{public}@'"
- "[%{public}@] Segment: dictation found literal '%{public}@' at position %lu"
- "[%{public}@] Segment: extra text after all segments: '%{public}@'"
- "[%{public}@] Segment: literal '%{public}@' matched"
- "[%{public}@] Segment: literal '%{public}@' mismatch"
- "[%{public}@] Segment: multi-match branch for '%{public}@'='%{public}@' result=%lu"
- "[%{public}@] Segment: skipping consumed cache key '%{public}@' for '%{public}@'"
- "[%{public}@] Segment: transcription is prefix of literal '%{public}@'"
- "[%{public}@] Segment: trying '%{public}@'='%{public}@'"
- "[%{public}@] Segment: trying multi-match branch for '%{public}@'='%{public}@'"
- "[%{public}@] Trying regex for string %lu: '%{public}@'"
```
