## UARPUpdaterServiceHID

> `/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/XPCServices/UARPUpdaterServiceHID.xpc/UARPUpdaterServiceHID`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1cef4` | `0x1d064` | **`+0x170`** |
| `__TEXT.__cstring` | `0x1fc3` | `0x1f80` | **`-0x43`** |
| `__TEXT.__unwind_info` | `0x790` | `0x7a0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x158` | `0x160` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1587.0.3.0.3
+1587.0.21.0.0

-  Functions: 776
-  Symbols:   571
-  CStrings:  1006
+  Functions: 780
+  Symbols:   575
+  CStrings:  1005
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
