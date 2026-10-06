## KeyboardArbiter

> `/System/Library/PrivateFrameworks/KeyboardArbiter.framework/KeyboardArbiter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1faac` | `0x1f8e4` | **`-0x1c8`** |
| `__TEXT.__oslogstring` | `0x2388` | `0x2404` | **`+0x7c`** |
| `__AUTH_CONST.__objc_const` | `0x2be8` | `0x2bb8` | **`-0x30`** |
| `__TEXT.__cstring` | `0x1996` | `0x19bf` | **`+0x29`** |
| `__DATA_CONST.__const` | `0x958` | `0x978` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x9a8` | `0x994` | **`-0x14`** |
| `__DATA_DIRTY.__bss` | `0xf0` | `0x100` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1954` | `0x1944` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x2f0` | `0x2e8` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1270` | `0x1278` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x700` | `0x708` | **`+0x8`** |

### Other Changes

```diff

-9127.0.79.1.102
+9127.0.84.1.102

-  Symbols:   1199
-  CStrings:  346
+  Symbols:   1198
+  CStrings:  349
Symbols:
+ -[_UIKeyboardArbiter _handleForPID:]
+ -[_UIKeyboardArbiter handleRepresentsEventDeferringTarget:]
+ -[_UIKeyboardArbiterAdvisorAction abortForUsageViolation:]
+ -[_UIKeyboardArbiterClientHandle keyboardSceneHostComponent]
+ -[_UIKeyboardArbiterOmniscientDelegateAction abortForUsageViolation:]
+ GCC_except_table131
+ GCC_except_table137
+ GCC_except_table173
+ GCC_except_table177
+ GCC_except_table179
+ GCC_except_table198
+ GCC_except_table199
+ GCC_except_table46
+ GCC_except_table63
+ GCC_except_table65
+ GCC_except_table67
+ GCC_except_table95
+ ___36-[_UIKeyboardArbiter _handleForPID:]_block_invoke
+ ___block_descriptor_36_e40_B16?0"_UIKeyboardArbiterClientHandle"8l
- -[_UIKeyboardArbiterClientHandle pointIsWithinKeyboardContent:onCompletion:]
- -[_UIKeyboardArbiterClientHandle setAllVisibleFrames:]
- -[_UIKeyboardArbiterInputUIClientSceneComponent setVisibleKeyboardFrames:]
- GCC_except_table129
- GCC_except_table135
- GCC_except_table170
- GCC_except_table174
- GCC_except_table176
- GCC_except_table195
- GCC_except_table196
- GCC_except_table47
- GCC_except_table64
- GCC_except_table66
- GCC_except_table68
- GCC_except_table96
- _.str
- _OBJC_CLASS_$_UIPeripheralHost
- ___54-[_UIKeyboardArbiter setActiveInputDestinationHandle:]_block_invoke_3
- ___54-[_UIKeyboardArbiterClientHandle setAllVisibleFrames:]_block_invoke
- ___74-[_UIKeyboardArbiterInputUIClientSceneComponent setVisibleKeyboardFrames:]_block_invoke
CStrings:
+ "B16@?0@\"_UIKeyboardArbiterClientHandle\"8"
+ "KeyboardArbiter could not find a keyboard scene for app scene %@"
+ "KeyboardArbiter has no scene identity for client handle %@"
```
