## AppStoreComponents

> `/System/Library/PrivateFrameworks/AppStoreComponents.framework/AppStoreComponents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x90ea8` | `0x90cb4` | **`-0x1f4`** |
| `__TEXT.__oslogstring` | `0x31bd` | `0x3214` | **`+0x57`** |
| `__TEXT.__cstring` | `0x3961` | `0x3921` | **`-0x40`** |
| `__AUTH_CONST.__cfstring` | `0x4d00` | `0x4ce0` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0xfab0` | `0xfa98` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3ed8` | `0x3ef0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x8c54` | `0x8c3c` | **`-0x18`** |
| `__TEXT.__gcc_except_tab` | `0x8e4` | `0x8f0` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0xd48` | `0xd40` | **`-0x8`** |
| `__DATA_CONST.__const` | `0x19e8` | `0x19f0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x918` | `0x920` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2780` | `0x2788` | **`+0x8`** |

### Other Changes

```diff

-27.0.46.2.1
+27.1.7.0.0

-  Functions: 3826
-  Symbols:   5966
+  Functions: 3821
+  Symbols:   5959
Symbols:
+ +[ASCDefaultLockupTheme preferredLabelAlignmentForSize:compatibleWithTraitCollection:]
+ -[ASCMiniProductPageTitleView ageRatingFrameWithSize:atEndOfLineFrame:]
+ -[ASCMiniProductPageTitleView resolveLayoutFittingSize:]
+ -[ASCMiniProductPageTitleView setAgeRatingImage:]
+ -[ASCMiniProductPageTitleView setAgeRatingText:]
+ -[ASCMiniProductPageView setTextAlignment]
+ GCC_except_table46
+ GCC_except_table54
+ _OBJC_CLASS_$_UITraitLayoutDirection
+ ___block_descriptor_40_e8_32r_e30_B16?0"NSTextLayoutFragment"8lr32l8
- +[ASCDefaultLockupTheme preferredLabelAlignmentForSize:]
- -[ASCArtworkView setSemanticContentAttribute:]
- -[ASCLockupContentView onPreferredContentSizeCategoryChange]
- -[ASCLockupContentView setSemanticContentAttribute:]
- -[ASCMiniProductPageTitleView setAgeRatingView:]
- -[ASCOfferButton setSemanticContentAttribute:]
- -[UIView(AppStoreComponents) asc_layoutTraitEnvironment]
- GCC_except_table43
- GCC_except_table45
- GCC_except_table57
- _OUTLINED_FUNCTION_6
- _OUTLINED_FUNCTION_7
- _OUTLINED_FUNCTION_8
- _OUTLINED_FUNCTION_9
- __OBJC_$_PROP_LIST_UIView_$_AppStoreComponents
- ___56-[UIView(AppStoreComponents) asc_layoutTraitEnvironment]_block_invoke
- ___block_descriptor_40_e27_v16?0"<UIMutableTraits>"8l
CStrings:
+ "B16@?0@\"NSTextLayoutFragment\"8"
+ "Current process is not eligible to use %{public}@ lockup view size, keeping %{public}@"
- "Current process is not eligible to use %@ lockup view size"
- "v16@?0@\"<UIMutableTraits>\"8"
```
