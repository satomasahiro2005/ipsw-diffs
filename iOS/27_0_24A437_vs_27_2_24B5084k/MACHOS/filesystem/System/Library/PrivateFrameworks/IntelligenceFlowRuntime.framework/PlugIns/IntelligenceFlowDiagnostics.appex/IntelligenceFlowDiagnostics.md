## IntelligenceFlowDiagnostics

> `/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/PlugIns/IntelligenceFlowDiagnostics.appex/IntelligenceFlowDiagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c2f8` | `0x1b158` | **`-0x11a0`** |
| `__DATA_CONST.__const` | `0x19b0` | `0x1760` | **`-0x250`** |
| `__DATA.__bss` | `0x2300` | `0x2200` | **`-0x100`** |
| `__TEXT.__objc_stubs` | `0x580` | `0x480` | **`-0x100`** |
| `__TEXT.__swift5_capture` | `0x40c` | `0x388` | **`-0x84`** |
| `__TEXT.__const` | `0x1850` | `0x17e8` | **`-0x68`** |
| `__TEXT.__objc_methname` | `0x3f2` | `0x396` | **`-0x5c`** |
| `__TEXT.__swift5_typeref` | `0x6f2` | `0x69c` | **`-0x56`** |
| `__DATA.__objc_selrefs` | `0x180` | `0x140` | **`-0x40`** |
| `__TEXT.__auth_stubs` | `0x12d0` | `0x1310` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x540` | `0x508` | **`-0x38`** |
| `__TEXT.__eh_frame` | `0xb10` | `0xb40` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x788` | `0x758` | **`-0x30`** |
| `__DATA.__data` | `0x810` | `0x830` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x970` | `0x990` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0xd12` | `0xcf9` | **`-0x19`** |
| `__TEXT.__swift5_assocty` | `0x48` | `0x30` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x14` | **`-0x14`** |
| `__TEXT.__objc_methtype` | `0x4d` | `0x3d` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x128` | `0x11c` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x1f0` | `0x1f8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x7c` | `0x78` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-3600.156.4.501.4
+3605.14.3.501.4

-  Functions: 794
-  Symbols:   169
-  CStrings:  138
+  Functions: 762
+  Symbols:   163
+  CStrings:  129
Symbols:
- _swift_allocBox
- _swift_endAccess
- _swift_getForeignTypeMetadata
- _swift_projectBox
- _swift_release_x12
- _swift_retain_x8
CStrings:
+ "FeatureStore transcript query failed: %@"
+ "IntelligenceFlowDiagnostics: InteractionStoreAttachment error: %@"
+ "TranscriptAttachment: event has no source proto, skipping"
+ "TranscriptAttachment: file path: %{public}s"
+ "TranscriptAttachment: finished writing to: %{public}s"
- "Datastream"
- "IntelligenceFlow"
- "Transcript"
- "TranscriptAttachment: event has no data"
- "TranscriptAttachment: failed to fully publish events: %s"
- "TranscriptAttachment: file path: %s"
- "TranscriptAttachment: finished publishing events successfully"
- "TranscriptAttachment: finished writing to: %s"
- "TranscriptAttachment: unknown completion state: %s"
- "clientRequestId"
- "data"
- "identifiers"
- "sessionId"
- "setLastN:"
```
