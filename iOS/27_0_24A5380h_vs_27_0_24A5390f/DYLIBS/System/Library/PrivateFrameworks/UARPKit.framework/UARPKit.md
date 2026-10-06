## UARPKit

> `/System/Library/PrivateFrameworks/UARPKit.framework/UARPKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14334` | `0x143f0` | **`+0xbc`** |
| `__TEXT.__objc_methlist` | `0x14d8` | `0x14f8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xd78` | `0xd88` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x1e88` | `0x1e90` | **`+0x8`** |

### Other Changes

```diff

-1587.0.21.0.0
+1587.0.27.0.0

-  Functions: 516
-  Symbols:   776
+  Functions: 518
+  Symbols:   778
Symbols:
+ -[UARPDeviceManager startPruning]
+ GCC_except_table120
+ GCC_except_table123
+ ___33-[UARPDeviceManager startPruning]_block_invoke
- GCC_except_table118
- GCC_except_table121
```
