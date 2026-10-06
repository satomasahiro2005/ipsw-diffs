## com.apple.driver.AppleAVE2

> `com.apple.driver.AppleAVE2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1d0028` | `0x1d0048` | **`+0x20`** |
| `__TEXT.__cstring` | `0x4804a` | `0x48053` | **`+0x9`** |
| `__TEXT.__os_log` | `0x5cabd` | `0x5cac2` | **`+0x5`** |

### Other Changes

```diff

-913.43.1.0.0
+913.48.1.0.0
Functions:
~ sub_fffffff0086fdc68 -> __Z27AVE_CHM_MakeFwCmd_Start_AVCP10_S_AVE_CHMyjP14_S_AVE_TimeOutP16sCAveCmdAvcStart : 1896 -> 1900
~ __Z27AVE_CHM_MakeFwCmd_Start_AV1P10_S_AVE_CHMyjP14_S_AVE_TimeOutP16sCAveCmdAv1Start : 1732 -> 1736
~ __Z25AVE_CHM_SetDataInfo_FwBufP10_S_AVE_CHMP14_S_AVE_CmdInfoP16_S_AVE_FrameInfoP14_S_AVE_DPB_SetP18AVE_PICMGMT_PARAMS : 23076 -> 23104
~ sub_fffffff008889630 -> sub_fffffff0088b5f14 : 48 -> 44
CStrings:
+ "%lld %d AVE %s: %s:%d %s | invalid MB/CTU stats firmware buffer %p %d %lld %p %lld | %d"
+ "%lld %d AVE %s: %s:%d %s | invalid MB/CTU stats firmware buffer %p %d %lld %p %lld | %d\n"
+ "2 <= pInfo->VideoParamsDriver.userDPBnumFrames && pInfo->VideoParamsDriver.userDPBnumFrames <= (((16) > (15) ? (16) : (15)) + 1)"
+ "23:11:01"
+ "913.48.1"
+ "Sep  4 2026"
+ "num_ref_frame <= ((16) > (15) ? (16) : (15))"
+ "pInfo->sBufPFSet.saMBStats[m].iAddr != 0"
- "%lld %d AVE %s: %s:%d %s | invalid MB/CTU stats firmware buffer %p %d %lld %p %lld"
- "%lld %d AVE %s: %s:%d %s | invalid MB/CTU stats firmware buffer %p %d %lld %p %lld\n"
- "2 <= pInfo->VideoParamsDriver.userDPBnumFrames && pInfo->VideoParamsDriver.userDPBnumFrames <= (((16) > (16) ? (16) : (16)) + 1)"
- "21:32:58"
- "913.43.1"
- "Aug 13 2026"
- "num_ref_frame <= ((16) > (16) ? (16) : (16))"
- "pInfo->sBufPFSet.sMBStats.iAddr != 0"
```
