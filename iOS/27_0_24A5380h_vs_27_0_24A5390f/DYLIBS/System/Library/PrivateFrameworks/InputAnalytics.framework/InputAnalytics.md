## InputAnalytics

> `/System/Library/PrivateFrameworks/InputAnalytics.framework/InputAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x91e0` | `0x92a0` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x5f22` | `0x5fd2` | **`+0xb0`** |
| `__AUTH_CONST.__objc_intobj` | `0x11a0` | `0x1230` | **`+0x90`** |
| `__TEXT.__text` | `0x1f960` | `0x1f9f0` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x1f48` | `0x1f78` | **`+0x30`** |

### Other Changes

```diff

-145.0.0.0.0
+147.0.0.0.0

-  Symbols:   2650
-  CStrings:  1362
+  Symbols:   2656
+  CStrings:  1368
Symbols:
+ _IASignalImageGenerationLibraryWallpaperEditorAppeared
+ _IASignalImageGenerationLibraryWallpaperSet
+ _IASignalImageGenerationPregeneratedWallpaperEditorAppeared
+ _IASignalImageGenerationPregeneratedWallpaperSet
+ _IASignalImageGenerationUserCreatedWallpaperEditorAppeared
+ _IASignalImageGenerationUserCreatedWallpaperSet
Functions:
~ ___58+[IAImageGenerationAnalytics imageCreationSignalToEnumMap]_block_invoke : 1772 -> 1916
CStrings:
+ "LibraryWallpaperEditorAppeared"
+ "LibraryWallpaperSet"
+ "PregeneratedWallpaperEditorAppeared"
+ "PregeneratedWallpaperSet"
+ "UserCreatedWallpaperEditorAppeared"
+ "UserCreatedWallpaperSet"
```
