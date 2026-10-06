## UIKitCore

> `/System/Library/PrivateFrameworks/UIKitCore.framework/UIKitCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bcb43c` | `0x1bcb540` | **`+0x104`** |
| `__AUTH_CONST.__cfstring` | `0xb3720` | `0xb3760` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x54c32` | `0x54c60` | **`+0x2e`** |
| `__TEXT.__cstring` | `0x101b1d` | `0x101b2a` | **`+0xd`** |

### Other Changes

```diff

-9127.0.84.1.115
+9127.0.84.1.116

-  CStrings:  33771
+  CStrings:  33774
Functions:
~ +[UIKeyboard sizeForInterfaceOrientation:includingAssistantBar:ignoreInputView:] : 452 -> 712
CStrings:
+ "Calculated size for keyboard %@ assistant: %@"
+ "with"
+ "without"
```
