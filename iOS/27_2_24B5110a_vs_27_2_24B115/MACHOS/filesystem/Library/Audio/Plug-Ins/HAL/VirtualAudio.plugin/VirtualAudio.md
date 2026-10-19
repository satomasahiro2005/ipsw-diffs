## VirtualAudio

> `/Library/Audio/Plug-Ins/HAL/VirtualAudio.plugin/VirtualAudio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55b31c` | `0x55dec4` | **`+0x2ba8`** |
| `__DATA.__bss` | `0x26310` | `0x269b0` | **`+0x6a0`** |
| `__TEXT.__gcc_except_tab` | `0x65f24` | `0x661cc` | **`+0x2a8`** |
| `__TEXT.__cstring` | `0x3785d` | `0x37a3a` | **`+0x1dd`** |
| `__TEXT.__oslogstring` | `0x58e77` | `0x58fb2` | **`+0x13b`** |
| `__TEXT.__unwind_info` | `0x15018` | `0x15030` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x29728` | `0x29738` | **`+0x10`** |
| `__TEXT.__const` | `0xb4920` | `0xb4930` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__dof_Aggregate`
- `__TEXT.__dof_VirtualA0`
- `__TEXT.__dof_VirtualAu`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 12538
+  Functions: 12546

-  CStrings:  12340
+  CStrings:  12363
CStrings:
+ "%25s:%-5d HomePod is a rear speaker of a surround group? %s"
+ "%25s:%-5d HomePod is in a surround sound role? %s"
+ "%25s:%-5d HomePod is in party rendering mode? %s"
+ "%25s:%-5d Homepod surround state changed from %u to %u. Queueing internal update"
+ "%25s:%-5d Setting rear trim to %f for device %s, rear surround speaker? %s"
+ ", group compositions: "
+ ", rendering mode: "
+ ", spatialize stereo: "
+ "@@ Strips Oct  3 2026 19:41:58"
+ "group composition"
+ "groupComposition"
+ "groupRenderingMode"
+ "home_theater_surround"
+ "rendering mode"
+ "spatialize stereo"
+ "speaker_multichannel_surround_lowlatency"
+ "speaker_multichannel_surround_movie"
+ "speaker_multichannel_surround_music"
+ "speaker_stereo_surround_lowlatency"
+ "speaker_stereo_surround_movie"
+ "speaker_stereo_surround_music"
+ "speaker_stereo_surround_spoken_word"
+ "surroundCalibrationBandGains"
+ "surroundCalibrationGain"
- "@@ Strips Oct  4 2026 01:16:47"
```
