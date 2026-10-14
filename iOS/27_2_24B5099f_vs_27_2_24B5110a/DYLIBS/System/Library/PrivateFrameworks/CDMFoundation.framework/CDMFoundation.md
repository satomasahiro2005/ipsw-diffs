## CDMFoundation

> `/System/Library/PrivateFrameworks/CDMFoundation.framework/CDMFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28b2c4` | `0x28b360` | **`+0x9c`** |
| `__TEXT.__oslogstring` | `0x1f260` | `0x1f290` | **`+0x30`** |
| `__DATA.__data` | `0x1c38` | `0x1c48` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x8110` | `0x8100` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x4e60` | `0x4e58` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x55d4` | `0x55dc` | **`+0x8`** |

### Other Changes

```diff

-3605.18.1.0.0
+3605.19.1.11.1

-  Functions: 13049
+  Functions: 13054

-  CStrings:  4746
+  CStrings:  4747
Symbols:
+ ___swift_closure_destructor.216Tm
+ ___swift_closure_destructor.31Tm
+ ___swift_closure_destructor.51Tm
+ ___swift_closure_destructor.61Tm
- _AFDeviceSupportsSAEByDeviceCapabilityAndFeatureFlags
- ___swift_closure_destructor.219Tm
- ___swift_closure_destructor.34Tm
- ___swift_closure_destructor.54Tm
CStrings:
+ "cdmClient could not be created, aborting setup"
+ "cdmClient doesn't exist, should call setup"
- "cdmClient is nil, this can't happen"
```
