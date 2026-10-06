## HealthAppHealthDaemon

> `/System/Library/PrivateFrameworks/HealthAppHealthDaemon.framework/HealthAppHealthDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x45da8` | `0x48908` | **`+0x2b60`** |
| `__TEXT.__cstring` | `0x15a6` | `0x1775` | **`+0x1cf`** |
| `__DATA.__data` | `0x1100` | `0x1210` | **`+0x110`** |
| `__DATA_CONST.__got` | `0x758` | `0x868` | **`+0x110`** |
| `__AUTH_CONST.__auth_got` | `0xfe0` | `0x10a8` | **`+0xc8`** |
| `__TEXT.__eh_frame` | `0x2018` | `0x20c8` | **`+0xb0`** |
| `__DATA_CONST.__objc_selrefs` | `0x13d8` | `0x1430` | **`+0x58`** |
| `__AUTH_CONST.__const` | `0x1488` | `0x14d8` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x13e8` | `0x1430` | **`+0x48`** |
| `__TEXT.__const` | `0x2180` | `0x21c0` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1ddc` | `0x1e14` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x3068` | `0x3090` | **`+0x28`** |
| `__DATA_DIRTY.__data` | `0x930` | `0x918` | **`-0x18`** |
| `__TEXT.__swift5_reflstr` | `0x598` | `0x5a8` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x67c` | `0x688` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x814` | `0x820` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x638` | `0x640` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x148` | `0x150` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x58` | `0x60` | **`+0x8`** |
| `__TEXT.__swift5_assocty` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x14c` | `0x148` | **`-0x4`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /usr/lib/swift/libswiftCoreImage.dylib

-  Functions: 1614
-  Symbols:   1442
-  CStrings:  302
+  Functions: 1639
+  Symbols:   1485
+  CStrings:  311
Symbols:
+ -[HDHealthAppDailyAnalyticsEvent _domainContributedIHAGatedPayloadWithDataSource:]
+ -[HDHealthAppDailyAnalyticsEvent _domainContributedUnrestrictedPayloadWithDataSource:]
+ _HDSampleEntityPredicateForStartDate
+ _HKCategoryTypeIdentifierAbdominalCramps
+ _HKCategoryTypeIdentifierAcne
+ _HKCategoryTypeIdentifierAppetiteChanges
+ _HKCategoryTypeIdentifierBloating
+ _HKCategoryTypeIdentifierBreastPain
+ _HKCategoryTypeIdentifierCervicalMucusQuality
+ _HKCategoryTypeIdentifierConstipation
+ _HKCategoryTypeIdentifierContraceptive
+ _HKCategoryTypeIdentifierDiarrhea
+ _HKCategoryTypeIdentifierFatigue
+ _HKCategoryTypeIdentifierHeadache
+ _HKCategoryTypeIdentifierHotFlashes
+ _HKCategoryTypeIdentifierIntermenstrualBleeding
+ _HKCategoryTypeIdentifierLactation
+ _HKCategoryTypeIdentifierLowerBackPain
+ _HKCategoryTypeIdentifierMenstrualFlow
+ _HKCategoryTypeIdentifierMoodChanges
+ _HKCategoryTypeIdentifierNausea
+ _HKCategoryTypeIdentifierOvulationTestResult
+ _HKCategoryTypeIdentifierPelvicPain
+ _HKCategoryTypeIdentifierPregnancy
+ _HKCategoryTypeIdentifierPregnancyTestResult
+ _HKCategoryTypeIdentifierProgesteroneTestResult
+ _HKCategoryTypeIdentifierSexualActivity
+ _HKCategoryTypeIdentifierSleepChanges
+ _OBJC_CLASS_$_HDCategorySampleEntity
+ _OBJC_CLASS_$_HDMetadataManager
+ _OBJC_CLASS_$_HDSQLiteCompoundPredicate
+ _OBJC_CLASS_$_HDSQLitePredicate
+ _OBJC_CLASS_$_HDStateOfMindEntity
+ __HKPrivateMetadataKeyWasEnteredFromCycleTracking
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_HealthAppDailyAnalyticsContributing
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HealthAppDailyAnalyticsContributing
+ __OBJC_$_PROTOCOL_REFS_HealthAppDailyAnalyticsContributing
+ __OBJC_LABEL_PROTOCOL_$_HealthAppDailyAnalyticsContributing
+ __OBJC_PROTOCOL_$_HealthAppDailyAnalyticsContributing
+ __OBJC_PROTOCOL_REFERENCE_$_HealthAppDailyAnalyticsContributing
+ ___swift_project_boxed_opaque_existential_0
+ __swift_FORCE_LOAD_$_swiftCoreImage
+ __swift_FORCE_LOAD_$_swiftCoreImage_$_HealthAppHealthDaemon
+ _swift_setDeallocating
+ _symbolic SayypG
+ _symbolic yt
- GCC_except_table7
- _HKQuantityTypeIdentifierBodyMass
- _HKQuantityTypeIdentifierDietaryWater
CStrings:
+ " ORDER BY interaction_date DESC, uuid DESC"
+ "CREATE INDEX IF NOT EXISTS idx_HealthAppDatabaseSchema_user_interactions_feature_item_date ON HealthAppDatabaseSchema_user_interactions (feature_identifier, item_identifier, interaction_date)"
+ "DROP INDEX IF EXISTS idx_HealthAppDatabaseSchema_user_interactions_feature_item"
+ "feature_identifier = ?"
+ "idx_HealthAppDatabaseSchema_user_interactions_feature_item_date"
+ "interaction_date < ?"
+ "interaction_date >= ?"
+ "interaction_type != ''"
+ "interaction_type IN ("
+ "item_identifier IN ("
+ "offset element "
- " WHERE feature_identifier = ? AND item_identifier = ?"
- "idx_HealthAppDatabaseSchema_user_interactions_feature_item"
```
