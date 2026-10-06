## pppd

> `/usr/sbin/pppd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d338` | `0x2d474` | **`+0x13c`** |
| `__TEXT.__cstring` | `0x8d7e` | `0x8db7` | **`+0x39`** |
| `__TEXT.__unwind_info` | `0x768` | `0x770` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`

### Other Changes

```diff

-1027.0.0.0.0
+1029.0.0.0.0

-  CStrings:  1433
+  CStrings:  1434
Functions:
~ sub_100000920 : 492 -> 476
~ sub_100000b54 -> sub_100000b44 : 156 -> 164
~ _link_down : 308 -> 312
~ _link_established : 844 -> 848
~ _start_networks : 208 -> 224
~ _continue_networks : 200 -> 216
~ _check_protocols_ready : 204 -> 208
~ _auth_ip_addr : 264 -> 268
~ sub_100003ef8 -> sub_100003f20 : 1140 -> 1132
~ sub_100005634 -> sub_100005654 : 1912 -> 1896
~ sub_100006a9c -> sub_100006aac : 92 -> 104
~ sub_1000072c8 -> sub_1000072e4 : 780 -> 776
~ sub_1000075d4 -> sub_1000075ec : 320 -> 332
~ _demand_conf : 288 -> 292
~ _demand_block : 108 -> 112
~ _demand_discard : 164 -> 168
~ _loop_frame : 280 -> 288
~ _fsm_input : 992 -> 988
~ sub_10000ad84 -> sub_10000adb8 : 1376 -> 1380
~ sub_10000c224 -> sub_10000c25c : 1400 -> 1368
~ sub_10000cd3c -> sub_10000cd54 : 656 -> 644
~ sub_10000cfcc -> sub_10000cfd8 : 960 -> 968
~ sub_10000d38c -> sub_10000d3a0 : 2836 -> 2900
~ sub_10000deec -> sub_10000df40 : 1188 -> 1204
~ sub_10000edcc -> sub_10000ee30 : 612 -> 620
~ _random_bytes : 84 -> 92
~ _main : 4460 -> 4468
~ _script_setenv : 380 -> 368
~ _script_unsetenv : 164 -> 160
~ sub_100012fe4 -> sub_100013050 : 392 -> 456
~ sub_100013294 -> sub_100013340 : 1584 -> 1552
~ _print_options : 208 -> 212
~ sub_100013ba0 -> sub_100013c30 : 892 -> 888
~ _ppp_ip_probe_stop : 192 -> 200
~ _ppp_process_auxiliary_probe_input : 320 -> 316
~ _tdb_error : 92 -> 96
~ _tdb_update : 372 -> 376
~ _tdb_fetch : 292 -> 296
~ _tdb_exists : 244 -> 248
~ _tdb_nextkey : 424 -> 428
~ _tdb_delete : 688 -> 692
~ _tdb_store : 1384 -> 1388
~ _tdb_lockchain : 120 -> 128
~ _tdb_unlockchain : 120 -> 128
~ sub_10001de48 -> sub_10001df04 : 272 -> 268
~ sub_10001f46c -> sub_10001f524 : 2700 -> 2712
~ sub_10002080c -> sub_1000208d0 : 520 -> 532
~ _vslprintf : 2792 -> 2784
~ _lock : 688 -> 684
~ _check_vpn_interface_or_service_unrecoverable : 1660 -> 1652
~ sub_100024bbc -> sub_100024c78 : 664 -> 708
~ sub_100025538 -> sub_100025620 : 664 -> 672
~ sub_1000258ac -> sub_10002599c : 776 -> 780
~ sub_100026304 -> sub_1000263f8 : 588 -> 584
~ sub_1000267ac -> sub_10002689c : 216 -> 224
~ sub_100026948 -> sub_100026a40 : 524 -> 528
~ sub_10002765c -> sub_100027758 : 2568 -> 2572
~ _acsp_printpkt : 712 -> 720
~ sub_100029210 -> sub_100029318 : 1292 -> 1340
~ _DesSetkey : 304 -> 308
CStrings:
+ "ACSP plugin: not enough data (%d) for domain length (%d)"
```
