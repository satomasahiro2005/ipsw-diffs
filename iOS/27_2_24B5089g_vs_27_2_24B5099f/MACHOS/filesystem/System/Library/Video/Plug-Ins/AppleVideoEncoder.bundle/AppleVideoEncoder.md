## AppleVideoEncoder

> `/System/Library/Video/Plug-Ins/AppleVideoEncoder.bundle/AppleVideoEncoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f014c` | `0x1f1bd8` | **`+0x1a8c`** |
| `__TEXT.__cstring` | `0x5b565` | `0x5bde2` | **`+0x87d`** |
| `__TEXT.__const` | `0x25468` | `0x25528` | **`+0xc0`** |
| `__TEXT.__auth_stubs` | `0x1050` | `0x10a0` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x838` | `0x860` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xa00` | `0xa18` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x730` | `0x734` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__init_offsets`

### Other Changes

```diff

-913.48.1.0.0
+913.63.1.0.0

-  Functions: 1980
-  Symbols:   496
-  CStrings:  7552
+  Functions: 1986
+  Symbols:   501
+  CStrings:  7587
Symbols:
+ _CMBlockBufferAppendBufferReference
+ _CMBlockBufferCreateEmpty
+ _CMBlockBufferCreateWithBufferReference
+ _CMBlockBufferGetDataLength
+ _CMSampleBufferCreateCopyWithNewTiming
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
+ "20:40:45"
+ "20:40:48"
+ "20:40:50"
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
- "19:59:57"
- "20:00:01"
- "20:00:02"
- "20:00:03"
- "20:00:04"
- "913.48.1"
- "Sep 13 2026"
- "iNumberOfTemporalLayers >= 1"
- "iUserRPSForFaceTime > 0"
```
