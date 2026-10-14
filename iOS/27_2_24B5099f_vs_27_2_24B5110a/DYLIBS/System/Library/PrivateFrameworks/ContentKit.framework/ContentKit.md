## ContentKit

> `/System/Library/PrivateFrameworks/ContentKit.framework/ContentKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x211460` | `0x217a00` | **`+0x65a0`** |
| `__TEXT.__eh_frame` | `0xaa60` | `0xaef8` | **`+0x498`** |
| `__AUTH_CONST.__const` | `0xcd78` | `0xd148` | **`+0x3d0`** |
| `__DATA.__bss` | `0xdfc8` | `0xe348` | **`+0x380`** |
| `__TEXT.__const` | `0x9c44` | `0x9e34` | **`+0x1f0`** |
| `__TEXT.__swift5_capture` | `0x248c` | `0x25dc` | **`+0x150`** |
| `__DATA.__data` | `0x3a2c` | `0x3b5c` | **`+0x130`** |
| `__TEXT.__unwind_info` | `0x87b8` | `0x8880` | **`+0xc8`** |
| `__TEXT.__cstring` | `0x1cf75` | `0x1d035` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x1ab4` | `0x1b44` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x26e8` | `0x2776` | **`+0x8e`** |
| `__TEXT.__swift5_fieldmd` | `0x1d2c` | `0x1da0` | **`+0x74`** |
| `__TEXT.__oslogstring` | `0x6237` | `0x6287` | **`+0x50`** |
| `__TEXT.__swift5_assocty` | `0x480` | `0x4b0` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x908` | `0x938` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x4f4` | `0x514` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x6a8` | `0x6c4` | **`+0x1c`** |
| `__TEXT.__swift_as_entry` | `0x360` | `0x378` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0x141b` | `0x142b` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x220` | `0x228` | **`+0x8`** |

### Other Changes

```diff

-5113.0.1.1.1
+5114.0.8.3.0

-  Functions: 12876
-  Symbols:   11976
-  CStrings:  4865
+  Functions: 12959
+  Symbols:   11989
+  CStrings:  4868
Symbols:
+ _associated conformance 10ContentKit18FMReasonedResponseV18PartiallyGeneratedVyx_Gs12IdentifiableAA2IDsAGP_SH
+ _associated conformance 10ContentKit18FMReasonedResponseVyxG16FoundationModels022ConvertibleToGeneratedA0AaE19PromptRepresentable
+ _associated conformance 10ContentKit18FMReasonedResponseVyxG16FoundationModels022ConvertibleToGeneratedA0AaE25InstructionsRepresentable
+ _associated conformance 10ContentKit18FMReasonedResponseVyxG16FoundationModels9GenerableAA18PartiallyGeneratedAeFP_AE015ConvertibleFromiA0
+ _associated conformance 10ContentKit18FMReasonedResponseVyxG16FoundationModels9GenerableAaE022ConvertibleToGeneratedA0
+ _associated conformance 10ContentKit18FMReasonedResponseVyxG16FoundationModels9GenerableAaE024ConvertibleFromGeneratedA0
+ _symbolic _____ 10ContentKit18FMReasonedResponseV
+ _symbolic _____ 10ContentKit18FMReasonedResponseV18PartiallyGeneratedV
+ _symbolic _____y_____G 10ContentKit18FMReasonedResponseV AA12FMDateOutputV
+ _symbolic _____y_____G 10ContentKit18FMReasonedResponseV AA15FMBooleanOutputV
+ _symbolic _____y______y_____GG 16FoundationModels20LanguageModelSessionC8ResponseV 10ContentKit010FMReasonedF0V AF12FMDateOutputV
+ _symbolic _____y______y_____GG 16FoundationModels20LanguageModelSessionC8ResponseV 10ContentKit010FMReasonedF0V AF15FMBooleanOutputV
+ _symbolic _____yx_G 10ContentKit18FMReasonedResponseV18PartiallyGeneratedV
CStrings:
+ "Error message for the Use Model action when the Cloud Pro model can't be used, e.g. because the user's iCloud plan doesn't include it."
+ "Requesting a reasoned safety schema-wrapped response for output type: %s"
+ "Your request can’t be completed."
```
