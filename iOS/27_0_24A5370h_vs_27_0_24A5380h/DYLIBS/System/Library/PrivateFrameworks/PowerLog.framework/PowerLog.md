## PowerLog

> `/System/Library/PrivateFrameworks/PowerLog.framework/PowerLog`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1eac0` | `0x1ee98` | **`+0x3d8`** |
| `__AUTH.__objc_data` | `0x410` | `0x550` | **`+0x140`** |
| `__DATA_DIRTY.__objc_data` | `0x230` | `0xf0` | **`-0x140`** |
| `__AUTH_CONST.__objc_const` | `0x2238` | `0x22c8` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x2920` | `0x2980` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x14ac` | `0x150c` | **`+0x60`** |
| `__TEXT.__cstring` | `0x236f` | `0x23b6` | **`+0x47`** |
| `__DATA_CONST.__objc_selrefs` | `0x1048` | `0x1088` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x3a03` | `0x3a2d` | **`+0x2a`** |
| `__DATA_CONST.__const` | `0x660` | `0x688` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x1b8` | `0x1c8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1a8` | `0x1b4` | **`+0xc`** |
| `__DATA_DIRTY.__bss` | `0x80` | `0x88` | **`+0x8`** |

### Other Changes

```diff

-3486.0.21.502.1
+3486.0.46.502.1

-  Functions: 825
-  Symbols:   1215
-  CStrings:  681
+  Functions: 836
+  Symbols:   1230
+  CStrings:  686
Symbols:
+ -[PLClientLogger hasSeenFirstDrop]
+ -[PLClientLogger hourlyDropCount]
+ -[PLClientLogger hourlyWindowStart]
+ -[PLClientLogger sendHourlyDropSummaryWithTotalDrops:processName:]
+ -[PLClientLogger setHasSeenFirstDrop:]
+ -[PLClientLogger setHourlyDropCount:]
+ -[PLClientLogger setHourlyWindowStart:]
+ -[PLClientLogger trackHourlyClientDrops]
+ GCC_except_table53
+ GCC_except_table54
+ _OBJC_IVAR_$_PLClientLogger._hasSeenFirstDrop
+ _OBJC_IVAR_$_PLClientLogger._hourlyDropCount
+ _OBJC_IVAR_$_PLClientLogger._hourlyWindowStart
+ ___40-[PLClientLogger trackHourlyClientDrops]_block_invoke
+ ___40-[PLClientLogger trackHourlyClientDrops]_block_invoke_2
+ ___block_descriptor_52_e8_32s40s_e5_v8?0ls32l8s40l8
+ _isHourlyDropTrackingEnabled
- GCC_except_table49
- GCC_except_table50
CStrings:
+ "ClientDroppedEvents: sending payload:  %@"
+ "Count"
+ "Process"
+ "XPCMetrics::ClientDroppedEvents"
+ "xpc_hourly_drop_tracking"
```
