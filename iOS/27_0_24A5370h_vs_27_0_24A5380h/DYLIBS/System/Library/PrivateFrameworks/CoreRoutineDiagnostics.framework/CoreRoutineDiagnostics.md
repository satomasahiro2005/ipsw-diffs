## CoreRoutineDiagnostics

> `/System/Library/PrivateFrameworks/CoreRoutineDiagnostics.framework/CoreRoutineDiagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xee74` | `0xe808` | **`-0x66c`** |
| `__TEXT.__oslogstring` | `0x1c9a` | `0x1b2c` | **`-0x16e`** |
| `__AUTH_CONST.__objc_const` | `0xfc8` | `0xed8` | **`-0xf0`** |
| `__AUTH.__objc_data` | `0xf0` | `0x50` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x280` | `0x320` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x1940` | `0x18c0` | **`-0x80`** |
| `__TEXT.__cstring` | `0x17c7` | `0x1768` | **`-0x5f`** |
| `__TEXT.__objc_methlist` | `0xb14` | `0xabc` | **`-0x58`** |
| `__DATA_CONST.__const` | `0x5d8` | `0x618` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x8f8` | `0x8d0` | **`-0x28`** |
| `__TEXT.__gcc_except_tab` | `0x3cc` | `0x3b4` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0xac` | `0x98` | **`-0x14`** |
| `__TEXT.__unwind_info` | `0x410` | `0x420` | **`+0x10`** |
| `__TEXT.__const` | `0x170` | `0x168` | **`-0x8`** |

### Other Changes

```diff

-1114.0.0.0.0
+1117.0.0.0.0

-  Functions: 273
-  Symbols:   667
-  CStrings:  370
+  Functions: 268
+  Symbols:   653
+  CStrings:  359
Symbols:
+ +[RTRadarUtilities truncateRadarTitle:]
+ -[RTBugCaptureManager isRbcAllowed]
+ -[RTTransactionManager isRTTransactionDiagnosticMode]
+ -[RTTransactionManager isTransactionDiagnosticsSampled]
+ -[RTTransactionManager setTransactionDiagnosticsSampled:]
+ -[RTTransactionManager transactionDiagnosticsSampled]
+ GCC_except_table10
+ GCC_except_table22
+ GCC_except_table26
+ GCC_except_table39
+ GCC_except_table41
+ GCC_except_table5
+ GCC_except_table7
+ _OBJC_IVAR_$_RTTransactionManager._transactionDiagnosticsSampled
+ ___53-[RTTransactionManager isRTTransactionDiagnosticMode]_block_invoke
+ ___55-[RTTransactionManager isTransactionDiagnosticsSampled]_block_invoke
+ ___57-[RTTransactionManager setTransactionDiagnosticsSampled:]_block_invoke
+ ___block_descriptor_41_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_48_e8_32s40r_e5_v8?0lr40l8s32l8
+ _dispatch_sync
- +[RTTransaction stringFromCpuMeasurementMode:]
- -[RTTransaction computeCpuPercentage]
- -[RTTransactionProfileData cpuMeasurementMode]
- -[RTTransactionProfileData endCpuSystemTime]
- -[RTTransactionProfileData endCpuUserTime]
- -[RTTransactionProfileData setCpuMeasurementMode:]
- -[RTTransactionProfileData setEndCpuSystemTime:]
- -[RTTransactionProfileData setEndCpuUserTime:]
- -[RTTransactionProfileData setStartCpuSystemTime:]
- -[RTTransactionProfileData setStartCpuUserTime:]
- -[RTTransactionProfileData setTransactionThread:]
- -[RTTransactionProfileData startCpuSystemTime]
- -[RTTransactionProfileData startCpuUserTime]
- -[RTTransactionProfileData transactionThread]
- GCC_except_table21
- GCC_except_table25
- GCC_except_table3
- GCC_except_table38
- GCC_except_table40
- GCC_except_table8
- _OBJC_IVAR_$_RTTransactionProfileData._cpuMeasurementMode
- _OBJC_IVAR_$_RTTransactionProfileData._endCpuSystemTime
- _OBJC_IVAR_$_RTTransactionProfileData._endCpuUserTime
- _OBJC_IVAR_$_RTTransactionProfileData._startCpuSystemTime
- _OBJC_IVAR_$_RTTransactionProfileData._startCpuUserTime
- _OBJC_IVAR_$_RTTransactionProfileData._transactionThread
- ___error
- _getrusage
- _kRTTransactionMetricsKeyCpuMeasurementMode
- _kRTTransactionMetricsKeyCpuPercentage
- _mach_error_string
- _mach_thread_self
- _strerror
- _thread_info
CStrings:
+ "%@, %@, truncating radar title to %lu characters (originally %lu characters)"
+ "..."
+ "RTTransactionProfileData: startDate, %@, endDate, %@, startMemory, %.2fMB, endMemory, %.2fMB, peakMemory, %.2fMB, signpostId, %llu, bugCaptureTriggered, %@"
- "All CPU measurements failed for %@"
- "Failed to get resource usage for %@, %s"
- "Invalid CPU measurement for %@: cpuTime, %.6fs (start=%.6fs, end=%.6fs), measurementMode, %@"
- "Process-wide end measurement failed for %@: %s"
- "ProcessWide"
- "Profiling completed for %@, mode, %@"
- "Profiling started for %@, mode, %@"
- "RTTransactionProfileData: startDate, %@, endDate, %@, startMemory, %.2fMB, endMemory, %.2fMB, peakMemory, %.2fMB, cpuMeasurementMode, %@, signpostId, %llu, bugCaptureTriggered, %@"
- "Thread-specific end measurement failed for %@: %s, falling back to process-wide"
- "Thread-specific measurement failed for %@, falling back to process-wide, %s"
- "ThreadSpecific"
- "Unknown(0x%lx)"
- "cpuMeasurementMode"
- "cpuPercentage"
```
