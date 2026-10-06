## HeartRateCoordinator

> `/System/Library/PrivateFrameworks/HeartRateCoordinator.framework/HeartRateCoordinator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x46b0` | `0x4a80` | **`+0x3d0`** |
| `__TEXT.__objc_methlist` | `0x81c` | `0x874` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x1190` | `0x11d8` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x44f` | `0x48d` | **`+0x3e`** |
| `__TEXT.__gcc_except_tab` | `0x2e0` | `0x30c` | **`+0x2c`** |
| `__DATA_CONST.__objc_selrefs` | `0x430` | `0x458` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x280` | `0x298` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x78` | `0x80` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xc8` | `0xcc` | **`+0x4`** |

### Other Changes

```diff

-39.0.0.0.0
+40.0.0.0.0

-  Functions: 151
-  Symbols:   417
-  CStrings:  37
+  Functions: 158
+  Symbols:   428
+  CStrings:  38
Symbols:
+ -[HRCHeartRateRequestor handleRecentHighConfidenceHeartRates:]
+ -[HRCHeartRateRequestor recentHighConfidenceHeartRatesRequested]
+ -[HRCHeartRateRequestor setRecentHighConfidenceHeartRatesRequested:]
+ -[HRCHeartRateRequestorXPCHelper handleRecentHighConfidenceHeartRates:]
+ -[HRCHeartRateRequestorXPCHelper requestRecentHighConfidenceHeartRates]
+ GCC_except_table11
+ GCC_except_table14
+ GCC_except_table22
+ GCC_except_table24
+ GCC_except_table25
+ GCC_except_table9
+ _OBJC_IVAR_$_HRCHeartRateRequestor._recentHighConfidenceHeartRatesRequested
+ ___62-[HRCHeartRateRequestor handleRecentHighConfidenceHeartRates:]_block_invoke
+ ___62-[HRCHeartRateRequestor handleRecentHighConfidenceHeartRates:]_block_invoke_2
+ ___82-[HRCHeartRateRequestor initWithDelegate:onQueue:connectionHelper:privacyMonitor:]_block_invoke_3
- GCC_except_table10
- GCC_except_table12
- GCC_except_table15
- GCC_except_table7
CStrings:
+ "handling recent high confidence heart rates in client process"
```
