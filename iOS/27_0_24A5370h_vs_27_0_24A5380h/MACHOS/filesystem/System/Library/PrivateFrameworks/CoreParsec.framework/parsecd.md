## parsecd

> `/System/Library/PrivateFrameworks/CoreParsec.framework/parsecd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16f288` | `0x16f50c` | **`+0x284`** |
| `__TEXT.__auth_stubs` | `0x4fa0` | `0x5020` | **`+0x80`** |
| `__TEXT.__const` | `0xee80` | `0xee00` | **`-0x80`** |
| `__TEXT.__swift5_typeref` | `0x4f52` | `0x4edc` | **`-0x76`** |
| `__TEXT.__swift5_fieldmd` | `0x50a4` | `0x5110` | **`+0x6c`** |
| `__TEXT.__cstring` | `0x65a4` | `0x6604` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x4040` | `0x40a0` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x5493` | `0x54f3` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x27e0` | `0x2820` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x64b5` | `0x64f5` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x7260` | `0x7298` | **`+0x38`** |
| `__DATA.__data` | `0x97f8` | `0x97e0` | **`-0x18`** |
| `__DATA.__objc_selrefs` | `0x1530` | `0x1548` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x10228` | `0x10240` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x1ed0` | `0x1ee0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x13f8` | `0x13f0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.56.7.0.0
+3600.56.16.0.0

-  Functions: 8901
-  Symbols:   2320
-  CStrings:  2491
+  Functions: 8888
+  Symbols:   2328
+  CStrings:  2497
Symbols:
+ _$s10Foundation6LocaleV16decimalSeparatorSSSgvg
+ _$s10Foundation6LocaleV17groupingSeparatorSSSgvg
+ _$s10PegasusAPI020Apple_Parsec_Search_A12QueryContextV12numberFormatAA0c1_d1_e7_NumberI0Vvs
+ _$s10PegasusAPI020Apple_Parsec_Search_A12QueryContextV16shortDatePatternSSvs
+ _$s10PegasusAPI32Apple_Parsec_Search_NumberFormatV16decimalSeparatorSSvs
+ _$s10PegasusAPI32Apple_Parsec_Search_NumberFormatV17groupingSeparatorSSvs
+ _$s10PegasusAPI32Apple_Parsec_Search_NumberFormatVACycfC
+ _$s10PegasusAPI32Apple_Parsec_Search_NumberFormatVMa
+ _$s10PegasusAPI32Apple_Parsec_Search_NumberFormatVMn
+ _$s20PegasusConfiguration17DeviceContextUtilV10rdEstimateSo10RDEstimateCSgvgZ
+ _$s20PegasusConfiguration17DeviceContextUtilV11countryCodeSSSgvgZ
+ _OBJC_CLASS_$_NSDateFormatter
- _$s20PegasusConfiguration17DeviceContextUtilV17deviceCountryCodeSSSgyFZ
- _$s20PegasusConfiguration17DeviceContextUtilV19countryCodeProviderSSSgycSgvsZ
- _OBJC_CLASS_$_RDEstimate
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "dateFormat"
+ "decimalSeparator"
+ "groupingSeparator"
+ "setAppleIntelligenceEligible:"
+ "setDateStyle:"
+ "setSiriPreviewOptIn:"
+ "setTimeStyle:"
+ "shortDatePattern"
- "currentEstimates"
- "lastKnownEstimates"
```
