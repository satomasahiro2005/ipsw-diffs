## FMFUI

> `/System/Library/PrivateFrameworks/FMFUI.framework/FMFUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10228` | `0x101d4` | **`-0x54`** |

### Other Changes

```text
Functions:
~ +[FMFMapUtilities regionForAnnotations:] : 376 -> 372
~ -[FMFNoLocationView updateLabel] : 804 -> 800
~ -[FMFMapViewController _enablePreloadedHandles:] : 664 -> 660
~ -[FMFMapViewController loadCachedLocationsForHandles] : 520 -> 516
~ -[FMFMapViewController mapHasUserLocations] : 304 -> 300
~ -[FMFMapViewController recenterMap] : 516 -> 512
~ -[FMFMapViewController isLocationAlreadyOnMap:] : 428 -> 424
~ -[FMFMapViewController selectAnnotationIfSingleForMac] : 436 -> 432
~ -[FMFMapViewController deselectAllAnnotations] : 344 -> 340
~ -[FMFMapViewController singleAnnotationOnMap] : 324 -> 320
~ -[FMFMapViewController locationOnMapForHandle:enforceServerId:] : 532 -> 528
~ -[FMFMapViewController sessionContainsHandle:] : 388 -> 384
~ -[FMFMapViewController openInMapsButtonTapped:] : 800 -> 796
~ -[FMFMapViewController stopShowingLocationsForHandles:] : 404 -> 400
~ -[FMFMapViewController removeAllFriendLocationsFromMap] : 416 -> 412
~ ___66-[FMFMapViewController updateAllAnnotationsDueToAddressBookUpdate]_block_invoke : 428 -> 424
~ -[FMFRefreshBarButtonItem addLocation:] : 444 -> 440
~ -[FMFRefreshBarButtonItem removeLocationForHandle:] : 388 -> 384
~ -[FMFRefreshBarButtonItem anyLocationIsUpdating] : 256 -> 252
~ -[FMFMapViewDelegateInternal zoomToFitAnnotationsForMapView:includeMe:duration:] : 1644 -> 1636
```
