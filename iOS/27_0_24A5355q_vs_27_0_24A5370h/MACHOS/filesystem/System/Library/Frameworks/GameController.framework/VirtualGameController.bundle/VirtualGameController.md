## VirtualGameController

> `/System/Library/Frameworks/GameController.framework/VirtualGameController.bundle/VirtualGameController`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7214` | `0x7220` | **`+0xc`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-14.0.14.0.0
+14.0.17.0.0
Functions:
~ _GCVirtualControllerCreateAlphaMaskImage : 364 -> 376
~ ___GCAnalyticsSendVirtualControllerConnectedEvent_block_invoke : 632 -> 624
~ -[GCControllerButtonInputView setCustomImage:] : 1284 -> 1280
~ -[GCTouchController initWithConfiguration:] : 2004 -> 2020
~ -[_GCVirtualControllerImpl findKeyWindow] : 348 -> 344
```
