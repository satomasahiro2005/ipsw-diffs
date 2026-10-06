## libsystem_dnssd.dylib

> `/usr/lib/system/libsystem_dnssd.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x62bc` | `0x6290` | **`-0x2c`** |
| `__TEXT.__unwind_info` | `0x1c0` | `0x1b8` | **`-0x8`** |

### Other Changes

```diff

-3066.0.0.502.1
+3085.0.0.0.1
Functions:
~ _handle_browse_response : 520 -> 492
~ _DNSServiceConstructFullName : 636 -> 676
~ _DomainEndsInDot : 132 -> 128
~ _InternalTXTRecordSearch : 172 -> 180
~ _handle_query_response : 700 -> 696
~ _TXTRecordGetCount : 52 -> 60
~ _TXTRecordGetItemAtIndex : 292 -> 284
~ _handle_resolve_response : 456 -> 432
~ _handle_addrinfo_response : 820 -> 816
~ _handle_regservice_response : 388 -> 364
~ _handle_enumeration_response : 172 -> 168
```
