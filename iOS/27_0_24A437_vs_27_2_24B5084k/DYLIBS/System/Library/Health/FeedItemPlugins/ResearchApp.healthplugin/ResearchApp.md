## ResearchApp

> `/System/Library/Health/FeedItemPlugins/ResearchApp.healthplugin/ResearchApp`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x119a0` | `0xfb14` | **`-0x1e8c`** |
| `__DATA.__bss` | `0x880` | `0x1180` | **`+0x900`** |
| `__DATA_DIRTY.__bss` | `0x980` | `0x80` | **`-0x900`** |
| `__DATA_DIRTY.__data` | `0x630` | `0x118` | **`-0x518`** |
| `__TEXT.__eh_frame` | `0xe0` | `0x570` | **`+0x490`** |
| `__TEXT.__oslogstring` | `0x629` | `0x219` | **`-0x410`** |
| `__TEXT.__const` | `0xa44` | `0xce4` | **`+0x2a0`** |
| `__DATA.__data` | `0x1c0` | `0x448` | **`+0x288`** |
| `__AUTH.__data` | `0x118` | `0x398` | **`+0x280`** |
| `__TEXT.__cstring` | `0x578` | `0x3cc` | **`-0x1ac`** |
| `__TEXT.__swift5_typeref` | `0x250` | `0x3a4` | **`+0x154`** |
| `__AUTH_CONST.__const` | `0x468` | `0x5b8` | **`+0x150`** |
| `__TEXT.__constg_swiftt` | `0x360` | `0x49c` | **`+0x13c`** |
| `__AUTH_CONST.__objc_const` | `0x4f0` | `0x620` | **`+0x130`** |
| `__TEXT.__swift5_fieldmd` | `0x1a8` | `0x2b4` | **`+0x10c`** |
| `__DATA_DIRTY.__objc_data` | `0xe8` | `—` | **`-0xe8`** |
| `__TEXT.__unwind_info` | `0x420` | `0x4f8` | **`+0xd8`** |
| `__AUTH_CONST.__auth_got` | `0x860` | `0x920` | **`+0xc0`** |
| `__AUTH.__objc_data` | `0x200` | `0x288` | **`+0x88`** |
| `__TEXT.__swift5_reflstr` | `0xcb` | `0x149` | **`+0x7e`** |
| `__TEXT.__swift5_capture` | `0xc4` | `0x64` | **`-0x60`** |
| `__TEXT.__swift_as_cont` | `—` | `0x50` | **`+0x50`** |
| `__DATA.__common` | `0x18` | `0x50` | **`+0x38`** |
| `__TEXT.__swift5_assocty` | `0x30` | `0x68` | **`+0x38`** |
| `__TEXT.__swift_as_ret` | `—` | `0x2c` | **`+0x2c`** |
| `__TEXT.__swift_as_entry` | `—` | `0x24` | **`+0x24`** |
| `__DATA_DIRTY.__common` | `0x38` | `0x18` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x228` | `0x240` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x90` | `0xa4` | **`+0x14`** |
| `__TEXT.__swift5_protos` | `—` | `0x14` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x34` | `0x48` | **`+0x14`** |
| `__DATA.__objc_stublist` | `0x10` | `0x8` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x28` | `0x30` | **`+0x8`** |

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

+  - /System/Library/PrivateFrameworks/HealthKitOrchestrationAdditions.framework/HealthKitOrchestrationAdditions
+  - /System/Library/PrivateFrameworks/HealthOrchestration.framework/HealthOrchestration

+  - /System/Library/PrivateFrameworks/HealthPluginHost.framework/HealthPluginHost

+  - /System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry

-  Functions: 355
-  Symbols:   162
-  CStrings:  67
+  Functions: 375
+  Symbols:   167
+  CStrings:  41
Symbols:
+ _OBJC_CLASS_$_HKRegulatoryDomainManager
+ _OBJC_CLASS_$_NRPairedDeviceRegistry
+ _OBJC_CLASS_$_NSNotificationCenter
+ _OBJC_CLASS_$__HKMedicalIDData
+ _objc_retain_x27
+ _swift_allocBox
+ _swift_allocateGenericClassMetadata
+ _swift_conformsToProtocol2
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_deletedAsyncMethodErrorTu
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getGenericMetadata
+ _swift_isaMask
+ _swift_makeBoxUnique
+ _swift_retain_x8
+ _swift_storeEnumTagSinglePayloadGeneric
+ _swift_task_alloc
+ _swift_task_dealloc
+ _swift_task_switch
+ _swift_weakDestroy
+ _swift_weakInit
+ _swift_weakLoadStrong
+ _swift_willThrowTypedImpl
- _OBJC_CLASS_$_LSApplicationWorkspace
- _OBJC_CLASS_$_NSError
- _OBJC_METACLASS_$__TtC18HealthExperienceUI36AnyPlatformFeedItemViewActionHandler
- _os_unfair_lock_lock
- _os_unfair_lock_unlock
- _swift_allocError
- _swift_arrayInitWithTakeBackToFront
- _swift_arrayInitWithTakeFrontToBack
- _swift_bridgeObjectRelease_n
- _swift_cvw_initEnumMetadataMultiPayloadWithLayoutString
- _swift_cvw_multiPayloadEnumGeneric_destructiveInjectEnumTag
- _swift_cvw_multiPayloadEnumGeneric_getEnumTag
- _swift_dynamicCastObjCClass
- _swift_getExistentialMetatypeMetadata
- _swift_release_n
- _swift_release_x25
- _swift_release_x26
- _swift_retain
- _swift_retain_n
- _swift_retain_x25
CStrings:
+ "%s available on App Store"
+ "AMS lookup returned nil responseDataItems"
+ "AMS lookup threw: %@"
+ "App available in the App Store: %{bool}d"
+ "ResearchAppFeedItemGenerator"
+ "[%s.%s] %s promotion tapped."
+ "[%s.%s] healthStore is not primary or could not be recovered from context."
+ "[%s.%s] should not execute on iPad."
+ "app %s is already installed"
+ "applicationAvailabilities"
+ "com.apple.Health.ResearchApp"
+ "com.apple.health.researchApp"
+ "liveAMSLookup(adamID:)"
+ "no plugin app resolved for current state"
+ "research app state: %{public}s"
- "Down-casted Array element failed to match the target type\nExpected "
- "Invalid number of keys found, expected one."
- "LMAppStoreStatePluginStorage"
- "NSArray element failed to match the Swift Array Element type\nExpected "
- "[%s.%s] (%s)"
- "[%s.%s] Caching App Store lookup results: %s : %{bool}d."
- "[%s.%s] Checking if the Research App is in the App Store."
- "[%s.%s] Current user's NSLocale country: %s"
- "[%s.%s] Current user's country is excluded."
- "[%s.%s] Current user's country: %s"
- "[%s.%s] Error: %@."
- "[%s.%s] Failed to lookup App Store availability %@."
- "[%s.%s] Feed Item Changes: %s"
- "[%s.%s] Is the Research App in the App Store? %{bool}d."
- "[%s.%s] No cached App Store lookup."
- "[%s.%s] Previous Feed Items: %s"
- "[%s.%s] Research App State: %s"
- "[%s.%s] Research App is already installed."
- "[%s.%s] Should check App Store again: %{bool}d."
- "[%s.%s] The Research app is already installed on this device, deleting any feed items."
- "[%s.%s] The Research app is not in the App Store, deleting any feed items."
- "[%s.%s] Unable to compute Feed Item Changes: %@"
- "[%s.%s] Unable to determine the current user's country."
- "[%s.%s] Unable to retrieve country: %@."
- "[%s.%s] User Last Active Date: %s."
- "[%s.%s] User is already active, deleting any feed items."
- "[%s.%s] User is inactive, generating reminder feed item."
- "[%s.%s] User was never active, generating promotion feed item."
- "[%s.%s] feed item context did not have plugin data"
- "[%s.%s] feed item context had invalid plugin data"
- "[%s.%s] nil responseDataItems or non-nil error."
- "[%s.%s] promotion tapped."
- "alreadyInstalled"
- "amsLookupPublisher(context:)"
- "appStoreState userState "
- "appStoreStatePublisher(context:)"
- "changes(state:context:)"
- "com.apple.Research.UnitTests"
- "generatePluginFeedItemPublisher(context:locale:)"
- "isCountryExcluded(context:locale:)"
- "userStatePublisher(healthStore:)"
```
