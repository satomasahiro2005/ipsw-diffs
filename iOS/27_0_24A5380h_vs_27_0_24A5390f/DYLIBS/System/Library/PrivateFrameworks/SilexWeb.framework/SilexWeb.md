## SilexWeb

> `/System/Library/PrivateFrameworks/SilexWeb.framework/SilexWeb`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x189cc` | `0x18e04` | **`+0x438`** |
| `__DATA_CONST.__objc_selrefs` | `0x1680` | `0x16c0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x358c` | `0x35cc` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x9e10` | `0x9e40` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x498` | `0x4a8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x890` | `0x898` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x480` | `0x484` | **`+0x4`** |
| `__TEXT.__cstring` | `0x1e2d` | `0x1e30` | **`+0x3`** |

### Other Changes

```diff

-5923.0.0.0.0
+5926.0.0.0.0

-  Functions: 933
-  Symbols:   2569
+  Functions: 938
+  Symbols:   2577
Symbols:
+ -[SWContainerViewController currentScreen]
+ -[SWContainerViewController handleScreenDidDisconnect:]
+ -[SWContainerViewController invalidateKeyboardFrameIfScreenChanged]
+ -[SWContainerViewController keyboardScreen]
+ -[SWContainerViewController setKeyboardScreen:]
+ _OBJC_CLASS_$_UIScreen
+ _OBJC_IVAR_$_SWContainerViewController._keyboardScreen
+ _UIScreenDidDisconnectNotification
```
