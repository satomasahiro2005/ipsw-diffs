## usbaudiod

> `/System/Library/Audio/Plug-Ins/usbaudio.bundle/usbaudiod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x102f2c` | `0x105518` | **`+0x25ec`** |
| `__DATA.__bss` | `0x11fe0` | `0x120e0` | **`+0x100`** |
| `__TEXT.__const` | `0xc9c2` | `0xca62` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0xe1c8` | `0xe258` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0x1c00` | `0x1c90` | **`+0x90`** |
| `__TEXT.__cstring` | `0x70d2` | `0x7152` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x56a6` | `0x5706` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x6a84` | `0x6ad0` | **`+0x4c`** |
| `__DATA_CONST.__auth_got` | `0xe10` | `0xe58` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x2e82` | `0x2ebc` | **`+0x3a`** |
| `__TEXT.__eh_frame` | `0x5c50` | `0x5c88` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x35d8` | `0x3608` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x5518` | `0x553c` | **`+0x24`** |
| `__DATA.__data` | `0x5e08` | `0x5e28` | **`+0x20`** |
| `__DATA.__objc_data` | `0x2540` | `0x2558` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x9b4` | `0x9bc` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x54c` | `0x550` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-901.44.0.0.0
+901.48.0.0.0

-  Functions: 5077
-  Symbols:   712
-  CStrings:  1402
+  Functions: 5099
+  Symbols:   721
+  CStrings:  1405
Symbols:
+ _$sSJ8isNumberSbvg
+ _$sSS17UnicodeScalarViewV13_foreignIndex5afterSS0E0VAF_tF
+ _$sSS8UTF8ViewV13_foreignIndex_8offsetBySS0D0VAF_SitF
+ _$sSS9UTF16ViewV5index_8offsetBySS5IndexVAF_SitF
+ _$sSS9hasPrefixySbSSF
+ _$sSs5index5afterSS5IndexVAD_tF
+ _$sSsySJSS5IndexVcig
+ _$ss11_StringGutsV18foreignScalarAlignySS5IndexVAEF
+ _$ss11_StringGutsV27foreignErrorCorrectedScalar10startingAts7UnicodeO0F0V_Si12scalarLengthtSS5IndexV_tF
+ _objc_release_x14
- _objc_release_x13
CStrings:
+ ": channel count is 0"
+ "channelName lookup via "
+ "channelNameForChannelIndex: no cluster (terminalKind="
+ "skipping format for altSetting "
- "channelNameForChannelIndex"
```
