## DuetActivityScheduler

> `/System/Library/PrivateFrameworks/DuetActivityScheduler.framework/DuetActivityScheduler`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3efe4` | `0x3e758` | **`-0x88c`** |
| `__TEXT.__oslogstring` | `0x3306` | `0x31da` | **`-0x12c`** |
| `__AUTH_CONST.__objc_const` | `0x7f58` | `0x7ec8` | **`-0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x2960` | `0x28e8` | **`-0x78`** |
| `__TEXT.__objc_methlist` | `0x49e8` | `0x4988` | **`-0x60`** |
| `__AUTH.__objc_data` | `0x690` | `0x6e0` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x6e0` | `0x690` | **`-0x50`** |
| `__TEXT.__cstring` | `0x413c` | `0x40f2` | **`-0x4a`** |
| `__AUTH_CONST.__cfstring` | `0x5080` | `0x5060` | **`-0x20`** |
| `__AUTH_CONST.__const` | `0x3a0` | `0x380` | **`-0x20`** |
| `__DATA_CONST.__const` | `0xf30` | `0xf10` | **`-0x20`** |
| `__DATA.__bss` | `0xe8` | `0xf8` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0xc0` | `0xb0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x12f8` | `0x12e8` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x4a0` | `0x494` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x338` | `0x330` | **`-0x8`** |
| `__TEXT.__const` | `0x208` | `0x200` | **`-0x8`** |

### Other Changes

```diff

-2467.0.9.0.0
+2467.0.14.502.1

-  Functions: 1686
-  Symbols:   2844
-  CStrings:  989
+  Functions: 1674
+  Symbols:   2825
+  CStrings:  982
Symbols:
+ -[_DASPairedSystemContext usageThresholdForPriority:batteryLevel:isPluggedIn:shouldBypassApplicationUsage:]
+ GCC_except_table25
+ GCC_except_table33
- -[_DASPairedSystemContext appUsageRefreshTimer]
- -[_DASPairedSystemContext launchedAppCount]
- -[_DASPairedSystemContext remoteAppLaunchCount]
- -[_DASPairedSystemContext setAppUsageRefreshTimer:]
- -[_DASPairedSystemContext setLaunchedAppCount:]
- -[_DASPairedSystemContext setRemoteAppLaunchCount:]
- -[_DASPairedSystemContext updateAppUsageHistory]
- -[_DASPairedSystemContext usageLikelihoodForApplication:]
- -[_DASPairedSystemContext usageThresholdForPriority:batteryLevel:isPluggedIn:]
- GCC_except_table20
- GCC_except_table27
- GCC_except_table39
- GCC_except_table40
- _OBJC_CLASS_$_BMPublisherOptions
- _OBJC_IVAR_$__DASPairedSystemContext._appUsageRefreshTimer
- _OBJC_IVAR_$__DASPairedSystemContext._launchedAppCount
- _OBJC_IVAR_$__DASPairedSystemContext._remoteAppLaunchCount
- ___129-[_DASPairedSystemContext initWithClientIdentifier:context:callbackQueue:systemConditionChangeCallback:trafficCancelationHander:]_block_invoke_2
- ___48-[_DASPairedSystemContext updateAppUsageHistory]_block_invoke
- ___53-[_DASPairedSystemContext setPairedDeviceIdentifier:]_block_invoke
- ___block_descriptor_32_e32_"NSString"16?0"BMStoreEvent"8l
- _dispatch_block_create_with_qos_class
CStrings:
+ "(6"
- "(9"
- "@\"NSString\"16@?0@\"BMStoreEvent\"8"
- "CHECKING: %@, Priority=%@, App Usage: %lf, Watch Battery Level: %d, Watch Plugin Status: %u"
- "DENIED: %@, Priority=%@, App Usage: %lf, Watch Battery Level: %d, Watch Plugin Status: %u"
- "DuetActivitySchedulerPairedSystemContext"
- "Failed to get remote devices: %@"
- "Remote results for app usage history: %@"
- "Selected device (%@) for app usage history."
```
