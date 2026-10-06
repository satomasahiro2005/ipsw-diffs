## CarPlayHalogen

> `/System/Library/Audio/Plug-Ins/HAL/CarPlayHalogen.driver/CarPlayHalogen`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x747c` | `0x7324` | **`-0x158`** |
| `__TEXT.__cstring` | `0x132a` | `0x12c5` | **`-0x65`** |
| `__TEXT.__auth_stubs` | `0x5b0` | `0x560` | **`-0x50`** |
| `__TEXT.__oslogstring` | `0x93` | `0x52` | **`-0x41`** |
| `__DATA_CONST.__auth_got` | `0x2d8` | `0x2b0` | **`-0x28`** |
| `__DATA.__common` | `0x10` | `—` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x118` | `0x110` | **`-0x8`** |
| `__TEXT.__const` | `0x90` | `0x88` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1005.8.1.0.0
+1005.12.1.0.0

-  Symbols:   131
-  CStrings:  111
+  Symbols:   125
+  CStrings:  107
Symbols:
+ _FigSignalErrorAtGM
- _FigSignalErrorAt3
- ___stack_chk_fail
- ___stack_chk_guard
- __os_log_send_and_compose_impl
- _fig_log_call_emit_and_clean_up_after_send_and_compose
- _fig_log_emitter_get_os_log_and_send_and_compose_flags_and_os_log_type
- _os_log_type_enabled
Functions:
~ sub_683c -> sub_67ec : 424 -> 384
~ sub_6af0 -> sub_6a78 : 396 -> 92
CStrings:
+ "%s signalled err=%d at <>:%d"
- "%s%s%s signalled err=%d (%s) (%s) at %s:%d"
- "APHALCarAudioStream.c"
- "CarPlayHALPluginFactory %s: CarPlayEndpointManagerCarPlay = [%p]"
- "Unknown config change action"
- "kAudioHardwareIllegalOperationError"
```
