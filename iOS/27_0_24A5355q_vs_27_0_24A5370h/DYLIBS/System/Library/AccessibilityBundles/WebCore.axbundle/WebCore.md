## WebCore

> `/System/Library/AccessibilityBundles/WebCore.axbundle/WebCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__objc_selrefs` | `0x1098` | `0x10a8` | **`+0x10`** |
| `__TEXT.__text` | `0x10fcc` | `0x10fdc` | **`+0x10`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0
Functions:
~ -[UIKitWebAccessibilityObjectWrapper _accessibilityResolvedEditingStyles] : 524 -> 520
~ -[UIKitWebAccessibilityObjectWrapper _accessibilityIsDataEmpty:] : 116 -> 124
~ -[UIKitWebAccessibilityObjectWrapper _accessibilityConvertDataArrayToTextMarkerArray:] : 636 -> 632
~ -[UIKitWebAccessibilityObjectWrapper _accessibilityConvertTextMarkersToDataArray:] : 348 -> 344
~ -[UIKitWebAccessibilityObjectWrapper _accessibilityScrollAncestor] : 864 -> 860
~ -[UIKitWebAccessibilityObjectWrapper _accessibilityHeaderElementsForColumn:] : 504 -> 500
~ -[UIKitWebAccessibilityObjectWrapper _accessibilityHeaderElementsForRow:] : 500 -> 496
~ -[UIKitWebAccessibilityObjectWrapper _axBuildDetailsCustomActions:] : 720 -> 716
~ ___64-[UIKitWebAccessibilityObjectWrapper _accessibilityCustomRotor:]_block_invoke : 1004 -> 1032
~ -[UIKitWebAccessibilityObjectWrapper accessibilityCustomRotors] : 1240 -> 1236
~ -[UIKitWebAccessibilityObjectWrapper _performLiveRegionUpdate] : 2584 -> 2560
~ -[UIKitWebAccessibilityObjectWrapper _axDataConvertForNotification:] : 848 -> 840
~ ___67-[UIKitWebAccessibilityObjectWrapper _enqueReorderingNotification:]_block_invoke : 656 -> 652
~ -[UIKitWebAccessibilityObjectWrapper(UIFocusConformance) focusItemsInRect:] : 444 -> 500
~ __processMultiscriptArray : 484 -> 480
~ _AXWebNotificationName : 388 -> 384
```
