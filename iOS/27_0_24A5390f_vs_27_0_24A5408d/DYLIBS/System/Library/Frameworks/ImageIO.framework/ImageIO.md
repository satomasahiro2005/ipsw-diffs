## ImageIO

> `/System/Library/Frameworks/ImageIO.framework/ImageIO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4fdcb8` | `0x5028a4` | **`+0x4bec`** |
| `__DATA.__bss` | `0x2fc30` | `0x30e40` | **`+0x1210`** |
| `__TEXT.__const` | `0x49530` | `0x49ed0` | **`+0x9a0`** |
| `__TEXT.__cstring` | `0xa5f3e` | `0xa667d` | **`+0x73f`** |
| `__AUTH_CONST.__const` | `0x4ee80` | `0x4f290` | **`+0x410`** |
| `__TEXT.__unwind_info` | `0x13668` | `0x13880` | **`+0x218`** |
| `__TEXT.__eh_frame` | `0x908c` | `0x9214` | **`+0x188`** |
| `__DATA.__data` | `0x64b0` | `0x65f0` | **`+0x140`** |
| `__TEXT.__gcc_except_tab` | `0x2284c` | `0x2298c` | **`+0x140`** |
| `__TEXT.__swift5_typeref` | `0x3c68` | `0x3d88` | **`+0x120`** |
| `__TEXT.__swift5_reflstr` | `0x4fb5` | `0x50a5` | **`+0xf0`** |
| `__TEXT.__swift5_assocty` | `0x1c00` | `0x1cd8` | **`+0xd8`** |
| `__TEXT.__constg_swiftt` | `0x260c` | `0x26a4` | **`+0x98`** |
| `__TEXT.__swift5_proto` | `0x1604` | `0x1694` | **`+0x90`** |
| `__AUTH_CONST.__cfstring` | `0x35f60` | `0x35fe0` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x79f4` | `0x7a54` | **`+0x60`** |
| `__TEXT.__swift5_types` | `0x478` | `0x490` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x2f70` | `0x2f78` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x4b810` | `0x4b818` | **`+0x8`** |

### Other Changes

```diff

-2847.1.0.0.0
+2851.0.0.0.0

