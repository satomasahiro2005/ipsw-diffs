## MultitouchSupport

> `/System/Library/PrivateFrameworks/MultitouchSupport.framework/MultitouchSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cee4` | `0x1d4b8` | **`+0x5d4`** |
| `__TEXT.__unwind_info` | `0x698` | `0x6a8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x780` | `0x788` | **`+0x8`** |

### Other Changes

```diff

-10100.40.2.0.0
+10100.44.0.0.0

-  Functions: 644
-  Symbols:   985
+  Functions: 647
+  Symbols:   989
Symbols:
+ _MTConvert_V3HeaderToV2Header
+ _MTParse_V3BinaryPathOrImage
+ __Z27MTParse_V3BinaryFrameHeaderPhiP28MTParsedMultitouchFrameRep_tP10__MTDevice
+ _os_variant_has_internal_diagnostics
```
