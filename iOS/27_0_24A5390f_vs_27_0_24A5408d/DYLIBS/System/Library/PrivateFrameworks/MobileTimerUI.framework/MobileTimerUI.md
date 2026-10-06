## MobileTimerUI

> `/System/Library/PrivateFrameworks/MobileTimerUI.framework/MobileTimerUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc4fc` | `0xc658` | **`+0x15c`** |
| `__TEXT.__objc_methlist` | `0x1838` | `0x1850` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1558` | `0x1568` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x330` | `0x338` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x468` | `0x470` | **`+0x8`** |

### Other Changes

```diff

-2330.0.0.0.0
+2333.0.0.0.0

-  Functions: 458
-  Symbols:   1005
+  Functions: 459
+  Symbols:   1007
Symbols:
+ +[MTUIDateLabel designatorAttributesWithTextColor:font:timeDesignatorFont:usesFlexibleDayPeriods:]
+ __OBJC_$_CLASS_METHODS_MTUIDateLabel
Functions:
~ -[MTUIDateLabel _updateDateString] : 664 -> 696
+ +[MTUIDateLabel designatorAttributesWithTextColor:font:timeDesignatorFont:usesFlexibleDayPeriods:]
```
