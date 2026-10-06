## SpeechEngine

> `/System/Library/PrivateFrameworks/SpeechEngine.framework/SpeechEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x5a10` | `0x68f0` | **`+0xee0`** |
| `__AUTH.__data` | `0xe80` | `—` | **`-0xe80`** |
| `__TEXT.__text` | `0x13acb0` | `0x13b828` | **`+0xb78`** |
| `__TEXT.__swift5_reflstr` | `0x3d16` | `0x43f6` | **`+0x6e0`** |
| `__TEXT.__const` | `0xe950` | `0xeec0` | **`+0x570`** |
| `__TEXT.__unwind_info` | `0x5c78` | `0x6138` | **`+0x4c0`** |
| `__DATA.__bss` | `0x13e30` | `0x14130` | **`+0x300`** |
| `__TEXT.__swift5_fieldmd` | `0x4a14` | `0x4ca0` | **`+0x28c`** |
| `__AUTH.__objc_data` | `0xe8` | `—` | **`-0xe8`** |
| `__DATA_DIRTY.__objc_data` | `0x6e8` | `0x7d0` | **`+0xe8`** |
| `__AUTH_CONST.__const` | `0xc5d0` | `0xc6a8` | **`+0xd8`** |
| `__TEXT.__eh_frame` | `0xe6dc` | `0xe664` | **`-0x78`** |
| `__TEXT.__cstring` | `0x5981` | `0x5921` | **`-0x60`** |
| `__DATA.__data` | `0x2a88` | `0x2a50` | **`-0x38`** |
| `__TEXT.__swift5_assocty` | `0x1c8` | `0x1f8` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x3a22` | `0x3a52` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x19b8` | `0x19d8` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x5290` | `0x52ac` | **`+0x1c`** |
| `__TEXT.__swift5_proto` | `0xa2c` | `0xa44` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x1b8` | `0x1a4` | **`-0x14`** |
| `__TEXT.__swift5_mpenum` | `0x60` | `0x58` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x484` | `0x488` | **`+0x4`** |

### Other Changes

```diff

-3605.7.1.0.0
+3605.8.1.0.0

-  Functions: 9343
-  Symbols:   2412
-  CStrings:  937
+  Functions: 9390
+  Symbols:   2417
+  CStrings:  934
Symbols:
+ _associated conformance 12SpeechEngine0aB5ErrorV0C4CodeOSHAASQ
+ _associated conformance 12SpeechEngine0aB5ErrorV0C4CodeOs12CaseIterableAA8AllCasessAFP_Sl
+ _associated conformance 12SpeechEngine0aB5ErrorV10Foundation09LocalizedC0AAs0C0
+ _associated conformance 12SpeechEngine0aB5ErrorV10Foundation13CustomNSErrorAAs0C0
+ _associated conformance 12SpeechEngine0aB5ErrorVSHAASQ
+ _symbolic Say_____G 12SpeechEngine0aB5ErrorV0C4CodeO
+ _symbolic _____ 12SpeechEngine0aB5ErrorV
+ _symbolic _____ 12SpeechEngine0aB5ErrorV0C4CodeO
+ _type_layout_string 12SpeechEngine0aB5ErrorV
- _associated conformance 12SpeechEngine0aB5ErrorO10Foundation09LocalizedC0AAs0C0
- _get_enum_tag_for_layout_string 12SpeechEngine0aB5ErrorO
- _symbolic _____ 12SpeechEngine0aB5ErrorO
- _type_layout_string 12SpeechEngine0aB5ErrorO
CStrings:
+ "Model expects gumbel_noise but gumbelFile is nil"
- "Model expects gumbel_noise but gumbelFile is not configured"
- "SpeechEngineError.fileNotFound: "
- "SpeechEngineError.runtime: "
- "SpeechEngineError.unsupported: "
```
