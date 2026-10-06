## PCCAgentClientExtension

> `/System/Library/ExtensionKit/Extensions/PCCAgentClientExtension.appex/PCCAgentClientExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x32d70` | `0x37d94` | **`+0x5024`** |
| `__TEXT.__oslogstring` | `0x1c83` | `0x2023` | **`+0x3a0`** |
| `__TEXT.__auth_stubs` | `0x1500` | `0x17a0` | **`+0x2a0`** |
| `__TEXT.__eh_frame` | `0x2480` | `0x25d8` | **`+0x158`** |
| `__DATA_CONST.__auth_got` | `0xa88` | `0xbd8` | **`+0x150`** |
| `__DATA.__data` | `0xab0` | `0xbc8` | **`+0x118`** |
| `__DATA_CONST.__const` | `0x550` | `0x5c8` | **`+0x78`** |
| `__DATA_CONST.__got` | `0x2d0` | `0x348` | **`+0x78`** |
| `__TEXT.__constg_swiftt` | `0x3c0` | `0x428` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x9e8` | `0xa50` | **`+0x68`** |
| `__TEXT.__swift5_typeref` | `0x461` | `0x4c7` | **`+0x66`** |
| `__DATA.__objc_const` | `0x660` | `0x6c0` | **`+0x60`** |
| `__TEXT.__const` | `0xd60` | `0xdb0` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x238` | `0x278` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x114` | `0x150` | **`+0x3c`** |
| `__DATA_CONST.__auth_ptr` | `0x398` | `0x3d0` | **`+0x38`** |
| `__TEXT.__objc_methname` | `0x1cb` | `0x201` | **`+0x36`** |
| `__TEXT.__cstring` | `0x85d` | `0x88d` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x28c` | `0x2b0` | **`+0x24`** |
| `__TEXT.__swift_as_cont` | `0x220` | `0x240` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0xb8` | `0xc0` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xbc` | `0xc4` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-55.2.1.0.0
+62.0.0.0.0

-  Functions: 499
-  Symbols:   141
-  CStrings:  210
+  Functions: 528
+  Symbols:   144
+  CStrings:  224
Symbols:
+ _objc_release_x28
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
- _swift_retain_x22
CStrings:
+ "AIR inference report. requestID=%{public}s succeeded=%{bool,public}d latencySeconds=%{public}f"
+ "Cancelling the background connection task immediately; reason=%s."
+ "Closing LongLivedConnection; teardown=%s previousState=%s. elapsed=%s"
+ "Connection completed and streams finished"
+ "Emitted AIR inference event. requestID=%{public}s"
+ "Failed to emit AppleIntelligence inference event: %@"
+ "Failed to initialize AppleIntelligenceReporting.EventReporter: %@"
+ "Fresh connection went terminal before it could be claimed. session=%s"
+ "LongLivedConnection close() finished. elapsed=%s"
+ "PCC request already wound down before close(); nothing to cancel."
+ "PCC request already wound down before close(); nothing to watch."
+ "PCC request did not wind down within the grace period after close(); cancelling the background task as a last resort. This surfaces as cancellationReason=frameworkCancellation in PCC telemetry."
+ "PCC request wound down after close(). elapsed=%s"
+ "PCC request wound down on its own; no cancellation needed."
+ "backgroundWorkFinished"
+ "didSendRequest"
+ "teardownWatchdog"
- "Cancelling background connection task (if any)..."
- "Closing LongLivedConnection... currentState=%s"
- "LongLivedConnection closed successfully. elapsed=%s"
```
