## ImageIO

> `/System/Library/Frameworks/ImageIO.framework/ImageIO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4fcacc` | `0x4fd300` | **`+0x834`** |
| `__TEXT.__cstring` | `0xa5a3e` | `0xa5f9e` | **`+0x560`** |
| `__DATA.__bss` | `0x2f820` | `0x2fc30` | **`+0x410`** |
| `__AUTH_CONST.__const` | `0x4edb0` | `0x4eea0` | **`+0xf0`** |
| `__TEXT.__gcc_except_tab` | `0x22754` | `0x22844` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0x35fa0` | `0x35f60` | **`-0x40`** |
| `__DATA_DIRTY.__bss` | `0xba8` | `0xbe8` | **`+0x40`** |
| `__TEXT.__const` | `0x49460` | `0x494a0` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x90c4` | `0x908c` | **`-0x38`** |
| `__TEXT.__unwind_info` | `0x13640` | `0x13660` | **`+0x20`** |
| `__DATA.__common` | `0x2288` | `0x2270` | **`-0x18`** |
| `__DATA_DIRTY.__common` | `0xfa0` | `0xfb8` | **`+0x18`** |
| `__AUTH.__data` | `0x15c8` | `0x15d8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2f60` | `0x2f70` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x4b820` | `0x4b810` | **`-0x10`** |
| `__DATA_CONST.__got` | `0xaa0` | `0xab0` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x3c0` | `0x3b0` | **`-0x10`** |

### Other Changes

