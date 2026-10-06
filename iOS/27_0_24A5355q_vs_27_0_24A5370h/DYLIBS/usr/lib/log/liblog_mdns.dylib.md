## liblog_mdns.dylib

> `/usr/lib/log/liblog_mdns.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x585c` | `0x5880` | **`+0x24`** |

### Other Changes

```diff

-3066.0.0.502.1
+3085.0.0.0.1
Functions:
~ _mdns_base64_encode_u32_unpadded : 116 -> 96
~ _DNSMessageExtractDomainName : 320 -> 324
~ _DomainNameToString : 316 -> 324
~ _DomainNameEqual : 136 -> 152
~ __DNSRecordDataToStringEx2 : 5068 -> 5044
~ __AppendHexString : 172 -> 180
~ _OSLogCopyFormattedString : 412 -> 436
~ __log_mdns_format_dns_service_type : 136 -> 132
~ __log_mdns_format_gai_options : 280 -> 288
~ __log_mdns_format_dns_message_ex : 4020 -> 4024
~ _mdns_privacy_obfuscate_domain_name_str : 556 -> 560
~ __mdns_siphash_with_key_ex : 972 -> 980
```
