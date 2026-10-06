## AVConference

> `/System/Library/PrivateFrameworks/AVConference.framework/AVConference`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7e15bc` | `0x7e2570` | **`+0xfb4`** |
| `__TEXT.__oslogstring` | `0x1431d7` | `0x1435e0` | **`+0x409`** |
| `__TEXT.__objc_methlist` | `0x3ab38` | `0x3ac38` | **`+0x100`** |
| `__AUTH_CONST.__objc_const` | `0x6d0e8` | `0x6d1d8` | **`+0xf0`** |
| `__DATA.__data` | `0x7ce8` | `0x7c68` | **`-0x80`** |
| `__DATA_CONST.__got` | `0x1e48` | `0x1dd8` | **`-0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x18dd0` | `0x18e40` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x12590` | `0x125e0` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x29de0` | `0x29e00` | **`+0x20`** |
| `__TEXT.__cstring` | `0x9f767` | `0x9f784` | **`+0x1d`** |
| `__DATA.__objc_ivar` | `0x772c` | `0x7748` | **`+0x1c`** |
| `__DATA.__bss` | `0x938` | `0x920` | **`-0x18`** |
| `__TEXT.__gcc_except_tab` | `0x2dbc` | `0x2dc8` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x2c60` | `0x2c68` | **`+0x8`** |

### Other Changes

```diff

-2260.9.1.0.0
+2260.11.1.0.0

-  Functions: 35479
-  Symbols:   42007
-  CStrings:  34109
+  Functions: 35504
+  Symbols:   42030
+  CStrings:  34121
Symbols:
+ +[VCAudioToolboxAudioComponentMock activeInstanceCount]
+ +[VCAudioToolboxAudioComponentMock isMockingSessionActive]
+ -[VCAVFoundationCapture secondaryCameraRequestSizeForAspectRatio:]
+ -[VCAudioToolboxAudioComponentMock autorelease]
+ -[VCAudioToolboxAudioComponentMock release]
+ -[VCAudioToolboxAudioComponentMock retainCount]
+ -[VCAudioToolboxAudioComponentMock retain]
+ -[VCAudioTransmitterConfig setShouldCapBitrateForWatchRelay:]
+ -[VCAudioTransmitterConfig shouldCapBitrateForWatchRelay]
+ -[VCCallSession isRemoteWatchRelayDeviceWithDeviceType:]
+ -[VCCoreAudio_AudioUnitMock autorelease]
+ -[VCCoreAudio_AudioUnitMock beginSession]
+ -[VCCoreAudio_AudioUnitMock endSession]
+ -[VCCoreAudio_AudioUnitMock isMockingEnabled]
+ -[VCCoreAudio_AudioUnitMock release]
+ -[VCCoreAudio_AudioUnitMock retainCount]
+ -[VCCoreAudio_AudioUnitMock retain]
+ -[VCRTPHistory dealloc]
+ -[VCVideoStream canReuseTransportsForStreamConfigs:]
+ -[VCVideoStream expectedTransportArrayCountForStreamConfigs:]
+ -[VCVideoStream transportArrayContainsRTXTransport]
+ -[VCVideoStream transportStreamCountForStreamConfig:]
+ -[VCVideoStream willCreateRTXTransportForStreamConfig:]
+ GCC_except_table139
+ GCC_except_table141
+ GCC_except_table143
+ GCC_except_table145
+ GCC_except_table147
+ GCC_except_table210
+ GCC_except_table314
+ GCC_except_table368
+ GCC_except_table452
+ _OBJC_IVAR_$_VCAVFoundationCapture._dualCaptureRear1440x1080
+ _OBJC_IVAR_$_VCAudioToolboxAudioComponentMock._instancesLock
+ _OBJC_IVAR_$_VCAudioTransmitter._shouldCapBitrateForWatchRelay
+ _OBJC_IVAR_$_VCAudioTransmitterConfig._shouldCapBitrateForWatchRelay
+ _OBJC_IVAR_$_VCMockIDSDatagramChannel._enqueueLock
+ _OBJC_IVAR_$_VCMockIDSDatagramChannel._queueLock
+ _OBJC_IVAR_$_VCSession._remoteParticipantsMapLock
+ _objc_getAssociatedObject
+ _objc_setAssociatedObject
- -[VCAudioToolboxAudioComponentMock dealloc]
- -[VCCoreAudio_AudioUnitMock dealloc]
- GCC_except_table138
- GCC_except_table140
- GCC_except_table142
- GCC_except_table144
- GCC_except_table146
- GCC_except_table211
- GCC_except_table313
- GCC_except_table36
- GCC_except_table367
- GCC_except_table451
- ___30-[VCSession participantForID:]_block_invoke
- __audioComponentMockLock
- __audioUnitMockLock
- __weakAudioComponentMockInstance
- __weakAudioUnitMockInstance
- _objc_loadWeakRetained
CStrings:
+ " [%s] %s:%d %@(%p) Failed to allocate the active instances set"
+ " [%s] %s:%d %@(%p) Failed to init the instances lock"
+ " [%s] %s:%d %@(%p) [FTDC] No desired secondary capture formats: no video device format matches width=%d, height=%d, aspectRatio=%d among %lu multicam candidates of %lu total"
+ " [%s] %s:%d %@(%p) [FTDC] No exact %dx%d rear format (picker chose %dx%d); falling back to %dx%d"
+ " [%s] %s:%d Failed to allocate _enqueueLock"
+ " [%s] %s:%d Failed to allocate _queueLock"
+ " [%s] %s:%d Failed to allocate the active instances set"
+ " [%s] %s:%d Failed to init the instances lock"
+ " [%s] %s:%d [FTDC] No desired secondary capture formats: no video device format matches width=%d, height=%d, aspectRatio=%d among %lu multicam candidates of %lu total"
+ " [%s] %s:%d [FTDC] No exact %dx%d rear format (picker chose %dx%d); falling back to %dx%d"
+ " [%s] %s:%d beginSession: %lu audio unit mock instance(s) carried over from a previous session"
+ " [%s] %s:%d beginSession: %lu component mock instance(s) leaked from a previous session (never disposed)"
+ "-[VCAudioToolboxAudioComponentMock init]"
+ "-[VCCoreAudio_AudioUnitMock beginSession]"
+ "2260.11.1"
+ "VCVideoStream [%s] %s:%d %@(%p) Rebuilding transports for reconfigure. currentCount=%u expectedCount=%u localSSRCChanged=%d canReuse=%d"
+ "VCVideoStream [%s] %s:%d Rebuilding transports for reconfigure. currentCount=%u expectedCount=%u localSSRCChanged=%d canReuse=%d"
+ "dualCaptureRear1440x1080"
- " [%s] %s:%d %@(%p) no streams available"
- " [%s] %s:%d no streams available"
- "-[VCSessionUplinkVideoStreamController anchorStreamIDWithCappedVideoStreamIDs:]"
- "2260.9.1"
- "VCVideoStream [%s] %s:%d %@(%p) Reconfiguring VCVideoStream with a different number of transports."
- "VCVideoStream [%s] %s:%d Reconfiguring VCVideoStream with a different number of transports."
```
