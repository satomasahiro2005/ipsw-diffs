## LocalAuthenticationCore

> `/System/Library/PrivateFrameworks/LocalAuthenticationCore.framework/LocalAuthenticationCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x4800` | `0x76c0` | **`+0x2ec0`** |
| `__DATA_DIRTY.__objc_data` | `0x3cf0` | `0xe38` | **`-0x2eb8`** |
| `__AUTH.__data` | `0x2f08` | `0x24b0` | **`-0xa58`** |
| `__DATA_DIRTY.__data` | `0xf10` | `0x1938` | **`+0xa28`** |
| `__TEXT.__text` | `0x194d1c` | `0x194f2c` | **`+0x210`** |
| `__TEXT.__oslogstring` | `0xaf85` | `0xb0a5` | **`+0x120`** |
| `__TEXT.__cstring` | `0x1085c` | `0x1093a` | **`+0xde`** |
| `__DATA.__bss` | `0x7279` | `0x71a1` | **`-0xd8`** |
| `__AUTH_CONST.__cfstring` | `0x75a0` | `0x7660` | **`+0xc0`** |
| `__TEXT.__const` | `0xae44` | `0xade4` | **`-0x60`** |
| `__TEXT.__objc_methlist` | `0xd378` | `0xd3d8` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x2888` | `0x282c` | **`-0x5c`** |
| `__DATA_CONST.__objc_selrefs` | `0x49a0` | `0x49e8` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x2eec` | `0x2eb8` | **`-0x34`** |
| `__AUTH_CONST.__const` | `0x89c8` | `0x8998` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x55c8` | `0x55f0` | **`+0x28`** |
| `__DATA.__common` | `0x58` | `0x38` | **`-0x20`** |
| `__DATA.__data` | `0x7718` | `0x76f8` | **`-0x20`** |
| `__DATA_DIRTY.__common` | `0x60` | `0x80` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x208e` | `0x206e` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0x4114` | `0x40f8` | **`-0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x1568` | `0x1578` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x208` | `0x218` | **`+0x10`** |
| `__AUTH_CONST.__objc_const` | `0x590c8` | `0x590d0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xd30` | `0xd28` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x44c` | `0x444` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x2c8` | `0x2c0` | **`-0x8`** |

### Other Changes

