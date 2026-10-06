## footprint

> `/usr/bin/footprint`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x1a00` | `0x10e0` | **`-0x920`** |
| `__DATA_CONST.__const` | `0xf10` | `0x708` | **`-0x808`** |
| `__DATA.__bss` | `0x4140` | `0x48b8` | **`+0x778`** |
| `__TEXT.__cstring` | `0x311b` | `0x2ceb` | **`-0x430`** |
| `__TEXT.__text` | `0x1fc30` | `0x1fa48` | **`-0x1e8`** |
| `__TEXT.__objc_stubs` | `0x2420` | `0x23e0` | **`-0x40`** |
| `__TEXT.__objc_methname` | `0x24fe` | `0x24d3` | **`-0x2b`** |
| `__DATA.__objc_selrefs` | `0xa38` | `0xa28` | **`-0x10`** |
| `__DATA.__common` | `0x38` | `0x40` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x498` | `0x4a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-356.0.0.0.0
+358.0.0.0.0

-  Functions: 435
-  Symbols:   1501
-  CStrings:  1143
+  Functions: 434
+  Symbols:   1498
+  CStrings:  1068
Symbols:
+ categoryNameForTag:.tagCache
- ___37+[FPMemoryRegion categoryNameForTag:]_block_invoke
- _gRegionLabels
- _objc_msgSend$rangeOfString:options:
- _objc_msgSend$substringWithRange:
Functions:
~ +[FPSystemMem getBootCarveoutSize] : 256 -> 268
~ ___38-[FPMemgraphProcess enumerateRegions:]_block_invoke : 1548 -> 1348
~ +[FPMemoryRegion categoryNameForTag:] : 368 -> 328
- ___37+[FPMemoryRegion categoryNameForTag:]_block_invoke
~ -[FPMemoryObject finalizeUsingRegionDirtySize:] : 444 -> 440
~ -[FPMemoryObject finalizeObjectWithKernelRegion:] : 624 -> 620
~ -[FPMemoryObject _finalizeWithTotal:useRegionDirtySize:skipProcessViewCulling:] : 1784 -> 1764
~ -[FPMemoryObject _fakeRegion] : 292 -> 288
~ -[FPMemoryObject viewForProcess:] : 568 -> 564
~ -[FPMemoryObject _canonicalRegion] : 340 -> 336
~ -[FPMemoryObject wireTag] : 260 -> 256
~ +[FPProcess _nameForBsdInfo:] : 432 -> 424
~ _newProcessStructures : 360 -> 352
~ +[FPProcess childPidsForPids:] : 576 -> 572
~ +[FPProcess removeIdleExitCleanProcessesFrom:] : 364 -> 360
~ -[FPUserProcess gatherData:extendedInfoProvider:] : 2528 -> 2524
~ -[FPUserProcess _gatherOwnedVmObjects] : 544 -> 556
~ ___65-[FPUserProcess _populateMemoryRegionWithPageQueries:regionInfo:]_block_invoke : 908 -> 900
~ ___51-[FPUserProcess _addSubrangesForRegion:purgeState:]_block_invoke : 588 -> 580
~ -[FPUserProcess _gatherLedgers] : 200 -> 196
~ ___33-[FPUserProcess _gatherImageData]_block_invoke_2 : 1580 -> 1576
~ -[FPUserProcess auxData] : 496 -> 632
~ -[FPUserProcess extendedInfoForRegionType:at:extendedInfoProvider:] : 1436 -> 1432
~ -[FPKernelProcess gatherData:extendedInfoProvider:] : 2560 -> 2576
~ +[FPKernelProcess _nameForWiredInfo:withSymbolicator:zoneNames:zoneCount:] : 504 -> 508
~ -[NSDictionary(FPAuxData) fp_mergeWithData:forceAggregate:] : 700 -> 692
~ -[NSDictionary(FPAuxData) fp_jsonRepresentation] : 348 -> 344
~ -[FPFootprintArgs targetProcessesAndError:] : 4488 -> 4464
~ _main : 8488 -> 8472
~ ___sampleFootprint_block_invoke : 1136 -> 1128
~ -[FPFootprint _destroyMemoryObjectMaps] : 520 -> 516
~ -[FPFootprint analyzeData] : 2924 -> 2912
~ +[FPFootprint _totalForCategories:outTotal:] : 424 -> 420
~ -[FPFootprint printOutputVerbose:summarize:noCategories:] : 6788 -> 6716
~ -[FPFootprint _categoriesForObjects:viewedByProcess:hasProcessView:summarize:] : 544 -> 540
~ ___75-[FPFootprint _generateProcessToProcessGroupsWithSharedCacheProcessGroups:]_block_invoke : 372 -> 380
~ -[FPFootprint ioAccelMemoryInfoDetailsAtAddress:for:error:] : 1748 -> 1744
~ ___59-[FPFootprint ioAccelMemoryInfoDetailsAtAddress:for:error:]_block_invoke : 768 -> 760
~ -[FPOutputFormatterJSON printProcessHeader:] : 2080 -> 2072
~ ___44-[FPOutputFormatterJSON printProcessHeader:]_block_invoke : 2248 -> 2284
~ -[FPOutputFormatterJSON JSONForCategories:] : 1112 -> 1108
~ -[FPOutputFormatterJSON printSharedCategories:sharedWith:forProcess:hasProcessView:total:] : 584 -> 580
~ -[FPOutputFormatterJSON printSharedCache:categories:sharedWith:total:] : 500 -> 496
~ -[FPOutputFormatterJSON JSONForAuxData:] : 744 -> 740
~ -[FPOutputFormatterJSON printProcessesWithWarnings:processesWithErrors:globalErrors:] : 1568 -> 1552
~ -[FPOutputFormatterJSON endAtTime:] : 1476 -> 1472
~ -[FPOutputFormatterPerfdata _addCategories:] : 636 -> 640
~ -[FPOutputFormatterPerfdata printProcessAuxData:forProcess:] : 864 -> 860
~ -[FPOutputFormatterPerfdata _emitCategoryAuxDataVariables:name:] : 776 -> 772
~ -[FPOutputFormatterPerfdata _emitAuxData:parentMetric:processName:summaryTag:] : 656 -> 652
~ -[FPOutputFormatterPerfdata printSummaryCategories:total:hadErrors:] : 804 -> 800
~ ___64-[FPOutputFormatterText printVmmapLikeOutputForProcess:regions:]_block_invoke : 1292 -> 1308
~ -[FPOutputFormatterText printProcessHeader:] : 1400 -> 1392
~ -[FPOutputFormatterText printSharedCategories:sharedWith:forProcess:hasProcessView:total:] : 2280 -> 2276
~ -[FPOutputFormatterText printProcessesWithWarnings:processesWithErrors:globalErrors:] : 1372 -> 1360
~ -[FPOutputFormatterText printGlobalAuxData:] : 1240 -> 1236
~ ___53-[FPOutputFormatterText _printCategories:forProcess:]_block_invoke : 1164 -> 1160
~ -[FPOutputFormatterText endAtTime:] : 1720 -> 1716
~ _FPLedgerNameForLedger : 72 -> 76
~ ___FPLedgerIndexForLedger_block_invoke : 336 -> 332
CStrings:
+ "VM_MEMORY_%u"
+ "[6Q]"
+ "r!"
- "("
- ")"
- "+[FPMemoryRegion categoryNameForTag:]"
- "ASL"
- "ATS (font support)"
- "Accelerate image backing stores"
- "Accounts framework"
- "Activity Tracing"
- "AppKit"
- "Assets Library"
- "CG backing stores"
- "CG framebuffers"
- "CG image"
- "CG raster data"
- "CG shared images"
- "CG x-alloc"
- "Core Data"
- "Core Data object IDs"
- "CoreAnimation"
- "CoreGraphics"
- "CoreImage"
- "CoreMedia HLS"
- "CoreMedia HTTP cache"
- "CoreMedia RPC"
- "CoreMedia XPC"
- "CoreMedia memory pool"
- "CoreMedia read cache"
- "CoreProfile"
- "CoreServices"
- "CoreUI image data"
- "CoreUI image file"
- "DFR"
- "DHMM"
- "Foundation"
- "IOKit"
- "IOSurface"
- "ImageIO"
- "JS JIT generated code"
- "JS VM Gigacage"
- "JS VM Isolated Heap"
- "Java"
- "Mach message"
- "Objective-C dispatching code"
- "OpenCL"
- "OpenGL Shading Language"
- "QuickLook Thumbnails"
- "RawCamera"
- "SQLite page cache"
- "SceneKit"
- "Swift metadata"
- "Swift runtime"
- "WebCore purgeable data"
- "WebKit malloc"
- "[5Q]"
- "app-specific tag %d"
- "audio"
- "b!"
- "corpse info"
- "desc != NULL"
- "dyld malloc memory"
- "dyld private memory"
- "dylib"
- "guard"
- "libdispatch"
- "libnetwork"
- "os_alloc_once"
- "performance tool data"
- "rangeOfString:options:"
- "sbrk"
- "shared pmap"
- "skywalk"
- "stack"
- "substringWithRange:"
- "system/kernel diagnostics"
- "tag %d"
- "unshared pmap"
- "untagged (VM_ALLOCATE)"
- "video bitstream"
```
