## AssistantServices

> `/System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a0e88` | `0x1a268c` | **`+0x1804`** |
| `__TEXT.__oslogstring` | `0xf8f8` | `0xfbb3` | **`+0x2bb`** |
| `__TEXT.__cstring` | `0x3da93` | `0x3dc51` | **`+0x1be`** |
| `__AUTH_CONST.__const` | `0x3ca0` | `0x3dc0` | **`+0x120`** |
| `__DATA.__data` | `0x48c0` | `0x4988` | **`+0xc8`** |
| `__DATA.__bss` | `0x13b8` | `0x1470` | **`+0xb8`** |
| `__AUTH_CONST.__objc_const` | `0x366a8` | `0x36758` | **`+0xb0`** |
| `__TEXT.__objc_methlist` | `0x1f374` | `0x1f404` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x8228` | `0x8290` | **`+0x68`** |
| `__DATA_CONST.__const` | `0x8738` | `0x8788` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x28820` | `0x28860` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xc240` | `0xc280` | **`+0x40`** |
| `__AUTH.__data` | `0x248` | `0x280` | **`+0x38`** |
| `__DATA_DIRTY.__bss` | `0x1f8` | `0x1c8` | **`-0x30`** |
| `__AUTH_CONST.__objc_intobj` | `0x2718` | `0x2730` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x5f8` | `0x608` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xad8` | `0xae0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x16f8` | `0x1700` | **`+0x8`** |

### Other Changes

```diff

-3605.24.1.1.1
+3605.30.1.1.1

