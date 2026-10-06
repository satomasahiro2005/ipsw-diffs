## SiriAudioFlowTools

> `/System/Library/FlowTools/Tools/SiriAudioFlowTools.flowtool/SiriAudioFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x62f34` | `0x65420` | **`+0x24ec`** |
| `__TEXT.__oslogstring` | `0x3a88` | `0x3cd8` | **`+0x250`** |
| `__TEXT.__const` | `0x6d40` | `0x6ee0` | **`+0x1a0`** |
| `__DATA.__bss` | `0x9d40` | `0x9ec0` | **`+0x180`** |
| `__DATA_CONST.__const` | `0x3368` | `0x34a0` | **`+0x138`** |
| `__TEXT.__auth_stubs` | `0x1950` | `0x1a70` | **`+0x120`** |
| `__TEXT.__eh_frame` | `0x26b0` | `0x27c0` | **`+0x110`** |
| `__TEXT.__swift5_typeref` | `0x18cc` | `0x1960` | **`+0x94`** |
| `__DATA_CONST.__auth_got` | `0xcb0` | `0xd40` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x13f4` | `0x1478` | **`+0x84`** |
| `__TEXT.__unwind_info` | `0x1470` | `0x14e0` | **`+0x70`** |
| `__DATA.__data` | `0x24d0` | `0x2538` | **`+0x68`** |
| `__DATA_CONST.__auth_ptr` | `0x2120` | `0x2170` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x430` | `0x480` | **`+0x50`** |
| `__TEXT.__cstring` | `0xa75` | `0xab5` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x17e0` | `0x180c` | **`+0x2c`** |
| `__TEXT.__objc_methtype` | `0x1` | `0x26` | **`+0x25`** |
| `__TEXT.__objc_stubs` | `0x480` | `0x4a0` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x194` | `0x1b4` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x400` | `0x410` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x5d0` | `0x5e0` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x14bf` | `0x14cf` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x148` | `0x154` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x120` | `0x128` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x19c` | `0x1a4` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xec` | `0xf4` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x48` | `0x4c` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x90` | `0x94` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-3600.33.9.0.0
+3600.33.17.0.0

+  - /System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote

+  - /usr/lib/swift/libswiftRegexBuilder.dylib

+  - /usr/lib/swift/libswift_StringProcessing.dylib

-  Functions: 1655
-  Symbols:   192
-  CStrings:  313
+  Functions: 1692
+  Symbols:   205
+  CStrings:  322
Symbols:
+ _MRMediaRemoteSendCommandWithReply
+ _OBJC_CLASS_$_NSNumber
+ _OBJC_CLASS_$_OS_dispatch_queue
+ __Block_copy
+ __Block_release
+ __NSConcreteStackBlock
+ _kMRMediaRemoteOptionRemoteControlInterfaceIdentifier
+ _objc_retain_x26
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_dynamicCastObjCClass
+ _swift_getForeignTypeMetadata
+ _swift_retain_x2
CStrings:
+ "PlayAudioAppIntentExecutionStrategy.execute() - playbackRequestIdentifier=%{public}s applied to connect-to-speaker/warmup/play"
+ "PlayAudioAppIntentExecutionStrategy.playbackRequestIdentifier is 1P, try to use existing UUID"
+ "PlayAudioAppIntentExecutionStrategy.playbackRequestIdentifier not 1P ('%s'), mint new UUID"
+ "UpdateAudioAffinityAppIntentExecutionStrategy.skipToNextTrackIfNeeded() companion-paired request, not sending local next-track command (audio is on another device)"
+ "UpdateAudioAffinityAppIntentExecutionStrategy.skipToNextTrackIfNeeded() disliked a song, sending next-track command"
+ "UpdateAudioAffinityAppIntentExecutionStrategy.skipToNextTrackIfNeeded() next-track command did not succeed"
+ "com.apple.amp.agora"
+ "integerValue"
+ "sendNextTrackCommand()"
+ "v16@?0r^{__CFArray=}8"
- "PlayAudioAppIntentExecutionStrategy.execute() - minted playbackRequestIdentifier=%{public}s applied to connect-to-speaker/warmup/play"
```
