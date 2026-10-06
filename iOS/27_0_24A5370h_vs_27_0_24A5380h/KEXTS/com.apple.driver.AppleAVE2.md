## com.apple.driver.AppleAVE2

> `com.apple.driver.AppleAVE2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1c9b10` | `0x1c9a80` | **`-0x90`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ sub_fffffff008690aac -> sub_fffffff008688fac : 84 -> 68
~ __ZN8AVE_DDPB14SetDPBSnapShotEP19_S_AVE_DPB_Snapshotj : 1612 -> 1596
~ sub_fffffff0086a90c8 -> sub_fffffff0086a15a8 : 72 -> 80
~ sub_fffffff0086a9110 -> sub_fffffff0086a15f8 : 64 -> 80
~ sub_fffffff0086a9274 -> sub_fffffff0086a176c : 288 -> 296
~ __Z22AVE_CHM_SetDataInfo_RCP10_S_AVE_CHMP14_S_AVE_CmdInfoP16_S_AVE_FrameInfoP18AVE_PICMGMT_PARAMS : 2196 -> 2200
~ __Z25AVE_CHM_SetDataInfo_FwBufP10_S_AVE_CHMP14_S_AVE_CmdInfoP16_S_AVE_FrameInfoP14_S_AVE_DPB_SetP18AVE_PICMGMT_PARAMS : 20508 -> 20540
~ __Z17AVE_Client_ConfigP13_S_AVE_ClientP21_S_AVE_SurfaceIDInSet : 1188 -> 1196
~ __Z24AVE_Enc_CheckSearchRange12_E_AVE_DevID14_E_AVE_EncTypeiiii : 788 -> 796
~ sub_fffffff0087066b8 -> sub_fffffff0086febec : 84 -> 68
~ sub_fffffff008707f58 -> sub_fffffff00870047c : 60 -> 76
~ __ZN7AVE_DLB11ApplyStaticEP13_S_AVE_ClientP15_S_AVE_DLB_Info : 1832 -> 1828
~ __ZN7AVE_Drv22ProcessInputCmd_AssignEP13_S_AVE_ClientP10_S_AVE_Cmd : 3008 -> 3016
~ sub_fffffff008742320 -> sub_fffffff00873a858 : 772 -> 728
~ sub_fffffff008742a04 -> sub_fffffff00873af10 : 500 -> 488
~ sub_fffffff008745070 -> sub_fffffff00873d570 : 104 -> 88
~ sub_fffffff0087910d8 -> sub_fffffff0087895c8 : 72 -> 80
~ sub_fffffff008791120 -> sub_fffffff008789618 : 64 -> 80
~ sub_fffffff0087912c4 -> sub_fffffff0087897cc : 72 -> 80
~ sub_fffffff00879130c -> sub_fffffff00878981c : 64 -> 80
~ sub_fffffff008791470 -> sub_fffffff008789990 : 288 -> 296
~ sub_fffffff008793178 -> sub_fffffff00878b6a0 : 492 -> 476
~ __ZN9AVE_LAGOP11PostProcessEP10FrameStatsiiiPA4_P16_S_AVE_FrameInfoPA4_Pi : 1712 -> 1728
~ __ZN7AVE_IPC13CreateChannelEiim : 2012 -> 1992
~ __ZN8AVE_PMGR19SetPSDependencyDownEPK22_S_AVE_DevCap_PDDepSet14_E_AVE_PMGR_PD14_E_AVE_PMGR_PSb : 644 -> 620
~ __ZN8AVE_PMGR19SetPSDependencyDownEPK22_S_AVE_DevCap_PDDepSet14_E_AVE_PMGR_PD14_E_AVE_PMGR_PSb : 672 -> 652
~ sub_fffffff0087bc7fc -> sub_fffffff0087b4ce4 : 2620 -> 2456
~ sub_fffffff0087bd5e4 -> sub_fffffff0087b5a28 : 68 -> 80
~ sub_fffffff0087bd628 -> sub_fffffff0087b5a78 : 64 -> 80
~ sub_fffffff0087d2410 -> sub_fffffff0087ca870 : 176 -> 164
~ sub_fffffff0087d24c0 -> sub_fffffff0087ca914 : 3372 -> 3376
~ __ZN10AVE_SVEDPB5CheckEx : 2628 -> 2604
~ __ZN10AVE_SVEDPB6UpdateEx24_E_AVE_SVEDPB_FrameState : 2948 -> 2964
~ sub_fffffff00881b3d8 -> sub_fffffff008813828 : 68 -> 76
~ sub_fffffff0088242f8 -> sub_fffffff00881c750 : 72 -> 80
~ sub_fffffff008824340 -> sub_fffffff00881c7a0 : 64 -> 80
~ sub_fffffff008824380 -> sub_fffffff00881c7f0 : 288 -> 296
~ __Z19AV1_FindProfileName14_E_AV1_Profile : 288 -> 296
~ sub_fffffff00882e018 -> sub_fffffff008826498 : 212 -> 204
~ sub_fffffff00884906c -> sub_fffffff0088414e4 : 52 -> 44
CStrings:
+ "21:20:05"
+ "Jun 29 2026"
- "19:40:52"
- "Jun 18 2026"
```
