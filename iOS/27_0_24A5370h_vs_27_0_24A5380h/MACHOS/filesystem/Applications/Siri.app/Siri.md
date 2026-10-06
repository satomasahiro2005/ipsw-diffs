## Siri

> `/Applications/Siri.app/Siri`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xeee1c` | `0xefca8` | **`+0xe8c`** |
| `__TEXT.__const` | `0x2f84` | `0x30b4` | **`+0x130`** |
| `__DATA.__bss` | `0x1fe0` | `0x2100` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0xd6b4` | `0xd774` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x2b51f` | `0x2b5cf` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x242d0` | `0x24370` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x4c68` | `0x4cf8` | **`+0x90`** |
| `__TEXT.__objc_methtype` | `0xaec1` | `0xaf31` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x38a0` | `0x3910` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0xe2a0` | `0xe308` | **`+0x68`** |
| `__DATA_CONST.__cfstring` | `0x3320` | `0x3380` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x1967` | `0x19c7` | **`+0x60`** |
| `__DATA.__objc_const` | `0x10b60` | `0x10bb8` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x1264` | `0x12bc` | **`+0x58`** |
| `__DATA_CONST.__got` | `0x1808` | `0x1858` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x1b420` | `0x1b460` | **`+0x40`** |
| `__DATA.__data` | `0x4738` | `0x4768` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x2ff0` | `0x3020` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0xbe0` | `0xc08` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x1394` | `0x13bc` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x24cc` | `0x24e8` | **`+0x1c`** |
| `__DATA_CONST.__auth_got` | `0x1808` | `0x1820` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x8f98` | `0x8fa8` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x2606` | `0x2616` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x8f8` | `0x900` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x13c` | `0x144` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x114` | `0x118` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.55.10.0.0
+3600.55.26.0.0

-  Functions: 5157
-  Symbols:   1858
-  CStrings:  8993
+  Functions: 5192
+  Symbols:   1861
+  CStrings:  9005
Symbols:
+ _$s7SwiftUI6_GlassV10subvariantyACSSSgF
+ _$s7SwiftUI6_GlassV13ContentEffectV5lenseAEvgZ
+ _$s7SwiftUI6_GlassV13ContentEffectVMa
+ _$s7SwiftUI6_GlassV13ContentEffectVMn
+ _$s7SwiftUI6_GlassV13contentEffectyA2C07ContentE0VSgF
- _AFIsLinwoodEnabledAndAvailable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "%s #ccc Entering conversation mode (reason: %{public}@)"
+ "%s #ccc Not exiting conversation mode — currently attending"
+ "%s #ccc _enterConversationMode _isConversationModeActive: %d, isCarplayConversationModeEnabled: %d, reason: %{public}@"
+ "%s #tts-streamer didDetectFollowUp (streamId=%@)"
+ "-[SRSiriViewController _enterConversationModeWithReason:]"
+ "-[SRSiriViewController _exitConversationMode]_block_invoke"
+ "-[SRSiriViewController siriSpeakableStreamerWrapper:didDetectFollowUpForStreamId:]"
+ "_enableLensing"
+ "_enterConversationModeWithReason:"
+ "_glassSubvariant"
+ "carPlayConversationRequest"
+ "siriSpeakableStreamerWrapper:didDetectFollowUpForStreamId:"
+ "speakableStreamerDidDetectFollowUp:"
+ "streamChunkThreshold"
+ "unknown"
+ "v24@0:8@\"_TtC13AgentCanvasUI17SpeakableStreamer\"16"
+ "v32@0:8@\"SRSpeakableStreamerWrapper\"16@\"NSString\"24"
- "%s #ccc Clearing conversation mode — request cancelled"
- "%s #ccc Entering conversation mode"
- "-[SRSiriViewController _enterConversationMode]"
- "-[SRSiriViewController siriSessionWillCancelRequest]"
- "_enterConversationMode"
```
