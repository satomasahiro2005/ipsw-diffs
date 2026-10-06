## MusicCarDisplayUI

> `/System/Library/PrivateFrameworks/MusicCarDisplayUI.framework/MusicCarDisplayUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19444` | `0x1940c` | **`-0x38`** |
| `__TEXT.__objc_methlist` | `0x22e0` | `0x22f0` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x4fd0` | `0x4fd8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x3e8` | `0x3e0` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1ba8` | `0x1bb0` | **`+0x8`** |

### Other Changes

```diff

-4026.100.59.0.0
+4026.100.69.0.0

-  Symbols:   1350
+  Symbols:   1349
Symbols:
+ _UIFontWeightSemibold
- _UIFontTextStyleBody
- _UIFontWeightMedium
Functions:
~ _MCDSetChargeOnDescendantsOfView : 316 -> 312
~ _MCDClearTableViewSelection : 288 -> 284
~ __MCDStringFromIndexPath : 372 -> 368
~ -[MCDPlayableContentViewController refreshNavigationStackForLaunch] : 928 -> 924
~ ___50-[MCDPlayableContentViewController _populateStack]_block_invoke_2 : 344 -> 340
~ -[MCDPlayableContentViewController currentStack] : 552 -> 548
~ __MCDCreateMediaRemoteIndexPath : 172 -> 168
~ ___53-[MCDPCModel beginLoadingItemAtIndexPath:completion:]_block_invoke : 508 -> 504
~ ___38-[MCDPCModel itemsFromMRContentItems:]_block_invoke : 848 -> 836
~ -[MCDPCContainer _contentItemsUpdated:] : 1040 -> 1036
~ -[MCDPCContainer _nowPlayingIdentifiersDidChange:] : 1180 -> 1176
~ -[MCDPCContainer showCurrentlyPlayingIndex] : 368 -> 364
~ ___48-[MCDPCContainer getChildrenInRange:completion:]_block_invoke_2 : 764 -> 760
~ _MCDNSIndexPathFromMRMediaRemoteIndexPath : 196 -> 200
```
