## libpcap.A.dylib

> `/usr/lib/libpcap.A.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20c84` | `0x20dd0` | **`+0x14c`** |

### Other Changes

```text
Functions:
~ _pcap_filter_with_aux_data : 1140 -> 1104
~ _pcap_validate_filter : 276 -> 272
~ _pcap_findalldevs_interfaces : 372 -> 364
~ _pcap_compile : 1860 -> 1868
~ _finish_parse : 3536 -> 3528
~ _gen_protochain : 1840 -> 1816
~ _gen_mcode6 : 496 -> 492
~ _gen_bcmp : 468 -> 464
~ _pcap_nametoaddr : 72 -> 64
~ ___pcap_atoin : 108 -> 120
~ _bpf_optimize : 1532 -> 1540
~ _opt_loop : 4932 -> 4892
~ _convert_code_r : 864 -> 868
~ _propedom : 116 -> 112
~ _find_inedges : 112 -> 120
~ _opt_j : 416 -> 396
~ _get_dlt_list : 356 -> 360
~ _find_802_11 : 116 -> 124
~ _remove_non_802_11 : 84 -> 80
~ _remove_802_11 : 124 -> 120
~ _pcap_read_bpf : 1180 -> 1168
~ _dlt_to_linktype : 108 -> 104
~ _linktype_to_dlt : 112 -> 108
~ _pcap_setup_pktap_interface : 1884 -> 1880
~ _pcap_ng_dump_pktap_comment : 1332 -> 1336
~ _pcap_ng_dump_pktap_v2 : 1412 -> 1416
~ _pcap_sendpacket_multiple : 844 -> 852
~ _pcap_if_info_set_clear : 112 -> 108
~ _pcap_if_info_set_free : 116 -> 120
~ _pcap_if_info_set_find_by_name : 92 -> 108
~ _pcap_if_info_set_find_by_id : 56 -> 64
~ _pcap_find_if_info_by_id : 56 -> 64
~ _pcap_proc_info_set_clear : 112 -> 108
~ _pcap_proc_info_set_free : 64 -> 68
~ _pcap_proc_info_set_find_by_index : 48 -> 56
~ _pcap_find_proc_info_by_index : 48 -> 56
~ _pcap_set_tstamp_type : 128 -> 136
~ _pcap_set_tstamp_precision : 128 -> 136
~ _pcap_set_datalink : 304 -> 316
~ _pcap_datalink_val_to_name : 56 -> 72
~ _pcap_datalink_val_to_description : 44 -> 64
~ _pcap_datalink_val_to_description_or_dlt : 112 -> 132
~ _pcap_tstamp_type_val_to_name : 64 -> 72
~ _pcap_tstamp_type_val_to_description : 52 -> 68
~ _pcap_ng_block_reset : 348 -> 344
~ _pcap_ng_block_add_name_record_common : 464 -> 476
~ _pcap_fopen_offline_internal : 640 -> 636
~ _pcap_parse : 5184 -> 5472
~ _str2tok : 92 -> 112
~ _pcap_lex : 3716 -> 3712
~ _stou : 360 -> 352
~ _yy_get_previous_state : 204 -> 196
~ _pcap__scan_bytes : 136 -> 144
```
