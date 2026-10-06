## MobileTimerUI

> `/System/Library/PrivateFrameworks/MobileTimerUI.framework/MobileTimerUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc51c` | `0xc4fc` | **`-0x20`** |

### Other Changes

```diff

-2327.0.1.0.0
+2328.0.0.0.0
Functions:
~ -[MTUIBitmapHandView initWithBundle:resourcePath:partInfoList:rotationalCenter:] : 1120 -> 1112
~ +[MTUIAnalogClockView initialize] : 584 -> 580
~ +[MTUIAnalogClockView updateTimeForAllSweeping] : 636 -> 628
~ +[MTUIAnalogClockView unregisterSweepingClock:] : 572 -> 568
~ -[MTUIAnalogClockView init] : 1136 -> 1128
~ -[MTUIAnalogClockView setNighttime:] : 364 -> 372
~ -[MTUIAnalogClockView .cxx_destruct] : 300 -> 292
```
