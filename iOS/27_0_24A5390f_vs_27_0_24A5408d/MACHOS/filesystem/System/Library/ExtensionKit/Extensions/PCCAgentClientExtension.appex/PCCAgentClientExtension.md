## PCCAgentClientExtension

> `/System/Library/ExtensionKit/Extensions/PCCAgentClientExtension.appex/PCCAgentClientExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2c650` | `0x32d6c` | **`+0x671c`** |
| `__TEXT.__eh_frame` | `0x1f90` | `0x2480` | **`+0x4f0`** |
| `__TEXT.__oslogstring` | `0x18a2` | `0x1c83` | **`+0x3e1`** |
| `__TEXT.__auth_stubs` | `0x12b0` | `0x1500` | **`+0x250`** |
| `__TEXT.__unwind_info` | `0x8a8` | `0x9e8` | **`+0x140`** |
| `__DATA_CONST.__auth_got` | `0x960` | `0xa88` | **`+0x128`** |
| `__TEXT.__cstring` | `0x78e` | `0x85d` | **`+0xcf`** |
| `__DATA.__data` | `0x9f8` | `0xab0` | **`+0xb8`** |
| `__TEXT.__objc_methname` | `0x11c` | `0x1cb` | **`+0xaf`** |
| `__TEXT.__const` | `0xcd2` | `0xd60` | **`+0x8e`** |
| `__DATA.__objc_const` | `0x5e0` | `0x660` | **`+0x80`** |
| `__TEXT.__swift_as_cont` | `0x1a4` | `0x220` | **`+0x7c`** |
| `__TEXT.__swift5_reflstr` | `0x1e8` | `0x238` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x288` | `0x2d0` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x390` | `0x3c0` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x25c` | `0x28c` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x443` | `0x461` | **`+0x1e`** |
| `__DATA_CONST.__auth_ptr` | `0x388` | `0x398` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0xb0` | `0xbc` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0xb0` | `0xb8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-47.0.0.0.0
+55.2.1.0.0

-  Functions: 440
-  Symbols:   135
-  CStrings:  181
+  Functions: 499
+  Symbols:   141
+  CStrings:  210
Symbols:
+ _objc_retain_x27
+ _swift_allocBox
+ _swift_arrayInitWithCopy
+ _swift_bridgeObjectRetain_n
+ _swift_projectBox
+ _swift_release_x22
+ _swift_retain_x22
- _objc_retain_x26
CStrings:
+ "%s %s value %ld does not fit pid_t; using -1 sentinel"
+ "%s could not get handle for pid %d"
+ "%s could not get identifier for pid %d"
+ "%s could not get process bundle for pid=%d"
+ "%s daemon %s for pid=%d is not allowed"
+ "%s is bundle-id %s for pid %d"
+ "%{public}s"
+ "Background task cancelled during close(). elapsed=%s"
+ "Cancelling background connection task (if any)..."
+ "Emitted Request.MediaDecoderMetrics"
+ "Emitted RequestOutcome status=%{public}s reason=%{public}s"
+ "FinalResponse.Received"
+ "PCCAgent prewarmHint: already warm session=%s"
+ "PCCAgent prewarmHint: connection warm-up failed error=%@"
+ "PCCAgent prewarmHint: prefetch attestations for session=%s"
+ "PCCAgent prewarmHint: session=%s"
+ "PCCAgent prewarmHint: warmed connection for session=%s"
+ "Request.MediaDecoderMetrics"
+ "RequestOneShot"
+ "RequestOutcome"
+ "RequestStream"
+ "RequestStream.Finished"
+ "Reusing prewarmed connection for session=%s"
+ "Taskgroup for infinite read and write cancelled. elapsed=%s"
+ "Unexpected error in background task during close(). elapsed=%s error=%@"
+ "[Error] Interval already ended"
+ "auditToken"
+ "close() ignored; already %s."
+ "completionReason: %s"
+ "isClaimed"
+ "onBehalfOfPID"
+ "parentOfOnBehalfOfPID"
+ "part %ld/%ld\n%{public}s"
+ "responseCount: %ld"
+ "sessionUUID: %s"
+ "status=%{public, signpost.description=attribute,public}s, reason=%{public, signpost.description=attribute,public}s"
- "%s could not get handle for pid %ld"
- "%s could not get identifier for pid %ld"
- "%s could not get process bundle for pid=%ld"
- "%s daemon %s for pid=%ld is not allowed"
- "%s is bundle-id %s for pid %ld"
- "Index: %ld, %s"
- "PCCAgent start completePrewarm: with %s"
```
