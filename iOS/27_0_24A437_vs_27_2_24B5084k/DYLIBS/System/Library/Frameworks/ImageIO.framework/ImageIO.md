## ImageIO

> `/System/Library/Frameworks/ImageIO.framework/ImageIO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5035b4` | `0x508374` | **`+0x4dc0`** |
| `__TEXT.__cstring` | `0xa6a6d` | `0xa709d` | **`+0x630`** |
| `__TEXT.__gcc_except_tab` | `0x229c0` | `0x22b68` | **`+0x1a8`** |
| `__TEXT.__const` | `0x49ed0` | `0x4a070` | **`+0x1a0`** |
| `__DATA.__data` | `0x65f0` | `0x6780` | **`+0x190`** |
| `__TEXT.__unwind_info` | `0x13890` | `0x13928` | **`+0x98`** |
| `__DATA_DIRTY.__bss` | `0xbe8` | `0xc58` | **`+0x70`** |
| `__DATA_CONST.__got` | `0xaa8` | `0xb10` | **`+0x68`** |
| `__AUTH_CONST.__const` | `0x4f290` | `0x4f2d0` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x921c` | `0x924c` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x2f78` | `0x2fa0` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0xd58` | `0xd68` | **`+0x10`** |

### Other Changes

```diff

-2851.0.0.0.0
+2851.1.4.0.0

