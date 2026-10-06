## Podcasts

> `/System/Library/AccessibilityBundles/Podcasts.axbundle/Podcasts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f74` | `0x7c64` | **`-0x310`** |
| `__AUTH_CONST.__objc_const` | `0x3998` | `0x3878` | **`-0x120`** |
| `__TEXT.__cstring` | `0x1d94` | `0x1cf2` | **`-0xa2`** |
| `__AUTH_CONST.__cfstring` | `0x25a0` | `0x2500` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x1c70` | `0x1bd0` | **`-0xa0`** |
| `__TEXT.__objc_methlist` | `0x132c` | `0x12cc` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x1e8` | `0x1c0` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0x410` | `0x3f8` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x318` | `0x308` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x538` | `0x530` | **`-0x8`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 314
-  Symbols:   947
-  CStrings:  327
+  Functions: 306
+  Symbols:   928
+  CStrings:  322
Symbols:
+ GCC_except_table112
+ GCC_except_table139
+ GCC_except_table160
+ GCC_except_table184
+ GCC_except_table211
+ GCC_except_table269
+ GCC_except_table297
+ GCC_except_table59
+ GCC_except_table62
+ GCC_except_table73
+ GCC_except_table77
- +[NowPlayingEpisodeUpsellBannerViewAccessibility _accessibilityPerformValidations:]
- +[NowPlayingEpisodeUpsellBannerViewAccessibility(SafeCategory) safeCategoryBaseClass]
- +[NowPlayingEpisodeUpsellBannerViewAccessibility(SafeCategory) safeCategoryTargetClassName]
- -[NowPlayingEpisodeUpsellBannerViewAccessibility accessibilityCustomActions]
- -[NowPlayingEpisodeUpsellBannerViewAccessibility accessibilityLabel]
- -[NowPlayingEpisodeUpsellBannerViewAccessibility isAccessibilityElement]
- GCC_except_table120
- GCC_except_table147
- GCC_except_table168
- GCC_except_table192
- GCC_except_table219
- GCC_except_table277
- GCC_except_table305
- GCC_except_table67
- GCC_except_table70
- GCC_except_table81
- GCC_except_table85
- _OBJC_CLASS_$_NowPlayingEpisodeUpsellBannerViewAccessibility
- _OBJC_CLASS_$___NowPlayingEpisodeUpsellBannerViewAccessibility_super
- _OBJC_METACLASS_$_NowPlayingEpisodeUpsellBannerViewAccessibility
- _OBJC_METACLASS_$___NowPlayingEpisodeUpsellBannerViewAccessibility_super
- __OBJC_$_CLASS_METHODS_NowPlayingEpisodeUpsellBannerViewAccessibility(SafeCategory)
- __OBJC_$_INSTANCE_METHODS_NowPlayingEpisodeUpsellBannerViewAccessibility
- __OBJC_CLASS_RO_$_NowPlayingEpisodeUpsellBannerViewAccessibility
- __OBJC_CLASS_RO_$___NowPlayingEpisodeUpsellBannerViewAccessibility_super
- __OBJC_METACLASS_RO_$_NowPlayingEpisodeUpsellBannerViewAccessibility
- __OBJC_METACLASS_RO_$___NowPlayingEpisodeUpsellBannerViewAccessibility_super
- ___76-[NowPlayingEpisodeUpsellBannerViewAccessibility accessibilityCustomActions]_block_invoke
- ___76-[NowPlayingEpisodeUpsellBannerViewAccessibility accessibilityCustomActions]_block_invoke_2
- ___block_descriptor_40_e8_32s_e5_v8?0ls32l8
CStrings:
- "NowPlayingEpisodeUpsellBannerViewAccessibility"
- "NowPlayingUI.NowPlayingEpisodeUpsellBannerView"
- "PodcastsUI.EpisodeUpsellBannerView"
- "closeButtonTapped"
- "dismiss.button"
```
