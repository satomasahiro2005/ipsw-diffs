## SiriUIFoundation

> `/System/Library/PrivateFrameworks/SiriUIFoundation.framework/SiriUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x91fec` | `0x92234` | **`+0x248`** |
| `__DATA.__data` | `0x1750` | `0x1740` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2fc0` | `0x2fd0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x4768` | `0x4778` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xf28` | `0xf20` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xa98` | `0xaa0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2788` | `0x2790` | **`+0x8`** |

### Other Changes

```diff

-3605.22.2.0.0
+3605.24.1.0.0

-  Functions: 3392
-  Symbols:   3757
+  Functions: 3394
+  Symbols:   3760
Symbols:
+ -[SRUIFInstrumentationManager emitResponseScrolledWithReachedLastLine:]
+ GCC_except_table106
+ _OBJC_CLASS_$_SISchemaUEIResponseScrolled
+ ___71-[SRUIFInstrumentationManager emitResponseScrolledWithReachedLastLine:]_block_invoke
- GCC_except_table111
```
