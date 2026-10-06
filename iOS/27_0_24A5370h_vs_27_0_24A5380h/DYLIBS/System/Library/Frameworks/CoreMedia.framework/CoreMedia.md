## CoreMedia

> `/System/Library/Frameworks/CoreMedia.framework/CoreMedia`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x1d360` | `0x1d1c0` | **`-0x1a0`** |
| `__TEXT.__cstring` | `0x5ff2a` | `0x5fdfa` | **`-0x130`** |
| `__TEXT.__text` | `0x2dd758` | `0x2dd884` | **`+0x12c`** |
| `__TEXT.__oslogstring` | `0x32d67` | `0x32e68` | **`+0x101`** |
| `__DATA.__common` | `0x8c0` | `0x7e0` | **`-0xe0`** |
| `__DATA_DIRTY.__common` | `0x2c8` | `0x3a8` | **`+0xe0`** |
| `__TEXT.__eh_frame` | `0x26a8` | `0x2760` | **`+0xb8`** |
| `__AUTH_CONST.__const` | `0xce80` | `0xce00` | **`-0x80`** |
| `__DATA_DIRTY.__data` | `0x2ec` | `0x35c` | **`+0x70`** |
| `__DATA.__bss` | `0xa1b8` | `0xa158` | **`-0x60`** |
| `__DATA.__data` | `0x2d00` | `0x2ca8` | **`-0x58`** |
| `__DATA_CONST.__const` | `0xbc70` | `0xbc20` | **`-0x50`** |
| `__TEXT.__unwind_info` | `0x78e8` | `0x7898` | **`-0x50`** |
| `__DATA_DIRTY.__bss` | `0x1b00` | `0x1b20` | **`+0x20`** |
| `__TEXT.__const` | `0xa798` | `0xa7b8` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x2460` | `0x2470` | **`+0x10`** |

### Other Changes

```diff

-3350.63.2.11.1
+3350.67.2.0.0

-  Functions: 17263
-  Symbols:   12742
-  CStrings:  15272
+  Functions: 17243
+  Symbols:   12710
+  CStrings:  15258
Symbols:
+ _swift_willThrowTypedImpl
- _FigTransportGetCMBaseObject
- _FigTransportGetClassID
- _FigTransportGetTypeID
- _FigTransportServiceGetCMBaseObject
- _FigTransportServiceGetClassID
- _FigTransportServiceGetTypeID
- _FigTransportSessionGetCMBaseObject
- _FigTransportSessionGetClassID
- _FigTransportSessionGetTypeID
- _FigTransportStreamGetCMBaseObject
- _FigTransportStreamGetClassID
- _FigTransportStreamGetTypeID
- _FigTransportStreamSendBatchSlow
- _kFigTransportSessionNotification_Disconnected
- _kFigTransportSessionNotification_KeepAliveResponseReceived
- _kFigTransportSessionProperty_KeepAliveInterval
- _kFigTransportSessionProperty_KeepAliveType
- _kFigTransportSessionProperty_UUID
- _kFigTransportSessionStreamOption_DelegatedID
- _kFigTransportSessionStreamOption_GroupID
- _kFigTransportSessionStreamOption_StreamPriority
- _kFigTransportSessionStreamOption_Type
- _kFigTransportStreamProperty_ID
- _service_copyFormattingDesc
- _service_getClassID
- _service_getClassID.sClassDesc
- _session_copyFormattingDesc
- _session_getClassID
- _session_getClassID.sClassDesc
- _stream_getClassID.sClassDesc
- _transport_copyFormattingDesc
- _transport_getClassID
- _transport_getClassID.sClassDesc
CStrings:
+ "<< FigEndpointManagerXPCRemote >> %s: Created aggregate endpoint proxy (type %d): <FigEndpointRemote %{private}p>{ endpointID : %{public}@ }"
+ "<<<< AudioFormatDescription >>>> %s: (%p) Creation layout channel count %d doesn't match the ASBD channel count %d."
+ "alternateIndex > 3"
+ "hevcbridgeParseSMPTE_ST2094_50AdaptiveToneMap"
- "DelegatedID"
- "FigTransport"
- "FigTransportService"
- "FigTransportSession"
- "FigTransportStream"
- "KeepAliveInterval"
- "KeepAliveType"
- "StreamGroupID"
- "StreamPriority"
- "StreamType"
- "TransportSession_Disconnected"
- "TransportSession_KeepAliveResponseReceived"
- "TransportStreamProperty_ID"
- "[FigTransport %p]"
- "[FigTransportService %p]"
- "[FigTransportSession %p]"
- "[FigTransportStream %p]"
- "alternateIndex > 4"
```