```diff

-2843.1.1.0.0
+2846.0.0.0.0

-  Functions: 22960
-  Symbols:   24297
-  CStrings:  18177
+  Functions: 22998
+  Symbols:   24341
+  CStrings:  18195
Symbols:
+ GCC_except_table218
+ __ZGVZ23OFDCreatePDFDataFromURLE7ofdLock
+ __ZN19HEIFStereoAggressor13writeToStreamEP15__CFWriteStream
+ __ZN3xdr13NullTexture1D5writeEDv4_ft
+ __ZN3xdr13NullTexture1DD0Ev
+ __ZN3xdr13NullTexture1DD1Ev
+ __ZN3xdr13NullTexture3D5writeEDv4_fDv3_t
+ __ZN3xdr13NullTexture3DD0Ev
+ __ZN3xdr13NullTexture3DD1Ev
+ __ZN3xdr29dispatch_compute_gainmap_loopILt2ELt2EEEvRKNS_7imageInES3_RKNS_8imageOutERKNS_16colorTransformInES9_RKNS_16gainTransformOutEDv2_t
+ __ZN3xdr35dispatch_compute_gainmap_image_loopILt2ELt1EEEvRKNS_7imageInES3_RKNS_8imageOutES6_RKNS_16colorTransformInES9_RKNS_16gainTransformOutERKNS_17colorTransformOutEDv2_t
+ __ZN3xdr35dispatch_compute_gainmap_image_loopILt2ELt2EEEvRKNS_7imageInES3_RKNS_8imageOutES6_RKNS_16colorTransformInES9_RKNS_16gainTransformOutERKNS_17colorTransformOutEDv2_t
+ __ZN3xdr35dispatch_compute_gainmap_image_loopILt4ELt2EEEvRKNS_7imageInES3_RKNS_8imageOutES6_RKNS_16colorTransformInES9_RKNS_16gainTransformOutERKNS_17colorTransformOutEDv2_t
+ __ZN3xdr35dispatch_compute_gainmap_image_loopILt4ELt4EEEvRKNS_7imageInES3_RKNS_8imageOutES6_RKNS_16colorTransformInES9_RKNS_16gainTransformOutERKNS_17colorTransformOutEDv2_t
+ __ZN3xdr44dispatch_convert_gainmap_image_to_image_loopILt2ELt2EEEvRKNS_7imageInES3_RKNS_8imageOutERKNS_16colorTransformInERKNS_15gainTransformInERKNS_17colorTransformOutEDv2_t
+ __ZN3xdr44dispatch_convert_image_to_gainmap_image_loopILt2ELt2EEEvRKNS_7imageInERKNS_8imageOutES6_RKNS_16colorTransformInES9_RKNS_17colorTransformOutERKNS_16gainTransformOutEDv2_t
+ __ZN3xdr44dispatch_convert_image_to_gainmap_image_loopILt4ELt2EEEvRKNS_7imageInERKNS_8imageOutES6_RKNS_16colorTransformInES9_RKNS_17colorTransformOutERKNS_16gainTransformOutEDv2_t
+ __ZN3xdr44dispatch_convert_image_to_gainmap_image_loopILt4ELt4EEEvRKNS_7imageInERKNS_8imageOutES6_RKNS_16colorTransformInES9_RKNS_17colorTransformOutERKNS_16gainTransformOutEDv2_t
+ __ZN3xdr52dispatch_convert_gainmap_image_to_gainmap_image_loopILt2ELt1EEEvRKNS_7imageInES3_RKNS_8imageOutES6_RKNS_16colorTransformInERKNS_15gainTransformInES9_SC_RKNS_17colorTransformOutERKNS_16gainTransformOutEDv2_t
+ __ZN3xdr52dispatch_convert_gainmap_image_to_gainmap_image_loopILt2ELt2EEEvRKNS_7imageInES3_RKNS_8imageOutES6_RKNS_16colorTransformInERKNS_15gainTransformInES9_SC_RKNS_17colorTransformOutERKNS_16gainTransformOutEDv2_t
+ __ZN3xdr52dispatch_convert_gainmap_image_to_gainmap_image_loopILt4ELt2EEEvRKNS_7imageInES3_RKNS_8imageOutES6_RKNS_16colorTransformInERKNS_15gainTransformInES9_SC_RKNS_17colorTransformOutERKNS_16gainTransformOutEDv2_t
+ __ZN3xdr52dispatch_convert_gainmap_image_to_gainmap_image_loopILt4ELt4EEEvRKNS_7imageInES3_RKNS_8imageOutES6_RKNS_16colorTransformInERKNS_15gainTransformInES9_SC_RKNS_17colorTransformOutERKNS_16gainTransformOutEDv2_t
+ __ZNK3xdr10ColorBoxIn9transformEv
+ __ZNK3xdr11ColorBoxOut9transformEv
+ __ZNK3xdr13NullTexture1D4readEt
+ __ZNK3xdr13NullTexture3D4readEDv3_t
+ __ZNK3xdr18PixelFormatR8Unorm13bytesPerPixelEv
+ __ZNK3xdr19PixelFormatR16Float13bytesPerPixelEv
+ __ZNK3xdr19PixelFormatR16Unorm13bytesPerPixelEv
+ __ZNK3xdr19PixelFormatR32Float13bytesPerPixelEv
+ __ZNK3xdr19PixelFormatRG8Unorm13bytesPerPixelEv
+ __ZNK3xdr20PixelFormatRG16Unorm13bytesPerPixelEv
+ __ZNK3xdr21PixelFormatBGRA8Unorm13bytesPerPixelEv
+ __ZNK3xdr22PixelFormatRGBA16Float13bytesPerPixelEv
+ __ZNK3xdr22PixelFormatRGBA16Unorm13bytesPerPixelEv
+ __ZNK3xdr22PixelFormatRGBA32Float13bytesPerPixelEv
+ __ZNK3xdr23PixelFormatBGR10A2Unorm13bytesPerPixelEv
+ __ZTIN3xdr13NullTexture1DE
+ __ZTIN3xdr13NullTexture3DE
+ __ZTSN3xdr13NullTexture1DE
+ __ZTSN3xdr13NullTexture3DE
+ __ZTVN3xdr13NullTexture1DE
+ __ZTVN3xdr13NullTexture3DE
+ __ZZL27IIOGetCodesigningIdentifiervE11cachedBytes
+ _fmod
+ _modf
- _kCGImageAuxiliaryDataTypeProvenanceProcessedImage
- _kCGImageAuxiliaryDataTypeProvenanceUnprocessedImage
CStrings:
+ "%.0f,%.6f%c"
+ "*** ERROR: failed to read RLE size table\n"
+ "*** ERROR: invalid JP2: PaletteBox %d color components\n"
+ "*** ERROR: invalid JP2: PaletteBox %d entries\n"
+ "*** ERROR: invalid JP2: PaletteBox component %u unsupported bit depth %u\n"
+ "*** ERROR: preserveGainMapUsingCFDataRef scaled gain map dimensions out of range (%u x %u)\n"
+ "*** ERROR: preserveGainMapUsingCFDataRef source gain map dimensions out of range (%u x %u)\n"
+ "-[HDRImageConverter_SIMD computeLumaGainHistogram:scale:image:transform:gainMap:transform:]"
+ "-[HDRImageConverter_SIMD computeStatistics:image:transform:]"
+ "-[HDRImageConverter_SIMD computeStatistics:image:transform:gainMap:transform:]"
+ "PixelBufferTexture"
+ "PixelBufferTexture: malformed pixel buffer - bytesPerRow %zu < %u * %zu for format %s"
+ "computeGainMap:fromBaseImage:alternateImage: missing image plane (unsupported pixel type)"
+ "computeGainMap:outputImage:fromBaseImage:alternateImage: missing image plane (unsupported pixel type)"
+ "computeLumaGainHistogram: missing image plane (unsupported pixel type)"
+ "computeStatistics:image: missing image plane (unsupported pixel type)"
+ "computeStatistics:image:gainMap: missing image plane (unsupported pixel type)"
+ "convertImage:alternate:gainMap:alternate:toImage:gainMap: missing image plane (unsupported pixel type)"
+ "convertImage:alternate:toImage:gainMap: missing image plane (unsupported pixel type)"
+ "convertImage:gainMap:toImage: missing image plane (unsupported pixel type)"
+ "convertImage:toImage: missing image plane (unsupported pixel type)"
+ "☀️ Using subsample factor: %u (%zu px)"
- "%d,%lg%c"
- "kCGImageAuxiliaryDataTypeProvenanceProcessedImage"
- "kCGImageAuxiliaryDataTypeProvenanceUnprocessedImage"
- "☀️ Using subsample factor: %u (%u px)"
```
