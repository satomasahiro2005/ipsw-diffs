## AXRuntime

> `/System/Library/PrivateFrameworks/AXRuntime.framework/AXRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4df88` | `0x4e6dc` | **`+0x754`** |
| `__TEXT.__oslogstring` | `0x1535` | `0x16f9` | **`+0x1c4`** |
| `__TEXT.__objc_methlist` | `0x38f4` | `0x3954` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x50e0` | `0x5120` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1350` | `0x1390` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x2408` | `0x2440` | **`+0x38`** |
| `__TEXT.__cstring` | `0x5d8e` | `0x5dc3` | **`+0x35`** |
| `__DATA_CONST.__const` | `0x1270` | `0x1298` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x3a08` | `0x3a28` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xaa0` | `0xab0` | **`+0x10`** |
| `__TEXT.__const` | `0x448` | `0x458` | **`+0x10`** |
| `__DATA.__bss` | `0x300` | `0x308` | **`+0x8`** |
| `__DATA.__data` | `0x8b8` | `0x8c0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x23c` | `0x240` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0xba4` | `0xba0` | **`-0x4`** |

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

-  Functions: 1638
-  Symbols:   3240
-  CStrings:  947
+  Functions: 1652
+  Symbols:   3258
+  CStrings:  952
Symbols:
+ +[AXUIElement uiElementAtCoordinate:forApplication:contextId:displayId:allowSameProcess:coordinateIsInHostedCoordinates:]
+ -[AXElement _convertRectFromWindowCoordinates:]
+ -[AXElementFetcher _fuzzyMatchElement:candidate:]
+ -[AXElementFetcher findElementMatchingElement:allowFuzzyMatch:]
+ -[AXElementGroup _fuzzyMatchItem:candidate:]
+ -[AXElementGroup _unionOfChildFrames]
+ -[AXElementGroup firstDescendantMatchingItem:allowFuzzyMatch:]
+ -[_AXObjectCacheHelper .cxx_destruct]
+ GCC_except_table1178
+ GCC_except_table1330
+ GCC_except_table1333
+ GCC_except_table1362
+ GCC_except_table1379
+ GCC_except_table1393
+ GCC_except_table1471
+ GCC_except_table1499
+ GCC_except_table1546
+ GCC_except_table1607
+ GCC_except_table1615
+ GCC_except_table166
+ GCC_except_table169
+ GCC_except_table185
+ GCC_except_table240
+ GCC_except_table241
+ GCC_except_table259
+ GCC_except_table260
+ GCC_except_table264
+ GCC_except_table268
+ GCC_except_table277
+ GCC_except_table347
+ GCC_except_table349
+ GCC_except_table351
+ GCC_except_table365
+ GCC_except_table453
+ GCC_except_table459
+ GCC_except_table524
+ GCC_except_table545
+ GCC_except_table672
+ GCC_except_table678
+ GCC_except_table765
+ GCC_except_table769
+ GCC_except_table773
+ GCC_except_table783
+ GCC_except_table784
+ GCC_except_table785
+ GCC_except_table786
+ GCC_except_table838
+ GCC_except_table844
+ GCC_except_table919
+ GCC_except_table926
+ GCC_except_table930
+ GCC_except_table932
+ GCC_except_table956
+ GCC_except_table992
+ _AXAIWhiteGloveLoggingEnabled
+ _CGRectContainsRect
+ _OBJC_IVAR_$__AXObjectCacheHelper._weakElement
+ _UIAccessibilityTokenDynamicContentAnnouncement
+ __AXElementFromElementCache
+ __AXUIElementCopyElementAtPositionCommon
+ __AXUIElementCopyElementAtPositionInHostedCoordinatesWithParams
+ ___63-[AXElementFetcher findElementMatchingElement:allowFuzzyMatch:]_block_invoke
+ ____AXElementFromElementCache_block_invoke
+ ____AXUIElementCopyElementAtPositionCommon_block_invoke
+ ___block_descriptor_57_e8_32s40s48r_e5_v8?0ls32l8s40l8r48l8
+ __auditTokenCacheLock
- GCC_except_table1169
- GCC_except_table1321
- GCC_except_table1324
- GCC_except_table1353
- GCC_except_table1368
- GCC_except_table1382
- GCC_except_table1460
- GCC_except_table1488
- GCC_except_table1535
- GCC_except_table1593
- GCC_except_table1601
- GCC_except_table164
- GCC_except_table167
- GCC_except_table173
- GCC_except_table238
- GCC_except_table239
- GCC_except_table257
- GCC_except_table258
- GCC_except_table262
- GCC_except_table266
- GCC_except_table275
- GCC_except_table344
- GCC_except_table346
- GCC_except_table358
- GCC_except_table39
- GCC_except_table446
- GCC_except_table452
- GCC_except_table517
- GCC_except_table538
- GCC_except_table665
- GCC_except_table671
- GCC_except_table758
- GCC_except_table762
- GCC_except_table766
- GCC_except_table776
- GCC_except_table777
- GCC_except_table778
- GCC_except_table779
- GCC_except_table822
- GCC_except_table836
- GCC_except_table911
- GCC_except_table914
- GCC_except_table918
- GCC_except_table924
- GCC_except_table948
- GCC_except_table984
- ___47-[AXElementFetcher findElementMatchingElement:]_block_invoke
- ____AXUIElementCopyElementAtPositionWithParams_block_invoke
CStrings:
+ "<oob>"
+ "UIAccessibilityTokenDynamicContentAnnouncement"
+ "_AXInternalRemoveFromElementCache called off the main thread — this indicates a client is releasing AX elements on a background thread (rdar://183478648)"
+ "rdar://159429576 _axUnit word enter position=%ld direction=%d stringLen=%ld tokenizerRange={loc=%ld,len=%ld} string=%{private}@"
+ "rdar://159429576 _axUnit word punctuation-attach initial={loc=%ld,len=%ld} final={loc=%ld,len=%ld} leadingAttached=%ld trailingAttached=%ld resultSubstring=%{private}@"
```
