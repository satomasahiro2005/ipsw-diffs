## Pegasus

> `/System/Library/PrivateFrameworks/Pegasus.framework/Pegasus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43c38` | `0x4404c` | **`+0x414`** |
| `__DATA_CONST.__objc_selrefs` | `0x2d08` | `0x2d30` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x4654` | `0x4674` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1470` | `0x1478` | **`+0x8`** |

### Other Changes

```diff

-307.0.0.0.0
+310.0.0.0.0

-  Functions: 1761
-  Symbols:   3165
+  Functions: 1764
+  Symbols:   3167
Symbols:
+ -[PGButtonGroupView _visibleButtonCount]
+ -[PGButtonGroupView hitTest:withEvent:]
+ -[PGButtonView setTouchOutsets:]
+ GCC_except_table47
- GCC_except_table3
- GCC_except_table46
```
