## AudioServerDriver

> `/System/Library/PrivateFrameworks/AudioServerDriver.framework/AudioServerDriver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x280` | `0xbe0` | **`+0x960`** |
| `__DATA_DIRTY.__objc_data` | `0xdc0` | `0x460` | **`-0x960`** |
| `__TEXT.__oslogstring` | `0x2ef4` | `0x2f27` | **`+0x33`** |
| `__TEXT.__unwind_info` | `0x2558` | `0x2578` | **`+0x20`** |
| `__TEXT.__text` | `0x6bfbc` | `0x6bfcc` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x3f64` | `0x3f58` | **`-0xc`** |
| `__TEXT.__cstring` | `0x3f48` | `0x3f51` | **`+0x9`** |

### Other Changes

```diff

-1200.30.0.0.0
+1200.31.0.0.0

-  Functions: 2498
+  Functions: 2499

-  CStrings:  838
+  CStrings:  839
CStrings:
+ "!graphHelper || !*graphHelper"
+ "DSP graph not configured for prewarmInputDSPGraph\n"
- "prewarmInputDSPGraph"
```
