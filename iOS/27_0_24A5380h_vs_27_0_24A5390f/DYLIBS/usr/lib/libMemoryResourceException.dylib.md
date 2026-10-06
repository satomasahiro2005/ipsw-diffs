## libMemoryResourceException.dylib

> `/usr/lib/libMemoryResourceException.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x800` | `—` | **`-0x800`** |
| `__DATA_DIRTY.__bss` | `0x4101` | `0x4901` | **`+0x800`** |
| `__TEXT.__text` | `0x1ac5c` | `0x1ad98` | **`+0x13c`** |
| `__AUTH_CONST.__objc_const` | `0x3090` | `0x31c0` | **`+0x130`** |
| `__TEXT.__objc_methlist` | `0x15fc` | `0x167c` | **`+0x80`** |
| `__AUTH.__objc_data` | `0xf0` | `0x140` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0xf88` | `0xfc0` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x4a8` | `0x4c0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x290` | `0x29c` | **`+0xc`** |
| `__TEXT.__cstring` | `0x1b0c` | `0x1b16` | **`+0xa`** |
| `__DATA_CONST.__got` | `0x288` | `0x290` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x90` | `0x98` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x78` | `0x80` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x3c4` | `0x3bc` | **`-0x8`** |

### Other Changes

```diff

-360.0.0.0.0
+364.0.0.0.0

-  Functions: 497
-  Symbols:   1279
+  Functions: 507
+  Symbols:   1298
Symbols:
+ -[FPMemoryObject hasSyntheticObjectID]
+ -[FPMemoryRegion adoptObjectIdentityFromMemoryObject:]
+ -[FPMemoryRegion hasSyntheticObjectID]
+ -[FPMemoryRegion setSyntheticObjectIDForPid:]
+ -[FPProcess _canReuseInsteadOf:]
+ -[FPProcess _gatherData:extendedInfoProvider:]
+ -[FPProcess canReuseInsteadOf:]
+ -[FPProcess isGathered]
+ -[FPUserProcess _canReuseInsteadOf:]
+ -[FPUserProcess _gatherData:extendedInfoProvider:]
+ -[RMELogPath .cxx_destruct]
+ GCC_except_table30
+ _OBJC_CLASS_$_RMELogPath
+ _OBJC_IVAR_$_FPFootprint._wireTagUniqueObjectsNextKey
+ _OBJC_IVAR_$_FPMemoryRegion._hasSyntheticObjectID
+ _OBJC_IVAR_$_RMELogPath._fileCreationDate
+ _OBJC_IVAR_$_RMELogPath._filePath
+ _OBJC_METACLASS_$_RMELogPath
+ _RMEGetTimeOrderedLogPaths
+ __OBJC_$_INSTANCE_METHODS_RMELogPath
+ __OBJC_$_INSTANCE_VARIABLES_RMELogPath
+ __OBJC_CLASS_RO_$_RMELogPath
+ __OBJC_METACLASS_RO_$_RMELogPath
+ ___RMEGetTimeOrderedLogPaths_block_invoke
+ ___block_descriptor_32_e35_q24?0"RMELogPath"8"RMELogPath"16l
- -[FPUserProcess gatherData:extendedInfoProvider:]
- GCC_except_table28
- _OBJC_IVAR_$_FPMemoryRegion._reserved
- _RMEGetTimeOrderedLogPathsMatchingPrefs
- ___RMEGetTimeOrderedLogPathsMatchingPrefs_block_invoke
- ___block_descriptor_32_e25_q24?0"NSURL"8"NSURL"16l
CStrings:
+ "q24@?0@\"RMELogPath\"8@\"RMELogPath\"16"
- "q24@?0@\"NSURL\"8@\"NSURL\"16"
```
