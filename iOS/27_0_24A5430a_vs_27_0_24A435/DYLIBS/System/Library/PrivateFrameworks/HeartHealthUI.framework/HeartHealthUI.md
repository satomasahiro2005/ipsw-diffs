## HeartHealthUI

> `/System/Library/PrivateFrameworks/HeartHealthUI.framework/HeartHealthUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c7a4` | `0x23cc8` | **`+0x7524`** |
| `__TEXT.__const` | `0xb88` | `0xcf8` | **`+0x170`** |
| `__TEXT.__eh_frame` | `—` | `0x150` | **`+0x150`** |
| `__AUTH_CONST.__auth_got` | `0x8f0` | `0x9f8` | **`+0x108`** |
| `__DATA.__bss` | `0xca0` | `0xda0` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x5b0` | `0x670` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x630` | `0x6e0` | **`+0xb0`** |
| `__DATA.__data` | `0x810` | `0x898` | **`+0x88`** |
| `__AUTH.__data` | `0x690` | `0x710` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x4b4` | `0x534` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x483` | `0x4e3` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x4a4` | `0x4e8` | **`+0x44`** |
| `__TEXT.__swift5_typeref` | `0x701` | `0x72d` | **`+0x2c`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x70` | `0x80` | **`+0x10`** |
| `__TEXT.__cstring` | `0xba` | `0xca` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xd0` | `0xe0` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x6c` | `0x74` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x54` | `0x5c` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 555
-  Symbols:   238
-  CStrings:  5
+  Functions: 635
+  Symbols:   250
+  CStrings:  6
Symbols:
+ _OBJC_CLASS_$_HKUnit
+ ___swift_memcpy1_1
+ ___swift_memcpy56_8
+ ___swift_memcpy9_8
+ _associated conformance 13HeartHealthUI13HRVBucketDataVSHAASQ
+ _bzero
+ _get_enum_tag_for_layout_string 13HeartHealthUI10MetricDataO
+ _get_witness_table 7SwiftUI7ForEachVySay011HeartHealthB016MetricHourlyDataVG10Foundation4DateVAA19_ConditionalContentVyALyACySayAD0g5ChartI0VGAjCySayAD0G5RangeVGAH4UUIDVALy6Charts0nM0PAUE15foregroundStyleyQrqd__AA05ShapeS0Rd__lFQOyAwUE10symbolSizeyQrSo6CGSizeVFQOyAU9PointMarkV_Qo__AA5ColorVQo_AwUEAXyQrqd__AaYRd__lFQOyAwUE12cornerRadius_5styleQr12CoreGraphics7CGFloatV_AA013RoundedCornerS0OtFQOyAU03BarY0V_Qo__A5_Qo_GGGA20_GA15_GGAuVHpA22_AuVHpA21_AuVHpA20_AuVHpA19_AuVHpA18_AuVHpqd0__AuVHD3_A6_HO_qd0__AuVHD3_A17_HOHC_HC_HC_A20_AuVHpA19_AuVHpA18_AuVHpqd0__AuVHD3_A6_HO_qd0__AuVHD3_A17_HOHC_HC_HCHC_A15_AuVHPyHCHC_HC
+ _objc_retain_x24
+ _swift_cvw_enumFn_getEnumTag
+ _symbolic Say_____GSg 13HeartHealthUI13HRVBucketDataV
+ _symbolic _____ 10Foundation8IndexSetV
+ _symbolic _____ 13HeartHealthUI0A25RateVariabilityDaySummaryV
+ _symbolic _____ 13HeartHealthUI13HRVBucketDataV
+ _symbolic _____ySay_____G__________yAEyAAySay_____GAdAySay_____G_____AEy_____y_____y______Qo_______Qo______y_____y______Qo__AMQo_GGGATGAOGG 7SwiftUI7ForEachV 011HeartHealthB016MetricHourlyDataV 10Foundation4DateV AA19_ConditionalContentV AD0g5ChartI0V AD0G5RangeV AG4UUIDV 6Charts0nM0PARE15foregroundStyleyQrqd__AA05ShapeS0Rd__lFQO AtRE10symbolSizeyQrSo6CGSizeVFQO AR9PointMarkV AA5ColorV AtREAUyQrqd__AaVRd__lFQO AtRE12cornerRadius_5styleQr12CoreGraphics7CGFloatV_AA013RoundedCornerS0OtFQO AR03BarY0V
+ _type_layout_string 13HeartHealthUI0A25RateVariabilityDaySummaryV
- ___swift_memcpy0_1
- ___swift_memcpy8_8
- _get_witness_table 7SwiftUI7ForEachVySay011HeartHealthB016MetricHourlyDataVG10Foundation4DateVAA19_ConditionalContentVyACySayAD0g5ChartI0VGAjCySayAD0G5RangeVGAH4UUIDVALy6Charts0nM0PAUE15foregroundStyleyQrqd__AA05ShapeS0Rd__lFQOyAwUE10symbolSizeyQrSo6CGSizeVFQOyAU9PointMarkV_Qo__AA5ColorVQo_AwUEAXyQrqd__AaYRd__lFQOyAwUE12cornerRadius_5styleQr12CoreGraphics7CGFloatV_AA013RoundedCornerS0OtFQOyAU03BarY0V_Qo__A5_Qo_GGGA15_GGAuVHpA21_AuVHpA20_AuVHpA19_AuVHpA18_AuVHpqd0__AuVHD3_A6_HO_qd0__AuVHD3_A17_HOHC_HC_HC_A15_AuVHPyHCHC_HC
- _symbolic _____ySay_____G__________yAAySay_____GAdAySay_____G_____AEy_____y_____y______Qo_______Qo______y_____y______Qo__AMQo_GGGAOGG 7SwiftUI7ForEachV 011HeartHealthB016MetricHourlyDataV 10Foundation4DateV AA19_ConditionalContentV AD0g5ChartI0V AD0G5RangeV AG4UUIDV 6Charts0nM0PARE15foregroundStyleyQrqd__AA05ShapeS0Rd__lFQO AtRE10symbolSizeyQrSo6CGSizeVFQO AR9PointMarkV AA5ColorV AtREAUyQrqd__AaVRd__lFQO AtRE12cornerRadius_5styleQr12CoreGraphics7CGFloatV_AA013RoundedCornerS0OtFQO AR03BarY0V
CStrings:
+ "key value "
```
