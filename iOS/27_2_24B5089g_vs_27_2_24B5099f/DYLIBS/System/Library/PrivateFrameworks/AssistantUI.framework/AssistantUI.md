## AssistantUI

> `/System/Library/PrivateFrameworks/AssistantUI.framework/AssistantUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x65f50` | `0x66004` | **`+0xb4`** |
| `__DATA_CONST.__const` | `0x1bc8` | `0x1bf0` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x72c0` | `0x72e8` | **`+0x28`** |
| `__TEXT.__oslogstring` | `0x57f3` | `0x5807` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x53f0` | `0x5400` | **`+0x10`** |
| `__TEXT.__cstring` | `0x8a66` | `0x8a76` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x83d0` | `0x83d8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x21b0` | `0x21b8` | **`+0x8`** |

### Other Changes

```diff

-3605.24.1.0.0
+3605.30.1.0.0

-  Functions: 2807
-  Symbols:   4444
+  Functions: 2809
+  Symbols:   4445
Symbols:
+ -[AFUISiriSession _launchContextMachAbsoluteTimeForRequestOptions:]
+ -[AFUISiriSession performIFAction:turnIdentifier:]
+ GCC_except_table221
+ GCC_except_table228
+ GCC_except_table232
+ GCC_except_table234
+ GCC_except_table257
+ GCC_except_table263
+ GCC_except_table271
+ GCC_except_table280
+ GCC_except_table300
+ GCC_except_table330
+ ___50-[AFUISiriSession performIFAction:turnIdentifier:]_block_invoke
+ ___block_descriptor_56_e8_32s40s48w_e5_v8?0ls32l8s40l8w48l8
- GCC_except_table222
- GCC_except_table224
- GCC_except_table227
- GCC_except_table231
- GCC_except_table233
- GCC_except_table256
- GCC_except_table259
- GCC_except_table262
- GCC_except_table270
- GCC_except_table279
- GCC_except_table299
- GCC_except_table328
- ___35-[AFUISiriSession performIFAction:]_block_invoke
CStrings:
+ "%s action: %@, turnIdentifier: %@"
+ "-[AFUISiriSession performIFAction:turnIdentifier:]"
- "%s action: %@"
- "-[AFUISiriSession performIFAction:]"
```
