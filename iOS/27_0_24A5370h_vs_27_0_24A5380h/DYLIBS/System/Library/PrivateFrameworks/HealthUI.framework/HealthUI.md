## HealthUI

> `/System/Library/PrivateFrameworks/HealthUI.framework/HealthUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x43c3f0` | `0x44b090` | **`+0xeca0`** |
| `__AUTH_CONST.__const` | `0x84b8` | `0x8bf0` | **`+0x738`** |
| `__TEXT.__swift5_capture` | `0x1150` | `0x14a4` | **`+0x354`** |
| `__TEXT.__eh_frame` | `0x3058` | `0x3388` | **`+0x330`** |
| `__TEXT.__unwind_info` | `0xf110` | `0xf368` | **`+0x258`** |
| `__AUTH_CONST.__objc_const` | `0x66040` | `0x66280` | **`+0x240`** |
| `__TEXT.__cstring` | `0x2312f` | `0x2330f` | **`+0x1e0`** |
| `__TEXT.__objc_methlist` | `0x3b27c` | `0x3b3c4` | **`+0x148`** |
| `__TEXT.__swift5_reflstr` | `0x3066` | `0x31a6` | **`+0x140`** |
| `__DATA_CONST.__got` | `0x3768` | `0x3850` | **`+0xe8`** |
| `__TEXT.__oslogstring` | `0x7385` | `0x7455` | **`+0xd0`** |
| `__DATA.__data` | `0x8220` | `0x82d8` | **`+0xb8`** |
| `__DATA_DIRTY.__objc_data` | `0x15e0` | `0x1680` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x18a10` | `0x18aa0` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x3488` | `0x3516` | **`+0x8e`** |
| `__TEXT.__swift5_fieldmd` | `0x3078` | `0x3100` | **`+0x88`** |
| `__AUTH.__objc_data` | `0x18368` | `0x183e0` | **`+0x78`** |
| `__TEXT.__const` | `0x8d44` | `0x8db4` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0x3078` | `0x30d8` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x4e84` | `0x4ec8` | **`+0x44`** |
| `__TEXT.__swift_as_cont` | `0x11c` | `0x158` | **`+0x3c`** |
| `__TEXT.__gcc_except_tab` | `0x23a4` | `0x23d4` | **`+0x30`** |
| `__AUTH.__data` | `0x2628` | `0x2640` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x7978` | `0x7990` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0x6c` | `0x84` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x7c` | `0x90` | **`+0x14`** |
| `__DATA.__bss` | `0x70c0` | `0x70b0` | **`-0x10`** |
| `__DATA.__common` | `0x250` | `0x260` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x48` | `0x58` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x4054` | `0x405c` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x21a8` | `0x21b0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x3f0` | `0x3f4` | **`+0x4`** |

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

