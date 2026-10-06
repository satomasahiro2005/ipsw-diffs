## NanoTimeKitCompanion

> `/System/Library/AccessibilityBundles/NanoTimeKitCompanion.axbundle/NanoTimeKitCompanion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__gcc_except_tab` | `0x418` | `0x48c` | **`+0x74`** |
| `__DATA_CONST.__cfstring` | `0x4160` | `0x4140` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x2040` | `0x2060` | **`+0x20`** |
| `__TEXT.__cstring` | `0x37d6` | `0x37b9` | **`-0x1d`** |
| `__TEXT.__objc_methname` | `0x2768` | `0x2785` | **`+0x1d`** |
| `__TEXT.__text` | `0x11ec4` | `0x11ed0` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0xb28` | `0xb30` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1032.0.0.0.0
+1034.0.0.0.0

-  Symbols:   1839
-  CStrings:  969
+  Symbols:   1840
+  CStrings:  968
Symbols:
+ ___block_descriptor_80_e8_32s40s48s56r64r_e5_v8?0lr56l8s32l8s40l8s48l8r64l8
+ _objc_msgSend$_usesColorPickerForEditMode:
- ___block_descriptor_72_e8_32s40s48s56r_e5_v8?0lr56l8s32l8s40l8s48l8
Functions:
~ +[AXNanoTimeKitGlue installNanoTimeKitClasses:] : 832 -> 812
~ __accessibilityValueForKeylineInfo : 1820 -> 1828
~ ____accessibilityValueForKeylineInfo_block_invoke_4 : 60 -> 88
~ ____accessibilityValueForKeylineInfo_block_invoke_5 : 60 -> 56
CStrings:
- "NTKVideoListingAccessibility"
```
