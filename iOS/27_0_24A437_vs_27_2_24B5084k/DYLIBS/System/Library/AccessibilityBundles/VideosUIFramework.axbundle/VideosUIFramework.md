## VideosUIFramework

> `/System/Library/AccessibilityBundles/VideosUIFramework.axbundle/VideosUIFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15274` | `0x1536c` | **`+0xf8`** |
| `__TEXT.__cstring` | `0x3beb` | `0x3bbd` | **`-0x2e`** |
| `__AUTH_CONST.__const` | `0x800` | `0x820` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xa28` | `0xa40` | **`+0x18`** |
| `__DATA.__bss` | `0x80` | `0x90` | **`+0x10`** |
| `__TEXT.__ustring` | `0x22` | `0x2c` | **`+0xa`** |

### Other Changes

```diff

-3048.0.0.0.0
+3050.3.0.0.0

-  Functions: 686
-  Symbols:   1821
+  Functions: 687
+  Symbols:   1824
Symbols:
+ GCC_except_table271
+ GCC_except_table277
+ GCC_except_table413
+ GCC_except_table447
+ GCC_except_table578
+ GCC_except_table632
+ ____accessibilityStringByRemovingInvisibleFormatting_block_invoke
+ __accessibilityStringByRemovingInvisibleFormatting.invisibleFormatting
+ __accessibilityStringByRemovingInvisibleFormatting.onceToken_invisibleFormatting
- GCC_except_table269
- GCC_except_table276
- GCC_except_table412
- GCC_except_table446
- GCC_except_table577
- GCC_except_table631
Functions:
~ ___47+[AXVideosUIGlue accessibilityInitializeBundle]_block_invoke_3 : 1372 -> 1352
~ -[AccessibilityNodeAccessibility__VideosUI__SwiftUI accessibilityAttributedLabel] : 500 -> 696
+ ____accessibilityStringByRemovingInvisibleFormatting_block_invoke
CStrings:
+ "\ufeff\u2060\u200b\u00ad"
- "VideosUI_CanonicalBannerInfoViewAccessibility"
```
