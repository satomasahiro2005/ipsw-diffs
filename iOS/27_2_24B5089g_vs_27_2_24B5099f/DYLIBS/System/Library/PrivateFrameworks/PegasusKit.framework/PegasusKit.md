## PegasusKit

> `/System/Library/PrivateFrameworks/PegasusKit.framework/PegasusKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1067cc` | `0x107e74` | **`+0x16a8`** |
| `__TEXT.__oslogstring` | `0x32ef` | `0x34af` | **`+0x1c0`** |
| `__DATA.__bss` | `0x2aa0` | `0x2ba0` | **`+0x100`** |
| `__TEXT.__swift5_reflstr` | `0x263d` | `0x270d` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x30b1` | `0x3121` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x20f4` | `0x2160` | **`+0x6c`** |
| `__TEXT.__const` | `0x69a0` | `0x69e0` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x7118` | `0x7140` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x4324` | `0x433c` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x31e8` | `0x3200` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x320a` | `0x3218` | **`+0xe`** |
| `__AUTH_CONST.__auth_got` | `0x1d30` | `0x1d38` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x2a0` | `0x2a8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x53c` | `0x540` | **`+0x4`** |

### Other Changes

```diff

-3605.23.1.1.1
+3605.26.1.0.0

-  Functions: 5930
-  Symbols:   1703
-  CStrings:  600
+  Functions: 5952
+  Symbols:   1713
+  CStrings:  609
Symbols:
+ _OUTLINED_FUNCTION_427
+ _OUTLINED_FUNCTION_428
+ _OUTLINED_FUNCTION_429
+ _OUTLINED_FUNCTION_430
+ _OUTLINED_FUNCTION_431
+ _OUTLINED_FUNCTION_432
+ _OUTLINED_FUNCTION_433
+ _OUTLINED_FUNCTION_434
+ _OUTLINED_FUNCTION_435
+ ___swift_get_extra_inhabitant_index.403Tm
+ ___swift_store_extra_inhabitant_index.404Tm
+ _symbolic _____SgXwz_Xx 10PegasusKit0A27ProxyForSAMIntelligenceFlowC
- ___swift_get_extra_inhabitant_index.402Tm
- ___swift_store_extra_inhabitant_index.403Tm
CStrings:
+ "%.3fs left in window"
+ "[RequestThrottle] %{public}s, isQualified: %{bool,public}d"
+ "[RequestThrottle] backoff window elapsed after %{public}ld failure(s), allowing probe request"
+ "[RequestThrottle] context: %{public}s"
+ "[RequestThrottle] record a failure, backoff: %{public}s, failedCount: %{public}ld"
+ "[RequestThrottle] record a success, closed backoff"
+ "[RequestThrottle] request rejected, still in backoff window: %{public}s"
+ "pegasusKitSAMPrewarm"
+ "window elapsed %.3fs ago, next request probes"
```