-  Functions: 26132
-  Symbols:   35603
-  CStrings:  5300
+  Functions: 26351
+  Symbols:   35635
+  CStrings:  5314
Symbols:
+ +[HKSettingsAuthorizationFactory authorizationViewControllerWithSource:sourceAuthorizationController:healthStore:shareDescription:updateDescription:researchStudyUsageDescription:storedDataViewControllerProvider:backgroundAppRefreshStatusProvider:]
+ -[HKAuthorizationSettingsViewController _rebuildReadingTypeOrdering]
+ -[HKAuthorizationSettingsViewController _recomputeReadingOrderingAndSections]
+ -[HKAuthorizationSettingsViewController _shouldHideDocumentRowInReadingSection]
+ -[HKAuthorizationSettingsViewController authorizationControllerDidReloadDocumentAuthorizations:]
+ -[HKAuthorizationSettingsViewController commitPendingAuthorizationsWithCompletion:]
+ -[HKCalendarScrollViewController _frameForWeekView:atOriginY:]
+ -[HKInteractiveChartViewController objectTypeForDisplayType:]
+ -[HKSourceAuthorizationController _clampEnabledReadingSubtypeModesToParents]
+ -[HKSourceAuthorizationController _readingWindowForType:exceedsLimitedWindowStartingAt:]
+ -[HKSourceAuthorizationController _setAuthorizationStatuses:completion:]
+ -[HKSourceAuthorizationController _stagedReadingModeForType:]
+ -[HKSourceAuthorizationController _updateAuthorizationStatusWithTypes:completion:]
+ -[HKSourceAuthorizationController commitAuthorizationStatusesForTypes:]
+ -[HKSourceAuthorizationController commitAuthorizationStatusesWithCompletion:]
+ -[HKSourceAuthorizationController enabledSubtypesForType:inSection:]
+ -[HKSourceAuthorizationController setEnabled:forTypes:inSection:commit:]
+ GCC_except_table131
+ GCC_except_table139
+ GCC_except_table60
+ _OBJC_CLASS_$__TtCO8HealthUI17WorkoutZonesCells7Default
+ _OBJC_IVAR_$_HKAuthorizationSettingsViewController._shouldCommitOnFinish
+ _OBJC_IVAR_$_HKCalendarScrollViewController._lastLayoutHorizontalSafeArea
+ _OBJC_METACLASS_$__TtCO8HealthUI17WorkoutZonesCells7Default
+ __DATA__TtCO8HealthUI17WorkoutZonesCells7Default
+ __INSTANCE_METHODS__TtCO8HealthUI17WorkoutZonesCells7Default
+ __METACLASS_DATA__TtCO8HealthUI17WorkoutZonesCells7Default
+ __OBJC_$_INSTANCE_METHODS__TtC8HealthUI37HKSettingsAuthorizationViewController(HealthUI|HealthUI1|HealthUI2)
+ __OBJC_CLASS_PROTOCOLS_$__TtC8HealthUI37HKSettingsAuthorizationViewController(HealthUI|HealthUI1|HealthUI2)
+ ___70-[HKSourceAuthorizationController _reloadDocumentAuthorizationRecords]_block_invoke_2
+ ___72-[HKSourceAuthorizationController _setAuthorizationStatuses:completion:]_block_invoke
+ ___83-[HKAuthorizationSettingsViewController commitPendingAuthorizationsWithCompletion:]_block_invoke
+ ___block_descriptor_48_e8_32bs40w_e20_v20?0B8"NSError"12lw40l8s32l8
+ ___swift_closure_destructor.18Tm
+ ___swift_closure_destructor.67Tm
+ ___swift_closure_destructor.74Tm
+ _swift_release_x12
+ _symbolic SaySo12HKObjectTypeCG
+ _symbolic SaySo18NSLayoutConstraintCG
+ _symbolic So7NSErrorCSgIeyBhy_
+ _symbolic _____ 8HealthUI17WorkoutZonesCellsO7DefaultC
+ _symbolic _____Sg 9HealthKit31DarwinNotificationObserverTokenC
+ _symbolic _____SgXw 8HealthUI51ClinicalAuthorizationAccountsOverviewViewControllerC
+ _symbolic _____SgXwz_Xx 8HealthUI51ClinicalAuthorizationAccountsOverviewViewControllerC
+ _symbolic ______pSgIeghg_ s5ErrorP
+ _symbolic _____yScTyyt_____GSgG 15Synchronization5MutexVAARi_zrlE s5NeverO
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 8HealthUI016Xoroshiro256StarF033_C2E9D1CDEE51921DD7A4542007EFF122LLV
- +[HKSettingsAuthorizationFactory authorizationViewControllerWithSource:sourceAuthorizationController:healthStore:shareDescription:updateDescription:storedDataViewControllerProvider:backgroundAppRefreshStatusProvider:]
- -[HKSourceAuthorizationController _commitAuthorizationStatuses:authorizationModes:modeInfo:]
- -[HKSourceAuthorizationController _setAuthorizationStatuses:]
- -[HKSourceAuthorizationController _updateAuthorizationStatusWithTypes:]
- GCC_except_table138
- __OBJC_$_INSTANCE_METHODS__TtC8HealthUI37HKSettingsAuthorizationViewController(HealthUI|HealthUI1)
- __OBJC_CLASS_PROTOCOLS_$__TtC8HealthUI37HKSettingsAuthorizationViewController(HealthUI|HealthUI1)
- ___61-[HKSourceAuthorizationController _setAuthorizationStatuses:]_block_invoke
- ___92-[HKSourceAuthorizationController _commitAuthorizationStatuses:authorizationModes:modeInfo:]_block_invoke
- ___block_descriptor_48_e8_32s40s_e55_v32?0"_HKAuthorizationModeInfo"8"NSDictionary"16^B24ls32l8s40l8
- ___swift_closure_destructor.13Tm
- _get_type_metadata 15Synchronization5MutexVy8HealthUI016Xoroshiro256StarF033_C2E9D1CDEE51921DD7A4542007EFF122LLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVyScTyyts5NeverOGSgG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic _____Sg 9HealthKit27HKPreferredWorkoutZoneStoreV
CStrings:
+ "%s returned to foreground, reloading accounts list"
+ "ALLOW_%@_TO_UPDATE_TITLECASED"
+ "AUTHORIZATION_CHARACTERISTICS_CATEGORY_HEADER"
+ "AUTHORIZATION_STATUS_LIMIT_%@"
+ "AUTHORIZATION_STATUS_RAISE_%@_TO_FULL"
+ "AUTHORIZATION_STATUS_RAISE_%@_TO_LIMITED"
+ "CYCLING_POWER_CONFIGURATION_WATTS_UNIT"
+ "Failed to fetch cycling power zone config: %{public}s"
+ "Failed to save CyclingPowerZonesConfiguration: %{public}s"
+ "LIMITING_%@_WILL_ALSO_LIMIT_%@"
+ "RAISING_%@_TO_FULL_WILL_RAISE_%@_TO_FULL"
+ "RAISING_%@_TO_LIMITED_WILL_RAISE_%@_TO_LIMITED"
+ "TIME_BOUNDED_AUTH_DISTINCT_DAYS_%ld"
+ "[CyclingPowerZones] Unsupported configurationType: %{public}s"
+ "queryDayDatesWithData(for:since:healthStore:)"
+ "queryEarliestSampleDate(for:healthStore:)"
- "Failed to fetch cycling power zone config: %@"
- "v32@?0@\"_HKAuthorizationModeInfo\"8@\"NSDictionary\"16^B24"
```
