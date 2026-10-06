## AppleJPEG

> `/System/Library/PrivateFrameworks/AppleJPEG.framework/AppleJPEG`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3a91c` | `0x3ab7c` | **`+0x260`** |
| `__TEXT.__unwind_info` | `0x888` | `0x890` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 657
+  Functions: 658
Functions:
~ _applejpeg_decode_destroy : 320 -> 328
~ _aj_istream_read_bytes_be : 176 -> 180
~ _aj_read_dqt : 400 -> 396
~ _aj_read_sof : 744 -> 768
~ _aj_read_dht : 716 -> 720
~ _aj_check_huffman_tables : 164 -> 160
~ _aj_imageinfo_init : 164 -> 176
~ _dec_free_allocations : 192 -> 204
~ _aj_huffman_decode_init : 1416 -> 1420
~ _aj_check_components_and_decimation : 848 -> 872
~ _aj_huffman_is_standard_table : 124 -> 128
~ _aj_check_single_huffman_table : 232 -> 248
~ _aj_huffman_decode_get_standard_table : 44 -> 48
+ sub_24e987c9c
~ _aj_block_pack : 1428 -> 1424
~ _aj_block_unpack : 1480 -> 1452
~ _arithmetic_encode_symbols : 620 -> 612
~ _init_cum_prob : 296 -> 308
~ _renormalize_probs : 300 -> 296
~ _aj_encode_buffers_progressive : 916 -> 904
~ _aj_concatenate_scans : 384 -> 380
~ _aj_encode_all_mt : 1312 -> 1332
~ _mt_write_callback : 164 -> 176
~ _set_plugin_config : 212 -> 232
~ _aj_init_decode_jobs : 1808 -> 1804
~ _aj_decode_init : 4196 -> 4232
~ _init_ra_table : 1072 -> 1112
~ _aj_compute_buffer_sizes : 604 -> 616
~ _aj_init_input_states : 244 -> 260
~ _fill_image_edges : 1172 -> 1160
~ _init_prog_scans : 1788 -> 1768
~ _init_blockdec : 524 -> 552
~ _aj_decode_init_index : 600 -> 624
~ _scan_is_needed : 144 -> 152
~ _init_scan : 796 -> 804
~ _aj_bufferproc_crop : 736 -> 744
~ _aj_huffman_encode_init_baseline : 76 -> 80
~ _aj_huffman_fill_standard_counts_values : 76 -> 80
~ _aj_find_and_handle_markers : 476 -> 484
~ _aj_mcu_decode : 1900 -> 1884
~ _aj_mcu_decode_index : 912 -> 888
~ _aj_mcu_decode_progressive : 2136 -> 2132
~ _loop_through_image : 228 -> 232
~ _get_row_lpf : 616 -> 620
~ _fill_coeff_buffer : 616 -> 612
~ _move_to_mcu : 1684 -> 1676
~ _aj_decode_all_mt : 700 -> 724
~ _aj_create_ra_table_mt : 552 -> 572
~ _fill_mcu_row_with_gray : 248 -> 260
~ _aj_write_sof : 308 -> 336
~ _aj_write_dht : 708 -> 740
~ _aj_write_single_dht : 252 -> 260
~ _aj_write_dqt : 328 -> 320
~ _aj_write_sos_baseline : 248 -> 268
~ _aj_write_sos_progressive : 304 -> 324
~ _aj_write_jpeg_headers : 440 -> 444
~ _aj_huffman_decode_skip_val_slow : 516 -> 520
~ _aj_prog_encode_AC_refine : 840 -> 832
~ _huffman_gen : 596 -> 592
~ _do_compress_lossless_neon : 5576 -> 5476
~ _do_compress_lossless : 1384 -> 1372
~ _encodeWriteHuffTable : 272 -> 284
~ _aj_mosquito_spray : 1864 -> 1740
~ _aj_block_dequantize_12bit : 304 -> 276
~ _prog_huff_decode_loop : 276 -> 284
~ _aj_prog_decode_AC_first : 624 -> 640
~ _aj_prog_decode_AC_refine : 1132 -> 1148
~ _aj_baseline_multiscan_decode_scan : 1004 -> 1012
~ _aj_mosquito_spray_enable : 144 -> 140
~ _aj_rotate_ip : 1028 -> 1024
~ _transpose_2bpp : 208 -> 224
~ _transpose_3bpp : 240 -> 248
~ _mirror_horizontal_1bpp : 104 -> 100
~ _aj_fill_coeffblock_from_scan_properties : 352 -> 360
~ _aj_row_translate : 760 -> 728
~ _aj_paint_region : 424 -> 428
~ _aj_reset_texture_buffer_ptrs : 224 -> 220
~ _aj_get_rowptrs : 192 -> 204
~ _aj_return_rowptrs : 144 -> 148
~ _aj_huffman_encode_init_lookups : 604 -> 608
~ _aj_lossless_decode_all : 2696 -> 2708
~ _aj_dct_prescale_qtable : 68 -> 56
~ _aj_get_qtable_for_quality : 164 -> 156
~ _aj_bufferproc_resize : 1728 -> 1732
~ _aj_bufferproc_resize_init : 1616 -> 1596
~ _aj_bufferproc_resize_terminate : 304 -> 324
~ _outbuffer_drain : 460 -> 452
~ _init_reduce : 1692 -> 1804
~ _aj_reduce_init_pack : 612 -> 596
~ _determine_max_bits : 164 -> 156
~ _applejpeg_recode_set_option_quantization_tables : 76 -> 72
~ _recode_all : 3248 -> 3240
~ _do_recode_plugin : 3340 -> 3360
~ _pad_region : 220 -> 244
~ _aj_encode_release_scan_buffers : 136 -> 132
~ _aj_reset_row_ptrs : 264 -> 260
~ _aj_allocate_enc_buffers : 272 -> 300
~ _aj_encode_init : 4456 -> 4376
~ _init_component : 308 -> 300
~ _aj_encode_reset_session : 476 -> 480
~ _aj_istream_read_bytes_le : 188 -> 192
~ _aj_istream_state_serialize : 72 -> 64
~ _aj_istream_state_deserialize : 80 -> 72
~ _aj_icol_row_420_rgb_12bit_generic : 504 -> 484
~ _aj_icol_row_422_to_biplanar : 316 -> 300
~ _aj_icol_row_420_to_biplanar : 712 -> 664
~ _aj_icol_row_440_to_biplanar : 216 -> 200
~ _aj_icol_row_all_to_gray : 140 -> 156
~ _aj_icol_row_all_to_gray_12bit : 140 -> 156
~ _aj_icol_row_gray_to_yuyv : 220 -> 216
~ _aj_icol_row_gray_to_yuv : 160 -> 156
~ _aj_icol_row_gray_to_color_generic : 352 -> 348
~ _aj_icol_row_gray_to_rgb : 160 -> 156
~ _aj_icol_row_gray_to_rgb_12bit : 160 -> 156
~ _aj_icol_row_gray_to_rgba : 168 -> 164
~ _aj_icol_row_gray_to_rgba_12bit : 168 -> 164
~ _aj_icol_mcurow_default : 1092 -> 1060
~ _invcol_wrapper : 860 -> 892
~ _aj_icol_mcurow_semiplanar444 : 576 -> 584
~ _aj_icol_mcurow_semiplanar422 : 592 -> 640
~ _aj_icol_mcurow_semiplanar4X0 : 1604 -> 1624
~ _arithmetic_decode_symbols : 664 -> 672
~ _arithmetic_encode_symbols : 536 -> 532
~ _init_cum_prob : 292 -> 328
~ _probs_to_cum : 92 -> 108
~ _scale_cumprob : 128 -> 140
~ _cum_to_probs : 104 -> 108
~ _aj_init_QT_as_no_op : 44 -> 48
~ _aj_init_QT_aanIDCT : 216 -> 204
~ _aj_idct_s2_2x4 : 360 -> 380
~ _aj_idct_s2_4x2 : 428 -> 460
~ _basic_idct_s1_12bit : 832 -> 880
~ _aj_idct_s1_16x8_bilinear_12bit : 272 -> 284
~ _aj_idct_s1_4x8_12bit : 144 -> 148
~ _aj_idct_s2_12bit : 460 -> 492
~ _aj_idct_s2_2x4_12bit : 368 -> 388
~ _aj_idct_s2_4x2_12bit : 424 -> 456
~ _aj_check_options : 1584 -> 1592
~ _aj_rowbuffer_add_block : 320 -> 324
~ _aj_rowbuffer_destroy : 132 -> 140
~ _aj_rowbuffer_get_buffer : 152 -> 168
~ _find_rowbuffer_for_pointer : 152 -> 160
~ _applejpeg_reduce_close : 236 -> 244
~ _read_variable_number_of_bytes_big_endian : 128 -> 140
~ _aj_BGR565_YUV422 : 712 -> 720
~ _aj_BGR565_YUV440 : 608 -> 632
~ _aj_BGR565_YUV420 : 1172 -> 1196
~ _aj_BGR565_to_gray : 140 -> 144
~ _aj_gray_YUV440 : 312 -> 308
~ _aj_gray_YUV420 : 328 -> 324
~ _aj_YUV422SEMIP_YUV420 : 540 -> 536
~ _aj_YUV422SEMIP_YUV440 : 556 -> 552
~ _aj_YUV420SEMIP_YUV420 : 456 -> 452
~ _aj_YUV420SEMIP_YUV440 : 472 -> 468
~ _aj_YUV440SEMIP_YUV420 : 488 -> 484
~ _aj_YUV440SEMIP_YUV440 : 420 -> 416
~ _aj_init_lookup : 256 -> 252
~ _aj_read_dht_prog : 432 -> 416
~ _aj_read_sos_prog : 720 -> 704
~ _copy_imagesession : 436 -> 448
~ _applejpeg_decode_set_ra_table : 1468 -> 1508
~ _applejpeg_decode_dump_ra_table : 684 -> 680
~ __get_qtables_helper : 548 -> 520
~ _applejpeg_decode_set_option_stride : 72 -> 68
~ _applejpeg_decode_image_all : 904 -> 908
~ _perform_decode : 512 -> 520
~ _applejpeg_decode_image_row_texture : 1276 -> 1292
~ _check_decode_row_options : 116 -> 112
~ _check_mcu_table : 196 -> 188
~ _aj_bufferproc_savefirst : 372 -> 376
~ _aj_bufferproc_upsample_422 : 412 -> 440
~ _aj_internal_upsample_422_12bit : 92 -> 88
~ _encode_check_options : 1192 -> 1184
~ _applejpeg_encode_set_option_q_tables : 296 -> 304
~ _check_input : 396 -> 392
~ _setup_input : 436 -> 456
~ _verify_pscan_setup : 292 -> 308
```
