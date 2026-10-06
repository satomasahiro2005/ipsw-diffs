## libsystem_asl.dylib

> `/usr/lib/system/libsystem_asl.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14e00` | `0x14b20` | **`-0x2e0`** |

### Other Changes

```text
Functions:
~ __vsyslog : 380 -> 376
~ __asl_msg_index : 488 -> 476
~ __jump_dealloc : 120 -> 116
~ __jump_dealloc : 332 -> 316
~ _asl_msg_set_key_val_op : 2248 -> 2236
~ __asl_send_message_text : 596 -> 580
~ _asl_format_message : 2852 -> 2848
~ _asl_core_str_match_absolute_or_relative_time : 516 -> 508
~ _asl_client_add_output_file : 344 -> 352
~ __asl_client_free_internal : 176 -> 160
~ _asl_client_set_output_file_filter : 72 -> 80
~ _asl_client_remove_output_file : 284 -> 272
~ _asl_core_encode_buffer : 524 -> 520
~ _asl_core_decode_buffer : 328 -> 320
~ _asl_core_str_to_uint32 : 44 -> 60
~ _asl_core_str_match_c_time : 1444 -> 1296
~ _asl_core_str_match_dotted_time : 1420 -> 1196
~ _asl_core_str_match_iso_8601_time : 2212 -> 1868
~ _asl_string_append_op : 420 -> 412
~ _redirect_atexit : 196 -> 192
~ __read_redirect : 440 -> 424
~ _asl_msg_list_to_string : 272 -> 268
~ _asl_msg_list_to_asl_string : 252 -> 248
~ _asl_msg_list_insert : 316 -> 308
~ _asl_msg_list_search : 236 -> 228
~ _asl_file_save : 1952 -> 1960
~ _asl_file_match_next : 336 -> 348
~ _asl_file_match : 688 -> 700
~ _msg_fetch : 920 -> 936
~ _asl_legacy1_match : 460 -> 488
~ _next_search_slot : 164 -> 168
~ __asl_msg_dump : 592 -> 588
~ __asl_msg_resolve_index : 168 -> 164
~ _asl_msg_cmp_list : 120 -> 116
~ __asl_msg_get_next_word : 924 -> 932
~ __asl_msg_basic_test : 644 -> 628
~ _asl_store_open_write : 740 -> 748
~ _asl_store_file_closeall : 100 -> 120
~ _asl_store_file_path : 60 -> 72
~ _asl_store_file_close : 112 -> 124
~ _asl_store_save : 1364 -> 1352
~ _asl_is_utf8 : 544 -> 540
~ _asl_b64_encode : 428 -> 448
```
