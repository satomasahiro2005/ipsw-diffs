## SystemIntentsSupport

> `/System/Library/PrivateFrameworks/SystemIntentsSupport.framework/SystemIntentsSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2640` | `0x2728` | **`+0xe8`** |
| `__TEXT.__cstring` | `0x1d6` | `0x1c6` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x200` | `0x208` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x170` | `0x178` | **`+0x8`** |

### Other Changes

```diff

-14.0.0.0.0
+16.0.0.0.0

-  Functions: 94
-  Symbols:   125
+  Functions: 95
+  Symbols:   126
Symbols:
+ _objc_release_x27
CStrings:
+ "SystemIntentsSupport.CloseApplicationAction"
+ "SystemIntentsSupport.CloseSceneAction"
+ "SystemIntentsSupport.ShowHomeScreenAction"
- "SystemIntentsSupport_Internal.CloseApplicationAction"
- "SystemIntentsSupport_Internal.CloseSceneAction"
- "SystemIntentsSupport_Internal.ShowHomeScreenAction"
```
