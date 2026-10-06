## LinkPresentation

> `/System/Library/Frameworks/LinkPresentation.framework/LinkPresentation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x3e40` | `0x36e8` | **`-0x758`** |
| `__DATA_DIRTY.__objc_data` | `0x1b58` | `0x22b0` | **`+0x758`** |
| `__TEXT.__text` | `0x10be24` | `0x10bf5c` | **`+0x138`** |
| `__DATA_CONST.__got` | `0xe08` | `0xed0` | **`+0xc8`** |
| `__AUTH_CONST.__objc_const` | `0x2ddf0` | `0x2de20` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x23408` | `0x233d8` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x11154` | `0x1117c` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x83d8` | `0x83f0` | **`+0x18`** |
| `__DATA.__bss` | `0x1b20` | `0x1b10` | **`-0x10`** |
| `__DATA.__data` | `0x1c28` | `0x1c18` | **`-0x10`** |
| `__TEXT.__const` | `0x2344` | `0x2354` | **`+0x10`** |
| `__AUTH.__data` | `0x4d8` | `0x4d0` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x7b38` | `0x7b40` | **`+0x8`** |
| `__DATA_DIRTY.__data` | `0x8` | `0x10` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1804` | `0x1808` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`
- `__TEXT.__ustring`

### Other Changes

```diff

-310.0.0.0.0
+311.0.0.0.0

-  Functions: 6856
-  Symbols:   11709
+  Functions: 6860
+  Symbols:   11715
Symbols:
+ -[LPCircularProgressIndicator tintColorDidChange]
+ -[LPCircularProgressIndicatorStyle setTrackColor:]
+ -[LPCircularProgressIndicatorStyle trackColor]
+ -[LPLinkMetadataPresentationTransformer setSupportsInlineSymbolImages:]
+ -[LPLinkMetadataPresentationTransformer setSupportsOverlaidMediaCaptionBars:]
+ -[LPLinkMetadataPresentationTransformer supportsInlineSymbolImages]
+ -[LPLinkMetadataPresentationTransformer supportsOverlaidMediaCaptionBars]
+ GCC_except_table281
+ GCC_except_table419
+ GCC_except_table420
+ _OBJC_IVAR_$_LPCircularProgressIndicatorStyle._trackColor
+ _OBJC_IVAR_$_LPLinkMetadataPresentationTransformer._supportsInlineSymbolImages
+ _OBJC_IVAR_$_LPLinkMetadataPresentationTransformer._supportsOverlaidMediaCaptionBars
+ _joinSymbolWithText
- -[LPCircularProgressIndicatorStyle borderColor]
- -[LPCircularProgressIndicatorStyle fillColor]
- -[LPCircularProgressIndicatorStyle setBorderColor:]
- -[LPCircularProgressIndicatorStyle setFillColor:]
- GCC_except_table174
- GCC_except_table283
- _OBJC_IVAR_$_LPCircularProgressIndicatorStyle._borderColor
- _OBJC_IVAR_$_LPCircularProgressIndicatorStyle._fillColor
```
