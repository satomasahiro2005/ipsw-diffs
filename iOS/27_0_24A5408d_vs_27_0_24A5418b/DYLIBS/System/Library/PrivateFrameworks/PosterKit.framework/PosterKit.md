## PosterKit

> `/System/Library/PrivateFrameworks/PosterKit.framework/PosterKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x55850` | `0x55950` | **`+0x100`** |
| `__TEXT.__text` | `0x187c14` | `0x187ccc` | **`+0xb8`** |
| `__TEXT.__objc_methlist` | `0x1a34c` | `0x1a374` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xc5d0` | `0xc5f0` | **`+0x20`** |
| `__TEXT.__const` | `0x5f54` | `0x5f44` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x6330` | `0x6338` | **`+0x8`** |

### Other Changes

```diff

-355.0.5.0.0
+355.0.8.0.0

-  Functions: 10601
-  Symbols:   15701
+  Functions: 10605
+  Symbols:   15708
Symbols:
+ -[PRRenderer extendRenderingSessionForReason:timeout:]
+ -[PRRenderingSession initWithReason:timeout:invalidationBlock:]
+ GCC_except_table37
+ GCC_except_table44
+ GCC_except_table46
+ GCC_except_table72
+ GCC_except_table87
+ _PRRenderingSessionDefaultTimeoutInterval
+ _PRRenderingSessionTimeoutSafetyMargin
+ _PRWidgetSnapshotRenderSessionRecommendedTimeout
+ _PRWidgetSnapshotRenderSessionTimeoutIsSufficient
+ ___54-[PRRenderer extendRenderingSessionForReason:timeout:]_block_invoke
+ ___63-[PRRenderingSession initWithReason:timeout:invalidationBlock:]_block_invoke
+ _extendRenderingSessionForReason:timeout:.count
- GCC_except_table43
- GCC_except_table45
- GCC_except_table71
- GCC_except_table86
- ___46-[PRRenderer extendRenderingSessionForReason:]_block_invoke
- ___55-[PRRenderingSession initWithReason:invalidationBlock:]_block_invoke
- _extendRenderingSessionForReason:.count
```
