## FitnessIntelligenceInference

> `/System/Library/PrivateFrameworks/FitnessIntelligenceInference.framework/FitnessIntelligenceInference`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa8b58` | `0xaa794` | **`+0x1c3c`** |
| `__TEXT.__oslogstring` | `0x2c85` | `0x2d85` | **`+0x100`** |
| `__TEXT.__eh_frame` | `0x8414` | `0x84e4` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x24a8` | `0x24d0` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x101e` | `0x1042` | **`+0x24`** |
| `__TEXT.__cstring` | `0xc19` | `0xc39` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1550` | `0x1538` | **`-0x18`** |
| `__TEXT.__swift5_reflstr` | `0xb12` | `0xb22` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x834` | `0x844` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x84c` | `0x850` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x37c` | `0x380` | **`+0x4`** |

### Other Changes

```diff

-2027.0.59.0.2
+2027.0.66.0.0

-  Functions: 1765
-  Symbols:   664
-  CStrings:  300
+  Functions: 1772
+  Symbols:   662
+  CStrings:  306
Symbols:
+ _symbolic ScsySd______pG s5ErrorP
+ _symbolic _____ySd______p_G Scs12ContinuationV s5ErrorP
+ _symbolic _____ySd______p_G Scs8IteratorV s5ErrorP
+ _symbolic _____ySd______p__G Scs12ContinuationV11YieldResultO s5ErrorP
+ _symbolic _____ySd______p__G Scs12ContinuationV15BufferingPolicyO s5ErrorP
- ___swift_closure_destructor.10Tm
- _objc_retain_x28
- _symbolic ScSySdG
- _symbolic _____ySd_G ScS12ContinuationV
- _symbolic _____ySd_G ScS8IteratorV
- _symbolic _____ySd__G ScS12ContinuationV11YieldResultO
- _symbolic _____ySd__G ScS12ContinuationV15BufferingPolicyO
CStrings:
+ "PhoneAvailabilitySystem"
+ "[%s][%s] Did not receive chunks; failing"
+ "[%s][%s] Enqueueing tone for streaming"
+ "[%s][%s] Error while attempting to stream tone: %@"
+ "[%s][%s] Skipping tone for legacy stream"
+ "[%s][%s] Unable to locate tone asset"
```
