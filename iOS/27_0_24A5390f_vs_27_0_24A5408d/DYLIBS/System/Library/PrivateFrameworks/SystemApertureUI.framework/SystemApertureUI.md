## SystemApertureUI

> `/System/Library/PrivateFrameworks/SystemApertureUI.framework/SystemApertureUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15174` | `0x152b4` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x6648` | `0x66c0` | **`+0x78`** |
| `__AUTH_CONST.__cfstring` | `0xa80` | `0xa20` | **`-0x60`** |
| `__TEXT.__objc_methlist` | `0x244c` | `0x249c` | **`+0x50`** |
| `__TEXT.__cstring` | `0xcad` | `0xc7d` | **`-0x30`** |
| `__TEXT.__oslogstring` | `0xaa4` | `0xa75` | **`-0x2f`** |
| `__DATA_CONST.__objc_selrefs` | `0x10b8` | `0x10d8` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x1ac` | `0x1b4` | **`+0x8`** |

### Other Changes

```diff

-99.0.0.0.0
+101.0.0.0.0

-  Functions: 603
-  Symbols:   1292
-  CStrings:  142
+  Functions: 607
+  Symbols:   1301
+  CStrings:  138
Symbols:
+ -[SAUIElementViewController _refreshMatchMoveAnimation]
+ -[SAUIElementViewController prefersContentViewMatchMove]
+ -[SAUIElementViewController setPrefersContentViewMatchMove:]
+ -[SAUILayoutSpecifyingElementViewController prefersContentViewMatchMove]
+ -[SAUILayoutSpecifyingElementViewController setPrefersContentViewMatchMove:]
+ GCC_except_table104
+ GCC_except_table107
+ GCC_except_table32
+ GCC_except_table6
+ _OBJC_IVAR_$_SAUIElementViewController._prefersContentViewMatchMove
+ _OBJC_IVAR_$_SAUILayoutSpecifyingElementViewController._prefersContentViewMatchMove
+ __OBJC_$_PROP_LIST_SAUIContentTransitioning
- GCC_except_table102
- GCC_except_table105
- GCC_except_table30
CStrings:
+ "\xd1!"
- "View will transition with settings: %{public}@"
- "__animator"
- "__mainContext"
- "_fluidBehaviorSettings"
- "\xc1!"
```
