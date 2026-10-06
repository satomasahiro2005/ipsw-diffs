## AppPredictionInternal

> `/System/Library/PrivateFrameworks/AppPredictionInternal.framework/AppPredictionInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x48e08c` | `0x48e24c` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x59752` | `0x59672` | **`-0xe0`** |
| `__TEXT.__oslogstring` | `0x3b999` | `0x3ba49` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x3b240` | `0x3b1e0` | **`-0x60`** |
| `__TEXT.__gcc_except_tab` | `0xf4b4` | `0xf48c` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1bf50` | `0x1bf58` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xe578` | `0xe580` | **`+0x8`** |

### Other Changes

```diff

-664.0.2.1.0
+667.0.0.0.0

-  Functions: 25689
+  Functions: 25692

-  CStrings:  12395
+  CStrings:  12394
CStrings:
+ "ATXSetInput: dropping NaN value for input %lu (\"%@\")"
+ "ATXSetInput: dropping infinite value %f for input %lu (\"%@\")"
+ "ATXSetInput: dropping out-of-range input type %lu (max %lu)"
- "Input type must be less than _ATXScoreInputMax: %lu >= %lu"
- "Value must be a number. currently nan (input %lu, \"%@\")"
- "Value must be finite (input %lu, \"%@\")"
- "void ATXSetInput(ATXPredictionItem * _Nonnull, _ATXScoreInput, double)"
```
