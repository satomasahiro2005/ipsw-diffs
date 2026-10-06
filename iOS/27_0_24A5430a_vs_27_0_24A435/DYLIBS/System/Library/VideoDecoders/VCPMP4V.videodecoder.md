## VCPMP4V.videodecoder

> `/System/Library/VideoDecoders/VCPMP4V.videodecoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21138` | `0x211c4` | **`+0x8c`** |
| `__TEXT.__eh_frame` | `0x50` | `0xa0` | **`+0x50`** |

### Other Changes

```text
Functions:
~ __Z12IDct8x8smartPhiPsiiS_ : 1204 -> 1208
~ __Z15Y420ToY422_yuvsPhS_S_PittttiS_S_ : 268 -> 276
~ __Z15Y420ToY422_2vuyPhS_S_PittttiS_S_ : 276 -> 284
~ __ZL23S_DeblockPlaneFastSmartP13INSTANCE_DECOP9buffer_u8S2_i : 516 -> 540
~ __Z18ResetAtBoundaryTopP15intra_predictori : 120 -> 124
~ __Z26RecoverMissingVideoPacketsP5frameS0_iiP13INSTANCE_DECO : 460 -> 500
~ __ZL16ReadAVideoPacketPihP5frameS1_P13INSTANCE_DECO : 9224 -> 9260
~ __ZL31DecodeBlockIntraDataPartitionedPhPsS0_S_iiiiihiiP13INSTANCE_DECOP15CIntraDcDecoderP14CBitStreamDeco : 464 -> 468
~ _CopyS16BlockToFrame : 140 -> 144
~ _CopyToBuffer_S16 : 96 -> 100
~ _CopyFromBuffer_S16 : 128 -> 132
```