-  Functions: 23003
-  Symbols:   24337
-  CStrings:  18195
+  Functions: 23178
+  Symbols:   24408
+  CStrings:  18232
Symbols:
+ GCC_except_table139
+ GCC_except_table148
+ GCC_except_table152
+ GCC_except_table154
+ GCC_except_table159
+ __ZL18FileIsInsideSystemi
+ __ZN13GlobalGIFInfo14globalColorMapEv
+ __ZN13IIODictionary13ensureMutableEv
+ __ZN14IIOImageSource27copyPreferredQualityOptionsEmP13IIODictionary
+ __ZN15JPEGWritePluginC2EP20IIOImageWriteSessionP19IIOImageDestinationj
+ __ZN9IIOStatusC1E12CGImageError13os_log_type_tPKciS3_z
+ __ZNKSt3__120__shared_ptr_pointerIP11IIOColorMapNS_14default_deleteIS1_EENS_9allocatorIS1_EEE13__get_deleterERKSt9type_info
+ __ZNSt3__110shared_ptrI11IIOColorMapEC2B9fqe220106IS1_NS_14default_deleteIS1_EELi0EEEONS_10unique_ptrIT_T0_EE
+ __ZNSt3__110shared_ptrI11IIOColorMapEaSB9fqe220106IS1_NS_14default_deleteIS1_EELi0EEERS2_ONS_10unique_ptrIT_T0_EE
+ __ZNSt3__115allocate_sharedB9fqe220106I11GIFColorMapNS_9allocatorIS1_EEJRP14ColorMapObjectELi0EEENS_10shared_ptrIT_EERKT0_DpOT1_
+ __ZNSt3__120__shared_ptr_emplaceI11GIFColorMapNS_9allocatorIS1_EEE16__on_zero_sharedEv
+ __ZNSt3__120__shared_ptr_emplaceI11GIFColorMapNS_9allocatorIS1_EEE21__on_zero_shared_weakEv
+ __ZNSt3__120__shared_ptr_emplaceI11GIFColorMapNS_9allocatorIS1_EEEC2B9fqe220106IJRP14ColorMapObjectES3_Li0EEES3_DpOT_
+ __ZNSt3__120__shared_ptr_emplaceI11GIFColorMapNS_9allocatorIS1_EEED0Ev
+ __ZNSt3__120__shared_ptr_emplaceI11GIFColorMapNS_9allocatorIS1_EEED1Ev
+ __ZNSt3__120__shared_ptr_pointerIP11IIOColorMapNS_14default_deleteIS1_EENS_9allocatorIS1_EEE16__on_zero_sharedEv
+ __ZNSt3__120__shared_ptr_pointerIP11IIOColorMapNS_14default_deleteIS1_EENS_9allocatorIS1_EEE21__on_zero_shared_weakEv
+ __ZNSt3__120__shared_ptr_pointerIP11IIOColorMapNS_14default_deleteIS1_EENS_9allocatorIS1_EEED0Ev
+ __ZNSt3__120__shared_ptr_pointerIP11IIOColorMapNS_14default_deleteIS1_EENS_9allocatorIS1_EEED1Ev
+ __ZTINSt3__114default_deleteI11IIOColorMapEE
+ __ZTINSt3__120__shared_ptr_emplaceI11GIFColorMapNS_9allocatorIS1_EEEE
+ __ZTINSt3__120__shared_ptr_pointerIP11IIOColorMapNS_14default_deleteIS1_EENS_9allocatorIS1_EEEE
+ __ZTSNSt3__114default_deleteI11IIOColorMapEE
+ __ZTSNSt3__120__shared_ptr_emplaceI11GIFColorMapNS_9allocatorIS1_EEEE
+ __ZTSNSt3__120__shared_ptr_pointerIP11IIOColorMapNS_14default_deleteIS1_EENS_9allocatorIS1_EEEE
+ __ZTVNSt3__120__shared_ptr_emplaceI11GIFColorMapNS_9allocatorIS1_EEEE
+ __ZTVNSt3__120__shared_ptr_pointerIP11IIOColorMapNS_14default_deleteIS1_EENS_9allocatorIS1_EEEE
+ __ZZ41CGImageMetadataRegisterNamespaceForPrefixE22alreadyRegistered_lock
+ ___unnamed_2
+ _associated conformance 7ImageIO15SchemaCodingKeyVs0dE0AAs23CustomStringConvertible
+ _associated conformance 7ImageIO15SchemaCodingKeyVs0dE0AAs28CustomDebugStringConvertible
+ _associated conformance 7ImageIO15SchemaCodingKeyVs26ExpressibleByStringLiteralAA0hI4TypesADP_s01_fg7BuiltinhI0
+ _associated conformance 7ImageIO15SchemaCodingKeyVs26ExpressibleByStringLiteralAAs0fg23ExtendedGraphemeClusterI0
+ _associated conformance 7ImageIO15SchemaCodingKeyVs33ExpressibleByUnicodeScalarLiteralAA0hiJ4TypesADP_s01_fg7BuiltinhiJ0
+ _associated conformance 7ImageIO15SchemaCodingKeyVs43ExpressibleByExtendedGraphemeClusterLiteralAA0hijK4TypesADP_s01_fg7BuiltinhijK0
+ _associated conformance 7ImageIO15SchemaCodingKeyVs43ExpressibleByExtendedGraphemeClusterLiteralAAs0fg13UnicodeScalarK0
+ _associated conformance 7ImageIO17ElementPropertiesV4HEIFV10CodingKeysOSHAASQ
+ _associated conformance 7ImageIO17ElementPropertiesV4HEIFV10CodingKeysOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 7ImageIO17ElementPropertiesV4HEIFV10CodingKeysOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 7ImageIO17ElementPropertiesV4HEIFV10CodingKeysOs12CaseIterableAA8AllCasessAHP_Sl
+ _associated conformance 7ImageIO17ElementPropertiesV4HEIFV11CameraModelV0G4TypeOSHAASQ
+ _associated conformance 7ImageIO17ElementPropertiesV4HEIFV11CameraModelV0G4TypeOs12CaseIterableAA8AllCasessAJP_Sl
+ _associated conformance 7ImageIO17ElementPropertiesV4HEIFV11CameraModelV10CodingKeysOSHAASQ
+ _associated conformance 7ImageIO17ElementPropertiesV4HEIFV11CameraModelV10CodingKeysOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 7ImageIO17ElementPropertiesV4HEIFV11CameraModelV10CodingKeysOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 7ImageIO17ElementPropertiesV4HEIFV11CameraModelV10CodingKeysOs12CaseIterableAA8AllCasessAJP_Sl
+ _associated conformance 7ImageIO17ElementPropertiesV4HEIFV11CameraModelVSHAASQ
+ _associated conformance 7ImageIO17ElementPropertiesV4HEIFV16CameraExtrinsicsV10CodingKeysOSHAASQ
+ _associated conformance 7ImageIO17ElementPropertiesV4HEIFV16CameraExtrinsicsV10CodingKeysOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 7ImageIO17ElementPropertiesV4HEIFV16CameraExtrinsicsV10CodingKeysOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 7ImageIO17ElementPropertiesV4HEIFV16CameraExtrinsicsV10CodingKeysOs12CaseIterableAA8AllCasessAJP_Sl
+ _associated conformance 7ImageIO17ElementPropertiesV4HEIFV16CameraExtrinsicsVSHAASQ
+ _associated conformance 7ImageIO17ElementPropertiesV4HEIFVSHAASQ
+ _get_enum_tag_for_layout_string 7ImageIO17ElementPropertiesV4HEIFV11CameraModelVSg
+ _get_enum_tag_for_layout_string 7ImageIO17ElementPropertiesV4HEIFV16CameraExtrinsicsVSg
+ _kCGImageSourcePrioritizeQuality
+ _swift_retain_n
+ _symbolic Say_____G 7ImageIO17ElementPropertiesV4HEIFV10CodingKeysO
+ _symbolic Say_____G 7ImageIO17ElementPropertiesV4HEIFV11CameraModelV0G4TypeO
+ _symbolic Say_____G 7ImageIO17ElementPropertiesV4HEIFV11CameraModelV10CodingKeysO
+ _symbolic Say_____G 7ImageIO17ElementPropertiesV4HEIFV16CameraExtrinsicsV10CodingKeysO
+ _symbolic _____ 7ImageIO15SchemaCodingKeyV
+ _symbolic _____ 7ImageIO17ElementPropertiesV4HEIFV
+ _symbolic _____ 7ImageIO17ElementPropertiesV4HEIFV10CodingKeysO
+ _symbolic _____ 7ImageIO17ElementPropertiesV4HEIFV11CameraModelV
+ _symbolic _____ 7ImageIO17ElementPropertiesV4HEIFV11CameraModelV0G4TypeO
+ _symbolic _____ 7ImageIO17ElementPropertiesV4HEIFV11CameraModelV10CodingKeysO
+ _symbolic _____ 7ImageIO17ElementPropertiesV4HEIFV16CameraExtrinsicsV
+ _symbolic _____ 7ImageIO17ElementPropertiesV4HEIFV16CameraExtrinsicsV10CodingKeysO
+ _symbolic _____Sg 7ImageIO17ElementPropertiesV4HEIFV11CameraModelV
+ _symbolic _____Sg 7ImageIO17ElementPropertiesV4HEIFV11CameraModelV0G4TypeO
+ _symbolic _____Sg 7ImageIO17ElementPropertiesV4HEIFV16CameraExtrinsicsV
+ _symbolic _____m 7ImageIO17ElementPropertiesV3DNGV
+ _symbolic _____m 7ImageIO17ElementPropertiesV4CIFFV
+ _symbolic _____m 7ImageIO17ElementPropertiesV4HEIFV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 7ImageIO15SchemaCodingKeyV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 7ImageIO17ElementPropertiesV4HEIFV10CodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 7ImageIO17ElementPropertiesV4HEIFV11CameraModelV10CodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 7ImageIO17ElementPropertiesV4HEIFV16CameraExtrinsicsV10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7ImageIO15SchemaCodingKeyV
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7ImageIO17ElementPropertiesV4HEIFV10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7ImageIO17ElementPropertiesV4HEIFV11CameraModelV10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7ImageIO17ElementPropertiesV4HEIFV16CameraExtrinsicsV10CodingKeysO
+ _symbolic _____y_____y_____mG______tG s23_ContiguousArrayStorageC s14PartialKeyPathC 7ImageIO10PropertiesV7SchemasO AE012SchemaCodingE0V
+ _symbolic _____y_____y_____mG______tG s23_ContiguousArrayStorageC s14PartialKeyPathC 7ImageIO17ElementPropertiesV7SchemasO AE012SchemaCodingE0V
+ _type_layout_string 7ImageIO15SchemaCodingKeyV
+ _type_layout_string 7ImageIO17ElementPropertiesV4HEIFV
+ _type_layout_string 7ImageIO17ElementPropertiesV4HEIFV11CameraModelV
+ _type_layout_string 7ImageIO17ElementPropertiesV4HEIFV16CameraExtrinsicsV
- GCC_except_table142
- GCC_except_table150
- GCC_except_table153
- GCC_except_table156
- GCC_except_table174
- __AlphaPosition
- __ZN15JPEGWritePluginC2EP20IIOImageWriteSessionP19IIOImageDestinationh
- __ZN9IIOStatusC1E12CGImageErrorPKciS2_z
- ___unnamed_1
- _associated conformance 7ImageIO10PropertiesV16SchemaCodingKeys33_DF82B7C27D6AB669670F758E5F1D3BB4LLOSHAASQ
- _associated conformance 7ImageIO10PropertiesV16SchemaCodingKeys33_DF82B7C27D6AB669670F758E5F1D3BB4LLOs0E3KeyAAs23CustomStringConvertible
- _associated conformance 7ImageIO10PropertiesV16SchemaCodingKeys33_DF82B7C27D6AB669670F758E5F1D3BB4LLOs0E3KeyAAs28CustomDebugStringConvertible
- _associated conformance 7ImageIO17ElementPropertiesV16SchemaCodingKeys33_382ED54AC95F759574B944F66D76DFEELLOSHAASQ
- _associated conformance 7ImageIO17ElementPropertiesV16SchemaCodingKeys33_382ED54AC95F759574B944F66D76DFEELLOs0F3KeyAAs23CustomStringConvertible
- _associated conformance 7ImageIO17ElementPropertiesV16SchemaCodingKeys33_382ED54AC95F759574B944F66D76DFEELLOs0F3KeyAAs28CustomDebugStringConvertible
- _symbolic _____ 7ImageIO10PropertiesV16SchemaCodingKeys33_DF82B7C27D6AB669670F758E5F1D3BB4LLO
- _symbolic _____ 7ImageIO17ElementPropertiesV16SchemaCodingKeys33_382ED54AC95F759574B944F66D76DFEELLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 7ImageIO10PropertiesV16SchemaCodingKeys33_DF82B7C27D6AB669670F758E5F1D3BB4LLO
- _symbolic _____y_____G s22KeyedDecodingContainerV 7ImageIO17ElementPropertiesV16SchemaCodingKeys33_382ED54AC95F759574B944F66D76DFEELLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 7ImageIO10PropertiesV16SchemaCodingKeys33_DF82B7C27D6AB669670F758E5F1D3BB4LLO
- _symbolic _____y_____G s22KeyedEncodingContainerV 7ImageIO17ElementPropertiesV16SchemaCodingKeys33_382ED54AC95F759574B944F66D76DFEELLO
- _symbolic _____y_____y_____mG7keyPath______9codingKeytG s23_ContiguousArrayStorageC s14PartialKeyPathC 7ImageIO10PropertiesV7SchemasO AG16SchemaCodingKeys33_DF82B7C27D6AB669670F758E5F1D3BB4LLO
- _symbolic _____y_____y_____mG7keyPath______9codingKeytG s23_ContiguousArrayStorageC s14PartialKeyPathC 7ImageIO17ElementPropertiesV7SchemasO AG16SchemaCodingKeys33_382ED54AC95F759574B944F66D76DFEELLO
CStrings:
+ "*** DEBUG: "
+ "*** DEFAULT: "
+ "*** ERROR: CG fallback rowBytes overflow rounding up: product=%u\n"
+ "*** ERROR: CG fallback rowBytes overflow: dstWidth=%zu * bpp=%u\n"
+ "*** ERROR: Extended XMP marker XMP data is NULL, skipping marker\n"
+ "*** ERROR: Failed to map shared memory from xpc_object_t\n"
+ "*** ERROR: IOSurface does not support chroma rowBytes larger than INT32_MAX"
+ "*** ERROR: _TAG::writeToBuffer - out-of-bounds source: offset: %u  tiffStart: %u  size: %u  jpegDataSize: %ld\n"
+ "*** ERROR: copyDateTime - out-of-bounds: offset: %u  tiffStart: %u  count: %u  size: %ld\n"
+ "*** ERROR: dstRowBytes overflow: dstWidth=%zu * (bpp/8)=%u\n"
+ "*** ERROR: iio_convert_XRGB2101010ToRGB16U: MALLOC(%zu) failed\n"
+ "*** ERROR: iio_convert_XRGB2101010ToRGB16U: rowBytes overflow (width=%zu)\n"
+ "*** ERROR: image dimensions exceed UINT32_MAX: %zu x %zu\n"
+ "*** ERROR: missing ContinuousCodestreamBox (count: %u)\n"
+ "*** ERROR: preserveGainMapUsingCFDataRef - gain map descriptor (%u x %u, rowBytes %u) inconsistent with %ld-byte source; skipping\n"
+ "*** ERROR: subsampleRGB888 MALLOC failed (src=%p dst=%p, %zu x %u)\n"
+ "*** ERROR: unexpected bitDepth for RGB  bpc:%zu  bpp:%zu\n"
+ "*** ERROR: unexpected bitDepth for RGB+alpha  alpha:%zu  bpc:%zu  bpp:%zu\n"
+ "*** ERROR: unexpected bitDepth for RGB+alpha(last)  bpc:%zu  bpp:%zu\n"
+ "*** FAULT: "
+ "*** INFO: "
+ "*** IOSurface does not support allocSize larger than INT32_MAX\n"
+ "*** IOSurface does not support rowBytes/allocSize larger than INT32_MAX\n"
+ "*** UNKNOWN: "
+ "*** dest buffer size overflow [%u x %u x %zu]\n"
+ "*** invalid row bytes (src=%u dst=%u)\n"
+ "9"
+ "9.dng"
+ "99"
+ "CameraExtrinsics("
+ "Failed to unmap shared memory (%p; 0x%lx): %s.\n"
+ "IIO_UpdatePlanarSurfaceOptions"
+ "IIO_UpdateSurfaceOptions"
+ "Inconsistent directory count between StripOffsets and StripByteCounts"
+ "Invalid DWT transform block geometry in multi-component transform.  The declared number of decomposition levels does not fully partition the block's inputs."
+ "Invalid DWT transform block geometry in multi-component transform.  The declared number of decomposition levels is inconsistent with the number of block inputs."
+ "METAL"
+ "SIMD"
+ "_TIFFGetStrileOffsetOrByteCountValue"
+ "cameraExtrinsics: "
+ "coordinateSystemId: "
+ "copyDateTime"
+ "kCGImageSourcePrioritizeQuality"
+ "prioritizeQuality: "
+ "source is invalid or only a proxy"
+ "writeToBuffer"
+ "☀️ Using %s converter: %s\n"
- "*** ERROR: duplicate JP2C Continuous Codestream Box (count: %u)\n"
- "*** ERROR: missing or invalid ContinuousCodestreamBox count (%u)\n"
- "*** ERROR: unexpected bitDepth for RGB+alpha  bpc:%zu  bpp:%zu\n"
- "*** could not allocate dest buffer [%d bytes]\n"
- "/System"
- "deltas <= &dec->alpha_data[dec->alpha_data_size]"
- "get_total_composition_dims never succeeded\n"
- "total_nodes >= 0"
- "☀️ Failed to initialize Metal converter, falling back to SIMD for image conversion (slow)"
- "☀️ Using converter: %s\n"
```
