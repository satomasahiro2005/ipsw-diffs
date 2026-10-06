## CoreSpeechExclave

> `/System/Library/PrivateFrameworks/CoreSpeechExclave.framework/CoreSpeechExclave`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23d50` | `0x22c00` | **`-0x1150`** |
| `__TEXT.__eh_frame` | `0x1d40` | `0x1af0` | **`-0x250`** |
| `__DATA.__bss` | `0x2700` | `0x2500` | **`-0x200`** |
| `__TEXT.__const` | `0x2108` | `0x1fc0` | **`-0x148`** |
| `__AUTH_CONST.__const` | `0x16a8` | `0x1590` | **`-0x118`** |
| `__TEXT.__swift5_fieldmd` | `0xb60` | `0xac8` | **`-0x98`** |
| `__TEXT.__oslogstring` | `0xdcc` | `0xe3c` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0xa59` | `0x9e9` | **`-0x70`** |
| `__TEXT.__unwind_info` | `0xb08` | `0xac0` | **`-0x48`** |
| `__TEXT.__swift5_typeref` | `0x8e2` | `0x89c` | **`-0x46`** |
| `__TEXT.__constg_swiftt` | `0x970` | `0x940` | **`-0x30`** |
| `__DATA.__data` | `0x248` | `0x230` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x440` | `0x454` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x6c8` | `0x6b8` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x188` | `0x178` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f0` | `0x1f8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xa0` | `0x98` | **`-0x8`** |

### Other Changes

```diff

-3600.70.47.11.1
+3605.23.1.0.0

-  Functions: 812
-  Symbols:   448
-  CStrings:  172
+  Functions: 790
+  Symbols:   439
+  CStrings:  174
Symbols:
+ -[CSSecureSiriAudioProvidingProxy skipProcessingRaiseToSpeakAOE:]
+ GCC_except_table42
+ GCC_except_table44
+ GCC_except_table46
+ GCC_except_table60
+ GCC_except_table64
+ GCC_except_table67
- GCC_except_table41
- GCC_except_table43
- GCC_except_table45
- GCC_except_table59
- GCC_except_table63
- GCC_except_table66
- ___swift_memcpy40_8
- _symbolic Say_____G 17CoreSpeechExclave27SecureRTSAccelSamplePrivateV
- _symbolic Say_____G s5Int16V
- _symbolic _____ 17CoreSpeechExclave26SecureRTSReplayDataPrivateV
- _symbolic _____ 17CoreSpeechExclave27SecureRTSAccelSamplePrivateV
- _symbolic _____ySiG s23_ContiguousArrayStorageC
- _symbolic _____y_____G s23_ContiguousArrayStorageC 17CoreSpeechExclave27SecureRTSAccelSamplePrivateV
- _symbolic _____y_____G s23_ContiguousArrayStorageC s5Int16V
- _type_layout_string 17CoreSpeechExclave26SecureRTSReplayDataPrivateV
- _type_layout_string 17CoreSpeechExclave27SecureRTSAccelSamplePrivateV
CStrings:
+ "Failed to set skip RaiseToSpeak processing with error: %@"
+ "RaiseToSpeak skip processing set to %{bool}d"
```
