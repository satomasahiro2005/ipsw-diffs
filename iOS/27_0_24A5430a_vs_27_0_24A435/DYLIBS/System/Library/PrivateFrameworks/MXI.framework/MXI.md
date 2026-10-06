## MXI

> `/System/Library/PrivateFrameworks/MXI.framework/MXI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f844` | `0x4f9b4` | **`+0x170`** |
| `__TEXT.__unwind_info` | `0xe00` | `0xdf8` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0x765c` | `0x7660` | **`+0x4`** |

### Other Changes

```text
Functions:
~ sub_28d7a01b4 -> sub_28e4e61b4 : 2300 -> 2256
~ sub_28d7a0ab0 -> sub_28e4e6a84 : 1148 -> 1184
~ sub_28d7a0f2c -> sub_28e4e6f24 : 768 -> 764
~ sub_28d7a1a74 -> sub_28e4e7a68 : 128 -> 132
~ sub_28d7a2dac -> sub_28e4e8da4 : 784 -> 800
~ sub_28d7a30bc -> sub_28e4e90c4 : 616 -> 632
~ sub_28d7a34c4 -> sub_28e4e94dc : 256 -> 260
~ sub_28d7a3724 -> sub_28e4e9740 : 1628 -> 1660
~ sub_28d7a3d80 -> sub_28e4e9dbc : 184 -> 192
~ sub_28d7a4480 -> sub_28e4ea4c4 : 196 -> 204
~ sub_28d7a4570 -> sub_28e4ea5bc : 1032 -> 1040
~ sub_28d7a5a2c -> sub_28e4eba80 : 736 -> 752
~ sub_28d7a904c -> sub_28e4ef0b0 : 284 -> 288
~ sub_28d7aeee0 -> sub_28e4f4f48 : 284 -> 288
~ sub_28d7aeffc -> sub_28e4f5068 : 284 -> 288
~ sub_28d7af118 -> sub_28e4f5188 : 372 -> 376
~ sub_28d7c6bf0 -> sub_28e50cc64 : 256 -> 260
~ sub_28d7c6e00 -> sub_28e50ce78 : 256 -> 260
~ sub_28d7c746c -> sub_28e50d4e8 : 304 -> 308
~ sub_28d7c7a7c -> sub_28e50dafc : 140 -> 144
~ sub_28d7ceecc -> sub_28e514f50 : 296 -> 300
~ __ZNK5tiled9Processor7GetMeshEPU15__autoreleasingP7NSError : 4632 -> 4628
~ __Z26init_block_size_descriptorjjjbjfR21block_size_descriptor : 5356 -> 5372
~ __Z14compress_blockRK16astcenc_contextiRK11image_blockPhR27compression_working_buffers : 3860 -> 3872
~ sub_28d7dd788 -> sub_28e523828 : 152 -> 156
~ __Z16load_image_block15astcenc_profileRK13astcenc_imageR11image_blockRK21block_size_descriptorjjjRK15astcenc_swizzle : 1244 -> 1264
~ __Z25load_image_block_fast_ldr15astcenc_profileRK13astcenc_imageR11image_blockRK21block_size_descriptorjjjRK15astcenc_swizzle : 496 -> 500
~ __Z17store_image_blockR13astcenc_imageRK11image_blockRK21block_size_descriptorjjjRK15astcenc_swizzle : 1780 -> 1784
~ __Z30find_best_partition_candidatesRK21block_size_descriptorRK11image_blockjjPjj : 4044 -> 4048
~ __Z20pack_color_endpoints7vfloat4S_S_S_iPh12quant_method : 4932 -> 5084
~ __Z10encode_ise12quant_methodjPKhPhj : 1804 -> 1864
~ __Z22astcenc_get_block_infoP15astcenc_contextPKhP18astcenc_block_info : 1292 -> 1284
~ __Z30compute_ideal_endpoint_formatsRK14partition_infoRK11image_blockRK9endpointsPKaPKfjjjPA4_hPiP12quant_methodSG_R27compression_working_buffers : 6156 -> 6100
~ __Z29compute_pixel_region_varianceR16astcenc_contextiRK17pixel_region_args : 2732 -> 2752
~ __Z30recompute_ideal_colors_2planesRK11image_blockRK21block_size_descriptorRK15decimation_infoPKhS9_R9endpointsR7vfloat4SD_i : 2072 -> 2076
```
