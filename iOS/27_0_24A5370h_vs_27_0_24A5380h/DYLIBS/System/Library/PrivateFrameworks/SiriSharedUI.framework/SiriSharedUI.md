## SiriSharedUI

> `/System/Library/PrivateFrameworks/SiriSharedUI.framework/SiriSharedUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x30` | `0xb88` | **`+0xb58`** |
| `__DATA_DIRTY.__objc_data` | `0x320` | `0xcc8` | **`+0x9a8`** |
| `__AUTH.__objc_data` | `0x51f8` | `0x4878` | **`-0x980`** |
| `__DATA.__data` | `0x5e40` | `0x58a0` | **`-0x5a0`** |
| `__AUTH.__data` | `0x3670` | `0x30e0` | **`-0x590`** |
| `__DATA.__common` | `0x520` | `0x2a0` | **`-0x280`** |
| `__DATA_DIRTY.__common` | `—` | `0x278` | **`+0x278`** |
| `__DATA_DIRTY.__bss` | `—` | `0x110` | **`+0x110`** |
| `__DATA.__bss` | `0x55d0` | `0x54d0` | **`-0x100`** |
| `__AUTH_CONST.__objc_const` | `0xf3e8` | `0xf408` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x4700` | `0x4720` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x36a6` | `0x36c6` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x16c8` | `0x16d8` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x26f0` | `0x26fc` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x5308` | `0x5310` | **`+0x8`** |
| `__TEXT.__text` | `0x165d0c` | `0x165d04` | **`-0x8`** |

### Other Changes

```diff

-3600.55.10.0.0
+3600.55.26.0.0

-  Symbols:   5361
+  Symbols:   5362
Symbols:
+ ___swift_closure_destructor.114Tm
+ _kCACornerCurveContinuous
- ___swift_closure_destructor.110Tm
Functions:
~ -[SiriSharedUIContentPlatterView setBackgroundView:] : 668 -> 708
~ -[SiriSharedUIContentPlatterView setIsInAmbient:] : 220 -> 296
~ sub_1c87930a0 -> sub_1cc9851b4 : 3540 -> 3564
~ sub_1c87961b4 -> sub_1cc9882e0 : 3804 -> 3820
~ sub_1c87c42b0 -> sub_1cc9b63ec : 528 -> 524
~ sub_1c87cc228 -> sub_1cc9be360 : 352 -> 404
~ sub_1c87cc3ec -> sub_1cc9be558 : 376 -> 88
~ sub_1c87cf3ac -> sub_1cc9c13f8 : 1032 -> 1020
~ sub_1c87fda2c -> sub_1cc9efa6c : 416 -> 412
~ sub_1c87fdbcc -> sub_1cc9efc08 : 432 -> 428
~ sub_1c8806d7c -> sub_1cc9f8db4 : 500 -> 496
~ sub_1c885847c -> sub_1cca4a4b0 : 596 -> 244
~ sub_1c885a3d0 -> sub_1cca4c2a4 : 872 -> 888
~ sub_1c885aff8 -> sub_1cca4cedc : 1100 -> 1120
~ sub_1c885b920 -> sub_1cca4d818 : 2748 -> 3096
~ sub_1c88814fc -> sub_1cca73550 : 480 -> 484
~ sub_1c8886ac8 -> sub_1cca78b20 : 240 -> 324
~ sub_1c8886fac -> sub_1cca79058 : 348 -> 328
```
