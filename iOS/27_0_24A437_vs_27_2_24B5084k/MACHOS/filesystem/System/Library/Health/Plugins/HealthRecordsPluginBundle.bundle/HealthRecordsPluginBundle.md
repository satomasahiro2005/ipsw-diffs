## HealthRecordsPluginBundle

> `/System/Library/Health/Plugins/HealthRecordsPluginBundle.bundle/HealthRecordsPluginBundle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a0` | `0x77c` | **`+0x2dc`** |
| `__TEXT.__objc_methname` | `0x3b4` | `0x4f3` | **`+0x13f`** |
| `__TEXT.__objc_stubs` | `0x140` | `0x240` | **`+0x100`** |
| `__DATA.__objc_const` | `0x310` | `0x3d8` | **`+0xc8`** |
| `__TEXT.__auth_stubs` | `0xd0` | `0x160` | **`+0x90`** |
| `__TEXT.__oslogstring` | `—` | `0x63` | **`+0x63`** |
| `__DATA.__data` | `0x240` | `0x2a0` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x158` | `0x1a8` | **`+0x50`** |
| `__DATA_CONST.__got` | `0xe0` | `0x130` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x70` | `0xb8` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x28c` | `0x2cc` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0x93` | `0xc6` | **`+0x33`** |
| `__TEXT.__objc_methtype` | `0x1e2` | `0x212` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x78` | `0x90` | **`+0x18`** |
| `__TEXT.__cstring` | `—` | `0xf` | **`+0xf`** |
| `__DATA_CONST.__objc_catlist` | `—` | `0x8` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__const` | `—` | `0x8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/PrivateFrameworks/HealthAppServices.framework/HealthAppServices

+  - /System/Library/PrivateFrameworks/HealthDaemonFoundation.framework/HealthDaemonFoundation

-  Functions: 12
-  Symbols:   48
-  CStrings:  83
+  Functions: 17
+  Symbols:   68
+  CStrings:  99
Symbols:
+ _HDClinicalAccountEntityPropertySignedClinicalDataIssuerROWID
+ _HDClinicalAccountEntityPropertyUserEnabled
+ _HKLogHealthRecordsCategory
+ _OBJC_CLASS_$_HDClinicalAccountEntity
+ _OBJC_CLASS_$_HDClinicalHealthLinkSyncEntity
+ _OBJC_CLASS_$_HDSQLiteComparisonPredicate
+ _OBJC_CLASS_$_HDSQLiteCompoundPredicate
+ _OBJC_CLASS_$_HDSQLiteNullPredicate
+ _OBJC_CLASS_$_NSDictionary
+ _OBJC_CLASS_$_NSNumber
+ __HKInitializeLogging
+ ___CFConstantStringClassReference
+ ___kCFBooleanTrue
+ __os_log_error_impl
+ _objc_release_x22
+ _objc_release_x23
+ _objc_release_x24
+ _objc_release_x25
+ _objc_retain_x8
+ _os_log_type_enabled
CStrings:
+ "%{public}@: Profile is nil."
+ "@\"NSDictionary\"24@0:8@\"HKAnalyticsDataSource\"16"
+ "DailyAnalytics"
+ "Failed to count CHR accounts for the daily event with error %{public}@"
+ "HealthAppDailyAnalyticsContributing"
+ "countOfObjectsWithPredicate:healthDatabase:error:"
+ "database"
+ "dictionaryWithObjects:forKeys:count:"
+ "isNullPredicateWithProperty:"
+ "isOnboardedCHR"
+ "makeIHAGatedDailyAnalyticsPayloadWithDataSource:"
+ "makeUnrestrictedDailyAnalyticsPayloadWithDataSource:"
+ "numberWithBool:"
+ "predicateMatchingAllPredicates:"
+ "predicateWithProperty:equalToValue:"
+ "profile"
```
