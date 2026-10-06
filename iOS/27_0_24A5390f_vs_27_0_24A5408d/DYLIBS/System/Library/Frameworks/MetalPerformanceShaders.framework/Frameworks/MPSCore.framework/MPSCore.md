## MPSCore

> `/System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSCore.framework/MPSCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x96204` | `0x962b8` | **`+0xb4`** |
| `__AUTH_CONST.__const` | `0x5f10` | `0x5f30` | **`+0x20`** |
| `__TEXT.__cstring` | `0xa611` | `0xa62c` | **`+0x1b`** |
| `__DATA_DIRTY.__bss` | `0x228` | `0x230` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1e30` | `0x1e38` | **`+0x8`** |

### Other Changes

```diff

-130.0.15.0.0
+130.0.19.0.0

-  Functions: 1724
-  Symbols:   799
-  CStrings:  878
+  Functions: 1726
+  Symbols:   800
+  CStrings:  879
Symbols:
+ _MPSIsPerfTestCmdSignpostEnabled
CStrings:
+ "130.0.19"
+ "MPS_PERF_TEST_CMD_SIGNPOST"
- "130.0.15"
```
