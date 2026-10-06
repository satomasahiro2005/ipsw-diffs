## ABMHelper

> `/System/Library/PrivateFrameworks/ABMHelper.framework/ABMHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cf444` | `0x1d058c` | **`+0x1148`** |
| `__TEXT.__gcc_except_tab` | `0x21888` | `0x21a08` | **`+0x180`** |
| `__AUTH_CONST.__const` | `0x9120` | `0x91b0` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0xdb4d` | `0xdbc4` | **`+0x77`** |
| `__TEXT.__unwind_info` | `0x7118` | `0x7148` | **`+0x30`** |
| `__TEXT.__cstring` | `0x88c2` | `0x88e8` | **`+0x26`** |
| `__DATA.__data` | `0x460` | `0x468` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x2960` | `0x2968` | **`+0x8`** |

### Other Changes

```diff

-1576.0.0.0.0
+1580.0.0.0.0

-  Functions: 4314
-  Symbols:   6799
-  CStrings:  2789
+  Functions: 4319
+  Symbols:   6807
+  CStrings:  2794
Symbols:
+ GCC_except_table149
+ GCC_except_table177
+ GCC_except_table178
+ GCC_except_table185
+ __ZN3abm5trace33kPCIDriverSnapshotDirectorySuffixE
+ __ZN3abm6helper30kCommandCollectAllBasebandLogsE
+ ___copy_helper_block_e8_40c32_ZTSNSt3__110shared_ptrI5TraceEE56c45_ZTSN3ctu2cf11CFSharedRefIK14__CFDictionaryEE64c32_ZTSNSt3__110shared_ptrI5TraceEE
+ ___destroy_helper_block_e8_40c32_ZTSNSt3__110shared_ptrI5TraceEE56c45_ZTSN3ctu2cf11CFSharedRefIK14__CFDictionaryEE64c32_ZTSNSt3__110shared_ptrI5TraceEE
CStrings:
+ "-pci-bin"
+ "CommandCollectAllBasebandLogs"
+ "Request to collect baseband and driver logs"
+ "Snapshot baseband and driver: Begin"
+ "Snapshot baseband and driver: Complete"
```
