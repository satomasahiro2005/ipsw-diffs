## libxslt.1.dylib

> `/usr/lib/libxslt.1.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2204c` | `0x21f24` | **`-0x128`** |
| `__AUTH.__data` | `—` | `0x20` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x40` | `0x20` | **`-0x20`** |

### Other Changes

```text
Functions:
~ _xsltParseStylesheetAttributeSet : 1452 -> 1444
~ _xsltCompileAttr : 1280 -> 1256
~ _xsltCompilePatternInternal : 2264 -> 2232
~ _xsltCompileRelativePathPattern : 444 -> 416
~ _xsltScanNCName : 628 -> 616
~ _xsltCompileIdKeyPattern : 1512 -> 1468
~ _xsltCompileStepPattern : 1524 -> 1484
~ _xsltScanLiteral : 512 -> 504
~ _xsltApplyXSLTTemplate : 1780 -> 1772
~ _xsltDocumentElem : 3272 -> 3252
~ _xsltCopyTree : 972 -> 944
~ _xsltApplyStylesheetInternal : 1944 -> 1952
~ _xsltParseStylesheetOutput : 1480 -> 1472
~ _xsltParseStylesheetProcess : 2556 -> 2568
~ _xsltParseStylesheetExcludePrefix : 712 -> 676
~ _xsltParseStylesheetExtPrefix : 480 -> 476
~ _xsltLoadStylesheetPI : 1476 -> 1460
~ _xsltGetQNameURI : 376 -> 384
~ _xsltGetQNameURI2 : 452 -> 444
```
