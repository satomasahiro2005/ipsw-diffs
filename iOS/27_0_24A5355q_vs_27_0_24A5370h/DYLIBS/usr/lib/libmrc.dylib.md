## libmrc.dylib

> `/usr/lib/libmrc.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6330` | `0x6360` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x2c0` | `0x2b8` | **`-0x8`** |

### Other Changes

```diff

-3066.0.0.502.1
+3085.0.0.0.1
Functions:
~ __mdns_siphash_with_key_ex : 972 -> 980
~ _mdns_cfset_enumerate : 296 -> 304
~ _DomainNameFromString : 304 -> 296
~ __mdns_domain_name_equal : 232 -> 248
~ __mdns_domain_name_cf_callback_hash : 140 -> 148
~ __mdns_domain_name_create : 720 -> 748
~ _mdns_privacy_obfuscate_domain_name_str : 260 -> 280
~ _mrc_dns_proxy_parameters_set_nat64_prefix : 248 -> 240
~ __mrc_xpc_dns_proxy_params_print_description : 820 -> 812
~ ____mrc_cached_local_records_inquiry_process_create_enhanced_record_info_copy_block_invoke : 840 -> 844
~ _mdns_base64_encode_u32_unpadded : 116 -> 96
```
