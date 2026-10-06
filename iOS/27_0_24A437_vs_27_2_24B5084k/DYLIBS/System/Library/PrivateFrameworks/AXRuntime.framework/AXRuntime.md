## AXRuntime

> `/System/Library/PrivateFrameworks/AXRuntime.framework/AXRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e6dc` | `0x4e78c` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x16f9` | `0x1792` | **`+0x99`** |
| `__TEXT.__cstring` | `0x5dc3` | `0x5d92` | **`-0x31`** |
| `__TEXT.__gcc_except_tab` | `0xba0` | `0xb7c` | **`-0x24`** |
| `__AUTH_CONST.__const` | `0xbc8` | `0xba8` | **`-0x20`** |
| `__DATA_DIRTY.__bss` | `0x2f8` | `0x2d8` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x1390` | `0x13b0` | **`+0x20`** |
| `__AUTH_CONST.__objc_intobj` | `0x1650` | `0x1668` | **`+0x18`** |
| `__TEXT.__dlopen_cstrs` | `0x31a` | `0x303` | **`-0x17`** |
| `__DATA.__bss` | `0x308` | `0x318` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xab0` | `0xab8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x2e8` | `0x2e0` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x3954` | `0x395c` | **`+0x8`** |

### Other Changes

```diff

-3240.9.0.0.0
+3245.7.1.0.0

-  Functions: 1652
-  Symbols:   3258
-  CStrings:  952
+  Functions: 1653
+  Symbols:   3257
+  CStrings:  963
Symbols:
+ +[AXUIElement uiApplicationAtCoordinate:displayId:]
+ GCC_except_table1179
+ GCC_except_table1331
+ GCC_except_table1334
+ GCC_except_table1363
+ GCC_except_table1380
+ GCC_except_table1394
+ GCC_except_table1472
+ GCC_except_table1500
+ GCC_except_table1547
+ GCC_except_table1608
+ GCC_except_table1616
+ GCC_except_table167
+ GCC_except_table170
+ GCC_except_table176
+ GCC_except_table178
+ GCC_except_table180
+ GCC_except_table182
+ GCC_except_table184
+ GCC_except_table186
+ GCC_except_table242
+ GCC_except_table261
+ GCC_except_table265
+ GCC_except_table269
+ GCC_except_table278
+ GCC_except_table348
+ GCC_except_table350
+ GCC_except_table352
+ GCC_except_table366
+ GCC_except_table454
+ GCC_except_table460
+ GCC_except_table525
+ GCC_except_table831
+ GCC_except_table839
+ GCC_except_table845
+ GCC_except_table920
+ GCC_except_table923
+ GCC_except_table927
+ GCC_except_table931
+ GCC_except_table933
+ GCC_except_table957
+ GCC_except_table993
+ _QuartzCoreLibraryCore.frameworkLibrary
+ __AXIPCToPidTimedOut
+ ___QuartzCoreLibraryCore_block_invoke
+ ___getCADisplayClass_block_invoke
+ _audit_stringQuartzCore
+ _getCADisplayClass.softClass
+ _os_signpost_id_generate
- GCC_except_table1178
- GCC_except_table1330
- GCC_except_table1333
- GCC_except_table1362
- GCC_except_table1379
- GCC_except_table1393
- GCC_except_table1471
- GCC_except_table1499
- GCC_except_table1546
- GCC_except_table1607
- GCC_except_table1615
- GCC_except_table166
- GCC_except_table169
- GCC_except_table175
- GCC_except_table177
- GCC_except_table179
- GCC_except_table181
- GCC_except_table183
- GCC_except_table185
- GCC_except_table240
- GCC_except_table259
- GCC_except_table264
- GCC_except_table268
- GCC_except_table277
- GCC_except_table347
- GCC_except_table349
- GCC_except_table351
- GCC_except_table365
- GCC_except_table453
- GCC_except_table459
- GCC_except_table524
- GCC_except_table830
- GCC_except_table838
- GCC_except_table844
- GCC_except_table919
- GCC_except_table922
- GCC_except_table926
- GCC_except_table930
- GCC_except_table932
- GCC_except_table956
- GCC_except_table992
- _FrontBoardServicesLibraryCore.frameworkLibrary
- _NSInternalInconsistencyException
- ___FrontBoardServicesLibraryCore_block_invoke
- ____displayMonitor_block_invoke
- ___getFBSDisplayMonitorClass_block_invoke
- __displayMonitor.DisplayMonitor
- __displayMonitor.onceToken
- _audit_stringFrontBoardServices
- _getFBSDisplayMonitorClass.softClass
Functions:
~ __allDisplayTypes : 344 -> 484
~ __AXElementForAXUIElementUniqueId : 236 -> 212
~ _AXUIElementCopyAttributeValueRecursive : 1696 -> 1644
+ __AXIPCToPidTimedOut
~ _AXUIElementCopyParameterizedAttributeValueRecursive : 2068 -> 2028
~ _AXUIElementSetAttributeValue : 908 -> 864
~ _AXUIElementCopyMultipleAttributeValues : 1792 -> 1740
~ _AXUIElementPerformFencedActionWithValue : 920 -> 868
~ _AXUIElementPerformAction : 632 -> 580
~ _cfAttributedStringUnserialize : 2156 -> 2128
- ____displayMonitor_block_invoke
~ -[AXRemoteElement _accessibilitySortedElementsWithin] : 84 -> 104
~ -[AXRemoteElement accessibilityElements] : 408 -> 436
~ +[AXUIElement applyElementAttributeCacheScheme:] : 1600 -> 1612
~ +[AXUIElement uiApplicationAtCoordinate:] : 156 -> 8
+ +[AXUIElement uiApplicationAtCoordinate:displayId:]
~ -[AXUIElement _cachedValueForAttribute:] : 172 -> 368
~ -[AXUIElement arrayWithAXAttribute:] : 372 -> 596
~ -[AXUIElement valueArrayWithAXAttributes:] : 380 -> 600
~ -[AXElement parentGroup] : 8 -> 44
~ -[AXElement setParentGroup:] : 8 -> 12
~ -[AXElement .cxx_destruct] : 128 -> 136
~ -[AXElementGroup dealloc] : 344 -> 72
~ -[AXElementGroup parentGroup] : 20 -> 52
~ -[AXElementGroup .cxx_destruct] : 160 -> 176
CStrings:
+ "!1"
+ "AXAttributeCacheLookup"
+ "AXBatchAttributeIPC"
+ "AXIPCTimeoutToApp"
+ "AXSingleAttributeIPC"
+ "CADisplay"
+ "Class getCADisplayClass(void)_block_invoke"
+ "attr=%ld"
+ "attr=%ld result=%{public}s"
+ "cachedNull"
+ "count=%ld"
+ "hit"
+ "miss"
+ "pid=%d reason=IPCTimeout"
+ "softlink:r:path:/System/Library/Frameworks/QuartzCore.framework/QuartzCore"
+ "void *QuartzCoreLibrary(void)"
- "Class getFBSDisplayMonitorClass(void)_block_invoke"
- "FBSDisplayMonitor"
- "attributedString: range offset bsize math error"
- "softlink:r:path:/System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices"
- "void *FrontBoardServicesLibrary(void)"
```
