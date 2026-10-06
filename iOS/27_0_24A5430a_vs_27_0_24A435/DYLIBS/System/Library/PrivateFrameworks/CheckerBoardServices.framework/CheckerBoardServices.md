## CheckerBoardServices

> `/System/Library/PrivateFrameworks/CheckerBoardServices.framework/CheckerBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x581c` | `0x58fc` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0xec8` | `0xef8` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x1250` | `0x1260` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xb20` | `0xb30` | **`+0x10`** |

### Other Changes

```diff

-  Functions: 189
-  Symbols:   487
+  Functions: 192
+  Symbols:   490
Symbols:
+ +[CBSUtilities motionStateUpdatesEnabled:]
+ +[CBSUtilities setMotionStateUpdatesEnabled:]
+ _OUTLINED_FUNCTION_2
Functions:
~ _OUTLINED_FUNCTION_0 : 12 -> 20
+ _OUTLINED_FUNCTION_2
+ +[CBSUtilities setMotionStateUpdatesEnabled:]
+ +[CBSUtilities currentLocaleIdentifier:]
~ ___17-[CBSClient init]_block_invoke.cold.1 : 60 -> 52
+ ___17-[CBSClient init]_block_invoke.99.cold.1
- ___33-[CBSClient systemServicesServer]_block_invoke.cold.1
```
