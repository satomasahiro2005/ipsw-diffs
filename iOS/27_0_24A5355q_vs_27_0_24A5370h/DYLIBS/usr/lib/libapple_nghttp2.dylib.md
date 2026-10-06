## libapple_nghttp2.dylib

> `/usr/lib/libapple_nghttp2.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10458` | `0x1048c` | **`+0x34`** |

### Other Changes

```text
Functions:
~ _session_new : 1496 -> 1512
~ _nghttp2_session_add_settings : 924 -> 956
~ _session_inbound_frame_reset : 376 -> 380
~ _nghttp2_iv_check : 152 -> 156
~ _nghttp2_nv_array_copy : 448 -> 472
~ _nghttp2_session_mem_send_internal : 6196 -> 6216
~ _nghttp2_session_on_settings_received : 1492 -> 1432
~ _nghttp2_session_mem_recv2 : 12876 -> 12888
~ _nghttp2_session_close_stream : 564 -> 560
~ _add_hd_table_incremental : 768 -> 764
~ _parse_uint : 88 -> 96
~ _nghttp2_hd_inflate_hd_nv : 1856 -> 1860
~ _nghttp2_hd_deflate_hd_bufs : 1444 -> 1440
~ _emit_string : 744 -> 748
~ _map_resize : 320 -> 308
~ _nghttp2_http_record_request_method : 248 -> 252
~ _nghttp2_pq_remove : 280 -> 276
~ _bubble_down : 172 -> 168
~ _nghttp2_session_del : 292 -> 312
~ _nghttp2_option_set_user_recv_extension_type : 56 -> 60
~ _nghttp2_map_each : 140 -> 132
~ _nghttp2_hd_deflate_hd_vec2 : 416 -> 404
~ _nghttp2_hd_deflate_bound : 48 -> 56
~ _parser_number : 452 -> 412
~ _parser_byteseq : 376 -> 368
~ _parser_dispstring : 452 -> 448
~ _nghttp2_submit_origin : 532 -> 556
~ _nghttp2_pack_settings_payload2 : 148 -> 156
~ _nghttp2_session_upgrade_internal : 488 -> 500
~ _nghttp2_check_header_value_rfc9113 : 108 -> 104
~ _nghttp2_check_method : 52 -> 56
~ _nghttp2_check_path : 52 -> 56
~ _nghttp2_check_authority : 52 -> 56
```
