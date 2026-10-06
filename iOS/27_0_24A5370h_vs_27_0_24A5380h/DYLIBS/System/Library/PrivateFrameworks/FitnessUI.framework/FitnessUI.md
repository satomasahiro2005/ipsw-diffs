## FitnessUI

> `/System/Library/PrivateFrameworks/FitnessUI.framework/FitnessUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__data` | `0xe98` | `0xe00` | **`-0x98`** |
| `__DATA_DIRTY.__data` | `—` | `0x98` | **`+0x98`** |
| `__TEXT.__text` | `0xa334c` | `0xa33c8` | **`+0x7c`** |
| `__AUTH.__objc_data` | `0x2040` | `0x1ff0` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x4b0` | `0x500` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x6c6c` | `0x6c7c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x4da0` | `0x4da8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2e00` | `0x2e08` | **`+0x8`** |

### Other Changes

```diff

-2027.0.55.0.0
+2027.0.59.0.0

-  Functions: 5892
-  Symbols:   5141
+  Functions: 5893
+  Symbols:   5142
Symbols:
+ -[FIUIWorkoutSettingsManager _shouldClearOldMetricsForSettingsByActivityType:metricFormatVersion:]
```
