## DateAndTimeSupport

> `/System/Library/PrivateFrameworks/DateAndTimeSupport.framework/DateAndTimeSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16c64` | `0x17570` | **`+0x90c`** |
| `__TEXT.__oslogstring` | `0x526` | `0x6f6` | **`+0x1d0`** |
| `__TEXT.__cstring` | `0x223` | `0x263` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x9a8` | `0x9e0` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x2c8` | `0x298` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x418` | `0x3f8` | **`-0x20`** |
| `__TEXT.__const` | `0xcf0` | `0xcd0` | **`-0x20`** |
| `__AUTH.__data` | `0x628` | `0x610` | **`-0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x234` | `0x21c` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x6b0` | `0x698` | **`-0x18`** |
| `__TEXT.__constg_swiftt` | `0x558` | `0x548` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x7c8` | `0x7d0` | **`+0x8`** |
| `__DATA.__data` | `0x2a0` | `0x2a8` | **`+0x8`** |

### Other Changes

```diff

-1259.0.0.0.0
+2027.0.2.0.0

-  Functions: 540
-  Symbols:   288
-  CStrings:  35
+  Functions: 543
+  Symbols:   289
+  CStrings:  42
Symbols:
+ _objc_release_x26
+ _swift_retain_x27
- _objc_retain_x27
CStrings:
+ "lastCitySelectorTimeZone"
+ "restorePreviousTimeZoneIfAvailable: lastCitySelectorTimeZone=%{public}s"
+ "restorePreviousTimeZoneIfAvailable: not restoring - either no stored citySelector time zone or outside retention period"
+ "restorePreviousTimeZoneIfAvailable: restoring citySelector time zone %{public}s"
+ "setsTimeZoneAutomatically: switching to citySelector mode - this will trigger time zone restoration"
+ "setsTimeZoneAutomatically: switching to nautical mode"
+ "timeZoneSelectionMode"
```
