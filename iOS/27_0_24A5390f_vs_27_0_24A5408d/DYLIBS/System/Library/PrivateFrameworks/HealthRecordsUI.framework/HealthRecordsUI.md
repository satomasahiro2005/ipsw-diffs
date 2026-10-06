## HealthRecordsUI

> `/System/Library/PrivateFrameworks/HealthRecordsUI.framework/HealthRecordsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3a7ce8` | `0x3a878c` | **`+0xaa4`** |
| `__TEXT.__oslogstring` | `0x7915` | `0x7995` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x14878` | `0x148a0` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x45b8` | `0x45cc` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x3218` | `0x3228` | **`+0x10`** |
| `__DATA.__data` | `0x7ca0` | `0x7cb0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xcea0` | `0xceb0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1f08` | `0x1f10` | **`+0x8`** |

### Other Changes

```diff

-7027.0.67.2.1
+7027.0.72.2.5

-  Functions: 18455
-  Symbols:   8171
-  CStrings:  2078
+  Functions: 18459
+  Symbols:   8170
+  CStrings:  2079
Symbols:
+ ___swift_closure_destructor.59Tm
+ ___swift_closure_destructor.65Tm
+ ___swift_closure_destructor.87Tm
+ ___swift_closure_destructor.99Tm
- ___swift_closure_destructor.111Tm
- ___swift_closure_destructor.53Tm
- ___swift_closure_destructor.62Tm
- ___swift_closure_destructor.84Tm
- ___swift_closure_destructor.96Tm
CStrings:
+ "%s caught error trying to stop sharing before deleting account %s, will ignore and go ahead and delete the account. Error: %s"
```
