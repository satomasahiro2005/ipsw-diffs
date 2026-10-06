## libBNNS.dylib

> `/System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libBNNS.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x113f1d4` | `0x114095c` | **`+0x1788`** |
| `__TEXT.__cstring` | `0x5fc50` | `0x5fcd4` | **`+0x84`** |
| `__TEXT.__unwind_info` | `0x1c150` | `0x1c180` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x2e95c` | `0x2e960` | **`+0x4`** |

### Other Changes

```diff

-2212.0.4.0.0
+2212.0.8.0.0

-  Functions: 39486
+  Functions: 39492

-  CStrings:  8722
+  CStrings:  8723
CStrings:
+ "BasicNeuralNetworkSubroutines-2212.0.8~25"
+ "ConvertInvokeOp: invoke op passes a token/state argument to its callee, but BNNS only supports tensor arguments in callee functions"
- "BasicNeuralNetworkSubroutines-2212.0.4~20"
```
