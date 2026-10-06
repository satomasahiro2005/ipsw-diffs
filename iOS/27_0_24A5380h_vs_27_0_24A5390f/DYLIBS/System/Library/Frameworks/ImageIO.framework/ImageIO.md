## ImageIO

> `/System/Library/Frameworks/ImageIO.framework/ImageIO`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4fd300` | `0x4fdcb8` | **`+0x9b8`** |
| `__TEXT.__swift5_fieldmd` | `0x7958` | `0x79f4` | **`+0x9c`** |
| `__TEXT.__const` | `0x494a0` | `0x49530` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x4f45` | `0x4fb5` | **`+0x70`** |
| `__TEXT.__cstring` | `0xa5f9e` | `0xa5f3e` | **`-0x60`** |
| `__TEXT.__swift5_typeref` | `0x3cb0` | `0x3c68` | **`-0x48`** |
| `__DATA.__data` | `0x64e0` | `0x64b0` | **`-0x30`** |
| `__AUTH_CONST.__const` | `0x4eea0` | `0x4ee80` | **`-0x20`** |
| `__DATA_CONST.__got` | `0xab0` | `0xaa8` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xb50` | `0xb48` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0x22844` | `0x2284c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x13660` | `0x13668` | **`+0x8`** |

### Other Changes

```diff

-2846.0.0.0.0
+2847.1.0.0.0

-  Functions: 22998
-  Symbols:   24341
+  Functions: 23003
+  Symbols:   24337
Symbols:
+ _CFUUIDCreateFromUUIDBytes
- _OBJC_CLASS_$_NSUUID
- _symbolic Ss_SuSgAAt
- _symbolic _____ySs_SuSgABtG 17_StringProcessing5RegexV
- _symbolic _____ySs_SuSgABt_G 17_StringProcessing5RegexV5MatchV
- _symbolic _____ySs_SuSgABt_GSg 17_StringProcessing5RegexV5MatchV
CStrings:
+ "'%s' is saving an opaque image (%dx%d) with '%s' --> ignoring alpha to avoid an unnecessary alpha plane.\n"
+ "✳️  %s '%c%c%c%c' [%ldx%ld]: imgHeadroom: %g   csHeadroom: %g   isImageSpecific: %d   isHDR: %d   isEDR: %d   decodeToSDR: %d   decodeToHDR: %d   cs: %s\n"
- "✳️  %s '%c%c%c%c' [%ldx%ld]: imgHeadroom: %g   csHeadroom: %g   hasFlexGTC: %d   isHDR: %d   isEDR: %d   decodeToSDR: %d   decodeToHDR: %d   cs: %s\n"
- "⭕️ ERROR: '%s' is trying to save an opaque image (%dx%d) with '%s'. This would unnecessarily increase the file size and will double (!!!) the required memory when decoding the image --> ignoring alpha.\n "
```
