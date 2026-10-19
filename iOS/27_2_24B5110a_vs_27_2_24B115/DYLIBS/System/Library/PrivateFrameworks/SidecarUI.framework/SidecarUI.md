## SidecarUI

> `/System/Library/PrivateFrameworks/SidecarUI.framework/SidecarUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdb0` | `0xe30` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x48c` | `0x4bc` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x4e0` | `0x4f0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2d8` | `0x2e8` | **`+0x10`** |

### Other Changes

```diff

-  Functions: 56
-  Symbols:   151
+  Functions: 58
+  Symbols:   153
Symbols:
+ -[SidecarServiceViewController sidecarServiceDisableSystemGestures]
+ -[SidecarServiceViewController sidecarServiceEnableSystemGestures]
```
