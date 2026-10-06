## Symbolication

> `/System/Library/PrivateFrameworks/Symbolication.framework/Symbolication`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbc230` | `0xbc2cc` | **`+0x9c`** |
| `__TEXT.__gcc_except_tab` | `0x596c` | `0x5990` | **`+0x24`** |
| `__AUTH_CONST.__cfstring` | `0xdba0` | `0xdbc0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2db8` | `0x2dc0` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-  CStrings:  2906
+  CStrings:  2907
Functions:
~ _OUTLINED_FUNCTION_2 : 32 -> 16
~ _OUTLINED_FUNCTION_4 -> _OUTLINED_FUNCTION_3 : 24 -> 32
~ -[VMUTaskMemoryScanner setDyldSharedCacheMemoryMappingOverridesWithRegions:] : 1164 -> 1172
~ ___59-[VMUTaskMemoryScanner _withReaderBlockForHeapEnumeration:]_block_invoke : 1840 -> 1844
~ -[VMUTaskMemoryScanner _identifySwiftAsyncTaskSlabs] : 1404 -> 1408
~ -[VMUTaskMemoryScanner zoneNameForNode:] : 532 -> 536
~ -[VMUTaskMemoryScanner withContentForNode:block:] : 1868 -> 1860
~ _OUTLINED_FUNCTION_5 : 20 -> 24
~ _OUTLINED_FUNCTION_10 -> _OUTLINED_FUNCTION_6 : 16 -> 20
~ _OUTLINED_FUNCTION_11 -> _OUTLINED_FUNCTION_7 : 16 -> 20
~ _OUTLINED_FUNCTION_19 : 12 -> 16
~ _OUTLINED_FUNCTION_20 : 20 -> 12
~ ___53-[VMUKernelCoreMemoryScanner _withMemoryReaderBlock:]_block_invoke : 1732 -> 1720
~ -[VMUKernelCoreMemoryScanner _enumerateZallocZones:blocks:] : 1808 -> 1816
~ -[VMUKernelCoreMemoryScanner zoneNameForNode:] : 532 -> 536
~ -[VMUKernelCoreMemoryScanner withContentForNode:block:] : 1788 -> 1800
~ _OUTLINED_FUNCTION_6 -> _OUTLINED_FUNCTION_9 : 12 -> 16
~ -[VMULeakDetector printContents:size:] : 380 -> 384
~ -[VMUProcessDescription _cpuTypeDescription] : 416 -> 504
~ -[VMUProcessObjectGraph parseMacOSArchitectureFromProcessDescription] : 604 -> 672
~ -[VMUMallocZoneAggregate modifySize:count:forClassInfo:] : 660 -> 656
~ -[VMUDirectedGraph removeMarkedNodes:] : 800 -> 804
~ -[VMUDirectedGraph _adjustAdjacencyMap] : 1156 -> 1164
~ -[VMUObjectGraph addEdgeFromNode:sourceOffset:withScanType:toNode:destinationOffset:] : 564 -> 568
~ -[VMUObjectGraph _refineTypesWithOverlay:] : 704 -> 708
~ -[VMUObjectGraph _compareWithGraph:andMarkOnMatch:] : 1144 -> 1148
~ -[VMUKernelCoreMemoryScanner scanLocalMemory:atOffset:node:length:isa:scanCaches:fieldInfo:stride:recorder:] : 3148 -> 3096
CStrings:
+ ".X1"
```
