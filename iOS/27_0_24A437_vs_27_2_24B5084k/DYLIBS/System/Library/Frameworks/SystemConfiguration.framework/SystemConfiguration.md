## SystemConfiguration

> `/System/Library/Frameworks/SystemConfiguration.framework/SystemConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x79828` | `0x79a58` | **`+0x230`** |
| `__TEXT.__oslogstring` | `0x58f5` | `0x5959` | **`+0x64`** |
| `__TEXT.__unwind_info` | `0xd28` | `0xd30` | **`+0x8`** |

### Other Changes

```diff

-1446.0.0.0.0
+1452.0.0.0.0

-  Functions: 1310
-  Symbols:   2372
-  CStrings:  2039
+  Functions: 1314
+  Symbols:   2371
+  CStrings:  2041
Symbols:
+ _OUTLINED_FUNCTION_5
- _____SCNetworkReachabilityRestartResolver_block_invoke_3
- _____SCNetworkReachabilitySetDispatchQueue_block_invoke_3
CStrings:
+ "%signoring DNS update from a superseded resolver"
+ "%signoring path update from a superseded evaluator"
```
