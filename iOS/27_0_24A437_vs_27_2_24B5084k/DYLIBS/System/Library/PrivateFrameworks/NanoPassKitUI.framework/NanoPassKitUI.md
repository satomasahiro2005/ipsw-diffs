## NanoPassKitUI

> `/System/Library/PrivateFrameworks/NanoPassKitUI.framework/NanoPassKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26234` | `0x261e0` | **`-0x54`** |
| `__AUTH_CONST.__objc_const` | `0x4728` | `0x4738` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f38` | `0x1f30` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x898` | `0x8a0` | **`+0x8`** |

### Other Changes

```diff

-1347.0.0.0.0
+1353.0.0.0.0

-  Functions: 946
-  Symbols:   1765
+  Functions: 945
+  Symbols:   1764
Symbols:
+ -[PKPass(NanoPassKitUI) npkHasBankLogoCardArt]
+ -[PKPass(NanoPassKitUI) npkNeedsCardArtTopRightText]
+ -[PKPass(NanoPassKitUI) npkNeedsForegroundLabelsWithDynamicCardArtInUse:]
- +[NPKPaymentPassView _hasBankLogoForPassBundle:]
- -[NPKDynamicFaceViewAdapter allowsForegroundLabels]
- -[NPKPaymentPassView _foregroundLabelsNeeded]
- -[NPKPaymentPassView _topRightLabelNeeded]
```
