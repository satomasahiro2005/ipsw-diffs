## MobileMulticastTransfer

> `/System/Library/PrivateFrameworks/MobileMulticastTransfer.framework/MobileMulticastTransfer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x363d8` | `0x38430` | **`+0x2058`** |
| `__TEXT.__oslogstring` | `0x4f38` | `0x51f9` | **`+0x2c1`** |
| `__AUTH_CONST.__objc_const` | `0x4df0` | `0x5038` | **`+0x248`** |
| `__AUTH_CONST.__const` | `0x2fe0` | `0x31a0` | **`+0x1c0`** |
| `__TEXT.__objc_methlist` | `0x1710` | `0x1868` | **`+0x158`** |
| `__DATA_CONST.__objc_selrefs` | `0xee0` | `0xf98` | **`+0xb8`** |
| `__AUTH.__objc_data` | `0x640` | `0x6e0` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x950` | `0x9c8` | **`+0x78`** |
| `__TEXT.__gcc_except_tab` | `0x74c` | `0x6d8` | **`-0x74`** |
| `__AUTH_CONST.__cfstring` | `0xb40` | `0xba0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x104a` | `0x109d` | **`+0x53`** |
| `__TEXT.__unwind_info` | `0xe60` | `0xe98` | **`+0x38`** |
| `__AUTH_CONST.__objc_arrayobj` | `—` | `0x18` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0xa0` | `0xb0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x98` | `0xa8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2b4` | `0x2c0` | **`+0xc`** |
| `__DATA_CONST.__objc_arraydata` | `—` | `0x8` | **`+0x8`** |

### Other Changes

