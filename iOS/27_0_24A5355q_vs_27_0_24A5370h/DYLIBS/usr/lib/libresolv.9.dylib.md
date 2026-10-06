## libresolv.9.dylib

> `/usr/lib/libresolv.9.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18ad8` | `0x18b1c` | **`+0x44`** |
| `__TEXT.__unwind_info` | `0x338` | `0x328` | **`-0x10`** |

### Other Changes

```text
Functions:
~ _res_9_vinit : 5208 -> 5220
~ _res_next_word : 140 -> 152
~ _res_build : 1640 -> 1648
~ _res_9_nclose : 140 -> 128
~ _res_9_b64_ntop : 340 -> 344
~ _res_9_b64_pton : 636 -> 676
~ __dns_parse_resource_record_internal : 2316 -> 2312
~ _dns_parse_packet : 732 -> 700
~ _dns_free_reply : 344 -> 324
~ _dns_free_resource_record : 280 -> 276
~ __dns_print_resource_record_lock : 1436 -> 1420
~ _dns_print_reply : 1552 -> 1536
~ _dns_print_handle : 308 -> 304
~ __pdns_print_handle : 1068 -> 1064
~ _dns_all_server_addrs : 456 -> 476
~ __dns_parse_domain_name : 600 -> 596
~ __check_cache : 1316 -> 1348
~ __pdns_free : 152 -> 148
~ __pdns_convert_sc : 1748 -> 1728
~ _dns_open : 748 -> 764
~ _dns_set_debug : 176 -> 192
~ _dns_free : 268 -> 264
~ __sdns_search : 1584 -> 1596
~ __pdns_get_default_handles : 352 -> 348
~ _res_9_dst_init : 272 -> 276
~ _dst_hmac_md5_to_dns_key : 108 -> 100
~ _dst_buffer_to_hmac_md5 : 368 -> 376
~ _res_9_dst_s_dns_key_id : 124 -> 128
~ _res_9_ns_datetosecs : 940 -> 948
~ _res_9_ns_name_pton2 : 1024 -> 1068
~ _res_9_ns_name_ntol : 280 -> 284
~ _res_9_ns_name_unpack2 : 412 -> 416
~ _res_9_ns_name_pack : 808 -> 816
~ _res_9_ns_skiprr : 180 -> 172
~ _res_9_ns_initparse : 288 -> 276
~ _res_9_ns_sprintrrf : 9344 -> 9188
~ _res_9_ns_samedomain : 368 -> 364
~ _res_9_ns_makecanon : 220 -> 244
~ _res_9_ns_format_ttl : 516 -> 524
~ _res_9_ns_verify_tcp : 1000 -> 996
~ _res_9_hnok : 180 -> 176
~ _res_9_mailok : 88 -> 92
~ _do_section : 1464 -> 1496
~ _res_9_sym_ntos : 160 -> 148
~ _res_9_sym_ntop : 152 -> 160
~ _latlon2ul : 932 -> 944
~ _res_9_nametoclass : 252 -> 264
~ _res_9_nametotype : 252 -> 264
~ _res_9_findzonecut : 224 -> 232
~ _res_9_setservers : 220 -> 232
~ _res_9_getservers : 192 -> 188
~ _res_setoptions : 1316 -> 1312
~ _res_nquery_soa_min : 1184 -> 1172
~ _res_9_hostalias_2 : 472 -> 492
~ ___res_nsearch_list_2 : 820 -> 832
~ _res_9_nquerydomain : 396 -> 392
~ _res_9_nsearch : 1004 -> 1000
~ _res_ourserver_p : 308 -> 320
~ _dns_res_send : 7288 -> 7308
```
