## momentsd

> `/usr/libexec/momentsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x261de0` | `0x2625c0` | **`+0x7e0`** |
| `__TEXT.__oslogstring` | `0x3336b` | `0x336eb` | **`+0x380`** |
| `__DATA_CONST.__got` | `0xbc0` | `0xe40` | **`+0x280`** |
| `__TEXT.__cstring` | `0x27a5e` | `0x2798e` | **`-0xd0`** |
| `__TEXT.__objc_stubs` | `0x1e9a0` | `0x1e960` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x5588` | `0x5548` | **`-0x40`** |
| `__TEXT.__objc_methname` | `0x39b68` | `0x39b38` | **`-0x30`** |
| `__TEXT.__objc_methtype` | `0x36a4` | `0x368e` | **`-0x16`** |
| `__DATA.__objc_selrefs` | `0x9988` | `0x9978` | **`-0x10`** |
| `__TEXT.__const` | `0x1470` | `0x1480` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x8304` | `0x82f4` | **`-0x10`** |
| `__DATA.__data` | `0x19c8` | `0x19c0` | **`-0x8`** |
| `__DATA_CONST.__const` | `0xc150` | `0xc148` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x11e8c` | `0x11e84` | **`-0x8`** |
| `__TEXT.__swift5_reflstr` | `0x149` | `0x14a` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_classname`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-412.0.0.0.0
+415.0.0.0.0

-  - /System/Library/PrivateFrameworks/ScreenTimeCore.framework/ScreenTimeCore

