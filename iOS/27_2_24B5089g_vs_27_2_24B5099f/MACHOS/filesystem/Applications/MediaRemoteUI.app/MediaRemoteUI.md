## MediaRemoteUI

> `/Applications/MediaRemoteUI.app/MediaRemoteUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x406b0` | `0x41ae4` | **`+0x1434`** |
| `__TEXT.__oslogstring` | `0x1621` | `0x1771` | **`+0x150`** |
| `__TEXT.__objc_stubs` | `0x2c80` | `0x2d20` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0x1930` | `0x1990` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x5dbd` | `0x5e0d` | **`+0x50`** |
| `__DATA.__objc_data` | `0x3b88` | `0x3bc0` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0x7a8` | `0x7e0` | **`+0x38`** |
| `__DATA.__data` | `0x29b0` | `0x29e0` | **`+0x30`** |
| `__DATA.__objc_const` | `0xadc8` | `0xadf8` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0xca8` | `0xcd8` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x2454` | `0x2484` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x1963` | `0x1993` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1040` | `0x1070` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x1250` | `0x1278` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x510` | `0x530` | **`+0x20`** |
| `__TEXT.__const` | `0x20d4` | `0x20f4` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1428` | `0x1448` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x12f0` | `0x1302` | **`+0x12`** |
| `__DATA_CONST.__auth_ptr` | `0x6d0` | `0x6e0` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0xecd` | `0xedd` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1138` | `0x1144` | **`+0xc`** |
| `__TEXT.__objc_methlist` | `0x1ca0` | `0x1ca8` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x7c8` | `0x7cc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4026.200.15.0.0
+4026.200.23.0.0

-  Functions: 1511
-  Symbols:   737
-  CStrings:  1296
+  Functions: 1521
+  Symbols:   749
+  CStrings:  1306
Symbols:
+ _$sSo6UIViewC5UIKitE14ReservedRegionV12QueryOptionsVMa
+ _$sSo6UIViewC5UIKitE14ReservedRegionV12QueryOptionsVMn
+ _$sSo6UIViewC5UIKitE14ReservedRegionV12QueryOptionsVs10SetAlgebraACMc
+ _$sSo6UIViewC5UIKitE14ReservedRegionV4KindV8divisionAGvgZ
+ _$sSo6UIViewC5UIKitE14ReservedRegionV4KindVMa
+ _$sSo6UIViewC5UIKitE14ReservedRegionV5frameSo6CGRectVvg
+ _$sSo6UIViewC5UIKitE14ReservedRegionVMa
+ _$sSo6UIViewC5UIKitE14ReservedRegionVMn
+ _$sSo6UIViewC5UIKitE15reservedRegions4kind7optionsSayAbCE14ReservedRegionVGAH4KindV_AH12QueryOptionsVtF
+ _$sSvN
+ _CGRectGetMidY
+ _OBJC_CLASS_$_CATransaction
+ _UIEdgeInsetsZero
- __UISheetContainerInsets
CStrings:
+ "LockScreenCoordinator - will flip backdrop scene size. backdropScene.screen.bounds=%fx%f backdropScene.effectiveGeometry.interfaceOrientation=%ld"
+ "MediaRemoteUI3"
+ "[CoverSheetBackgroundView] APL %{public}s view: %{public}s artworkTarget: %f backgroundTarget: %f visualizer: %fx%f artwork: %fx%f selfBounds: %fx%f"
+ "[CoverSheetBackgroundView] staticArtworkInsets base: %f contentInsets: %f/%f fold: %f/%f/%f reserved: %f/%f/%f sizeClass: %ld/%ld"
+ "begin"
+ "commit"
+ "filters.MRCAFilterNameAPL."
+ "lastAppliedArtworkAPL"
+ "layoutDirection"
+ "setDisableActions:"
+ "shouldFlipBackdropSceneSize"
- "[CoverSheetBackgroundView] staticArtworkInsets base: %f contentInsets: %f/%f sheet: %f/%f reserved: %f/%f sizeClass: %ld/%ld"
```
