## GenerativeExperiencesRuntime

> `/System/Library/PrivateFrameworks/GenerativeExperiencesRuntime.framework/GenerativeExperiencesRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xeab80` | `0xef500` | **`+0x4980`** |
| `__TEXT.__oslogstring` | `0x89a0` | `0x8e40` | **`+0x4a0`** |
| `__AUTH_CONST.__const` | `0x8488` | `0x8800` | **`+0x378`** |
| `__TEXT.__eh_frame` | `0x941c` | `0x9714` | **`+0x2f8`** |
| `__TEXT.__unwind_info` | `0x3468` | `0x3600` | **`+0x198`** |
| `__TEXT.__swift5_capture` | `0x2794` | `0x28d4` | **`+0x140`** |
| `__AUTH_CONST.__objc_const` | `0x3248` | `0x3300` | **`+0xb8`** |
| `__TEXT.__cstring` | `0x1ed5` | `0x1f75` | **`+0xa0`** |
| `__AUTH.__data` | `0x508` | `0x5a0` | **`+0x98`** |
| `__DATA.__data` | `0xb08` | `0xb90` | **`+0x88`** |
| `__TEXT.__const` | `0x5b4c` | `0x5ba8` | **`+0x5c`** |
| `__DATA_DIRTY.__data` | `0x3298` | `0x3248` | **`-0x50`** |
| `__TEXT.__swift5_typeref` | `0x2898` | `0x2854` | **`-0x44`** |
| `__TEXT.__swift5_reflstr` | `0x104d` | `0x108d` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x73c` | `0x76c` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x145c` | `0x1484` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x6e0` | `0x700` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x94c` | `0x96c` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x350` | `0x36c` | **`+0x1c`** |
| `__TEXT.__swift_as_ret` | `0x368` | `0x384` | **`+0x1c`** |
| `__DATA.__bss` | `0x27f0` | `0x27e0` | **`-0x10`** |
| `__DATA.__common` | `0xa0` | `0xb0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1d8` | `0x1e0` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x1f14` | `0x1f10` | **`-0x4`** |
| `__TEXT.__swift5_proto` | `0x304` | `0x308` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x220` | `0x224` | **`+0x4`** |

### Other Changes

```diff

-291.1.0.5.0
+291.6.0.5.101

+  - /System/Library/PrivateFrameworks/AppleMediaServices.framework/AppleMediaServices

-  Functions: 5187
-  Symbols:   283
-  CStrings:  656
+  Functions: 5262
+  Symbols:   286
+  CStrings:  673
Symbols:
+ _MobileGestalt_get_isVirtualDevice
+ _OBJC_CLASS_$_AMSEphemeralDefaults
+ _OBJC_CLASS_$_NSURLCache
CStrings:
+ "AvailabilityReporter skipped redundant write, but would have logged event: %{public}s"
+ "LanguagePreferences initialized with: %s"
+ "LanguagePreferences language change detected: %s"
+ "LanguagePreferences received %s, fetched: %s"
+ "WaitlistEnrollmentBackfill: %{public}s; enrolling + applying bypass"
+ "WaitlistEnrollmentBackfill: applied gmEligibilityBypass; now %{bool,public}d"
+ "WaitlistEnrollmentBackfill: gmEligibilityBypass already set; left as-is"
+ "WaitlistEnrollmentBackfill: signed up for waitlist featureID=%{public}s; status=%{public}s"
+ "WaitlistEnrollmentBackfill: skipping waitlist signup — virtual device"
+ "WaitlistEnrollmentBackfill: skipping — device not exempt and no accepted waitlist override (isExemptDevice=%{bool,public}d, forcedWaitlistStatus=%{public}s)"
+ "WaitlistEnrollmentBackfill: skipping — not an internal build"
+ "WaitlistEnrollmentBackfill: waitlist signup failed for featureID=%{public}s: %{public}s"
+ "accepted waitlist override present"
+ "com.apple.GenerativeFunctions.PeriodicTasks.WaitlistEnrollmentBackfill.Boot"
+ "device is exempt from waitlist"
+ "forceWaitlistStatus: set GM eligibility bypass to %{bool,public}d; gmEligibilityBypass() now %{bool,public}d"
+ "runWaitlistEnrollmentBackfill: missingEntitlementForAdditionalCapability"
```
