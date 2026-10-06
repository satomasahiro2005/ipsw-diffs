## Health

> `/private/var/staged_system_apps/Health.app/Health`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcb168` | `0xcc18c` | **`+0x1024`** |
| `__DATA.__bss` | `0x7088` | `0x7208` | **`+0x180`** |
| `__TEXT.__auth_stubs` | `0x5460` | `0x55a0` | **`+0x140`** |
| `__TEXT.__constg_swiftt` | `0x3498` | `0x3390` | **`-0x108`** |
| `__DATA_CONST.__const` | `0x5bc0` | `0x5cc0` | **`+0x100`** |
| `__TEXT.__swift5_reflstr` | `0x2409` | `0x2501` | **`+0xf8`** |
| `__TEXT.__objc_stubs` | `0x3500` | `0x35c0` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x56cd` | `0x577d` | **`+0xb0`** |
| `__DATA.__data` | `0x5880` | `0x57d8` | **`-0xa8`** |
| `__DATA.__objc_const` | `0x3758` | `0x37f8` | **`+0xa0`** |
| `__DATA_CONST.__auth_got` | `0x2a38` | `0x2ad8` | **`+0xa0`** |
| `__TEXT.__const` | `0x5834` | `0x58c4` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x2a0f` | `0x2a6a` | **`+0x5b`** |
| `__TEXT.__swift5_fieldmd` | `0x1b9c` | `0x1bf0` | **`+0x54`** |
| `__TEXT.__cstring` | `0x5422` | `0x545e` | **`+0x3c`** |
| `__DATA.__objc_selrefs` | `0x1378` | `0x13b0` | **`+0x38`** |
| `__DATA_CONST.__auth_ptr` | `0x10f8` | `0x1128` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x14b8` | `0x14d8` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x224c` | `0x222c` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0x27aa` | `0x27c4` | **`+0x1a`** |
| `__DATA.__objc_data` | `0x2238` | `0x2250` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x550` | `0x568` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x26d0` | `0x26e8` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x13d0` | `0x13dc` | **`+0xc`** |
| `__TEXT.__swift5_proto` | `0x3d4` | `0x3e0` | **`+0xc`** |
| `__DATA.__common` | `0x530` | `0x528` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0xe3c` | `0xe34` | **`-0x8`** |
| `__TEXT.__objc_methtype` | `0x1d55` | `0x1d59` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x1f4` | `0x1f8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_classname`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

+  - /System/Library/PrivateFrameworks/HealthBalanceUI.framework/HealthBalanceUI

+  - /System/Library/PrivateFrameworks/WorkoutUI.framework/WorkoutUI

-  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  Functions: 3628
-  Symbols:   2377
-  CStrings:  1681
+  Functions: 3641
+  Symbols:   2401
+  CStrings:  1694
Symbols:
+ _$s14HealthPlatform11ContentKindO09spotlightC0yA2CmFWC
+ _$s14HealthPlatform20TabPopToRootHandlingMp
+ _$s14HealthPlatform20TabPopToRootHandlingP03popeF0yyFTj
+ _$s18HealthExperienceUI17MicaAnimationViewC0E0V11PackageTypeO7archiveyA2GmFWC
+ _$s18HealthExperienceUI17MicaAnimationViewC0E0V11PackageTypeOMa
+ _$s18HealthExperienceUI17MicaAnimationViewC0E0V4name6bundle16supportsDarkMode0I11RightToLeft0I16NumberingSystems0I3Pad11packageType21maxStateWithDurations0T9LoopCount12initialDelay07restartX8DurationAESS_So8NSBundleCS4bAE07PackageS0OAE0euV8DurationOSiS2dSgtcfC
+ _$s18HealthExperienceUI18SnapshotDataSourcePAAE23withLayoutConfiguration_21collapseEmptySectionsAA0ef4WithH0CyxGAA0hI0V_SbtF
+ _$s18HealthExperienceUI25TimeBoundMappedDataSourceC06healthB5Store12contentKinds14sourceProfiles19categoryIdentifiers16dashboardPageIDs12dateProvider18notificationCenterAC0A8Platform0abJ0_p_SayAK11ContentKindOGSayAK0H7ProfileOGSaySSGSgAT10Foundation4DateVycSo014NSNotificationW0Ctcfc
+ _$s18HealthFoundationUI12SelectorItemVAA05SwiftC09EmptyViewVRs0_rlE5value4tint5title4iconACyxq_AFq1_Gx_AD5ColorVSgq_yXEq1_yXEtcfC
+ _$s18HealthFoundationUI12SelectorItemVyxq_q0_q1_GAA0D10BarContentAAMc
+ _$s24HealthPlatformFoundation18LocationPrefetcherC5cache15locationFetcherAcA0D7Caching_p_AA0D8Fetching_ptcfc
+ _$s24HealthPlatformFoundation18LocationPrefetcherC8prefetchyyF
+ _$s24HealthPlatformFoundation18LocationPrefetcherCMa
+ _$s24HealthPlatformFoundation18LocationPrefetcherCMn
+ _$s24HealthPlatformFoundation19LiveLocationFetcherCAA0E8FetchingAAWP
+ _$s24HealthPlatformFoundation19LiveLocationFetcherCACycfc
+ _$s24HealthPlatformFoundation19LiveLocationFetcherCMa
+ _$s24HealthPlatformFoundation23PrefetchedLocationCacheV11healthStoreACSo08HKHealthH0C_tcfC
+ _$s24HealthPlatformFoundation23PrefetchedLocationCacheVAA0E7CachingAAWP
+ _$s24HealthPlatformFoundation23PrefetchedLocationCacheVMa
+ _$s5UIKit26UIListContentConfigurationV15ImagePropertiesV9tintColorSo7UIColorCSgvs
+ _$s5UIKit26UIListContentConfigurationV15imagePropertiesAC05ImageF0VvM
+ _$s7SwiftUI9CalistogaV9isEnabledSbvgZ
+ _$sSo16UITabSidebarItemC5UIKitE7ContentO3tabyAESo0A0CcAEmFWC
+ _$sSo16UITabSidebarItemC5UIKitE7ContentOMa
+ _$sSo23UITabSidebarItemRequestC5UIKitE7contentSo0abC0CACE7ContentOvg
+ _$sSo26UIImageSymbolConfigurationC18HealthExperienceUIE07sidebarB6ConfigABvgZ
+ _$sSo5UITabC18HealthExperienceUIE17sidebarBrandColorSo7UIColorCSgvg
+ _$sSo5UITabC18HealthExperienceUIE17sidebarBrandColorSo7UIColorCSgvs
+ _objc_retain_x1
+ _objc_retain_x10
- _$s14HealthPlatform11ContentKindO7articleyA2CmFWC
- _$s18HealthExperienceUI17MicaAnimationViewC0E0V4name6bundle16supportsDarkMode0I11RightToLeft0I16NumberingSystems0I3Pad21maxStateWithDurations0R9LoopCount12initialDelay07restartV8DurationAESS_So8NSBundleCS4bAE0esT8DurationOSiS2dSgtcfC
- _$s18HealthExperienceUI25TimeBoundMappedDataSourceC06healthB5Store12contentKinds14sourceProfiles19categoryIdentifiers12dateProvider18notificationCenterAC0A8Platform0abJ0_p_SayAJ11ContentKindOGSayAJ0H7ProfileOGSaySSGSg10Foundation4DateVycSo014NSNotificationT0Ctcfc
- _$s18HealthFoundationUI12SelectorItemV5value4tint5title4iconACyxq_q0_Gx_05SwiftC05ColorVSgq_yXEq0_yXEtcfC
- _$s18HealthFoundationUI12SelectorItemVyxq_q0_GAA0D10BarContentAAMc
- __swift_FORCE_LOAD_$_swiftNaturalLanguage
- _swift_deallocPartialClassInstance
CStrings:
+ "$__lazy_storage_$_locationPrefetcher"
+ "@\"UIColor\"16@?0@\"UITraitCollection\"8"
+ "[%{public}s]: Failed to find resolvedHealthStore, cannot present SelectorBarDemoView"
+ "_systemImageNamed:"
+ "activeAppearance"
+ "appIntentsIndexingInitiated"
+ "applicationDidBecomeActiveWithNotification:"
+ "imageByApplyingSymbolConfiguration:"
+ "initWithDynamicProvider:"
+ "lifecycleManager"
+ "secondaryLabelColor"
+ "setImage:"
+ "setTag:"
+ "square.grid.2x2.fill"
+ "systemImageName"
- "__systemImageNamedSwift:"
- "initWithTabBarSystemItem:tag:"
```
