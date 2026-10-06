## PosterBoardFramework

> `/System/Library/AccessibilityBundles/PosterBoardFramework.axbundle/PosterBoardFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5d30` | `0x5f34` | **`+0x204`** |
| `__TEXT.__oslogstring` | `—` | `0x1ea` | **`+0x1ea`** |
| `__TEXT.__const` | `0x40` | `0x50` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x78` | `0x80` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x290` | `0x298` | **`+0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Symbols:   528
-  CStrings:  206
+  Symbols:   534
+  CStrings:  209
Symbols:
+ _AXAIWhiteGloveLoggingEnabled
+ _AXLogCommon
+ _NSStringFromClass
+ __os_log_error_impl
+ __os_log_impl
+ _os_log_type_enabled
Functions:
~ -[PBFPosterGalleryPreviewCellAccessibility accessibilityLabel] : 388 -> 620
~ -[PosterGalleryAffordanceCollectionViewCellAccessibility accessibilityLabel] : 12 -> 296
CStrings:
+ "rdar://168563356 PBFPosterGalleryPreviewCell accessibilityLabel default-fallback previewIdentifier=%{public}@ label=%{public}@ (no posterTitle, no accessibilityValue)"
+ "rdar://168563356 PBFPosterGalleryPreviewCell accessibilityLabel enter previewIdentifier=%{public}@ posterTitle=%{public}@ mappedLabel=%{public}@ superValue=%{public}@"
+ "rdar://168563356 PosterGalleryAffordanceCollectionViewCell accessibilityLabel class=%{public}@ identifier=%{public}@ label=%{public}@ superLabel=%{public}@"
```
