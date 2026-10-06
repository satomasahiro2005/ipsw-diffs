## Home

> `/System/Library/PrivateFrameworks/Home.framework/Home`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3cad28` | `0x3c8a44` | **`-0x22e4`** |
| `__AUTH_CONST.__cfstring` | `0x27440` | `0x275a0` | **`+0x160`** |
| `__TEXT.__cstring` | `0x34e1f` | `0x34f66` | **`+0x147`** |
| `__TEXT.__objc_methlist` | `0x2ca3c` | `0x2cb7c` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x1d91d` | `0x1da48` | **`+0x12b`** |
| `__TEXT.__eh_frame` | `0x7558` | `0x7458` | **`-0x100`** |
| `__AUTH_CONST.__objc_const` | `0x4c570` | `0x4c650` | **`+0xe0`** |
| `__DATA_CONST.__objc_selrefs` | `0x13098` | `0x13130` | **`+0x98`** |
| `__DATA_DIRTY.__data` | `0xf20` | `0xeb0` | **`-0x70`** |
| `__TEXT.__const` | `0x59e0` | `0x5970` | **`-0x70`** |
| `__TEXT.__unwind_info` | `0xebe0` | `0xeb70` | **`-0x70`** |
| `__DATA.__data` | `0x79f8` | `0x79b0` | **`-0x48`** |
| `__TEXT.__gcc_except_tab` | `0x4cf0` | `0x4d2c` | **`+0x3c`** |
| `__AUTH_CONST.__auth_got` | `0x2238` | `0x2208` | **`-0x30`** |
| `__AUTH_CONST.__const` | `0xf4a0` | `0xf470` | **`-0x30`** |
| `__TEXT.__swift5_capture` | `0x10b0` | `0x1080` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0x2d03` | `0x2cd4` | **`-0x2f`** |
| `__DATA_CONST.__const` | `0x11288` | `0x112b0` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x540` | `0x520` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x32c8` | `0x32b0` | **`-0x18`** |
| `__DATA.__bss` | `0x3c60` | `0x3c50` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x268` | `0x258` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x160c` | `0x1614` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x3d0` | `0x3d8` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x227c` | `0x2274` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x288` | `0x280` | **`-0x8`** |
| `__TEXT.__swift5_reflstr` | `0xee0` | `0xee3` | **`+0x3`** |

### Same-size Content Changes

- `__TEXT.__ustring`

### Other Changes

