## ImageIO

> `/System/Library/Frameworks/ImageIO.framework/ImageIO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x508374` | `0x509204` | **`+0xe90`** |
| `__TEXT.__cstring` | `0xa709d` | `0xa759d` | **`+0x500`** |
| `__DATA.__bss` | `0x30e40` | `0x30a30` | **`-0x410`** |
| `__DATA_DIRTY.__bss` | `0xc58` | `0x1058` | **`+0x400`** |
| `__AUTH_CONST.__const` | `0x4f2d0` | `0x4f498` | **`+0x1c8`** |
| `__AUTH_CONST.__cfstring` | `0x36000` | `0x36100` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x4b818` | `0x4b890` | **`+0x78`** |
| `__TEXT.__gcc_except_tab` | `0x22b68` | `0x22bd4` | **`+0x6c`** |
| `__AUTH_CONST.__auth_got` | `0x2fa0` | `0x2fc0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x13928` | `0x13948` | **`+0x20`** |
| `__AUTH.__data` | `0x15d8` | `0x15c8` | **`-0x10`** |
| `__DATA.__data` | `0x6780` | `0x6790` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x3b0` | `0x3c0` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x924c` | `0x925c` | **`+0x10`** |
| `__DATA.__common` | `0x2270` | `0x2268` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xb10` | `0xb18` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0xff0` | `0xff8` | **`+0x8`** |

### Other Changes

```diff

-2851.1.4.0.0
+2851.1.6.0.0

-  Functions: 23228
-  Symbols:   24473
-  CStrings:  18283
+  Functions: 23242
+  Symbols:   24492
+  CStrings:  18311
Symbols:
+ _CGColorSpaceContainsISO5Metadata
+ _CGImageGetContentAverageLightLevelNits
+ _ColorSyncProfileGetContentHeadroom
+ _ColorSyncProfileGetISO5AverageLightLevel
+ _IIO_CreateISO5MetadataInfo
+ __ZL21IIO_ApplyCheckNonZeroPKvS0_Pv
+ __ZL24IIO_CreateNeutralISO5KeyPK10__CFString
+ __ZL25IIO_ApplyNeutralISO5EntryPKvS0_Pv
+ __ZL29IIO_ApplyNeutralISO5KeyRenamePKvS0_Pv
+ __ZN10IIO_Reader19updateImageAVLLNitsEP7CGImageP19IIOImageReadSessionP12CGColorSpace20CGImageComponentTypej
+ __ZN13IIOReadPlugin29willApplyOrientationTransformEv
+ __ZN14HEIFReadPlugin29willApplyOrientationTransformEv
+ __ZN15IIO_Reader_HEIF19updateImageAVLLNitsEP7CGImageP19IIOImageReadSessionP12CGColorSpace20CGImageComponentTypej
+ _iptc_AIPromptInformation
+ _iptc_AIPromptWriterName
+ _kCGImagePropertyIPTCExtAIPromptInformation
+ _kCGImagePropertyIPTCExtAIPromptWriterName
+ _kColorSyncDerivedISO5Metadata
+ _kIIOICCISO5MetadataPropertyKey
CStrings:
+ "*** BMP - writePrefix failed, not writing pixel data\n"
+ "*** ERROR: CFURLCreateWithFileSystemPath returned nil.\n"
+ "*** ERROR: CGImageReadCreateWithURL returned nil.\n"
+ "*** ERROR: could not create the image reader for the given path.\n"
+ "*** ERROR: decodeStripPlanar destination row is %u bytes, the scatter needs %llu\n"
+ "*** ERROR: decodeTilePlanar destination row is %u bytes, the scatter needs %llu\n"
+ "*** ERROR: failed to allocte temp (%zu bytes)\n"
+ "*** ERROR: failed to read %zu bytes of pixel data for 420f\n"
+ "*** ERROR: updateTiffStruct failed after the codec data format was set\n"
+ "*** can't write KTX - failed to read %zu bytes of pixel data\n"
+ "*** can't write KTX - unsupported image size (%u x %u, rowBytes %zu)\n"
+ "*** can't write KTX2 - bad image size (%zu x %zu)\n"
+ "*** can't write KTX2 - failed to read %zu bytes of pixel data\n"
+ "*** failed to read %zu bytes of pixel data\n"
+ "AIPromptInformation"
+ "AIPromptWriterName"
+ "AverageLightLevelNits"
+ "ColorPrimaries"
+ "MetadataDisplayName"
+ "Primaries"
+ "com.apple.cmm."
+ "decodeStripPlanar"
+ "ico image %zu: %zu bytes is too small for a BITMAPINFOHEADER\n"
+ "ico image %zu: header %u + pixels %zu + mask %zu exceeds %zu bytes\n"
+ "updateImageAVLLNits"
+ "write420fData"
+ "{ICC ISO-5}"
+ "☀️  %s - failed to update image avll: %d  [colorspace: '%s']\n"
+ "☀️  %s - not setting image avll: %d for SDR [colorspace: '%s']\n"
+ "☀️  %s - updating image AVLL: %d [colorspace: '%s']\n"
- "*** ERROR: failed to allocte temp (%d bytes)\n"
- "CGImageReadCreateWithURL returned nil.\n"
```
