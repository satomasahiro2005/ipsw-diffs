## libSMC.dylib

> `/usr/lib/libSMC.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5028` | `0x50fc` | **`+0xd4`** |

### Other Changes

```text
Functions:
~ _SMCParseBytesForNumeric : 432 -> 440
~ _SMCMakeUInt32Key : 104 -> 100
~ _SMCAEPopulatePlatform : 1056 -> 1076
~ _SMCAccumGetChannelInfoForKey : 240 -> 264
~ _SMCAEPopulateChannelInfo : 700 -> 704
~ _findMaxClientCreatorAndReport : 704 -> 716
~ _SMCReadBigEndianArrayToUIntMax : 44 -> 52
~ _SMCReadLittleEndianArrayToUIntMax : 52 -> 44
~ _SMCConvertNumericToBytes : 340 -> 348
~ _SMCSetAccum1msChannels : 112 -> 108
~ _SMCSetAccum1secChannels : 112 -> 108
~ _populateChannels : 172 -> 176
~ _copyKeyInfo : 144 -> 160
~ _SMCProgramAccumWithoutReset : 624 -> 632
~ _lookup1msChannel : 176 -> 172
~ _lookup1secChannel : 176 -> 172
~ _SMCProgramAccumDefaults : 556 -> 568
~ _SMCGetAccumStatus : 792 -> 816
~ _parseAccumOutput : 368 -> 416
~ _SMCGetAccumStatusFor : 444 -> 464
~ _SMCCreateAccumProgrammableChannelsDict1ms : 272 -> 284
~ _SMCCreateAccumProgrammableChannelsDict1sec : 272 -> 284
```
