## appleh16camerad

> `/usr/libexec/appleh16camerad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x84480` | `0x845ac` | **`+0x12c`** |
| `__TEXT.__unwind_info` | `0x1528` | `0x1580` | **`+0x58`** |
| `__TEXT.__gcc_except_tab` | `0x2098` | `0x20e8` | **`+0x50`** |
| `__TEXT.__cstring` | `0x8ac3` | `0x8afe` | **`+0x3b`** |
| `__TEXT.__objc_methtype` | `0x10b3` | `0x10e5` | **`+0x32`** |
| `__TEXT.__oslogstring` | `0x5e1e` | `0x5e43` | **`+0x25`** |
| `__DATA.__objc_const` | `0x5a8` | `0x5c8` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1582` | `0x1590` | **`+0xe`** |
| `__DATA_CONST.__const` | `0xb6c8` | `0xb6d0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x268` | `0x270` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x34` | `0x38` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-6.10.3.0.0
+6.12.2.0.0

-  Functions: 1690
+  Functions: 1692

-  CStrings:  2025
+  CStrings:  2029
CStrings:
+ "/usr/local/share/firmware/isp/dcs_v5x_isp_fw.bin"
+ "6.12.2"
+ "<UNKNOWN>"
+ "FlickerDetector: ArbiterClient grant arrived after cleanup, releasing resource\n\n"
+ "_contextMutex"
+ "{_opaque_pthread_mutex_t=\"__sig\"q\"__opaque\"[56c]}"
- "6.10.3"
- "StopAudioCaptureSession: invalid context \n\n"
```
