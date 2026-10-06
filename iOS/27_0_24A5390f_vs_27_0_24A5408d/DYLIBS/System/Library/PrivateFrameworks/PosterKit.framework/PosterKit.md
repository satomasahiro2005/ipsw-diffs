## PosterKit

> `/System/Library/PrivateFrameworks/PosterKit.framework/PosterKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1868a0` | `0x187c14` | **`+0x1374`** |
| `__AUTH_CONST.__objc_const` | `0x555e8` | `0x55850` | **`+0x268`** |
| `__TEXT.__objc_methlist` | `0x1a1ec` | `0x1a34c` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x8129` | `0x8229` | **`+0x100`** |
| `__DATA_CONST.__objc_selrefs` | `0xc550` | `0xc5d0` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x62e8` | `0x6330` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x38c0` | `0x38e8` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0xace0` | `0xad00` | **`+0x20`** |
| `__TEXT.__cstring` | `0xb0ef` | `0xb10f` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x1ac8` | `0x1adc` | **`+0x14`** |
| `__DATA.__bss` | `0x40e8` | `0x40f8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1be8` | `0x1bf0` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0xc8` | `0xd0` | **`+0x8`** |

### Other Changes

```diff

-350.1.100.0.0
+355.0.5.0.0

-  Functions: 10566
-  Symbols:   15653
-  CStrings:  2144
+  Functions: 10601
+  Symbols:   15701
+  CStrings:  2148
Symbols:
+ +[PRPosterPathUtilities _setHomeScreenConfigVersionTestProvider:]
+ +[PRPosterPathUtilities homeScreenConfigVersionForPath:]
+ -[PREditingFontAndContentStylePickerViewController _shouldHideFontComponentForCompactTime]
+ -[PREditingFontAndContentStylePickerViewController _updateFontComponentVisibilityForCompactTime]
+ -[PREditingFontAndContentStylePickerViewController fontComponentDivider]
+ -[PREditingFontAndContentStylePickerViewController setFontComponentDivider:]
+ -[PREditingFontPickerComponentViewController resetScrollPosition]
+ -[PREditingLook initWithDisplayName:initialTimeFontConfiguration:initialTitleColor:preferredFrostLevel:]
+ -[PREditingLook initWithIdentifier:displayName:initialTimeFontConfiguration:initialTitleColor:preferredFrostLevel:]
+ -[PREditingLook preferredFrostLevel]
+ -[PREditingLookProperties initWithTimeFontConfiguration:titlePosterColor:preferredFrostLevel:]
+ -[PRImmutableEditingLook initWithIdentifier:displayName:initialTimeFontConfiguration:initialTitleColor:preferredFrostLevel:]
+ -[PRImmutableEditingLookProperties initWithTimeFontConfiguration:titlePosterColor:preferredFrostLevel:]
+ -[PRImmutableEditingLookProperties preferredFrostLevel]
+ -[PRMutableEditingLook initWithIdentifier:displayName:initialTimeFontConfiguration:initialTitleColor:preferredFrostLevel:]
+ -[PRMutableEditingLook preferredFrostLevel]
+ -[PRMutableEditingLook setPreferredFrostLevel:]
+ -[PRMutableEditingLookProperties initWithTimeFontConfiguration:titlePosterColor:preferredFrostLevel:]
+ -[PRMutableEditingLookProperties preferredFrostLevel]
+ -[PRMutableEditingLookProperties setPreferredFrostLevel:]
+ -[PRMutablePosterDescriptor setPreferredFrostLevel:]
+ -[PRPosterConfigurableOptions preferredFrostLevel]
+ -[PRPosterConfigurableOptions setPreferredFrostLevel:]
+ -[PRPosterDescriptor preferredFrostLevel]
+ -[PRPosterWindow .cxx_destruct]
+ -[PRPosterWindow posterRole]
+ -[PRPosterWindow setPosterRole:]
+ -[PRRenderer _adaptiveTimeTopY]
+ -[PRRenderer posterRole]
+ GCC_except_table110
+ GCC_except_table135
+ GCC_except_table136
+ GCC_except_table43
+ GCC_except_table45
+ GCC_except_table71
+ GCC_except_table86
+ GCC_except_table99
+ _OBJC_IVAR_$_PREditingFontAndContentStylePickerViewController._fontComponentDivider
+ _OBJC_IVAR_$_PRImmutableEditingLookProperties._preferredFrostLevel
+ _OBJC_IVAR_$_PRMutableEditingLookProperties._preferredFrostLevel
+ _OBJC_IVAR_$_PRPosterConfigurableOptions._preferredFrostLevel
+ _OBJC_IVAR_$_PRPosterWindow._posterRole
+ _OUTLINED_FUNCTION_48
+ _OUTLINED_FUNCTION_49
+ _OUTLINED_FUNCTION_50
+ _PRClampedPreferredFrostLevel
+ __OBJC_$_INSTANCE_METHODS_PRPosterWindow
+ __OBJC_$_INSTANCE_VARIABLES_PRPosterWindow
+ __OBJC_$_PROP_LIST_PRPosterWindow
+ __OBJC_PROTOCOL_REFERENCE_$_PRPosterContentStyleGlassAppearanceSupporting
+ ___40-[PRRenderer _updateRenderingExtensions]_block_invoke_2
+ ___52-[PRMutablePosterDescriptor setPreferredFrostLevel:]_block_invoke
+ ___60-[PREditingFontAndContentStylePickerViewController loadView]_block_invoke
+ ___block_descriptor_48_e8_32s40s_e23_v32?0"UIView"8Q16^B24ls32l8s40l8
+ __prHomeScreenConfigVersionTestProvider
+ _stat
- -[PRImmutableEditingLookProperties initWithTimeFontConfiguration:titlePosterColor:]
- -[PRMutableEditingLookProperties initWithTimeFontConfiguration:titlePosterColor:]
- GCC_except_table102
- GCC_except_table103
- GCC_except_table29
- GCC_except_table44
- GCC_except_table85
- GCC_except_table97
CStrings:
+ "<PRRenderer %p> Using com.apple.chrono.WidgetRenderer-Snapshots"
+ "<PRRenderer %p> Using default WidgetRenderer"
+ "iconConfigurationFromPosterConfiguration: home-screen-config mtime unstable after %lu attempts for %{public}@; stamping conservative version"
+ "preferredFrostLevel"
```
