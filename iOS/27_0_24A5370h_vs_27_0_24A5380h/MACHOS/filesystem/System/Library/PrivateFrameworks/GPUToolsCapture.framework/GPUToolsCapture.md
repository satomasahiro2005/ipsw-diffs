## GPUToolsCapture

> `/System/Library/PrivateFrameworks/GPUToolsCapture.framework/GPUToolsCapture`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x291f90` | `0x29665c` | **`+0x46cc`** |
| `__TEXT.__cstring` | `0x30589` | `0x30821` | **`+0x298`** |
| `__TEXT.__const` | `0x9f30` | `0xa020` | **`+0xf0`** |
| `__TEXT.__objc_stubs` | `0x183e0` | `0x184c0` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x2382` | `0x2418` | **`+0x96`** |
| `__DATA_CONST.__cfstring` | `0x4900` | `0x4980` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x1b8ac` | `0x1b911` | **`+0x65`** |
| `__DATA_CONST.__got` | `0x810` | `0x868` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x4c20` | `0x4c68` | **`+0x48`** |
| `__DATA.__objc_selrefs` | `0x7010` | `0x7040` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2178` | `0x2198` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0xafae` | `0xafc9` | **`+0x1b`** |
| `__DATA.__bss` | `0x4688` | `0x4698` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1930` | `0x1920` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x1358c` | `0x1359c` | **`+0x10`** |
| `__DATA.__objc_const` | `0x1b4a8` | `0x1b4b0` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xcb0` | `0xca8` | **`-0x8`** |

### Same-size Content Changes

- `__AUTH_CONST.__interpose`
- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__thread_vars`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-2027.0.31.0.0
+2027.0.33.0.0

