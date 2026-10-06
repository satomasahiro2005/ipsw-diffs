## PhotosUIFramework

> `/System/Library/AccessibilityBundles/PhotosUIFramework.axbundle/PhotosUIFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14224` | `0x14510` | **`+0x2ec`** |
| `__AUTH_CONST.__cfstring` | `0x4f20` | `0x4ec0` | **`-0x60`** |
| `__TEXT.__cstring` | `0x3b65` | `0x3b32` | **`-0x33`** |
| `__TEXT.__gcc_except_tab` | `0x414` | `0x438` | **`+0x24`** |
| `__AUTH_CONST.__const` | `0x4a0` | `0x4c0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x7c8` | `0x7d8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xea0` | `0xea8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x2154` | `0x215c` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 661
-  Symbols:   1593
-  CStrings:  675
+  Functions: 665
+  Symbols:   1598
+  CStrings:  672
Symbols:
+ -[PUPhotosSharingGridCellAccessibility _axIsSelected]
+ GCC_except_table461
+ GCC_except_table470
+ GCC_except_table504
+ GCC_except_table507
+ GCC_except_table564
+ GCC_except_table649
+ ___53-[PUPhotosSharingGridCellAccessibility _axIsSelected]_block_invoke
+ ___53-[PUPhotosSharingGridCellAccessibility _axIsSelected]_block_invoke_2
+ ___53-[PUPhotosSharingGridCellAccessibility _axIsSelected]_block_invoke_3
- GCC_except_table464
- GCC_except_table496
- GCC_except_table503
- GCC_except_table556
- GCC_except_table645
CStrings:
+ "isItemAtIndexPathSelected:"
- "desiredPlayState"
- "scrubber.paused"
- "scrubber.playing"
- "video.playbackcontrol.label"
```
