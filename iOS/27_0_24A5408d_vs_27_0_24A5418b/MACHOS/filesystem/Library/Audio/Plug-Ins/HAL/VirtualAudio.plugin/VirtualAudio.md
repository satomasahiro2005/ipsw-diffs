## VirtualAudio

> `/Library/Audio/Plug-Ins/HAL/VirtualAudio.plugin/VirtualAudio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x52ee30` | `0x530ae8` | **`+0x1cb8`** |
| `__TEXT.__gcc_except_tab` | `0x5f90c` | `0x5fbb0` | **`+0x2a4`** |
| `__TEXT.__oslogstring` | `0x56a41` | `0x56cb8` | **`+0x277`** |
| `__DATA_CONST.__const` | `0x28c80` | `0x28d10` | **`+0x90`** |
| `__TEXT.__cstring` | `0x36b5e` | `0x36bce` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x14430` | `0x14480` | **`+0x50`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
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

-1451.115.0.0.0
+1451.115.30.0.0

-  Functions: 12158
+  Functions: 12180

-  CStrings:  12105
+  CStrings:  12114
CStrings:
+ "%25s:%-5d EXCEPTION (GetCurrentFormat(streamFormat, kAudioStreamPropertyPhysicalFormat)) [error GetCurrentFormat(streamFormat, kAudioStreamPropertyPhysicalFormat) is an error]: \"error getting current stream format\""
+ "%25s:%-5d Route change failed: device %u (%s) is left with nominal sample rate %.0f."
+ "%25s:%-5d Route change failed: publishing property changes accumulated before the failure: %s."
+ "%25s:%-5d Route change failed: restoring dependent sample rate %u on device %u."
+ "%25s:%-5d Route change failed: restoring nominal sample rate %.0f on device %u."
+ "%25s:%-5d Untrustworthy stream %s could not supply its physical format; %s."
+ "@@ Strips Aug  9 2026 03:26:56"
+ "] "
+ "assuming it is not an Atmos stream"
+ "using a neutral latency scale factor"
- "@@ Strips Aug  4 2026 11:01:42"
```
