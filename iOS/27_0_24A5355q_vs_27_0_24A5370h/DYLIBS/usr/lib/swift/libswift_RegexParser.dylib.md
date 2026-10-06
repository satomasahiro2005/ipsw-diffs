## libswift_RegexParser.dylib

> `/usr/lib/swift/libswift_RegexParser.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x814ac` | `0x818d4` | **`+0x428`** |
| `__AUTH_CONST.__auth_got` | `0x680` | `0x670` | **`-0x10`** |
| `__TEXT.__const` | `0x5d98` | `0x5da8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1910` | `0x1900` | **`-0x10`** |

### Other Changes

```diff

-6.4.0.19.103
+6.4.0.23.102

-  Symbols:   6667
+  Symbols:   6665
Symbols:
- _swift_release_x27
- _swift_retain_x27
Functions:
~ _$s12_RegexParser19parseWithDelimitersyAA3ASTVxKSyRzSs11SubSequenceRtzlF : 1380 -> 1388
~ _$sSTsSQ7ElementRpzrlE13elementsEqualySbqd__STRd__AAQyd__ABRSlFSS8UTF8ViewV_SsAEVTg5 : 684 -> 680
~ _$sSTsSQ7ElementRpzrlE13elementsEqualySbqd__STRd__AAQyd__ABRSlFSs8UTF8ViewV_SSAEVTg5 : 664 -> 660
~ _$s12_RegexParser0B0V5parseAA3ASTVyF : 368 -> 364
~ _$s12_RegexParser0B0V18parseConcatenationAA3ASTV4NodeOyF : 3236 -> 3232
~ _$s12_RegexParser0B0V16lexInterpolationAA3ASTV0D0VSgyF : 1896 -> 1920
~ _$s12_RegexParser0B0V13lexQuantifierAA6SourceV7LocatedVy_AA3ASTV14QuantificationV6AmountOG_AHy_AL4KindOGSayAJ6TriviaVGtSgyF : 684 -> 688
~ _$s12_RegexParser0A9Validator33_D63F04F108272DD427D4E85D589C1C70LLV12validateNodeyyAA3ASTV0N0OF : 732 -> 740
~ _$s12_RegexParser0B0V13lexQuantifierAA6SourceV7LocatedVy_AA3ASTV14QuantificationV6AmountOG_AHy_AL4KindOGSayAJ6TriviaVGtSgyFAvCzXEfU_ : 1992 -> 2032
~ _$s12_RegexParser0B0V13lexGroupStartAA6SourceV7LocatedVy_AA3ASTV0D0V4KindOGSgyF : 700 -> 704
~ _$s12_RegexParser0B0V25lexPOSIXCharacterProperty33_E16AF135E664C72DDA9A5705859E2720LLAA6SourceV7LocatedVy_AA3ASTV4AtomV09CharacterE0VGSgyF : 1344 -> 1352
~ _$s12_RegexParser0B0V26lexExplicitPCRE2GroupStartAA3ASTV0F0V4KindOSgyF : 672 -> 676
~ _$s12_RegexParser0B0V24lexGroupConditionalStartAA6SourceV7LocatedVy_AA3ASTV0D0V4KindOGSgyF : 800 -> 804
~ _$s12_RegexParser11DiagnosticsV20appendNewFatalErrors4fromyAC_tF : 372 -> 376
~ _$s12_RegexParser3ASTV4AtomV4KindOMr : 220 -> 228
~ _$s12_RegexParser0A9Validator33_D63F04F108272DD427D4E85D589C1C70LLV16validateCapturesyyF : 240 -> 256
~ _$s12_RegexParser0A9Validator33_D63F04F108272DD427D4E85D589C1C70LLV12validateAtom_22inCustomCharacterClassyAA3ASTV0N0V_SbtF : 724 -> 740
~ _$s12_RegexParser0A9Validator33_D63F04F108272DD427D4E85D589C1C70LLV8validateAA3ASTVyF : 1468 -> 1272
~ _$sSS17UnicodeScalarViewV8distance4from2toSiSS5IndexV_AGtF : 536 -> 512
~ _$s12_RegexParser5parseyAA3ASTVx_AA13SyntaxOptionsVtKSyRzSs11SubSequenceRtzlF : 348 -> 356
~ _$s12_RegexParser0A9Validator33_D63F04F108272DD427D4E85D589C1C70LLV28validateCharacterClassMemberyyAA3ASTV06CustomnO0V0P0OF : 532 -> 572
~ _$s12_RegexParser0B0V25parseCustomCharacterClassyAA3ASTV0deF0VAA6SourceV7LocatedVy_AH5StartOGF : 2044 -> 2084
~ _$s12_RegexParser0B0V21parsePotentialCCRange4intoySayAA3ASTV20CustomCharacterClassV6MemberOGz_tF : 4796 -> 4720
~ _$s12_RegexParser0B0V13lexQuantBoundAA3ASTV4AtomV6NumberVSgyF : 964 -> 996
~ _$s12_RegexParser0A9Validator33_D63F04F108272DD427D4E85D589C1C70LLV22validateQuantificationyyAA3ASTV0N0VF : 704 -> 720
~ _$s12_RegexParser0B0V16lexUnicodeScalarAA3ASTV4AtomV4KindOSgyF : 940 -> 944
~ _$s12_RegexParser0B0V9lexNumberyAA3ASTV4AtomV0D0VSgAA9RadixKindOF : 1516 -> 1540
~ _$s12_RegexParser0B0V19lexEscapedReference33_E16AF135E664C72DDA9A5705859E2720LLAA6SourceV7LocatedVy_AA3ASTV4AtomV4KindOGSgyFTm : 1372 -> 1360
~ _$sSlsE5first7ElementQzSgvgSS17UnicodeScalarViewV_Tg5 : 456 -> 512
~ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtF12_RegexParser3ASTV20CustomCharacterClassV6MemberO_Tg5 : 476 -> 480
~ _$ss20_ArrayBufferProtocolPsE15replaceSubrange_4with10elementsOfySnySiG_Siqd__ntSlRd__7ElementQyd__AGRtzlFs01_aB0Vy12_RegexParser3ASTV20CustomCharacterClassV6MemberOG_s15EmptyCollectionVyARGTg5Tf4nndn_n : 348 -> 344
~ _$s12_RegexParser11CaptureListV0C0Vwst : 80 -> 76
~ _$s12_RegexParser0B0V14parseGroupBody5start_AA3ASTV0D0VSS5IndexV_AA6SourceV7LocatedVy_AI4KindOGtF : 968 -> 1040
~ _$s12_RegexParser0A9Validator33_D63F04F108272DD427D4E85D589C1C70LLV13validateGroupyyAA3ASTV0N0VF : 648 -> 664
~ _$sSTsSQ7ElementRpzrlE8containsySbABFSaySJG_Tg5 : 116 -> 132
~ _$s12_RegexParser0B0V25lexMatchingOptionSequenceAA3ASTV0deF0VSgyF : 2264 -> 2252
~ _$sSTsE8contains5whereS2b7ElementQzKXE_tKFSS17UnicodeScalarViewV_Tg5059$sSy12_RegexParserE020spansMultipleLinesInA7LiteralSbvgSbs7d2O6E6VXEfU_Tf1cn_n : 404 -> 556
~ _$s12_RegexParser0B0V14validateNumber33_E16AF135E664C72DDA9A5705859E2720LLyxSgAA6SourceV7LocatedVy_SSG_xmAA9RadixKindOts17FixedWidthIntegerRzlFs6UInt32V_Tt1B5 : 1500 -> 1528
~ _$s12_RegexParser0B0V20lexNumberedReference33_E16AF135E664C72DDA9A5705859E2720LL20allowWholePatternRef0M14RecursionLevelAA3ASTV0E0VSgSb_SbtF : 936 -> 940
~ _$s12_RegexParser0A9Validator33_D63F04F108272DD427D4E85D589C1C70LLV23validateMatchingOptionsyyAA3ASTV0N14OptionSequenceVF : 2008 -> 2000
~ _$s12_RegexParser9_TreeNodePAAE6heightSivpAaBRzlxTK : 52 -> 56
~ _$s12_RegexParser14DelimiterLexer33_1710201BEB5C5E0B1A3F76C737834CEFLLV12tryEatEnding_13contentsStartSS0P0_SV3endtSgAA0C0V_SVtKF : 532 -> 528
~ _$s12_RegexParser14DelimiterLexer33_1710201BEB5C5E0B1A3F76C737834CEFLLV013tryLexOpeningC010poundCountAA0C0VSgSi_tF : 400 -> 408
~ _$ss17FixedWidthIntegerPsEyxSgSScfCs5UInt8V_Tt1g5 : 792 -> 816
~ _$ss13_parseInteger5ascii5radixq_Sgx_SitSyRzs010FixedWidthB0R_r0_lFSSSiADSSRszsAER_r0_lIetgyr_Tpq5s5UInt8V_Tg5 : 1492 -> 1508
~ _$ss17FixedWidthIntegerPsE_5radixxSgqd___SitcSyRd__lufcADSRys5UInt8VGXEfU_Si_SsTG5SiTf3nnpSi10_n : 320 -> 332
~ _$s12_RegexParser0B0V17lexKnownCondition33_E16AF135E664C72DDA9A5705859E2720LLAA3ASTV11ConditionalV0E0VSgyF : 928 -> 940
~ _$s12_RegexParser0B0V24lexOnigurumaNamedCalloutAA3ASTV4AtomV0F0OSgyFTm : 720 -> 724
~ _$s12_RegexParser0B0V24lexBacktrackingDirectiveAA3ASTV4AtomV0dE0VSgyF : 644 -> 648
~ _$ss13_parseInteger5ascii5radixq_Sgx_SitSyRzs010FixedWidthB0R_r0_lFSs_SiTg5 : 1432 -> 1456
~ _$ss13_parseInteger5ascii5radixq_Sgx_SitSyRzs010FixedWidthB0R_r0_lFSS_s6UInt32VTg5 : 1400 -> 1424
~ _$ss13_parseInteger5ascii5radixq_Sgx_SitSyRzs010FixedWidthB0R_r0_lFSS_SiTg5 : 1420 -> 1444
~ _$ss13_parseInteger5ascii5radixq_Sgx_SitSyRzs010FixedWidthB0R_r0_lFSS_s6UInt16VTg5 : 1492 -> 1508
~ _$sSTsE21_copySequenceContents12initializing8IteratorQz_SitSry7ElementQzG_tFSs8UTF8ViewV_Tgq5 : 524 -> 508
~ _$sSlsE5first7ElementQzSgvgSS17UnicodeScalarViewV_Tgq5 : 444 -> 500
~ _$ss10SetAlgebraPs7ElementQz012ArrayLiteralC0RtzrlE05arrayE0xAFd_tcfC12_RegexParser13SyntaxOptionsV_Tg5 : 196 -> 188
~ _$s12_RegexParser11CaptureListV07indexOfC05namedSiSgSS_tF : 156 -> 164
~ _$s12_RegexParser11CaptureListV03hasC05namedSbSS_tF : 132 -> 156
~ _$sSasSQRzlE2eeoiySbSayxG_ABtFZ12_RegexParser3ASTV20GlobalMatchingOptionV_Tt1g5 : 200 -> 212
~ _$sSasSQRzlE2eeoiySbSayxG_ABtFZ12_RegexParser10DiagnosticV_Tt1g5 : 604 -> 608
~ _$sSasSQRzlE2eeoiySbSayxG_ABtFZ12_RegexParser3ASTV4AtomV6ScalarV_Tt1g5 : 120 -> 132
~ _$sSasSQRzlE2eeoiySbSayxG_ABtFZ12_RegexParser3ASTV20CustomCharacterClassV6MemberO_Tt1g5 : 200 -> 216
~ _$sSasSQRzlE2eeoiySbSayxG_ABtFZ12_RegexParser3ASTV14MatchingOptionV_Tt1g5 : 120 -> 132
~ _$sSasSQRzlE2eeoiySbSayxG_ABtFZ12_RegexParser3ASTV6TriviaV_Tt1g5Tm : 204 -> 212
~ _$sSasSQRzlE2eeoiySbSayxG_ABtFZ12_RegexParser6SourceV8LocationV_Tt1g5 : 100 -> 116
~ _$sSasSQRzlE2eeoiySbSayxG_ABtFZ12_RegexParser11CaptureListV0D0V_Tt1g5 : 368 -> 380
~ _$s12_RegexParser11CaptureListV11descriptionSSvg : 488 -> 500
~ _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtF12_RegexParser3ASTV20CustomCharacterClassV6MemberO_Tg5 : 472 -> 476
~ _$s12_RegexParser19parseWithDelimitersyAA3ASTVxKSyRzSs11SubSequenceRtzlFSS_Tg5 : 1216 -> 1224
~ _$s12_RegexParser16CaptureStructureO6encode2toySw_tFADL__10isTopLevelyAC_SbtFTf0nnns_n : 608 -> 616
~ _$s12_RegexParser16CaptureStructureO6_printyyAA13PrettyPrinterVzF : 1228 -> 1236
~ _$s12_RegexParser0B0V18applySyntaxOptions33_F50E6FA39D48CAE20DE1ECAC5A1082E2LL2of8isScopedyAA3ASTV22MatchingOptionSequenceV_SbtF : 664 -> 728
~ _$sSTsE8contains5whereS2b7ElementQzKXE_tKFSs17UnicodeScalarViewV_Tg5059$sSy12_RegexParserE020spansMultipleLinesInA7LiteralSbvgSbs7d2O6E6VXEfU_Tf1cn_n : 952 -> 1000
~ _$s12_RegexParser11DiagnosticsV11hasAnyErrorSbvg : 56 -> 72
~ _$s12_RegexParser11DiagnosticsV13hasFatalErrorSbvg : 60 -> 76
~ _$sSasSHRzlE4hash4intoys6HasherVz_tF12_RegexParser10DiagnosticV_Tg5 : 356 -> 372
~ _$sSasSHRzlE4hash4intoys6HasherVz_tF12_RegexParser3ASTV20GlobalMatchingOptionV_Tg5 : 528 -> 532
~ _$sSasSHRzlE4hash4intoys6HasherVz_tF12_RegexParser3ASTV14MatchingOptionV_Tg5 : 112 -> 128
~ _$sSasSHRzlE4hash4intoys6HasherVz_tF12_RegexParser3ASTV20CustomCharacterClassV6MemberO_Tg5 : 844 -> 820
~ _$sSasSHRzlE4hash4intoys6HasherVz_tF12_RegexParser3ASTV6TriviaV_Tg5 : 148 -> 160
~ _$sSasSHRzlE4hash4intoys6HasherVz_tF12_RegexParser3ASTV4NodeO_Tg5 : 88 -> 108
~ _$sSasSHRzlE4hash4intoys6HasherVz_tF12_RegexParser6SourceV8LocationV_Tg5 : 96 -> 116
~ _$sSasSHRzlE4hash4intoys6HasherVz_tF12_RegexParser6SourceV7LocatedVy_SSG_Tg5 : 116 -> 128
~ _$sSasSHRzlE4hash4intoys6HasherVz_tF12_RegexParser3ASTV4AtomV6ScalarV_Tg5 : 112 -> 128
~ _$s12_RegexParser0A9Validator33_D63F04F108272DD427D4E85D589C1C70LLV17validateReferenceyyAA3ASTV0N0VF : 460 -> 492
~ _$s12_RegexParser0A9Validator33_D63F04F108272DD427D4E85D589C1C70LLV25validateCharacterProperty_2atyAA3ASTV4AtomV0nO0V_AA6SourceV8LocationVtF : 560 -> 576
~ _$ss10_NativeSetV4copyyyFSS_Tg5 : 344 -> 340
~ _$s12_RegexParser3ASTV4NodeO10_postOrder4intoySayAEGz_tF : 416 -> 412
~ _$s12_RegexParser3ASTV4NodeO7_render2inSaySSGSS_tF : 1864 -> 1860
~ _$s12_RegexParser13PrettyPrinterV17outputAsCanonicalyyAA3ASTV28GlobalMatchingOptionSequenceVF : 184 -> 200
~ _$s12_RegexParser13PrettyPrinterV17outputAsCanonicalyyAA3ASTV4NodeOF : 1304 -> 1324
~ _$s12_RegexParser13PrettyPrinterV17outputAsCanonicalyyAA3ASTV20CustomCharacterClassVF : 3480 -> 3536
~ _$s12_RegexParser13_ASTPrintablePAAE5_dumpSSyFAA3ASTV4NodeO_TB5 : 912 -> 908
~ _$s12_RegexParser13_ASTPrintablePAAE5_dumpSSyFAA3ASTV14AbsentFunctionV_TB5 : 816 -> 812
~ _$s12_RegexParser13_ASTPrintablePAAE5_dumpSSyFAA3ASTV13ConcatenationV_TB5 : 548 -> 552
~ _$s12_RegexParser13_ASTPrintablePAAE5_dumpSSyFAA3ASTV11AlternationV_TB5 : 676 -> 680
~ _$s12_RegexParser13_ASTPrintablePAAE5_dumpSSyF : 756 -> 752
~ _$s12_RegexParser3ASTV4AtomV9_dumpBaseSSvg : 1672 -> 1688
~ _$s12_RegexParser3ASTV4AtomV7CalloutO14OnigurumaNamedV7ArgListV9_dumpBaseSSvg : 340 -> 356
~ _$s12_RegexParser3ASTV20CustomCharacterClassV6MemberO9_dumpBaseSSvg : 1224 -> 1216
~ _$s12_RegexParser3ASTV11ensureValidACyKF : 308 -> 320
~ _$s12_RegexParser3ASTV4NodeO10hasCaptureSbvg : 372 -> 380
~ _$s12_RegexParser3ASTV9isInvalidSbvg : 56 -> 72
~ _$s12_RegexParser3ASTV11AlternationV8locationAA6SourceV8LocationVvg : 272 -> 276
~ _$s12_RegexParser3ASTV11AlternationV4hash4intoys6HasherVz_tF : 124 -> 136
~ _$s12_RegexParser3ASTV11AlternationV9hashValueSivg : 124 -> 144
~ _$s12_RegexParser3ASTV11AlternationVSHAASH9hashValueSivgTW : 124 -> 144
~ _$s12_RegexParser3ASTV11AlternationVSHAASH4hash4intoys6HasherVz_tFTW : 124 -> 136
~ _$s12_RegexParser3ASTV11AlternationVSHAASH13_rawHashValue4seedS2i_tFTW : 120 -> 140
~ _$s12_RegexParser3ASTV13ConcatenationV4hash4intoys6HasherVz_tF : 124 -> 136
~ _$s12_RegexParser3ASTV13ConcatenationV9hashValueSivg : 148 -> 160
~ _$s12_RegexParser3ASTV13ConcatenationVSHAASH9hashValueSivgTW : 148 -> 160
~ _$s12_RegexParser3ASTV13ConcatenationVSHAASH13_rawHashValue4seedS2i_tFTW : 144 -> 156
~ _$s12_RegexParser3ASTV28GlobalMatchingOptionSequenceV8locationAA6SourceV8LocationVvg : 100 -> 104
~ _$s12_RegexParser3ASTV20CustomCharacterClassV5SetOpO8rawValueSSvg : 28 -> 24
~ _$s12_RegexParser3ASTV20CustomCharacterClassV22strippingTriviaShallowAEvg : 480 -> 476
~ _$s12_RegexParser3ASTV20CustomCharacterClassV6MemberO4hash4intoys6HasherVz_tF : 724 -> 720
~ _$s12_RegexParser3ASTV20CustomCharacterClassV5SetOpOSYAASY8rawValue03RawJ0QzvgTW : 32 -> 28
~ _$s12_RegexParser3ASTV20CustomCharacterClassV5SetOpOSHAASH9hashValueSivgTW : 96 -> 92
~ _$s12_RegexParser3ASTV20CustomCharacterClassV5SetOpOSHAASH4hash4intoys6HasherVz_tFTW : 68 -> 64
~ _$s12_RegexParser3ASTV20CustomCharacterClassV5SetOpOSHAASH13_rawHashValue4seedS2i_tFTW : 92 -> 88
~ _$s12_RegexParser3ASTV5GroupV4KindOwst : 92 -> 88
~ _$sSTsSQ7ElementRpzrlE13elementsEqualySbqd__STRd__AAQyd__ABRSlFSS8UTF8ViewV_SWTg5 : 464 -> 440
~ _$sSTsSQ7ElementRpzrlE13elementsEqualySbqd__STRd__AAQyd__ABRSlFSW_SS8UTF8ViewVTg5 : 520 -> 500
~ _$sSTsSQ7ElementRpzrlE13elementsEqualySbqd__STRd__AAQyd__ABRSlFSs8UTF8ViewV_s8RepeatedVys5UInt8VGTg5 : 568 -> 548
~ _$sSTsSQ7ElementRpzrlE13elementsEqualySbqd__STRd__AAQyd__ABRSlFSW_Ss8UTF8ViewVTg5 : 560 -> 540
~ _$sSTsSQ7ElementRpzrlE13elementsEqualySbqd__STRd__AAQyd__ABRSlFSays5UInt8VG_SS8UTF8ViewVTg5 : 508 -> 488
~ _$s12_RegexParser3ASTV4AtomV14EscapedBuiltinO9characterSJvg : 28 -> 24
~ _$s12_RegexParser3ASTV4AtomV14ScalarSequenceV12scalarValuesSays7UnicodeO0E0VGvg : 192 -> 216
~ _$s12_RegexParser3ASTV4AtomV17CharacterPropertyV4KindO4hash4intoys6HasherVz_tF : 956 -> 952
~ _$s12_RegexParser3ASTV4AtomV17CharacterPropertyV19PCRESpecialCategoryO8rawValueSSvg : 28 -> 24
~ _$s12_RegexParser3ASTV4AtomV17CharacterPropertyV19PCRESpecialCategoryOSYAASY8rawValue03RawJ0QzvgTW : 32 -> 28
~ _$s12_RegexParser3ASTV4AtomV17CharacterPropertyV19PCRESpecialCategoryOSHAASH9hashValueSivgTW : 96 -> 92
~ _$s12_RegexParser3ASTV4AtomV17CharacterPropertyV19PCRESpecialCategoryOSHAASH4hash4intoys6HasherVz_tFTW : 68 -> 64
~ _$s12_RegexParser3ASTV4AtomV17CharacterPropertyV19PCRESpecialCategoryOSHAASH13_rawHashValue4seedS2i_tFTW : 92 -> 88
~ _$s12_RegexParser3ASTV4AtomV14EscapedBuiltinO11scalarValues7UnicodeO6ScalarVSgvg : 24 -> 20
~ _$s12_RegexParser3ASTV4AtomV18literalStringValueSSSgvg13scalarLiteralL_ySSSays7UnicodeO6ScalarVGF : 448 -> 456
~ _$ss11_StringGutsV15scalarAlignSlowySS5IndexVAEF : 288 -> 256
```
