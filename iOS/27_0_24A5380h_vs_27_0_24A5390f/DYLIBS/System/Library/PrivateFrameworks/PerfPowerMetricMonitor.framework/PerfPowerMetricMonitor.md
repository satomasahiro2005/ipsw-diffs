## PerfPowerMetricMonitor

> `/System/Library/PrivateFrameworks/PerfPowerMetricMonitor.framework/PerfPowerMetricMonitor`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18680` | `0x19d90` | **`+0x1710`** |
| `__AUTH_CONST.__objc_const` | `0x2308` | `0x2898` | **`+0x590`** |
| `__TEXT.__objc_methlist` | `0x15a4` | `0x187c` | **`+0x2d8`** |
| `__TEXT.__cstring` | `0x1157` | `0x1308` | **`+0x1b1`** |
| `__AUTH_CONST.__cfstring` | `0x14a0` | `0x1640` | **`+0x1a0`** |
| `__TEXT.__ustring` | `0x6c0` | `0x77e` | **`+0xbe`** |
| `__AUTH.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x680` | `0x710` | **`+0x90`** |
| `__TEXT.__gcc_except_tab` | `0x928` | `0x998` | **`+0x70`** |
| `__DATA_CONST.__objc_arraydata` | `0x280` | `0x2e8` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0xee0` | `0xf40` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x1be2` | `0x1c3b` | **`+0x59`** |
| `__DATA.__objc_ivar` | `0x22c` | `0x280` | **`+0x54`** |
| `__TEXT.__unwind_info` | `0x4c0` | `0x510` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x1a0` | `0x1c0` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x30` | `0x48` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xf0` | `0x108` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x58` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x40` | `0x50` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x58` | `0x68` | **`+0x10`** |

### Other Changes

```diff

-3486.0.46.502.1
+3486.0.81.502.4

