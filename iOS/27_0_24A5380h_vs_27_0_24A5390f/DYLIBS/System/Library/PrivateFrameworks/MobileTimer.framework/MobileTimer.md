## MobileTimer

> `/System/Library/PrivateFrameworks/MobileTimer.framework/MobileTimer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x135d4c` | `0x1360e0` | **`+0x394`** |
| `__AUTH_CONST.__objc_const` | `0x2c238` | `0x2c510` | **`+0x2d8`** |
| `__TEXT.__eh_frame` | `0x5098` | `0x50c8` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x7520` | `0x7540` | **`+0x20`** |
| `__TEXT.__cstring` | `0x99c2` | `0x99d2` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x113c` | `0x114c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x59a0` | `0x59a8` | **`+0x8`** |

### Other Changes

```diff

-2329.0.0.0.0
+2330.0.0.0.0

-  Functions: 7893
+  Functions: 7894

-  CStrings:  2852
+  CStrings:  2853
Symbols:
+ -[MTReport .cxx_destruct]
+ -[MTReport concerns]
+ -[MTReport date]
+ -[MTReport initWithDate:concerns:]
+ -[MTReport isValid]
+ _OBJC_CLASS_$_MTReport
+ _OBJC_IVAR_$_MTReport._concerns
+ _OBJC_IVAR_$_MTReport._date
+ _OBJC_METACLASS_$_MTReport
+ __OBJC_$_INSTANCE_METHODS_MTReport
+ __OBJC_$_INSTANCE_VARIABLES_MTReport
+ __OBJC_$_PROP_LIST_MTReport
+ __OBJC_CLASS_PROTOCOLS_$_MTReport
+ __OBJC_CLASS_RO_$_MTReport
+ __OBJC_METACLASS_RO_$_MTReport
+ _symbolic SaySo8MTReportCG
+ _symbolic SaySo8MTReportCGIeghg_
- -[MTStoredReportValue .cxx_destruct]
- -[MTStoredReportValue concerns]
- -[MTStoredReportValue date]
- -[MTStoredReportValue initWithDate:concerns:]
- -[MTStoredReportValue isValid]
- _OBJC_CLASS_$_MTStoredReportValue
- _OBJC_IVAR_$_MTStoredReportValue._concerns
- _OBJC_IVAR_$_MTStoredReportValue._date
- _OBJC_METACLASS_$_MTStoredReportValue
- __OBJC_$_INSTANCE_METHODS_MTStoredReportValue
- __OBJC_$_INSTANCE_VARIABLES_MTStoredReportValue
- __OBJC_$_PROP_LIST_MTStoredReportValue
- __OBJC_CLASS_PROTOCOLS_$_MTStoredReportValue
- __OBJC_CLASS_RO_$_MTStoredReportValue
- __OBJC_METACLASS_RO_$_MTStoredReportValue
- _symbolic Say_____G 11MobileTimer10MTCDReportC
- _symbolic Say_____GIeghg_ 11MobileTimer10MTCDReportC
CStrings:
+ "ALARM_THIS_WEEKDAY_FORMAT"
```
