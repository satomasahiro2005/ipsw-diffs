## CoreDuet

> `/System/Library/PrivateFrameworks/CoreDuet.framework/CoreDuet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1901a0` | `0x1904f4` | **`+0x354`** |
| `__AUTH.__objc_data` | `0x5050` | `0x4f38` | **`-0x118`** |
| `__DATA_DIRTY.__objc_data` | `0x2940` | `0x2a58` | **`+0x118`** |
| `__TEXT.__cstring` | `0x15d57` | `0x15d8f` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x73e0` | `0x7408` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x12d40` | `0x12d60` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x8088` | `0x80a8` | **`+0x20`** |
| `__TEXT.__const` | `0x5b8` | `0x5d0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xa78` | `0xa80` | **`+0x8`** |
| `__DATA.__bss` | `0xd70` | `0xd68` | **`-0x8`** |
| `__DATA_DIRTY.__bss` | `0x220` | `0x228` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x54a8` | `0x54b0` | **`+0x8`** |

### Other Changes

```diff

-1975.0.0.0.0
+1976.0.0.0.0

-  Symbols:   13369
-  CStrings:  4655
+  Symbols:   13371
+  CStrings:  4656
Symbols:
+ _CFStringNormalize
+ __CDNonASCIIDigitRangeStarts
+ __CDStringByConvertingPhoneNumberStringToASCII
+ ___block_descriptor_136_e8_32s40s48s56s64s72s80r88r96r104r112r120r_e5_v8?0ls32l8r80l8r88l8s40l8s48l8s56l8r96l8s64l8s72l8r104l8r112l8r120l8
- __CDConvertPhoneNumberStringToASCII
- ___block_descriptor_120_e8_32s40s48s56s64s72r80r88r96r_e5_v8?0ls32l8s40l8s48l8s56l8r72l8s64l8r80l8r88l8r96l8
CStrings:
+ "creationDate > %@ OR (creationDate == %@ AND uuid > %@)"
```
