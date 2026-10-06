## SiriUI

> `/System/Library/PrivateFrameworks/SiriUI.framework/SiriUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x460e8` | `0x46148` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x260` | `0x280` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0xb818` | `0xb838` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xa50` | `0xa60` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x49f8` | `0x4a00` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x7354` | `0x735c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x15f0` | `0x15f8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x6d4` | `0x6d8` | **`+0x4`** |

### Other Changes

```diff

-3600.55.10.0.0
+3600.55.26.0.0

-  Functions: 2098
-  Symbols:   4337
+  Functions: 2100
+  Symbols:   4339
Symbols:
+ -[SiriUISnippetManager _ensurePluginBundlesLoaded]
+ GCC_except_table25
+ GCC_except_table33
+ GCC_except_table39
+ _OBJC_IVAR_$_SiriUISnippetManager._pluginBundlesLoaded
+ ___50-[SiriUISnippetManager _ensurePluginBundlesLoaded]_block_invoke
- GCC_except_table20
- GCC_except_table23
- GCC_except_table29
- GCC_except_table35
```
