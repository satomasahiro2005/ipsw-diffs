## liblog_network.dylib

> `/usr/lib/log/liblog_network.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17c0` | `0x17a8` | **`-0x18`** |
| `__TEXT.__const` | `0x58` | `0x50` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xb0` | `0xa8` | **`-0x8`** |

### Other Changes

```diff

-6681.0.372.502.1
+6681.0.436.0.8
Functions:
~ _NWOLCopyFormattedStringIPv4Address -> _NWOLCopyFormattedStringSockaddr : 592 -> 1412
~ _NWOLCopyFormattedStringIPv6Address -> _NWOLCopyFormattedStringIPv4Address : 512 -> 592
~ _NWOLCopyFormattedStringSockaddr -> _NWOLCopyFormattedStringIPv6Address : 1416 -> 512
~ _NWOLCopyFormattedStringData : 700 -> 688
~ ___NWOLCopyFormattedStringTCPPackets_block_invoke : 612 -> 604
```
