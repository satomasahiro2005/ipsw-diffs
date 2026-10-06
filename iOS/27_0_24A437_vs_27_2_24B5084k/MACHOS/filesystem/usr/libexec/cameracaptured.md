## cameracaptured

> `/usr/libexec/cameracaptured`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x163` | `0x254` | **`+0xf1`** |
| `__TEXT.__text` | `0x628` | `0x700` | **`+0xd8`** |
| `__TEXT.__auth_stubs` | `0x2a0` | `0x2d0` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x160` | `0x178` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x60` | `0x74` | **`+0x14`** |
| `__TEXT.__const` | `0x2c` | `0x34` | **`+0x8`** |
| `__TEXT.__cstring` | `0x71` | `0x76` | **`+0x5`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-764.22.13.0.0
+764.40.4.122.1

-  Symbols:   56
-  CStrings:  18
+  Symbols:   59
+  CStrings:  20
Symbols:
+ __os_log_send_and_compose_impl
+ _fig_log_call_emit_and_clean_up_after_send_and_compose
+ _fig_log_emitter_get_os_log_and_send_and_compose_flags_and_os_log_type
Functions:
~ sub_100000ad0 : 1264 -> 1480
CStrings:
+ "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/CameraCapture/CMCapture/Sources/cameracaptured/Resources-Embedded/cameracaptured.m %s: cannot listen for language changed notification (%d)"
+ "main"
```
