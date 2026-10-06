## OSIntelligence

> `/System/Library/PrivateFrameworks/OSIntelligence.framework/OSIntelligence`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d4d4` | `0x1e468` | **`+0xf94`** |
| `__TEXT.__cstring` | `0x1d26` | `0x1f11` | **`+0x1eb`** |
| `__AUTH_CONST.__cfstring` | `0x18c0` | `0x1aa0` | **`+0x1e0`** |
| `__DATA_CONST.__const` | `0x918` | `0x990` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0x2c5d` | `0x2ccc` | **`+0x6f`** |
| `__TEXT.__objc_methlist` | `0x2590` | `0x25f0` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x1410` | `0x1458` | **`+0x48`** |
| `__TEXT.__unwind_info` | `0xa78` | `0xab8` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x3488` | `0x34b8` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x7a0` | `0x7c0` | **`+0x20`** |
| `__DATA.__bss` | `0x10` | `0x20` | **`+0x10`** |
| `__TEXT.__const` | `0x1d8` | `0x1e0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x224` | `0x228` | **`+0x4`** |

### Other Changes

```diff

-288.40.3.0.0
+288.40.6.0.0

-  Functions: 1016
-  Symbols:   1509
-  CStrings:  505
+  Functions: 1030
+  Symbols:   1525
+  CStrings:  523
Symbols:
+ +[_OSIBLMAnalyticsHandler allNotificationAnalyticsKeys]
+ +[_OSIBLMAnalyticsHandler analyticsKeyForNotificationDecision:]
+ -[_OSIBLMAnalyticsHandler historicalNotificationDataForDate:]
+ -[_OSIBLMAnalyticsHandler recordNotificationDecision:]
+ -[_OSIBLMAnalyticsHandler windowedNotificationSumsEndingDate:days:suffix:]
+ -[_OSIBLManager analyticsHandler]
+ -[_OSIBLManager isCurrentDrainUnusualWithDecision:]
+ -[_OSIBLManager setAnalyticsHandler:]
+ GCC_except_table57
+ GCC_except_table60
+ GCC_except_table64
+ _OBJC_IVAR_$__OSIBLManager._analyticsHandler
+ ___54-[_OSIBLMAnalyticsHandler recordNotificationDecision:]_block_invoke
+ ___55+[_OSIBLMAnalyticsHandler allNotificationAnalyticsKeys]_block_invoke
+ ___61-[_OSIBLMAnalyticsHandler historicalNotificationDataForDate:]_block_invoke
+ ___74-[_OSIBLMAnalyticsHandler windowedNotificationSumsEndingDate:days:suffix:]_block_invoke
+ ___block_descriptor_64_e8_32s40s48s56s_e39_v32?0"NSString"8"NSDictionary"16^B24ls32l8s40l8s48l8s56l8
+ _allNotificationAnalyticsKeys.keys
+ _allNotificationAnalyticsKeys.onceToken
- GCC_except_table55
- GCC_except_table58
- GCC_except_table62
CStrings:
+ "IBLMNotificationDecision"
+ "Last30Days"
+ "Last7Days"
+ "NotificationDecision"
+ "Recorded notification decision %{public}@ for %@ (now %ld)"
+ "Unsupported notification decision for analytics %ld"
+ "com.apple.osintelligence.iblm.recordNotificationDecision"
+ "historicalIBLMNotificationCounts"
+ "notificationEvaluationCount"
+ "notificationSuppressedByBackstop"
+ "notificationSuppressedByCooldown"
+ "notificationSuppressedByDisabled"
+ "notificationSuppressedByInsufficientData"
+ "notificationSuppressedByNotUnusual"
+ "notificationSuppressedBySlotOutOfRange"
+ "notificationSuppressedByStartHour"
+ "onboardingNotificationCount"
+ "unusualDrainNotificationCount"
```
