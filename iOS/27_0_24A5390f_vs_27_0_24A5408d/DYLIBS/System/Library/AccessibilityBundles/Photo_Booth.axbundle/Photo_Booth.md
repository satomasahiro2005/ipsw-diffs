## Photo Booth

> `/System/Library/AccessibilityBundles/Photo Booth.axbundle/Photo Booth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13e4` | `0x1cbc` | **`+0x8d8`** |
| `__AUTH_CONST.__cfstring` | `0x720` | `0x8e0` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x6ce` | `0x7fe` | **`+0x130`** |
| `__TEXT.__objc_methlist` | `0x1e4` | `0x248` | **`+0x64`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c8` | `0x228` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x98` | `0xe8` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `—` | `0x44` | **`+0x44`** |
| `__TEXT.__unwind_info` | `0xe0` | `0x120` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x70` | `0x78` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x18` | `0x20` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 37
-  Symbols:   139
-  CStrings:  72
+  Functions: 50
+  Symbols:   167
+  CStrings:  89
Symbols:
+ +[PBShelfTileAccessibility _accessibilityPerformValidations:]
+ -[PBControllerAccessibility _axInstallPhotoActionLabelBlocks]
+ -[PBControllerAccessibility _axLabelForPhotoActionWithFormatKey:]
+ -[PBControllerAccessibility _axValueForFlipButton]
+ -[PBControllerAccessibility _removeTilesAtIndices:animated:]
+ -[PBShelfTileAccessibility _axIsPhotoSelected]
+ -[PBShelfTileAccessibility accessibilityHint]
+ -[PBShelfTileAccessibility animatePrinting:]
+ GCC_except_table15
+ GCC_except_table19
+ _AXPerformBlockOnMainThreadAfterDelay
+ _UIAccessibilitySpeakAndDoNotBeInterrupted
+ __Unwind_Resume
+ ___42-[PBControllerAccessibility toggleCamera:]_block_invoke
+ ___44-[PBShelfTileAccessibility animatePrinting:]_block_invoke
+ ___61-[PBControllerAccessibility _axInstallPhotoActionLabelBlocks]_block_invoke
+ ___61-[PBControllerAccessibility _axInstallPhotoActionLabelBlocks]_block_invoke_2
+ ___71-[PBControllerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke
+ ___block_descriptor_40_e8_32s_e5_v8?0ls32l8
+ ___block_descriptor_40_e8_32w_e15_"NSString"8?0lw32l8
+ ___objc_personality_v0
+ __dispatch_main_q
+ _dispatch_after
+ _dispatch_time
+ _objc_copyWeak
+ _objc_destroyWeak
+ _objc_initWeak
+ _objc_loadWeakRetained
CStrings:
+ "@\"NSString\"8@?0"
+ "NSMutableArray"
+ "_deleteButton"
+ "_highlightedTile"
+ "_removeTilesAtIndices:animated:"
+ "_shareButton"
+ "_tiles"
+ "animatePrinting:"
+ "camera.chooser.back.value"
+ "camera.chooser.button.label"
+ "camera.chooser.front.value"
+ "delete.photo.label"
+ "isReviewed"
+ "photo.select.hint"
+ "photo.unselect.hint"
+ "share.photo.label"
+ "v8@?0"
```