```diff

-253.0.0.0.0
+266.0.0.0.0

-  Functions: 1536
-  Symbols:   1548
-  CStrings:  557
+  Functions: 1603
+  Symbols:   1597
+  CStrings:  574
Symbols:
+ -[MIBUEncodedFileInfo dealloc]
+ -[MIBUFileDecodingContext .cxx_destruct]
+ -[MIBUFileDecodingContext completed]
+ -[MIBUFileDecodingContext decoder]
+ -[MIBUFileDecodingContext fileNumber]
+ -[MIBUFileDecodingContext fileSize]
+ -[MIBUFileDecodingContext outputFile]
+ -[MIBUFileDecodingContext packetCount]
+ -[MIBUFileDecodingContext setCompleted:]
+ -[MIBUFileDecodingContext setDecoder:]
+ -[MIBUFileDecodingContext setFileNumber:]
+ -[MIBUFileDecodingContext setFileSize:]
+ -[MIBUFileDecodingContext setOutputFile:]
+ -[MIBUFileDecodingContext setPacketCount:]
+ -[MIBURaptorQFileManifest .cxx_destruct]
+ -[MIBURaptorQFileManifest basicParameters]
+ -[MIBURaptorQFileManifest extendedParameters]
+ -[MIBURaptorQFileManifest fileNumbers]
+ -[MIBURaptorQFileManifest initWithFileNumbers:basicParameters:extendedParameters:]
+ -[MIBURaptorQFileManifest isValid]
+ -[MIBURaptorQFileManifest setBasicParameters:]
+ -[MIBURaptorQFileManifest setExtendedParameters:]
+ -[MIBURaptorQFileManifest setFileNumbers:]
+ -[MIBURaptorQPacketConsumer _reassembleFileFromParts:toOutputFile:maxBytesToRead:error:]
+ -[MIBURaptorQPacketConsumer initWithEncoderSummaryFile:stopThreshold:outputFile:]
+ -[MIBURaptorQPacketConsumer initWithStopThreshold:fileManifests:outputFiles:]
+ -[MIBURaptorQPacketConsumer packetSize]
+ -[MIBURaptorQPacketProvider _activateEncodedFile:]
+ -[MIBURaptorQPacketProvider _deactivateEncodedFile:]
+ -[MIBURaptorQPacketProvider activateEncodedFile:]
+ -[MIBURaptorQPacketProvider deactivateEncodedFile:]
+ -[MIBURaptorQPacketProvider encodeInputFile:]
+ -[MIBURaptorQPacketProvider fileManifestForEncodedFile:]
+ -[MIBURaptorQPacketProvider initWithPayloadSize:repairFactor:]
+ -[SKRaptorQDecoder symbolSize]
+ GCC_except_table10
+ GCC_except_table34
+ GCC_except_table50
+ _OBJC_CLASS_$_CUOPACK
+ _OBJC_CLASS_$_MIBUFileDecodingContext
+ _OBJC_CLASS_$_MIBURaptorQFileManifest
+ _OBJC_CLASS_$_NSConstantArray
+ _OBJC_IVAR_$_MIBUFileDecodingContext._completed
+ _OBJC_IVAR_$_MIBUFileDecodingContext._decoder
+ _OBJC_IVAR_$_MIBUFileDecodingContext._fileNumber
+ _OBJC_IVAR_$_MIBUFileDecodingContext._fileSize
+ _OBJC_IVAR_$_MIBUFileDecodingContext._outputFile
+ _OBJC_IVAR_$_MIBUFileDecodingContext._packetCount
+ _OBJC_IVAR_$_MIBUMulticastSocket._packetSize
+ _OBJC_IVAR_$_MIBURaptorQFileManifest._basicParameters
+ _OBJC_IVAR_$_MIBURaptorQFileManifest._extendedParameters
+ _OBJC_IVAR_$_MIBURaptorQFileManifest._fileNumbers
+ _OBJC_IVAR_$_MIBURaptorQPacketConsumer._contextByFileNumber
+ _OBJC_IVAR_$_MIBURaptorQPacketConsumer._contexts
+ _OBJC_IVAR_$_MIBURaptorQPacketConsumer._contextsByOutputFile
+ _OBJC_IVAR_$_MIBURaptorQPacketConsumer._fileManifests
+ _OBJC_IVAR_$_MIBURaptorQPacketConsumer._packetSize
+ _OBJC_IVAR_$_MIBURaptorQPacketConsumer._stopThreshold
+ _OBJC_IVAR_$_MIBURaptorQPacketConsumer._workQueue
+ _OBJC_IVAR_$_MIBURaptorQPacketProvider._activeEncodedFiles
+ _OBJC_IVAR_$_MIBURaptorQPacketProvider._activeFileNumbers
+ _OBJC_IVAR_$_MIBURaptorQPacketProvider._fileNumbers
+ _OBJC_IVAR_$_MIBURaptorQPacketProvider._workQueue
+ _OBJC_METACLASS_$_MIBUFileDecodingContext
+ _OBJC_METACLASS_$_MIBURaptorQFileManifest
+ __OBJC_$_INSTANCE_METHODS_MIBUFileDecodingContext
+ __OBJC_$_INSTANCE_METHODS_MIBURaptorQFileManifest
+ __OBJC_$_INSTANCE_VARIABLES_MIBUFileDecodingContext
+ __OBJC_$_INSTANCE_VARIABLES_MIBURaptorQFileManifest
+ __OBJC_$_PROP_LIST_MIBUFileDecodingContext
+ __OBJC_$_PROP_LIST_MIBURaptorQFileManifest
+ __OBJC_CLASS_RO_$_MIBUFileDecodingContext
+ __OBJC_CLASS_RO_$_MIBURaptorQFileManifest
+ __OBJC_METACLASS_RO_$_MIBUFileDecodingContext
+ __OBJC_METACLASS_RO_$_MIBURaptorQFileManifest
+ ___45-[MIBURaptorQPacketProvider encodeInputFile:]_block_invoke
+ ___45-[MIBURaptorQPacketProvider encodeInputFile:]_block_invoke_2
+ ___49-[MIBURaptorQPacketProvider activateEncodedFile:]_block_invoke
+ ___50-[MIBURaptorQPacketProvider _activateEncodedFile:]_block_invoke
+ ___50-[MIBURaptorQPacketProvider _activateEncodedFile:]_block_invoke_2
+ ___51-[MIBURaptorQPacketProvider deactivateEncodedFile:]_block_invoke
+ ___52-[MIBURaptorQPacketProvider _deactivateEncodedFile:]_block_invoke
+ ___56-[MIBURaptorQPacketProvider fileManifestForEncodedFile:]_block_invoke
+ ___62-[MIBURaptorQPacketProvider initWithPayloadSize:repairFactor:]_block_invoke
+ ___77-[MIBURaptorQPacketConsumer initWithStopThreshold:fileManifests:outputFiles:]_block_invoke
+ ___88-[MIBURaptorQPacketConsumer _reassembleFileFromParts:toOutputFile:maxBytesToRead:error:]_block_invoke
+ ___block_descriptor_48_e8_32s_e12_v24?0Q8^B16ls32l8
+ ___block_descriptor_56_e8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
+ ___block_descriptor_56_e8_32s40s48r_e5_v8?0ls32l8s40l8r48l8
+ _dispatch_assert_queue_not$V2
- -[MIBURaptorQPacketConsumer initWithBasicParametersArray:extendedParametersArray:threshold:fileRanges:outputFiles:]
- -[MIBURaptorQPacketConsumer initWithEncoderSummaryFile:threshold:outputFile:]
- -[MIBURaptorQPacketConsumer reassembleFileFromParts:toOutputFile:maxBytesToRead:error:]
- -[MIBURaptorQPacketProvider _bootstrap]
- -[MIBURaptorQPacketProvider fileRangeTable]
- -[MIBURaptorQPacketProvider initWithPayloadSize:repairFactor:inputFiles:]
- -[MIBURaptorQPacketProvider rqBasicParametersArray]
- -[MIBURaptorQPacketProvider rqBasicParameters]
- -[MIBURaptorQPacketProvider rqExtendedParametersArray]
- -[MIBURaptorQPacketProvider rqExtendedParameters]
- GCC_except_table30
- GCC_except_table33
- _NSStringFromRange
- _OBJC_CLASS_$_NSValue
- _OBJC_IVAR_$_MIBURaptorQPacketConsumer._basicParametersArray
- _OBJC_IVAR_$_MIBURaptorQPacketConsumer._extendedParametersArray
- _OBJC_IVAR_$_MIBURaptorQPacketConsumer._fileCompletionStatus
- _OBJC_IVAR_$_MIBURaptorQPacketConsumer._fileRanges
- _OBJC_IVAR_$_MIBURaptorQPacketConsumer._packetCountsPerFile
- _OBJC_IVAR_$_MIBURaptorQPacketConsumer._partOutputFiles
- _OBJC_IVAR_$_MIBURaptorQPacketConsumer._partOutputFilesSizes
- _OBJC_IVAR_$_MIBURaptorQPacketConsumer._queue
- _OBJC_IVAR_$_MIBURaptorQPacketConsumer._raptorQDecoders
- _OBJC_IVAR_$_MIBURaptorQPacketConsumer._threshold
- _OBJC_IVAR_$_MIBURaptorQPacketProvider._encodedFiles
- _OBJC_IVAR_$_MIBURaptorQPacketProvider._fileRangeTable
- _OBJC_IVAR_$_MIBURaptorQPacketProvider._inputFiles
- _OBJC_IVAR_$_MIBURaptorQPacketProvider._queue
- _OBJC_IVAR_$_MIBURaptorQPacketProvider._rqBasicParameters
- _OBJC_IVAR_$_MIBURaptorQPacketProvider._rqBasicParametersArray
- _OBJC_IVAR_$_MIBURaptorQPacketProvider._rqExtendedParameters
- _OBJC_IVAR_$_MIBURaptorQPacketProvider._rqExtendedParametersArray
- ___115-[MIBURaptorQPacketConsumer initWithBasicParametersArray:extendedParametersArray:threshold:fileRanges:outputFiles:]_block_invoke
- ___36-[MIBURaptorQPacketProvider _rewind]_block_invoke
- ___38-[MIBURaptorQPacketProvider bootstrap]_block_invoke
- ___39-[MIBURaptorQPacketProvider _bootstrap]_block_invoke
- ___39-[MIBURaptorQPacketProvider _bootstrap]_block_invoke_2
- ___73-[MIBURaptorQPacketProvider initWithPayloadSize:repairFactor:inputFiles:]_block_invoke
- ___87-[MIBURaptorQPacketConsumer reassembleFileFromParts:toOutputFile:maxBytesToRead:error:]_block_invoke
- ___kCFBooleanFalse
- ___kCFBooleanTrue
CStrings:
+ "%@.part"
+ "%{public}@: Invalid size of NAN multicast session data: %ld"
+ "%{public}@: No or invalid packet size specified."
+ "%{public}@: failed to encode payload via OPACK: %{public}@"
+ "Activating encoded file: %{public}@"
+ "Creating RaptorQ decoder for fileNumber=%u, basicParam=%llu, extendedParam=%u, outputPath=%{public}@"
+ "Deactivating encoded file: %{public}@"
+ "Duplicate fileNumber %u detected, aborting bootstrap"
+ "Each file manifest must be mapped to one output file!"
+ "Encoded file (Encoded files: %lu, File numbers: %@) activated! Total active files: %lu"
+ "Encoded file (Encoded files: %lu, File numbers: %@) deactivated! Remaining active files: %lu"
+ "Encoded file [#%lu]: rqBasicParameters=%llu, rqExtendedParameters=%u"
+ "Encoding file: %{public}@"
+ "Failed to decode file %lu: %{public}@"
+ "Failed to decode multicast data via NSKeyedUnarchiver: %{public}@"
+ "Failed to decode multicast data via OPACK: %{public}@"
+ "Failed to encode file: %{public}@ error: %{public}@"
+ "Failed to initialize RaptorQ decoder for file %u: %{public}@"
+ "Failed to read directory contents: %{public}@ error: %{public}@"
+ "File %lu received %lu packets in total"
+ "File %{public}@ was already split into %lu parts, reusing existing parts"
+ "Initialize packet consumer with stop threshold: %lu, file manifests: %lu, output files: %{public}@"
+ "Initialize packet provider with payload size: %lu, repair factor: %lu"
+ "Input file was already activated."
+ "Input file was already deactivated."
+ "Input file was not yet encoded."
+ "Invalid file manifest provided."
+ "Invalid size of NAN multicast session data: %ld"
+ "NAN publisher received multicast data which decodes to: %{public}@"
+ "PacketSize"
+ "Processing output file with %lu part files: %{public}@"
+ "RaptorQ decoder successfully created! File size: %lu, Symbol size: %lu"
+ "Reassembling ouput file: %{public}@ from part files: %{public}@"
+ "Short read for encoded file %{public}@ (file %u, block %u): expected %lu, got %lu bytes."
+ "Starting to decode file %lu..."
+ "Successfully decoded file %lu to output: %{public}@, discarded packets: %lu"
+ "Total RaptorQ decoders created: %lu"
+ "Unexpected RaptorQ decoder symbol size: %lu"
+ "Unexpected size of data read from socket: %ld (expected: %lu)"
+ "[file%lu=%lu] "
+ "v24@?0Q8^B16"
- "\f"
- "Bootstrap complete: %lu input files, %lu encoded files total"
- "Created %lu decoders for multi-file transfer"
- "Creating RaptorQ encoder..."
- "Creating decoder for file %lu , partFile %lu with basicParam=%llu, extendedParam=%u, output=%{public}@"
- "Failed to decode part file %lu: %{public}@"
- "Failed to encode input file: %{public}@"
- "Failed to initialize RaptorQ decoder for file %lu part file %lu: %{public}@"
- "Failed to initialize RaptorQ encoder: %{public}@"
- "Failed to initialize file handle from: %{public}@ error: %{public}@"
- "File %lu received %lu packets total"
- "File %lu: rqBasicParameters=%llu, rqExtendedParameters=%u"
- "Initialize packet consumer for multi-file transfer with %lu files, threshold: %lu, file ranges: %{public}@ output files: %{public}@"
- "Initialize packet provider with payload size: %lu, repair factor: %lu, input files: %{public}@"
- "Input file '%{public}@' assigned with range '%{public}@'"
- "Invalid decoder for fileNumber %u (expected 0-%lu)"
- "NAN publisher received multicast data blob which decodes to: %@"
- "Parameter arrays: basicParamsArray has %lu elements, extendedParamsArray has %lu elements"
- "RaptorQ encoder not created."
- "Reassembling part files %{public}@ into %{public}@"
- "Starting decode for file %lu (received %lu packets)..."
- "Successfully decoded part file %lu to %{public}@, discarded %lu packets"
- "Unexpected size of data read from socket: %ld (expected 1032)"
- "file%lu=%lu "
```
