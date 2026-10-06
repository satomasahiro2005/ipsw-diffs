## VirtualAudio

> `/Library/Audio/Plug-Ins/HAL/VirtualAudio.plugin/VirtualAudio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x558b6c` | `0x5598b0` | **`+0xd44`** |
| `__TEXT.__gcc_except_tab` | `0x65c2c` | `0x65d4c` | **`+0x120`** |
| `__DATA.__bss` | `0x25e60` | `0x25f40` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x58deb` | `0x58e77` | **`+0x8c`** |
| `__TEXT.__unwind_info` | `0x14fd8` | `0x14ff0` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
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

-1451.209.0.0.0
+1451.212.0.0.0

-  Functions: 12531
+  Functions: 12532

-  CStrings:  12326
+  CStrings:  12328
CStrings:
+ "%25s:%-5d Bluetooth device expired, not handling PME update."
+ "%25s:%-5d Registering for PME updates for bluetooth audio device with UID \"%s\""
+ "@@ Strips Sep 29 2026 20:52:07"
- "@@ Strips Sep 12 2026 08:23:41"
```
