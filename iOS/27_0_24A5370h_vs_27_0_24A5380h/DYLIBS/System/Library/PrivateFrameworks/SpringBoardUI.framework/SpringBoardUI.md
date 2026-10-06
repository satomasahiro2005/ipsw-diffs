## SpringBoardUI

> `/System/Library/PrivateFrameworks/SpringBoardUI.framework/SpringBoardUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15280` | `0x1526c` | **`-0x14`** |
| `__TEXT.__unwind_info` | `0x7f8` | `0x800` | **`+0x8`** |

### Other Changes

```diff

-4621.0.0.0.0
+4626.103.0.0.0

-  Symbols:   1790
+  Symbols:   1794
Symbols:
+ __UIClamp
+ __UILerp
+ __UIUnitClamp
+ __UIUnlerp
Functions:
~ -[SBUIFlashlightController _main_configureWithFlashlight:] : 884 -> 864
~ -[SBUIFlashlightController _updateObservedBeamWidth:] : 244 -> 228
~ -[SBUIFlashlightController _setIntensity:width:animated:withPowerChange:] : 684 -> 676
~ -[SBUIFlashlightController _setFlashlightBeamWidth:] : 148 -> 172
```
