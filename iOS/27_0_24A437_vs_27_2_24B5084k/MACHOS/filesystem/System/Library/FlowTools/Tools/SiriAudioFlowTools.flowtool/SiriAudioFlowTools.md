## SiriAudioFlowTools

> `/System/Library/FlowTools/Tools/SiriAudioFlowTools.flowtool/SiriAudioFlowTools`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6543c` | `0x71044` | **`+0xbc08`** |
| `__TEXT.__oslogstring` | `0x3cd8` | `0x4494` | **`+0x7bc`** |
| `__DATA.__bss` | `0x9ec0` | `0xa040` | **`+0x180`** |
| `__TEXT.__auth_stubs` | `0x1a70` | `0x1be0` | **`+0x170`** |
| `__TEXT.__const` | `0x6ee0` | `0x7008` | **`+0x128`** |
| `__TEXT.__eh_frame` | `0x27c0` | `0x28a8` | **`+0xe8`** |
| `__TEXT.__cstring` | `0xab5` | `0xb75` | **`+0xc0`** |
| `__DATA_CONST.__auth_got` | `0xd40` | `0xdf8` | **`+0xb8`** |
| `__DATA_CONST.__auth_ptr` | `0x2170` | `0x2218` | **`+0xa8`** |
| `__DATA_CONST.__const` | `0x34a0` | `0x3520` | **`+0x80`** |
| `__DATA_CONST.__got` | `0x480` | `0x4e8` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x14e0` | `0x1548` | **`+0x68`** |
| `__DATA.__data` | `0x2538` | `0x2590` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0x1960` | `0x19b8` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0x1478` | `0x149c` | **`+0x24`** |
| `__TEXT.__swift5_fieldmd` | `0x180c` | `0x1828` | **`+0x1c`** |
| `__TEXT.__swift5_proto` | `0x5e0` | `0x5ec` | **`+0xc`** |
| `__TEXT.__swift5_reflstr` | `0x14cf` | `0x14c8` | **`-0x7`** |
| `__TEXT.__swift5_types` | `0x1a4` | `0x1a8` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x154` | `0x158` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-3600.33.17.0.0
+3605.20.1.0.0

+  - /System/Library/PrivateFrameworks/SiriAudioSupport.framework/SiriAudioSupport

-  Functions: 1692
+  Functions: 1720

-  CStrings:  322
+  CStrings:  340
Symbols:
+ _swift_release_x14
- _objc_retain_x27
CStrings:
+ "No PlayAudioIntent found on the client device for bundleId "
+ "PlayAudioAppIntentExecutionStrategy.makeDeviceTargetedInvocation() - no PlayAudioIntent on device %{private}s for home-speaker origin (deviceIdiom=%{public}s); refusing to fall back to local to avoid leaking playback onto the companion"
+ "PlayAudioAppIntentExecutionStrategy.remapPlaybackAttributes() - remapped collection element type to %s"
+ "PlayAudioAppIntentExecutionStrategy.remapQueueLocation() - remapped enum type to %{public}s"
+ "PlayAudioAppIntentExecutionStrategy.warmupAudioQueueIntent() - attributed %{public}s to the remote target"
+ "PlayAudioAppIntentExecutionStrategy.warmupAudioQueueIntent() - resolving warmup tool on client device %{private}s"
+ "PlayAudioAppIntentExecutionStrategy.warmupAudioQueueIntent() - skipping warmup: invocation targets %{public}s but the request came from %{private}s. Warmup must run on the requesting device."
+ "PlayAudioAppIntentExecutionStrategy.warmupTargetsRequestingDevice() - unknown target device kind %{public}s; refusing to warm"
+ "RemoteParameterAttribution.attributed() - %{public}s → %{public}s"
+ "RemoteParameterAttribution.attributingParameters() - parameter '%{public}s' is an un-attributed collection; it needs a schema-resolved target type (see findMatchingTargetType), not this helper"
+ "RemoteParameterAttribution.attributingParameters() - re-homed parameter '%{public}s' onto %{public}s"
+ "RemoteParameterAttribution.reducingToStableIdentifier() - %{public}s → %{public}s for remote resolution"
+ "WholeHouseAudioService.createSpeakerConnectionInvocation() - %{public}ld destination(s), element type %{public}s"
+ "WholeHouseAudioService.declaredDestinationsElementType() - '%s' is not device-attributed on %s; using the local type"
+ "WholeHouseAudioService.declaredDestinationsElementType() - tool definition %s declares no '%s' parameter"
+ "WholeHouseAudioService.declaredDestinationsElementType() - using declared type %s"
+ "home speaker originated request; refusing to fall back to the companion to avoid "
+ "leaking playback onto it"
```
