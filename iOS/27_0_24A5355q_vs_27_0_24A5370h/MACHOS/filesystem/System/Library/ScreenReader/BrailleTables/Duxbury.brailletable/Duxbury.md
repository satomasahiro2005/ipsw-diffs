## Duxbury

> `/System/Library/ScreenReader/BrailleTables/Duxbury.brailletable/Duxbury`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28748` | `0x286c0` | **`-0x88`** |
| `__TEXT.__unwind_info` | `0x490` | `0x498` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```text
Functions:
~ _BRLTRN_UnicodeStringInit : 148 -> 132
~ _BRLTRN_TranslateString : 496 -> 480
~ -[DBTDuxburyBrailleTranslator _prepBuffersForConversion:withString:mode:prefixLength:] : 284 -> 292
~ -[DBTDuxburyBrailleTranslator _populatePrintBrailleForTextLocations:inLength:outLength:translationHandle:offsetToBraille:prefixCodeLength:preprocessedMap:optimize:] : 904 -> 972
~ -[DBTDuxburyBrailleTranslator _scrubDollarCodesInBuffer:originalLength:originalLocations:newLocations:convertASCIIBrailleToUnicode:limitRange:] : 328 -> 324
~ +[DBTDuxburyBrailleTranslator _mappedRange:withPreprocessedMap:] : 220 -> 212
~ -[DBTDuxburyBrailleTranslator _populateTextForPrintBrailleLocations:inLength:outLength:offsetToBraille:prefixLength:optimize:] : 576 -> 588
~ -[DBTDuxburyBrailleTranslator _textForPrintBraille:mode:locations:optimize:] : 700 -> 692
~ -[DBTDuxburyBrailleTranslator _eightDotPrintBrailleForText:locations:textFormattingRanges:] : 1204 -> 1180
~ -[DBTDuxburyBrailleTranslator _eightDotTextForPrintBraille:locations:] : 828 -> 816
~ -[DBTDuxburyBrailleTranslator _eightDotTablesFromRawTable:translationTable:backTranslationTable:] : 1552 -> 1544
~ _DBTNSStringFromWideCharBuffer : 156 -> 160
~ _lev2 : 472 -> 476
~ _dxbin_code_in_str : 252 -> 268
~ _BRLDISP_PrintDots : 460 -> 480
~ _is_basename_equal : 240 -> 248
~ _BRLTRN_TranslateStringEx : 2476 -> 2484
~ _BRLTRN_InputPosFromOutputPos : 164 -> 156
~ _BRLTRN_OutputPosFromArray : 100 -> 96
~ _dxchi_map_set_multiple : 316 -> 304
~ _dxchi_map_init : 152 -> 148
~ _BRLTRN_UnicodeStringInit_Apple : 148 -> 132
~ _BRLTRN_TranslateStringAndGetLocationMap : 468 -> 452
~ _chdimrm : 184 -> 188
~ _chdimrs : 104 -> 96
~ _dxscb_engine_deactivate : 160 -> 156
~ _readtable : 1780 -> 1724
~ _chdiwam : 184 -> 188
~ _chdiwas : 104 -> 96
~ _is_text : 52 -> 48
~ _chiini_stream : 2052 -> 2000
~ -[DBTDuxburyFormatNode LaTeXRepresentation] : 316 -> 312
~ -[DBTDuxburyFormatNode _debugDescriptionWithIndent:] : 480 -> 476
~ _dxchi_unimap_read : 696 -> 692
~ _unimap_read_mapping : 348 -> 364
~ _dxxins : 212 -> 220
~ _dxcini : 1936 -> 1904
~ _getprm : 720 -> 676
~ _ermgmg : 800 -> 804
~ _dxios_stream_printf : 2252 -> 2244
~ -[DBTTextFormatterPreprocessor preprocessPrintString:withLocationMap:isEightDot:textFormattingRanges:] : 2092 -> 2076
~ _dxios_search_fopen : 400 -> 408
~ _dxios_search_fopen_w : 400 -> 408
~ _jreaq : 596 -> 572
~ _linecq : 372 -> 368
~ _dxnin_engine_reactivate : 112 -> 128
~ _extract_styname : 120 -> 112
~ _dxnin_engine_getc : 5416 -> 5316
~ _wcmp : 200 -> 188
~ _lookcw : 496 -> 488
~ _get_hyp : 440 -> 428
~ _readfonts : 324 -> 340
~ _wcapsend : 5356 -> 5536
~ -[DBTDuxburyFormatParser _parseInputString:error:] : 1960 -> 1948
~ -[DBTDuxburyFormatParser closeENodeIfNeeded] : 464 -> 460
~ _dxscb_engine_process : 928 -> 916
~ _prdtqr : 2100 -> 2080
~ _scltb : 160 -> 168
~ _sgose : 172 -> 164
~ _scswp : 376 -> 396
~ _strcic : 140 -> 136
~ _dxbte_engine_process : 6204 -> 6236
~ _dxbte_state_equals : 104 -> 124
~ _ttgesp : 332 -> 328
~ _trcedbc : 916 -> 920
~ _trcck : 600 -> 584
~ _wcscpx : 48 -> 52
~ _wcscax : 92 -> 104
```
