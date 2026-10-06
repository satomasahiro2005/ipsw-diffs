## liblog_mdnsresponder.dylib

> `/usr/lib/log/liblog_mdnsresponder.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d00` | `0x1d18` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xa0` | `0x98` | **`-0x8`** |

### Other Changes

```diff

-3066.0.0.502.1
+3085.0.0.0.1
Functions:
~ _DomainNameToString : 300 -> 308
~ _OSLogCopyFormattedString : 132 -> 148
~ _MDNSOLCopyFormattedStringmDNSLabel : 688 -> 684
~ _MDNSOLCopyFormattedStringMDNSNameHashTypeBytes : 2328 -> 2316
~ _MDNSOLCopyFormattedStringNetworkChangeEventFlag : 296 -> 312
```
