## BridgePreferences

> `/System/Library/PrivateFrameworks/BridgePreferences.framework/BridgePreferences`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x38b1c` | `0x38bc0` | **`+0xa4`** |
| `__AUTH_CONST.__cfstring` | `0x4400` | `0x4420` | **`+0x20`** |
| `__TEXT.__cstring` | `0x4672` | `0x4692` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x3228` | `0x3248` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x29d0` | `0x29e8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x7a0` | `0x7a8` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x318` | `0x310` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xdc8` | `0xdd0` | **`+0x8`** |

### Other Changes

```diff

-1350.1.0.0.0
+1355.0.0.1.0

-  Functions: 1407
-  Symbols:   2535
-  CStrings:  841
+  Functions: 1409
+  Symbols:   2539
+  CStrings:  843
Symbols:
+ -[BPSListController lazyLoadBundle:]
+ -[BPSListController tableView:estimatedHeightForRowAtIndexPath:]
+ -[BPSRemoteWatchView _screenImageForSize:scale:]
+ -[BPSWatchMigrationController captionText]
+ _UITableViewAutomaticDimension
- -[BPSRemoteWatchView _imageForSize:]
CStrings:
+ "BIXBY_CAPTION_TEXT"
+ "SwiftUI"
```
