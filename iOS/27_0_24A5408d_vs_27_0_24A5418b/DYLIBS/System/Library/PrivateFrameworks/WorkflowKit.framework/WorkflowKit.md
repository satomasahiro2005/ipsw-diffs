## WorkflowKit

> `/System/Library/PrivateFrameworks/WorkflowKit.framework/WorkflowKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8fabc0` | `0x8fb078` | **`+0x4b8`** |
| `__TEXT.__oslogstring` | `0x2395d` | `0x23a17` | **`+0xba`** |
| `__TEXT.__gcc_except_tab` | `0x4cfc` | `0x4d24` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1bfe8` | `0x1bff8` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x5d44` | `0x5d48` | **`+0x4`** |

### Other Changes

```diff

-5037.103.100.0.0
+5037.109.0.0.0

-  Functions: 43822
-  Symbols:   35155
-  CStrings:  17994
+  Functions: 43824
+  Symbols:   35156
+  CStrings:  17996
Symbols:
+ GCC_except_table13453
+ GCC_except_table13456
+ ___block_descriptor_56_e8_32s40s48bs_e15_v16?0"NSSet"8ls32l8s40l8s48l8
+ ___block_descriptor_64_e8_32s40s48bs56w_e23_v16?0"PKPaymentPass"8lw56l8s32l8s48l8s40l8
- GCC_except_table13457
- ___block_descriptor_56_e8_32s40bs48w_e15_v16?0"NSSet"8lw48l8s32l8s40l8
- ___block_descriptor_64_e8_32s40s48s56bs_e23_v16?0"PKPaymentPass"8ls32l8s40l8s56l8s48l8
CStrings:
+ "%s Did not find valid payment transaction, waiting (%lu waiter(s) for identifier: %@)..."
+ "%s Found matching transaction but it was incomplete, waiting."
+ "%s Received a payment transaction with a nil identifier; ignoring."
+ "All merchant types selected leaving empty state which means Any Category"
- "%s Did not find valid payment transaction waiting..."
- "%s Found valid transaction but it was incomplete, waiting."
```
