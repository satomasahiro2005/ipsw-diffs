## netstat

> `/usr/sbin/netstat`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1af20` | `0x1b058` | **`+0x138`** |
| `__TEXT.__cstring` | `0xee1c` | `0xeebc` | **`+0xa0`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  2350
+  CStrings:  2353
Functions:
~ _intpr : 6792 -> 6932
~ _intpr_ri : 1852 -> 1860
~ _icmp_stats : 1184 -> 1152
~ _ip6_stats : 5492 -> 5508
~ _icmp6_stats : 1888 -> 1872
~ _pfkey_stats : 1692 -> 1672
~ _name2protox : 132 -> 128
~ _reinitalize_protocols : 120 -> 112
~ _printprotoifstats : 116 -> 112
~ _knownname : 104 -> 120
~ _mbpr : 3276 -> 3280
~ _ifmalist_dump_af : 664 -> 708
~ _ifmalist_dump : 2964 -> 2956
~ _sdl_addr_to_hex : 164 -> 172
~ _routepr : 1760 -> 1756
~ _mptcppr : 820 -> 816
~ _unixpr_n : 916 -> 912
~ _print_if_ports_used_list : 920 -> 924
~ _print_if_lpw_stats : 1988 -> 2164
CStrings:
+ "\t%llu LPW exit%s for connection not idle on Bluetooth\n"
+ "\t%llu LPW exit%s for connection not idle on Cellular\n"
+ "\t%llu LPW exit%s for connection not idle on Wi-Fi\n"
```
