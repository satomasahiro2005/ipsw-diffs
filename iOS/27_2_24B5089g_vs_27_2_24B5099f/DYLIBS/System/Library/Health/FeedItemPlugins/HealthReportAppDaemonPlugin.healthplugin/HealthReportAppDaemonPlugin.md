## HealthReportAppDaemonPlugin

> `/System/Library/Health/FeedItemPlugins/HealthReportAppDaemonPlugin.healthplugin/HealthReportAppDaemonPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x40ac0` | `0x47b4c` | **`+0x708c`** |
| `__AUTH_CONST.__auth_got` | `0x1cb0` | `0x1358` | **`-0x958`** |
| `__TEXT.__eh_frame` | `0x1618` | `0x1f38` | **`+0x920`** |
| `__TEXT.__cstring` | `0xc04` | `0x464` | **`-0x7a0`** |
| `__DATA.__data` | `0xef0` | `0x9a8` | **`-0x548`** |
| `__TEXT.__oslogstring` | `0xd61` | `0x11d1` | **`+0x470`** |
| `__TEXT.__unwind_info` | `0xa18` | `0xd60` | **`+0x348`** |
| `__TEXT.__const` | `0x119c` | `0x131c` | **`+0x180`** |
| `__DATA.__bss` | `0x1780` | `0x1630` | **`-0x150`** |
| `__TEXT.__swift5_typeref` | `0x565` | `0x6b5` | **`+0x150`** |
| `__AUTH_CONST.__const` | `0x738` | `0x7e8` | **`+0xb0`** |
| `__AUTH.__data` | `0xa30` | `0xad0` | **`+0xa0`** |
| `__TEXT.__swift_as_cont` | `0xfc` | `0x180` | **`+0x84`** |
| `__DATA_CONST.__objc_selrefs` | `0x30` | `0xa0` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0xec` | `0x158` | **`+0x6c`** |
| `__TEXT.__constg_swiftt` | `0x620` | `0x684` | **`+0x64`** |
| `__AUTH.__objc_data` | `0x138` | `0x188` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x8a8` | `0x8f8` | **`+0x50`** |
| `__TEXT.__swift_as_ret` | `0x8c` | `0xd4` | **`+0x48`** |
| `__TEXT.__swift_as_entry` | `0x6c` | `0xa8` | **`+0x3c`** |
| `__TEXT.__swift5_reflstr` | `0x40b` | `0x43b` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x50c` | `0x530` | **`+0x24`** |
| `__TEXT.__swift5_assocty` | `0x80` | `0x98` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0xc0` | `0xb4` | **`-0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x50` | **`+0x8`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  - /System/Library/PrivateFrameworks/HealthTopicsCore.framework/HealthTopicsCore

+  - /System/Library/PrivateFrameworks/Sleep.framework/Sleep

-  Functions: 778
-  Symbols:   170
-  CStrings:  116
+  Functions: 919
+  Symbols:   192
+  CStrings:  106
Symbols:
+ _HKCategoryTypeIdentifierAppleStandHour
+ _HKIsFitnessTrackingEnabled
+ _HKProtectedHealthDatabaseDidBecomeAvailableNotification
+ _OBJC_CLASS_$_HKCategorySample
+ _OBJC_CLASS_$_HKCategoryType
+ _OBJC_CLASS_$_HKHealthStore
+ _OBJC_CLASS_$_HKQuery
+ _OBJC_CLASS_$_HKSPSleepStore
+ _OBJC_CLASS_$_HKSample
+ _OBJC_CLASS_$_NSCompoundPredicate
+ _OBJC_CLASS_$_NSPredicate
+ _OBJC_CLASS_$__HKBehavior
+ _objc_release
+ _objc_release_x28
+ _objc_retain_x24
+ _swift_asyncLet_begin
+ _swift_asyncLet_finish
+ _swift_asyncLet_get
+ _swift_asyncLet_get_throwing
+ _swift_cvw_enumFn_getEnumTag
+ _swift_getAtKeyPath
+ _swift_getKeyPath
+ _swift_initStackObject
- _swift_dynamicCastClass
CStrings:
+ "Accessing Environment<%s>'s value outside of being installed on a View. This will always read the default value and will not update."
+ "HealthReportAppDaemonPlugin/EvaluationTileView.swift"
+ "HealthSummaryDatabaseRetryCriteria"
+ "[%s] Could not compute the survey window ending %s."
+ "[%s] Could not compute the watch wear window ending %s."
+ "[%s] Could not read the Mulberry gate; reporting ineligible: %@"
+ "[%s] Could not read the health assessment; leaving its counts unset: %@"
+ "[%s] Database locked for %{public}s; parked without spending an attempt."
+ "[%s] Database locked mid-generation; parking %ld experience(s) until it is reachable: %@"
+ "[%s] Database reachability changed; retrying %ld parked experience(s)."
+ "[%s] Database retry armed for %ld experience(s)."
+ "[%s] Failed to count days with Apple Watch stand hours: %@"
+ "[%s] Failed to count fitness routine survey responses: %@"
+ "[%s] Failed to gather the Tab 2 snapshot: %@"
+ "[%s] Failed to read the sleep schedule model: %@"
+ "[HealthAgeDailyAnalytics] Evaluation exceeded its budget; reporting settings fields only"
+ "[HealthAgeDailyAnalytics] Evaluation failed: %{public}@"
+ "[HealthAgeDailyAnalytics] Watch-sample probe failed: %{public}@"
+ "awaitingDatabase"
+ "date input "
- "A quick check-in can help you notice changes in how you're feeling."
- "Building upper body and core strength supports daily activities and long-term mobility."
- "Complete your anxiety check-in for a full picture."
- "Complete your balance evaluation to see your full results."
- "Complete your mood check-in to stay aware of your wellbeing."
- "Finish your cardio fitness evaluation for a complete picture."
- "Finish your heart and lung evaluation for your full cardiovascular picture."
- "Finish your nutrition assessment to get personalized suggestions."
- "Finish your stress assessment to track your progress."
- "Get a blood draw to understand your general and metabolic health."
- "Good balance helps prevent falls and supports coordination in everyday movement."
- "Pick up where you left off on your flexibility assessment."
- "Pick up where you left off to complete your sleep assessment."
- "Record an ECG to check your heart rhythm from your wrist."
- "Reflect on what's going well and build on your strengths."
- "Regular flexibility work can help reduce stiffness and improve your range of motion."
- "Regular mood check-ins help you stay aware of your mental wellbeing over time."
- "Review your activity habits to find opportunities for improvement."
- "Review your daily habits that support mental and physical wellbeing."
- "Take a few minutes to check in on this area of your health."
- "Take a quick check-in on your eating habits to get personalized suggestions."
- "Test your hearing to catch changes early."
- "Track your height, weight, and body composition over time."
- "Tracking stress levels helps you spot triggers and build better coping strategies."
- "Understand your sleep habits and get better suggestions."
- "Understanding your cardio fitness level helps you train at the right intensity."
- "Understanding your heart and lung health is key to staying active and healthy."
- "You've started your strength evaluation — finish to see your results."
- "[%s] Mulberry unavailable; contributing nothing."
- "generatedSentence"
```