-  Functions: 609
-  Symbols:   978
-  CStrings:  317
+  Functions: 674
+  Symbols:   1095
+  CStrings:  334
Symbols:
+ +[PPSLiteMetricCollection extractLiteMetrics:]
+ +[PPSLiteMetricCollection supportsSecureCoding]
+ +[PPSLiteProcessMetricCollection _metricSamplePropertyKeys]
+ +[PPSLiteProcessMetricCollection supportsSecureCoding]
+ -[PPSLiteMetricCollection .cxx_destruct]
+ -[PPSLiteMetricCollection description]
+ -[PPSLiteMetricCollection encodeWithCoder:]
+ -[PPSLiteMetricCollection initWithCoder:]
+ -[PPSLiteMetricCollection init]
+ -[PPSLiteMetricCollection processMetrics]
+ -[PPSLiteMetricCollection setProcessMetrics:]
+ -[PPSLiteProcessMetricCollection .cxx_destruct]
+ -[PPSLiteProcessMetricCollection aneEnergy]
+ -[PPSLiteProcessMetricCollection aneTime]
+ -[PPSLiteProcessMetricCollection bundleID]
+ -[PPSLiteProcessMetricCollection bytesRead]
+ -[PPSLiteProcessMetricCollection bytesWritten]
+ -[PPSLiteProcessMetricCollection coalitionID]
+ -[PPSLiteProcessMetricCollection cpuEnergyWithVouchers]
+ -[PPSLiteProcessMetricCollection cpuEnergyWithoutVouchers]
+ -[PPSLiteProcessMetricCollection cpuInstructions]
+ -[PPSLiteProcessMetricCollection cpuPInstructions]
+ -[PPSLiteProcessMetricCollection cpuSecondsWithVouchers]
+ -[PPSLiteProcessMetricCollection cpuSecondsWithoutVouchers]
+ -[PPSLiteProcessMetricCollection description]
+ -[PPSLiteProcessMetricCollection encodeWithCoder:]
+ -[PPSLiteProcessMetricCollection gpuEnergyWithVouchers]
+ -[PPSLiteProcessMetricCollection gpuEnergyWithoutVouchers]
+ -[PPSLiteProcessMetricCollection gpuTime]
+ -[PPSLiteProcessMetricCollection initWithCoder:]
+ -[PPSLiteProcessMetricCollection initWithProcessMetricCollection:]
+ -[PPSLiteProcessMetricCollection pid]
+ -[PPSLiteProcessMetricCollection processActive]
+ -[PPSLiteProcessMetricCollection processName]
+ -[PPSLiteProcessMetricCollection sampleTime]
+ -[PPSLiteProcessMetricCollection setAneEnergy:]
+ -[PPSLiteProcessMetricCollection setAneTime:]
+ -[PPSLiteProcessMetricCollection setBundleID:]
+ -[PPSLiteProcessMetricCollection setBytesRead:]
+ -[PPSLiteProcessMetricCollection setBytesWritten:]
+ -[PPSLiteProcessMetricCollection setCoalitionID:]
+ -[PPSLiteProcessMetricCollection setCpuEnergyWithVouchers:]
+ -[PPSLiteProcessMetricCollection setCpuEnergyWithoutVouchers:]
+ -[PPSLiteProcessMetricCollection setCpuInstructions:]
+ -[PPSLiteProcessMetricCollection setCpuPInstructions:]
+ -[PPSLiteProcessMetricCollection setCpuSecondsWithVouchers:]
+ -[PPSLiteProcessMetricCollection setCpuSecondsWithoutVouchers:]
+ -[PPSLiteProcessMetricCollection setGpuEnergyWithVouchers:]
+ -[PPSLiteProcessMetricCollection setGpuEnergyWithoutVouchers:]
+ -[PPSLiteProcessMetricCollection setGpuTime:]
+ -[PPSLiteProcessMetricCollection setPid:]
+ -[PPSLiteProcessMetricCollection setProcessActive:]
+ -[PPSLiteProcessMetricCollection setProcessName:]
+ -[PPSLiteProcessMetricCollection setSampleTime:]
+ -[PPSMetricMonitor collectLiteMetricsOnSnapshot:]
+ -[PPSMetricMonitorConfiguration liteMode]
+ -[PPSMetricMonitorConfiguration setLiteMode:]
+ -[PPSMetricMonitorService _emitSystemMetricsSignpost:beginMct:endMct:deltaTime:]
+ GCC_except_table111
+ GCC_except_table33
+ GCC_except_table44
+ GCC_except_table47
+ GCC_except_table49
+ GCC_except_table54
+ GCC_except_table65
+ GCC_except_table70
+ GCC_except_table74
+ GCC_except_table78
+ GCC_except_table89
+ _OBJC_CLASS_$_NSMutableString
+ _OBJC_CLASS_$_PPSLiteMetricCollection
+ _OBJC_CLASS_$_PPSLiteProcessMetricCollection
+ _OBJC_IVAR_$_PPSLiteMetricCollection._processMetrics
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._aneEnergy
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._aneTime
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._bundleID
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._bytesRead
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._bytesWritten
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._coalitionID
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._cpuEnergyWithVouchers
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._cpuEnergyWithoutVouchers
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._cpuInstructions
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._cpuPInstructions
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._cpuSecondsWithVouchers
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._cpuSecondsWithoutVouchers
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._gpuEnergyWithVouchers
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._gpuEnergyWithoutVouchers
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._gpuTime
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._pid
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._processActive
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._processName
+ _OBJC_IVAR_$_PPSLiteProcessMetricCollection._sampleTime
+ _OBJC_IVAR_$_PPSMetricMonitorConfiguration._liteMode
+ _OBJC_METACLASS_$_PPSLiteMetricCollection
+ _OBJC_METACLASS_$_PPSLiteProcessMetricCollection
+ __OBJC_$_CLASS_METHODS_PPSLiteMetricCollection
+ __OBJC_$_CLASS_METHODS_PPSLiteProcessMetricCollection
+ __OBJC_$_CLASS_PROP_LIST_PPSLiteMetricCollection
+ __OBJC_$_CLASS_PROP_LIST_PPSLiteProcessMetricCollection
+ __OBJC_$_INSTANCE_METHODS_PPSLiteMetricCollection
+ __OBJC_$_INSTANCE_METHODS_PPSLiteProcessMetricCollection
+ __OBJC_$_INSTANCE_VARIABLES_PPSLiteMetricCollection
+ __OBJC_$_INSTANCE_VARIABLES_PPSLiteProcessMetricCollection
+ __OBJC_$_PROP_LIST_PPSLiteMetricCollection
+ __OBJC_$_PROP_LIST_PPSLiteProcessMetricCollection
+ __OBJC_CLASS_PROTOCOLS_$_PPSLiteMetricCollection
+ __OBJC_CLASS_PROTOCOLS_$_PPSLiteProcessMetricCollection
+ __OBJC_CLASS_RO_$_PPSLiteMetricCollection
+ __OBJC_CLASS_RO_$_PPSLiteProcessMetricCollection
+ __OBJC_METACLASS_RO_$_PPSLiteMetricCollection
+ __OBJC_METACLASS_RO_$_PPSLiteProcessMetricCollection
+ ___38-[PPSLiteMetricCollection description]_block_invoke
+ ___46+[PPSLiteMetricCollection extractLiteMetrics:]_block_invoke
+ ___49-[PPSMetricMonitor collectLiteMetricsOnSnapshot:]_block_invoke
+ ___49-[PPSMetricMonitor collectLiteMetricsOnSnapshot:]_block_invoke_2
+ ___59+[PPSLiteProcessMetricCollection _metricSamplePropertyKeys]_block_invoke
+ ___block_descriptor_40_e8_32s_e53_v32?0"NSNumber"8"PPSProcessMetricCollection"16^B24ls32l8
+ ___block_descriptor_40_e8_32s_e57_v32?0"NSNumber"8"PPSLiteProcessMetricCollection"16^B24ls32l8
+ _kPPSLiteBundleIDKey
+ _kPPSLiteCoalitionIDKey
+ _kPPSLitePidKey
+ _kPPSLiteProcessActiveKey
+ _kPPSLiteProcessMetricsKey
+ _kPPSLiteProcessNameKey
+ _kPPSLiteSampleTimeKey
+ _kPPSMMConfigLiteMode
- GCC_except_table110
- GCC_except_table41
- GCC_except_table46
- GCC_except_table51
- GCC_except_table64
- GCC_except_table69
- GCC_except_table73
- GCC_except_table77
- GCC_except_table88
CStrings:
+ "  %@\n"
+ ")"
+ "Cannot call collectMetricsOnSnapshot: in lite mode — use collectLiteMetricsOnSnapshot: instead"
+ "Cannot collect lite metrics when interrupted"
+ "Cannot collect lite metrics when not monitoring"
+ "PPSLiteMetricCollection(\n"
+ "PPSLiteProcessMetricCollection(pid=%d name=%@ cpuEnergyWithVouchers=%@ gpuEnergyWithVouchers=%@ cpuSeconds=%@ aneEnergy=%@ bytesRead=%@ cpuInstructions=%@ sampleTime=%@)"
+ "PPSMetricMonitorConfig(mode: %ld updateInterval: %f updateDelegate: %d includeBackBoardUsage: %d isHeadless: %d emitTracingSignposts: %d emitSignposts: %d liteMode: %d))"
+ "bundleID"
+ "coalitionID"
+ "collectLiteMetricsOnSnapshot error %@"
+ "collecting lite snapshot"
+ "lite metrics collected %@"
+ "liteMode"
+ "pid"
+ "processActive"
+ "processName"
+ "v32@?0@\"NSNumber\"8@\"PPSLiteProcessMetricCollection\"16^B24"
- "PPSMetricMonitorConfig(mode: %ld updateInterval: %f updateDelegate: %d includeBackBoardUsage: %d isHeadless: %d emitTracingSignposts: %d emitSignposts: %d))"
```
