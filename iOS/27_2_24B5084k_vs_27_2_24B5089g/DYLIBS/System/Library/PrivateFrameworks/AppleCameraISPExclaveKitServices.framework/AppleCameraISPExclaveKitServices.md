## AppleCameraISPExclaveKitServices

> `/System/Library/PrivateFrameworks/AppleCameraISPExclaveKitServices.framework/AppleCameraISPExclaveKitServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x32b94` | `0x32ca4` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x442e` | `0x44fe` | **`+0xd0`** |
| `__TEXT.__gcc_except_tab` | `0x928` | `0x934` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x588` | `0x590` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-20.104.4.0.0
+20.105.6.0.0

-  Symbols:   782
-  CStrings:  824
+  Symbols:   783
+  CStrings:  828
Symbols:
+ _usleep
CStrings:
+ "%s:%d - after calling off IDL (attempt %u)\n"
+ "%s:%d - before calling off IDL (attempt %u)\n"
+ "%s:%d - cmd[0x%x]: HW OutstandingRequestCount not drained after %u ms\n"
+ "%s:%d - cmd[0x%x]: HW drained after %u retries\n"
+ "v24@?0{applecamera_ispexclavekitshared_ekstreamingcontrol_off__result_s=C(?={applecamera_exclavesispshared_exclavesisperror_s=Q}B)}8"
- "v24@?0{applecamera_ispexclavekitshared_ekstreamingcontrol_off__result_s=C(?={applecamera_exclavesispshared_exclavesisperror_s=Q})}8"
```
