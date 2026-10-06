## footprint

> `/usr/bin/footprint`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21314` | `0x215c0` | **`+0x2ac`** |
| `__TEXT.__cstring` | `0x303f` | `0x3072` | **`+0x33`** |
| `__DATA.__objc_const` | `0x3200` | `0x3220` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xce0` | `0xcf0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x680` | `0x688` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x268` | `0x270` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4d0` | `0x4d8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2c4` | `0x2c8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-364.0.0.0.0
+365.0.0.0.0

-  Functions: 453
-  Symbols:   1556
-  CStrings:  1102
+  Functions: 454
+  Symbols:   1560
+  CStrings:  1105
Symbols:
+ -[FPOutputFormatterPerfdata _emitTimeMeasurementForTime:metric:]
+ OBJC_IVAR_$_FPOutputFormatterPerfdata._dateFormatter
+ _pdunit_s
+ _pdwriter_record_label_dbl
Functions:
+ +[FPSharedCache instanceCache]
- +[FPSharedCache instanceCache]
~ -[FPOutputFormatterPerfdata initWithPath:] : 424 -> 496
~ -[FPOutputFormatterPerfdata startAtTime:] : 12 -> 104
+ -[FPOutputFormatterPerfdata _emitTimeMeasurementForTime:metric:]
~ -[FPOutputFormatterPerfdata endAtTime:] : 160 -> 200
~ -[FPOutputFormatterPerfdata .cxx_destruct] : 80 -> 92
CStrings:
+ "date"
+ "mach_absolute_time_ns"
+ "mach_continuous_time_ns"
```
