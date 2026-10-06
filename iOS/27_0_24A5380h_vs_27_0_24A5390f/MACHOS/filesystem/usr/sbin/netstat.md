## netstat

> `/usr/sbin/netstat`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xeebc` | `0xf116` | **`+0x25a`** |
| `__TEXT.__text` | `0x1afe4` | `0x1b114` | **`+0x130`** |
| `__DATA.__bss` | `0xabc8` | `0xabd8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  2353
+  CStrings:  2371
Functions:
~ _print_droptap_stats : 4200 -> 4308
~ sub_100019c10 -> sub_100019c7c : 104 -> 136
~ sub_100019c78 -> sub_100019d04 : 168 -> 172
~ _drop_description_str : 4916 -> 5040
~ sub_10001b2e4 -> sub_10001b3f0 : 104 -> 136
~ sub_10001b34c -> sub_10001b478 : 168 -> 172
CStrings:
+ "DROP_REASON_IP6_NDP_SELF_LLADDR"
+ "DROP_REASON_IPSEC_IN_AUTH_FAILED"
+ "DROP_REASON_IPSEC_IN_BAD_SPI"
+ "DROP_REASON_IPSEC_IN_DECRYPT_FAILED"
+ "DROP_REASON_IPSEC_IN_INVALID"
+ "DROP_REASON_IPSEC_IN_MBUF_ALLOC_FAILED"
+ "DROP_REASON_IPSEC_IN_NO_SA"
+ "DROP_REASON_IPSEC_IN_POLICY"
+ "DROP_REASON_IPSEC_IN_REPLAY"
+ "IPsec input: authentication failed"
+ "IPsec input: bad SPI"
+ "IPsec input: decryption failed"
+ "IPsec input: invalid or malformed packet"
+ "IPsec input: mbuf allocation failed"
+ "IPsec input: no security association found"
+ "IPsec input: replay check failed"
+ "IPsec input: security policy violation"
+ "IPv6 NDP option claims our own LL address"
```
