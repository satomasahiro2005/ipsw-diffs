## visionhwserverd

> `/usr/libexec/visionhwserverd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4d8` | `0x5c0` | **`+0xe8`** |
| `__TEXT.__oslogstring` | `0xb8` | `0x11a` | **`+0x62`** |
| `__TEXT.__gcc_except_tab` | `0x74` | `0x90` | **`+0x1c`** |
| `__TEXT.__auth_stubs` | `0x1b0` | `0x1a0` | **`-0x10`** |
| `__TEXT.__cstring` | `0xd4` | `0xc5` | **`-0xf`** |
| `__DATA_CONST.__auth_got` | `0xe8` | `0xe0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4.4.10.0.0
+4.4.12.0.0

-  Functions: 6
-  Symbols:   38
+  Functions: 7
+  Symbols:   37
Symbols:
- __os_feature_enabled_impl
Functions:
~ sub_1000032f8 : 1016 -> 1164
+ sub_100003824
CStrings:
+ "Loading VisionHWAccelerationServices.framework..."
+ "Now launching the VisionHWAccelerationServices XPC service framework"
+ "VisionHWServerStop"
- "AppleCVHWA"
- "VisionHWA XPCService"
- "enable_visionhwserverd"
```
