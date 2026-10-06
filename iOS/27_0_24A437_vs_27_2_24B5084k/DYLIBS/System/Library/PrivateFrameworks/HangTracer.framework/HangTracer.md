## HangTracer

> `/System/Library/PrivateFrameworks/HangTracer.framework/HangTracer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18394` | `0x18438` | **`+0xa4`** |
| `__TEXT.__const` | `0x288` | `0x258` | **`-0x30`** |
| `__AUTH_CONST.__const` | `0x5c0` | `0x5a0` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0x618` | `0x628` | **`+0x10`** |
| `__DATA.__bss` | `0x138` | `0x128` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x1890` | `0x1898` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xb6c` | `0xb74` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x618` | `0x610` | **`-0x8`** |
| `__TEXT.__cstring` | `0x469d` | `0x4697` | **`-0x6`** |

### Other Changes

```diff

-426.0.0.0.0
+430.0.0.0.0

-  Functions: 606
-  Symbols:   1369
+  Functions: 607
+  Symbols:   1372
Symbols:
+ -[HTPrefs allTaskingPrefNames]
+ GCC_except_table40
+ _CFPreferencesCopyMultiple
+ ___NSDictionary0__struct
+ __isBlockedWidgetRendererBundleID
+ _defaultsTextForDomain
+ _kHTExtendedAttributeEventEnd
+ _kHTExtendedAttributeEventStart
+ _kHTExtendedAttributeEventType
+ _objc_opt_new
- GCC_except_table39
- _HTCPURoleMonitoringDenylist.denylist
- _HTCPURoleMonitoringDenylist.onceToken
- _OBJC_CLASS_$_NSSet
- ___HTCPURoleMonitoringDenylist_block_invoke
- _kHTExtendedAttributeHangEnd
- _kHTExtendedAttributeHangStart
CStrings:
+ "com.apple.chrono.WidgetRenderer-"
+ "hangtracer.event_end"
+ "hangtracer.event_start"
+ "hangtracer.event_type"
- "WidgetRenderer-Default"
- "com.apple.chrono.WidgetRenderer-Default"
- "hangtracer.hang_end"
- "hangtracer.hang_start"
```
