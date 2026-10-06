## CCPortrait

> `/System/Library/VideoProcessors/CCPortrait.bundle/CCPortrait`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x412bc` | `0x415e0` | **`+0x324`** |
| `__AUTH_CONST.__cfstring` | `0x6020` | `0x60c0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x93ae` | `0x941e` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x2ff4` | `0x302c` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x5700` | `0x5730` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x1fd8` | `0x2000` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x2a0` | `0x2b8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x9e8` | `0xa00` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x628` | `0x638` | **`+0x10`** |
| `__DATA.__bss` | `0xf8` | `0x108` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x108` | `0xf8` | **`-0x10`** |
| `__TEXT.__gcc_except_tab` | `0x91c` | `0x928` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x3f8` | `0x400` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3f4` | `0x3f8` | **`+0x4`** |

### Other Changes

```diff

-758.0.0.122.2
+761.0.0.0.3

+  - /System/Library/PrivateFrameworks/CMCapture.framework/CMCapture

-  Functions: 1432
-  Symbols:   439
-  CStrings:  1345
+  Functions: 1437
+  Symbols:   445
+  CStrings:  1350
Symbols:
+ _OBJC_CLASS_$_CMInferenceUtils
+ _e5rt_precompiled_compute_op_create_options_set_anef_intermediate_buffer_size_hint
+ _espresso_network_bind_cvpixelbuffer
+ _kEspressoInferenceDeviceANE
+ _kEspressoInferenceDeviceCPU
+ _kEspressoInferenceDeviceGPU
+ _qos_class_self
- _e5rt_precompiled_compute_op_create_options_set_iosurface_memory_pool_id
CStrings:
+ "%@|%@"
+ "1x - ANEDriver intermediate buffer(BSS) size hint"
+ "2x - ANEDriver intermediate buffer(BSS) size hint"
+ "ANE"
+ "CPU"
+ "GPU"
+ "Warning - Failed to set ANEF intermediate buffer size hint"
- "  - Memory pool ID: %llu\n"
- "Warning - Failed to set memory pool ID"
```
