## CoreUARP

> `/System/Library/PrivateFrameworks/CoreUARP.framework/CoreUARP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x895f8` | `0x89750` | **`+0x158`** |
| `__TEXT.__cstring` | `0x7de4` | `0x7da1` | **`-0x43`** |
| `__TEXT.__unwind_info` | `0x26c8` | `0x26d0` | **`+0x8`** |

### Other Changes

```diff

-1587.0.3.0.3
+1587.0.21.0.0

-  Functions: 3967
-  Symbols:   6530
-  CStrings:  2049
+  Functions: 3970
+  Symbols:   6534
+  CStrings:  2048
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
