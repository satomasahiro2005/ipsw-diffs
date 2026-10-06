## SpringBoardUIServices

> `/System/Library/PrivateFrameworks/SpringBoardUIServices.framework/SpringBoardUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa2c10` | `0xa2ef8` | **`+0x2e8`** |
| `__AUTH_CONST.__objc_const` | `0x2daa0` | `0x2dac0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x7cc8` | `0x7ce8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xe8b4` | `0xe8cc` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x32d8` | `0x32e0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xd3c` | `0xd40` | **`+0x4`** |
| `__TEXT.__cstring` | `0xabf9` | `0xabfa` | **`+0x1`** |

### Other Changes

```diff

-4636.102.1.0.0
+4636.110.0.0.0

-  Functions: 4807
-  Symbols:   9435
+  Functions: 4809
+  Symbols:   9436
Symbols:
+ -[SBUIPasscodeLockViewWithKeyboard _correctContainerBottomConstraintIfNeeded]
+ -[SBUIPasscodeLockViewWithKeyboard initWithLightStyle:pinKeyboardToBottom:]
+ _OBJC_IVAR_$_SBUIPasscodeLockViewWithKeyboard._pinKeyboardToBottom
- GCC_except_table13
- GCC_except_table17
Functions:
~ +[SBUIPasscodeLockViewFactory _passcodeLockViewForStyle:withLightStyle:dimmed:] : 220 -> 280
~ -[SBUIPasscodeLockViewWithKeyboard initWithLightStyle:] : 1224 -> 8
+ -[SBUIPasscodeLockViewWithKeyboard initWithLightStyle:pinKeyboardToBottom:]
~ -[SBUIPasscodeLockViewWithKeyboard layoutSubviews] : 100 -> 136
+ -[SBUIPasscodeLockViewWithKeyboard _correctContainerBottomConstraintIfNeeded]
```