-  Functions: 9799
-  Symbols:   16216
-  CStrings:  9407
+  Functions: 9823
+  Symbols:   16252
+  CStrings:  9425
Symbols:
+ GCC_except_table2182
+ GCC_except_table2227
+ GCC_except_table2354
+ GCC_except_table2380
+ GCC_except_table3062
+ GCC_except_table3070
+ GCC_except_table3206
+ GCC_except_table3357
+ GCC_except_table3364
+ GCC_except_table3373
+ GCC_except_table3473
+ GCC_except_table3600
+ GCC_except_table4226
+ GCC_except_table4404
+ GCC_except_table4416
+ GCC_except_table4417
+ GCC_except_table4592
+ GCC_except_table4593
+ GCC_except_table4864
+ _DYTraceDecode_MTL4ComputeCommandEncoder_copyFromTensor_sourceOrigin_sourceDimensions_sourcePlane_toTensor_destinationOrigin_destinationDimensions_destinationPlane
+ _DYTraceDecode_MTLBlitCommandEncoder_copyFromTensor_sourceOrigin_sourceDimensions_sourcePlane_toTensor_destinationOrigin_destinationDimensions_destinationPlane
+ _DYTraceDecode_MTLDevice_newTensorWithDescriptor_attachments_error
+ _DYTraceDecode_MTLTensor_getBytes_strides_fromSliceOrigin_sliceDimensions_plane
+ _DYTraceDecode_MTLTensor_replaceSliceOrigin_sliceDimensions_plane_withBytes_strides
+ _DYTraceEncode_MTL4ComputeCommandEncoder_copyFromTensor_sourceOrigin_sourceDimensions_sourcePlane_toTensor_destinationOrigin_destinationDimensions_destinationPlane
+ _DYTraceEncode_MTLBlitCommandEncoder_copyFromTensor_sourceOrigin_sourceDimensions_sourcePlane_toTensor_destinationOrigin_destinationDimensions_destinationPlane
+ _DYTraceEncode_MTLDevice_newTensorWithDescriptor_attachments_error
+ _DYTraceEncode_MTLTensor_getBytes_strides_fromSliceOrigin_sliceDimensions_plane
+ _DYTraceEncode_MTLTensor_replaceSliceOrigin_sliceDimensions_plane_withBytes_strides
+ _DecodeDYMTLTensorBufferAttachments
+ _EncodeDYMTLTensorBufferAttachments
+ _GTMTLTensorDataType_alignment
+ _GTMTLTensorDataType_bitsLength
+ _GTMTLTensorExtents_computeFormatAlignedStrides
+ _GTMTLTensorExtents_divideExtents
+ _MTLTensor_dataTypeForPlane
+ _MakeDYMTLTensorBufferAttachmentsItem
+ _MakeMTLTensorBufferAttachments
+ _OBJC_CLASS_$_MTLTensorAuxiliaryPlaneDescriptorMap
+ _OBJC_CLASS_$_MTLTensorBufferAttachments
+ _OBJC_CLASS_$_NSDateFormatter
+ _OBJC_CLASS_$_NSLocale
+ _SaveDYMTLTensorBufferAttachmentsItem
+ _SaveMTLTensorBufferAttachments
+ _StoreMTLTensorBufferAttachmentsUsingEncode
+ _TranslateGTMTLTensorBufferAttachments
+ ___61-[GTMTLCaptureService startWithDescriptor:completionHandler:]_block_invoke_2
+ _objc_msgSend$compressionMetadata
+ _objc_msgSend$downloadCompressionMetadataForTexture:gpuAddress:length:
+ _objc_msgSend$localeWithLocaleIdentifier:
+ _objc_msgSend$processName
+ _objc_msgSend$setAuxiliaryPlanes:
+ _objc_msgSend$setDateFormat:
+ _objc_msgSend$setLocale:
+ _objc_msgSend$stringFromDate:
+ startWithDescriptor:completionHandler:.formatter
+ startWithDescriptor:completionHandler:.once
- GCC_except_table2181
- GCC_except_table2226
- GCC_except_table2348
- GCC_except_table2379
- GCC_except_table3060
- GCC_except_table3068
- GCC_except_table3204
- GCC_except_table3355
- GCC_except_table3362
- GCC_except_table3371
- GCC_except_table3471
- GCC_except_table3598
- GCC_except_table4224
- GCC_except_table4399
- GCC_except_table4400
- GCC_except_table4412
- GCC_except_table4586
- GCC_except_table4587
- GCC_except_table4862
- _objc_msgSend$globallyUniqueString
- _objc_retain_x6
CStrings:
+ "%@_%@_p%d.gputrace"
+ "(unlabeled)"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/trackers/GTResourceTracker.c:232"
+ "C@17ul@17ululU<b>@17ul"
+ "CU<b>@17ul@17ul@17ulul"
+ "Ct@17ul@17ulult@17ul@17ulul"
+ "compressionMetadata"
+ "en_US_POSIX"
+ "kDYFEMTLTensor_harvested_replaceSliceOrigin_sliceDimensions_plane_withBytes_strides"
+ "localeWithLocaleIdentifier:"
+ "memcmp((const char*)bytes + offset, (\"C@17ul@17ululU<b>@17ul\"), sizeof(\"C@17ul@17ululU<b>@17ul\")) == 0"
+ "memcmp((const char*)bytes + offset, (\"CU<b>@17ul@17ul@17ulul\"), sizeof(\"CU<b>@17ul@17ul@17ulul\")) == 0"
+ "memcmp((const char*)bytes + offset, (\"Ct@17ul@17ulult@17ul@17ulul\"), sizeof(\"Ct@17ul@17ulult@17ul@17ulul\")) == 0"
+ "processName"
+ "setAuxiliaryPlanes:"
+ "setDateFormat:"
+ "setLocale:"
+ "stringFromDate:"
+ "warning: Compression metadata SPI unavailable for placement sparse texture '%s'"
+ "warning: Compression metadata empty for placement sparse texture '%s'"
+ "yyyy-MM-dd_HH-mm-ss-SSS"
+ "{MTL4BufferRange=QQ}16@0:8"
- ".gputrace"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/GPUToolsDevice/GPUTools/GTMTLCapture/trackers/GTResourceTracker.c:230"
- "Multiplanar tensors"
- "globallyUniqueString"
```
