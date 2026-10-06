## CoreBrightness

> `/System/Library/PrivateFrameworks/CoreBrightness.framework/CoreBrightness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17d0dc` | `0x17d528` | **`+0x44c`** |
| `__TEXT.__oslogstring` | `0x1aded` | `0x1aefd` | **`+0x110`** |
| `__AUTH_CONST.__cfstring` | `0xed80` | `0xedc0` | **`+0x40`** |
| `__TEXT.__const` | `0x1b6c0` | `0x1b6e0` | **`+0x20`** |
| `__DATA.__bss` | `0x6b40` | `0x6b50` | **`+0x10`** |
| `__TEXT.__cstring` | `0xd335` | `0xd345` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x5960` | `0x5968` | **`+0x8`** |

### Other Changes

```diff

-2300.40.37.0.0
+2300.40.39.0.0

-  CStrings:  4871
+  CStrings:  4877
Symbols:
+ _OBJC_IVAR_$_CBCPMSModule._currentHDRNits
- _OBJC_IVAR_$_CBCPMSModule._currentSDRNits
Functions:
~ __ZN4AABC20setPropertyForClientEPK10__CFStringPKvS4_ : 13556 -> 13560
~ ___DisplaySetProperty_block_invoke : 19892 -> 20208
~ __ZN4AABC11handleEventEPU26objcproto15CBEventProtocol11objc_object : 1032 -> 1036
~ __ZN4AABC14HandleALSEventEPU49objcproto18CBALSEventProtocol18CBHIDEventProtocol11objc_object : 7420 -> 7416
~ -[CBCPMSModule handleNotificationForKey:withProperty:] : 112 -> 304
~ ___DisplayFadeCallback : 4260 -> 4272
~ ___DisplaySetLogicalBrightnessInternal : 7016 -> 7048
~ -[CBDisplayModuleiOS handleDisplayBrightnessUpdate:] : 4164 -> 4176
~ __ZN4AABC16RampDoneCallbackEv : 876 -> 880
~ __ZN4AABC16SetDisplayFactorEfb : 2812 -> 2800
~ __ZN4AABC11UpdateStateENS_9eAABStateE : 1044 -> 1048
~ __ZN4AABC14UpdateALSStateEj : 140 -> 144
~ __ZN4AABC20handleAODStateUpdateE8AODStatefP11objc_object : 3612 -> 3620
~ -[CBSBIM initialiseLimits:] : 1316 -> 1352
~ __DisplaySetBrightnessMaxPhysicalWithFade : 1088 -> 1132
~ __DisplaySetBrightnessMaxPhysicalZeroWithFade : 616 -> 680
~ -[CBCPMSModule handleBudgetUpdate:] : 1060 -> 1108
~ __ZN4AABCC2EPK8__CFUUIDPN3AAB19UpdateCurveStrategyE : 1264 -> 1284
~ __ZN4AABC15registerDisplayEP9__DisplayP16CBDisplayContext : 8680 -> 9020
~ __ZN4AABC20InitializeCPMSModuleEv : 2292 -> 2272
~ __ZN4AABC17revertToGoodCurveE22CBAABCurveUpdateReason : 1148 -> 1144
~ __ZN4AABC21_UpdateEsensorTrustedEfNSt3__18optionalIfEE : 2096 -> 2088
~ __ZN4AABC14SetALSIntervalEf : 224 -> 228
CStrings:
+ "CPMSCurrentHDRNits"
+ "Grimaldi lux cap = %.2f"
+ "[BRT update: %s]: begin ramp L: %0.2f -> %0.2f P: %0.2f -> %0.2f (hwMax-perceptual) t: %f rate: %0.2f nits/s %0.2fhz"
+ "[CPMS] Current HDR brightness updated: %f -> %f"
+ "[CPMS] Sending nits cap ramp to display: target=%f duration=%fs start=%f"
+ "[CPMS] Using current HDR nits (%f) instead of cap (%f) for ramp duration calculation"
+ "[Display] CPMS cap ramp: seeding origin %f -> %f (target %f, headroom %f)"
+ "[Display] CPMS ramp request: target=%f duration=%f start=%f"
+ "grimaldi-lux-cap"
+ "startNits"
- "CPMSCurrentSDRNits"
- "[CPMS] Sending nits cap ramp to display: target=%f duration=%fs"
- "[CPMS] Using current SDR nits (%f) instead of cap (%f) for ramp duration calculation"
- "[Display] CPMS ramp request: target=%f duration=%f"
```
