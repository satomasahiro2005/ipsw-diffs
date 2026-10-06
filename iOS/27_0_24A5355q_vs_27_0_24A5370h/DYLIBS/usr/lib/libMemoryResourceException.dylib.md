## libMemoryResourceException.dylib

> `/usr/lib/libMemoryResourceException.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x26e0` | `0x1e00` | **`-0x8e0`** |
| `__DATA.__bss` | `—` | `0x800` | **`+0x800`** |
| `__DATA_CONST.__const` | `0xe38` | `0x650` | **`-0x7e8`** |
| `__TEXT.__cstring` | `0x1f38` | `0x1b0c` | **`-0x42c`** |
| `__TEXT.__text` | `0x1ada4` | `0x1ac4c` | **`-0x158`** |
| `__DATA_DIRTY.__bss` | `0x4189` | `0x4101` | **`-0x88`** |
| `__AUTH_CONST.__const` | `0x280` | `0x260` | **`-0x20`** |
| `__DATA.__common` | `0x30` | `0x38` | **`+0x8`** |

### Other Changes

```diff

-356.0.0.0.0
+358.0.0.0.0

-  Functions: 498
-  Symbols:   1280
-  CStrings:  463
+  Functions: 497
+  Symbols:   1279
+  CStrings:  392
Symbols:
+ _categoryNameForTag:.tagCache
- ___37+[FPMemoryRegion categoryNameForTag:]_block_invoke
- _gRegionLabels
Functions:
~ _getLogPathsSortedByProcessFrequencyForLogs : 760 -> 756
~ +[RMECacheEnumerator getLogPathsForSystemDiagnostic] : 1968 -> 1956
~ _filesWithinSizeThreshold : 420 -> 416
~ _filesWithinAgeThreshold : 456 -> 452
~ _uniqueLogsArray : 332 -> 328
~ -[MemoryResourceException _symbolOwners] : 744 -> 740
~ -[MemoryResourceException prettyPrintBinaryImages] : 860 -> 848
~ -[MemoryResourceException prettyPrintIOAccelMemoryInfo] : 1432 -> 1428
~ -[MemoryResourceException _populateAddtionalMetadataWithOptions:timeoutSecs:] : 4104 -> 4100
~ ___77-[MemoryResourceException _populateAddtionalMetadataWithOptions:timeoutSecs:]_block_invoke : 1380 -> 1372
~ +[FPProcess _nameForBsdInfo:] : 432 -> 424
~ _newProcessStructures : 360 -> 352
~ +[FPProcess childPidsForPids:] : 576 -> 572
~ +[FPProcess removeIdleExitCleanProcessesFrom:] : 364 -> 360
~ -[FPUserProcess gatherData:extendedInfoProvider:] : 2528 -> 2524
~ -[FPUserProcess _gatherOwnedVmObjects] : 544 -> 556
~ ___65-[FPUserProcess _populateMemoryRegionWithPageQueries:regionInfo:]_block_invoke : 868 -> 860
~ ___51-[FPUserProcess _addSubrangesForRegion:purgeState:]_block_invoke : 588 -> 580
~ -[FPUserProcess _gatherLedgers] : 220 -> 216
~ ___33-[FPUserProcess _gatherImageData]_block_invoke_2 : 1552 -> 1548
~ -[FPUserProcess auxData] : 496 -> 632
~ -[FPUserProcess extendedInfoForRegionType:at:extendedInfoProvider:] : 1436 -> 1432
~ -[FPMemoryObject finalizeUsingRegionDirtySize:] : 2080 -> 2056
~ -[FPMemoryObject _fakeRegion] : 292 -> 288
~ -[FPMemoryObject viewForProcess:] : 568 -> 564
~ -[FPMemoryObject _canonicalRegion] : 344 -> 340
~ -[FPMemoryObject wireTag] : 260 -> 256
~ +[FPMemoryRegion categoryNameForTag:] : 364 -> 324
- ___37+[FPMemoryRegion categoryNameForTag:]_block_invoke
~ -[MREOutputFormatterInMemory printProcessHeader:] : 1572 -> 1576
~ -[MREOutputFormatterInMemory dataForCategories:] : 748 -> 740
~ -[MREOutputFormatterInMemory printSharedCategories:sharedWith:forProcess:hasProcessView:total:] : 636 -> 632
~ -[MREOutputFormatterInMemory printProcessesWithWarnings:processesWithErrors:globalErrors:] : 592 -> 584
~ -[FPFootprint _destroyMemoryObjectMaps] : 520 -> 516
~ -[FPFootprint analyzeData] : 2472 -> 2440
~ +[FPFootprint _totalForCategories:outTotal:] : 424 -> 420
~ -[FPFootprint printOutputVerbose:summarize:noCategories:] : 6296 -> 6228
~ -[FPFootprint _categoriesForObjects:viewedByProcess:hasProcessView:summarize:] : 568 -> 564
~ -[FPFootprint _categoriesForAllProcessesShouldSummarize:] : 676 -> 672
~ ___75-[FPFootprint _generateProcessToProcessGroupsWithSharedCacheProcessGroups:]_block_invoke : 356 -> 364
~ -[FPFootprint ioAccelMemoryInfoDetailsAtAddress:for:error:] : 1748 -> 1744
~ ___59-[FPFootprint ioAccelMemoryInfoDetailsAtAddress:for:error:]_block_invoke : 768 -> 760
~ _FPLedgerNameForLedger : 72 -> 76
~ ___FPLedgerIndexForLedger_block_invoke : 336 -> 332
~ _mergePrefsFromInput : 2176 -> 2168
~ _RMEGetTimeOrderedLogPathsMatchingPrefs : 1124 -> 1116
~ _mergePrefsFromInputProcessList : 444 -> 440
~ -[NSDictionary(FPAuxData) fp_mergeWithData:forceAggregate:] : 700 -> 692
~ -[NSDictionary(FPAuxData) fp_jsonRepresentation] : 348 -> 344
CStrings:
+ "VM_MEMORY_%u"
+ "r!"
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
- "sbrk"
- "shared pmap"
- "skywalk"
- "stack"
- "system/kernel diagnostics"
- "tag %d"
- "unshared pmap"
- "untagged (VM_ALLOCATE)"
- "video bitstream"
```
