## OSIntelligence

> `/System/Library/PrivateFrameworks/OSIntelligence.framework/OSIntelligence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a5e8` | `0x1b5dc` | **`+0xff4`** |
| `__TEXT.__oslogstring` | `0x2609` | `0x2820` | **`+0x217`** |
| `__TEXT.__cstring` | `0x1a4a` | `0x1b54` | **`+0x10a`** |
| `__AUTH_CONST.__cfstring` | `0x1580` | `0x1660` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x2290` | `0x2338` | **`+0xa8`** |
| `__AUTH_CONST.__objc_const` | `0x30e8` | `0x3188` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1208` | `0x1278` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x9b8` | `0x9e8` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x6a8` | `0x6c8` | **`+0x20`** |
| `__TEXT.__const` | `0x1a8` | `0x1b8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1d8` | `0x1e4` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x1f0` | `0x1f8` | **`+0x8`** |

### Other Changes

```diff

-284.0.0.0.0
+286.0.0.0.0

-  Functions: 921
-  Symbols:   1404
-  CStrings:  438
+  Functions: 938
+  Symbols:   1424
+  CStrings:  455
Symbols:
+ -[_OSBatteryPredictor currentBatteryDrainAggregatedOverTimeWidth:withError:]
+ -[_OSBatteryPredictor typicalBatteryDrainWithReferenceDays:aggregatedOverTimeWidth:withError:]
+ -[_OSIBLManager doubleValueForTrialFactor:withDefault:]
+ -[_OSIBLManager isCurrentDrainUnusual]
+ -[_OSIBLManager notificationDefaults]
+ -[_OSIBLManager recentUnusualDrainPostDatesWithinWindow]
+ -[_OSIBLManager recordUnusualDrainPostAtDate:]
+ -[_OSIBLManager setNotificationDefaults:]
+ -[_OSIBLManager setUnusualDrainRampUpFraction:]
+ -[_OSIBLManager setUnusualDrainStartingThreshold:]
+ -[_OSIBLManager unusualDrainRampUpFraction]
+ -[_OSIBLManager unusualDrainStartingThreshold]
+ _OBJC_IVAR_$__OSIBLManager._notificationDefaults
+ _OBJC_IVAR_$__OSIBLManager._unusualDrainRampUpFraction
+ _OBJC_IVAR_$__OSIBLManager._unusualDrainStartingThreshold
+ _OUTLINED_FUNCTION_9
+ ___76-[_OSBatteryPredictor currentBatteryDrainAggregatedOverTimeWidth:withError:]_block_invoke
+ ___94-[_OSBatteryPredictor typicalBatteryDrainWithReferenceDays:aggregatedOverTimeWidth:withError:]_block_invoke
+ ___NSArray0__struct
+ _objc_retain_x26
CStrings:
+ "Drain check slot %lu (hour %lu): current %f vs median %f + threshold %f -> %{public}s"
+ "Drain slot %lu out of range (typical=%lu, current=%lu); skipping"
+ "IBLM_UnusualDrainRampUpFraction"
+ "IBLM_UnusualDrainStartingThreshold"
+ "Local hour %lu before start hour %lu; skipping unusual-drain notification"
+ "Not enough drain data (typicalErr: %@, currentErr: %@); skipping"
+ "Notified for IBLM onboarding notification"
+ "Notified for IBLM unusual-drain notification"
+ "Onboarding IBLM notification already posted once; skipping"
+ "Unusual-drain notification posted %lu times in the last %.0f days; skipping"
+ "Unusual-drain notification within %.0f-day cooldown; skipping"
+ "com.apple.osi.iblm.unusualDrainNotification"
+ "com.apple.osintelligence.iblm.notifications"
+ "kDidPostOnboardingNotification"
+ "kDidRecordFirstUnusualDrainTrigger"
+ "normal"
+ "unusual"
+ "unusualDrainNotificationDates"
- "Notified for IBLM Engaged notification"
```
