## CameraEditKit

> `/System/Library/PrivateFrameworks/CameraEditKit.framework/CameraEditKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41ddc` | `0x41e68` | **`+0x8c`** |
| `__AUTH.__objc_data` | `0x1450` | `0x14a0` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x320` | `0x2d0` | **`-0x50`** |
| `__AUTH_CONST.__objc_const` | `0x9200` | `0x9230` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x56d4` | `0x56ec` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3470` | `0x3480` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x700` | `0x704` | **`+0x4`** |

### Other Changes

```diff

-4167.0.0.0.2
+4171.0.0.0.1
+  - /System/Library/Frameworks/AVFoundation.framework/AVFoundation

-  Functions: 2054
-  Symbols:   3378
+  Functions: 2056
+  Symbols:   3381
Symbols:
+ -[CEKExpandingTickMarksView expandedTicksUseMainHeight]
+ -[CEKExpandingTickMarksView setExpandedTicksUseMainHeight:]
+ _OBJC_IVAR_$_CEKExpandingTickMarksView._expandedTicksUseMainHeight
Functions:
~ -[CEKExpandingTickMarksView initWithMinimumValue:maximumValue:] : 400 -> 420
+ -[CEKExpandingTickMarksView setExpandedTicksUseMainHeight:]
~ ___43-[CEKExpandingTickMarksView layoutSubviews]_block_invoke : 564 -> 612
+ -[CEKExpandingTickMarksView setSelectionStyle:]
~ -[CEKExpandingSlider initWithTitle:minimumValue:maximumValue:defaultValue:tickMarkStyle:] : 1624 -> 1640
```
