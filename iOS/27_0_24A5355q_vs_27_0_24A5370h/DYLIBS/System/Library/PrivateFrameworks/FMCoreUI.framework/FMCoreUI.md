## FMCoreUI

> `/System/Library/PrivateFrameworks/FMCoreUI.framework/FMCoreUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x172c0` | `0x1725c` | **`-0x64`** |

### Other Changes

```text
Functions:
~ -[FMAppShortcutManager setShortcutItems:] : 564 -> 560
~ -[FMAppShortcutManager setShortcutItem:] : 660 -> 656
~ -[FMAppShortcutManager removeShortcutItemWithIentifier:] : 488 -> 484
~ -[FMMapView removeAnnotations:] : 272 -> 268
~ -[FMMapView isOverlayOnMap:] : 300 -> 296
~ -[FMMapView mapRectForAnnotations:shouldIncludeRadius:] : 900 -> 896
~ -[FMMapView nearbyAnnotations] : 612 -> 608
~ -[FMMapView annotationsSortedByDistance] : 588 -> 584
~ -[FMMapView mapView:didAddAnnotationViews:] : 392 -> 388
~ -[FMMapView depthSortAnnotations] : 852 -> 848
~ -[FMMapGestureRecognizer touchesEnded:withEvent:] : 1620 -> 1616
~ -[FMMapGestureRecognizer finishSwipeGesture:] : 400 -> 396
~ -[FMObservingCell addKVOObservationToken:forObject:] : 596 -> 592
~ -[FMObservingCell removeKVOObservationTokens] : 488 -> 484
~ -[FMObservingCell removeNotificationTokens] : 308 -> 304
~ ___77-[FMAttributedStringRenderer _imageFromTextStorage:width:showExclusionPaths:]_block_invoke : 452 -> 448
~ -[UIView(ISCommonUI) allSubviews] : 340 -> 336
~ -[UIView(ISCommonUI) performOnAllSubviews:] : 280 -> 276
~ -[FMAnnotationView initWithAnnotation:reuseIdentifier:tintColor:] : 2208 -> 2204
~ -[UIViewController(FMCoreUI) addConstraintsToFillSuperview] : 716 -> 708
~ -[FMViewController dealloc] : 420 -> 416
~ -[FMViewController addKVOObservationToken:forObject:] : 596 -> 592
~ -[FMViewController removeKVOObservationTokens] : 584 -> 580
~ -[FMViewController removeNotificationTokens] : 308 -> 304
```
