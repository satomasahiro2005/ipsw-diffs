## SuggestedImage

> `/System/Library/PrivateFrameworks/SuggestedImage.framework/SuggestedImage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x103db8` | `0x10625c` | **`+0x24a4`** |
| `__TEXT.__eh_frame` | `0xc850` | `0xcab8` | **`+0x268`** |
| `__TEXT.__oslogstring` | `0x2788` | `0x2838` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0x4500` | `0x4568` | **`+0x68`** |
| `__TEXT.__swift_as_cont` | `0xb44` | `0xb68` | **`+0x24`** |
| `__TEXT.__swift5_reflstr` | `0x1917` | `0x1937` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x688` | `0x69c` | **`+0x14`** |
| `__TEXT.__const` | `0x7e0d` | `0x7e1d` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1d20` | `0x1d2c` | **`+0xc`** |

### Other Changes

```diff

-198.2.11.0.0
+198.2.12.0.0

-  Functions: 3997
+  Functions: 4017

-  CStrings:  486
+  CStrings:  488
Symbols:
+ ___swift_closure_destructor.284Tm
- ___swift_closure_destructor.281Tm
CStrings:
+ "On-demand generation failed a safety check for request %s (useCase: %s); refusing it permanently."
+ "Skipping on-demand generation for refused request: %s"
```
