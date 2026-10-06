## ImageIO

> `/System/Library/Frameworks/ImageIO.framework/ImageIO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5028a4` | `0x5035b4` | **`+0xd10`** |
| `__TEXT.__cstring` | `0xa667d` | `0xa6a6d` | **`+0x3f0`** |
| `__DATA_DIRTY.__common` | `0xfb8` | `0xff0` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x2298c` | `0x229c0` | **`+0x34`** |
| `__AUTH_CONST.__cfstring` | `0x35fe0` | `0x36000` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x13880` | `0x13890` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x9214` | `0x921c` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 23178
-  Symbols:   24408
-  CStrings:  18232
+  Functions: 23179
+  Symbols:   24417
+  CStrings:  18247
Symbols:
+ __ZL33IIOCopyDNGProvenanceFromContainerPK14__CFDictionaryPK10__CFString
+ __ZN14IIOImageSource25copyProvenanceDataAtIndexEmP21CGImageProvenanceType
+ _gFunc_CMPhotoDNGCopyProperties
+ _gIIO_kCMPhotoCustomMetadataTypeURN_Provenance_LowerBoundTimeStamp
+ _gIIO_kCMPhotoCustomMetadataTypeURN_Provenance_ProcessedImage
+ _gIIO_kCMPhotoCustomMetadataTypeURN_Provenance_UnprocessedImage
+ _gIIO_kCMPhotoCustomMetadataTypeURN_Provenance_UpperBoundTimeStamp
+ _gIIO_kCMPhoto_CGImagePropertyDNGProvenanceProcessedImage
+ _gIIO_kCMPhoto_CGImagePropertyDNGProvenanceUnprocessedImage
CStrings:
+ "*** CMPhotoCompressionSessionAddCustomMetadata (provenance) err = %s [%d]\n"
+ "CMPhotoDNGCopyProperties"
+ "kCMPhotoCustomMetadataTypeURN_Provenance_LowerBoundTimeStamp"
+ "kCMPhotoCustomMetadataTypeURN_Provenance_ProcessedImage"
+ "kCMPhotoCustomMetadataTypeURN_Provenance_UnprocessedImage"
+ "kCMPhotoCustomMetadataTypeURN_Provenance_UpperBoundTimeStamp"
+ "kCMPhoto_CGImagePropertyDNGProvenanceProcessedImage"
+ "kCMPhoto_CGImagePropertyDNGProvenanceUnprocessedImage"
+ "❌  failed to load 'CMPhotoDNGCopyProperties' [%s]\n"
+ "❌  failed to load 'kCMPhotoCustomMetadataTypeURN_Provenance_LowerBoundTimeStamp' [%s]\n"
+ "❌  failed to load 'kCMPhotoCustomMetadataTypeURN_Provenance_ProcessedImage' [%s]\n"
+ "❌  failed to load 'kCMPhotoCustomMetadataTypeURN_Provenance_UnprocessedImage' [%s]\n"
+ "❌  failed to load 'kCMPhotoCustomMetadataTypeURN_Provenance_UpperBoundTimeStamp' [%s]\n"
+ "❌  failed to load 'kCMPhoto_CGImagePropertyDNGProvenanceProcessedImage' [%s]\n"
+ "❌  failed to load 'kCMPhoto_CGImagePropertyDNGProvenanceUnprocessedImage' [%s]\n"
```
