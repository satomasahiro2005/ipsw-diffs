## NANDInfo

> `/System/Library/PrivateFrameworks/NANDInfo.framework/NANDInfo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_intobj` | `0x11bc8` | `0x120d8` | **`+0x510`** |
| `__AUTH_CONST.__cfstring` | `0xfba0` | `0xffa0` | **`+0x400`** |
| `__DATA_CONST.__objc_arraydata` | `0xd668` | `0xd9f0` | **`+0x388`** |
| `__TEXT.__cstring` | `0xc7a9` | `0xcaa9` | **`+0x300`** |
| `__TEXT.__text` | `0x1d4e4` | `0x1d784` | **`+0x2a0`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x9030` | `0x92b8` | **`+0x288`** |

### Other Changes

```diff

-849.40.12.0.1
+849.40.17.0.0

-  Functions: 279
-  Symbols:   472
-  CStrings:  2386
+  Functions: 281
+  Symbols:   474
+  CStrings:  2418
Symbols:
+ _GetXNUCountersSysctlNames
+ _GetXNUStatCountersHostInfo64Names
CStrings:
+ "OpenBandExtraSensesOnLastWLPerMode"
+ "OpenBandExtraSensesPerMode"
+ "OpenBandReadsPerMode"
+ "debugDataCompressionFailed"
+ "debugDataDumpSuccess"
+ "debugDataGetFail"
+ "debugDataGetSuccess"
+ "debugDataRequestDump"
+ "ldefragActivations"
+ "ldefragDroppedSegs"
+ "ldefragFromAlignedFlows"
+ "ldefragHostTotalReadSectors"
+ "ldefragHostTrimSectors"
+ "ldefragOnlyTrollingOnChoke"
+ "ldefragTrollChains"
+ "ldefragTrollFragments"
+ "ldefragTrollSectors"
+ "ldefragTrollTotalReadSectors"
+ "ldefragTrollTrimSectors"
+ "sanitizeDone"
+ "sanitizeDoneTime"
+ "sanitizeFailed"
+ "sanitizeReject"
+ "sanitizeStart"
+ "sanitizeStartTime"
+ "sanitizeStatus"
+ "timer_read64_synced"
+ "vm.compressor.swapper.swapouts_darkwake"
+ "vm.compressor.swapper.swapouts_donate"
+ "vm.compressor.swapper.swapouts_freezer"
+ "vm.compressor.swapper.swapouts_pressure"
+ "vm.compressor.swapper.swapouts_scavenger"
```
