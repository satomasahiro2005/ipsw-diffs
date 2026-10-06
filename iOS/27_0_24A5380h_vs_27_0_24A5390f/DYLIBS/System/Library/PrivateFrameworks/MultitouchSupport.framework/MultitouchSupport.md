## MultitouchSupport

> `/System/Library/PrivateFrameworks/MultitouchSupport.framework/MultitouchSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ca58` | `0x1cee4` | **`+0x48c`** |
| `__TEXT.__const` | `0x2008` | `0x2018` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x690` | `0x698` | **`+0x8`** |

### Other Changes

```diff

-10100.40.0.0.0
+10100.40.2.0.0

-  Functions: 639
-  Symbols:   980
+  Functions: 644
+  Symbols:   985
Symbols:
+ _MTConvert_CompactV10HeaderToV2Header
+ _MTParse_CompactV10BinaryPath
+ __Z24MTCompactV10HeaderUnpackP29MTCompactBinaryFrameHeaderV10Phj
+ __Z31MTCompactV10BinaryContactUnpackP25MTCompactBinaryContactV10Phj
+ __Z35MTParse_CompactV10BinaryFrameHeaderP29MTCompactBinaryFrameHeaderV10P28MTParsedMultitouchFrameRep_tP10__MTDevice
```
