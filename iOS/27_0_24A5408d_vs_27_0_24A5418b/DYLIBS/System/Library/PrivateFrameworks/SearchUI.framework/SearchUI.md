## SearchUI

> `/System/Library/PrivateFrameworks/SearchUI.framework/SearchUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__lazy_helpers` | `0x54` | `0xa8` | **`+0x54`** |
| `__AUTH_CONST.__lazy_load_got` | `0x8` | `0x10` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xa268` | `0xa260` | **`-0x8`** |
| `__TEXT.__text` | `0xf587c` | `0xf5878` | **`-0x4`** |

### Other Changes

```diff

-673.0.12.102.0
+673.0.12.104.0

-  Symbols:   11493
+  Symbols:   11496
Symbols:
+ _PUPhotosFileProviderTypeIdentifierLivePhotoBundle
+ _PUPhotosFileProviderTypeIdentifierLivePhotoBundle$lazyAuthGOT_IA_ad_0
+ _PUPhotosFileProviderTypeIdentifierLivePhotoBundle$lazyLoadStub
Functions:
~ -[SearchUIHomeScreenAppIconView updateCorners] : 112 -> 96
~ -[SearchUIPhotosOneUpController setupOneUpViewWithAssets:] : 564 -> 576
```
