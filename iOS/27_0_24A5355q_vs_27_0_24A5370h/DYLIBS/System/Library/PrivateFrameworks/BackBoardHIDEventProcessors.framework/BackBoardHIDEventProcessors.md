## BackBoardHIDEventProcessors

> `/System/Library/PrivateFrameworks/BackBoardHIDEventProcessors.framework/BackBoardHIDEventProcessors`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2164` | `0x2148` | **`-0x1c`** |

### Other Changes

```diff

-860.0.1.0.0
+866.0.0.0.0
Functions:
~ -[BKHIDVendorDefinedEventProcessor processEvent:sender:dispatcher:] : 524 -> 520
~ -[BKHIDGameControllerEventProcessor processEvent:sender:dispatcher:] : 452 -> 448
~ -[BKHIDGenericGestureEventProcessor processEvent:sender:dispatcher:] : 1280 -> 1276
~ -[BKHIDGenericGestureEventProcessor serviceDidDisappear:] : 580 -> 576
~ -[BKHIDPointerEventProcessor _dispatchEvent:sender:dispatcher:destinations:] : 352 -> 348
~ -[BKHIDScrollEventProcessor _dispatchEvent:sender:dispatcher:destinations:] : 352 -> 348
~ -[BKHIDBiometricEventProcessor processEvent:sender:dispatcher:] : 480 -> 476
```