-  Symbols:   20149
-  CStrings:  15944
+  Symbols:   20142
+  CStrings:  15945
Symbols:
+ +[MOSummarizationUtilities bundlesWithNonPlaceResourcesFromWorkoutResources:photoResources:mediaResources:emotionResources:]
+ +[MOSummarizationUtilities getPhotoMediaEmotionResourcesForOutingSummaryBundleWithPhotoResources:mediaResources:emotionResources:shouldUpLevelPhoto:]
+ +[MOSummarizationUtilities getWorkoutResourcesForOutingSummaryBundle:]
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/Moments/install/TempContent/Objects/Moments.build/momentsd.build/Objects-normal/arm64e/MOMotionManagerKeys.o
+ MOMotionManagerKeys.m
+ ___block_descriptor_112_e8_32s40s48s56s64s72bs80r88r96r_e29_v24?0"NSArray"8"NSError"16lr80l8s32l8s40l8s48l8r88l8s56l8s64l8r96l8s72l8
+ ___block_descriptor_113_e8_32s40s48s56s64s72s80bs88r96r104r_e5_v8?0lr88l8s32l8s40l8s48l8s56l8r96l8s64l8s72l8r104l8s80l8
+ _kMOMotionQueryInterval
+ _objc_msgSend$bundlesWithNonPlaceResourcesFromWorkoutResources:photoResources:mediaResources:emotionResources:
+ _objc_msgSend$getPhotoMediaEmotionResourcesForOutingSummaryBundleWithPhotoResources:mediaResources:emotionResources:shouldUpLevelPhoto:
+ _objc_msgSend$getWorkoutResourcesForOutingSummaryBundle:
- +[MOSummarizationUtilities bundlesWithNonPlaceResourcesFromResourceDicts:photoResources:mediaResources:emotionResources:]
- +[MOSummarizationUtilities getResourcesForOutingSummaryBundleWithWorkoutResources:photoResources:mediaResources:emotionResources:shouldUpLevelPhoto:]
- -[MOOnboardingAndSettingsPersistence _MOStatusFromSTStatus:]
- -[MOOnboardingAndSettingsPersistence fetchScreenTimeEnablementStatus]
- _$s8momentsd18MOAppCategoryUsageC13totalDurationSdvpACTK
- _$s8momentsd18MOAppCategoryUsageC13totalDurationSdvpACTk
- _$s8momentsd18MOAppCategoryUsageC8categorySSvpACTK
- _$s8momentsd18MOAppCategoryUsageC8categorySSvpACTk
- _OBJC_CLASS_$_STManagementState
- ___69-[MOOnboardingAndSettingsPersistence fetchScreenTimeEnablementStatus]_block_invoke
- ___block_descriptor_56_e8_32s40r48r_e20_v24?0q8"NSError"16lr40l8r48l8s32l8
- ___block_descriptor_88_e8_32s40s48s56bs64r72r80r_e5_v8?0ls32l8r64l8r72l8s40l8s48l8r80l8s56l8
- _kMOAnalyticsScreentTimeState
- _objc_msgSend$_MOStatusFromSTStatus:
- _objc_msgSend$bundlesWithNonPlaceResourcesFromResourceDicts:photoResources:mediaResources:emotionResources:
- _objc_msgSend$fetchScreenTimeEnablementStatus
- _objc_msgSend$getResourcesForOutingSummaryBundleWithWorkoutResources:photoResources:mediaResources:emotionResources:shouldUpLevelPhoto:
- _objc_msgSend$screenTimeStateWithCompletionHandler:
CStrings:
+ "%lu stored motion events (%lu within CM window, %lu cached, %lu cached with locations), %lu motion events rehydrated, %lu new motion events fetched for %@ to %@"
+ "Dropping photo/media/emotion resources due to insufficient distribution - keeping place and workout resources only"
+ "Extended retention enabled: %d, cached events beyond CM window: %lu"
+ "INVARIANT VIOLATION: createActivityMegaBundleFromBundles has MOActionTypeWorkout but no MOResourceTypeWorkout in resources, suggestionID=%@"
+ "INVARIANT VIOLATION: createDominantBundleFromBundles has MOActionTypeWorkout but no MOResourceTypeWorkout in resources, suggestionID=%@"
+ "INVARIANT VIOLATION: createOutingMegaBundleFromBundles has MOActionTypeWorkout but no MOResourceTypeWorkout in resources, suggestionID=%@"
+ "Location fetch error for cached motion events: %@"
+ "MOInternalMotionActivityUITreatment"
+ "Phone-sensed motion activity suggestion was rejected from UI because elapsed time >%.2f days: bundleID %@, suggestionID %@, bundleSubType %lu, elapsedTime %.2f"
+ "Stored events partitioned: %lu within CoreMotion window, %lu beyond (cache hits)"
+ "Visit summary non-place distribution gate: total_bundles=%d, with_non_place_resources=%d (%.1f%%), threshold=%.1f%%, include_photo_media_emotion=%d (workouts always included separately)"
+ "bundlesWithNonPlaceResourcesFromWorkoutResources:photoResources:mediaResources:emotionResources:"
+ "getPhotoMediaEmotionResourcesForOutingSummaryBundleWithPhotoResources:mediaResources:emotionResources:shouldUpLevelPhoto:"
+ "getWorkoutResourcesForOutingSummaryBundle:"
- "%lu stored walking events, %lu walking events rehydrated, %lu new walking events fetched for %@ to %@"
- "-[MOOnboardingAndSettingsPersistence fetchScreenTimeEnablementStatus]"
- "/Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Sources/Moments/momentsd/Shared/Core/MOOnboardingAndSettingsPersistence.m"
- "@52@0:8@16@24@32@40B48"
- "Dropping non-place resources due to insufficient distribution - keeping only place resources"
- "Screen Time fetch failed: %@"
- "Visit summary resource filtering: total=%d, with_non_place_resources=%d (%.1f%%), threshold=%.1f%%, include=%d"
- "_MOStatusFromSTStatus:"
- "bundlesWithNonPlaceResourcesFromResourceDicts:photoResources:mediaResources:emotionResources:"
- "fetchScreenTimeEnablementStatus"
- "getResourcesForOutingSummaryBundleWithWorkoutResources:photoResources:mediaResources:emotionResources:shouldUpLevelPhoto:"
- "screenTimeState"
- "screenTimeStateWithCompletionHandler:"
```
