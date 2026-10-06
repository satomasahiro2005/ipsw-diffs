## WatchQuickActionsServices

> `/System/Library/PrivateFrameworks/WatchQuickActionsServices.framework/WatchQuickActionsServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xad8c` | `0xad20` | **`-0x6c`** |

### Other Changes

```diff

-191.0.0.0.0
+192.0.0.0.0

-  Symbols:   620
+  Symbols:   619
Symbols:
- _objc_retain_x27
Functions:
~ _wqa_dump_call_stack : 500 -> 496
~ -[WQAOverlayCoordinator refreshOverlaysIfNecessary] : 944 -> 940
~ -[WQAOverlayCoordinator _shouldShowHintsForQuickActions:] : 448 -> 444
~ ___58-[WQAOverlayCoordinator _mainQueue_showUIForQuickActions:]_block_invoke.417 -> ___58-[WQAOverlayCoordinator _mainQueue_showUIForQuickActions:]_block_invoke.438 : 260 -> 256
~ -[WQAOverlayCoordinator _mainQueue_showHintsWithPrimaryQuickActions:completion:] : 1468 -> 1452
~ ___80-[WQAOverlayCoordinator _mainQueue_showHintsWithPrimaryQuickActions:completion:]_block_invoke : 712 -> 708
~ ___80-[WQAOverlayCoordinator _mainQueue_showHintsWithPrimaryQuickActions:completion:]_block_invoke_2 : 428 -> 420
~ ___80-[WQAOverlayCoordinator _mainQueue_showHintsWithPrimaryQuickActions:completion:]_block_invoke_4 : 428 -> 420
~ ___80-[WQAOverlayCoordinator _mainQueue_showHintsWithPrimaryQuickActions:completion:]_block_invoke_6 : 428 -> 420
~ ___80-[WQAOverlayCoordinator _mainQueue_showHintsWithPrimaryQuickActions:completion:]_block_invoke_8 : 428 -> 420
~ ___80-[WQAOverlayCoordinator _mainQueue_showHintsWithPrimaryQuickActions:completion:]_block_invoke.431 -> ___80-[WQAOverlayCoordinator _mainQueue_showHintsWithPrimaryQuickActions:completion:]_block_invoke.452 : 420 -> 416
~ -[WQAOverlayCoordinator _mainQueue_cleanupHintViews] : 324 -> 320
~ -[WQAOverlayCoordinator _mainQueue_cleanupShapeLayers] : 640 -> 632
~ -[WatchQuickActionsServices _handleAppDidBecomeActiveNotification] : 1032 -> 1028
~ -[WatchQuickActionsServices registerQuickActions:startupCallback:] : 872 -> 868
~ ___66-[WatchQuickActionsServices registerQuickActions:startupCallback:]_block_invoke.513 -> ___66-[WatchQuickActionsServices registerQuickActions:startupCallback:]_block_invoke.534 : 276 -> 272
~ ___70-[WatchQuickActionsServices _local_removeQuickActionsWithIdentifiers:]_block_invoke : 592 -> 584
~ ___63-[WatchQuickActionsServices _retrieveQuickActionForIdentifier:]_block_invoke : 320 -> 316
```
