## SystemUIDisplayUtilities

> `/System/Library/PrivateFrameworks/SystemUIDisplayUtilities.framework/SystemUIDisplayUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xac18` | `0xabe4` | **`-0x34`** |

### Other Changes

```text
Functions:
~ ___85-[SDUDisplayRegionBlankingCoordinator setBlankingState:ofDisplayRegion:forBundleIDs:]_block_invoke : 324 -> 320
~ ___85-[SDUDisplayRegionBlankingCoordinator setBlankingState:ofDisplayRegion:forBundleIDs:]_block_invoke_2 : 324 -> 320
~ ___82-[SDUDisplayRegionBlankingServiceServer displayRegion:blankingStateWillChange:at:]_block_invoke : 344 -> 340
~ ___81-[SDUDisplayRegionBlankingServiceServer displayRegion:blankingStateDidChange:at:]_block_invoke : 344 -> 340
~ -[SDUDisplayRegionBlankingServiceServer invalidateAllAssertionsForConnection:] : 1020 -> 1012
~ -[SDUDisplayRegionBlankingServiceServer removeConnectionFromAllObserverSets:] : 516 -> 508
~ -[SDUDisplayRegionBlankingService _locked_blankingStateWillChange:forDisplayRegion:at:] : 520 -> 516
~ -[SDUDisplayRegionBlankingService _locked_blankingStateDidChange:forDisplayRegion:at:] : 556 -> 552
~ -[SDUDisplayRegionBlankingService _locked_evaluateInProcessCoordinatorBlankingStateObservation] : 344 -> 340
~ -[SDUDisplayRegionBlankingController dealloc] : 272 -> 268
~ sub_21e759a04 -> sub_21f57a9d4 : 280 -> 276
```
