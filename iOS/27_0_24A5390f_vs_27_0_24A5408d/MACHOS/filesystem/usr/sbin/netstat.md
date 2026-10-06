## netstat

> `/usr/sbin/netstat`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xf116` | `0xf2c1` | **`+0x1ab`** |
| `__TEXT.__text` | `0x1b114` | `0x1b288` | **`+0x174`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  2371
+  CStrings:  2381
Functions:
~ _print_if_lpw_stats : 2164 -> 2392
~ _print_droptap_stats : 4308 -> 4344
~ sub_100019d04 -> sub_100019e0c : 172 -> 184
~ _drop_description_str : 5040 -> 5124
~ sub_10001b478 -> sub_10001b5e0 : 172 -> 184
CStrings:
+ "\t%llu LPW exit%s for fragmented packet\n"
+ "\t%llu LPW exit%s for fragmented packet on Bluetooth\n"
+ "\t%llu LPW exit%s for fragmented packet on Cellular\n"
+ "\t%llu LPW exit%s for fragmented packet on Wi-Fi\n"
+ "DROP_REASON_IP6_ND_CACHE_TEARDOWN"
+ "DROP_REASON_IP6_ND_HOLD_EVICTED"
+ "DROP_REASON_IP6_RA_BAD_ND_OPT"
+ "IPv6 ND held packet dropped on neighbor cache teardown"
+ "IPv6 ND held packet evicted while awaiting resolution"
+ "IPv6 RA with invalid ND opt"
```
