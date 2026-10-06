## PowerlogLiteOperators

> `/System/Library/PrivateFrameworks/PowerlogLiteOperators.framework/PowerlogLiteOperators`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4daef0` | `0x4dcf2c` | **`+0x203c`** |
| `__TEXT.__cstring` | `0x5ee66` | `0x5efd9` | **`+0x173`** |
| `__TEXT.__oslogstring` | `0x158fe` | `0x15a25` | **`+0x127`** |
| `__AUTH_CONST.__cfstring` | `0x75aa0` | `0x75ba0` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0x37308` | `0x373c8` | **`+0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x14768` | `0x14818` | **`+0xb0`** |
| `__TEXT.__objc_methlist` | `0x2e4f4` | `0x2e594` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x2cf0` | `0x2d5c` | **`+0x6c`** |
| `__DATA_CONST.__const` | `0x9440` | `0x9478` | **`+0x38`** |
| `__TEXT.__const` | `0x2ce0` | `0x2cc0` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x1b18` | `0x1b30` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x16670` | `0x16680` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1950` | `0x1948` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x1ec8` | `0x1ed0` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0x46e0` | `0x46e8` | **`+0x8`** |
| `__DATA_DIRTY.__objc_ivar` | `0x1308` | `0x1310` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x8240` | `0x8248` | **`+0x8`** |

### Other Changes

```diff

-3486.0.81.502.4
+3486.2.4.0.0

+  - /System/Library/Frameworks/_LocationEssentials.framework/_LocationEssentials

+  - /System/Library/PrivateFrameworks/AttentionAwareness.framework/AttentionAwareness

-  Functions: 19458
-  Symbols:   25324
-  CStrings:  19471
+  Functions: 19473
+  Symbols:   25344
+  CStrings:  19489
Symbols:
+ +[PLBatteryAgent entryEventPointDefinitionBatteryShutdownPack]
+ +[PLDisplayAgent _entryEventBackwardDefinitionAPLStatsWithLogSelector:]
+ -[KernelTaskMonitorStats cpu_energy_m]
+ -[KernelTaskMonitorStats setCpu_energy_m:]
+ -[PLBatteryAgent logBatteryShutdownToCA:forBatteryPack:]
+ -[PLBatteryAgent logEventPointBatteryShutdownWithRawData:packID:systemShutdownData:]
+ -[PLSMCMetricsAgent lastAccumlatedSampleCA]
+ -[PLSMCMetricsAgent setLastAccumlatedSampleCA:]
+ -[PLSpringBoardAgent attentionAwarenessClient]
+ -[PLSpringBoardAgent lastUserEventMediaTime]
+ -[PLSpringBoardAgent setAttentionAwarenessClient:]
+ -[PLSpringBoardAgent setLastUserEventMediaTime:]
+ -[PLSpringBoardAgent startAttentionAwarenessClient]
+ -[PLSpringBoardAgent stopAttentionAwarenessClient]
+ GCC_except_table136
+ GCC_except_table140
+ GCC_except_table158
+ GCC_except_table175
+ GCC_except_table187
+ GCC_except_table193
+ GCC_except_table248
+ GCC_except_table257
+ GCC_except_table260
+ GCC_except_table262
+ GCC_except_table271
+ GCC_except_table278
+ GCC_except_table283
+ GCC_except_table325
+ GCC_except_table328
+ GCC_except_table332
+ _OBJC_CLASS_$_AWAttentionAwarenessClient
+ _OBJC_CLASS_$_AWAttentionAwarenessConfiguration
+ _OBJC_IVAR_$_KernelTaskMonitorStats._cpu_energy_m
+ _OBJC_IVAR_$_PLSpringBoardAgent._lastUserEventMediaTime
+ ___51-[PLSpringBoardAgent startAttentionAwarenessClient]_block_invoke
+ ___56-[PLBatteryAgent logBatteryShutdownToCA:forBatteryPack:]_block_invoke
+ ___84-[PLBatteryAgent logEventPointBatteryShutdownWithRawData:packID:systemShutdownData:]_block_invoke
+ ___84-[PLBatteryAgent logEventPointBatteryShutdownWithRawData:packID:systemShutdownData:]_block_invoke_2
+ ___block_descriptor_40_e8_32w_e26_v16?0"AWAttentionEvent"8lw32l8
+ _kCLLocationAccuracyReduced
+ _kPLBatteryAgentEventPointNameBatteryShutdownPack0
+ _kPLBatteryAgentStringLastShutdownSystemTimestamp0
+ _kPLBatteryAgentStringLastShutdownSystemTimestampSystem
- -[PLBatteryAgent logBatteryShutdownToCA:]
- GCC_except_table117
- GCC_except_table135
- GCC_except_table139
- GCC_except_table157
- GCC_except_table174
- GCC_except_table186
- GCC_except_table192
- GCC_except_table247
- GCC_except_table256
- GCC_except_table259
- GCC_except_table261
- GCC_except_table269
- GCC_except_table275
- GCC_except_table281
- GCC_except_table323
- GCC_except_table326
- GCC_except_table330
- _BKSHIDServicesLastUserEventTime
- ___41-[PLBatteryAgent logBatteryShutdownToCA:]_block_invoke
- ___46-[PLBatteryAgent logEventPointBatteryShutdown]_block_invoke
- ___46-[PLBatteryAgent logEventPointBatteryShutdown]_block_invoke_2
- _kPLBatteryAgentStringLastShutdownSystemTimestamp
CStrings:
+ "-[PLBatteryAgent logEventPointBatteryShutdownWithRawData:packID:systemShutdownData:]"
+ "-[PLSpringBoardAgent startAttentionAwarenessClient]"
+ "AppleSmartBatteryPack"
+ "AttentionAwareness unavailable on this image; autolock energy will use fallback timing"
+ "BatteryShutdown: Failed to get AppleSmartBatteryPack data with result=%x"
+ "BatteryShutdown: log entry for pack=%@"
+ "BatteryShutdownPack0"
+ "CPUEnergyM"
+ "Failed to configure AttentionAwareness client: %{public}@"
+ "Failed to resume AttentionAwareness client: %{public}@"
+ "Failed to retrieve power sources list handle."
+ "LastShutdownSystemTimestampSystem"
+ "PDEB"
+ "PDTP"
+ "Unable to retrieve %s"
+ "com.apple.powerlog.autolock"
+ "gcSlowInlineWritesMigration"
+ "gcSlowInlineWritesTotal"
+ "hw.perflevel%d.physicalcpu"
+ "numMcpuCores"
+ "skipping PE mitigated via BackgroundQoSDisabled"
+ "v16@?0@\"AWAttentionEvent\"8"
- "-[PLBatteryAgent logEventPointBatteryShutdown]"
- "Unable to retrieve hw.perflevel%d.physicalcpu"
- "hw.perflevel0.physicalcpu"
- "hw.perflevel1.physicalcpu"
```
