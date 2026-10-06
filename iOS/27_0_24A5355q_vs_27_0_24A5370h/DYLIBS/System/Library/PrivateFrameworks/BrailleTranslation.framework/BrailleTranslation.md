## BrailleTranslation

> `/System/Library/PrivateFrameworks/BrailleTranslation.framework/BrailleTranslation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x31a7c` | `0x31b4c` | **`+0xd0`** |

### Other Changes

```diff

-455.1.1.0.0
+458.0.0.0.0
Functions:
~ -[BRLTTranslator arrayFromData:] : 184 -> 200
~ -[BRLTTable locales] : 400 -> 396
~ -[BRLTTable replacements] : 572 -> 568
~ -[BRLTTable _bundle] : 392 -> 388
~ -[BRLTUnicodePrintPreprocessor preprocessPrintString:withLocationMap:isEightDot:textFormattingRanges:] : 1088 -> 1084
~ +[BRLTTableEnumerator defaultTablesArrayForLocale:] : 1200 -> 1196
~ -[BRLTTableEnumerator translatorBundles] : 936 -> 932
~ -[BRLTTableEnumerator supportedLocales] : 352 -> 348
~ -[BRLTTableEnumerator supportedLocalesForTable:] : 640 -> 632
~ -[BRLTTableEnumerator supportedLanguageLocales] : 392 -> 388
~ -[BRLTTableEnumerator languageAgnosticTables] : 332 -> 328
~ -[BRLTTableEnumerator languageAgnosticTablesInBundle:] : 488 -> 484
~ -[BRLTTableEnumerator languageAgnosticTablesForIdentifier:inBundle:] : 392 -> 388
~ -[BRLTTableEnumerator tablesForLocale:inBundle:] : 548 -> 544
~ -[BRLTTableEnumerator languageAgnosticIdentifiersToTables] : 616 -> 612
~ -[BRLTBrailleString unicode] : 328 -> 324
~ +[BRLTBrailleString unicodeToDin:] : 456 -> 452
~ +[BRLTBrailleString brfToUnicode:] : 284 -> 280
~ +[BRLTBrailleChar grade1EnglishLetterForBrailleChar:] : 224 -> 220
~ -[BRLTServiceTranslator initWithTable:] : 668 -> 664
~ -[BRLTServiceTranslator _arrayFromData:] : 184 -> 200
~ +[NSBundle(BRLTBrailleTables) brl_brailleTableBundleWithIdentifier:] : 356 -> 352
~ -[NSBundle(BRLTBrailleTables) brl_supportedLocales] : 560 -> 556
~ -[NSBundle(BRLTBrailleTables) brl_supportedTablesForLocale:] : 1120 -> 1140
~ -[NSBundle(BRLTBrailleTables) brl_languageAgnosticTables] : 340 -> 336
~ -[NSBundle(BRLTBrailleTables) brl_supportedLocalesForTableWithIdentifier:] : 360 -> 356
~ +[BRLTPreprocessorHelper mergePreprocessorOutputLocationMap:outputToPreprocessedMap:outputLen:outputToTextMap:] : 216 -> 220
~ -[BRLTBrailleStateManager _generateBrailleBuffer:] : 800 -> 788
~ -[BRLTBrailleStateManager _textRangeForBrailleRange:textPositions:scriptLength:] : 208 -> 204
~ -[BRLTBrailleStateManager _brailleRangeForTextRange:textPositions:brailleLength:] : 208 -> 204
~ -[BRLTBrailleStateManager _translate:] : 3176 -> 3172
~ -[BRLTBrailleStateManager scriptRangeOfBrailleCellRepresentingCharacterAtScriptIndex:] : 316 -> 312
~ sub_24eff91ac -> sub_2506dc168 : 1900 -> 1920
~ sub_24eff9c58 -> sub_2506dcc28 : 444 -> 460
~ sub_24effa25c -> sub_2506dd23c : 456 -> 512
~ sub_24effa424 -> sub_2506dd43c : 2300 -> 2308
~ sub_24effb090 -> sub_2506de0b0 : 444 -> 396
~ sub_24effb918 -> sub_2506de908 : 276 -> 256
~ sub_24effc76c -> sub_2506df748 : 92 -> 104
~ sub_24effc7f0 -> sub_2506df7d8 : 1820 -> 1832
~ sub_24effd090 -> sub_2506e0084 : 1828 -> 1860
~ sub_24f003da0 -> sub_2506e6db4 : 940 -> 1108
~ sub_24f00414c -> sub_2506e7208 : 2264 -> 2272
~ sub_24f00deac -> sub_2506f0f70 : 280 -> 276
~ sub_24f0156b0 -> sub_2506f8770 : 176 -> 196
~ sub_24f015798 -> sub_2506f886c : 708 -> 700
~ sub_24f015a5c -> sub_2506f8b28 : 684 -> 688
```
