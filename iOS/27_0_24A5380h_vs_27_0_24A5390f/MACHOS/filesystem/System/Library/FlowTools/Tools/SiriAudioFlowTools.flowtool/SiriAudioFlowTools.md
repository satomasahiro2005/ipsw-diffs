## SiriAudioFlowTools

> `/System/Library/FlowTools/Tools/SiriAudioFlowTools.flowtool/SiriAudioFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6301c` | `0x62f34` | **`-0xe8`** |
| `__TEXT.__oslogstring` | `0x39b8` | `0x3a88` | **`+0xd0`** |
| `__TEXT.__eh_frame` | `0x2740` | `0x26b0` | **`-0x90`** |
| `__TEXT.__auth_stubs` | `0x1920` | `0x1950` | **`+0x30`** |
| `__TEXT.__cstring` | `0xa55` | `0xa75` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xc98` | `0xcb0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1488` | `0x1470` | **`-0x18`** |
| `__DATA.__data` | `0x24c8` | `0x24d0` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x2118` | `0x2120` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x428` | `0x430` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x18c4` | `0x18cc` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x150` | `0x148` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0xf0` | `0xec` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-3600.33.6.0.0
+3600.33.9.0.0

-  Functions: 1658
+  Functions: 1655

-  CStrings:  311
+  CStrings:  313
CStrings:
+ "PlayAudioAppIntentExecutionStrategy.execute() - minted playbackRequestIdentifier=%{public}s applied to connect-to-speaker/warmup/play"
+ "PlayAudioAppIntentExecutionStrategy.warmupAudioQueueIntent() - Skipping warmup, remote request originatingDevice=%{public}s. PlayIntent runs directly without prewarmed queue."
+ "requestIdentifierOverride"
- "PlayAudioAppIntentExecutionStrategy.handleDestinationsAndWarmupAudioQueue() - warm up audio queue."
```