-  Functions: 12191
-  Symbols:   22344
-  CStrings:  8665
+  Functions: 12227
+  Symbols:   22414
+  CStrings:  8694
Symbols:
+ +[AFFeatureFlags(SWEFeatureFlags) isLinwoodModalityConnectionSkipEnabled]
+ -[AFPreferences assistantEnabledBeforeRestrictionIsCurrentVersion]
+ -[AFPreferences fetchUseWithSiriEnabledForApp:completion:]
+ -[AFPreferences fetchUseWithSiriStateForApp:completion:]
+ -[AFPreferences updateUseWithSiriEnabled:forApp:]
+ GCC_except_table10149
+ GCC_except_table10258
+ GCC_except_table10269
+ GCC_except_table10302
+ GCC_except_table10305
+ GCC_except_table10381
+ GCC_except_table10385
+ GCC_except_table10395
+ GCC_except_table10406
+ GCC_except_table10419
+ GCC_except_table10504
+ GCC_except_table10506
+ GCC_except_table10530
+ GCC_except_table10646
+ GCC_except_table10709
+ GCC_except_table10712
+ GCC_except_table10716
+ GCC_except_table10733
+ GCC_except_table10747
+ GCC_except_table10821
+ GCC_except_table10879
+ GCC_except_table10905
+ GCC_except_table11180
+ GCC_except_table11326
+ GCC_except_table11339
+ GCC_except_table11384
+ GCC_except_table11478
+ GCC_except_table11717
+ GCC_except_table12041
+ GCC_except_table12175
+ GCC_except_table12178
+ GCC_except_table12180
+ GCC_except_table7019
+ GCC_except_table7021
+ GCC_except_table7024
+ GCC_except_table7033
+ GCC_except_table7095
+ GCC_except_table7116
+ GCC_except_table7141
+ GCC_except_table7147
+ GCC_except_table7297
+ GCC_except_table7301
+ GCC_except_table7303
+ GCC_except_table7306
+ GCC_except_table7312
+ GCC_except_table7316
+ GCC_except_table7322
+ GCC_except_table7572
+ GCC_except_table7585
+ GCC_except_table7589
+ GCC_except_table7601
+ GCC_except_table7605
+ GCC_except_table7718
+ GCC_except_table7720
+ GCC_except_table7794
+ GCC_except_table7838
+ GCC_except_table8202
+ GCC_except_table8209
+ GCC_except_table8215
+ GCC_except_table8217
+ GCC_except_table8219
+ GCC_except_table8264
+ GCC_except_table8266
+ GCC_except_table8272
+ GCC_except_table8278
+ GCC_except_table8282
+ GCC_except_table8288
+ GCC_except_table8295
+ GCC_except_table8297
+ GCC_except_table8302
+ GCC_except_table8304
+ GCC_except_table8309
+ GCC_except_table8321
+ GCC_except_table8324
+ GCC_except_table8338
+ GCC_except_table8340
+ GCC_except_table8342
+ GCC_except_table8344
+ GCC_except_table8346
+ GCC_except_table8348
+ GCC_except_table8350
+ GCC_except_table8396
+ GCC_except_table8422
+ GCC_except_table8479
+ GCC_except_table8515
+ GCC_except_table8918
+ GCC_except_table9207
+ GCC_except_table9406
+ GCC_except_table9414
+ GCC_except_table9472
+ GCC_except_table9848
+ GCC_except_table9852
+ GCC_except_table9897
+ GCC_except_table9903
+ GCC_except_table9928
+ GCC_except_table9934
+ _AFUseWithSiriAvailableForApp
+ _AFUseWithSiriEnabledForApp
+ _AFUseWithSiriSetEnabled
+ _CFBundleCreate
+ _IntentsLibrary.sLib
+ _IntentsLibrary.sOnce
+ _LSBundleProxyFunction
+ _LSSystemApplicationTypeFunction
+ _OBJC_CLASS_$_NSExtension
+ _TCCLibrary.sLib
+ _TCCLibrary.sOnce
+ __AFCopyBundleForAppID
+ __AFPreferencesCachedLanguageValue
+ __AFPreferencesLanguageCacheGenerationForTesting
+ __AFPreferencesObserveLanguageChanges.observerOnceToken
+ __AFPreferencesSetLanguageCacheDidComputeHookForTesting
+ __OBJC_$_CLASS_METHODS_AFVoiceInfo(SiriTTSServiceAdditions|VSAdditions|AFLocalizationAdditions)
+ __OBJC_$_INSTANCE_METHODS_AFCompanionDeviceInfo(AFCompanionDeviceInfoMutability|BackwardCompatibility)
+ __OBJC_$_INSTANCE_METHODS_AFVoiceInfo(SiriTTSServiceAdditions|VSAdditions|AFLocalizationAdditions)
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AFPreferencesInternalProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AFPreferencesProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AFPreferencesInternalProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AFPreferencesProviding
+ __OBJC_$_PROTOCOL_REFS_AFPreferencesInternalProviding
+ __OBJC_$_PROTOCOL_REFS_AFPreferencesProviding
+ __OBJC_CLASS_PROTOCOLS_$_AFPreferences
+ __OBJC_LABEL_PROTOCOL_$_AFPreferencesInternalProviding
+ __OBJC_LABEL_PROTOCOL_$_AFPreferencesProviding
+ __OBJC_PROTOCOL_$_AFPreferencesInternalProviding
+ __OBJC_PROTOCOL_$_AFPreferencesProviding
+ ___56-[AFPreferences fetchUseWithSiriStateForApp:completion:]_block_invoke
+ ___AFUseWithSiriAvailableForApp_block_invoke
+ ___IntentsLibrary_block_invoke
+ ___TCCLibrary_block_invoke
+ ____AFPreferencesObserveLanguageChanges_block_invoke
+ ____AFPreferencesObserveLanguageChanges_block_invoke_2
+ ___block_descriptor_32_e8_16?0Q8l
+ ___block_descriptor_40_e8_32s_e25_v32?0"NSString"8Q16^B24ls32l8
+ ___block_descriptor_48_e8_32s40bs_e29_v24?0"NSArray"8"NSError"16ls32l8s40l8
+ ___initLSBundleProxy_block_invoke
+ ___initLSSystemApplicationType_block_invoke
+ ___initkTCCInfoGranted_block_invoke
+ ___initkTCCInfoService_block_invoke
+ ___initkTCCServiceSiri_block_invoke
+ _classLSBundleProxy
+ _constantLSSystemApplicationType
+ _constantkTCCInfoGranted
+ _constantkTCCInfoService
+ _constantkTCCServiceSiri
+ _getLSBundleProxyClass
+ _getLSSystemApplicationType
+ _getkTCCInfoGranted
+ _getkTCCInfoService
+ _getkTCCServiceSiri
+ _initLSBundleProxy
+ _initLSBundleProxy.sOnce
+ _initLSSystemApplicationType
+ _initLSSystemApplicationType.sOnce
+ _initTCCAccessCopyInformationForBundle
+ _initTCCAccessSetForBundle
+ _initkTCCInfoGranted
+ _initkTCCInfoGranted.sOnce
+ _initkTCCInfoService
+ _initkTCCInfoService.sOnce
+ _initkTCCServiceSiri
+ _initkTCCServiceSiri.sOnce
+ _kTCCInfoGrantedFunction
+ _kTCCInfoServiceFunction
+ _kTCCServiceSiriFunction
+ _sLanguageCacheDidComputeHookForTesting
+ _sLanguageCachePublished
+ _sLanguageCaches
+ _sSupportedLanguagesGeneration
+ _sSupportedLanguagesGeneration_block_invoke.token
+ _sSupportedLanguagesLock
+ _softLinkTCCAccessCopyInformationForBundle
+ _softLinkTCCAccessSetForBundle
- GCC_except_table10075
- GCC_except_table10077
- GCC_except_table10101
- GCC_except_table10217
- GCC_except_table10280
- GCC_except_table10283
- GCC_except_table10287
- GCC_except_table10304
- GCC_except_table10318
- GCC_except_table10392
- GCC_except_table10450
- GCC_except_table10476
- GCC_except_table10751
- GCC_except_table10897
- GCC_except_table10910
- GCC_except_table10955
- GCC_except_table11049
- GCC_except_table11171
- GCC_except_table11173
- GCC_except_table11176
- GCC_except_table11185
- GCC_except_table11247
- GCC_except_table11268
- GCC_except_table11293
- GCC_except_table11299
- GCC_except_table11449
- GCC_except_table11453
- GCC_except_table11455
- GCC_except_table11458
- GCC_except_table11464
- GCC_except_table11468
- GCC_except_table11474
- GCC_except_table11681
- GCC_except_table12005
- GCC_except_table12139
- GCC_except_table12142
- GCC_except_table12144
- GCC_except_table7179
- GCC_except_table7192
- GCC_except_table7196
- GCC_except_table7208
- GCC_except_table7212
- GCC_except_table7325
- GCC_except_table7327
- GCC_except_table7401
- GCC_except_table7445
- GCC_except_table7807
- GCC_except_table7814
- GCC_except_table7820
- GCC_except_table7822
- GCC_except_table7824
- GCC_except_table7869
- GCC_except_table7871
- GCC_except_table7877
- GCC_except_table7883
- GCC_except_table7887
- GCC_except_table7893
- GCC_except_table7896
- GCC_except_table7898
- GCC_except_table7903
- GCC_except_table7905
- GCC_except_table7910
- GCC_except_table7922
- GCC_except_table7925
- GCC_except_table7939
- GCC_except_table7941
- GCC_except_table7943
- GCC_except_table7945
- GCC_except_table7947
- GCC_except_table7949
- GCC_except_table7951
- GCC_except_table7996
- GCC_except_table8022
- GCC_except_table8079
- GCC_except_table8112
- GCC_except_table8490
- GCC_except_table8779
- GCC_except_table8978
- GCC_except_table8986
- GCC_except_table9044
- GCC_except_table9420
- GCC_except_table9424
- GCC_except_table9469
- GCC_except_table9475
- GCC_except_table9500
- GCC_except_table9506
- GCC_except_table9720
- GCC_except_table9829
- GCC_except_table9840
- GCC_except_table9873
- GCC_except_table9876
- GCC_except_table9952
- GCC_except_table9956
- GCC_except_table9966
- GCC_except_table9977
- GCC_except_table9990
- _AFPreferencesSupportedDictationLanguages.onceToken
- _AFPreferencesSupportedDictationLanguages.sSupportedDictationLanguages
- _AFPreferencesSupportedDictationLanguagesSet.onceToken
- _AFPreferencesSupportedDictationLanguagesSet.stAllLanguagesSet
- _AFPreferencesSupportedLanguages.onceToken
- _AFPreferencesSupportedLanguages.stAllLanguageCodes
- __AFPreferencesDictationLanguagePrefixes.onceToken
- __AFPreferencesDictationLanguagePrefixes.sLanguagePrefixes
- __OBJC_$_CLASS_METHODS_AFVoiceInfo(SiriTTSServiceAdditions|AFLocalizationAdditions|VSAdditions)
- __OBJC_$_INSTANCE_METHODS_AFCompanionDeviceInfo(BackwardCompatibility|AFCompanionDeviceInfoMutability)
- __OBJC_$_INSTANCE_METHODS_AFVoiceInfo(SiriTTSServiceAdditions|AFLocalizationAdditions|VSAdditions)
- ___block_descriptor_32_e25_v32?0"NSString"8Q16^B24l
CStrings:
+ "%s Enumerating apps with an Intents extension to resolve %@"
+ "%s Enumeration returned %lu apps while resolving %@"
+ "%s No bundle for %@, cannot set Use with Siri"
+ "%s No bundle for %@, reporting Use with Siri as off"
+ "%s TCC rejected the Use with Siri write for %@"
+ "%s Use with Siri %@ for %@"
+ "%s Use with Siri available for %@"
+ "%s Use with Siri unavailable for %@: Siri is disabled"
+ "%s Use with Siri unavailable for %@: could not enumerate apps with an Intents extension: %@"
+ "%s Use with Siri unavailable for %@: language %@ not supported (%@)"
+ "%s Use with Siri unavailable for %@: no SiriKit Intents extension among %lu candidates"
+ "%s Use with Siri unavailable for %@: the Intents app enumeration is unavailable"
+ "/System/Library/PrivateFrameworks/TCC.framework/TCC"
+ "@16@?0Q8"
+ "AFUseWithSiriAvailableForApp"
+ "AFUseWithSiriAvailableForApp_block_invoke"
+ "AFUseWithSiriEnabledForApp"
+ "AFUseWithSiriSetEnabled"
+ "Assistant Enabled Before Restriction Version"
+ "LSBundleProxy"
+ "LSSystemApplicationType"
+ "TCCAccessCopyInformationForBundle"
+ "TCCAccessSetForBundle"
+ "com.apple.assistant.siri_settings_did_change"
+ "granted"
+ "kTCCInfoGranted"
+ "kTCCInfoService"
+ "kTCCServiceSiri"
+ "linwood_modality_connection_skip"
+ "revoked"
- "Pull Down Gesture"
```
