## libafc.dylib

> `/usr/lib/libafc.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x15618` | `0x1562c` | **`+0x14`** |
| `__DATA_DIRTY.__bss` | `0xf8` | `0xf9` | **`+0x1`** |

### Other Changes

```text
Functions:
~ ___WaitForTimeoutOrEvent : 1304 -> 1312
~ ___AFCConnectionDispatchReply : 244 -> 232
~ _AFCProcessServerPacket : 14420 -> 14444
```
