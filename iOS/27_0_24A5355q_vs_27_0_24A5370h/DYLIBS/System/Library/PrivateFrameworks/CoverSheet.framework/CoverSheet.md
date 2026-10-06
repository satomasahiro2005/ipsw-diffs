## CoverSheet

> `/System/Library/PrivateFrameworks/CoverSheet.framework/CoverSheet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18bc18` | `0x18c2f4` | **`+0x6dc`** |
| `__AUTH_CONST.__objc_const` | `0x3c460` | `0x3c670` | **`+0x210`** |
| `__TEXT.__objc_methlist` | `0x162d4` | `0x16444` | **`+0x170`** |
| `__DATA_CONST.__objc_selrefs` | `0xc548` | `0xc618` | **`+0xd0`** |
| `__TEXT.__cstring` | `0xc96a` | `0xc9ec` | **`+0x82`** |
| `__DATA.__data` | `0x5618` | `0x5678` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x12c0` | `0x1310` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x8e3a` | `0x8e7c` | **`+0x42`** |
| `__TEXT.__unwind_info` | `0x47f0` | `0x4830` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x4080` | `0x40a8` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x1264` | `0x127c` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x1b80` | `0x1b90` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1578` | `0x1588` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x7a8` | `0x7b0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x668` | `0x670` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x5e8` | `0x5f0` | **`+0x8`** |

### Other Changes

