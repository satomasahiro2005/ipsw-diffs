## ACCMediaLibraryFeature

> `/System/Library/PrivateFrameworks/CoreAccessoriesFeatures.framework/XPCServices/ACCMediaLibraryFeature.xpc/ACCMediaLibraryFeature`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a410` | `0x2a520` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x59c6` | `0x5a1b` | **`+0x55`** |
| `__DATA_CONST.__got` | `0x248` | `0x260` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x564` | `0x560` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1196.0.0.502.1
+1203.0.0.0.0

-  CStrings:  1540
+  CStrings:  1541
Functions:
~ ___51-[ACCMediaLibraryShimInfo _sendRadioLibraryUpdates]_block_invoke : 236 -> 244
~ -[ACCMediaLibraryShimInfo dealloc] : 668 -> 656
~ -[ACCMediaLibraryShimInfo stopSendingMediaLibraryUpdates] : 372 -> 456
~ -[ACCMediaLibraryShimInfo confirmMediaLibraryUpdateLastRevision:updateCount:] : 244 -> 256
~ -[ACCMediaLibraryShim _updateSubscribedToAppleMusicStatus:] : 356 -> 336
~ ___74-[ACCMediaLibraryProvider confirmUpdate:library:lastRevision:updateCount:]_block_invoke : 1148 -> 1140
~ ___77-[ACCMediaLibraryProvider confirmPlaylistContentUpdate:library:lastRevision:]_block_invoke : 860 -> 856
~ -[ACCMediaLibraryAccessory confirmUpdates:revision:count:] : 616 -> 612
~ ___58-[ACCMediaLibraryAccessory confirmUpdates:revision:count:]_block_invoke : 1792 -> 2036
~ -[ACCMediaLibraryAccessory confirmPlaylistContentUpdates:revision:] : 436 -> 432
~ -[ACCMediaLibraryFeature confirmUpdate:library:lastRevision:updateCount:] : 184 -> 160
CStrings:
+ "confirmUpdates: %@, library %@, revision %@, drained %lu update(s), waitlist now %lu"
```
