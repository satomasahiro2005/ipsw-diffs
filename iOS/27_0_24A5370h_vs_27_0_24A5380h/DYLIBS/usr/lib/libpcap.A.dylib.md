## libpcap.A.dylib

> `/usr/lib/libpcap.A.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20dd0` | `0x20e10` | **`+0x40`** |
| `__TEXT.__cstring` | `0x6c2e` | `0x6c4c` | **`+0x1e`** |

### Other Changes

```diff

-  Functions: 524
+  Functions: 525

-  CStrings:  1079
+  CStrings:  1080
Functions:
~ _pcap_nametoeproto : 84 -> 100
~ _pcap_nametollc : 80 -> 96
~ ___pcap_atoin : 120 -> 108
~ _bpf_optimize : 1540 -> 1516
~ _pcap_setup_pktap_interface : 1880 -> 1908
~ _pcap_datalink_val_to_description : 64 -> 72
~ _pcap_datalink_val_to_description_or_dlt : 132 -> 140
~ _pcap_tstamp_type_val_to_description : 68 -> 76
~ _str2tok : 112 -> 116
~ _pcap_lex : 3712 -> 3708
~ _pcap__create_buffer : 140 -> 136
~ _stou : 352 -> 336
~ _pcap__scan_buffer : 160 -> 152
~ _pcap__scan_bytes : 144 -> 156
~ _pcap_lex_init : 152 -> 156
~ _pcap_lex_init_extra : 164 -> 168
CStrings:
+ "bad length in yy_scan_bytes()"
```
