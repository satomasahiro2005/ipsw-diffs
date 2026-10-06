## com.apple.nke.ppp

> `com.apple.nke.ppp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x744c` | `0x7588` | **`+0x13c`** |

### Other Changes

```text
Functions:
~ sub_fffffff00a79d418 -> sub_fffffff00a87f038 : 168 -> 172
~ _ppp_comp_setcompressor : 524 -> 528
~ sub_fffffff00a79d8cc -> sub_fffffff00a87f4f4 : 132 -> 136
~ _ppp_comp_ccp : 588 -> 592
~ sub_fffffff00a79db9c -> sub_fffffff00a87f7cc : 104 -> 108
~ _ppp_comp_logmbuf : 640 -> 644
~ sub_fffffff00a79defc -> sub_fffffff00a87fb34 : 128 -> 132
~ sub_fffffff00a79dfa4 -> sub_fffffff00a87fbe0 : 28 -> 32
~ _ppp_proto_ioctl : 364 -> 368
~ sub_fffffff00a79e12c -> sub_fffffff00a87fd70 : 28 -> 32
~ sub_fffffff00a79e148 -> sub_fffffff00a87fd90 : 124 -> 128
~ sub_fffffff00a79e1c4 -> sub_fffffff00a87fe10 : 80 -> 84
~ _ppp_proto_add : 112 -> 116
~ _ppp_proto_remove : 116 -> 120
~ _ppp_domain_dispose : 92 -> 96
~ _ppp_proto_free : 120 -> 124
~ _ppp_proto_input : 180 -> 184
~ sub_fffffff00a79e4a8 -> sub_fffffff00a88010c : 88 -> 92
~ sub_fffffff00a79e500 -> sub_fffffff00a880168 : 88 -> 92
~ sub_fffffff00a79e558 -> sub_fffffff00a8801c4 : 76 -> 80
~ _ppp_if_init : 212 -> 216
~ sub_fffffff00a79e6e4 -> sub_fffffff00a880358 : 1096 -> 1100
~ sub_fffffff00a79eb2c -> sub_fffffff00a8807a4 : 680 -> 684
~ _ppp_if_demux : 132 -> 136
~ _ppp_if_add_proto : 84 -> 88
~ _ppp_if_del_proto : 68 -> 72
~ _ppp_if_frameout : 196 -> 200
~ _ppp_if_ioctl : 632 -> 636
~ sub_fffffff00a79f22c -> sub_fffffff00a880ebc : 88 -> 92
~ sub_fffffff00a79f284 -> sub_fffffff00a880f18 : 152 -> 156
~ _ppp_if_detachclient : 580 -> 584
~ _ppp_if_input : 1600 -> 1604
~ _ppp_if_control : 1304 -> 1308
~ sub_fffffff00a7a0154 -> sub_fffffff00a881df8 : 212 -> 216
~ sub_fffffff00a7a0228 -> sub_fffffff00a881ed0 : 240 -> 244
~ sub_fffffff00a7a0318 -> sub_fffffff00a881fc4 : 624 -> 628
~ _ppp_if_xmit : 332 -> 336
~ sub_fffffff00a7a06d4 -> sub_fffffff00a882388 : 104 -> 108
~ sub_fffffff00a7a0770 -> sub_fffffff00a882428 : 100 -> 104
~ sub_fffffff00a7a07d4 -> sub_fffffff00a882490 : 116 -> 120
~ _ppp_link_detach : 216 -> 220
~ sub_fffffff00a7a0920 -> sub_fffffff00a8825e4 : 108 -> 112
~ _ppp_link_input : 316 -> 320
~ _ppp_link_logmbuf : 700 -> 704
~ _ppp_link_control : 816 -> 820
~ sub_fffffff00a7a10b4 -> sub_fffffff00a882d88 : 132 -> 136
~ _ppp_link_send : 292 -> 296
~ _pppisr_thread : 432 -> 436
~ sub_fffffff00a7a1578 -> sub_fffffff00a883258 : 1108 -> 1112
~ _pppserial_open : 564 -> 568
~ _pppserial_close : 352 -> 356
~ _pppserial_ioctl : 736 -> 740
~ _pppserial_input : 2492 -> 2496
~ sub_fffffff00a7a2a14 -> sub_fffffff00a884708 : 160 -> 164
~ _pppserial_lk_ioctl : 1064 -> 1068
~ sub_fffffff00a7a2edc -> sub_fffffff00a884bd8 : 268 -> 272
~ sub_fffffff00a7a2fe8 -> sub_fffffff00a884ce8 : 196 -> 200
~ _pppserial_logchar : 132 -> 136
~ _ppp_module_start : 200 -> 204
~ _ppp_module_stop : 316 -> 320
~ sub_fffffff00a7a3334 -> sub_fffffff00a885044 : 236 -> 240
~ sub_fffffff00a7a3420 -> sub_fffffff00a885134 : 1508 -> 1512
~ sub_fffffff00a7a3a04 -> sub_fffffff00a88571c : 228 -> 232
~ sub_fffffff00a7a3ae8 -> sub_fffffff00a885804 : 1044 -> 1048
~ _ppp_ipv6_attach : 288 -> 292
~ _ppp_ipv6_detach : 116 -> 120
~ sub_fffffff00a7a40c8 -> sub_fffffff00a885df0 : 36 -> 40
~ sub_fffffff00a7a40ec -> sub_fffffff00a885e18 : 60 -> 64
~ _ppp_ipv6_ioctl : 152 -> 156
~ _ppp_ip_attach : 304 -> 308
~ _ppp_ip_detach : 128 -> 132
~ sub_fffffff00a7a43bc -> sub_fffffff00a8860f8 : 36 -> 40
~ sub_fffffff00a7a43e0 -> sub_fffffff00a886120 : 60 -> 64
~ sub_fffffff00a7a441c -> sub_fffffff00a886160 : 184 -> 188
~ _ppp_ip_ioctl : 276 -> 280
~ sub_fffffff00a7a45e8 -> sub_fffffff00a886334 : 92 -> 96
~ sub_fffffff00a7a4644 -> sub_fffffff00a886394 : 92 -> 96
~ sub_fffffff00a7a46a0 -> sub_fffffff00a8863f4 : 140 -> 144
~ sub_fffffff00a7a472c -> sub_fffffff00a886484 : 140 -> 144
```
