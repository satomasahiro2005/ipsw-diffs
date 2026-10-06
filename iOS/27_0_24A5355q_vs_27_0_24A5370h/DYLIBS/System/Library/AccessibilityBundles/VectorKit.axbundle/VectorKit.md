## VectorKit

> `/System/Library/AccessibilityBundles/VectorKit.axbundle/VectorKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x27bf0` | `0x27b20` | **`-0xd0`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0
Functions:
~ -[VKToneGenerator configurePlayerWithPitchFactor:leftBalance:rightBalance:volume:loop:] : 1088 -> 1084
~ _AXVKAccessibilityPaths : 660 -> 652
~ _AXVKAccessibilityPoints : 608 -> 604
~ -[VKExplorationAccessibilityElement accessibilityPaths] : 892 -> 888
~ -[AXVKExplorationVertexElement connectingRoadWith:] : 592 -> 596
~ -[AXVKExplorationVertexElement accessibilityLabel] : 576 -> 572
~ -[AXVKExplorationVertexElement description] : 564 -> 560
~ -[VKFeatureAccessibilityElement addFeaturesFromElement:] : 372 -> 368
~ -[VKFeatureAccessibilityElement pointInside:] : 356 -> 352
~ -[VKFeatureAccessibilityElement _mergePaths] : 456 -> 452
~ -[VKRoadFeatureAccessibilityElement _updatePath] : 3088 -> 3080
~ -[VKRoadFeatureAccessibilityElement consolidatedAndOrderedFeatures] : 756 -> 752
~ -[VKRoadFeatureAccessibilityElement consolidatedAndOrderedFeaturesFromAllFeaturePoints:] : 1192 -> 1196
~ -[VKRoadFeatureAccessibilityElement accessibilityViableIntersectorsForPoint:fromSortedArray:isStart:] : 864 -> 860
~ -[VKRoadFeatureAccessibilityElement _accessibilityRoadContainsTrackingPoint:] : 560 -> 552
~ -[VKRoadFeatureAccessibilityElement _roadLength] : 876 -> 872
~ -[VKRoadFeatureAccessibilityElement pointInside:] : 384 -> 380
~ -[VKRoadFeatureAccessibilityElement _nearestIntersectionForPoint:] : 728 -> 724
~ ___62-[VKRoadFeatureAccessibilityElement _roadDirectionDescription]_block_invoke.720 -> ___62-[VKRoadFeatureAccessibilityElement _roadDirectionDescription]_block_invoke.726 : 820 -> 816
~ -[VKMultiSectionFeatureAccessibilityElement _updatePath] : 944 -> 940
~ -[VKMapDebugView addIntersectionPoints:] : 344 -> 340
~ -[VKMapDebugView _addValidPaths:array:] : 448 -> 444
~ -[VKMapDebugView drawRect:] : 3992 -> 3964
~ -[VKMapViewAccessibility accessibilityElements] : 1396 -> 1392
~ -[VKMapViewAccessibility _axIntersectionBetweenRoad:andOtherRoad:] : 792 -> 788
~ -[VKMapViewAccessibility accessibilityUpcomingRoadsForPoint:forAngle:withElement:] : 1960 -> 1952
~ -[VKMapViewAccessibility _axSummaryForVisibleBounds] : 1960 -> 1956
~ -[VKMapViewAccessibility _axStartListeningForMapAccessibilityEnabled] : 424 -> 420
~ -[VKMapViewTourGuideManager _elementIntersectsElement:point:radius:] : 752 -> 744
~ -[VKMapViewAccessibilityElementManager _descriptionForTransitNodeLabel:] : 1080 -> 1076
~ -[VKMapViewAccessibilityElementManager _descriptionForTransitLineLabel:] : 704 -> 700
~ -[VKMapViewAccessibilityElementManager _descriptionForRouteTransitNodeLabel:] : 1016 -> 1012
~ -[VKMapViewAccessibilityElementManager _accessibilityElementsForMapView:mapViewBounds:visibleLabels:visibleTiles:existingElements:] : 1420 -> 1412
~ ___131-[VKMapViewAccessibilityElementManager _accessibilityElementsForMapView:mapViewBounds:visibleLabels:visibleTiles:existingElements:]_block_invoke : 4404 -> 4400
~ -[VKMapViewAccessibilityElementManager _filterAccessibilityElements:zoomLevel:mapView:] : 1496 -> 1492
~ -[VKMapViewAccessibilityElementManager roadHasMapAncestor:inWindow:] : 532 -> 528
~ -[VKMapViewAccessibilityElementManager accessibilityMapsExplorationBeginFromLocationCoordinate:] : 1356 -> 1352
~ -[VKMapViewAccessibilityElementManager accessibilityMapsExplorationBeginFromRoad:] : 916 -> 912
~ -[VKMapViewAccessibilityElementManager addNeighborsAsRelevantFeaturesForVertex:] : 488 -> 484
~ -[VKMapViewAccessibilityElementManager computeVertex:] : 1596 -> 1592
~ -[VKMapViewAccessibilityElementManager roadElementForFeatureWrapper:] : 688 -> 684
~ -[VKMapViewAccessibilityElementManager accessibilityMapsExplorationCurrentRoadsWithAngles] : 1560 -> 1552
~ -[VKMapViewAccessibilityElementManager edgeBetweenVertex:andVertex:] : 580 -> 584
~ -[VKMapViewAccessibilityElementManager accessibilityVisiblePOIsBetweenPoint:andPoint:onRoad:] : 1468 -> 1464
~ -[VKPitchGenerator initWithPitchMode:minDepth:maxDepth:minPtich:maxPitch:twoPitchesThreshold:fourPitchesThresholdArray:] : 456 -> 452
```
