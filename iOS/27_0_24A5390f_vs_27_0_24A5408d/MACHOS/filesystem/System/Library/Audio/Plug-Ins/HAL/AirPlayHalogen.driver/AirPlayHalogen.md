## AirPlayHalogen

> `/System/Library/Audio/Plug-Ins/HAL/AirPlayHalogen.driver/AirPlayHalogen`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xecd0` | `0xe7fc` | **`-0x4d4`** |
| `__TEXT.__cstring` | `0x3468` | `0x3182` | **`-0x2e6`** |
| `__TEXT.__oslogstring` | `0xb6` | `0x4b` | **`-0x6b`** |
| `__TEXT.__auth_stubs` | `0x970` | `0x930` | **`-0x40`** |
| `__DATA_CONST.__auth_got` | `0x4b8` | `0x498` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x320` | `0x308` | **`-0x18`** |
| `__DATA.__common` | `0x10` | `—` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`

### Other Changes

```diff

-980.71.1.0.0
+980.75.1.0.0

-  Functions: 320
-  Symbols:   218
-  CStrings:  266
+  Functions: 316
+  Symbols:   214
+  CStrings:  241
Symbols:
+ _FigSignalErrorAtGM
- _FigSignalErrorAt3
- __os_log_send_and_compose_impl
- _fig_log_call_emit_and_clean_up_after_send_and_compose
- _fig_log_emitter_get_os_log_and_send_and_compose_flags_and_os_log_type
- _os_log_type_enabled
CStrings:
+ "%s signalled err=%d at <>:%d"
- "%s%s%s signalled err=%d (%s) (%s) at %s:%d"
- "APHALAudioControl.c"
- "APHALAudioDevice.c"
- "APHALAudioStream.c"
- "APHALHandoffAudioControl.c"
- "APHALHandoffAudioDevice.c"
- "APHALHandoffAudioStream.c"
- "AirPlayHALPluginFactory %s: apPlugin_InstantiateAirPlayEndpointManager: APGetEndpointManager returned [%p]"
- "Could not allocate APHALAudioSharedState"
- "Could not allocate APHALHandoffAudioSharedState"
- "Could not allocate volumeContextRef"
- "Device was unplugged"
- "EndpointStream has NULL ID"
- "Expecting WriteMix operation"
- "Failed to create notification queue"
- "NULL changeRecord"
- "Need at least one supported PCM format from endpointStream"
- "No AudioEngine"
- "Unknown change action"
- "kAudioHardwareBadDeviceError"
- "kAudioHardwareBadObjectError"
- "kAudioHardwareIllegalOperationError"
- "kAudioHardwareUnsupportedOperationError"
- "kCMBaseObjectError_AllocationFailed"
- "kCMBaseObjectError_ParamErr"
- "kFigEndpointStreamError_InvalidParameter"
```