```diff

-146.0.1.0.0
+149.0.0.0.0

-  Functions: 7893
-  Symbols:   13979
-  CStrings:  2646
+  Functions: 7924
+  Symbols:   14029
+  CStrings:  2650
Symbols:
+ +[CSContentCutoutBoundsCalculator contentCutoutBoundsForInterfaceOrientation:deviceConfiguration:]
+ +[CSContentCutoutBoundsCalculator contentCutoutBoundsForInterfaceOrientation:screen:]
+ +[CSContentCutoutBoundsCalculator contentCutoutBoundsForInterfaceOrientation:windowScene:]
+ +[CSContentCutoutBoundsCalculator contentCutoutBoundsForOrientation:deviceConfiguration:]
+ +[CSContentCutoutBoundsCalculator contentCutoutBoundsForOrientation:screen:]
+ +[CSContentCutoutBoundsCalculator contentCutoutBoundsForOrientation:windowScene:]
+ +[CSContentCutoutBoundsCalculator modalContentCutoutBoundsForInterfaceOrientation:deviceConfiguration:]
+ +[CSContentCutoutBoundsCalculator modalContentCutoutBoundsForInterfaceOrientation:screen:]
+ +[CSContentCutoutBoundsCalculator modalContentCutoutBoundsForInterfaceOrientation:windowScene:]
+ +[CSContentCutoutBoundsCalculator modalContentCutoutBoundsForOrientation:deviceConfiguration:]
+ +[CSContentCutoutBoundsCalculator modalContentCutoutBoundsForOrientation:screen:]
+ +[CSContentCutoutBoundsCalculator modalContentCutoutBoundsForOrientation:windowScene:]
+ +[CSContentCutoutBoundsCalculator modalNormalizedContentCutoutBoundsForOrientation:deviceConfiguration:]
+ +[CSContentCutoutBoundsCalculator modalNormalizedContentCutoutBoundsForOrientation:screen:]
+ +[CSContentCutoutBoundsCalculator modalNormalizedContentCutoutBoundsForOrientation:windowScene:]
+ +[CSContentCutoutBoundsCalculator normalizedContentCutoutBoundsForOrientation:deviceConfiguration:]
+ +[CSContentCutoutBoundsCalculator normalizedContentCutoutBoundsForOrientation:screen:]
+ +[CSContentCutoutBoundsCalculator normalizedContentCutoutBoundsForOrientation:windowScene:]
+ -[CSCoverSheetView setBackgroundRestorationPaused:]
+ -[CSCoverSheetViewController _setLockScreenContentsAlphaForCoverSheetTransition:forPresentationValue:]
+ -[CSCoverSheetViewController acquireExternalWallpaperOverlayHostingAssertion]
+ -[CSCoverSheetViewController activeExternalWallpaperOverlayHostingAssertion]
+ -[CSCoverSheetViewController setActiveExternalWallpaperOverlayHostingAssertion:]
+ -[_CSExternalWallpaperOverlayHostingAssertion .cxx_destruct]
+ -[_CSExternalWallpaperOverlayHostingAssertion dealloc]
+ -[_CSExternalWallpaperOverlayHostingAssertion initWithViews:reclaimBlock:]
+ -[_CSExternalWallpaperOverlayHostingAssertion invalidate]
+ -[_CSExternalWallpaperOverlayHostingAssertion views]
+ GCC_except_table10
+ GCC_except_table104
+ GCC_except_table195
+ GCC_except_table235
+ GCC_except_table356
+ GCC_except_table419
+ GCC_except_table429
+ GCC_except_table433
+ GCC_except_table511
+ GCC_except_table575
+ GCC_except_table595
+ GCC_except_table606
+ GCC_except_table688
+ GCC_except_table752
+ GCC_except_table762
+ GCC_except_table764
+ GCC_except_table773
+ GCC_except_table787
+ GCC_except_table798
+ GCC_except_table835
+ _OBJC_CLASS_$__CSExternalWallpaperOverlayHostingAssertion
+ _OBJC_IVAR_$_CSCoverSheetView._backgroundRestorationPaused
+ _OBJC_IVAR_$_CSCoverSheetViewController._activeExternalWallpaperOverlayHostingAssertion
+ _OBJC_IVAR_$__CSExternalWallpaperOverlayHostingAssertion._reclaimBlock
+ _OBJC_IVAR_$__CSExternalWallpaperOverlayHostingAssertion._views
+ _OBJC_METACLASS_$__CSExternalWallpaperOverlayHostingAssertion
+ __OBJC_$_INSTANCE_METHODS__CSExternalWallpaperOverlayHostingAssertion
+ __OBJC_$_INSTANCE_VARIABLES__CSExternalWallpaperOverlayHostingAssertion
+ __OBJC_$_PROP_LIST_CSExternalWallpaperOverlayHostingAssertion
+ __OBJC_$_PROP_LIST__CSExternalWallpaperOverlayHostingAssertion
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CSExternalWallpaperOverlayHostingAssertion
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CSExternalWallpaperOverlayHostingAssertion
+ __OBJC_$_PROTOCOL_REFS_CSExternalWallpaperOverlayHostingAssertion
+ __OBJC_CLASS_PROTOCOLS_$__CSExternalWallpaperOverlayHostingAssertion
+ __OBJC_CLASS_RO_$__CSExternalWallpaperOverlayHostingAssertion
+ __OBJC_LABEL_PROTOCOL_$_CSExternalWallpaperOverlayHostingAssertion
+ __OBJC_METACLASS_RO_$__CSExternalWallpaperOverlayHostingAssertion
+ __OBJC_PROTOCOL_$_CSExternalWallpaperOverlayHostingAssertion
+ ___77-[CSCoverSheetViewController acquireExternalWallpaperOverlayHostingAssertion]_block_invoke
+ ___block_descriptor_88_e8_32s40s48s56s64w_e5_v8?0ls32l8s40l8s48l8s56l8w64l8
+ _kCAFilterInputBackdropAware
- GCC_except_table190
- GCC_except_table230
- GCC_except_table351
- GCC_except_table414
- GCC_except_table423
- GCC_except_table427
- GCC_except_table505
- GCC_except_table569
- GCC_except_table589
- GCC_except_table600
- GCC_except_table682
- GCC_except_table746
- GCC_except_table756
- GCC_except_table758
- GCC_except_table767
- GCC_except_table781
- GCC_except_table792
- GCC_except_table99
- _OUTLINED_FUNCTION_101
CStrings:
+ "%s:%spid:%d,%s:%s%s%s%s%s%u:%s cccurve25519 failed: small-order point used%s\n"
+ "CornerPocket"
+ "External wallpaper overlay hosting assertion already outstanding."
+ "generate_wrapping_key_curve25519"
+ "\xf0\xf0R\xf0\xf0\xf0\xa1"
- "\xf0\xf0B\xf0\xf0\xf0\xa1"
```
