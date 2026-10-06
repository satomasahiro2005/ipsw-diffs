## UARPiCloud

> `/System/Library/PrivateFrameworks/UARPiCloud.framework/UARPiCloud`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c030` | `0x1c194` | **`+0x164`** |
| `__AUTH.__objc_data` | `0x140` | `0xf0` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x190` | `0x1e0` | **`+0x50`** |
| `__TEXT.__cstring` | `0x2464` | `0x2421` | **`-0x43`** |
| `__TEXT.__unwind_info` | `0x608` | `0x610` | **`+0x8`** |

### Other Changes

```diff

-1587.0.3.0.3
+1587.0.21.0.0

-  Functions: 691
-  Symbols:   1021
-  CStrings:  446
+  Functions: 694
+  Symbols:   1025
+  CStrings:  445
Symbols:
+ _uarpDownstreamEndpointProcessReachableMessage
+ _uarpPlatformDownstreamEndpointReachable2
+ _uarpProcessTLV2
+ _uarpProtocolSupportsDownstreamReachableTLVs
+ _uarpSendDownstreamEndpointReachable2
- _uarpTransmitBufferUpstream
CStrings:
+ "%s: ESPRESSO: Message <type=0x%04x, id=0x%04x> Length too big ! expected <%u>, got <%u>"
- "%s: ESPRESSO:Bonus Message <type=0x%04x, length=x0x%04x, id=0x%04x>"
- "%s: ESPRESSO:Message <type=0x%04x, id=0x%04x> Length too big ! expected <%u>, got <%u>"
```
