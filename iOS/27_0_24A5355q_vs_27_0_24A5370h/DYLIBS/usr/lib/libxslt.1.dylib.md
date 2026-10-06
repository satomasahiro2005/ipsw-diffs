## libxslt.1.dylib

> `/usr/lib/libxslt.1.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21fb0` | `0x2204c` | **`+0x9c`** |
| `__AUTH_CONST.__auth_got` | `0x6f0` | `0x6e0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x4f0` | `0x4e8` | **`-0x8`** |

### Other Changes

```diff

-21.13.0.0.0
+21.13.2.0.0

-  Symbols:   663
+  Symbols:   661
Symbols:
+ _arc4random_buf
- _random
- _srandom
- _time
Functions:
~ _xsltAttribute : 1240 -> 1256
~ _xsltFreeAVTList : 276 -> 260
~ _xsltCompileAttr : 1248 -> 1280
~ _xsltEvalAVT : 232 -> 228
~ _xsltDebug : 728 -> 708
~ _xsltDocumentFunction : 1568 -> 1560
~ _xsltKeyFunction : 1048 -> 1044
~ _xsltGenerateIdFunction : 988 -> 984
~ __initBaseValue : 68 -> 16
~ _xsltAddKey : 1084 -> 1064
~ _xsltInitCtxtKey : 1344 -> 1348
~ _xsltNumberFormat : 800 -> 812
~ _xsltNumberFormatTokenize : 1548 -> 1496
~ _xsltNumberFormatAlpha : 336 -> 332
~ _xsltFreeCompMatch : 216 -> 204
~ _xsltNormalizeCompSteps : 64 -> 80
~ _xsltTestCompMatch : 1648 -> 1660
~ _xsltCompilePatternInternal : 2208 -> 2264
~ _xsltGetTemplate : 1220 -> 1216
~ _xsltTestCompMatchDirect : 552 -> 560
~ _xsltTestStepMatch : 620 -> 628
~ _xsltCompileRelativePathPattern : 416 -> 444
~ _xsltScanNCName : 616 -> 628
~ _xsltCompileIdKeyPattern : 1464 -> 1512
~ _xsltCompileStepPattern : 1476 -> 1524
~ _xsltScanLiteral : 500 -> 512
~ _xsltStylePreCompute : 2120 -> 2128
~ _xsltAttrTemplateValueProcessNode : 740 -> 732
~ _xsltNewTransformContext : 916 -> 912
~ _xsltFreeTransformContext : 472 -> 468
~ _xsltApplyXSLTTemplate : 1792 -> 1780
~ _xsltApplySequenceConstructor : 2204 -> 2184
~ _xsltDocumentElem : 3252 -> 3272
~ _xsltComment : 340 -> 336
~ _xsltPreCompEval : 108 -> 124
~ _xsltCopyTree : 944 -> 972
~ _xsltApplyTemplates : 1428 -> 1424
~ _xsltPreCompEvalToBoolean : 108 -> 124
~ _xsltForEach : 1184 -> 1176
~ _xsltApplyStylesheetInternal : 1896 -> 1944
~ _xsltFlagRVTs : 524 -> 520
~ _xsltEvalUserParams : 92 -> 116
~ _xsltQuoteUserParams : 92 -> 116
~ _xsltProcessUserParamInternal : 988 -> 1000
~ _xsltStackLookup : 276 -> 260
~ _xsltXPathVariableLookup : 696 -> 680
~ _xsltAllocateExtraCtxt : 296 -> 284
~ _xsltParseTemplateContent : 1120 -> 1128
~ _xsltParseStylesheetProcess : 2580 -> 2556
~ _xsltParseStylesheetExcludePrefix : 708 -> 712
~ _xsltPreprocessStylesheet : 1124 -> 1120
~ _xsltLoadStylesheetPI : 1452 -> 1476
~ _xsltParseStylesheetTemplate : 1108 -> 1096
~ _xsltNewLocale : 1772 -> 1752
~ _xsltMessage : 348 -> 344
~ _xsltSplitQName : 180 -> 184
~ _xsltGetQNameURI : 360 -> 376
~ _xsltGetQNameURI2 : 448 -> 452
~ _xsltDocumentSortFunction : 176 -> 180
~ _xsltComputeSortResultInternal : 556 -> 560
~ _xsltDefaultSortFunction : 1768 -> 1744
~ _xsltSaveProfiling : 2316 -> 2296
~ _pretty_templ_match : 204 -> 200
~ _xsltGetProfileInformation : 800 -> 804
```
