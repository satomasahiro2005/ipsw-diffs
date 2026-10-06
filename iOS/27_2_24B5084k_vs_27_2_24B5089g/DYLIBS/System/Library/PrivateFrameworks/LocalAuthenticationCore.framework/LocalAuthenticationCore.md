## LocalAuthenticationCore

> `/System/Library/PrivateFrameworks/LocalAuthenticationCore.framework/LocalAuthenticationCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x1938` | `0x9398` | **`+0x7a60`** |
| `__AUTH.__objc_data` | `0x7730` | `—` | **`-0x7730`** |
| `__DATA_DIRTY.__objc_data` | `0xe38` | `0x8568` | **`+0x7730`** |
| `__DATA.__data` | `0x7798` | `0x2280` | **`-0x5518`** |
| `__AUTH.__data` | `0x2558` | `—` | **`-0x2558`** |
| `__TEXT.__text` | `0x196e28` | `0x196ec4` | **`+0x9c`** |
| `__DATA.__common` | `0x38` | `0x58` | **`+0x20`** |
| `__DATA_DIRTY.__common` | `0x80` | `0x60` | **`-0x20`** |
| `__TEXT.__oslogstring` | `0xb0f5` | `0xb115` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x218` | `0x208` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0xd4b0` | `0xd4c0` | **`+0x10`** |

### Other Changes

```diff

-2319.40.29.0.0
+2319.40.35.0.1

-  Functions: 10929
-  Symbols:   22035
-  CStrings:  3132
+  Functions: 10930
+  Symbols:   22036
+  CStrings:  3133
Symbols:
+ -[LACNWPathMonitorAdapter dealloc]
+ _OBJC_IVAR_$_LACNWPathMonitorAdapter._isForwarding
- _OBJC_IVAR_$_LACNWPathMonitorAdapter._isMonitoring
Functions:
~ -[LACFlags featureFlagDimpleKeySentinelEnabled] : 140 -> 176
+ -[LACNWPathMonitorAdapter dealloc]
~ -[LACNWPathMonitorAdapter startMonitoringOnQueue:] : 1380 -> 1444
~ -[LACNWPathMonitorAdapter stopMonitoring] : 444 -> 168
~ -[LACNWPathMonitorAdapter _handlePathUpdate:] : 492 -> 504
CStrings:
+ "Paused network monitoring"
+ "Resumed network monitoring"
- "Stopped network monitoring"
```
