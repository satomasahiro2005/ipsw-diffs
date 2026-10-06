## AppleIDSetup

> `/System/Library/PrivateFrameworks/AppleIDSetup.framework/AppleIDSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x219464` | `0x219a88` | **`+0x624`** |
| `__AUTH_CONST.__const` | `0x16410` | `0x164e0` | **`+0xd0`** |
| `__DATA.__data` | `0x9800` | `0x9880` | **`+0x80`** |
| `__TEXT.__const` | `0x2ca60` | `0x2cae0` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x1109c` | `0x1110c` | **`+0x70`** |
| `__TEXT.__oslogstring` | `0x6700` | `0x6690` | **`-0x70`** |
| `__TEXT.__swift5_capture` | `0x2308` | `0x2378` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x87b8` | `0x87fc` | **`+0x44`** |
| `__TEXT.__unwind_info` | `0xa328` | `0xa358` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x81ac` | `0x81d4` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x4df0` | `0x4e00` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x978c` | `0x979c` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xa80` | `0xa84` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0xb24` | `0xb28` | **`+0x4`** |

### Other Changes

```diff

-128.1.1.0.0
+129.125.3.0.0

-  Functions: 14011
-  Symbols:   4764
-  CStrings:  874
+  Functions: 14027
+  Symbols:   4769
+  CStrings:  873
Symbols:
+ ___swift_closure_destructor.281Tm
+ ___swift_closure_destructor.310Tm
+ ___unnamed_17
+ ___unnamed_31
+ ___unnamed_34
+ ___unnamed_43
+ ___unnamed_48
+ ___unnamed_50
+ _symbolic _____ 12AppleIDSetup12_CoordinatedC13UpdateOutcome33_093F3A1234C334A2894A8262621197C2LLV
+ _symbolic _____yx_G_____yx______pGYacSg 12AppleIDSetup12_CoordinatedC13UpdateOutcome33_093F3A1234C334A2894A8262621197C2LLV s6ResultOsRi_zRi0_zrlE s5ErrorP
+ _symbolic _____yx______pG_____yx_GIegHno_ s6ResultOsRi_zRi0_zrlE s5ErrorP 12AppleIDSetup12_CoordinatedC13UpdateOutcome33_093F3A1234C334A2894A8262621197C2LLV
+ _type_layout_string s8SendableRzl12AppleIDSetup12_CoordinatedC13UpdateOutcome33_093F3A1234C334A2894A8262621197C2LLVyx_G
- ___swift_closure_destructor.276Tm
- ___unnamed_16
- ___unnamed_33
- ___unnamed_42
- ___unnamed_46
- _symbolic Sb_____yx______pGYacSg s6ResultOsRi_zRi0_zrlE s5ErrorP
- _symbolic _____yx______pGSbIegHnd_ s6ResultOsRi_zRi0_zrlE s5ErrorP
CStrings:
+ "Face ID verification is supported - biometry: %ld, flow: %s, ageRange: %lu"
+ "Flow type %s does not support Face ID verification"
- "Face ID verification is supported - biometry: %ld, flow: %s, country: empty, ageRange: %lu"
- "Flow type %s is not buddy - Face ID verification not supported"
- "Regulatory country region is not empty (%s) - Face ID verification not supported"
```
