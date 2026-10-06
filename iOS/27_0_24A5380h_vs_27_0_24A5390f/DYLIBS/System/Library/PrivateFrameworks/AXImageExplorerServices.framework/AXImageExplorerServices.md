## AXImageExplorerServices

> `/System/Library/PrivateFrameworks/AXImageExplorerServices.framework/AXImageExplorerServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9204` | `0x95d8` | **`+0x3d4`** |
| `__TEXT.__cstring` | `0x3ee` | `0x45e` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x3b3` | `0x3c3` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x450` | `0x458` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1a8` | `0x1b0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2f8` | `0x300` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-3234.5.0.0.0
+3237.1.0.0.0

+  - /System/Library/PrivateFrameworks/MediaExperience.framework/MediaExperience

-  Functions: 239
-  Symbols:   280
-  CStrings:  43
+  Functions: 244
+  Symbols:   283
+  CStrings:  46
Symbols:
+ _AXImageExplorerGetSilentMode
+ _OBJC_CLASS_$_AVSystemController
+ _swift_allocError
CStrings:
+ "Error saving image description: %@"
+ "Saved image description into asset."
+ "fetchImageDescription(withType:invocationMethod:source:playSound:)"
+ "kAXImageDescriptionCached"
+ "kAXImageDescriptionError"
+ "kAXImageDescriptionPlaySound"
+ "saveImageDescriptionToAsset(withType:source:cachedDescription:)"
- "Error speaking image description: %@"
- "Spoke image description."
- "fetchImageDescription(withType:invocationMethod:source:)"
- "speakImageDescription(withType:invocationMethod:source:)"
```
