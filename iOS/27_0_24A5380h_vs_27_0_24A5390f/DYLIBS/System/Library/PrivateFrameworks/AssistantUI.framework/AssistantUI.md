## AssistantUI

> `/System/Library/PrivateFrameworks/AssistantUI.framework/AssistantUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x65aa0` | `0x65b50` | **`+0xb0`** |
| `__TEXT.__objc_methlist` | `0x7240` | `0x7270` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1ba0` | `0x1bc8` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x83b8` | `0x83c8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x53a0` | `0x53b0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2198` | `0x21a0` | **`+0x8`** |

### Other Changes

```diff

-3600.55.26.0.0
+3600.55.30.0.0

-  Functions: 2799
-  Symbols:   4431
+  Functions: 2801
+  Symbols:   4436
Symbols:
+ -[AFUISiriSession assistantConnection:setReplayCaptureRequested:toPath:]
+ GCC_except_table119
+ GCC_except_table154
+ GCC_except_table157
+ GCC_except_table186
+ GCC_except_table187
+ GCC_except_table224
+ GCC_except_table233
+ GCC_except_table256
+ GCC_except_table259
+ GCC_except_table262
+ GCC_except_table270
+ GCC_except_table279
+ GCC_except_table299
+ ___72-[AFUISiriSession assistantConnection:setReplayCaptureRequested:toPath:]_block_invoke
+ ___block_descriptor_41_e8_32s_e35_v16?0"<AFUISiriSessionDelegate>"8ls32l8
- GCC_except_table117
- GCC_except_table152
- GCC_except_table155
- GCC_except_table184
- GCC_except_table185
- GCC_except_table216
- GCC_except_table254
- GCC_except_table257
- GCC_except_table268
- GCC_except_table277
- GCC_except_table297
```
