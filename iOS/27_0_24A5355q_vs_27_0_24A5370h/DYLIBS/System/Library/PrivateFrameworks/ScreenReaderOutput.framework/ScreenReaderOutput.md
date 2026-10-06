## ScreenReaderOutput

> `/System/Library/PrivateFrameworks/ScreenReaderOutput.framework/ScreenReaderOutput`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9acc4` | `0x9b508` | **`+0x844`** |
| `__AUTH_CONST.__objc_const` | `0xbb38` | `0xbc18` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x8ed8` | `0x8f70` | **`+0x98`** |
| `__TEXT.__oslogstring` | `0x26d3` | `0x2763` | **`+0x90`** |
| `__TEXT.__cstring` | `0x5971` | `0x59e1` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x5420` | `0x5480` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x3220` | `0x3280` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x4630` | `0x4678` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0x2868` | `0x2880` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x8ac` | `0x8c0` | **`+0x14`** |
| `__DATA.__bss` | `0x11f8` | `0x1208` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x18fc` | `0x1900` | **`+0x4`** |

### Other Changes

```diff

-455.1.1.0.0
+458.0.0.0.0

-  Functions: 3944
-  Symbols:   5723
-  CStrings:  1048
+  Functions: 3959
+  Symbols:   5746
+  CStrings:  1057
Symbols:
+ +[SCROBrailleUIUtilities textFromPDFAtURL:]
+ -[SCROBrailleHandlerXPC runScriptFile:]
+ -[SCROBrailleHandlerXPC runShortcutWithIdentifier:]
+ -[SCROBrailleHandlerXPC scriptHandler]
+ -[SCROBrailleHandlerXPC setScriptHandler:]
+ -[SCROScriptClient _setupXPCConnection]
+ -[SCROScriptClient setXpcConnection:]
+ -[SCROScriptClient setXpcRemoteProxy:]
+ -[SCROScriptClient xpcConnection]
+ -[SCROScriptClient xpcRemoteProxy]
+ GCC_except_table1522
+ GCC_except_table1642
+ GCC_except_table1781
+ GCC_except_table1783
+ GCC_except_table1791
+ GCC_except_table1800
+ GCC_except_table1883
+ GCC_except_table1932
+ GCC_except_table2044
+ GCC_except_table2065
+ GCC_except_table2070
+ GCC_except_table2076
+ GCC_except_table2175
+ GCC_except_table2357
+ GCC_except_table2375
+ GCC_except_table2491
+ GCC_except_table2492
+ GCC_except_table2497
+ GCC_except_table2503
+ GCC_except_table2508
+ GCC_except_table2509
+ GCC_except_table2514
+ GCC_except_table2519
+ GCC_except_table2521
+ GCC_except_table2524
+ GCC_except_table2872
+ GCC_except_table2873
+ GCC_except_table2891
+ GCC_except_table2910
+ GCC_except_table2911
+ GCC_except_table2912
+ GCC_except_table2975
+ GCC_except_table2977
+ GCC_except_table2979
+ GCC_except_table2980
+ GCC_except_table2982
+ GCC_except_table2984
+ _OBJC_IVAR_$_SCROBrailleDisplay._lastSentCells
+ _OBJC_IVAR_$_SCROBrailleDisplay._lastSentRows
+ _OBJC_IVAR_$_SCROBrailleHandlerXPC._scriptHandler
+ _OBJC_IVAR_$_SCROScriptClient._xpcConnection
+ _OBJC_IVAR_$_SCROScriptClient._xpcRemoteProxy
+ _PDFDocumentFunction
+ _PDFKitLibrary.sLib
+ _PDFKitLibrary.sOnce
+ ___39-[SCROScriptClient _setupXPCConnection]_block_invoke
+ ___PDFKitLibrary_block_invoke
+ _classPDFDocument
+ _getPDFDocumentClass
+ _initPDFDocument
- GCC_except_table1518
- GCC_except_table1638
- GCC_except_table1777
- GCC_except_table1779
- GCC_except_table1787
- GCC_except_table1796
- GCC_except_table1879
- GCC_except_table1924
- GCC_except_table2040
- GCC_except_table2061
- GCC_except_table2066
- GCC_except_table2072
- GCC_except_table2171
- GCC_except_table2353
- GCC_except_table2371
- GCC_except_table2487
- GCC_except_table2488
- GCC_except_table2489
- GCC_except_table2498
- GCC_except_table2499
- GCC_except_table2500
- GCC_except_table2501
- GCC_except_table2515
- GCC_except_table2517
- GCC_except_table2520
- GCC_except_table2860
- GCC_except_table2861
- GCC_except_table2876
- GCC_except_table2895
- GCC_except_table2896
- GCC_except_table2897
- GCC_except_table2960
- GCC_except_table2962
- GCC_except_table2964
- GCC_except_table2965
- GCC_except_table2967
- GCC_except_table2969
CStrings:
+ ".pdf"
+ "/Library/Accessibility/ktoa_u_kwa_v6.dic"
+ "/System/Library/Frameworks/PDFKit.framework/PDFKit"
+ "Braille UI: Failed to open PDF %@"
+ "Braille UI: PDF has no extractable text %@"
+ "NBSC Braille for text: can't read ktoa_u_kwa: %s"
+ "NBSC Braille for text: writing the unzipped file of ktoa_u_kwa failed: %@"
+ "PDFDocument"
+ "SCROScriptClient XPC connection invalidated"
+ "SCROScriptClient XPC error: %@"
+ "pdf"
- "NBSC Braille for text: can't read ktoa_u_kwp.zip: %s"
- "NBSC Braille for text: writing the unzipped file of ktoa_u_kwa.zip failed: %@"
```
