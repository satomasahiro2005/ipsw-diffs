## AXImageExplorerServices

> `/System/Library/PrivateFrameworks/AXImageExplorerServices.framework/AXImageExplorerServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x95d8` | `0x96a8` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x45e` | `0x49f` | **`+0x41`** |
| `__AUTH_CONST.__cfstring` | `—` | `0x20` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b0` | `0x1d0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x458` | `0x460` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x3c8` | `0x3d0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x300` | `0x2f8` | **`-0x8`** |

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

-  Functions: 244
-  Symbols:   283
-  CStrings:  46
+  Functions: 245
+  Symbols:   285
+  CStrings:  48
Symbols:
+ _AXImageExplorerProcessingHapticEnabled
+ _AXImageExplorerProcessingSoundEnabled
+ __AXSVibrationDisabled
+ ___CFConstantStringClassReference
- _AXImageExplorerGetSilentMode
- _OBJC_CLASS_$_AVSystemController
CStrings:
+ "ImageRecognition"
+ "kAXImageExplorerSourceIsItem"
+ "present(withType:invocationMethod:sourceIsItem:)"
- "present(withType:invocationMethod:)"
```
