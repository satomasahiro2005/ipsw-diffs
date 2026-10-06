## GenerativeFunctionsInstrumentation

> `/System/Library/PrivateFrameworks/GenerativeFunctionsInstrumentation.framework/GenerativeFunctionsInstrumentation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a2c8` | `0x5a084` | **`-0x244`** |
| `__TEXT.__cstring` | `0x1bed` | `0x1c4d` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0xfe8` | `0x1018` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0xd08` | `0xd14` | **`+0xc`** |
| `__AUTH_CONST.__const` | `0x1fb0` | `0x1fb8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1128` | `0x1120` | **`-0x8`** |

### Other Changes

```diff

-287.0.6.0.0
+291.1.0.5.0

-  Functions: 2178
+  Functions: 2172

-  CStrings:  259
+  CStrings:  262
CStrings:
+ "promptExpertLoadLatency"
+ "totalExpertsNeedingNANDLoad"
+ "totalExpertsPurgedCount"
```
