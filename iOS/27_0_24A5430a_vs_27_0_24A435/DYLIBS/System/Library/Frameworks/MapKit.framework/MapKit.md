## MapKit

> `/System/Library/Frameworks/MapKit.framework/MapKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28fef0` | `0x28fee8` | **`-0x8`** |

### Other Changes

```text
Functions:
~ -[MKGradientPolylineRenderer drawMapRect:zoomScale:inContext:] : 3912 -> 3908
~ ___64-[MKOverlayView _forEachMapRectForKey:withContext:performBlock:]_block_invoke : 592 -> 596
~ __ZNSt3__16vectorIN2gm6MatrixIdLi2ELi1EEENS_9allocatorIS3_EEE7reserveEm : 180 -> 176
~ __ZNSt3__16vectorIN2gm6MatrixIdLi2ELi1EEENS_9allocatorIS3_EEE24__emplace_back_slow_pathIJRdS8_EEEPS3_DpOT_ : 212 -> 208
~ -[MKAnnotationContainerView _updateClusterableAnnotationViews:withID:] : 1544 -> 1548
~ ___68-[MKOverlayRenderer _forEachMapRectForKey:withContext:performBlock:]_block_invoke : 592 -> 596
~ -[MKTileOverlayRenderer rasterTileProviderForOverlay:] : 644 -> 636
```
