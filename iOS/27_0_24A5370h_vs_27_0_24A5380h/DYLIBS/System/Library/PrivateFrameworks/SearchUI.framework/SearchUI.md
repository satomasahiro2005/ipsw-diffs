## SearchUI

> `/System/Library/PrivateFrameworks/SearchUI.framework/SearchUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf3198` | `0xf3c28` | **`+0xa90`** |
| `__TEXT.__const` | `0x3824` | `0x38a4` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0xa198` | `0xa1f0` | **`+0x58`** |
| `__DATA_CONST.__got` | `0x24e8` | `0x2538` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x12208` | `0x12258` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x99c` | `0x9e8` | **`+0x4c`** |
| `__TEXT.__swift5_typeref` | `0x3336` | `0x3378` | **`+0x42`** |
| `__AUTH_CONST.__objc_const` | `0x1dd58` | `0x1dd98` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x2885` | `0x28c5` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x13f8` | `0x1418` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x47e0` | `0x4800` | **`+0x20`** |
| `__DATA.__data` | `0x3430` | `0x3440` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x8b0` | `0x8c0` | **`+0x10`** |
| `__AUTH_CONST.__const` | `0x2a20` | `0x2a28` | **`+0x8`** |
| `__DATA_DIRTY.__objc_data` | `0x1c38` | `0x1c40` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xcd8` | `0xcdc` | **`+0x4`** |
| `__TEXT.__swift5_proto` | `0x144` | `0x148` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x24` | `0x28` | **`+0x4`** |

### Other Changes

```diff

-672.1.0.0.0
+673.0.1.0.0

+  - /System/Library/PrivateFrameworks/Categories.framework/Categories

-  Functions: 6933
-  Symbols:   11396
-  CStrings:  818
+  Functions: 6943
+  Symbols:   11415
+  CStrings:  819
Symbols:
+ +[SearchUIThumbnailViewController applyImageConstraintsToImageView:isCompact:preventThumbnailScaling:usesCompactWidth:isTopHit:]
+ +[SearchUIUtilities bundleIdentifierForDefaultAppToOpenURL:]
+ +[SearchUIUtilities defaultRecordForURL:]
+ +[SearchUIUtilities urlForDefaultAppToOpenURL:]
+ -[SearchUIAppIconImage resolvedBundleIDForCurrentPlatform:]
+ -[SearchUICollectionViewCell _applyIntrinsicContentHeightToAttributes:]
+ -[SearchUICollectionViewCell _shouldUseIntrinsicContentHeight]
+ -[SearchUISwitchAccessoryViewController awaitingTimeoutBlock]
+ -[SearchUISwitchAccessoryViewController setAwaitingTimeoutBlock:]
+ _CTOSPlatformCurrent
+ _CTOSPlatformmacOS
+ _CTOSPlatformtvOS
+ _CTOSPlatformvisionOS
+ _CTOSPlatformwatchOS
+ _OBJC_CLASS_$_CTCategories
+ _OBJC_IVAR_$_SearchUISwitchAccessoryViewController._awaitingTimeoutBlock
+ _SearchUITopHitContentHorizontalInset
+ _SearchUITopHitContentVerticalInset
+ ___54-[SearchUISwitchAccessoryViewController buttonPressed]_block_invoke
+ _instanceIdentifierCodingKey
+ _symbolic $s8SearchUI0A30UIIntrinsicHeightRFCardSectionP
+ _symbolic ______p 8SearchUI0A30UIIntrinsicHeightRFCardSectionP
+ _symbolic ______pSg 8SearchUI0A30UIIntrinsicHeightRFCardSectionP
+ _typeIdentifierCodingKey
- +[SearchUIDefaultPunchoutAppIconImage defaultRecordForURL:]
- +[SearchUIThumbnailViewController applyImageConstraintsToImageView:isCompact:preventThumbnailScaling:usesCompactWidth:]
- __OBJC_$_CLASS_METHODS_SearchUIDefaultPunchoutAppIconImage
- _instanceIdentifier
- _typeIdentifier
CStrings:
+ "Ignoring stale event for BiomeStream (%@) — expected %d, got %d"
```
