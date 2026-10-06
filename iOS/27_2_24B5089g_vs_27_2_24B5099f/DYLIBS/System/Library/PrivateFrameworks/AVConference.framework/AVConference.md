## AVConference

> `/System/Library/PrivateFrameworks/AVConference.framework/AVConference`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x420` | `0x6570` | **`+0x6150`** |
| `__DATA.__data` | `0x7c68` | `0x1c10` | **`-0x6058`** |
| `__TEXT.__text` | `0x7e2570` | `0x7e3170` | **`+0xc00`** |
| `__DATA.__bss` | `0x920` | `0xf18` | **`+0x5f8`** |
| `__DATA_DIRTY.__bss` | `0xab0` | `0x4c0` | **`-0x5f0`** |
| `__TEXT.__oslogstring` | `0x1435e0` | `0x143a07` | **`+0x427`** |
| `__AUTH.__data` | `0xf8` | `—` | **`-0xf8`** |
| `__AUTH_CONST.__objc_const` | `0x6d1d8` | `0x6d248` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x29e00` | `0x29e40` | **`+0x40`** |
| `__TEXT.__cstring` | `0x9f784` | `0x9f79e` | **`+0x1a`** |
| `__TEXT.__objc_methlist` | `0x3ac38` | `0x3ac50` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x2dc8` | `0x2ddc` | **`+0x14`** |
| `__TEXT.__unwind_info` | `0x125e0` | `0x125f0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x7748` | `0x7754` | **`+0xc`** |

### Other Changes

```diff

-2260.11.1.0.0
+2260.14.1.0.0

-  Functions: 35504
-  Symbols:   42030
-  CStrings:  34121
+  Functions: 35511
+  Symbols:   42036
+  CStrings:  34132
Symbols:
+ -[VCVideoStreamSendGroupConfig enableSyncGroupReferenceTimestamp]
+ -[VCVideoStreamSendGroupConfig setEnableSyncGroupReferenceTimestamp:]
+ _OBJC_IVAR_$_VCCoreAudio_AudioUnitMock._isImplicitPreferenceSession
+ _OBJC_IVAR_$_VCVideoStreamSendGroup._enableSyncGroupReferenceTimestamp
+ _OBJC_IVAR_$_VCVideoStreamSendGroupConfig._enableSyncGroupReferenceTimestamp
+ ___44-[VCControlChannelMultiWay lastUsedMKIBytes]_block_invoke
+ ___block_descriptor_40_e8_32o_e232_v20?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}^IQ})}12ls32l8
- ___block_descriptor_40_e8_32o_e229_v20?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}})}12ls32l8
CStrings:
+ " [%s] %s:%d %@(%p) Video frame is too old and modulated timestamp rolled backward – dropping frame. modulatedTimestamp=%u, frameTimeInSec=%f, rtpTimestampRate=%u"
+ " [%s] %s:%d Bad buffer length(%zu) for FaceTime audio media control info with header bitmap 0x%x, expecting %zu"
+ " [%s] %s:%d Bad buffer length(%zu) for FaceTime audio media control info, expecting %zu"
+ " [%s] %s:%d Not enough buffer for ECN CE count"
+ " [%s] %s:%d Not enough buffer for ECN ECT1 count"
+ " [%s] %s:%d Not enough buffer for bandwidth estimation"
+ " [%s] %s:%d Not enough buffer for video burst loss"
+ " [%s] %s:%d SignalEncoder[%p] MSCEncoderSessionInit failed with error=%d"
+ " [%s] %s:%d Video frame is too old and modulated timestamp rolled backward – dropping frame. modulatedTimestamp=%u, frameTimeInSec=%f, rtpTimestampRate=%u"
+ " [%s] %s:%d [FTDC] _dualCaptureSupported=%d, useVirtualCapture=%d"
+ " [%s] %s:%d configureWithBuffer failed with error %08X for control info=%p, dropping it"
+ "-[VCControlChannelMultiWay lastUsedMKIBytes]_block_invoke"
+ "2260.14.1"
+ "VideoPacketBuffer [%s] %s:%d /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/AVConference/AVConference.subproj/Sources/Others/VideoPacketBuffer.c:%d: VideoPacketBuffer[%p] Reusing cached plaintext for re-assembled frame timestamp=%u frameSequenceNumber=%d isLate=%d"
+ "lcid"
+ "rcid"
+ "v20@?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}^IQ})}12"
- " [%s] %s:%d Bad buffer length(%zu) for FaceTime audio media control info, expecting %u"
- " [%s] %s:%d SignalEncoder[%p] MSCEncoderSessionCreate failed with error=%i"
- " [%s] %s:%d [FTDC] _dualCaptureSupported=%d"
- "-[VCControlChannelMultiWay lastUsedMKIBytes]"
- "2260.11.1"
- "v20@?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}})}12"
```