```diff

-2319.0.16.502.1
+2319.0.33.0.1

-  Symbols:   21975
-  CStrings:  3104
+  Symbols:   21944
+  CStrings:  3117
Symbols:
+ +[LACACMHelper createContext:]
+ +[LACACMHelper createContextWithExternalForm:]
+ +[LACACMHelper createContextWithFlags:contextRef:]
+ +[LACMobileGestalt deviceHasSecureDoublePressHW]
+ +[LACMobileGestalt deviceHasSpecialTouchID]
+ +[LACMobileGestalt deviceHasTouchIDAndSecureDoublePress]
+ +[LACMobileGestalt deviceIsPoseidon]
+ +[LACMobileGestalt deviceSupportsSecureDoubleClick]
+ -[LACDTOBiometryWatchdog initWithIsRunning:time:threshold:]
+ -[LACDTOBiometryWatchdog threshold]
+ -[LACDTOBiometryWatchdogPack watchdogForOptions:]
+ -[LACDTOMutableEnvironment allowsAuthenticationFallbacksForOptions:]
+ GCC_except_table57
+ GCC_except_table59
+ GCC_except_table76
+ GCC_except_table78
+ GCC_except_table80
+ GCC_except_table82
+ GCC_except_table84
+ GCC_except_table86
+ GCC_except_table99
+ _$s23LocalAuthenticationCore37LACAnalyticsContextManagementReporterC06reportE13CreationRetry13originalError05retryL0ySi_SitF
+ _$s23LocalAuthenticationCore37LACAnalyticsContextManagementReporterC06reportE13CreationRetry13originalError05retryL0ySi_SitFTo
+ _$s23LocalAuthenticationCore37LACAnalyticsContextManagementReporterC09analyticsG0014_A90692431F3D3K17C560F240C9A719F89LLSo0dG0_pvpWvd
+ _$s23LocalAuthenticationCore37LACAnalyticsContextManagementReporterC09analyticsG0ACSo0dG0_p_tcfC
+ _$s23LocalAuthenticationCore37LACAnalyticsContextManagementReporterC09analyticsG0ACSo0dG0_p_tcfCTfq4en_n
+ _$s23LocalAuthenticationCore37LACAnalyticsContextManagementReporterC09analyticsG0ACSo0dG0_p_tcfCTj
+ _$s23LocalAuthenticationCore37LACAnalyticsContextManagementReporterC09analyticsG0ACSo0dG0_p_tcfCTq
+ _$s23LocalAuthenticationCore37LACAnalyticsContextManagementReporterC09analyticsG0ACSo0dG0_p_tcfc
+ _$s23LocalAuthenticationCore37LACAnalyticsContextManagementReporterC09analyticsG0ACSo0dG0_p_tcfcTf4en_n
+ _$s23LocalAuthenticationCore37LACAnalyticsContextManagementReporterCMu
+ _$s23LocalAuthenticationCore6LACLogO8sessions2os6LoggerVvgZ
+ _$s23LocalAuthenticationCore6LACLogO8sessions2os6LoggerVvpZMV
+ _CFArrayContainsValue
+ _CFArrayGetCount
+ _LACLogPushButton
+ _LACLogPushButton.__logObj
+ _LACLogPushButton.onceToken
+ _OBJC_IVAR_$_LACDTOBiometryWatchdog._threshold
+ _OBJC_IVAR_$_LACUserInterfaceRemoteUIAdapter._currentRequestId
+ ___48+[LACMobileGestalt deviceHasSecureDoublePressHW]_block_invoke
+ ___51+[LACMobileGestalt deviceSupportsSecureDoubleClick]_block_invoke
+ ___LACLogPushButton_block_invoke
+ ___der_key_group_seed_generation
+ ___der_key_group_seed_kcv
+ ___der_key_group_seed_wrapping_type
+ ___der_key_group_user_count
+ ___der_key_vek_group_seed_generation
+ ___der_key_volume_bag_vek_cache_status
+ _aks_unlock_bag_with_options
+ _der_key_group_seed_generation
+ _der_key_group_seed_kcv
+ _der_key_group_seed_wrapping_type
+ _der_key_group_user_count
+ _der_key_vek_group_seed_generation
+ _der_key_volume_bag_vek_cache_status
+ _deviceHasSecureDoublePressHW.hasSecureDoublePressHW
+ _deviceHasSecureDoublePressHW.onceToken
+ _deviceSupportsSecureDoubleClick.onceToken
+ _deviceSupportsSecureDoubleClick.supportsSecureDoubleClick
+ _kAKSInternalInfoGroupSeedGeneration
+ _kAKSInternalInfoGroupSeedKCV
+ _kAKSInternalInfoGroupSeedWrappingType
+ _kAKSInternalInfoGroupUserCount
+ _kAKSInternalInfoVolumeBagVEKCacheStatus
+ _pdk_generate
+ _symbolic _____yxG 15Synchronization5MutexVAARi_zrlE
- -[LACDTOBiometryWatchdog initWithIsRunning:time:minThreshold:maxThreshold:]
- -[LACDTOBiometryWatchdog isPastBarkingPeriod]
- -[LACDTOBiometryWatchdog maxThreshold]
- -[LACDTOBiometryWatchdog minThreshold]
- -[LACDTOBiometryWatchdogPack isPastBarkingPeriod]
- -[LACDTOMutableEnvironment allowsAuthenticationFallbacks]
- GCC_except_table23
- GCC_except_table32
- GCC_except_table53
- GCC_except_table54
- GCC_except_table73
- GCC_except_table75
- GCC_except_table77
- GCC_except_table79
- GCC_except_table81
- GCC_except_table83
- GCC_except_table93
- _$s15Synchronization5MutexVyytGMR
- _$s15Synchronization5MutexVyytGMd
- _$s23LocalAuthenticationCore37LACAnalyticsContextManagementReporterC09analyticsG0014_A90692431F3D3K17C560F240C9A719F89LLSo0dG0CvpWvd
- _$s23LocalAuthenticationCore41LACDTOAnalyticsReporterCollapseEvaluationC8watchdog33_0DE24F6C74C7BAA3DC3332A943B749AELL3for11environmentSo22LACDTOBiometryWatchdogCSo20LACEvaluationRequest_p_So17LACDTOEnvironment_ptFTf4nnd_n
- _$s23LocalAuthenticationCore9LACLoggerV13dtoEvaluationACvgZ
- _$s23LocalAuthenticationCore9LACLoggerV13dtoEvaluationACvpZMV
- _$s23LocalAuthenticationCore9LACLoggerV14dtoEnvironmentACvgZ
- _$s23LocalAuthenticationCore9LACLoggerV14dtoEnvironmentACvpZMV
- _$s23LocalAuthenticationCore9LACLoggerV2uiACvgZ
- _$s23LocalAuthenticationCore9LACLoggerV2uiACvpZMV
- _$s23LocalAuthenticationCore9LACLoggerV3abmACvgZ
- _$s23LocalAuthenticationCore9LACLoggerV3abmACvgZTm
- _$s23LocalAuthenticationCore9LACLoggerV3abmACvpZMV
- _$s23LocalAuthenticationCore9LACLoggerV3log5level_yAC5LevelO_SStF
- _$s23LocalAuthenticationCore9LACLoggerV3logyySSF
- _$s23LocalAuthenticationCore9LACLoggerV4infoyySSF
- _$s23LocalAuthenticationCore9LACLoggerV5LevelO2eeoiySbAE_AEtFZ
- _$s23LocalAuthenticationCore9LACLoggerV5LevelO4hash4intoys6HasherVz_tF
- _$s23LocalAuthenticationCore9LACLoggerV5LevelO4infoyA2EmFWC
- _$s23LocalAuthenticationCore9LACLoggerV5LevelO5debugyA2EmFWC
- _$s23LocalAuthenticationCore9LACLoggerV5LevelO5erroryA2EmFWC
- _$s23LocalAuthenticationCore9LACLoggerV5LevelO7defaultyA2EmFWC
- _$s23LocalAuthenticationCore9LACLoggerV5LevelO9hashValueSivg
- _$s23LocalAuthenticationCore9LACLoggerV5LevelO9hashValueSivpMV
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOAESQAAWL
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOAESQAAWl
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOMF
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOMa
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOMf
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOMn
- _$s23LocalAuthenticationCore9LACLoggerV5LevelON
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOSHAAMc
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOSHAAMcMK
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOSHAASH13_rawHashValue4seedS2i_tFTW
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOSHAASH4hash4intoys6HasherVz_tFTW
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOSHAASH9hashValueSivgTW
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOSHAASQWb
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOSQAAMc
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOSQAAMcMK
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOSQAASQ2eeoiySbx_xtFZTW
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOWV
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOwet
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOwst
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOwug
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOwui
- _$s23LocalAuthenticationCore9LACLoggerV5LevelOwup
- _$s23LocalAuthenticationCore9LACLoggerV5debugyySSF
- _$s23LocalAuthenticationCore9LACLoggerV5dtoUIACvgZ
- _$s23LocalAuthenticationCore9LACLoggerV5dtoUIACvpZMV
- _$s23LocalAuthenticationCore9LACLoggerV5erroryySSF
- _$s23LocalAuthenticationCore9LACLoggerV5testsACvgZ
- _$s23LocalAuthenticationCore9LACLoggerV5testsACvpZMV
- _$s23LocalAuthenticationCore9LACLoggerV7defaultACvgZ
- _$s23LocalAuthenticationCore9LACLoggerV7defaultACvpZMV
- _$s23LocalAuthenticationCore9LACLoggerV7warningyySSF
- _$s23LocalAuthenticationCore9LACLoggerV8preboardACvgZ
- _$s23LocalAuthenticationCore9LACLoggerV8preboardACvpZMV
- _$s23LocalAuthenticationCore9LACLoggerV9processorACvgZ
- _$s23LocalAuthenticationCore9LACLoggerV9processorACvpZMV
- _$s23LocalAuthenticationCore9LACLoggerVMF
- _$s23LocalAuthenticationCore9LACLoggerVMa
- _$s23LocalAuthenticationCore9LACLoggerVMf
- _$s23LocalAuthenticationCore9LACLoggerVMl
- _$s23LocalAuthenticationCore9LACLoggerVMn
- _$s23LocalAuthenticationCore9LACLoggerVMr
- _$s23LocalAuthenticationCore9LACLoggerVN
- _$s23LocalAuthenticationCore9LACLoggerVWV
- _$s23LocalAuthenticationCore9LACLoggerVwet
- _$s23LocalAuthenticationCore9LACLoggerVwst
- _$s2os6LoggerV23LocalAuthenticationCoreE5dtoUIACvgZ
- _$s2os6LoggerV23LocalAuthenticationCoreE5dtoUIACvpZMV
- _$s2os6LoggerVMn
- _OBJC_IVAR_$_LACDTOBiometryWatchdog._maxThreshold
- _OBJC_IVAR_$_LACDTOBiometryWatchdog._minThreshold
- _associated conformance 23LocalAuthenticationCore9LACLoggerV5LevelOSHAASQ
- _get_type_metadata 15Synchronization5MutexVyytG noncopyable
- _get_type_metadata l15Synchronization5MutexVyxG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic _____ 23LocalAuthenticationCore9LACLoggerV
- _symbolic _____ 23LocalAuthenticationCore9LACLoggerV5LevelO
- _symbolic _____ 2os6LoggerV
CStrings:
+ "%@ not processing dismiss message for rid: %u - id does not match %u"
+ "ACMContextCreateWithExternalForm returned NULL."
+ "ACMContextCreateWithFlags rc=%d."
+ "ACMContextCreateWithFlags rc=0 (after retrying on rc=%d)."
+ "Can't query SecureDoubleClick."
+ "DeviceSupportsSecureDoubleClick"
+ "GroupSeedGeneration"
+ "GroupSeedKCV"
+ "GroupSeedWrappingType"
+ "GroupUserCount"
+ "HardwareSupportsSecureDoubleClick"
+ "VolumeBagVEKCacheStatus"
+ "com.apple.LocalAuthentication.ContextManagement.ContextCreationRetry"
+ "deviceHasSecureDoublePressHW returned %d"
+ "deviceSupportsSecureDoubleClick returned %d"
+ "threshold: %.2f"
- "Unable to create ACM context with status: %d"
- "maxThreshold: %.2f"
- "minThreshold: %.2f"
```
