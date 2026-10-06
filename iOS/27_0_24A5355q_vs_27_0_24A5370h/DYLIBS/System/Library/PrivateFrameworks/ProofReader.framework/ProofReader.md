## ProofReader

> `/System/Library/PrivateFrameworks/ProofReader.framework/ProofReader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbe860` | `0xbdad0` | **`-0xd90`** |
| `__TEXT.__eh_frame` | `0x290` | `0x288` | **`-0x8`** |

### Other Changes

```diff

-688.0.0.0.0
+689.0.0.0.0
Functions:
~ _ICintget : 3664 -> 3644
~ _ICspl : 4112 -> 4052
~ _PRDbInit : 4000 -> 4096
~ _PRSSInit : 624 -> 628
~ _PRPunLoad : 1520 -> 1568
~ _PRExprLoad : 960 -> 944
~ _PRAmInit : 588 -> 608
~ -[AppleSpell dataBundlesForLanguageObject:] : 848 -> 840
~ _SetFarTable : 264 -> 304
~ -[PRDictionary initWithURL:fallbackURL:] : 796 -> 788
~ -[AppleSpell(Dictionary) localDictionaryArrayForLanguageObject:] : 860 -> 856
~ _SetHugeTable : 204 -> 244
~ _PDapp : 1056 -> 1020
~ _ICpd : 2376 -> 2364
~ -[AppleSpell(Spelling) spellServer:findMisspelledWordInString:range:languages:topLanguages:orthography:checkOrthography:mutableResults:offset:autocorrect:onlyAtInsertionPoint:initialCapitalize:autocapitalize:keyEventArray:appIdentifier:selectedRangeValue:parameterBundles:wordCount:countOnly:appendCorrectionLanguage:correction:] : 9988 -> 10148
~ -[AppleSpell databasePathForLanguageObject:] : 320 -> 316
~ -[AppleSpell databaseConnectionForLanguageObject:] : 2960 -> 2976
~ _SLchcnv : 188 -> 184
~ _UpdateDocFormat : 576 -> 540
~ _PRdb : 1748 -> 1736
~ _PRIcs : 1612 -> 1600
~ _ICint : 1900 -> 1904
~ _simpleTokenRangeAfterIndex : 944 -> 940
~ -[AppleSpell(Spelling) validateWordBuffer:length:languageObject:connection:sender:checkBase:checkDict:checkTemp:checkUser:checkNames:checkHyphens:checkIntercaps:checkOptions:forCorrection:depth:] : 10808 -> 10940
~ -[AppleSpell(Spelling) validateAbbreviationOrNumberWordBuffer:length:languageObject:connection:sender:] : 1232 -> 1220
~ -[AppleSpell(Dictionary) globalDictionaryArray] : 384 -> 380
~ -[AppleSpell enumerateLexiconEntriesForWord:language:usingBlock:] : 372 -> 368
~ -[AppleSpell _checkGrammarInString:range:language:connection:sender:bufIO:errorRange:details:] : 904 -> 896
~ -[AppleSpell spellServer:checkString:offset:types:options:orthography:wordCount:] : 5328 -> 5288
~ _SLcap : 224 -> 220
~ _SLstrcmp : 48 -> 44
~ _SLc2pasc : 112 -> 108
~ _SLpasc2c : 48 -> 64
~ -[AppleSpell(LanguageModeling) _contextLengthForRange:languageObject:tagger:languageModel:maxContextLength:context:cleanOffset:cleanContextRange:lastTokenRange:lastTokenID:] : 1184 -> 1192
~ ___173-[AppleSpell(LanguageModeling) _contextLengthForRange:languageObject:tagger:languageModel:maxContextLength:context:cleanOffset:cleanContextRange:lastTokenRange:lastTokenID:]_block_invoke : 348 -> 344
~ ___52-[AppleSpell(LanguageModeling) _resetLanguageModels]_block_invoke : 544 -> 540
~ -[AppleSpell(LanguageModeling) _addLanguageModelCompletionsForPartialWordRange:languageObject:connection:sender:tagger:appIdentifier:waitForLanguageModel:allowTransformer:candidates:scoreDictionary:tryTransliteration:] : 1772 -> 1776
~ -[AppleSpell(LanguageModeling) _rankedCandidatesForRange:candidates:languageObject:tagger:appIdentifier:allowTransformer:scoreDictionary:] : 1616 -> 1608
~ -[AppleSpell(LanguageModeling) _languageModelStateScoresForCandidateList:languageModel:state:language:tagger:] : 828 -> 824
~ -[AppleSpell(LanguageModeling) _rankedCandidatesForCandidateList:languageObject:tagger:appIdentifier:parameterBundles:] : 4152 -> 4132
~ -[AppleSpell(LanguageModeling) _useAlternateLanguageForRange:ofString:languageObject:tagger:alternateLanguageObject:alternateTagger:appIdentifier:] : 716 -> 724
~ -[PRWordLanguageModel _descriptionForTokenSequence:length:] : 180 -> 176
~ -[PRNLPLanguageModelState enumeratePredictions:maxTokensPerPrediction:withBlock:] : 532 -> 528
~ -[PRDictionary checkWordBuffer:length:encoding:index:caseInsensitive:] : 1812 -> 1824
~ -[AppleSpell(Dictionary) checkNameWordBuffer:length:languageObject:globalOnly:] : 548 -> 540
~ -[AppleSpell(Dictionary) dictionaryForLanguageObject:index:] : 276 -> 272
~ -[AppleSpell(Dictionary) capitalizationDictionaryArrayForLanguageObject:] : 320 -> 316
~ -[AppleSpell(Dictionary) parameterBundleForLanguageObject:] : 244 -> 240
~ -[AppleSpell(Dictionary) transformerParameterBundleForLanguageObject:] : 272 -> 268
~ _SLchk : 208 -> 224
~ _SLcrypt : 76 -> 80
~ _SLlisten : 616 -> 612
~ _SLmap : 344 -> 360
~ _SLord : 620 -> 664
~ _SLpar : 608 -> 604
~ _SLrecap : 288 -> 280
~ _SLwldcmp : 544 -> 552
~ _SLWildCmp : 612 -> 628
~ _SLwldfix : 288 -> 268
~ _SLwldpro : 348 -> 356
~ _SLWildPro : 1024 -> 1036
~ _SLparcmp : 440 -> 452
~ _SFaccent : 2072 -> 2064
~ _SFadd : 300 -> 304
~ _SFadd1 : 388 -> 376
~ _SFanachk : 192 -> 188
~ _SFanagrm : 524 -> 520
~ _SFanaqua : 1064 -> 1036
~ _SFbisrch : 676 -> 672
~ _SFchkwrd : 1388 -> 1396
~ _SFcltchk : 188 -> 236
~ _SFcltscr : 1024 -> 1064
~ _SFcor1qd : 1040 -> 1052
~ _SFcor2qd : 1144 -> 1136
~ _SFcor3qd : 1420 -> 1416
~ _SFcor6qd : 1664 -> 1660
~ _SFcor8qd : 1444 -> 1432
~ _SFcorbr8 : 648 -> 628
~ _SFcorbru : 2116 -> 2112
~ _SFcorqbr : 2184 -> 2148
~ _SFcorrec : 2100 -> 2088
~ _SFcorsrt : 1084 -> 1100
~ -[PRTypologyRecord dictionaryRepresentation] : 936 -> 928
~ ___40+[PRTypologyRecord writeTypologyRecords]_block_invoke : 264 -> 260
~ _SFdecbit : 1252 -> 1248
~ _SFicdecode : 5196 -> 5212
~ _SFwild : 1300 -> 1252
~ _SFdc : 768 -> 748
~ _ICcapcod : 1216 -> 1168
~ _ICEndToken : 440 -> 432
~ _ICcchadd : 648 -> 664
~ _ICclt : 1784 -> 1792
~ _middle_dot : 580 -> 616
~ _middle_dot_ver : 180 -> 208
~ _spanish_accentchk : 260 -> 252
~ _preclitic_search : 600 -> 604
~ _postclitic_search : 1076 -> 1072
~ _pandstemfr : 752 -> 768
~ _stemnpost : 868 -> 888
~ _postnotstem : 2012 -> 2032
~ _vowelchange : 656 -> 708
~ _ICcltacc : 748 -> 752
~ _ICcltcap : 2112 -> 2100
~ _ICcltrp : 2260 -> 2344
~ _icstem2 : 292 -> 260
~ _ICcltstm : 1044 -> 1040
~ _ICcltuna : 1400 -> 1372
~ _ICcmp : 3908 -> 3860
~ _ICcmpalt : 1432 -> 1420
~ _ICcmpdbl : 1400 -> 1368
~ _ICcmpexc : 1352 -> 1324
~ _ICcmpfnd : 1864 -> 1836
~ -[AppleSpell(Completion) spellServer:suggestCompletionsForPartialWordRange:inString:inLanguage:options:] : 540 -> 536
~ -[AppleSpell(Completion) spellServer:suggestCompletionDictionariesForPartialWordRange:inString:inLanguage:options:] : 1412 -> 1400
~ -[AppleSpell(Completion) spellServer:suggestNextLetterDictionariesForPartialWordRange:inString:inLanguage:options:] : 816 -> 804
~ -[AppleSpell(Completion) spellServer:candidatesForSelectedRange:inString:offset:types:options:orthography:] : 7448 -> 7440
~ _ICcmphhy : 2464 -> 2432
~ _ICcmphyp : 588 -> 584
~ _ICcmplmc : 1240 -> 1160
~ -[AppleSpell(Correction) _addGuessesForWordBuffer:length:languageObject:connection:sender:minAutocorrectionLength:previousLetter:nextLetter:basicOnly:toGuesses:] : 4784 -> 4724
~ -[AppleSpell(Correction) _umlautCorrectionForWord:buffer:length:languageObject:connection:typologyCorrection:] : 1076 -> 1084
~ -[AppleSpell(Correction) _connectionCorrectionForWord:buffer:length:languageObject:connection:flags:isCapitalized:accentCorrectionOnly:isAbbreviation:trySpaceInsertion:hasAccentCorrections:candidateList:typologyCorrection:] : 2044 -> 2036
~ _removeDiacriticsX : 888 -> 896
~ -[AppleSpell(Correction) _spaceInsertionCorrectionForWord:buffer:length:languageObject:connection:flags:isCapitalized:typologyCorrection:] : 2152 -> 2140
~ -[AppleSpell(Correction) _correctionResultForString:range:inString:offset:tagger:appIdentifier:dictionary:languages:connection:flags:keyEventArray:selectedRangeValue:parameterBundles:previousLetter:nextLetter:extraMisspellingCount:extraCorrectionCount:] : 3884 -> 3872
~ _ICcmpnum : 964 -> 936
~ _ICcmprmc : 1140 -> 1136
~ _ICcmpsmh : 1204 -> 1256
~ _ICcmpspc : 1936 -> 1916
~ _Split : 804 -> 796
~ _ICcmpver : 2992 -> 2976
~ _checked_strcpy : 104 -> 100
~ _ICcorspl : 584 -> 592
~ _ICcorucf : 3252 -> 3220
~ _cleanup : 264 -> 272
~ _icisint : 216 -> 208
~ _ICdblchk : 388 -> 384
~ _buildfullword : 252 -> 248
~ _ICdblver : 3436 -> 3432
~ _ICfndchk : 3012 -> 2980
~ _puntvolat_to_dot : 152 -> 184
~ _ligature : 972 -> 940
~ _lig_pos : 256 -> 240
~ _ICfoldio : 364 -> 360
~ _ICget : 796 -> 768
~ _HypStrip : 176 -> 164
~ _ICpre : 2496 -> 2424
~ _ICprever : 4484 -> 4460
~ _ICreadjpo : 104 -> 108
~ _ICacrnym : 1180 -> 1168
~ _ichhchk : 696 -> 688
~ _ICremacc : 324 -> 312
~ _ICsplini : 1168 -> 1148
~ _ICPDadd : 248 -> 244
~ _period_to_puntvolat : 160 -> 192
~ _puntvolat_to_period_list : 432 -> 416
~ _checked_strncpy : 104 -> 100
~ _ICverify : 3200 -> 3024
~ _gk_apocope : 468 -> 460
~ _gk_nu_drop : 332 -> 344
~ _gk_elision : 1292 -> 1304
~ _gk_undouble_accent : 300 -> 304
~ _ICpar : 14420 -> 14500
~ _IHcache : 240 -> 244
~ _IHclean : 276 -> 284
~ +[PRCandidate candidateWithBuffer:encoding:transform:replacementRange:errorScore:capitalizationDictionaryArray:] : 504 -> 500
~ -[PRCandidateList addCandidate:] : 412 -> 408
~ -[PRCandidateList candidateStrings] : 268 -> 264
~ -[PRCandidateList candidateWithString:] : 268 -> 264
~ _IHdecode : 1876 -> 1868
~ _IHgetmap : 384 -> 408
~ _IHhyp : 4300 -> 4292
~ _ReadCodes : 244 -> 256
~ _ReadData : 296 -> 280
~ _PDadd : 1108 -> 1120
~ _PDexpand : 908 -> 888
~ _PDcorrec : 680 -> 688
~ _PDcorsrt : 896 -> 916
~ _PDdb : 2216 -> 2124
~ _PDdballoc : 1560 -> 1456
~ _PDupibuf : 388 -> 364
~ _PDdbfree : 1068 -> 960
~ _PDfreedid : 1312 -> 1148
~ _PDsdneg : 612 -> 608
~ _StopWord : 104 -> 116
~ _PDdecode : 1404 -> 1372
~ _PDdecod2 : 2792 -> 2732
~ _PDdecodOldSD : 2696 -> 2588
~ _PDdel : 200 -> 204
~ _PDedit : 1424 -> 1380
~ _PDatoi : 88 -> 84
~ _PDatobyte : 88 -> 84
~ _PDreadas : 3176 -> 3092
~ _PDashead : 1724 -> 1680
~ _PDwriteas : 2940 -> 2844
~ _PDRDinit : 476 -> 472
~ _PDgetrdwrd : 392 -> 384
~ _PDgetrdraw : 192 -> 184
~ _PDcmp : 128 -> 136
~ _PDcapcmp : 68 -> 84
~ _PDsearch : 1272 -> 1308
~ _PDSFcorrec : 2052 -> 2032
~ _PDSFchkwrd : 1456 -> 1464
~ _PDSFwild : 1300 -> 1252
~ _PDSFanagrm : 516 -> 512
~ _PDSFdc : 760 -> 740
~ _PDSFcorqbr : 2304 -> 2196
~ _PDDCengan : 304 -> 296
~ _PDDCposclt : 316 -> 324
~ _PDDCposcls : 336 -> 332
~ _PDDCpreclt : 68 -> 64
~ _PDDCposacc : 532 -> 536
~ _PDDCcalacc : 468 -> 484
~ _PDSFanaqua : 1060 -> 1036
~ ___80-[AppleSpell(Lexicon) _loadLexiconsForLanguage:localization:cachedOnly:onQueue:]_block_invoke_2 : 684 -> 680
~ ___89-[AppleSpell(Lexicon) getMetaFlagsForWord:inLexiconForLanguage:metaFlags:otherMetaFlags:]_block_invoke_2 : 316 -> 312
~ -[AppleSpell(Lexicon) enumerateEntriesForWord:inLexiconForLanguage:withBlock:] : 348 -> 344
~ -[AppleSpell(Lexicon) enumerateCorrectionEntriesForWord:maxCorrections:inLexiconForLanguage:withBlock:] : 356 -> 352
~ -[AppleSpell(Lexicon) enumerateEntriesForWord:inLexiconForLanguageObject:withBlock:] : 348 -> 344
~ -[AppleSpell(Lexicon) enumerateCorrectionEntriesForWord:maxCorrections:inLexiconForLanguageObject:withBlock:] : 356 -> 352
~ -[PRLexicon initWithName:words:] : 456 -> 452
~ _PDSFcltscr : 1024 -> 1064
~ _PDSFcor1qd : 1020 -> 1012
~ _PDSFcor2qd : 1116 -> 1132
~ _PDSFcor3qd : 1404 -> 1368
~ _PDSFcor6qd : 1636 -> 1612
~ _PDSFcor8qd : 1436 -> 1400
~ _PDSFcorsrt : 1084 -> 1100
~ _PDhypins : 252 -> 236
~ _PDhypstrip : 176 -> 168
~ _PDasparse : 428 -> 412
~ _PDword : 4716 -> 4492
~ _PDcheckDID : 96 -> 88
~ _PDalt : 220 -> 216
~ _PDchknegs : 104 -> 96
~ _DecompOldSD : 1004 -> 1000
~ _PDOpenFile : 540 -> 532
~ _PDCompress : 4580 -> 4508
~ _MergeAndCompare : 1996 -> 1988
~ _output_counts : 400 -> 388
~ _scale_counts : 132 -> 136
~ _input_counts : 216 -> 220
~ _PDstrrev : 152 -> 156
~ _StartDb : 448 -> 436
~ _StartWord : 356 -> 360
~ _AltAndWrite : 424 -> 420
~ _Huffman_Comp : 1620 -> 1652
~ -[AppleSpell(SentenceCorrection) _checkEnglishArticlesInSentence:buffer:length:mutableCorrections:] : 2096 -> 2100
~ ___51-[AppleSpell(SentenceCorrection) englishPhraseRoot]_block_invoke : 936 -> 932
~ ___98-[AppleSpell(SentenceCorrection) _checkEnglishPhrasesInSentence:buffer:length:mutableCorrections:]_block_invoke_2 : 428 -> 424
~ -[AppleSpell(SentenceCorrection) _checkSentence:languageObject:] : 612 -> 616
~ -[AppleSpell(SentenceCorrection) spellServer:checkSentenceCorrectionInString:rangeInParagraph:languageObject:locale:tagger:offset:keyEventArray:selectedRangeValue:autocorrect:checkGrammar:ignoreTermination:mutableResults:] : 3220 -> 3208
~ _PDExtSort : 2724 -> 2688
~ _PDsdsort : 224 -> 232
~ _DownHeap : 440 -> 432
~ _AsciiCmp : 420 -> 408
~ _PDngrams : 1740 -> 1700
~ _sort_fr : 140 -> 164
~ _get_counts : 136 -> 140
~ _HeapSort : 140 -> 156
~ _DownHeap : 404 -> 388
~ _PDsavsort : 220 -> 208
~ _PDSFcorbru : 2116 -> 2112
~ _PDSFaccent : 2092 -> 2068
~ _LMargin : 72 -> 68
~ _inithyphen : 1228 -> 1232
~ _Hyphenate : 2400 -> 2416
~ _DCengan : 396 -> 388
~ _DCposclt : 352 -> 356
~ _DCposcls : 396 -> 384
~ _DCposacc : 544 -> 548
~ _DCcalacc : 440 -> 448
~ _char_in : 60 -> 56
~ _cmp_strings : 108 -> 124
~ _an_analyze : 2924 -> 2848
~ _stem_check : 240 -> 248
~ _scan : 1616 -> 1612
~ _stem_prefix_stem_suffix_check_hun : 520 -> 516
~ _stem_stem_suffix_check_hun : 2376 -> 2380
~ _cdict_find_first : 388 -> 372
~ _cdict_locate_first : 568 -> 552
~ __strcommon : 100 -> 92
~ _cdict_delete : 248 -> 260
~ _cdict_add : 1284 -> 1260
~ _freq_init : 408 -> 396
~ -[PRTurkishSuffix _fillPatternBuffer] : 292 -> 284
~ -[PRTurkishSuffix matchingIndexInBuffer:length:followedByLetter:matchWithNameOnly:] : 2372 -> 2300
~ __isTurkishVowel : 276 -> 272
~ +[PRTurkishSuffix standardTurkishNounSuffixes] : 1684 -> 1676
~ +[PRTurkishSuffix standardTurkishVerbSuffixes] : 5232 -> 5228
~ +[PRTurkishSuffix _enumerateSuffixMatchesForBuffer:length:followedByLetter:options:depth:matchState:suffixStack:suffixRangeStack:usingBlock:] : 736 -> 712
~ +[PRTurkishSuffix enumerateSuffixMatchesForBuffer:length:options:usingBlock:] : 248 -> 252
~ -[AppleSpell(Turkish) testTurkishSuffixationPattern:] : 672 -> 656
~ _hdr_init : 332 -> 344
~ _hdr_find : 64 -> 72
~ _f_gets : 212 -> 204
~ _hyphen_init : 1400 -> 1424
~ _hyphen_usr : 572 -> 556
~ _hyphen_ate : 4608 -> 4128
~ _hyphen_delete : 372 -> 384
~ _hyphen_find : 348 -> 360
~ _add_userhypdict : 320 -> 336
~ _add_hypdict : 340 -> 356
~ _HUhyphenate : 220 -> 212
~ _result_f : 508 -> 512
~ _charset_reinit : 1280 -> 1200
~ _db_init : 1360 -> 1344
~ _db_finish : 196 -> 204
~ _db_search : 1044 -> 992
~ _spell_check : 2200 -> 2192
~ _check_word : 828 -> 852
~ _check_mac : 3380 -> 3320
~ _segm_word : 1752 -> 1680
~ _check__words : 1676 -> 1684
~ _suggest_finish : 644 -> 620
~ _suggest_1_corr : 4352 -> 4268
~ _sugg_capitalize1 : 288 -> 276
~ _PRAltMod : 5440 -> 5680
~ _PRAltHsh : 548 -> 544
~ _PRSetTmpAlt : 1168 -> 1148
~ _PRProcTmpAlts : 776 -> 740
~ _PRapp : 1192 -> 1184
~ _FreeAppElem : 464 -> 448
~ _PRbuf : 1796 -> 1844
~ _PRCtGet : 1012 -> 996
~ _ActionStringLength : 376 -> 368
~ _PRdecomp : 284 -> 280
~ _PRDerive : 3068 -> 2880
~ _PRerr : 1768 -> 1888
~ _GetAltEmOff : 344 -> 332
~ _InsertString : 1452 -> 1456
~ _PRgetWarn : 672 -> 668
~ _ConvertAlts : 128 -> 144
~ _CompString : 376 -> 364
~ _PRevamac : 4308 -> 4300
~ _PRExprMatch : 1408 -> 1416
~ _PRdoFsa : 476 -> 488
~ _PRdoAction : 1284 -> 1276
~ _PRdoSub : 692 -> 684
~ _PRgetmsg : 396 -> 392
~ _PRIcsTokWalk : 2400 -> 2388
~ _GetCompNum : 252 -> 248
~ _FillWordElems : 628 -> 624
~ _AddToWordElems : 248 -> 244
~ _PRmapost : 5552 -> 5148
~ _EvaActionMacro : 372 -> 368
~ _CheckAltStr : 2304 -> 2300
~ _ReCapAltStr : 224 -> 220
~ _PRmatchr : 1844 -> 1920
~ _PRmevrul : 2740 -> 2728
~ _SetRef : 104 -> 108
~ _EvaLogInGlueByte : 272 -> 260
~ _EvaMacRulePiece : 1168 -> 1172
~ _EvaWordRulePiece : 912 -> 876
~ _SkipPieces : 348 -> 344
~ _EvaOneRulePiece : 652 -> 648
~ _PRmisrul : 636 -> 628
~ _PRaddAlts : 276 -> 280
~ _PRaddList : 388 -> 392
~ _PRaddFils : 280 -> 284
~ _PRaddRefs : 280 -> 284
~ _PRpd : 656 -> 648
~ _PRInitOrLoad : 684 -> 704
~ _PRPostAgree : 828 -> 840
~ _PRprune : 1428 -> 1424
~ _PRPunct : 3576 -> 3460
~ _PRInsRefs : 288 -> 292
~ _PRopnScope : 888 -> 896
~ _PRclsScope : 1012 -> 1024
~ -[AppleSpell(Spelling) acceptabilityOfWordBuffer:length:languageObject:forPrediction:alreadyCapitalized:depth:] : 1236 -> 1228
~ -[AppleSpell(Spelling) validateWordPrefixBuffer:length:connection:] : 340 -> 360
~ -[AppleSpell(Spelling) checkSpecialPrefixesForWordBuffer:length:] : 632 -> 628
~ _getLongTypeDescription : 436 -> 484
~ _getTypeDescriptions : 484 -> 524
~ _getRuleDescriptions : 692 -> 736
~ _getRuleStatus : 500 -> 544
~ _getOneDesc : 1080 -> 1124
~ _getOneStatus : 148 -> 156
~ _PRSfxGet : 484 -> 500
~ _PRss : 7072 -> 7060
~ _PRgrowWkBuf : 380 -> 364
~ _PRnormalize : 4480 -> 4320
~ _PRssPost : 1776 -> 1760
~ _PRisListEnum : 492 -> 500
~ _PRgermScan : 964 -> 1020
~ _PRisDutchOpenCompound : 160 -> 168
~ _PRSSWdGet : 312 -> 328
~ _PRtoktyp : 1028 -> 1024
~ _FreeTokenNode : 212 -> 224
~ _PRFillError : 2072 -> 2064
~ _PRMakenFillErr : 1884 -> 1876
~ _getPosition : 264 -> 312
~ _getTypeIndex : 164 -> 160
~ _CalExtBytesAfterCnv : 188 -> 184
~ _AltOneToMultiChrCnv : 480 -> 472
~ _OneToMultiChrCnv : 552 -> 540
~ _ToUpUnaccentedCnv : 108 -> 112
~ _PRword : 4304 -> 4276
~ _add_phrase : 876 -> 884
~ _find_phrase : 804 -> 800
~ _print_node : 296 -> 292
~ _create_phrase_root_from_strings : 144 -> 152
~ _next_phrase : 164 -> 168
~ _pinyin_root : 108 -> 132
~ _jyutping_root : 108 -> 132
~ _internalFromExternalZhuyin : 112 -> 108
~ _externalZhuyinFromInternal : 84 -> 80
~ _add_zhuyin : 420 -> 444
~ -[AppleSpell(EnglishGrammar) _checkEnglishGrammarInString:range:indexIntoBuffer:bufferLength:languageObject:connection:sender:bufIO:retval:errorRange:details:] : 1784 -> 1796
~ _findZhuyin : 624 -> 620
~ -[PRZhuyinContext _advanceIndexes] : 548 -> 556
~ -[PRZhuyinContext _addTranspositions] : 1524 -> 1556
~ -[PRZhuyinContext _addReplacements] : 1024 -> 1060
~ -[PRZhuyinContext _addInsertions] : 1184 -> 1180
~ -[PRZhuyinContext _addDeletions] : 1324 -> 1376
~ -[PRZhuyinContext _filterModifications] : 1236 -> 1220
~ -[PRZhuyinContext removeNumberOfInputCharacters:] : 260 -> 248
~ _modificationArrayFilteredByMaskAndLength : 488 -> 480
~ -[AppleSpell(Zhuyin) _addContextAlternativesForZhuyinInputString:modifications:afterIndex:delta:toArray:] : 668 -> 664
~ _restrictedEditDistance : 436 -> 400
~ _effectiveEditDistance : 164 -> 168
~ _restrictedUTF16EditDistance : 440 -> 404
~ _effectiveUTF16EditDistance : 164 -> 176
~ -[AppleSpell(Guessing) _addConnectionGuessesForWord:buffer:length:languageObject:connection:candidateList:] : 680 -> 692
~ _removeDiacriticsX : 860 -> 868
~ -[AppleSpell(Guessing) _addAdditionalGuessesForWord:sender:buffer:length:languageObject:connection:accents:isCapitalized:isAllCaps:isAllAlpha:hasLigature:suggestPossessive:checkUser:checkHyphens:candidateList:] : 5420 -> 5328
~ -[AppleSpell(Guessing) _spellServer:suggestGuessesForWordRange:inString:languageObject:options:tagger:errorModel:guessesDictionaries:] : 4108 -> 4148
~ -[PRPinyinString initWithString:syllableCount:lastSyllableIsPartial:score:originalLength:originalCheckedLength:numberOfModifications:modificationTypes:originalModificationRanges:finalModificationRanges:originalSyllableRanges:originalAdditionalSyllableRanges:] : 600 -> 544
~ -[AppleSpell(Chinese) englishStringsFromWordBuffer:length:connection:] : 1912 -> 1896
~ -[AppleSpell(Chinese) addSpecialModifiedPinyinToArray:inBuffer:length:atEnd:] : 1296 -> 1288
~ _findPinyin : 1772 -> 1796
~ -[AppleSpell(Chinese) addModifiedPinyinToArray:connection:fromIndex:prevIndex:prevPrevIndex:startingModificationsAt:inBuffer:length:initialSyllableCount:initialScore:prevScore:prevPrevScore:lastSyllableScore:couldBeAbbreviatedPinyin:] : 8868 -> 8704
~ -[AppleSpell(Chinese) _primitiveRetainedAlternativesForPinyinInputString:] : 1040 -> 1032
~ -[AppleSpell(Chinese) _getSplitIndexes:maxCount:forPinyinInputString:] : 532 -> 528
~ -[AppleSpell(Chinese) _pinyinStringByCombiningPinyinString:withPinyinString:] : 1236 -> 1216
~ -[AppleSpell(Chinese) _retainedAlternativesByCombiningAlternatives:withAlternatives:andAddingAlternatives:] : 716 -> 708
~ -[AppleSpell(Chinese) _recursiveRetainedAlternativesForPinyinInputString:depth:] : 748 -> 728
~ -[AppleSpell(Chinese) spellServer:_retainedPrefixesForPinyinInputString:] : 1900 -> 1928
~ -[AppleSpell(Chinese) spellServer:_retainedCorrectionsForPinyinInputString:] : 672 -> 656
~ -[AppleSpell(Chinese) spellServer:_retainedFinalModificationsForPinyinInputString:geometryModelData:] : 336 -> 332
~ -[PRPinyinContext _advanceIndexes] : 384 -> 380
~ -[PRPinyinContext _addEnglishWordForRange:quickly:] : 660 -> 664
~ -[PRPinyinContext _addSpecialEnglishWords] : 956 -> 952
~ -[PRPinyinContext _addTranspositions] : 1368 -> 1384
~ -[PRPinyinContext _addReplacements] : 956 -> 960
~ -[PRPinyinContext _addValidSequenceReplacements] : 936 -> 940
~ -[PRPinyinContext _addDeletions] : 1088 -> 1092
~ -[PRPinyinContext _filterModifications] : 1340 -> 1324
~ -[PRPinyinContext _addPrefixes] : 1084 -> 1112
~ -[PRPinyinContext addInputCharacter:geometryModel:geometryData:] : 784 -> 780
~ -[PRPinyinContext removeNumberOfInputCharacters:] : 360 -> 348
~ -[PRPinyinContext guesses] : 428 -> 424
~ -[PRPinyinContext completions] : 432 -> 428
~ -[AppleSpell(TestPinyin) inputStringIsPinyin:allowPartialLastSyllable:] : 304 -> 300
~ -[AppleSpell(TestPinyin) inputStringIsFullOrAbbreviatedPinyin:] : 204 -> 200
~ -[AppleSpell(TestPinyin) _addContextAlternativesForPinyinInputString:modifications:afterIndex:delta:toArray:] : 848 -> 844
~ _ConvertStringToHangulCompatibilityJamo : 448 -> 464
~ _ConvertStringFromHangulCompatibilityJamo : 432 -> 444
~ _HangulCompatibilityToJamo : 172 -> 180
~ -[AppleSpell(Korean) spellServer:suggestGuessesForKoreanWordRange:inString:options:] : 1072 -> 1064
~ sub_1ca0b4590 -> sub_1ca941808 : 296 -> 300
~ sub_1ca0b5d4c -> sub_1ca942fc8 : 340 -> 336
~ sub_1ca0b6670 -> sub_1ca9438e8 : 1236 -> 1228
```
