## NTKUltraCubeFaceBundleCompanion

> `/System/Library/AccessibilityBundles/NTKUltraCubeFaceBundleCompanion.axbundle/NTKUltraCubeFaceBundleCompanion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__gcc_except_tab` | `0x1f0` | `0x264` | **`+0x74`** |
| `__DATA_CONST.__cfstring` | `0x1aa0` | `0x1a80` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x3e0` | `0x3c0` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0xb60` | `0xb80` | **`+0x20`** |
| `__TEXT.__cstring` | `0x18ae` | `0x1891` | **`-0x1d`** |
| `__TEXT.__objc_methname` | `0xa8b` | `0xaa8` | **`+0x1d`** |
| `__DATA_CONST.__auth_got` | `0x200` | `0x1f0` | **`-0x10`** |
| `__TEXT.__text` | `0x49d8` | `0x49e4` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x350` | `0x358` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1a0` | `0x1a8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1032.0.0.0.0
+1034.0.0.0.0

-  Symbols:   356
-  CStrings:  339
+  Symbols:   355
+  CStrings:  338
Symbols:
+ ___block_descriptor_80_e8_32s40s48s56r64r_e5_v8?0lr56l8s32l8s40l8s48l8r64l8
+ _objc_msgSend$_usesColorPickerForEditMode:
- ___block_descriptor_72_e8_32s40s48s56r_e5_v8?0lr56l8s32l8s40l8s48l8
- _objc_retain_x23
- _objc_retain_x27
Functions:
~ +[AXNanoTimeKitGlue installNanoTimeKitClasses:] : 832 -> 812
~ __accessibilityValueForKeylineInfo : 1820 -> 1828
~ ____accessibilityValueForKeylineInfo_block_invoke_4 : 60 -> 88
~ ____accessibilityValueForKeylineInfo_block_invoke_5 : 60 -> 56
CStrings:
- "NTKVideoListingAccessibility"
```
