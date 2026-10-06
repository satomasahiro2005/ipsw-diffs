## libtidy.A.dylib

> `/usr/lib/libtidy.A.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23430` | `0x233b4` | **`-0x7c`** |
| `__TEXT.__unwind_info` | `0x6c0` | `0x6d0` | **`+0x10`** |

### Other Changes

```text
Functions:
~ _AccessibilityChecks : 412 -> 388
~ _AccessibilityCheckNode : 2864 -> 2784
~ _textFromOneNode : 152 -> 128
~ _CheckImage : 1220 -> 1196
~ _CheckApplet : 508 -> 460
~ _CheckASCII : 620 -> 616
~ _CheckFrameSet : 476 -> 452
~ _CheckTH : 392 -> 388
~ _GetRgb : 496 -> 500
~ _GetFileExtension : 132 -> 128
~ _IsValidMediaExtension : 144 -> 152
~ _IsImage : 144 -> 152
~ _IsValidSrcExtension : 144 -> 152
~ _CheckColumns : 240 -> 236
~ _getTextNode : 152 -> 148
~ _FreeAttrTable : 424 -> 416
~ _IsValidHTMLID : 80 -> 76
~ _CheckColor : 616 -> 640
~ _CheckNumber : 236 -> 232
~ _CheckLength : 220 -> 240
~ _CheckLowerCaseAttrValue : 156 -> 148
~ _AttrValueIsAmong : 96 -> 80
~ _insrc_getByte : 48 -> 44
~ _tidyBufGetByte : 48 -> 44
~ _CleanWord2000 : 1268 -> 1264
~ _VerifyHTTPEquiv : 776 -> 800
~ _CreateProps : 556 -> 592
~ _CleanNode : 1604 -> 1620
~ _ResetConfigToDefault : 140 -> 164
~ _TakeConfigSnapshot : 88 -> 104
~ _lookupOption : 96 -> 112
~ _ResetConfigToSnapshot : 160 -> 196
~ _NeedReparseTagDecls : 268 -> 276
~ _CopyConfig : 168 -> 184
~ _ParseConfigFileEnc : 1116 -> 1112
~ _ParseConfigOption : 192 -> 212
~ _getNextOptionPick : 68 -> 72
~ _ConfigDiffThanDefault : 68 -> 72
~ _SaveConfigToStream : 532 -> 544
~ _ParseCharEnc : 348 -> 340
~ _ParseNewline : 404 -> 396
~ _ParseDocType : 444 -> 436
~ _ParseRepeatAttr : 336 -> 328
~ _ParseString : 480 -> 472
~ _ParseName : 308 -> 304
~ _ParseCSS1Selector : 360 -> 348
~ _ParseTagNames : 768 -> 764
~ _WriteOptionString : 156 -> 152
~ _WriteOptionPick : 92 -> 88
~ _HTMLVersion : 192 -> 196
~ _AddCharToLexer : 392 -> 388
~ _AddStringLiteral : 68 -> 60
~ _HTMLVersionNameFromCode : 64 -> 80
~ _WarnMissingSIInEmittedDocType : 212 -> 228
~ _FixDocType : 544 -> 560
~ _GetToken : 6096 -> 6084
~ _InitMap : 316 -> 296
~ _ParseEntity : 972 -> 964
~ _ParseTagName : 232 -> 228
~ _ParseAttrs : 556 -> 552
~ _FindGivenVersion : 288 -> 312
~ _ParseValue : 1984 -> 1968
~ _NtoS : 244 -> 236
~ _ReportMissingAttr : 188 -> 196
~ _tidy_out : 164 -> 160
~ _messagePos : 592 -> 580
~ _IsBlank : 108 -> 104
~ _TrimInitialSpace : 308 -> 304
~ _ParseBody : 1444 -> 1440
~ _CleanSpaces : 736 -> 732
~ _PFlushLine : 236 -> 232
~ _PCondFlushLine : 240 -> 236
~ _WrapLine : 208 -> 204
~ _TextStartsWithWhitespace : 168 -> 164
~ _PPrintChar : 1148 -> 1164
~ _AddString : 128 -> 136
~ _PPrintAttrValue : 1180 -> 1140
~ _WriteChar : 1212 -> 1268
~ _GetEncodingNameFromTidyId : 68 -> 76
~ _GetEncodingOptNameFromTidyId : 52 -> 64
~ _GetCharEncodingFromOptName : 92 -> 112
~ _lookup : 276 -> 272
~ _FreeDeclaredTags : 500 -> 496
~ _FreeTags : 196 -> 192
~ _nodeHasText : 124 -> 120
~ _tidyOptGetCurrPick : 148 -> 140
~ _tmbstrndup : 156 -> 140
~ _tmbstrncpy : 76 -> 72
~ _tmbstrcpy : 64 -> 48
~ _tmbstrcat : 108 -> 76
~ _tmbstrcmp : 72 -> 60
~ _tmbstrncmp : 84 -> 76
~ _tmbsubstrn : 188 -> 180
~ _tmbstrtolower : 68 -> 84
~ _tmbstrtoupper : 68 -> 84
~ _DecodeUTF8BytesToChar : 896 -> 892
```
