## Home

> `/private/var/staged_system_apps/Home.app/Home`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc0a60` | `0xc04a8` | **`-0x5b8`** |
| `__DATA_CONST.__cfstring` | `0x3080` | `0x31a0` | **`+0x120`** |
| `__TEXT.__cstring` | `0x6fa2` | `0x70c2` | **`+0x120`** |
| `__TEXT.__eh_frame` | `0x29d0` | `0x2950` | **`-0x80`** |
| `__TEXT.__oslogstring` | `0x70f3` | `0x7163` | **`+0x70`** |
| `__TEXT.__objc_stubs` | `0xba60` | `0xbac0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x7178` | `0x7128` | **`-0x50`** |
| `__TEXT.__auth_stubs` | `0x3420` | `0x33e0` | **`-0x40`** |
| `__TEXT.__const` | `0x3384` | `0x3354` | **`-0x30`** |
| `__TEXT.__objc_methname` | `0x13121` | `0x13151` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x12bc` | `0x1290` | **`-0x2c`** |
| `__DATA_CONST.__auth_got` | `0x1a20` | `0x1a00` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x2ac8` | `0x2aa8` | **`-0x20`** |
| `__DATA.__objc_const` | `0x77b8` | `0x77a0` | **`-0x18`** |
| `__DATA.__objc_selrefs` | `0x44d0` | `0x44e8` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0xb40` | `0xb50` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x4ffa` | `0x5008` | **`+0xe`** |
| `__DATA.__data` | `0x53dc` | `0x53e4` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x12b0` | `0x12a8` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x1298` | `0x12a0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x594c` | `0x5944` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x1a4` | `0x19c` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0xb8` | `0xb4` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0xb4` | `0xb0` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1238.0.0.0.0
+1241.1.7.1.2

-  Functions: 3958
-  Symbols:   1793
-  CStrings:  4447
+  Functions: 3949
+  Symbols:   1790
+  CStrings:  4460
Symbols:
+ _$s6HomeUI14AccessorySetupO014DefaultPendingD9ValidatorVMn
+ _$s6HomeUI14AccessorySetupO17WarmUpCoordinatorC19prefetchAndValidate_2inySay0C0QzG_0A0QztF
+ _$s6HomeUI14AccessorySetupO17WarmUpCoordinatorC5resetyyF
+ _$s6HomeUI14AccessorySetupO17WarmUpCoordinatorCAaC22LockOnboardingProviderCy_So6HMHomeCSo16HFPinCodeManagerCGRszAC014DefaultPendingD9ValidatorVRs_rlE10productionAEy_AlNGyFZ
+ _$s6HomeUI14AccessorySetupO17WarmUpCoordinatorCMn
- _$s6HomeUI14AccessorySetupO22LockOnboardingProviderC8prefetch2in16needsPinCodeData0J14WalletKeyStateyx_S2btYaF
- _$s6HomeUI14AccessorySetupO22LockOnboardingProviderC8prefetch2in16needsPinCodeData0J14WalletKeyStateyx_S2btYaFTu
- _$s6HomeUI14AccessorySetupO22LockOnboardingProviderCAASo6HMHomeCRszSo16HFPinCodeManagerCRs_rlE6sharedAEy_AgIGvgZ
- _$s6HomeUI23AppleIntelligenceHelperC30isReduceNotificationsAvailableSbvgZ
- _$s6HomeUI23AppleIntelligenceHelperCMa
- _$s7HomeUI223LivePlaybackEnvironmentC27quickSearchEnabledByDefaultSbvsZ
- _$s7HomeUI223LivePlaybackEnvironmentCMa
- _swift_retain_n
CStrings:
+ "HONewFeaturesView_Caption"
+ "HONewFeaturesView_Description_Attribution"
+ "HONewFeaturesView_Description_CameraExperience"
+ "HONewFeaturesView_Description_CameraSummaries"
+ "HONewFeaturesView_Description_ReducedNotifications"
+ "HONewFeaturesView_Subtitle_Attribution"
+ "HONewFeaturesView_Subtitle_CameraExperience"
+ "HONewFeaturesView_Subtitle_CameraSummaries"
+ "HONewFeaturesView_Subtitle_ReducedNotifications"
+ "accessorySetupWarmUp"
+ "batteryState"
+ "bell.badge"
+ "isProtectedDataAvailable"
+ "no need to preload DashboardViewController due to selectedTab: %s isLaunchedFromBackgroundTask: %{bool}d"
+ "person"
+ "preloading DashboardViewController before presenting it"
+ "setBatteryMonitoringEnabled:"
+ "setCaptionText:"
+ "setPresentedWhileAppBackgrounded:"
+ "supportsOnDeviceCaptionPlayback"
+ "video"
- "HONewFeaturesView_Description_HomeIntelligence"
- "HONewFeaturesView_Subtitle_HomeIntelligence"
- "Prefetching lock onboarding data for home: %s for %ld lock(s)"
- "apple.intelligence"
- "isReduceNotificationsAvailable"
- "lastPrefetchedLockIDs"
- "supportsAccessCodes"
- "supportsWalletKey"
```
