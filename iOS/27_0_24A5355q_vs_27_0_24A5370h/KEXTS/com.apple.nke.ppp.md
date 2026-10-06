## com.apple.nke.ppp

> `com.apple.nke.ppp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x720` | **`+0x720`** |
| `__TEXT_EXEC.__text` | `0x7458` | `0x7450` | **`-0x8`** |

### Other Changes

```diff

-1027.0.0.0.0
+1029.0.0.0.0
Functions:
~ _ppp_comp_setcompressor : 528 -> 524
~ _ppp_comp_logmbuf : 632 -> 640
~ sub_fffffff00a78b118 -> sub_fffffff00a82397c : 688 -> 680
~ sub_fffffff00a78b878 -> sub_fffffff00a8240d4 : 156 -> 152
~ _ppp_if_control : 1312 -> 1304
~ _ppp_link_logmbuf : 696 -> 700
~ sub_fffffff00a78db68 -> sub_fffffff00a8263bc : 1168 -> 1124
~ _pppserial_input : 2488 -> 2492
~ sub_fffffff00a78f95c -> sub_fffffff00a828188 : 204 -> 236
~ sub_fffffff00a78fa28 -> sub_fffffff00a828274 : 1500 -> 1508
~ sub_fffffff00a7900e8 -> sub_fffffff00a82893c : 1040 -> 1044
```
