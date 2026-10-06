## CoreGPSTest.dylib

> `/System/Library/PrivateFrameworks/CoreGPSTest.framework/CoreGPSTest.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x60904` | `0x60a34` | **`+0x130`** |
| `__TEXT.__oslogstring` | `0x9fef` | `0xa031` | **`+0x42`** |
| `__AUTH_CONST.__cfstring` | `0x13a0` | `0x13c0` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x4fa8` | `0x4fc8` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x35a0` | `0x35b8` | **`+0x18`** |
| `__TEXT.__cstring` | `0x50d0` | `0x50e2` | **`+0x12`** |
| `__DATA.__bss` | `0x250` | `0x260` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x25b8` | `0x25c8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xba8` | `0xbb0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x298` | `0x2a0` | **`+0x8`** |

### Other Changes

```diff

-365.0.5.0.0
+365.0.6.0.0

-  Functions: 2571
-  Symbols:   4168
-  CStrings:  1322
+  Functions: 2572
+  Symbols:   4169
+  CStrings:  1324
Symbols:
+ __ZNK15GpsdPreferences17acLongitudeOffsetEv
+ ____ZNK15GpsdPreferences17acLongitudeOffsetEv_block_invoke
+ _objc_opt_isKindOfClass
- _$s9Tightbeam0A7EncoderVSgWOh
- __ZL9fDefaults
CStrings:
+ "#gdm,ACLongitudeOffset,applied,%{public}.6f,trackAge,%{public}.3f"
+ "#version,CoreGPS-365.0.6,machContSec,%{public}.3f,BuildTime,{Jun 30 2026,21:07:20}"
+ "21:10:40"
+ "ACLongitudeOffset"
+ "Jun 30 2026"
- "#version,CoreGPS-365.0.5,machContSec,%{public}.3f,BuildTime,{Jun 18 2026,19:48:09}"
- "19:51:04"
- "Jun 18 2026"
```
