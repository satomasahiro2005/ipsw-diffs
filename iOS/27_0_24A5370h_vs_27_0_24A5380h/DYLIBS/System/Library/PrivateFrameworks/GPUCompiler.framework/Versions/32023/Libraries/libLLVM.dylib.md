## libLLVM.dylib

> `/System/Library/PrivateFrameworks/GPUCompiler.framework/Versions/32023/Libraries/libLLVM.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20376c0` | `0x202d264` | **`-0xa45c`** |
| `__DATA_DIRTY.__bss` | `0x43f90` | `0x46b60` | **`+0x2bd0`** |
| `__DATA.__bss` | `0x63f8` | `0x3e20` | **`-0x25d8`** |
| `__TEXT.__unwind_info` | `0x2c878` | `0x2d400` | **`+0xb88`** |
| `__TEXT.__cstring` | `0x118e82` | `0x11940a` | **`+0x588`** |
| `__AUTH_CONST.__const` | `0x66588` | `0x66660` | **`+0xd8`** |
| `__TEXT.__const` | `0x4191150` | `0x4191200` | **`+0xb0`** |
| `__DATA.__common` | `0x7c7` | `0x7b7` | **`-0x10`** |
| `__DATA_DIRTY.__common` | `0xc0eb` | `0xc0f3` | **`+0x8`** |

### Other Changes

```diff

-32023.917.2.0.0
+32023.920.0.0.0

-  Functions: 72687
-  Symbols:   21890
-  CStrings:  43486
+  Functions: 72762
+  Symbols:   21893
+  CStrings:  43511
Symbols:
+ __ZN4llvm25runInferAddressSpacesPassERNS_8FunctionERNS_9AAResultsERNS_15AssumptionCacheEPKNS_13DominatorTreeERNS_9MemorySSAEPKNS_19TargetTransformInfoEj
+ __ZN4llvm26isSafeToCastConstAddrSpaceEPKNS_8ConstantEjj
+ __ZN4llvm29runInferAddressSpacesAnalysisERNS_8FunctionERKNS_15SmallVectorImplIjEERNS_9CallGraphERNS_9AAResultsERNS_15AssumptionCacheEPKNS_13DominatorTreeERNS_9MemorySSAEPKNS_19TargetTransformInfoEj
+ __ZNK4llvm5Value33stripGenericAddrspacePointerCastsEj
- __ZN4llvm25runInferAddressSpacesPassERNS_8FunctionERNS_15AssumptionCacheEPKNS_13DominatorTreeERNS_9MemorySSAEPKNS_19TargetTransformInfoEj
CStrings:
+ "32023.920"
+ "Apple LLVM version 32023.920"
+ "Average loop iteration count used to weight instruction bonuses inside loops"
+ "Average number of recursion iterations to weight bonuses to (mutually) recursive functions"
+ "Don't specialize functions that have less than this threshold number of instructions"
+ "Ignore costs when specializing functions"
+ "LLVM version 32023.920"
+ "LLVM_SPECIALIZE_ADDRESS_SPACES_AVG_LOOP_COUNT"
+ "LLVM_SPECIALIZE_ADDRESS_SPACES_AVG_RECURSION_COUNT"
+ "LLVM_SPECIALIZE_ADDRESS_SPACES_CONCRETE_SPEEDUP_FACTOR"
+ "LLVM_SPECIALIZE_ADDRESS_SPACES_DEPENDENCY_COST_DIVISOR"
+ "LLVM_SPECIALIZE_ADDRESS_SPACES_MAX_NUM_CALL_BONUS"
+ "LLVM_SPECIALIZE_ADDRESS_SPACES_MAX_PER_FUNC"
+ "LLVM_SPECIALIZE_ADDRESS_SPACES_PHI_PREDICTION_FACTOR"
+ "LLVM_SPECIALIZE_ADDRESS_SPACES_SMALL_FN_THRESHOLD"
+ "LLVM_SPECIALIZE_ADDRESS_SPACES_SPECIALIZE_ALL"
+ "The divisor which we reduce the cost of specializations computed from the dataflow"
+ "The factor by which to reduce the bonus of uses of a phi/select for each generic incoming value"
+ "The factor which we assume builtin functions are sped up by replacing a generic argument with a concrete one"
+ "The maximum allowed number of specializations for a single function"
+ "The maximum bonus factor for a function that has many call sites"
+ "llvm-mc (based on LLVM 32023.920)"
+ "specialize-addrspaces-avg-iters-count"
+ "specialize-addrspaces-avg-recursion-count"
+ "specialize-addrspaces-calls-bonus"
+ "specialize-addrspaces-concrete-speedup"
+ "specialize-addrspaces-dependency-divisor"
+ "specialize-addrspaces-force-specialize"
+ "specialize-addrspaces-max-per-func"
+ "specialize-addrspaces-phi-prediction-factor"
+ "specialize-addrspaces-size-threshold"
- "32023.917.2"
- "Apple LLVM version 32023.917.2"
- "LLVM version 32023.917.2"
- "Set the max specialization-inference iterations to perform"
- "llvm-mc (based on LLVM 32023.917.2)"
- "specialize-addrspaces-max-iter"
```
