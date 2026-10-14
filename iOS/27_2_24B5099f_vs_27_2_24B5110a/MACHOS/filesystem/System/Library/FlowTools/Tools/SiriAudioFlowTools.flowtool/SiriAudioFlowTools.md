## SiriAudioFlowTools

> `/System/Library/FlowTools/Tools/SiriAudioFlowTools.flowtool/SiriAudioFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x71c3c` | `0x7a244` | **`+0x8608`** |
| `__TEXT.__oslogstring` | `0x4498` | `0x47e8` | **`+0x350`** |
| `__TEXT.__eh_frame` | `0x2908` | `0x2c40` | **`+0x338`** |
| `__DATA.__bss` | `0xa040` | `0xa1c0` | **`+0x180`** |
| `__DATA_CONST.__const` | `0x3528` | `0x3670` | **`+0x148`** |
| `__TEXT.__const` | `0x7020` | `0x7168` | **`+0x148`** |
| `__TEXT.__swift5_reflstr` | `0x14cf` | `0x15ef` | **`+0x120`** |
| `__TEXT.__swift5_fieldmd` | `0x1828` | `0x192c` | **`+0x104`** |
| `__TEXT.__unwind_info` | `0x1538` | `0x1600` | **`+0xc8`** |
| `__TEXT.__auth_stubs` | `0x1be0` | `0x1ca0` | **`+0xc0`** |
| `__DATA.__data` | `0x2590` | `0x2628` | **`+0x98`** |
| `__DATA_CONST.__auth_ptr` | `0x2250` | `0x22e8` | **`+0x98`** |
| `__TEXT.__cstring` | `0xb75` | `0xc05` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x14a4` | `0x1518` | **`+0x74`** |
| `__TEXT.__swift5_typeref` | `0x19b8` | `0x1a1c` | **`+0x64`** |
| `__DATA_CONST.__auth_got` | `0xdf8` | `0xe58` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x4e8` | `0x548` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x1b4` | `0x1d4` | **`+0x20`** |
| `__TEXT.__swift_as_ret` | `0x158` | `0x178` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x5ec` | `0x5f8` | **`+0xc`** |
| `__TEXT.__swift_as_cont` | `0x94` | `0xa0` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0xf4` | `0x100` | **`+0xc`** |
| `__TEXT.__swift5_protos` | `0x4c` | `0x50` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x1a8` | `0x1ac` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-3605.23.1.0.0
+3605.24.1.0.0

+  - /System/Library/PrivateFrameworks/IntelligenceFlowShared.framework/IntelligenceFlowShared

-  Functions: 1721
+  Functions: 1761

-  CStrings:  340
+  CStrings:  352
CStrings:
+ "NowPlayingStyleService.requestStyle() - couldn't resolve %{public}s parameter type on %{public}s"
+ "NowPlayingStyleService.requestStyle() - failed to request Now Playing style: %s. This error is caught here, so it should not prevent playback."
+ "NowPlayingStyleService.requestStyle() result: %s"
+ "NowPlayingStyleService.requestStyle() style=%{public}s"
+ "PlayAudioAppIntentExecutionStrategy.requestAppIntentPrewarm() - no target intent, skipping prewarm: %s"
+ "PlayAudioAppIntentExecutionStrategy.requestAppIntentPrewarm() - prewarming %s on device %{private}s"
+ "RequestNowPlayingStyleIntent"
+ "ToolKitServiceProvider.getToolDefinition(bundleID:clientDeviceId:matching:) called with bundleID: %s, clientDeviceId: %s"
+ "ToolKitServiceProvider.getToolDefinition(bundleID:clientDeviceId:matching:) resolved tool for %s: %s"
+ "com.apple.pebblenowplaying"
+ "internalSignalsFromSiriAudio"
+ "speakerIDConfidence"
```
