## AXRuntime

> `/System/Library/PrivateFrameworks/AXRuntime.framework/AXRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e78c` | `0x4e830` | **`+0xa4`** |
| `__DATA.__data` | `0x8c0` | `0x880` | **`-0x40`** |
| `__DATA_DIRTY.__data` | `0x50` | `0x90` | **`+0x40`** |
| `__DATA.__bss` | `0x318` | `0x308` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x2d8` | `0x2e8` | **`+0x10`** |

### Other Changes

```diff

-3245.7.1.0.0
+3245.8.2.0.0

-  Functions: 1653
-  Symbols:   3257
+  Functions: 1654
+  Symbols:   3258
Symbols:
+ GCC_except_table1395
+ GCC_except_table1473
+ GCC_except_table1501
+ GCC_except_table1548
+ GCC_except_table1609
+ GCC_except_table1617
+ ___42-[AXElementFetcher disableEventManagement]_block_invoke
- GCC_except_table1394
- GCC_except_table1472
- GCC_except_table1500
- GCC_except_table1547
- GCC_except_table1608
- GCC_except_table1616
Functions:
~ -[AXElementFetcher disableEventManagement] : 428 -> 240
+ ___42-[AXElementFetcher disableEventManagement]_block_invoke
```
