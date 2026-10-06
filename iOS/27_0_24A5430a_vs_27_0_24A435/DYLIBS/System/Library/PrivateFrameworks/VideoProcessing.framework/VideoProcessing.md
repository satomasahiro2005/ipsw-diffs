## VideoProcessing

> `/System/Library/PrivateFrameworks/VideoProcessing.framework/VideoProcessing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d819c` | `0x1d9cc4` | **`+0x1b28`** |
| `__TEXT.__oslogstring` | `0xa855` | `0xa992` | **`+0x13d`** |
| `__AUTH_CONST.__cfstring` | `0x5100` | `0x5140` | **`+0x40`** |
| `__TEXT.__cstring` | `0x7b6a` | `0x7ba8` | **`+0x3e`** |
| `__TEXT.__eh_frame` | `0x568` | `0x530` | **`-0x38`** |
| `__TEXT.__unwind_info` | `0x2c88` | `0x2c98` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1108` | `0x1110` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x5abc` | `0x5ab8` | **`-0x4`** |

### Other Changes

```diff

-  Functions: 3361
-  Symbols:   1314
-  CStrings:  2102
+  Functions: 3362
+  Symbols:   1315
+  CStrings:  2111
Symbols:
+ _IORegistryEntryGetName
CStrings:
+ "IOPlatformExpertDevice"
+ "VCPEnc %p (%dx%d, %s): Got 10b input and set HDRMetadataInsertionMode_Auto/HEVC_Main10_AutoLevel/bitdepth10\n"
+ "VCPEnc %p (%dx%d, %s): Got 10b input and set HDRMetadataInsertionMode_Auto/HEVC_Main44410_AutoLevel/bitdepth10\n"
+ "VCPEnc %p (%dx%d, %s): Got 8b 444 input and set HEVC_Main444_AutoLevel\n"
+ "VCPEnc: Detected H18 A0"
+ "arm-io"
+ "chip-revision"
+ "device_type"
+ "t8150"
```
