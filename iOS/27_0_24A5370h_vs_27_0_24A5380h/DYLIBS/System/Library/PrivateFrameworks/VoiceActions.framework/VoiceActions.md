## VoiceActions

> `/System/Library/PrivateFrameworks/VoiceActions.framework/VoiceActions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18957c` | `0x18a814` | **`+0x1298`** |
| `__TEXT.__const` | `0xc8f0` | `0xca40` | **`+0x150`** |
| `__DATA.__bss` | `0x107d0` | `0x108d0` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x41be` | `0x429e` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x683d` | `0x690d` | **`+0xd0`** |
| `__TEXT.__eh_frame` | `0xd14c` | `0xd1ec` | **`+0xa0`** |
| `__TEXT.__swift5_reflstr` | `0x5cad` | `0x5d4d` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x13890` | `0x13920` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x5990` | `0x59dc` | **`+0x4c`** |
| `__DATA_CONST.__got` | `0xa08` | `0xa28` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x6210` | `0x6230` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x94c0` | `0x94dc` | **`+0x1c`** |
| `__TEXT.__swift5_typeref` | `0x2a7c` | `0x2a94` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0xdc` | `0xf0` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x1940` | `0x1948` | **`+0x8`** |
| `__DATA.__data` | `0x1e08` | `0x1e10` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0x24` | `0x2c` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x85c` | `0x864` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x52c` | `0x534` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x50c` | `0x510` | **`+0x4`** |

### Other Changes

```diff

-96.0.0.0.0
+97.0.0.0.0

-  Functions: 7512
-  Symbols:   559
-  CStrings:  1160
+  Functions: 7527
+  Symbols:   561
+  CStrings:  1169
Symbols:
+ _mach_task_self_
+ _vm_region_64
CStrings:
+ " mNumberChannels="
+ "Failed to allocate copy buffer for "
+ "Rejecting unsafe audio buffer in VAfp16AVAudioBufferToFP32Array: %s"
+ "VANRSpotterBridge.addAudio rejecting unsafe buffer at VoiceActions entry point: %s"
+ "VAfp16AVAudioBufferToFP32Array converting %s"
+ "backingMemoryUnreadable: "
+ "frameLengthAbsurd: "
+ "frameLengthExceedsCapacity: "
+ "mDataByteSizeTooSmall: "
+ "noInt16ChannelData: "
- "Error adding audio"
```