```diff

-1241.1.7.1.3
+1263.1.0.1.2

-  Functions: 21339
-  Symbols:   30322
-  CStrings:  8555
+  Functions: 21297
+  Symbols:   30349
+  CStrings:  8570
Symbols:
+ +[HFUtilities isHomeDemoModeLocked]
+ -[HFAccessoryBuilder removeItemFromHome:]
+ -[HFAccessorySettingDeviceOptionsAdapter identifyAccessorySolo:]
+ -[HFAccessorySettingDeviceOptionsAdapterUtility identifyAccessorySolo:]
+ -[HFAccessorySettingItem _appleTVAccessoryForVendor]
+ -[HFCustomDiffableDataSourceSnapshot reloadItemsWithIdentifiers:]
+ -[HFCustomDiffableDataSourceSnapshot reloadSectionsWithIdentifiers:]
+ -[HFDemoModeAccessoryBuilder removeItemFromHome:]
+ -[HFHomePropertyCacheManager home:didUpdateRoom:forAccessory:]
+ -[HFItemManager pendingBatchProcessCancellationToken]
+ -[HFItemManager setPendingBatchProcessCancellationToken:]
+ -[HFItemManager(HomeKitDelegates) accessory:didUpdateMatterNodeID:]
+ -[HFItemManagersRegistry liveManagers]
+ -[HFMediaSystemBuilder removeItemFromHome:]
+ -[HFServiceBuilder removeItemFromHome:]
+ -[HFServiceGroupBuilder removeItemFromHome:]
+ -[HFSetupAutomaticDiscoveryPairingController _notifyObserversOfAccessoryReTapRequest:]
+ -[HFSetupAutomaticDiscoveryPairingController failureError]
+ -[HFSetupAutomaticDiscoveryPairingController setFailureError:]
+ -[HMAccessory(HFMediaAdditions) hf_identifyHomePodSolo:]
+ -[NSError(HFAdditions) hf_isNFCReaderTooHotError]
+ GCC_except_table147
+ GCC_except_table150
+ GCC_except_table153
+ GCC_except_table156
+ GCC_except_table162
+ GCC_except_table169
+ GCC_except_table185
+ GCC_except_table200
+ GCC_except_table203
+ GCC_except_table57
+ GCC_except_table96
+ _HFAccessoryLikeItemProviderDiffingKey
+ _HFPreferencesSimulateMatterCommandErrorKey
+ _HFPreferencesSimulateMatterCommandErrorStatusKey
+ _HFPreferencesSimulateMatterCommandErrorTypeKey
+ _HFURLComponentsColorCode
+ _OBJC_IVAR_$_HFItemManager._pendingBatchProcessCancellationToken
+ _OBJC_IVAR_$_HFSetupAutomaticDiscoveryPairingController._failureError
+ __OBJC_$_CATEGORY_CLASS_METHODS_HMCHIPEcosystem_$_HFAdditions
+ __OBJC_$_CATEGORY_CLASS_METHODS_HMHomeManager_$_HFAdditions
+ __OBJC_$_CATEGORY_CLASS_METHODS_HMSetting_$_HFAdditions
+ __OBJC_$_CATEGORY_CLASS_METHODS_HMSettings_$_HFAdditions
+ __OBJC_$_CATEGORY_CLASS_METHODS_NSString_$_HFAdditions
+ __OBJC_$_CATEGORY_HMAccessoryNumberSetting_$_HFAdditions
+ __OBJC_$_CATEGORY_HMAccessoryProfile_$_AccessoryLikeObjectDataSource
+ __OBJC_$_CATEGORY_HMAction_$_HFAdditions
+ __OBJC_$_CATEGORY_HMCHIPEcosystem_$_HFAdditions
+ __OBJC_$_CATEGORY_HMCameraSignificantEvent_$_HFAdditions
+ __OBJC_$_CATEGORY_HMCharacteristicEvent_$_HFCharacteristicEventAdditions
+ __OBJC_$_CATEGORY_HMCharacteristicMetadata_$_HFAdditions
+ __OBJC_$_CATEGORY_HMCharacteristicThresholdRangeEvent_$_HFAdditions
+ __OBJC_$_CATEGORY_HMCharacteristicWriteAction_$_HFAdditions
+ __OBJC_$_CATEGORY_HMCharacteristic_$_Additions
+ __OBJC_$_CATEGORY_HMEventTrigger_$_HFAdditions
+ __OBJC_$_CATEGORY_HMHomeManager_$_HFAdditions
+ __OBJC_$_CATEGORY_HMMediaProfile_$_AccessoryLikeObjectDataSource
+ __OBJC_$_CATEGORY_HMMediaSystem_$_AccessoryLikeObjectDataSource
+ __OBJC_$_CATEGORY_HMResidentDevice_$_HFAdditions
+ __OBJC_$_CATEGORY_HMServiceGroup_$_AccessoryLikeObjectDataSource
+ __OBJC_$_CATEGORY_HMService_$_AccessoryLikeObjectDataSource
+ __OBJC_$_CATEGORY_HMSetting_$_HFAdditions
+ __OBJC_$_CATEGORY_HMSettings_$_HFAdditions
+ __OBJC_$_CATEGORY_HMTimerTrigger_$_HFTimerTriggerAdditions
+ __OBJC_$_CATEGORY_HMTrigger_$_HFAdditions
+ __OBJC_$_CATEGORY_HMUser_$_HFAdditions
+ __OBJC_$_CATEGORY_NSArray_$_HFDebugging
+ __OBJC_$_CATEGORY_NSDictionary_$_HFDebugging
+ __OBJC_$_CATEGORY_NSError_$_HFAdditions
+ __OBJC_$_CATEGORY_NSString_$_HFAdditions
+ __OBJC_$_CLASS_METHODS_HFAccessoryTypeGroup(Filtering|Performance)
+ __OBJC_$_CLASS_METHODS_HMAccessory(Home|Home1|AccessoryLikeObjectDataSource|AbstractionAdditions|HFIncludedContextProtocol|HFSymptomFixableObject|HFAdditions|HFMediaAdditions|HFSoftwareUpdateAdditions|HFApplicationData|HFDebugging|HFReordering|HFHomeContainedObjectConformance|HFUserNotificationServiceSettings)
+ __OBJC_$_CLASS_METHODS_HMAccessoryProfile(AccessoryLikeObjectDataSource|AbstractionAdditions|HFAdditions|HFIncludedContextProtocol|HFDebugging|HFHomeKitObjectConformance)
+ __OBJC_$_CLASS_METHODS_HMActionSet(HFFavoritableAdoption|HFIncludedContextProtocol|HFAdditions|HFApplicationData|HFDebugging|HFReordering|HFHomeKitObjectConformance)
+ __OBJC_$_CLASS_METHODS_HMCharacteristic(Additions|HFDebugging|HFHomeKitObjectConformance|HFActionSuggestions)
+ __OBJC_$_CLASS_METHODS_HMEventTrigger(HFAdditions|HFEventTriggerAdditions|HFDebugging|AutomationBuilders|NaturalLanguage)
+ __OBJC_$_CLASS_METHODS_HMHome(Home|AbstractionAdditions|Additions|HFFavoritingAdditions|HFApplicationData|HFDebugging|HFDemoMode|HFReordering|HFHomeKitObjectConformance|HFCharacteristicValueManagerAdditions|HFUserNotificationTopics|PredictionCaching|HFUserHandleAdditions)
+ __OBJC_$_CLASS_METHODS_HMService(AccessoryLikeObjectDataSource|AbstractionAdditions|HFIncludedContextProtocol|Additions|HFProgrammableSwitchAdditions|HFApplicationData|HFDebugging|HFReordering|HFHomeContainedObjectConformance|HFCharacteristicValueDisplayMetadataAdditions|HFUserNotificationServiceSettings)
+ __OBJC_$_CLASS_METHODS_HMTimerTrigger(HFTimerTriggerAdditions|AutomationBuilders|NaturalLanguage)
+ __OBJC_$_CLASS_METHODS_HMTrigger(HFAdditions|HFDebugging|HFHomeKitObjectConformance|AutomationBuilders|NaturalLanguage)
+ __OBJC_$_CLASS_METHODS_NSArray(HFDebugging|HUAdditions|HFAdditions|HFPropertyListConverting|HFUtilities)
+ __OBJC_$_CLASS_METHODS_NSDate(HFAnalytics|Additions|HFPropertyListConverting)
+ __OBJC_$_CLASS_METHODS_NSError(HFAdditions|HFErrorAdditions|HFErrorHandlerAdditions)
+ __OBJC_$_INSTANCE_METHODS_HFAccessoryTypeGroup(Filtering|Performance)
+ __OBJC_$_INSTANCE_METHODS_HFActionSetBuilder(AccessoryLikeObjectContainer|AutomationBuilders|Comparison)
+ __OBJC_$_INSTANCE_METHODS_HFCharacteristicValueManager(Home|Tests|HFLightProfileValueSource)
+ __OBJC_$_INSTANCE_METHODS_HFEventTriggerBuilder(Comparison|AutomationBuilders|LegacyInterfaces)
+ __OBJC_$_INSTANCE_METHODS_HFItemManager(Home|DiffableDataSource|HFDebugging|HomeKitDelegates)
+ __OBJC_$_INSTANCE_METHODS_HFTimerTriggerBuilder(Comparison|AutomationBuilders)
+ __OBJC_$_INSTANCE_METHODS_HFTriggerActionSetsBuilder(Comparison|UI|AutomationBuilders)
+ __OBJC_$_INSTANCE_METHODS_HFTriggerBuilder(Comparison|AutomationBuilders)
+ __OBJC_$_INSTANCE_METHODS_HMAccessory(Home|Home1|AccessoryLikeObjectDataSource|AbstractionAdditions|HFIncludedContextProtocol|HFSymptomFixableObject|HFAdditions|HFMediaAdditions|HFSoftwareUpdateAdditions|HFApplicationData|HFDebugging|HFReordering|HFHomeContainedObjectConformance|HFUserNotificationServiceSettings)
+ __OBJC_$_INSTANCE_METHODS_HMAccessoryNumberSetting(HFAdditions|HFDebugging)
+ __OBJC_$_INSTANCE_METHODS_HMAccessoryProfile(AccessoryLikeObjectDataSource|AbstractionAdditions|HFAdditions|HFIncludedContextProtocol|HFDebugging|HFHomeKitObjectConformance)
+ __OBJC_$_INSTANCE_METHODS_HMAction(HFAdditions|HFDebugging|HFHomeKitObjectConformance)
+ __OBJC_$_INSTANCE_METHODS_HMActionSet(HFFavoritableAdoption|HFIncludedContextProtocol|HFAdditions|HFApplicationData|HFDebugging|HFReordering|HFHomeKitObjectConformance)
+ __OBJC_$_INSTANCE_METHODS_HMCHIPEcosystem(HFAdditions|HFHomeKitObjectConformance)
+ __OBJC_$_INSTANCE_METHODS_HMCameraSignificantEvent(HFAdditions|HFDebugging|HFHomeKitObjectConformance)
+ __OBJC_$_INSTANCE_METHODS_HMCharacteristic(Additions|HFDebugging|HFHomeKitObjectConformance|HFActionSuggestions)
+ __OBJC_$_INSTANCE_METHODS_HMCharacteristicEvent(HFCharacteristicEventAdditions|HFDebugging)
+ __OBJC_$_INSTANCE_METHODS_HMCharacteristicMetadata(HFAdditions|HFDebugging)
+ __OBJC_$_INSTANCE_METHODS_HMCharacteristicThresholdRangeEvent(HFAdditions|HMCharacteristicThresholdRangeEventAdditions|HFDebugging)
+ __OBJC_$_INSTANCE_METHODS_HMCharacteristicWriteAction(HFAdditions|HFDebugging)
+ __OBJC_$_INSTANCE_METHODS_HMEventTrigger(HFAdditions|HFEventTriggerAdditions|HFDebugging|AutomationBuilders|NaturalLanguage)
+ __OBJC_$_INSTANCE_METHODS_HMHome(Home|AbstractionAdditions|Additions|HFFavoritingAdditions|HFApplicationData|HFDebugging|HFDemoMode|HFReordering|HFHomeKitObjectConformance|HFCharacteristicValueManagerAdditions|HFUserNotificationTopics|PredictionCaching|HFUserHandleAdditions)
+ __OBJC_$_INSTANCE_METHODS_HMHomeManager(HFAdditions|HFAdditionsHelper|HFApplicationData|HFDebugging)
+ __OBJC_$_INSTANCE_METHODS_HMMediaProfile(AccessoryLikeObjectDataSource|AbstractionAdditions|HFIncludedContextProtocol|HFReordering|HFMediaAccessoryProfileAdditions)
+ __OBJC_$_INSTANCE_METHODS_HMMediaSystem(AccessoryLikeObjectDataSource|AbstractionAdditions|HFIncludedContextProtocol|HFAdditions|HFReordering|HFHomeKitObjectConformance|HFMediaSystemBuilderAdditions|HFMediaAccessoryProfileAdditions)
+ __OBJC_$_INSTANCE_METHODS_HMResidentDevice(HFAdditions|HFDebugging|HFHomeKitObjectConformance)
+ __OBJC_$_INSTANCE_METHODS_HMRoom(AbstractionAdditions|HFAdditions|HFApplicationData|HFDebugging|HFDemoMode|HFReordering|HFHomeKitObjectConformance)
+ __OBJC_$_INSTANCE_METHODS_HMService(AccessoryLikeObjectDataSource|AbstractionAdditions|HFIncludedContextProtocol|Additions|HFProgrammableSwitchAdditions|HFApplicationData|HFDebugging|HFReordering|HFHomeContainedObjectConformance|HFCharacteristicValueDisplayMetadataAdditions|HFUserNotificationServiceSettings)
+ __OBJC_$_INSTANCE_METHODS_HMServiceGroup(AccessoryLikeObjectDataSource|AbstractionAdditions|HFIncludedContextProtocol|HFAdditions|HFApplicationData|HFDebugging|HFReordering|HFHomeKitObjectConformance|HFUserNotificationServiceSettings)
+ __OBJC_$_INSTANCE_METHODS_HMSetting(HFAdditions|HFDebugging)
+ __OBJC_$_INSTANCE_METHODS_HMSettings(HFAdditions|HFDebugging)
+ __OBJC_$_INSTANCE_METHODS_HMTimerTrigger(HFTimerTriggerAdditions|AutomationBuilders|NaturalLanguage)
+ __OBJC_$_INSTANCE_METHODS_HMTrigger(HFAdditions|HFDebugging|HFHomeKitObjectConformance|AutomationBuilders|NaturalLanguage)
+ __OBJC_$_INSTANCE_METHODS_HMUser(HFAdditions|HFDebugging|HFHomeKitObjectConformance)
+ __OBJC_$_INSTANCE_METHODS_NSArray(HFDebugging|HUAdditions|HFAdditions|HFPropertyListConverting|HFUtilities)
+ __OBJC_$_INSTANCE_METHODS_NSDate(HFAnalytics|Additions|HFPropertyListConverting)
+ __OBJC_$_INSTANCE_METHODS_NSDictionary(HFDebugging|HUAdditions|HFAdditions|HFPropertyListConverting)
+ __OBJC_$_INSTANCE_METHODS_NSError(HFAdditions|HFErrorAdditions|HFErrorHandlerAdditions)
+ __OBJC_$_INSTANCE_METHODS_NSString(HFAdditions|HFStringGeneratoreAdditions|HFPropertyListConverting)
+ __OBJC_$_PROP_LIST_HMCharacteristicEvent_$_HFCharacteristicEventAdditions
+ __OBJC_$_PROP_LIST_HMTimerTrigger_$_HFTimerTriggerAdditions
+ __OBJC_$_PROP_LIST_NSError_$_HFAdditions
+ __OBJC_CATEGORY_PROTOCOLS_$_HMCharacteristicEvent_$_HFCharacteristicEventAdditions
+ __OBJC_CATEGORY_PROTOCOLS_$_HMTimerTrigger_$_HFTimerTriggerAdditions
+ __OBJC_CLASS_PROTOCOLS_$_HFAccessoryTypeGroup(Filtering|Performance)
+ __OBJC_CLASS_PROTOCOLS_$_HFActionSetBuilder(AccessoryLikeObjectContainer|AutomationBuilders|Comparison)
+ __OBJC_CLASS_PROTOCOLS_$_HFCharacteristicValueManager(Home|Tests|HFLightProfileValueSource)
+ __OBJC_CLASS_PROTOCOLS_$_HFItemManager(Home|DiffableDataSource|HFDebugging|HomeKitDelegates)
+ __OBJC_CLASS_PROTOCOLS_$_HFTriggerActionSetsBuilder(Comparison|UI|AutomationBuilders)
+ __OBJC_CLASS_PROTOCOLS_$_HFTriggerBuilder(Comparison|AutomationBuilders)
+ __OBJC_CLASS_PROTOCOLS_$_HMAccessory(Home|Home1|AccessoryLikeObjectDataSource|AbstractionAdditions|HFIncludedContextProtocol|HFSymptomFixableObject|HFAdditions|HFMediaAdditions|HFSoftwareUpdateAdditions|HFApplicationData|HFDebugging|HFReordering|HFHomeContainedObjectConformance|HFUserNotificationServiceSettings)
+ __OBJC_CLASS_PROTOCOLS_$_HMAccessoryNumberSetting(HFAdditions|HFDebugging)
+ __OBJC_CLASS_PROTOCOLS_$_HMAccessoryProfile(AccessoryLikeObjectDataSource|AbstractionAdditions|HFAdditions|HFIncludedContextProtocol|HFDebugging|HFHomeKitObjectConformance)
+ __OBJC_CLASS_PROTOCOLS_$_HMAction(HFAdditions|HFDebugging|HFHomeKitObjectConformance)
+ __OBJC_CLASS_PROTOCOLS_$_HMActionSet(HFFavoritableAdoption|HFIncludedContextProtocol|HFAdditions|HFApplicationData|HFDebugging|HFReordering|HFHomeKitObjectConformance)
+ __OBJC_CLASS_PROTOCOLS_$_HMCHIPEcosystem(HFAdditions|HFHomeKitObjectConformance)
+ __OBJC_CLASS_PROTOCOLS_$_HMCameraSignificantEvent(HFAdditions|HFDebugging|HFHomeKitObjectConformance)
+ __OBJC_CLASS_PROTOCOLS_$_HMCharacteristic(Additions|HFDebugging|HFHomeKitObjectConformance|HFActionSuggestions)
+ __OBJC_CLASS_PROTOCOLS_$_HMCharacteristicMetadata(HFAdditions|HFDebugging)
+ __OBJC_CLASS_PROTOCOLS_$_HMCharacteristicThresholdRangeEvent(HFAdditions|HMCharacteristicThresholdRangeEventAdditions|HFDebugging)
+ __OBJC_CLASS_PROTOCOLS_$_HMEventTrigger(HFAdditions|HFEventTriggerAdditions|HFDebugging|AutomationBuilders|NaturalLanguage)
+ __OBJC_CLASS_PROTOCOLS_$_HMHome(Home|AbstractionAdditions|Additions|HFFavoritingAdditions|HFApplicationData|HFDebugging|HFDemoMode|HFReordering|HFHomeKitObjectConformance|HFCharacteristicValueManagerAdditions|HFUserNotificationTopics|PredictionCaching|HFUserHandleAdditions)
+ __OBJC_CLASS_PROTOCOLS_$_HMHomeManager(HFAdditions|HFAdditionsHelper|HFApplicationData|HFDebugging)
+ __OBJC_CLASS_PROTOCOLS_$_HMMediaProfile(AccessoryLikeObjectDataSource|AbstractionAdditions|HFIncludedContextProtocol|HFReordering|HFMediaAccessoryProfileAdditions)
+ __OBJC_CLASS_PROTOCOLS_$_HMMediaSystem(AccessoryLikeObjectDataSource|AbstractionAdditions|HFIncludedContextProtocol|HFAdditions|HFReordering|HFHomeKitObjectConformance|HFMediaSystemBuilderAdditions|HFMediaAccessoryProfileAdditions)
+ __OBJC_CLASS_PROTOCOLS_$_HMResidentDevice(HFAdditions|HFDebugging|HFHomeKitObjectConformance)
+ __OBJC_CLASS_PROTOCOLS_$_HMRoom(AbstractionAdditions|HFAdditions|HFApplicationData|HFDebugging|HFDemoMode|HFReordering|HFHomeKitObjectConformance)
+ __OBJC_CLASS_PROTOCOLS_$_HMService(AccessoryLikeObjectDataSource|AbstractionAdditions|HFIncludedContextProtocol|Additions|HFProgrammableSwitchAdditions|HFApplicationData|HFDebugging|HFReordering|HFHomeContainedObjectConformance|HFCharacteristicValueDisplayMetadataAdditions|HFUserNotificationServiceSettings)
+ __OBJC_CLASS_PROTOCOLS_$_HMServiceGroup(AccessoryLikeObjectDataSource|AbstractionAdditions|HFIncludedContextProtocol|HFAdditions|HFApplicationData|HFDebugging|HFReordering|HFHomeKitObjectConformance|HFUserNotificationServiceSettings)
+ __OBJC_CLASS_PROTOCOLS_$_HMSetting(HFAdditions|HFDebugging)
+ __OBJC_CLASS_PROTOCOLS_$_HMSettings(HFAdditions|HFDebugging)
+ __OBJC_CLASS_PROTOCOLS_$_HMTrigger(HFAdditions|HFDebugging|HFHomeKitObjectConformance|AutomationBuilders|NaturalLanguage)
+ __OBJC_CLASS_PROTOCOLS_$_HMUser(HFAdditions|HFDebugging|HFHomeKitObjectConformance)
+ __OBJC_CLASS_PROTOCOLS_$_NSArray(HFDebugging|HUAdditions|HFAdditions|HFPropertyListConverting|HFUtilities)
+ __OBJC_CLASS_PROTOCOLS_$_NSDate(HFAnalytics|Additions|HFPropertyListConverting)
+ __OBJC_CLASS_PROTOCOLS_$_NSDictionary(HFDebugging|HUAdditions|HFAdditions|HFPropertyListConverting)
+ __OBJC_CLASS_PROTOCOLS_$_NSString(HFAdditions|HFStringGeneratoreAdditions|HFPropertyListConverting)
+ ___41-[HFAccessoryBuilder removeItemFromHome:]_block_invoke
+ ___41-[HFAccessoryBuilder removeItemFromHome:]_block_invoke_2
+ ___56-[HMAccessory(HFMediaAdditions) hf_identifyHomePodSolo:]_block_invoke
+ ___68+[HFAccessorySettingFormatterFactory _siriPersonalRequestsFormatter]_block_invoke_3
+ ___80-[HMMediaSystem(HFMediaAccessoryProfileAdditions) hf_siriLanguageOptionsManager]_block_invoke
+ ___swift_closure_destructor.103Tm
+ ___swift_closure_destructor.5Tm
+ ___swift_closure_destructor.94Tm
+ ___swift_closure_destructor.9Tm
+ _kIdentifySolo
+ _symbolic _____y_____SgG s23_ContiguousArrayStorageC s6UInt16V
- -[HMAccessory(HFAdditions) hf_adaptiveTemperatureEnabled]
- GCC_except_table149
- GCC_except_table152
- GCC_except_table155
- GCC_except_table158
- GCC_except_table161
- GCC_except_table167
- GCC_except_table183
- GCC_except_table198
- GCC_except_table202
- GCC_except_table62
- GCC_except_table92
- GCC_except_table95
- __OBJC_$_CATEGORY_CLASS_METHODS_NSArray_$_HFUtilities
- __OBJC_$_CATEGORY_HMAccessoryNumberSetting_$_HFDebugging
- __OBJC_$_CATEGORY_HMAccessoryProfile_$_AbstractionAdditions
- __OBJC_$_CATEGORY_HMAction_$_HFDebugging
- __OBJC_$_CATEGORY_HMCHIPEcosystem_$_HFHomeKitObjectConformance
- __OBJC_$_CATEGORY_HMCameraSignificantEvent_$_HFDebugging
- __OBJC_$_CATEGORY_HMCharacteristicEvent_$_HFDebugging
- __OBJC_$_CATEGORY_HMCharacteristicMetadata_$_HFDebugging
- __OBJC_$_CATEGORY_HMCharacteristicThresholdRangeEvent_$_HFDebugging
- __OBJC_$_CATEGORY_HMCharacteristicWriteAction_$_HFDebugging
- __OBJC_$_CATEGORY_HMCharacteristic_$_HFDebugging
- __OBJC_$_CATEGORY_HMEventTrigger_$_HFDebugging
- __OBJC_$_CATEGORY_HMHomeManager_$_HFDebugging
- __OBJC_$_CATEGORY_HMMediaProfile_$_AbstractionAdditions
- __OBJC_$_CATEGORY_HMMediaSystem_$_AbstractionAdditions
- __OBJC_$_CATEGORY_HMResidentDevice_$_HFDebugging
- __OBJC_$_CATEGORY_HMServiceGroup_$_AbstractionAdditions
- __OBJC_$_CATEGORY_HMService_$_AbstractionAdditions
- __OBJC_$_CATEGORY_HMSetting_$_HFDebugging
- __OBJC_$_CATEGORY_HMSettings_$_HFDebugging
- __OBJC_$_CATEGORY_HMTimerTrigger_$_NaturalLanguage
- __OBJC_$_CATEGORY_HMTrigger_$_HFDebugging
- __OBJC_$_CATEGORY_HMUser_$_HFDebugging
- __OBJC_$_CATEGORY_INSTANCE_METHODS_HMCHIPEcosystem_$_HFHomeKitObjectConformance
- __OBJC_$_CATEGORY_NSArray_$_HFUtilities
- __OBJC_$_CATEGORY_NSDictionary_$_HFAdditions
- __OBJC_$_CATEGORY_NSError_$_HFErrorHandlerAdditions
- __OBJC_$_CATEGORY_NSString_$_HFPropertyListConverting
- __OBJC_$_CLASS_METHODS_HFAccessoryTypeGroup(Performance|Filtering)
- __OBJC_$_CLASS_METHODS_HMAccessory(Home|Home1|AbstractionAdditions|HFDebugging|HFMediaAdditions|HFAdditions|HFSymptomFixableObject|HFIncludedContextProtocol|HFHomeContainedObjectConformance|HFSoftwareUpdateAdditions|HFUserNotificationServiceSettings|HFApplicationData|AccessoryLikeObjectDataSource|HFReordering)
- __OBJC_$_CLASS_METHODS_HMAccessoryProfile(AbstractionAdditions|HFAdditions|HFDebugging|HFIncludedContextProtocol|HFHomeKitObjectConformance|AccessoryLikeObjectDataSource)
- __OBJC_$_CLASS_METHODS_HMActionSet(HFFavoritableAdoption|HFDebugging|HFAdditions|HFIncludedContextProtocol|HFHomeKitObjectConformance|HFApplicationData|HFReordering)
- __OBJC_$_CLASS_METHODS_HMCHIPEcosystem(HFHomeKitObjectConformance|HFAdditions)
- __OBJC_$_CLASS_METHODS_HMCharacteristic(HFDebugging|HFHomeKitObjectConformance|Additions|HFActionSuggestions)
- __OBJC_$_CLASS_METHODS_HMEventTrigger(HFDebugging|NaturalLanguage|HFAdditions|HFEventTriggerAdditions|AutomationBuilders)
- __OBJC_$_CLASS_METHODS_HMHome(Home|AbstractionAdditions|HFUserHandleAdditions|HFDebugging|HFCharacteristicValueManagerAdditions|HFFavoritingAdditions|Additions|PredictionCaching|HFHomeKitObjectConformance|HFUserNotificationTopics|HFDemoMode|HFApplicationData|HFReordering)
- __OBJC_$_CLASS_METHODS_HMHomeManager(HFDebugging|HFAdditions|HFApplicationData|HFAdditionsHelper)
- __OBJC_$_CLASS_METHODS_HMService(AbstractionAdditions|HFDebugging|HFCharacteristicValueDisplayMetadataAdditions|HFIncludedContextProtocol|Additions|HFProgrammableSwitchAdditions|HFHomeContainedObjectConformance|HFUserNotificationServiceSettings|HFApplicationData|AccessoryLikeObjectDataSource|HFReordering)
- __OBJC_$_CLASS_METHODS_HMSetting(HFDebugging|HFAdditions)
- __OBJC_$_CLASS_METHODS_HMSettings(HFDebugging|HFAdditions)
- __OBJC_$_CLASS_METHODS_HMTimerTrigger(NaturalLanguage|HFTimerTriggerAdditions|AutomationBuilders)
- __OBJC_$_CLASS_METHODS_HMTrigger(HFDebugging|NaturalLanguage|HFHomeKitObjectConformance|HFAdditions|AutomationBuilders)
- __OBJC_$_CLASS_METHODS_NSDate(HFAnalytics|HFPropertyListConverting|Additions)
- __OBJC_$_CLASS_METHODS_NSError(HFErrorHandlerAdditions|HFErrorAdditions|HFAdditions)
- __OBJC_$_CLASS_METHODS_NSString(HFPropertyListConverting|HFAdditions|HFStringGeneratoreAdditions)
- __OBJC_$_INSTANCE_METHODS_HFAccessoryTypeGroup(Performance|Filtering)
- __OBJC_$_INSTANCE_METHODS_HFActionSetBuilder(Comparison|AutomationBuilders|AccessoryLikeObjectContainer)
- __OBJC_$_INSTANCE_METHODS_HFCharacteristicValueManager(Home|HFLightProfileValueSource|Tests)
- __OBJC_$_INSTANCE_METHODS_HFEventTriggerBuilder(AutomationBuilders|LegacyInterfaces|Comparison)
- __OBJC_$_INSTANCE_METHODS_HFItemManager(Home|HFDebugging|HomeKitDelegates|DiffableDataSource)
- __OBJC_$_INSTANCE_METHODS_HFTimerTriggerBuilder(AutomationBuilders|Comparison)
- __OBJC_$_INSTANCE_METHODS_HFTriggerActionSetsBuilder(UI|AutomationBuilders|Comparison)
- __OBJC_$_INSTANCE_METHODS_HFTriggerBuilder(AutomationBuilders|Comparison)
- __OBJC_$_INSTANCE_METHODS_HMAccessory(Home|Home1|AbstractionAdditions|HFDebugging|HFMediaAdditions|HFAdditions|HFSymptomFixableObject|HFIncludedContextProtocol|HFHomeContainedObjectConformance|HFSoftwareUpdateAdditions|HFUserNotificationServiceSettings|HFApplicationData|AccessoryLikeObjectDataSource|HFReordering)
- __OBJC_$_INSTANCE_METHODS_HMAccessoryNumberSetting(HFDebugging|HFAdditions)
- __OBJC_$_INSTANCE_METHODS_HMAccessoryProfile(AbstractionAdditions|HFAdditions|HFDebugging|HFIncludedContextProtocol|HFHomeKitObjectConformance|AccessoryLikeObjectDataSource)
- __OBJC_$_INSTANCE_METHODS_HMAction(HFDebugging|HFHomeKitObjectConformance|HFAdditions)
- __OBJC_$_INSTANCE_METHODS_HMActionSet(HFFavoritableAdoption|HFDebugging|HFAdditions|HFIncludedContextProtocol|HFHomeKitObjectConformance|HFApplicationData|HFReordering)
- __OBJC_$_INSTANCE_METHODS_HMCameraSignificantEvent(HFDebugging|HFHomeKitObjectConformance|HFAdditions)
- __OBJC_$_INSTANCE_METHODS_HMCharacteristic(HFDebugging|HFHomeKitObjectConformance|Additions|HFActionSuggestions)
- __OBJC_$_INSTANCE_METHODS_HMCharacteristicEvent(HFDebugging|HFCharacteristicEventAdditions)
- __OBJC_$_INSTANCE_METHODS_HMCharacteristicMetadata(HFDebugging|HFAdditions)
- __OBJC_$_INSTANCE_METHODS_HMCharacteristicThresholdRangeEvent(HFDebugging|HFAdditions|HMCharacteristicThresholdRangeEventAdditions)
- __OBJC_$_INSTANCE_METHODS_HMCharacteristicWriteAction(HFDebugging|HFAdditions)
- __OBJC_$_INSTANCE_METHODS_HMEventTrigger(HFDebugging|NaturalLanguage|HFAdditions|HFEventTriggerAdditions|AutomationBuilders)
- __OBJC_$_INSTANCE_METHODS_HMHome(Home|AbstractionAdditions|HFUserHandleAdditions|HFDebugging|HFCharacteristicValueManagerAdditions|HFFavoritingAdditions|Additions|PredictionCaching|HFHomeKitObjectConformance|HFUserNotificationTopics|HFDemoMode|HFApplicationData|HFReordering)
- __OBJC_$_INSTANCE_METHODS_HMHomeManager(HFDebugging|HFAdditions|HFApplicationData|HFAdditionsHelper)
- __OBJC_$_INSTANCE_METHODS_HMMediaProfile(AbstractionAdditions|HFIncludedContextProtocol|HFMediaAccessoryProfileAdditions|AccessoryLikeObjectDataSource|HFReordering)
- __OBJC_$_INSTANCE_METHODS_HMMediaSystem(AbstractionAdditions|HFAdditions|HFMediaSystemBuilderAdditions|HFIncludedContextProtocol|HFHomeKitObjectConformance|HFMediaAccessoryProfileAdditions|AccessoryLikeObjectDataSource|HFReordering)
- __OBJC_$_INSTANCE_METHODS_HMResidentDevice(HFDebugging|HFAdditions|HFHomeKitObjectConformance)
- __OBJC_$_INSTANCE_METHODS_HMRoom(AbstractionAdditions|HFDebugging|HFAdditions|HFHomeKitObjectConformance|HFDemoMode|HFApplicationData|HFReordering)
- __OBJC_$_INSTANCE_METHODS_HMService(AbstractionAdditions|HFDebugging|HFCharacteristicValueDisplayMetadataAdditions|HFIncludedContextProtocol|Additions|HFProgrammableSwitchAdditions|HFHomeContainedObjectConformance|HFUserNotificationServiceSettings|HFApplicationData|AccessoryLikeObjectDataSource|HFReordering)
- __OBJC_$_INSTANCE_METHODS_HMServiceGroup(AbstractionAdditions|HFDebugging|HFAdditions|HFIncludedContextProtocol|HFHomeKitObjectConformance|HFUserNotificationServiceSettings|HFApplicationData|AccessoryLikeObjectDataSource|HFReordering)
- __OBJC_$_INSTANCE_METHODS_HMSetting(HFDebugging|HFAdditions)
- __OBJC_$_INSTANCE_METHODS_HMSettings(HFDebugging|HFAdditions)
- __OBJC_$_INSTANCE_METHODS_HMTimerTrigger(NaturalLanguage|HFTimerTriggerAdditions|AutomationBuilders)
- __OBJC_$_INSTANCE_METHODS_HMTrigger(HFDebugging|NaturalLanguage|HFHomeKitObjectConformance|HFAdditions|AutomationBuilders)
- __OBJC_$_INSTANCE_METHODS_HMUser(HFDebugging|HFHomeKitObjectConformance|HFAdditions)
- __OBJC_$_INSTANCE_METHODS_NSArray(HFUtilities|HFDebugging|HFPropertyListConverting|HFAdditions|HUAdditions)
- __OBJC_$_INSTANCE_METHODS_NSDate(HFAnalytics|HFPropertyListConverting|Additions)
- __OBJC_$_INSTANCE_METHODS_NSDictionary(HFAdditions|HFDebugging|HFPropertyListConverting|HUAdditions)
- __OBJC_$_INSTANCE_METHODS_NSError(HFErrorHandlerAdditions|HFErrorAdditions|HFAdditions)
- __OBJC_$_INSTANCE_METHODS_NSString(HFPropertyListConverting|HFAdditions|HFStringGeneratoreAdditions)
- __OBJC_$_PROP_LIST_HMAccessoryNumberSetting_$_HFDebugging
- __OBJC_$_PROP_LIST_HMCHIPEcosystem_$_HFHomeKitObjectConformance
- __OBJC_CATEGORY_PROTOCOLS_$_HMAccessoryNumberSetting_$_HFDebugging
- __OBJC_CATEGORY_PROTOCOLS_$_HMCHIPEcosystem_$_HFHomeKitObjectConformance
- __OBJC_CATEGORY_PROTOCOLS_$_HMCharacteristicMetadata_$_HFDebugging
- __OBJC_CATEGORY_PROTOCOLS_$_HMSetting_$_HFDebugging
- __OBJC_CATEGORY_PROTOCOLS_$_HMSettings_$_HFDebugging
- __OBJC_CLASS_PROTOCOLS_$_HFAccessoryTypeGroup(Performance|Filtering)
- __OBJC_CLASS_PROTOCOLS_$_HFActionSetBuilder(Comparison|AutomationBuilders|AccessoryLikeObjectContainer)
- __OBJC_CLASS_PROTOCOLS_$_HFCharacteristicValueManager(Home|HFLightProfileValueSource|Tests)
- __OBJC_CLASS_PROTOCOLS_$_HFItemManager(Home|HFDebugging|HomeKitDelegates|DiffableDataSource)
- __OBJC_CLASS_PROTOCOLS_$_HFTriggerActionSetsBuilder(UI|AutomationBuilders|Comparison)
- __OBJC_CLASS_PROTOCOLS_$_HFTriggerBuilder(AutomationBuilders|Comparison)
- __OBJC_CLASS_PROTOCOLS_$_HMAccessory(Home|Home1|AbstractionAdditions|HFDebugging|HFMediaAdditions|HFAdditions|HFSymptomFixableObject|HFIncludedContextProtocol|HFHomeContainedObjectConformance|HFSoftwareUpdateAdditions|HFUserNotificationServiceSettings|HFApplicationData|AccessoryLikeObjectDataSource|HFReordering)
- __OBJC_CLASS_PROTOCOLS_$_HMAccessoryProfile(AbstractionAdditions|HFAdditions|HFDebugging|HFIncludedContextProtocol|HFHomeKitObjectConformance|AccessoryLikeObjectDataSource)
- __OBJC_CLASS_PROTOCOLS_$_HMAction(HFDebugging|HFHomeKitObjectConformance|HFAdditions)
- __OBJC_CLASS_PROTOCOLS_$_HMActionSet(HFFavoritableAdoption|HFDebugging|HFAdditions|HFIncludedContextProtocol|HFHomeKitObjectConformance|HFApplicationData|HFReordering)
- __OBJC_CLASS_PROTOCOLS_$_HMCameraSignificantEvent(HFDebugging|HFHomeKitObjectConformance|HFAdditions)
- __OBJC_CLASS_PROTOCOLS_$_HMCharacteristic(HFDebugging|HFHomeKitObjectConformance|Additions|HFActionSuggestions)
- __OBJC_CLASS_PROTOCOLS_$_HMCharacteristicEvent(HFDebugging|HFCharacteristicEventAdditions)
- __OBJC_CLASS_PROTOCOLS_$_HMCharacteristicThresholdRangeEvent(HFDebugging|HFAdditions|HMCharacteristicThresholdRangeEventAdditions)
- __OBJC_CLASS_PROTOCOLS_$_HMEventTrigger(HFDebugging|NaturalLanguage|HFAdditions|HFEventTriggerAdditions|AutomationBuilders)
- __OBJC_CLASS_PROTOCOLS_$_HMHome(Home|AbstractionAdditions|HFUserHandleAdditions|HFDebugging|HFCharacteristicValueManagerAdditions|HFFavoritingAdditions|Additions|PredictionCaching|HFHomeKitObjectConformance|HFUserNotificationTopics|HFDemoMode|HFApplicationData|HFReordering)
- __OBJC_CLASS_PROTOCOLS_$_HMHomeManager(HFDebugging|HFAdditions|HFApplicationData|HFAdditionsHelper)
- __OBJC_CLASS_PROTOCOLS_$_HMMediaProfile(AbstractionAdditions|HFIncludedContextProtocol|HFMediaAccessoryProfileAdditions|AccessoryLikeObjectDataSource|HFReordering)
- __OBJC_CLASS_PROTOCOLS_$_HMMediaSystem(AbstractionAdditions|HFAdditions|HFMediaSystemBuilderAdditions|HFIncludedContextProtocol|HFHomeKitObjectConformance|HFMediaAccessoryProfileAdditions|AccessoryLikeObjectDataSource|HFReordering)
- __OBJC_CLASS_PROTOCOLS_$_HMResidentDevice(HFDebugging|HFAdditions|HFHomeKitObjectConformance)
- __OBJC_CLASS_PROTOCOLS_$_HMRoom(AbstractionAdditions|HFDebugging|HFAdditions|HFHomeKitObjectConformance|HFDemoMode|HFApplicationData|HFReordering)
- __OBJC_CLASS_PROTOCOLS_$_HMService(AbstractionAdditions|HFDebugging|HFCharacteristicValueDisplayMetadataAdditions|HFIncludedContextProtocol|Additions|HFProgrammableSwitchAdditions|HFHomeContainedObjectConformance|HFUserNotificationServiceSettings|HFApplicationData|AccessoryLikeObjectDataSource|HFReordering)
- __OBJC_CLASS_PROTOCOLS_$_HMServiceGroup(AbstractionAdditions|HFDebugging|HFAdditions|HFIncludedContextProtocol|HFHomeKitObjectConformance|HFUserNotificationServiceSettings|HFApplicationData|AccessoryLikeObjectDataSource|HFReordering)
- __OBJC_CLASS_PROTOCOLS_$_HMTimerTrigger(NaturalLanguage|HFTimerTriggerAdditions|AutomationBuilders)
- __OBJC_CLASS_PROTOCOLS_$_HMTrigger(HFDebugging|NaturalLanguage|HFHomeKitObjectConformance|HFAdditions|AutomationBuilders)
- __OBJC_CLASS_PROTOCOLS_$_HMUser(HFDebugging|HFHomeKitObjectConformance|HFAdditions)
- __OBJC_CLASS_PROTOCOLS_$_NSArray(HFUtilities|HFDebugging|HFPropertyListConverting|HFAdditions|HUAdditions)
- __OBJC_CLASS_PROTOCOLS_$_NSDate(HFAnalytics|HFPropertyListConverting|Additions)
- __OBJC_CLASS_PROTOCOLS_$_NSDictionary(HFAdditions|HFDebugging|HFPropertyListConverting|HUAdditions)
- __OBJC_CLASS_PROTOCOLS_$_NSString(HFPropertyListConverting|HFAdditions|HFStringGeneratoreAdditions)
- ___51-[HMAccessory(HFMediaAdditions) hf_identifyHomePod]_block_invoke
- ___swift_closure_destructor.105Tm
- ___swift_closure_destructor.3Tm
- ___swift_closure_destructor.96Tm
- ___swift_mutable_project_boxed_opaque_existential_1Tm
- _symbolic _____Sg 13HomeDataModel15StaticAccessoryV
- _symbolic _____SgXw 13HomeDataModel0A5StateV6StreamC0A0E0A17FrameworkObserverC
- _symbolic _____SgXwz_Xx 13HomeDataModel0A5StateV6StreamC0A0E0A17FrameworkObserverC
- _symbolic _____y_____G s11_SetStorageC 13HomeDataModel15StaticAccessoryV
- _symbolic ytSg
- _symbolic ytSgIeAgHr_
CStrings:
+ "%s solo = %{BOOL}d"
+ "-[HFAccessorySettingDeviceOptionsAdapterUtility identifyAccessorySolo:]"
+ "HFHomeHubSoftwareUpdateRequiredAlertMessage"
+ "HFHomeHubSoftwareUpdateRequiredAlertTitle"
+ "HFSecureEraseHomePodErrorDescription"
+ "HFSecureEraseHomePodErrorTitle"
+ "HFSensitiveStrings-ChinaDataErase"
+ "MatterAccessoryLikeItemProvider: Failed to get accessory for tilePath %{public}s"
+ "NFC transport dropped mid-pairing; asking the user to tap the accessory again"
+ "Personal Content is Off for %@ because these accessories are not enrolled: %@"
+ "Preparing to send identify message to accessory: %@, solo = %{BOOL}d"
+ "colorCode"
+ "identifyAccessory invoked, solo = %{BOOL}d"
+ "nfc_retry"
+ "processSetupAccessoryProgressChange: SetupInterruptedAwaitingReTap, holding phase %@"
+ "simulateMatterCommandError"
+ "simulateMatterCommandErrorStatus"
+ "simulateMatterCommandErrorType"
+ "solo"
- "-[HFAccessorySettingDeviceOptionsAdapterUtility identifyAccessory]"
- "MatterAccessoryLikeItemProvider: Failed to get static accessory for tilePath %{public}s"
- "Preparing to send identify message to accessory: %@"
- "identifyAccessory invoked"
```
