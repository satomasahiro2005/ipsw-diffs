## libsystem_info.dylib

> `/usr/lib/system/libsystem_info.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24720` | `0x24864` | **`+0x144`** |

### Other Changes

```text
Functions:
~ _search_item_bynumber : 196 -> 204
~ _cache_fetch_item : 248 -> 292
~ _search_get_module : 128 -> 124
~ _si_item_match : 700 -> 720
~ _getgrouplist_internal : 272 -> 276
~ _file_grouplist : 588 -> 608
~ _LI_ils_create : 2688 -> 2724
~ __fsi_tokenize : 536 -> 524
~ __fsi_append_string : 96 -> 104
~ _LI_get_thread_info : 416 -> 420
~ _si_module_with_name : 300 -> 320
~ _si_module_config_modules_for_category : 276 -> 280
~ ___si_module_cache_byname_block_invoke : 172 -> 168
~ _search_set_flags : 144 -> 156
~ _getifaddrs : 1500 -> 1528
~ _si_addrinfo : 1512 -> 1516
~ __gai_numerichost : 404 -> 400
~ _si_list_release : 148 -> 144
~ _copy_group_r : 436 -> 448
~ __LI_data_free : 176 -> 168
~ _ether_aton : 244 -> 240
~ _si_list_concat : 260 -> 256
~ __gai_sort_list : 472 -> 476
~ _if_nameindex : 336 -> 340
~ __fsi_get_service : 656 -> 660
~ _dn_expand : 316 -> 324
~ _inet6_option_next : 216 -> 220
~ _inet6_option_find : 244 -> 256
~ _inet6_opt_next : 184 -> 188
~ _inet6_rthdr_add : 96 -> 104
~ _inet6_rth_reverse : 196 -> 204
~ _cache_close : 188 -> 176
~ _cache_fetch_list : 324 -> 340
~ __fsi_get_host : 840 -> 844
~ __fsi_get_name_number_aliases : 696 -> 708
~ __fsi_get_fs : 1600 -> 1604
~ _kvbuf_next_dict : 228 -> 224
~ _kvbuf_next_key : 308 -> 304
~ _kvbuf_next_val_len : 152 -> 148
~ _kvbuf_decode : 692 -> 688
~ _kvarray_free : 252 -> 248
~ __getgrouplist_2_internal : 264 -> 268
~ _ether_hostton : 268 -> 264
~ _ether_ntohost : 280 -> 276
~ _mdns_hostbyaddr : 876 -> 884
~ __mdns_search_ex : 3008 -> 2984
~ __mdns_query_start : 888 -> 900
~ __mdns_hostent_clear : 164 -> 156
~ __mdns_query_callback : 1440 -> 1448
~ __mdns_pack_domain_name : 284 -> 288
~ __mdns_hostent_append_alias : 264 -> 268
~ __mdns_canonicalize : 92 -> 112
~ __mdns_parse_domain_name : 296 -> 280
~ _search_close : 124 -> 132
~ _search_host_byname : 288 -> 296
~ _search_host_byaddr : 288 -> 296
~ _search_list : 436 -> 444
~ _si_addrinfo_list_from_hostent : 384 -> 380
~ __gai_nat64_second_pass : 640 -> 644
~ _si_ipnode_byname : 1160 -> 1148
~ _lower_case : 136 -> 120
~ _merge_alias : 216 -> 224
~ _free_build_hostent : 164 -> 160
~ ___si_async_call_block_invoke : 284 -> 280
~ _si_async_handle_reply : 132 -> 128
~ _si_standardize_mac_address : 284 -> 292
~ ____dd_mbr_check_membership_ext_block_invoke_4 : 168 -> 172
~ ____dd_mbr_check_membership_ext_block_invoke_5 : 168 -> 172
~ ____dd_mbr_check_membership_ext_block_invoke_6 : 168 -> 172
~ ____muser_extract_group_block_invoke : 360 -> 356
~ _clnt_sperror : 716 -> 732
~ _clnt_sperrno : 60 -> 68
~ _clnt_perrno : 72 -> 80
~ _clnt_spcreateerror : 568 -> 584
~ _common_prefix_length : 104 -> 108
~ ___darwin_directory_grouplist_block_invoke_2 : 228 -> 240
~ _clnt_broadcast : 1708 -> 1712
~ _xprt_unregister : 216 -> 212
~ __svcauth_unix : 392 -> 400
~ _readtcp : 328 -> 324
~ _writetcp : 116 -> 124
~ _xdr_union : 188 -> 172
~ _xdr_string : 296 -> 292
~ _xdrrec_putbytes : 164 -> 168
~ _get_input_bytes : 196 -> 200
~ _rcmd_af : 2076 -> 2064
~ ___ivaliduser_sa : 904 -> 908
~ _ether_line : 192 -> 188
~ _getifmaddrs : 816 -> 828
```
