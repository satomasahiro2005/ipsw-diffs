## liblzma.5.dylib

> `/usr/lib/liblzma.5.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17508` | `0x17444` | **`-0xc4`** |

### Other Changes

```text
Functions:
~ _lzma_filters_free : 112 -> 132
~ _lzma_raw_coder_init : 348 -> 388
~ _lzma_raw_coder_memusage : 148 -> 164
~ _lzma_index_file_size : 128 -> 136
~ _lzma_index_append : 556 -> 572
~ _iter_set_info : 444 -> 464
~ _lzma_index_iter_locate : 244 -> 236
~ _lzma_block_header_size : 252 -> 260
~ _lzma_block_header_encode : 364 -> 344
~ _lzma_filter_encoder_is_supported : 52 -> 60
~ _encoder_find : 48 -> 64
~ _lzma_filters_update : 244 -> 252
~ _lzma_mt_block_size : 176 -> 192
~ _lzma_properties_size : 96 -> 112
~ _lzma_properties_encode : 72 -> 88
~ _index_encode : 600 -> 592
~ _lzma_vli_encode : 188 -> 192
~ _block_decode : 644 -> 640
~ _lzma_block_header_decode : 516 -> 520
~ _lzma_filter_decoder_is_supported : 52 -> 56
~ _decoder_find : 48 -> 56
~ _lzma_properties_decode : 80 -> 88
~ _stream_decode : 1160 -> 1168
~ _lzma_vli_decode : 336 -> 308
~ _lzma_crc32 : 288 -> 304
~ _lzma_crc64 : 236 -> 232
~ _lzip_decode : 1100 -> 1080
~ _lzma_mf_hc3_find : 432 -> 428
~ _lzma_mf_hc3_skip : 196 -> 192
~ _lzma_mf_hc4_skip : 232 -> 224
~ _lzma_mf_bt2_find : 200 -> 196
~ _lzma_mf_bt2_skip : 172 -> 168
~ _lzma_mf_bt3_find : 448 -> 444
~ _lzma_mf_bt3_skip : 228 -> 224
~ _lzma_mf_bt4_skip : 264 -> 256
~ _normalize : 128 -> 120
~ _lzma_str_to_filters : 1160 -> 1192
~ _lzma_str_from_filters : 980 -> 1016
~ _lzma_str_list_filters : 1020 -> 1036
~ _str_append_u32 : 272 -> 280
~ _parse_options : 912 -> 904
~ _lzma_lzma_encode : 2216 -> 2100
~ _lzma_lzma_encoder_reset : 536 -> 532
~ _match : 984 -> 876
~ _length_update_prices : 432 -> 416
~ _lzma_lzma_preset : 252 -> 244
~ _lzma_lzma_optimum_fast : 936 -> 940
~ _lzma_lzma_optimum_normal : 6488 -> 6264
~ _file_info_decode : 1488 -> 1480
~ _lzma_decode : 10884 -> 10856
~ _lzma_decoder_reset : 660 -> 656
~ _lzma_lzma2_props_encode : 184 -> 180
~ _lzma2_encode : 828 -> 844
~ _arm64_code : 220 -> 212
~ _stream_decode_mt : 2880 -> 2920
~ _stream_decoder_mt_get_progress : 200 -> 192
~ _threads_end : 224 -> 220
~ _delta_encode : 304 -> 320
~ _delta_decode : 156 -> 164
~ _x86_code : 388 -> 408
~ _powerpc_code : 176 -> 180
~ _ia64_code : 324 -> 340
~ _threads_end : 216 -> 220
~ _threads_stop : 256 -> 260
~ _sparc_code : 204 -> 212
```