-  Functions: 23179
-  Symbols:   24417
-  CStrings:  18247
+  Functions: 23228
+  Symbols:   24473
+  CStrings:  18283
Symbols:
+ -[IIO_CXMLParser dealloc]
+ GCC_except_table179
+ GCC_except_table217
+ _CGColorSpaceCreateWithCopyOfDataAndMetadata
+ _CGImageCopyColorSyncISO5Metadata
+ _ColorSyncProfileCopyISO5Metadata
+ _ColorSyncProfileCreateCopyWithISO5Metadata
+ _IIOImageIsHDR
+ _IIO_ColorSpaceCreateWithICCDataAndISO5Metadata
+ _IIO_CreateColorSpaceCopyWithColorSyncISO5Metadata
+ _IIO_CreateImageCopyWithColorSyncISO5Metadata
+ _IIO_CreateMergedISO5Metadata
+ _IIO_FloatsMatch
+ _IIO_GetCLLFromISO5Dict
+ _IIO_GetMDCVLuminanceFromISO5Dict
+ __Z21CreateReader_DDS_ASTCv
+ __Z22CreateReader_RawCameraP13IIODictionary
+ __ZL18IIO_GetFloatForKeyPK14__CFDictionaryPK10__CFString
+ __ZL19DDSDXGIFormatIsASTCj
+ __ZL26IIO_ISO5CategoryDictsMatchPK14__CFDictionaryS1_PKPK10__CFStringj
+ __ZL29HEIFCopyColorSyncISO5MetadataP7CGImage
+ __ZL31dds_dx9_packed_format_for_masksjjjjj
+ __ZN11OFDDocument5closeEv
+ __ZN11OFDTemplate5closeEv
+ __ZN11OutOfBoundsD0Ev
+ __ZN11OutOfBoundsD1Ev
+ __ZN12BCReadPlugin21decode1010102toRGBA16EP19IIOImageReadSessionP13vImage_Buffer
+ __ZN12BCReadPlugin22decodePacked16toRGBA16EP19IIOImageReadSessionP13vImage_Bufferj
+ __ZN12BCReadPlugin24decodeUncompressedToRGBAEP19IIOImageReadSessionP13vImage_Buffer
+ __ZN13HEIFMainImage23getMaxContentLightLevelEv
+ __ZN13HEIFMainImage28hasISO5ContentLightLevelInfoEv
+ __ZN13HEIFMainImage34getISO5MasteringDisplayColorVolumeEv
+ __ZN13HEIFMainImage34hasISO5MasteringDisplayColorVolumeEv
+ __ZN14ASTCTextureImp24MetalFormatForDXGIFormatEj
+ __ZN14IIO_Reader_RAD27hasCustomCompareOptionsProcEv
+ __ZN20IIOPixelConverterRGBC1E13IIO_PixelTypehhhhhS0_hhPKcbb
+ __ZN20IIOPixelConverterRGBC2E13IIO_PixelTypehhhhhS0_hhPKcbb
+ __ZN7GPSCopy13checkCapacityEPhm
+ __ZN7GPSCopy15pointerToOffsetEm
+ __ZN7GPSCopy15read32UncheckedEPh
+ __ZN7GPSCopy22checkInitializedLengthEPhm
+ __ZNKSt9exception4whatEv
+ __ZNSt9exceptionD2Ev
+ __ZTI11OutOfBounds
+ __ZTS11OutOfBounds
+ __ZTV11OutOfBounds
+ __ZZL16DDSASTCBlockDimsjPhS_E4dims
+ __ZZN14ASTCTextureImp24MetalFormatForDXGIFormatEjE3hdr
+ __ZZN14ASTCTextureImp24MetalFormatForDXGIFormatEjE3ldr
+ __ZZN14ASTCTextureImp24MetalFormatForDXGIFormatEjE4srgb
+ _kCGColorSpaceExtendedRange
+ _kColorSyncAverageLightLevel
+ _kColorSyncAverageLuminance
+ _kColorSyncCCVInfo
+ _kColorSyncCLLInfo
+ _kColorSyncCRWLInfo
+ _kColorSyncMDCVInfo
+ _kColorSyncMaxLightLevel
+ _kColorSyncMaxLuminance
+ _kColorSyncMinLuminance
+ _kColorSyncPrimaries
+ _kColorSyncReferenceWhite
+ _sniffDDS
+ _unzClose
+ _vImageConvert_RGBFFFtoRGBAFFFF
- GCC_except_table181
- GCC_except_table185
- GCC_except_table215
- __ZN19IIOReader_RawCameraC1EP13IIODictionary
- __ZN20IIOPixelConverterRGBC1E13IIO_PixelTypehhhhhS0_hhPKc
- __ZN20IIOPixelConverterRGBC2E13IIO_PixelTypehhhhhS0_hhPKc
- __ZN7GPSCopy6read32EPh
- _sniffBC
- _sniffOlympusRaw
CStrings:
+ "       : opacity=%d flags=0x%02x%s\n"
+ " (hidden)"
+ "*** BC - no compressed data for level %d\n"
+ "*** CMPhotoDecompressionContainerCopyXMPForIndexWithOptions returned noErr with no XMP data\n"
+ "*** DDS/ASTC: image dimensions overflow\n"
+ "*** ERROR: BC (KTX) no complete miplevel in file\n"
+ "*** ERROR: TIFFSetDirectory failed\n"
+ "*** ERROR: iio_vImageBuffer_InitWithCGImage failed: %ld\n"
+ "*** ERROR: no XMP could be reassembled from the extended XMP blocks\n"
+ "*** ERRROR: could not allocate rlebuf - size=%llu\n"
+ "*** ERRROR: unsupported height (%llu)\n"
+ "*** ERRROR: unsupported width (%llu)\n"
+ "*** NOTE: layer#%u has %u channels; cannot apply opacity %u\n"
+ "*** NOTE: skipping hidden layer#%u\n"
+ "*** RGBX coverage?  bitMask: %08X\n"
+ "*** _bitsPerPixel %d is too small for 4 channels of %d bits [%d-%d-%d-%d]\n"
+ "*** bad 'fcTL' chunk size at offset %ld: %u - expected frames: %ld  found: %ld\n"
+ "*** bad DDS/ASTC data: expected %llu bytes\n"
+ "*** bad DDS/ASTC height %u\n"
+ "*** bad DDS/ASTC width %u\n"
+ "*** bad KTX: [%ldx%ld]  srcBpp: %lld  fileSize: %d\n"
+ "*** bad packed KTX: [%ldx%ld] fileSize: %d\n"
+ "*** could not create ASTC encoder\n"
+ "*** decode buffer is too small for the SDR conversion\n"
+ "*** decode buffer too small: need %zu bytes (%zu x %zu), have %zu\n"
+ "*** frame[%ld] rect {%d, %d, %d, %d} does not fit the %d x %d destination\n"
+ "*** truncated 'fcTL' chunk at offset %ld - expected frames: %ld  found: %ld\n"
+ "*** truncated chunk header at offset %ld - expected frames: %ld  found: %ld\n"
+ "8BIMiOpa"
+ "TIFFReadDirEntryFloatArray"
+ "TIFFReadDirEntryIfd8Array"
+ "TIFFReadDirEntryLong8ArrayWithLimit"
+ "TIFFReadDirEntryLongArray"
+ "TIFFReadDirEntryShortArray"
+ "TIFFReadDirEntrySlong8Array"
+ "TIFFReadDirEntrySlongArray"
+ "TIFFReadDirEntrySshortArray"
+ "loadTIFFStructure"
- "*** ERRROR: could not allocate rlebuf - size=%d\n"
- "*** bad KTX: [%ldx%ld]  channels: %ld  fileSize: %d\n"
```
