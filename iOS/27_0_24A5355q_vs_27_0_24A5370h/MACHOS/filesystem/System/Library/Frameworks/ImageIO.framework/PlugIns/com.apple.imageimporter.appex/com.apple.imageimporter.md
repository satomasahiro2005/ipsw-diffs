## com.apple.imageimporter

> `/System/Library/Frameworks/ImageIO.framework/PlugIns/com.apple.imageimporter.appex/com.apple.imageimporter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x160c` | `0x1758` | **`+0x14c`** |
| `__TEXT.__objc_methname` | `0x819` | `0x863` | **`+0x4a`** |
| `__TEXT.__objc_stubs` | `0xd40` | `0xd80` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0xa0` | `0xd0` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x2c0` | `0x2e8` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x66` | `0x87` | **`+0x21`** |
| `__DATA_CONST.__auth_got` | `0x58` | `0x70` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `—` | `0x18` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x360` | `0x370` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x98` | `0xa4` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0xa0` | `0xa8` | **`+0x8`** |
| `__TEXT.__cstring` | `0x1bc` | `0x1be` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`

### Other Changes

```diff

-2839.0.0.0.0
+2843.1.1.0.0

+  - /System/Library/PrivateFrameworks/FileDerivatives.framework/FileDerivatives

-  Functions: 15
-  Symbols:   107
-  CStrings:  145
+  Functions: 16
+  Symbols:   116
+  CStrings:  149
Symbols:
+ _CGImageSourceCreateThumbnailAtIndex
+ _FDSApplyAttributeDictionaryToCSSearchableItemAttributeSet
+ _FDSAttributeDictionaryFromImageWithOptions
+ _OBJC_CLASS_$_NSConstantIntegerNumber
+ _kCGImageSourceEnableRestrictedDecoding
+ _kCGImageSourceThumbnailMaxPixelSize
+ _kCGImageSourceUseHardwareAcceleration
+ _kFDSImportOptionAllOptions
+ _kFDSImportOptionFallbackOCR
CStrings:
+ "@40@0:8^{CGImageSource=}16@24@32"
+ "attributeDictionary"
+ "i"
+ "performOCRWithImageSource:existingAttributes:options:"
```
