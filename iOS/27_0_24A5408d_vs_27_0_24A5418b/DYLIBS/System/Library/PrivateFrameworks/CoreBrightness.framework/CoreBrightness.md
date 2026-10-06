## CoreBrightness

> `/System/Library/PrivateFrameworks/CoreBrightness.framework/CoreBrightness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x171b1c` | `0x171b9c` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0xd5f4` | `0xd60c` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x5a60` | `0x5a70` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x5700` | `0x5708` | **`+0x8`** |

### Other Changes

```diff

-2300.2.7.0.0
+2300.2.9.0.0

-  Functions: 8830
-  Symbols:   10314
+  Functions: 8832
+  Symbols:   10316
Symbols:
+ -[CBIndicatorBrightnessModule currentTimeUs]
+ -[CBIndicatorBrightnessModule shouldHintSILOnForEventTimestampUs:]
```
