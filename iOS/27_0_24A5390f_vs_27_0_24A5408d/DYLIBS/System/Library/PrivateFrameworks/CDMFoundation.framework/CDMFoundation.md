## CDMFoundation

> `/System/Library/PrivateFrameworks/CDMFoundation.framework/CDMFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x274fcc` | `0x274ee0` | **`-0xec`** |
| `__TEXT.__gcc_except_tab` | `0xb4ac` | `0xb52c` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x8160` | `0x81a0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x8664` | `0x8684` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x1dd56` | `0x1dd75` | **`+0x1f`** |
| `__AUTH_CONST.__objc_intobj` | `0x660` | `0x678` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x7e80` | `0x7e98` | **`+0x18`** |
| `__TEXT.__cstring` | `0x1ba45` | `0x1ba53` | **`+0xe`** |
| `__AUTH_CONST.__objc_const` | `0x128c0` | `0x128c8` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x220` | `0x228` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x53f8` | `0x5400` | **`+0x8`** |

### Other Changes

```diff

-3600.31.10.0.0
+3600.31.14.0.0

-  Symbols:   8866
-  CStrings:  4589
+  Symbols:   8869
+  CStrings:  4592
Symbols:
+ +[CDMSiriVocabularyProtoSpanMatcher tokensWithinCharacterBudget:maxCharacters:]
+ -[CDMClient forceCleanup]
+ -[CDMClientInterface forceCleanup]
+ GCC_except_table180
+ GCC_except_table185
+ GCC_except_table187
+ GCC_except_table189
+ GCC_except_table194
+ GCC_except_table2150
+ GCC_except_table2154
+ GCC_except_table2157
+ GCC_except_table2164
+ GCC_except_table2173
+ GCC_except_table2179
+ GCC_except_table2183
+ GCC_except_table2186
+ GCC_except_table2190
+ GCC_except_table2192
+ GCC_except_table2208
+ GCC_except_table2211
+ GCC_except_table2214
+ GCC_except_table2297
+ GCC_except_table2332
+ GCC_except_table2337
+ GCC_except_table2357
+ GCC_except_table239
+ GCC_except_table243
+ GCC_except_table2446
+ GCC_except_table2448
+ GCC_except_table245
+ GCC_except_table2468
+ GCC_except_table247
+ GCC_except_table249
+ GCC_except_table2493
+ GCC_except_table2504
+ GCC_except_table2505
+ GCC_except_table251
+ GCC_except_table253
+ GCC_except_table2537
+ GCC_except_table2540
+ GCC_except_table256
+ GCC_except_table2567
+ GCC_except_table2568
+ GCC_except_table258
+ GCC_except_table2595
+ GCC_except_table260
+ GCC_except_table262
+ GCC_except_table265
+ GCC_except_table267
+ GCC_except_table270
+ GCC_except_table273
+ GCC_except_table275
+ GCC_except_table285
+ GCC_except_table298
+ GCC_except_table300
+ GCC_except_table304
+ GCC_except_table316
+ GCC_except_table325
+ GCC_except_table327
+ GCC_except_table331
+ GCC_except_table337
+ GCC_except_table372
+ GCC_except_table377
+ GCC_except_table383
+ GCC_except_table413
+ GCC_except_table417
+ GCC_except_table431
+ GCC_except_table558
+ GCC_except_table602
+ GCC_except_table608
+ GCC_except_table661
+ GCC_except_table669
+ GCC_except_table684
+ GCC_except_table687
+ GCC_except_table695
+ GCC_except_table702
+ GCC_except_table704
+ GCC_except_table707
+ GCC_except_table712
+ GCC_except_table715
+ GCC_except_table719
+ GCC_except_table727
+ GCC_except_table765
- +[CDMBaseSpanMatchService trimTokenizerResponses:toMaxCharacters:]
- GCC_except_table179
- GCC_except_table184
- GCC_except_table186
- GCC_except_table188
- GCC_except_table190
- GCC_except_table2145
- GCC_except_table2153
- GCC_except_table2155
- GCC_except_table2163
- GCC_except_table2171
- GCC_except_table2174
- GCC_except_table2180
- GCC_except_table2185
- GCC_except_table2189
- GCC_except_table2191
- GCC_except_table2202
- GCC_except_table2210
- GCC_except_table2212
- GCC_except_table2285
- GCC_except_table2331
- GCC_except_table2333
- GCC_except_table2338
- GCC_except_table238
- GCC_except_table242
- GCC_except_table2430
- GCC_except_table244
- GCC_except_table2447
- GCC_except_table246
- GCC_except_table2467
- GCC_except_table248
- GCC_except_table2490
- GCC_except_table2498
- GCC_except_table250
- GCC_except_table252
- GCC_except_table2533
- GCC_except_table2538
- GCC_except_table255
- GCC_except_table2565
- GCC_except_table2566
- GCC_except_table257
- GCC_except_table259
- GCC_except_table2593
- GCC_except_table261
- GCC_except_table264
- GCC_except_table266
- GCC_except_table269
- GCC_except_table272
- GCC_except_table274
- GCC_except_table284
- GCC_except_table297
- GCC_except_table299
- GCC_except_table302
- GCC_except_table315
- GCC_except_table321
- GCC_except_table326
- GCC_except_table330
- GCC_except_table336
- GCC_except_table371
- GCC_except_table376
- GCC_except_table380
- GCC_except_table412
- GCC_except_table415
- GCC_except_table430
- GCC_except_table557
- GCC_except_table600
- GCC_except_table604
- GCC_except_table660
- GCC_except_table663
- GCC_except_table683
- GCC_except_table685
- GCC_except_table689
- GCC_except_table696
- GCC_except_table703
- GCC_except_table706
- GCC_except_table708
- GCC_except_table713
- GCC_except_table718
- GCC_except_table726
- GCC_except_table762
CStrings:
+ "%s [WARN]: SiriVocabulary span-match input %lu chars > limit %lu; truncating to %lu and skipping phonetic asrHypothesis before SEM (rdar://175985393)"
+ "SpeechInput supports turn taking but is not a recognized turn-taking candidate type, cannot post NLTRPCandidateMessage for CDM Setup failure callback"
+ "TVRemoteCore"
+ "com.apple.TVRemoteApp"
+ "com.apple.TVRemoteUIService"
+ "iOSBundleIDRename"
- "%s Trimmed tokenizer response from %lu to %lu chars (limit=%lu) and from %lu to %lu tokens to bound span matching work"
- "+[CDMBaseSpanMatchService trimTokenizerResponses:toMaxCharacters:]"
- "SpeechInput supports turn taking but doesn't conform to TurnConstructionCandidate, cannot post NLTRPCandidateMessage for CDM Setup failure callback"
```
