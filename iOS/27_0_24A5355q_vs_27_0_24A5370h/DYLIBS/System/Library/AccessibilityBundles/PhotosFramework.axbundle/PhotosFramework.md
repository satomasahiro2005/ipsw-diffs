## PhotosFramework

> `/System/Library/AccessibilityBundles/PhotosFramework.axbundle/PhotosFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ff8` | `0x2144` | **`+0x14c`** |
| `__TEXT.__gcc_except_tab` | `0x14` | `0x54` | **`+0x40`** |
| `__DATA_CONST.__const` | `0xb0` | `0xd8` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x720` | `0x740` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xe0` | `0xf0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x51c` | `0x525` | **`+0x9`** |
| `__DATA_CONST.__objc_selrefs` | `0x2b0` | `0x2b8` | **`+0x8`** |
| `__TEXT.__const` | `0x10` | `0x18` | **`+0x8`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Functions: 36
-  Symbols:   146
-  CStrings:  69
+  Functions: 39
+  Symbols:   155
+  CStrings:  71
Symbols:
+ GCC_except_table14
+ _AXPerformSafeBlock
+ _UIAXStarRatingStringForRating
+ __Block_object_dispose
+ ___42-[PHAssetAccessibility accessibilityLabel]_block_invoke
+ ___Block_byref_object_copy_
+ ___Block_byref_object_dispose_
+ ___block_descriptor_48_e8_32s40r_e5_v8?0ls32l8r40l8
+ _objc_release_x1
CStrings:
+ "q"
+ "rating"
```
