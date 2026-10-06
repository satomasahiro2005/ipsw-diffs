## IconServices

> `/System/Library/PrivateFrameworks/IconServices.framework/IconServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x66840` | `0x666ec` | **`-0x154`** |
| `__AUTH_CONST.__cfstring` | `0x49c0` | `0x49e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x45c3` | `0x45df` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x6a8` | `0x6b0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3178` | `0x3180` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x19d8` | `0x19d0` | **`-0x8`** |

### Other Changes

```diff

-788.0.0.0.0
+792.100.0.0.0

-  Symbols:   4960
-  CStrings:  1076
+  Symbols:   4961
+  CStrings:  1077
Symbols:
+ _OBJC_CLASS_$_IFImageInspector
Functions:
~ _ISShouldSkipCacheForIcon : 156 -> 236
~ _ISIsTransparent : 256 -> 72
~ -[ISIconStackCompositeResource iconStackForSize:scale:] : 292 -> 320
~ -[ISIconStackComposer iconStackForSize:scale:desiredAssetAppearance:designGeneration:returningGenerationReport:] : 4748 -> 4472
~ -[ISIconStackComposer iconStackForSize:scale:desiredAssetAppearance:designGeneration:returningGenerationReport:].cold.2 -> -[ISIconStackComposer iconStackForSize:scale:desiredAssetAppearance:designGeneration:returningGenerationReport:].cold.1 : 64 -> 76
CStrings:
+ "23:13:26"
+ "com.apple.graphic-icon.siri"
- "20:59:25"
```
