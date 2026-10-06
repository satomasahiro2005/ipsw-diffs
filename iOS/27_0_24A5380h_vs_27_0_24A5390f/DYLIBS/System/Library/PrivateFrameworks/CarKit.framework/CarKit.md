## CarKit

> `/System/Library/PrivateFrameworks/CarKit.framework/CarKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x619d0` | `0x61a40` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x10290` | `0x102d8` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x62fc` | `0x632c` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x36e0` | `0x36f8` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x9e8` | `0x9f8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x72c` | `0x730` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-794.0.0.0.0
+797.0.0.0.0

-  Functions: 3038
-  Symbols:   4734
+  Functions: 3041
+  Symbols:   4737
Symbols:
+ -[CRFeatureAvailability deviceSupportedCarPlayFeaturesForThemeAssetID:]
+ -[CRVehicleAccessory setThemeAssetIdentifier:]
+ -[CRVehicleAccessory themeAssetIdentifier]
+ GCC_except_table14
+ GCC_except_table63
+ GCC_except_table71
+ GCC_except_table88
+ _OBJC_IVAR_$_CRVehicleAccessory._themeAssetIdentifier
+ ___71-[CRFeatureAvailability deviceSupportedCarPlayFeaturesForThemeAssetID:]_block_invoke
+ ___71-[CRFeatureAvailability deviceSupportedCarPlayFeaturesForThemeAssetID:]_block_invoke_2
- GCC_except_table17
- GCC_except_table21
- GCC_except_table61
- GCC_except_table69
- GCC_except_table86
- ___55-[CRFeatureAvailability deviceSupportedCarPlayFeatures]_block_invoke
- ___55-[CRFeatureAvailability deviceSupportedCarPlayFeatures]_block_invoke_2
```
