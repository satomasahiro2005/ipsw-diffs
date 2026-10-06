## libAce3Updater.dylib

> `/usr/lib/updaters/libAce3Updater.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ef50` | `0x1f0c0` | **`+0x170`** |
| `__TEXT.__cstring` | `0x5edb` | `0x5e98` | **`-0x43`** |
| `__TEXT.__unwind_info` | `0x7a8` | `0x7b0` | **`+0x8`** |

### Other Changes

```diff

-1587.0.3.0.3
+1587.0.21.0.0

-  Functions: 953
-  Symbols:   1197
-  CStrings:  698
+  Functions: 957
+  Symbols:   1201
+  CStrings:  697
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
