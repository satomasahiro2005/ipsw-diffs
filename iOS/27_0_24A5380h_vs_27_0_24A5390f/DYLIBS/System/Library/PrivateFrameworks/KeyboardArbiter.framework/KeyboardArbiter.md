## KeyboardArbiter

> `/System/Library/PrivateFrameworks/KeyboardArbiter.framework/KeyboardArbiter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f7bc` | `0x1faac` | **`+0x2f0`** |
| `__TEXT.__oslogstring` | `0x22dc` | `0x2388` | **`+0xac`** |
| `__TEXT.__const` | `0x108` | `0x110` | **`+0x8`** |
| `__TEXT.__cstring` | `0x1998` | `0x1996` | **`-0x2`** |

### Other Changes

```diff

-9127.0.75.1.101
+9127.0.79.1.102

-  Symbols:   1197
-  CStrings:  344
+  Symbols:   1199
+  CStrings:  346
Symbols:
+ _NSStringFromCGRect
+ _objc_retain_x26
Functions:
~ ___65-[_UIKeyboardArbiter updateKeyboardStatus:fromHandler:fromFocus:]_block_invoke_2 : 180 -> 432
~ ___58-[_UIKeyboardArbiter processWithPID:foreground:suspended:]_block_invoke : 2288 -> 2520
~ ___58-[_UIKeyboardArbiter processWithPID:foreground:suspended:]_block_invoke.286 : 148 -> 400
~ ___45-[_UIKeyboardArbiter configureNewConnection:]_block_invoke.326 : 968 -> 984
CStrings:
+ "-[_UIKeyboardArbiter processWithPID:foreground:suspended:]_block_invoke"
+ "TX %{public}@(%d) queue_keyboardChanged (source:%{public}@ onScreen:%s frame:%{public}@"
+ "processWithPID:%d foreground:%s suspended:%s (%{public}@ wasRunning:%s isRunning:%s"
- "-[_UIKeyboardArbiter processWithPID:foreground:suspended:]_block_invoke_2"
```
