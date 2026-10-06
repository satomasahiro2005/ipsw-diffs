## BTAudioHALPlugin

> `/System/Library/Audio/Plug-Ins/HAL/BTAudioHALPlugin.driver/BTAudioHALPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7dbf0` | `0x7dc0c` | **`+0x1c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ sub_1a82c : 84 -> 88
~ sub_1ac88 -> sub_1ac8c : 84 -> 88
~ sub_3d814 -> sub_3d81c : 648 -> 652
~ _butterfly5last : 500 -> 508
~ _hfft_run : 304 -> 324
~ _g722_decode_frame : 1220 -> 1208
```
