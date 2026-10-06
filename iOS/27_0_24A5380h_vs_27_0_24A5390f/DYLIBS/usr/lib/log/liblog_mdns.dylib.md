## liblog_mdns.dylib

> `/usr/lib/log/liblog_mdns.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xa0` | `—` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0xa0` | **`+0xa0`** |
| `__TEXT.__text` | `0x5864` | `0x58c0` | **`+0x5c`** |
| `__TEXT.__cstring` | `0xdbb` | `0xdb4` | **`-0x7`** |

### Other Changes

```diff

-3089.0.0.0.1
+3109.0.0.0.0

-  CStrings:  381
+  CStrings:  380
Functions:
~ __DNSRecordDataToStringEx2 : 5016 -> 5064
~ __log_mdns_format_dns_message_ex : 4024 -> 4068
CStrings:
+ " ["
+ " key%u"
- " %s%s"
- " key%u=\""
- "["
```
