## MediaContinuityKit

> `/System/Library/PrivateFrameworks/MediaContinuityKit.framework/MediaContinuityKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x127240` | `0x128a98` | **`+0x1858`** |
| `__TEXT.__cstring` | `0x192e` | `0x1c43` | **`+0x315`** |
| `__DATA.__data` | `0x2c00` | `0x2b48` | **`-0xb8`** |
| `__TEXT.__unwind_info` | `0x51c8` | `0x5270` | **`+0xa8`** |
| `__AUTH_CONST.__const` | `0x89c8` | `0x8978` | **`-0x50`** |
| `__TEXT.__eh_frame` | `0xf934` | `0xf980` | **`+0x4c`** |
| `__TEXT.__swift5_reflstr` | `0x5f14` | `0x5ed4` | **`-0x40`** |
| `__TEXT.__swift5_typeref` | `0x3e51` | `0x3e1f` | **`-0x32`** |
| `__TEXT.__swift5_capture` | `0xd08` | `0xcdc` | **`-0x2c`** |
| `__TEXT.__const` | `0xd9e4` | `0xd9c4` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x5588` | `0x5570` | **`-0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x4640` | `0x4628` | **`-0x18`** |
| `__AUTH.__data` | `0x46c8` | `0x46b8` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x13a0` | `0x13b0` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x100` | `0xf0` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x3835` | `0x3845` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xefc` | `0xf08` | **`+0xc`** |
| `__DATA_CONST.__objc_protorefs` | `0x88` | `0x80` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x640` | `0x648` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x564` | `0x568` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x780` | `0x784` | **`+0x4`** |

### Other Changes

```diff

-100.40.1.0.0
+100.45.0.0.0

-  Functions: 4434
-  Symbols:   1825
-  CStrings:  496
+  Functions: 4442
+  Symbols:   1820
+  CStrings:  509
Symbols:
+ ___swift_project_boxed_opaque_existential_0
+ _objc_retain_x9
+ _swift_task_reportUnexpectedExecutor
- __OBJC_$_PROTOCOL_REFS_OS_nw_endpoint
- __OBJC_LABEL_PROTOCOL_$_OS_nw_endpoint
- __OBJC_PROTOCOL_$_OS_nw_endpoint
- _flat unique So14OS_nw_endpoint_p
- _swift_continuation_resume
- _symbolic Sccyyt_____G s5NeverO
- _symbolic _____ So17CMSampleBufferRefa
- _symbolic ______p So14OS_nw_endpointP
CStrings:
+ "MediaContinuityKit/AVConferenceBackedMediaStream.swift"
+ "MediaContinuityKit/AVConferenceBackedScreenCapture.swift"
+ "MediaContinuityKit/CoexServerXPCListener.swift"
+ "MediaContinuityKit/FigPWDSenderBackedProtectedDisplayKeyNegotiator.swift"
+ "MediaContinuityKit/MediaContinuityCoexSession.swift"
+ "MediaContinuityKit/MediaStreamAVConference.swift"
+ "MediaContinuityKit/MediaStreamManager.swift"
+ "MediaContinuityKit/NetworkBackedControlConnection.swift"
+ "MediaContinuityKit/NetworkBackedControlConnectionListener.swift"
+ "MediaContinuityKit/ProtectedDisplayKeyNegotiationResponder.swift"
+ "MediaContinuityKit/RequestResponseCoordinator.swift"
+ "MediaContinuityKit/VideoStreamAVConference.swift"
+ "_createCheckedContinuation(_:)"
```
