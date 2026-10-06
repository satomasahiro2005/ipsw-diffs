## FontServices

> `/System/Library/PrivateFrameworks/FontServices.framework/FontServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbf90` | `0xc330` | **`+0x3a0`** |
| `__TEXT.__cstring` | `0x1a2e` | `0x1a5b` | **`+0x2d`** |
| `__AUTH_CONST.__cfstring` | `0xe60` | `0xe80` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x8e8` | `0x900` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x6c8` | `0x6d4` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x5f0` | `0x5f8` | **`+0x8`** |

### Other Changes

```diff

-168.0.0.0.0
+169.0.0.0.0

-  Functions: 354
-  Symbols:   846
-  CStrings:  186
+  Functions: 355
+  Symbols:   850
+  CStrings:  188
Symbols:
+ _GSFontCopyLocallyActivatedFontsInfo
+ _GSFontRegisterLocallyActivatedFontsInfo
+ _GSFontUnregisterLocallyActivatedURL
+ _LocallyActivatedFontsInfoWithSandboxExtensions
+ ___block_descriptor_32_e39_v32?0"NSString"8"NSDictionary"16^B24l
+ ___block_descriptor_40_e8_32s_e39_v32?0"NSString"8"NSDictionary"16^B24ls32l8
+ _objc_retain_x28
- _GSFontUnregisterURL2
- ___block_descriptor_32_e33_v32?0"NSString"8"NSData"16^B24l
- ___block_descriptor_40_e8_32s_e33_v32?0"NSString"8"NSData"16^B24ls32l8
CStrings:
+ "data"
+ "v32@?0@\"NSString\"8@\"NSDictionary\"16^B24"
```
