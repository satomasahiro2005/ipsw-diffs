## Silex

> `/System/Library/PrivateFrameworks/Silex.framework/Silex`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1188f0` | `0x118cf8` | **`+0x408`** |
| `__TEXT.__objc_methlist` | `0x1e6bc` | `0x1e6fc` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xb830` | `0xb858` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x51c78` | `0x51c90` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x7c8` | `0x7d0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4f28` | `0x4f20` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-5926.0.0.0.0
+5934.2.0.0.0

-  Functions: 8569
-  Symbols:   20670
+  Functions: 8573
+  Symbols:   20676
Symbols:
+ +[SXEmbedComponentView installUserScriptsIntoContentController:userScript:]
+ +[SXEmbedComponentView resetUserScriptsInContentController:userScript:]
+ -[SXScrollViewController dismissPresentedFullscreenCanvas]
+ -[TSDCanvasView(SXAccessibility) _sxaxCollectImageViewsInView:intoArray:]
+ _OBJC_CLASS_$_NSTextAttachment
+ _UIAccessibilityConvertAttachmentsInAttributedStringToAX
+ __OBJC_$_CLASS_METHODS_SXEmbedComponentView
- _OBJC_CLASS_$_AXAttributedString
CStrings:
+ "1.32"
- "1.31"
```
