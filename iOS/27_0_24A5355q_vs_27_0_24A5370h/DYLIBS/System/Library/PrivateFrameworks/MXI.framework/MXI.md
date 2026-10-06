## MXI

> `/System/Library/PrivateFrameworks/MXI.framework/MXI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xbcdb` | `0xbdca` | **`+0xef`** |
| `__AUTH_CONST.__cfstring` | `0x4000` | `0x4080` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x75d4` | `0x764c` | **`+0x78`** |
| `__TEXT.__text` | `0x50d8c` | `0x50d64` | **`-0x28`** |
| `__TEXT.__const` | `0x9f20` | `0x9f40` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x620` | `0x638` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xe00` | `0xe08` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-48.0.0.0.0
+48.0.1.0.0

-  Symbols:   490
-  CStrings:  1164
+  Symbols:   493
+  CStrings:  1169
Symbols:
+ _MXISceneBuilderConfigurationSharpness
+ _MXISceneBuilderConfigurationSharpnessDither
+ _MXISceneBuilderConfigurationSharpnessFarScale
Functions:
~ sub_2866e4784 -> sub_287c20784 : 252 -> 244
~ sub_2866e4cd0 -> sub_287c20cc8 : 1952 -> 1948
~ sub_2866e6280 -> sub_287c22274 : 2260 -> 2300
~ sub_2866e6b54 -> sub_287c22b70 : 1268 -> 1148
~ sub_2866e7048 -> sub_287c22fec : 792 -> 768
~ sub_2866e7ba8 -> sub_287c23b34 : 132 -> 128
~ sub_2866e7d9c -> sub_287c23d24 : 1292 -> 1252
~ sub_2866e83d8 -> sub_287c24338 : 156 -> 124
~ sub_2866e86f8 -> sub_287c24638 : 1292 -> 1300
~ sub_2866e9898 -> sub_287c257e0 : 1644 -> 1628
~ sub_2866ea6c8 -> sub_287c26600 : 248 -> 204
~ sub_2866ea7ec -> sub_287c266f8 : 1036 -> 1032
~ sub_2866eaf70 -> sub_287c26e78 : 500 -> 504
~ sub_2866eb164 -> sub_287c27070 : 248 -> 288
~ sub_2866eb25c -> sub_287c27190 : 128 -> 140
~ sub_2866eb7cc -> sub_287c2770c : 1208 -> 1192
~ sub_2866ebc84 -> sub_287c27bb4 : 760 -> 736
~ sub_2866ee5c0 -> sub_287c2a4d8 : 3408 -> 3404
~ sub_2866f1924 -> sub_287c2d838 : 264 -> 284
~ sub_2866f45ac -> sub_287c304d4 : 2972 -> 3044
~ sub_2866f65f0 -> sub_287c32560 : 1456 -> 1440
~ sub_2866f827c -> sub_287c341dc : 4768 -> 4684
~ sub_28670016c -> sub_287c3c078 : 1020 -> 1016
~ sub_286700778 -> sub_287c3c680 : 132 -> 128
~ sub_2867027c4 -> sub_287c3e6c8 : 1252 -> 1744
~ sub_286703ba8 -> sub_287c3fc98 : 3720 -> 4016
~ sub_286706550 -> sub_287c42768 : 1572 -> 1568
~ sub_2867083ac -> sub_287c445c0 : 2512 -> 2496
~ sub_286708d7c -> sub_287c44f80 : 4528 -> 4504
~ sub_28670d204 -> sub_287c493f0 : 472 -> 484
~ sub_28670f660 -> sub_287c4b858 : 2116 -> 2124
~ sub_28670fea4 -> sub_287c4c0a4 : 2328 -> 2352
~ sub_28671187c -> sub_287c4da94 : 2300 -> 2308
~ __ZN5tiled9Processor6CreateEPU19objcproto9MTLDevice11objc_objectNS_4TypeEjNS_5RangeERKNS_6ConfigEPU15__autoreleasingP7NSError : 3656 -> 3668
~ __ZN5tiled9Processor8AddLayerEPU27objcproto16MTLCommandBuffer11objc_objectjNS_4FaceEfPU21objcproto10MTLTexture11objc_objectS5_S5_NS_11DepthParamsEf : 8720 -> 8840
~ __ZNK5tiled9Processor7GetMeshEPU15__autoreleasingP7NSError : 4788 -> 4804
~ __ZNK5tiled9Processor8GetAtlasEPU15__autoreleasingPU21objcproto10MTLTexture11objc_objectPjbbfjPU15__autoreleasingP7NSError : 3200 -> 3192
~ __ZNK5tiled9Processor8GetAtlasERNSt3__16vectorIU8__strongPU21objcproto10MTLTexture11objc_objectNS1_9allocatorIS5_EEEEbbfjPU15__autoreleasingP7NSError : 4000 -> 4028
~ __ZN5tiled1d9Processor8AddLayerEPU27objcproto16MTLCommandBuffer11objc_objectjNS0_4FaceEfPU21objcproto10MTLTexture11objc_objectS6_NS0_11DepthParamsEf : 6720 -> 6708
~ __ZNK5tiled1d9Processor7GetMeshEPU15__autoreleasingP7NSError : 1744 -> 1748
~ __ZNK5tiled1d9Processor8GetAtlasEPU15__autoreleasingPU21objcproto10MTLTexture11objc_objectPjbbfjPU15__autoreleasingP7NSError : 3168 -> 3160
~ __ZNK5tiled1d9Processor8GetAtlasERNSt3__16vectorIU8__strongPU21objcproto10MTLTexture11objc_objectNS2_9allocatorIS6_EEEEbbfjPU15__autoreleasingP7NSError : 3408 -> 3364
~ sub_28671dadc -> sub_287c59d68 : 1600 -> 1596
~ sub_28671e1d8 -> sub_287c5a460 : 1748 -> 1760
~ sub_28671eab4 -> sub_287c5ad48 : 1748 -> 1740
~ __Z26init_block_size_descriptorjjjbjfR21block_size_descriptor : 5696 -> 5356
~ __Z14compress_blockRK16astcenc_contextiRK11image_blockPhR27compression_working_buffers : 3976 -> 3860
~ __ZN5image7ReadKTXEPNS_6ReaderEPU19objcproto9MTLDevice11objc_objectbb : 1612 -> 1616
~ __Z8WriteKTXPN5image6WriterEP7NSArrayIPU21objcproto10MTLTexture11objc_objectE14MTLTextureType : 1536 -> 1544
~ __Z20symbolic_to_physicalRK21block_size_descriptorRK25symbolic_compressed_blockPh : 1308 -> 1396
~ __Z20physical_to_symbolicRK21block_size_descriptorPKhR25symbolic_compressed_block : 1500 -> 1548
~ __Z16load_image_block15astcenc_profileRK13astcenc_imageR11image_blockRK21block_size_descriptorjjjRK15astcenc_swizzle : 1204 -> 1244
~ __Z25load_image_block_fast_ldr15astcenc_profileRK13astcenc_imageR11image_blockRK21block_size_descriptorjjjRK15astcenc_swizzle : 480 -> 496
~ __Z17store_image_blockR13astcenc_imageRK11image_blockRK21block_size_descriptorjjjRK15astcenc_swizzle : 1804 -> 1836
~ __Z23get_2d_percentile_tablejj : 540 -> 528
~ __Z22prepare_angular_tablesv : 152 -> 148
~ __Z32compute_angular_endpoints_1planebRK21block_size_descriptorPKfjR27compression_working_buffers : 416 -> 424
~ __Z33compute_angular_endpoints_2planesRK21block_size_descriptorPKfjR27compression_working_buffers : 528 -> 512
~ __Z30find_best_partition_candidatesRK21block_size_descriptorRK11image_blockjjPjj : 4088 -> 4044
~ __Z32compute_avgs_and_dirs_3_comp_rgbRK14partition_infoRK11image_blockP17partition_metrics : 1480 -> 1484
~ __Z28compute_avgs_and_dirs_2_compRK14partition_infoRK11image_blockjjP17partition_metrics : 416 -> 412
~ __Z26compute_error_squared_rgbaRK14partition_infoRK11image_blockPK15processed_line4S7_PfRfS9_ : 972 -> 960
~ __Z25compute_error_squared_rgbRK14partition_infoRK11image_blockP16partition_lines3RfS7_ : 848 -> 840
~ __Z20pack_color_endpoints7vfloat4S_S_S_iPh12quant_method : 5008 -> 4932
~ __Z10encode_ise12quant_methodjPKhPhj : 1800 -> 1868
~ __Z10decode_ise12quant_methodjPKhPhj : 828 -> 824
~ __Z19astcenc_config_init15astcenc_profilejjjfjP14astcenc_config : 1520 -> 1500
~ __Z22astcenc_get_block_infoP15astcenc_contextPKhP18astcenc_block_info : 1300 -> 1292
~ __Z30compute_ideal_endpoint_formatsRK14partition_infoRK11image_blockRK9endpointsPKaPKfjjjPA4_hPiP12quant_methodSG_R27compression_working_buffers : 6184 -> 6156
~ __Z29compute_pixel_region_varianceR16astcenc_contextiRK17pixel_region_args : 3104 -> 2732
~ __Z39compute_ideal_colors_and_weights_1planeRK11image_blockRK14partition_infoR21endpoints_and_weights : 904 -> 888
~ __Z34compute_error_of_weight_set_1planeRK21endpoints_and_weightsRK15decimation_infoPKf : 312 -> 324
~ __Z35compute_error_of_weight_set_2planesRK21endpoints_and_weightsS1_RK15decimation_infoPKfS6_ : 456 -> 476
~ __Z36compute_ideal_weights_for_decimationRK21endpoints_and_weightsRK15decimation_infoPf : 884 -> 868
~ __Z40compute_quantized_weights_for_decimationRK15decimation_infoffPKfPfPh12quant_method : 472 -> 468
~ __Z30recompute_ideal_colors_2planesRK11image_blockRK21block_size_descriptorRK15decimation_infoPKhS9_R9endpointsR7vfloat4SD_i : 2104 -> 2072
~ __Z14unpack_weightsRK21block_size_descriptorRK25symbolic_compressed_blockRK15decimation_infobPiS8_ : 336 -> 364
~ __Z25decompress_symbolic_block15astcenc_profileRK21block_size_descriptoriiiRK25symbolic_compressed_blockR11image_block : 2012 -> 2040
~ __Z40compute_symbolic_block_difference_2planeRK14astcenc_configRK21block_size_descriptorRK25symbolic_compressed_blockRK11image_block : 684 -> 716
~ __Z40compute_symbolic_block_difference_1planeRK14astcenc_configRK21block_size_descriptorRK25symbolic_compressed_blockRK11image_block : 852 -> 840
~ __Z51compute_symbolic_block_difference_1plane_1partitionRK14astcenc_configRK21block_size_descriptorRK25symbolic_compressed_blockRK11image_block : 804 -> 820
CStrings:
+ "/+1"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:442: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderBase.mm:249"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderBase.mm:260"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderBase.mm:279"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderBase.mm:443"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderBase.mm:454"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderBase.mm:462"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderBase.mm:630"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderBase.mm:635"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderTiled.mm:356"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderTiled.mm:465"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderTiled.mm:694"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderTiled.mm:699"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1086"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1105"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1152"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1209"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1401"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1434"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1465"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1507"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1521"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1593"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1606"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1645"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1700"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1705"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1709"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1714"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1718"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1744"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1753"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1768"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1793"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1826"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1882"
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1895"
+ "Mismatched number of atlas views (%zu), expected (%d)"
+ "[MXI.framework/MXISceneBuilderBase.mm:182] getLayerRange should not be used if layer depths was overridden"
+ "[MXI.framework/MXISceneBuilderBase.mm:190] getLayerViewMatrix should not be used if layer depths was overridden"
+ "[MXI.framework/MXISceneBuilderBase.mm:248] Could not capture color texture"
+ "[MXI.framework/MXISceneBuilderBase.mm:259] Could not capture color texture"
+ "[MXI.framework/MXISceneBuilderBase.mm:442] Could not capture color texture"
+ "[MXI.framework/MXISceneBuilderBase.mm:453] Could not capture depth texture"
+ "[MXI.framework/MXISceneBuilderBase.mm:461] Could not capture blend texture"
+ "[MXI.framework/MXISceneBuilderBase.mm:547] Unknown color primaries specified %@"
+ "[MXI.framework/MXISceneBuilderBase.mm:552] Unknown color primaries specified %@"
+ "[MXI.framework/MXISceneBuilderBase.mm:567] Layer depths should be overridden with NSArray<NSNumber*>, but the value is not NSArray"
+ "[MXI.framework/MXISceneBuilderBase.mm:569] Layer depths array size (%u) shold match number of layers (%u)"
+ "[MXI.framework/MXISceneBuilderBase.mm:576] Failed parsing depth for layer %u"
+ "[MXI.framework/MXISceneBuilderBase.mm:629] Could not capture color texture"
+ "[MXI.framework/MXISceneBuilderBase.mm:634] Could not capture normal texture"
+ "[MXI.framework/MXISceneBuilderTiled.mm:195] Cannot recognize ASTC quality option %@"
+ "[MXI.framework/MXISceneBuilderTiled.mm:264] Failed on creating TiledProcessor"
+ "[MXI.framework/MXISceneBuilderTiled.mm:279] Failed on creating BackLayer"
+ "[MXI.framework/MXISceneBuilderTiled.mm:321] Unexpected refinement settings"
+ "[MXI.framework/MXISceneBuilderTiled.mm:355] Could not add layer (%ld), face (%ld)"
+ "[MXI.framework/MXISceneBuilderTiled.mm:373] only one of the refinement options are given."
+ "[MXI.framework/MXISceneBuilderTiled.mm:378] refinement warp option is not a valid matrix_float3x3"
+ "[MXI.framework/MXISceneBuilderTiled.mm:383] Refinement weights, aotfrImageOption, or its build options are missing"
+ "[MXI.framework/MXISceneBuilderTiled.mm:388] AOTFR coefficients, projection matrix, or its build options are missing"
+ "[MXI.framework/MXISceneBuilderTiled.mm:404] Failed mip mapping the refinement image"
+ "[MXI.framework/MXISceneBuilderTiled.mm:409] Failed mip mapping the aotfr image"
+ "[MXI.framework/MXISceneBuilderTiled.mm:443] Could not create the atlas"
+ "[MXI.framework/MXISceneBuilderTiled.mm:449] Could not create the atlas"
+ "[MXI.framework/MXISceneBuilderTiled.mm:482] MXI min depth is too low! depth range (%g, %g)"
+ "[MXI.framework/MXISceneBuilderTiled.mm:571] Failed generating backing plane"
+ "[MXI.framework/MXISceneBuilderTiled.mm:688] MTLCommandBuffer failed"
+ "[MXI.framework/MXISceneBuilderTiled.mm:740] MTLCommandBuffer failed"
+ "[Tiled/TiledProcessor.mm:1160] Tiled Processor destroyed."
+ "[Tiled/TiledProcessor.mm:1644] Could not compress to ASTC"
+ "[Tiled/TiledProcessor.mm:1881] Could not compress to ASTC"
+ "[Tiled/TiledProcessor.mm:1894] Could not compress to ASTC"
+ "[Tiled/TiledProcessor.mm:376] [TiledProcessor] WARNING: nil MTLBinaryArchive for mxi_archive, error %@"
+ "[Tiled/TiledProcessor.mm:429] Packing in compressed atlas is not supported, continuing without it."
+ "[Tiled/TiledProcessor.mm:519] Unexpected thread execution width"
+ "[Tiled/TiledProcessor.mm:522] Mismatched max threads per threadgroup"
+ "[Tiled/TiledProcessor.mm:589] OTFR is not supporteed with pack in compressed atlas."
+ "[Tiled/TiledProcessor.mm:641] Number of atlas slices exceeds MAX_FIXED_ATLAS_SLICES."
+ "[Tiled/TiledProcessor.mm:678] Failed to allocate atlas."
+ "[Tiled/TiledProcessor.mm:694] Failed to allocate atlas view"
+ "[Tiled/TiledProcessor.mm:707] Failed to allocate atlas."
+ "[Tiled/TiledProcessor.mm:724] Failed to allocate atlas view"
+ "[Tiled/TiledProcessor.mm:744] Unexpected color texture width"
+ "[Tiled/TiledProcessor.mm:745] Unexpected color texture height"
+ "[Tiled/TiledProcessor.mm:851] Unexpected refinement settings"
+ "[Tiled/TiledProcessor.mm:965] Not enough threads per threadgroup for tile size"
+ "sharpness"
+ "sharpness_dither"
+ "sharpness_far_scale"
- "/)1"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:413: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:418: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:441: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderBase.mm:246"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderBase.mm:257"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderBase.mm:276"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderBase.mm:440"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderBase.mm:451"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderBase.mm:459"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderBase.mm:627"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderBase.mm:632"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderTiled.mm:349"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderTiled.mm:458"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderTiled.mm:687"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/MXI/src/MXISceneBuilderTiled.mm:692"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1063"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1082"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1129"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1186"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1378"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1411"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1442"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1475"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1484"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1524"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1583"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1622"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1677"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1682"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1687"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1691"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1717"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1726"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1741"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1766"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1799"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1855"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/MXI/Tiled/src/TiledProcessor.mm:1868"
- "[MXI.framework/MXISceneBuilderBase.mm:179] getLayerRange should not be used if layer depths was overridden"
- "[MXI.framework/MXISceneBuilderBase.mm:187] getLayerViewMatrix should not be used if layer depths was overridden"
- "[MXI.framework/MXISceneBuilderBase.mm:245] Could not capture color texture"
- "[MXI.framework/MXISceneBuilderBase.mm:256] Could not capture color texture"
- "[MXI.framework/MXISceneBuilderBase.mm:439] Could not capture color texture"
- "[MXI.framework/MXISceneBuilderBase.mm:450] Could not capture depth texture"
- "[MXI.framework/MXISceneBuilderBase.mm:458] Could not capture blend texture"
- "[MXI.framework/MXISceneBuilderBase.mm:544] Unknown color primaries specified %@"
- "[MXI.framework/MXISceneBuilderBase.mm:549] Unknown color primaries specified %@"
- "[MXI.framework/MXISceneBuilderBase.mm:564] Layer depths should be overridden with NSArray<NSNumber*>, but the value is not NSArray"
- "[MXI.framework/MXISceneBuilderBase.mm:566] Layer depths array size (%u) shold match number of layers (%u)"
- "[MXI.framework/MXISceneBuilderBase.mm:573] Failed parsing depth for layer %u"
- "[MXI.framework/MXISceneBuilderBase.mm:626] Could not capture color texture"
- "[MXI.framework/MXISceneBuilderBase.mm:631] Could not capture normal texture"
- "[MXI.framework/MXISceneBuilderTiled.mm:191] Cannot recognize ASTC quality option %@"
- "[MXI.framework/MXISceneBuilderTiled.mm:257] Failed on creating TiledProcessor"
- "[MXI.framework/MXISceneBuilderTiled.mm:272] Failed on creating BackLayer"
- "[MXI.framework/MXISceneBuilderTiled.mm:314] Unexpected refinement settings"
- "[MXI.framework/MXISceneBuilderTiled.mm:348] Could not add layer (%ld), face (%ld)"
- "[MXI.framework/MXISceneBuilderTiled.mm:366] only one of the refinement options are given."
- "[MXI.framework/MXISceneBuilderTiled.mm:371] refinement warp option is not a valid matrix_float3x3"
- "[MXI.framework/MXISceneBuilderTiled.mm:376] Refinement weights, aotfrImageOption, or its build options are missing"
- "[MXI.framework/MXISceneBuilderTiled.mm:381] AOTFR coefficients, projection matrix, or its build options are missing"
- "[MXI.framework/MXISceneBuilderTiled.mm:397] Failed mip mapping the refinement image"
- "[MXI.framework/MXISceneBuilderTiled.mm:402] Failed mip mapping the aotfr image"
- "[MXI.framework/MXISceneBuilderTiled.mm:436] Could not create the atlas"
- "[MXI.framework/MXISceneBuilderTiled.mm:442] Could not create the atlas"
- "[MXI.framework/MXISceneBuilderTiled.mm:475] MXI min depth is too low! depth range (%g, %g)"
- "[MXI.framework/MXISceneBuilderTiled.mm:564] Failed generating backing plane"
- "[MXI.framework/MXISceneBuilderTiled.mm:681] MTLCommandBuffer failed"
- "[MXI.framework/MXISceneBuilderTiled.mm:733] MTLCommandBuffer failed"
- "[Tiled/TiledProcessor.mm:1137] Tiled Processor destroyed."
- "[Tiled/TiledProcessor.mm:1621] Could not compress to ASTC"
- "[Tiled/TiledProcessor.mm:1854] Could not compress to ASTC"
- "[Tiled/TiledProcessor.mm:1867] Could not compress to ASTC"
- "[Tiled/TiledProcessor.mm:373] [TiledProcessor] WARNING: nil MTLBinaryArchive for mxi_archive, error %@"
- "[Tiled/TiledProcessor.mm:423] Packing in compressed atlas is not supported, continuing without it."
- "[Tiled/TiledProcessor.mm:513] Unexpected thread execution width"
- "[Tiled/TiledProcessor.mm:516] Mismatched max threads per threadgroup"
- "[Tiled/TiledProcessor.mm:583] OTFR is not supporteed with pack in compressed atlas."
- "[Tiled/TiledProcessor.mm:621] Number of atlas slices exceeds MAX_FIXED_ATLAS_SLICES."
- "[Tiled/TiledProcessor.mm:658] Failed to allocate atlas."
- "[Tiled/TiledProcessor.mm:674] Failed to allocate atlas view"
- "[Tiled/TiledProcessor.mm:687] Failed to allocate atlas."
- "[Tiled/TiledProcessor.mm:704] Failed to allocate atlas view"
- "[Tiled/TiledProcessor.mm:724] Unexpected color texture width"
- "[Tiled/TiledProcessor.mm:725] Unexpected color texture height"
- "[Tiled/TiledProcessor.mm:831] Unexpected refinement settings"
- "[Tiled/TiledProcessor.mm:942] Not enough threads per threadgroup for tile size"
```
