## DataAccess

> `/System/Library/PrivateFrameworks/DataAccess.framework/DataAccess`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b16c` | `0x3b25c` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x488c` | `0x489c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2dc0` | `0x2dc8` | **`+0x8`** |

### Other Changes

```diff

-2708.1.5.0.0
+2708.2.2.0.0

-  Functions: 1616
-  Symbols:   2929
+  Functions: 1617
+  Symbols:   2930
Symbols:
+ -[DAAccount _removeXpcActivity]
Functions:
~ -[DAAccount shouldCancelTaskDueToOnPowerFetchMode] : 144 -> 172
~ -[DAAccount saveXpcActivity:] : 196 -> 224
~ -[DAAccount hasXpcActivity] : 16 -> 72
~ -[DAAccount incrementXpcActivityContinueCount] : 204 -> 228
~ -[DAAccount decrementXpcActivityContinueCount] : 232 -> 256
~ -[DAAccount removeXpcActivity] : 280 -> 80
+ -[DAAccount _removeXpcActivity]
```
