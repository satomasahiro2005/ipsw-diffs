## UserNotificationsUIKit

> `/System/Library/PrivateFrameworks/UserNotificationsUIKit.framework/UserNotificationsUIKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bd718` | `0x1bddd8` | **`+0x6c0`** |
| `__TEXT.__objc_methlist` | `0x1ac5c` | `0x1acdc` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0xcb60` | `0xcbb8` | **`+0x58`** |
| `__AUTH_CONST.__const` | `0x4e08` | `0x4e28` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x2d54` | `0x2d38` | **`-0x1c`** |
| `__TEXT.__unwind_info` | `0x73a8` | `0x73c0` | **`+0x18`** |
| `__DATA.__bss` | `0x14d8` | `0x14e8` | **`+0x10`** |
| `__TEXT.__const` | `0x43d4` | `0x43e4` | **`+0x10`** |

### Other Changes

```diff

-1076.1.0.0.0
+1077.0.1.0.0

-  Functions: 10909
-  Symbols:   14419
+  Functions: 10922
+  Symbols:   14431
Symbols:
+ +[NCFullScreenStagingBannerView _verticalDetailSecondaryFont]
+ -[NCFullScreenStagingBannerView _detailIconTargetCenterForBounds:]
+ -[NCFullScreenStagingBannerView _detailPrimaryLabelFont]
+ -[NCFullScreenStagingBannerView _detailScrollViewFrameForBounds:contentWidth:contentHeight:]
+ -[NCFullScreenStagingBannerView _detailSecondaryLabelFont]
+ -[NCFullScreenStagingBannerView _detailThumbnailFrameForBounds:scrollViewFrame:]
+ -[NCFullScreenStagingBannerView _grabberFrameForBounds:scale:]
+ -[NCFullScreenStagingBannerView _requiresAlternativeGrabberPlacement:]
+ -[NCFullScreenStagingBannerView _requiresVerticalLayoutFromBounds:]
+ -[NCFullScreenStagingBannerView _verticalDetailHorizontalInsets]
+ -[NCFullScreenStagingBannerView _verticalDetailIconRowHeight]
+ GCC_except_table61
+ GCC_except_table82
+ ___61+[NCFullScreenStagingBannerView _verticalDetailSecondaryFont]_block_invoke
+ __verticalDetailSecondaryFont._verticalDetailSecondaryFont
+ __verticalDetailSecondaryFont.onceToken
- GCC_except_table111
- GCC_except_table49
- GCC_except_table67
- GCC_except_table78
```
