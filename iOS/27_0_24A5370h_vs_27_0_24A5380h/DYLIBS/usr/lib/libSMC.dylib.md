## libSMC.dylib

> `/usr/lib/libSMC.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x50fc` | `0x5128` | **`+0x2c`** |
| `__TEXT.__unwind_info` | `0x158` | `0x150` | **`-0x8`** |

### Other Changes

```text
Functions:
~ _SMCMakeUInt32Key -> _SMCOSAccumSampleChannel : 100 -> 288
~ _SMCOSAccumSampleChannel -> _SMCWriteKey : 288 -> 116
~ _SMCOSAccumIsSupported -> _SMCWriteKeyWithKnownSize : 116 -> 360
~ _SMCWriteKeyWithKnownSize -> _SMCMakeUInt32Key : 360 -> 100
~ _lookup1msChannel : 172 -> 192
~ _lookup1secChannel : 172 -> 192
~ _SMCGetAccumStatusFor : 464 -> 468
```
