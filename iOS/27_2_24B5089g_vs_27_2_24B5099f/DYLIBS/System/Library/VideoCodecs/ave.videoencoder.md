## ave.videoencoder

> `/System/Library/VideoCodecs/ave.videoencoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x172238` | `0x173c04` | **`+0x19cc`** |
| `__TEXT.__cstring` | `0x4c971` | `0x4d200` | **`+0x88f`** |
| `__TEXT.__const` | `0x25294` | `0x2534c` | **`+0xb8`** |
| `__AUTH_CONST.__auth_got` | `0x760` | `0x788` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xa48` | `0xa58` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x6e4` | `0x6e8` | **`+0x4`** |

### Other Changes

```diff

-913.48.1.0.0
+913.63.1.0.0

-  Functions: 1535
-  Symbols:   2336
-  CStrings:  6358
+  Functions: 1541
+  Symbols:   2347
+  CStrings:  6395
Symbols:
+ _CMBlockBufferAppendBufferReference
+ _CMBlockBufferCreateEmpty
+ _CMBlockBufferCreateWithBufferReference
+ _CMBlockBufferGetDataLength
+ _CMSampleBufferCreateCopyWithNewTiming
+ __ZL18AVE_AV1_FH_IsShownPKhi
+ __ZN29H264VideoEncoderFrameReceiver18WrapAV1BlockBufferEP19OpaqueCMBlockBufferxixi
+ __ZN29H264VideoEncoderFrameReceiver19DrainAV1ReadyTokensEv
+ __ZN29H264VideoEncoderFrameReceiver22FlushAV1ReorderPendingEv
+ __ZN29H264VideoEncoderFrameReceiver8TokenPopEP17_S_AVE_FrameToken
+ __ZN29H264VideoEncoderFrameReceiver9TokenPushEP16_S_AVE_FrameInfo
CStrings:
+ "%lld %d AVE %s: %s:%d %s | num pics out of range %u %u"
+ "%lld %d AVE %s: %s:%d %s | num pics out of range %u %u\n"
+ "%lld %d AVE %s: %s:%d FIG: Throughput calculated from iMaxFrameRate"
+ "%lld %d AVE %s: %s:%d FIG: Throughput calculated from iMaxFrameRate\n"
+ "%lld %d AVE %s: %s:%d turn off MCTF"
+ "%lld %d AVE %s: %s:%d turn off MCTF\n"
+ "%lld %d AVE %s: %s::%s:%d %s | %p TokenPush null frame"
+ "%lld %d AVE %s: %s::%s:%d %s | %p TokenPush null frame\n"
+ "%lld %d AVE %s: %s::%s:%d %s | AV1 token overflow %p %d"
+ "%lld %d AVE %s: %s::%s:%d %s | AV1 token overflow %p %d\n"
+ "%lld %d AVE %s: %s::%s:%d %s | AV1 token push failed %d frame %d"
+ "%lld %d AVE %s: %s::%s:%d %s | AV1 token push failed %d frame %d\n"
+ "%lld %d AVE %s: %s::%s:%d %s | WrapAV1BlockBuffer CMSampleBufferCreate failed %d"
+ "%lld %d AVE %s: %s::%s:%d %s | WrapAV1BlockBuffer CMSampleBufferCreate failed %d\n"
+ "%lld %d AVE %s: %s::%s:%d %s | WrapAV1BlockBuffer bad size %zu"
+ "%lld %d AVE %s: %s::%s:%d %s | WrapAV1BlockBuffer bad size %zu\n"
+ "%lld %d AVE %s: %s::%s:%d %s | WrapAV1BlockBuffer null block buffer"
+ "%lld %d AVE %s: %s::%s:%d %s | WrapAV1BlockBuffer null block buffer\n"
+ "%lld %d AVE %s: AV1 reorder bundle bbuf create failed %d"
+ "%lld %d AVE %s: AV1 reorder bundle bbuf create failed %d\n"
+ "%lld %d AVE %s: AV1 reorder disengaged with %d held / %d token(s) pending; flushing at frame %d"
+ "%lld %d AVE %s: AV1 reorder disengaged with %d held / %d token(s) pending; flushing at frame %d\n"
+ "%lld %d AVE %s: AV1 reorder hold overflow, dropping frame %d"
+ "%lld %d AVE %s: AV1 reorder hold overflow, dropping frame %d\n"
+ "%lld %d AVE %s: AV1 reorder ready FIFO overflow (bundle)"
+ "%lld %d AVE %s: AV1 reorder ready FIFO overflow (bundle)\n"
+ "%lld %d AVE %s: AV1 reorder ready FIFO overflow (sfx)"
+ "%lld %d AVE %s: AV1 reorder ready FIFO overflow (sfx)\n"
+ "%lld %d AVE %s: AV1 reorder retime failed %d for frame %lld; using placeholder timing"
+ "%lld %d AVE %s: AV1 reorder retime failed %d for frame %lld; using placeholder timing\n"
+ "0 < iNumberOfTemporalLayers && iNumberOfTemporalLayers <= 7"
+ "20:36:17"
+ "913.63.1"
+ "Sep 27 2026"
+ "TokenPush"
+ "WrapAV1BlockBuffer"
+ "bb != __null"
+ "err == noErr && sbuf != __null"
+ "iSampleSize > 0"
+ "iUserRPSForFaceTime > 0 && iUserRPSForFaceTime < 65"
+ "m_iAV1TokenCount >= 0 && m_iAV1TokenCount < 32"
+ "pInfo->num_negative_pics <= 16 && pInfo->num_positive_pics <= 16"
- "19:55:37"
- "913.48.1"
- "Sep 13 2026"
- "iNumberOfTemporalLayers >= 1"
- "iUserRPSForFaceTime > 0"
```
