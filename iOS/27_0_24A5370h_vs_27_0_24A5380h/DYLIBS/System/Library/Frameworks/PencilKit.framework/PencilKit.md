## PencilKit

> `/System/Library/Frameworks/PencilKit.framework/PencilKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3534ec` | `0x354664` | **`+0x1178`** |
| `__TEXT.__oslogstring` | `0xebad` | `0xed2f` | **`+0x182`** |
| `__TEXT.__gcc_except_tab` | `0x2520c` | `0x25338` | **`+0x12c`** |
| `__DATA.__data` | `0x6cb8` | `0x6d68` | **`+0xb0`** |
| `__AUTH.__objc_data` | `0xa730` | `0xa690` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x1770` | `0x1810` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x8538` | `0x85d0` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x106b0` | `0x10738` | **`+0x88`** |
| `__AUTH_CONST.__objc_const` | `0x48d18` | `0x48d88` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x1eb8` | `0x1f24` | **`+0x6c`** |
| `__TEXT.__objc_methlist` | `0x25f9c` | `0x25fcc` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0xe740` | `0xe720` | **`-0x20`** |
| `__TEXT.__const` | `0x8ec4` | `0x8ee4` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1df8` | `0x1e10` | **`+0x18`** |
| `__DATA.__common` | `0x150` | `0x160` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1a9c` | `0x1aac` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x1ee4` | `0x1ef4` | **`+0x10`** |
| `__DATA.__bss` | `0x7038` | `0x7030` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x2cac` | `0x2cb4` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x13538` | `0x13530` | **`-0x8`** |
| `__DATA_DIRTY.__bss` | `0x7b8` | `0x7c0` | **`+0x8`** |
| `__DATA_DIRTY.__objc_ivar` | `0x1154` | `0x115c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1d8` | `0x1dc` | **`+0x4`** |
| `__TEXT.__cstring` | `0xf917` | `0xf918` | **`+0x1`** |

### Other Changes

