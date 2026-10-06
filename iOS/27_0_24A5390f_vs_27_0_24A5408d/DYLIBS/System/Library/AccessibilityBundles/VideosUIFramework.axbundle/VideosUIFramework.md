## VideosUIFramework

> `/System/Library/AccessibilityBundles/VideosUIFramework.axbundle/VideosUIFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15104` | `0x15274` | **`+0x170`** |
| `__TEXT.__objc_methlist` | `0x21bc` | `0x21fc` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0x48a0` | `0x48c0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x848` | `0x858` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x1f8` | `0x200` | **`+0x8`** |
| `__TEXT.__cstring` | `0x3bec` | `0x3beb` | **`-0x1`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 682
-  Symbols:   1817
-  CStrings:  665
+  Functions: 686
+  Symbols:   1821
+  CStrings:  666
Symbols:
+ -[VUIUpNextButtonAccessibility _axIsWatchListed]
+ -[VUIUpNextButtonAccessibility accessibilityHint]
+ -[VideosUI_FocusableTextViewAccessibility _accessibilityIsMoreLabelVisible]
+ -[VideosUI_FocusableTextViewAccessibility accessibilityActivationPoint]
+ -[VideosUI_FocusableTextViewAccessibility accessibilityHint]
+ -[VideosUI_FocusableTextViewAccessibility isAccessibilityElement]
+ GCC_except_table161
+ GCC_except_table197
+ GCC_except_table208
+ GCC_except_table236
+ GCC_except_table269
+ GCC_except_table270
+ GCC_except_table276
+ GCC_except_table412
+ GCC_except_table446
+ GCC_except_table577
+ GCC_except_table631
- -[PaginatedMediaMetadataContainerView_MediaShowcasingMetadataViewAccessibility _axContainedInCatchUpToLiveViewController]
- GCC_except_table163
- GCC_except_table199
- GCC_except_table210
- GCC_except_table238
- GCC_except_table271
- GCC_except_table272
- GCC_except_table278
- GCC_except_table410
- GCC_except_table444
- GCC_except_table575
- GCC_except_table627
- ___121-[PaginatedMediaMetadataContainerView_MediaShowcasingMetadataViewAccessibility _axContainedInCatchUpToLiveViewController]_block_invoke
CStrings:
+ "upnext.hint.add"
+ "upnext.hint.remove"
+ "upnext.state.added"
+ "upnext.state.removed"
- "VideosUI.CatchUpToLiveViewController"
- "upnext.button.add"
- "upnext.button.remove"
```
