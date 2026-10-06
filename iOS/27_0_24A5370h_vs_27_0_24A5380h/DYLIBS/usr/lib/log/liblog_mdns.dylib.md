## liblog_mdns.dylib

> `/usr/lib/log/liblog_mdns.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5880` | `0x5864` | **`-0x1c`** |

### Other Changes

```diff

-3085.0.0.0.1
+3089.0.0.0.1
Functions:
~ __DNSRecordDataToStringEx2 : 5044 -> 5016
~ _mdns_privacy_obfuscate_domain_name_str : 560 -> 564
~ __mdns_siphash_with_key_ex : 980 -> 972
~ _mdns_string_builder_append_escaped_ascii_string : 304 -> 308
```
