## VirtualAudio

> `/Library/Audio/Plug-Ins/HAL/VirtualAudio.plugin/VirtualAudio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5598b0` | `0x55b31c` | **`+0x1a6c`** |
| `__DATA.__bss` | `0x25f40` | `0x26310` | **`+0x3d0`** |
| `__TEXT.__gcc_except_tab` | `0x65d4c` | `0x65f24` | **`+0x1d8`** |
| `__TEXT.__cstring` | `0x37739` | `0x3785d` | **`+0x124`** |
| `__TEXT.__realtime` | `0x14c60` | `0x14c88` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x14ff0` | `0x15018` | **`+0x28`** |
| `__TEXT.__const` | `0xb4910` | `0xb4920` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
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

-  Functions: 12532
+  Functions: 12538

-  CStrings:  12328
+  CStrings:  12340
CStrings:
+ "@@ Strips Oct  4 2026 01:16:47"
+ "Precondition failure: concreteDefaultRoutePtr != NULL"
+ "SiriUI"
+ "basePowerParameterID"
+ "bspw"
+ "hdpw First Channel"
+ "hdpw Second Channel"
+ "headPower1ParameterID"
+ "headPower2ParameterID"
+ "hearables_disable_activation_audio_output_only"
+ "hspw"
+ "j490_ml_based_enhance_dialogue"
+ "ml_based_enhance_dialogue"
- "@@ Strips Sep 29 2026 20:52:07"
```
