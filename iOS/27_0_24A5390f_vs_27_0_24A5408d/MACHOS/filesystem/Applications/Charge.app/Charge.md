## Charge

> `/Applications/Charge.app/Charge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d720` | `0x1fc04` | **`+0x24e4`** |
| `__TEXT.__const` | `0x25c4` | `0x2904` | **`+0x340`** |
| `__DATA_CONST.__const` | `0xd58` | `0xf68` | **`+0x210`** |
| `__DATA.__bss` | `0x16c0` | `0x18a0` | **`+0x1e0`** |
| `__TEXT.__swift5_typeref` | `0x33f4` | `0x35b0` | **`+0x1bc`** |
| `__DATA.__data` | `0x1bb8` | `0x1d08` | **`+0x150`** |
| `__TEXT.__objc_stubs` | `0xb20` | `0xc40` | **`+0x120`** |
| `__TEXT.__auth_stubs` | `0x1420` | `0x1530` | **`+0x110`** |
| `__TEXT.__constg_swiftt` | `0x1078` | `0x116c` | **`+0xf4`** |
| `__TEXT.__objc_methname` | `0x1fe7` | `0x209f` | **`+0xb8`** |
| `__TEXT.__swift5_fieldmd` | `0x84c` | `0x8f4` | **`+0xa8`** |
| `__DATA.__objc_data` | `0xc38` | `0xcc0` | **`+0x88`** |
| `__DATA_CONST.__auth_got` | `0xa18` | `0xaa0` | **`+0x88`** |
| `__DATA.__objc_const` | `0x15c0` | `0x1630` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x698` | `0x708` | **`+0x70`** |
| `__DATA_CONST.__auth_ptr` | `0x628` | `0x688` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x768` | `0x7c8` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x710` | `0x768` | **`+0x58`** |
| `__TEXT.__cstring` | `0x5ff` | `0x63f` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x980` | `0x9b8` | **`+0x38`** |
| `__TEXT.__objc_methtype` | `0x11f4` | `0x1224` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x405` | `0x425` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x408` | `0x420` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x228` | `0x240` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x118` | `0x128` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0xac` | `0xb8` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x90` | `0x9c` | **`+0xc`** |
| `__DATA_CONST.__objc_protorefs` | `0x90` | `0x98` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-340.0.0.0.0
+342.1.0.0.0

-  Functions: 733
-  Symbols:   613
-  CStrings:  477
+  Functions: 785
+  Symbols:   635
+  CStrings:  494
Symbols:
+ _$s10Foundation4DateV19_bridgeToObjectiveCSo6NSDateCyF
+ _$s10Foundation4DateV1loiySbAC_ACtFZ
+ _$s10Foundation4DateV21timeIntervalSince1970ACSd_tcfC
+ _$s10Foundation4DateVACycfC
+ _$s10Foundation4DateVMa
+ _$s10Foundation6LocaleV19_bridgeToObjectiveCSo8NSLocaleCyF
+ _$s10Foundation8CalendarV13isDateInTodayySbAA0D0VF
+ _$s10Foundation8CalendarV16isDateInTomorrowySbAA0D0VF
+ _$s10Foundation8CalendarV17isDateInYesterdayySbAA0D0VF
+ _$s10Foundation8CalendarV7currentACvgZ
+ _$s10Foundation8CalendarVMa
+ _$s7SwiftUI13TextAlignmentOMn
+ _$s7SwiftUI17EnvironmentValuesV22multilineTextAlignmentAA0fG0Ovg
+ _$s7SwiftUI17EnvironmentValuesV22multilineTextAlignmentAA0fG0OvpMV
+ _$s7SwiftUI17EnvironmentValuesV22multilineTextAlignmentAA0fG0Ovs
+ _$s7SwiftUI4FontV8footnoteACvgZ
+ _$s7SwiftUI4FontV8headlineACvgZ
+ _$s7SwiftUI5GroupVMn
+ _$s7SwiftUI5GroupVyxGAA4ViewA2aERzlMc
+ _OBJC_CLASS_$_NSDateFormatter
+ _objc_release_x28
+ _swift_retain_x23
CStrings:
+ "CAFChargingScheduleObserver"
+ "SCHEDULE_CHARGING_SCHEDULED"
+ "SCHEDULE_SCHEDULED_DATE"
+ "_mode"
+ "_scheduleModel"
+ "chargingSchedule"
+ "chargingScheduleService:didUpdateTimeToStart:"
+ "chargingTimeService:didUpdateElapsedTime:"
+ "setDateStyle:"
+ "setDoesRelativeDateFormatting:"
+ "setLocale:"
+ "setLocalizedDateFormatFromTemplate:"
+ "setTimeStyle:"
+ "stringFromDate:"
+ "timeToStart"
+ "timeToStartInvalid"
+ "v32@0:8@\"CAFChargingSchedule\"16@\"NSMeasurement\"24"
```
