## AccessoryMediaLibrary

> `/System/Library/PrivateFrameworks/AccessoryMediaLibrary.framework/AccessoryMediaLibrary`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x141f4` | `0x14164` | **`-0x90`** |

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1
Functions:
~ -[AccessoryMediaLibraryClient availableLibrariesDidChange:] : 484 -> 480
~ -[AccessoryMediaLibraryClient libraryStateDidChange:stateType:enabled:] : 508 -> 504
~ ___73-[ACCMediaLibraryAccessory copyPendingNonContentUpdatesToSendForLibrary:]_block_invoke : 384 -> 380
~ ___78-[ACCMediaLibraryAccessory copyPendingPlaylistContentUpdatesToSendForLibrary:]_block_invoke : 1512 -> 1508
~ ___58-[ACCMediaLibraryAccessory confirmUpdates:revision:count:]_block_invoke : 1784 -> 1792
~ ___67-[ACCMediaLibraryAccessory confirmPlaylistContentUpdates:revision:]_block_invoke : 384 -> 380
~ ___init_logging_modules_block_invoke : 608 -> 588
~ ___59-[ACCMediaLibraryProvider accessoryMediaLibraryAllDetached]_block_invoke : 860 -> 856
~ -[ACCMediaLibraryProvider _notifyRemoteOfAvailableLibraries] : 572 -> 568
~ ___52-[ACCMediaLibraryProvider notifyAvailableLibraries:]_block_invoke : 1044 -> 1036
~ ___init_logging_signpost_modules_block_invoke : 608 -> 588
~ -[ACCMediaLibraryUpdatePlaylistContent initWithMediaLibrary:revision:dict:] : 872 -> 864
~ -[ACCMediaLibraryUpdatePlaylistContent copyContentDictList] : 576 -> 568
~ -[ACCMediaLibraryUpdatePlaylistContent iterateContentItems:] : 296 -> 292
~ -[ACCMediaLibraryUpdatePlaylistContent iterateContentPersistentIDs:] : 304 -> 300
~ _accessoryServer_registerAvailabilityChangedHandlerForServiceEntry : 444 -> 436
~ __SetupAvailabilityChangedHandlerForServiceEntry : 864 -> 852
~ _accessoryServer_unregisterAvailabilityChangedHandlerForServiceEntry : 280 -> 268
~ _accessoryServer_isServerAvailableForServiceEntry : 368 -> 348
```
