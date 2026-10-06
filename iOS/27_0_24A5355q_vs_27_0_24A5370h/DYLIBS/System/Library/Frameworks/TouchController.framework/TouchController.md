## TouchController

> `/System/Library/Frameworks/TouchController.framework/TouchController`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x31c04` | `0x31ca0` | **`+0x9c`** |
| `__AUTH_CONST.__auth_got` | `0x908` | `0x910` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xdc8` | `0xdd0` | **`+0x8`** |

### Other Changes

```diff

-  Symbols:   1704
+  Symbols:   1705
Symbols:
+ _swift_release_x26
Functions:
~ -[TCButton collectQuadDataInto:] : 500 -> 496
~ -[TCDirectionPad setThumbstickPos:center:] : 768 -> 760
~ -[TCDirectionPad collectQuadDataInto:] : 2176 -> 2160
~ -[TCSwitch collectQuadDataInto:] : 520 -> 516
~ -[TCThrottle collectQuadDataInto:] : 748 -> 740
~ -[TCThumbstick collectQuadDataInto:] : 808 -> 800
~ -[TCTouchpad collectQuadDataInto:] : 484 -> 480
~ -[_TCGameController init] : 616 -> 640
~ -[_TCGameController addButtonWithLabel:] : 608 -> 604
~ -[_TCGameController addDirectionPadWithLabel:] : 612 -> 608
~ -[TCTouchController setDrawableSize:] : 280 -> 276
~ -[TCTouchController renderUsingRenderCommandEncoder:] : 660 -> 656
~ -[TCTouchController _renderButtonQuadsWithCommandEncoder:] : 1212 -> 1200
~ -[TCTouchController buttons] : 324 -> 320
~ -[TCTouchController switches] : 324 -> 320
~ -[TCTouchController thumbsticks] : 324 -> 320
~ -[TCTouchController directionPads] : 324 -> 320
~ -[TCTouchController throttles] : 324 -> 320
~ -[TCTouchController touchpads] : 324 -> 320
~ -[TCTouchController controlAtPoint:] : 384 -> 380
~ -[TCTouchController automaticallyLayoutControlsForLabels:] : 1256 -> 1252
~ sub_245755d58 -> sub_24683dd00 : 1492 -> 1496
~ sub_245756a04 -> sub_24683e9b0 : 6788 -> 6796
~ sub_245758f1c -> sub_246840ed0 : 9308 -> 9340
~ sub_24575b6cc -> sub_2468436a0 : 280 -> 276
~ sub_24575c100 -> sub_2468440d0 : 364 -> 356
~ sub_24575c26c -> sub_246844234 : 328 -> 332
~ sub_24575c3c4 -> sub_246844390 : 252 -> 276
~ sub_245760250 -> sub_246848234 : 2740 -> 2880
~ sub_245762790 -> sub_24684a800 : 252 -> 276
~ sub_2457628a0 -> sub_24684a928 : 256 -> 276
```