```diff

-608.0.0.0.0
+610.100.0.0.0

-  Functions: 18429
-  Symbols:   33036
-  CStrings:  3585
+  Functions: 18446
+  Symbols:   33071
+  CStrings:  3592
Symbols:
+ +[PKRendererVSyncController deviceNameForScreen:]
+ +[PKRendererVSyncController sharedControllerForDeviceName:]
+ +[PKRendererVSyncController sharedControllerForScreen:]
+ -[PKMetalRendererController _updateVSyncController]
+ -[PKMetalRendererController setVSyncDeviceName:]
+ -[PKPaletteContainerView _shouldHideAccessoryView]
+ -[PKPaletteContainerView layoutSubviews]
+ -[PKPaletteHostView _updatePaletteViewLayoutGuideInsets]
+ -[PKPencilShadowView didMoveToWindow]
+ -[PKSelectionView _startWritingToolsWithDictionary:]
+ -[PKTiledCanvasView _updateVSyncController]
+ GCC_except_table286
+ GCC_except_table290
+ GCC_except_table296
+ GCC_except_table299
+ GCC_except_table303
+ GCC_except_table310
+ GCC_except_table313
+ GCC_except_table321
+ GCC_except_table328
+ GCC_except_table332
+ GCC_except_table333
+ GCC_except_table336
+ GCC_except_table340
+ GCC_except_table342
+ GCC_except_table349
+ GCC_except_table352
+ GCC_except_table354
+ GCC_except_table359
+ GCC_except_table366
+ GCC_except_table372
+ GCC_except_table377
+ GCC_except_table381
+ GCC_except_table386
+ GCC_except_table390
+ GCC_except_table394
+ GCC_except_table400
+ GCC_except_table408
+ GCC_except_table478
+ _$s7SwiftUI19UIHostingControllerC5coder8rootViewACyxGSgSo7NSCoderC_xtcfCTq
+ _$s7SwiftUI19UIHostingControllerC5coder8rootViewACyxGSgSo7NSCoderC_xtcfc
+ _$s7SwiftUI19UIHostingControllerC8rootViewACyxGx_tcfCTq
+ _$s9PencilKit23SecureHostingControllerC19_canShowWhileLockedSbyFTo
+ _$s9PencilKit23SecureHostingControllerC5coder8rootViewACyxGSgSo7NSCoderC_xtcfC
+ _$s9PencilKit23SecureHostingControllerC5coder8rootViewACyxGSgSo7NSCoderC_xtcfc
+ _$s9PencilKit23SecureHostingControllerC5coderACyxGSgSo7NSCoderC_tcfc
+ _$s9PencilKit23SecureHostingControllerC5coderACyxGSgSo7NSCoderC_tcfcTo
+ _$s9PencilKit23SecureHostingControllerC8rootViewACyxGx_tcfC
+ _$s9PencilKit23SecureHostingControllerC8rootViewACyxGx_tcfcTf4gn_n
+ _$s9PencilKit23SecureHostingControllerCMF
+ _$s9PencilKit23SecureHostingControllerCMI
+ _$s9PencilKit23SecureHostingControllerCMP
+ _$s9PencilKit23SecureHostingControllerCMa
+ _$s9PencilKit23SecureHostingControllerCMi
+ _$s9PencilKit23SecureHostingControllerCMn
+ _$s9PencilKit23SecureHostingControllerCMo
+ _$s9PencilKit23SecureHostingControllerCMr
+ _$s9PencilKit23SecureHostingControllerCfD
+ _$s9PencilKit23SecureHostingControllerCyAA28PKSqueezePaletteGlassArcView33_E0003CBE58FBC3EFB8AF3A591FBDBD72LLVGMR
+ _$s9PencilKit23SecureHostingControllerCyAA28PKSqueezePaletteGlassArcView33_E0003CBE58FBC3EFB8AF3A591FBDBD72LLVGMd
+ _$s9PencilKit35PKSqueezePaletteGlassBackgroundViewC17hostingController33_E0003CBE58FBC3EFB8AF3A591FBDBD72LLAA013SecureHostingI0CyAA0cde3ArcG0AELLVGSgvpWvd
+ _OBJC_IVAR_$_PKMetalRendererController._currentVSyncController
+ _OBJC_IVAR_$_PKMetalRendererController._vSyncDeviceName
+ _OBJC_IVAR_$_PKRendererVSyncController._deviceName
+ _PKPaletteDockedEdgeMargin
+ __INSTANCE_METHODS__TtC9PencilKit23SecureHostingController
+ __UIMap
+ ___44-[PKPaletteHostView safeAreaInsetsDidChange]_block_invoke_2
+ ___48-[PKMetalRendererController setVSyncDeviceName:]_block_invoke
+ ___48-[PKRendererVSyncController initWithDeviceName:]_block_invoke
+ ___unnamed_4
+ _swift_allocateGenericClassMetadata
+ _swift_initClassMetadata2
+ _symbolic _____ 9PencilKit23SecureHostingControllerC
+ _symbolic _____y_____G 9PencilKit23SecureHostingControllerC AA28PKSqueezePaletteGlassArcView33_E0003CBE58FBC3EFB8AF3A591FBDBD72LLV
+ _symbolic _____y_____GSg 9PencilKit23SecureHostingControllerC AA28PKSqueezePaletteGlassArcView33_E0003CBE58FBC3EFB8AF3A591FBDBD72LLV
+ _symbolic _____yxG 7SwiftUI19UIHostingControllerC
- +[PKRendererVSyncController sharedController]
- -[PKRendererVSyncController init]
- -[PKToolPicker _directionalLayoutMargins]
- -[PKToolPicker _setDirectionalLayoutMargins:]
- GCC_except_table289
- GCC_except_table294
- GCC_except_table297
- GCC_except_table302
- GCC_except_table309
- GCC_except_table311
- GCC_except_table318
- GCC_except_table331
- GCC_except_table334
- GCC_except_table337
- GCC_except_table341
- GCC_except_table344
- GCC_except_table351
- GCC_except_table353
- GCC_except_table357
- GCC_except_table361
- GCC_except_table369
- GCC_except_table376
- GCC_except_table380
- GCC_except_table385
- GCC_except_table389
- GCC_except_table392
- GCC_except_table399
- GCC_except_table406
- GCC_except_table412
- GCC_except_table479
- _$s7SwiftUI19UIHostingControllerCy9PencilKit28PKSqueezePaletteGlassArcView33_E0003CBE58FBC3EFB8AF3A591FBDBD72LLVGMR
- _$s7SwiftUI19UIHostingControllerCy9PencilKit28PKSqueezePaletteGlassArcView33_E0003CBE58FBC3EFB8AF3A591FBDBD72LLVGMd
- _$s9PencilKit35PKSqueezePaletteGlassBackgroundViewC17hostingController33_E0003CBE58FBC3EFB8AF3A591FBDBD72LL7SwiftUI09UIHostingI0CyAA0cde3ArcG0AELLVGSgvpWvd
- _NSStringFromDirectionalEdgeInsets
- _OBJC_IVAR_$_PKToolPicker.__directionalLayoutMargins
- _PKPaletteTopLayoutMarginIgnoringSafeArea
- __ZL13timebase_info
- __ZNSt3__14sortB9foe220106INS_11__wrap_iterIP18AttachmentTileInfoEEZ86-[PKTiledView updateTilesForVisibleRectRendering:offscreen:overrideAdditionalStrokes:]E3$_0EEvT_S6_T0_
- ___33-[PKRendererVSyncController init]_block_invoke
- ___45+[PKRendererVSyncController sharedController]_block_invoke
- _symbolic _____y_____G 7SwiftUI19UIHostingControllerC 9PencilKit28PKSqueezePaletteGlassArcView33_E0003CBE58FBC3EFB8AF3A591FBDBD72LLV
- _symbolic _____y_____GSg 7SwiftUI19UIHostingControllerC 9PencilKit28PKSqueezePaletteGlassArcView33_E0003CBE58FBC3EFB8AF3A591FBDBD72LLV
CStrings:
+ "Adding renderer controller to '%@': %p"
+ "Did configure mobile framebuffer by name: '%@' => %p"
+ "Removing renderer controller from '%@': %p"
+ "Skipping tile generation: non-finite attachment visible rect."
+ "Skipping tile generation: tile span out of range (%ld x %ld)."
+ "Skipping updateTilesForVisibleRectRendering: tileSize=%g frame=%@ zoomScale=%g tileScale=%g scrollBounds=%@"
+ "Tile span: %lu, %lu"
+ "Unable to open mobile framebuffer"
+ "VSync"
+ "_startWritingToolsWithDictionary: - PKSelectionView"
+ "\xf0\xf0\xf0\xf0q\x92"
- "Unable to open primary mobile framebuffer"
- "primary"
- "set directional layout margins to %{public}@"
- "\xf0\xf0\xf0\xf0Q\x82"
```
