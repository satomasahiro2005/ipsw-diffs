## libafc.dylib

> `/usr/lib/libafc.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15578` | `0x15618` | **`+0xa0`** |

### Other Changes

```text
Functions:
~ ___WaitForTimeoutOrEvent : 1268 -> 1304
~ _AFCFreeServerContext : 172 -> 192
~ _AFCFlushServerContext : 248 -> 252
~ _AFCSwapHeader : 156 -> 160
~ _AFCCopyErrorString : 160 -> 156
~ _AFCCopyPacketTypeString : 212 -> 208
~ ___AFCConnectionDispatchReply : 232 -> 244
~ _AFCCreateServerContext : 412 -> 428
~ _AFCProcessServerPacket : 14396 -> 14420
~ ___AFCProcessFileRefReadPacket_block_invoke : 568 -> 576
~ ___AFCProcessFileRefWritePacket_block_invoke : 344 -> 360
~ ___AFCProcessFileRefSeekPacket_block_invoke : 148 -> 156
~ ___AFCProcessFileRefClosePacket_block_invoke : 320 -> 340
```
