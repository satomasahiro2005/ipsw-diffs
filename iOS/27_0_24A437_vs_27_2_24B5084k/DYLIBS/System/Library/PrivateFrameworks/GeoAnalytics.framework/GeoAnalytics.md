## GeoAnalytics

> `/System/Library/PrivateFrameworks/GeoAnalytics.framework/GeoAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x97304` | `0x98d38` | **`+0x1a34`** |
| `__AUTH_CONST.__objc_const` | `0x2e98` | `0x33b8` | **`+0x520`** |
| `__AUTH_CONST.__cfstring` | `0x14600` | `0x14800` | **`+0x200`** |
| `__DATA_CONST.__objc_selrefs` | `0x41b0` | `0x43a8` | **`+0x1f8`** |
| `__TEXT.__cstring` | `0xeda2` | `0xef5d` | **`+0x1bb`** |
| `__TEXT.__objc_methlist` | `0x255c` | `0x26e4` | **`+0x188`** |
| `__DATA_CONST.__const` | `0x7bb0` | `0x7d00` | **`+0x150`** |
| `__AUTH.__objc_data` | `0x140` | `0x230` | **`+0xf0`** |
| `__AUTH_CONST.__objc_intobj` | `0x1cb0` | `0x1d88` | **`+0xd8`** |
| `__DATA.__data` | `0x490` | `0x550` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0x3758` | `0x37b8` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x1080` | `0x10e0` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x680` | `0x6bc` | **`+0x3c`** |
| `__DATA.__objc_ivar` | `0x1d0` | `0x1fc` | **`+0x2c`** |
| `__DATA_CONST.__got` | `0x6b0` | `0x6d8` | **`+0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0xea8` | `0xed0` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x110` | `0x128` | **`+0x18`** |
| `__DATA_CONST.__objc_superrefs` | `0xa0` | `0xb8` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x60` | `0x70` | **`+0x10`** |
| `__TEXT.__const` | `0x75c` | `0x764` | **`+0x8`** |

### Other Changes

```diff

-2075.30.6.12.12
+2075.31.6.17.9

-  Functions: 1615
-  Symbols:   3296
-  CStrings:  2807
+  Functions: 1645
+  Symbols:   3387
+  CStrings:  2826
Symbols:
+ +[GEOAPPortal capturePeriodicSettingsWithMapSettings:mapUiShown:mapsFeatures:mapsUserSettings:routingSettings:widgetConfiguration:]
+ +[GEOAPPortal capturePeriodicSettingsWithMapSettings:mapUiShown:mapsFeatures:mapsUserSettings:routingSettings:widgetConfiguration:additionalStates:providedDropRate:completionQueue:completionBlock:]
+ +[GEOAPPortal captureShowcaseSuppressionWithBusinessId:localSearchProviderID:showcaseId:suppressionReason:adamId:multipleShowcaseMetadatas:]
+ +[GEOAPPortal captureShowcaseSuppressionWithBusinessId:localSearchProviderID:showcaseId:suppressionReason:adamId:multipleShowcaseMetadatas:additionalStates:providedDropRate:completionQueue:completionBlock:]
+ +[GEOAPPortal(Extras) captureShowcaseSuppressionEventWithBusinessId:localSearchProviderID:showcaseId:adamId:suppressionReason:multipleShowcaseMetadata:]
+ -[GEOAPEphemeralWidgetPropertiesStateStore displayHeight]
+ -[GEOAPEphemeralWidgetPropertiesStateStore displayWidth]
+ -[GEOAPEphemeralWidgetPropertiesStateStore family]
+ -[GEOAPEphemeralWidgetPropertiesStateStore initWithIsPreview:family:displayWidth:displayHeight:]
+ -[GEOAPEphemeralWidgetPropertiesStateStore isPreview]
+ -[GEOAPEphemeralWidgetTimelineEntriesStateStore .cxx_destruct]
+ -[GEOAPEphemeralWidgetTimelineEntriesStateStore enumerateEntriesWith:]
+ -[GEOAPEphemeralWidgetTimelineEntriesStateStore initWithEntries:]
+ -[GEOAPSharedStateData _consumeWidgetConfiguration]
+ -[GEOAPSharedStateData performWidgetConfigurationUpdate:]
+ -[GEOAPUserActionDataModelInfoProviders initWithWidgetPropertiesProvider:]
+ -[GEOAPUserActionDataModelInfoProviders initWithWidgetPropertiesProvider:widgetTimelineEntriesProvider:]
+ -[GEOAPUserActionDataModelInfoProviders initWithWidgetTimelineEntriesProvider:]
+ -[GEOAPUserActionDataModelInfoProviders widgetPropertiesDataModelProvider]
+ -[GEOAPUserActionDataModelInfoProviders widgetTimelineEntriesDataModelProvider]
+ -[GEOAPUserActionDataModelInfoProviders(Internal) widgetPropertiesState]
+ -[GEOAPUserActionDataModelInfoProviders(Internal) widgetTimelineEntriesState]
+ -[GEOAPWidgetTimelineEntryInfo content]
+ -[GEOAPWidgetTimelineEntryInfo hasRelevance]
+ -[GEOAPWidgetTimelineEntryInfo initWithContent:]
+ -[GEOAPWidgetTimelineEntryInfo initWithContent:relevance:]
+ -[GEOAPWidgetTimelineEntryInfo relevance]
+ GCC_except_table1058
+ GCC_except_table1061
+ GCC_except_table1066
+ GCC_except_table1068
+ GCC_except_table1181
+ GCC_except_table1210
+ GCC_except_table1212
+ GCC_except_table1230
+ GCC_except_table1234
+ GCC_except_table1236
+ GCC_except_table1238
+ GCC_except_table1451
+ GCC_except_table1489
+ GCC_except_table553
+ GCC_except_table557
+ GCC_except_table559
+ GCC_except_table561
+ GCC_except_table563
+ GCC_except_table566
+ GCC_except_table569
+ GCC_except_table572
+ GCC_except_table575
+ GCC_except_table577
+ GCC_except_table584
+ GCC_except_table587
+ GCC_except_table590
+ GCC_except_table637
+ GCC_except_table639
+ GCC_except_table644
+ GCC_except_table658
+ GCC_except_table664
+ GCC_except_table673
+ _GeoAnalyticsConfig_AllowedCountriesForEnrichedResultsCount_Metadata_block_invoke_70
+ _GeoAnalyticsConfig_B74FC90_enabled_Metadata_block_invoke_73
+ _GeoAnalyticsConfig_GeoShifterObfuscationSeedIN_Metadata_block_invoke_72
+ _GeoAnalyticsConfig_LastMetroAssetCatalogDownload_Metadata_block_invoke_78
+ _GeoAnalyticsConfig_LocIntActiveBatchID_Metadata_block_invoke_74
+ _GeoAnalyticsConfig_LocIntSeqNo_Metadata_block_invoke_75
+ _GeoAnalyticsConfig_MetroAssetCatalogCheckInterval_Metadata_block_invoke_79
+ _GeoAnalyticsConfig_TrafficShiftingINEnabled_Metadata_block_invoke_71
+ _GeoAnalyticsConfig_UseriCloudAccountAvailable_Metadata_block_invoke_66
+ _GeoAnalyticsConfig_WidgetConfigurationMaxCountPerFamily
+ _GeoAnalyticsConfig_WidgetConfigurationMaxCountPerFamily_Metadata
+ _GeoAnalyticsConfig_WidgetConfigurationMaxCountPerFamily_Metadata_block_invoke_65
+ _GeoAnalyticsConfig__debug_AlwaysUseExpensiveUpload_Metadata_block_invoke_67
+ _GeoAnalyticsConfig__debug_CancelInflightUploads_Metadata_block_invoke_81
+ _GeoAnalyticsConfig__debug_KeepUploadFiles_Metadata_block_invoke_68
+ _GeoAnalyticsConfig__debug_NoMobileAssetPreloader_Metadata_block_invoke_82
+ _GeoAnalyticsConfig__debug_NoUploader_Metadata_block_invoke_80
+ _GeoAnalyticsConfig__debug_UploadCountersEnabled_Metadata_block_invoke_69
+ _GeoAnalyticsConfig__debug_simulateFileWriteError_Metadata_block_invoke_77
+ _GeoAnalyticsConfig__debug_simulateNoURLs_Metadata_block_invoke_76
+ _GeoAnalyticsStateConfig_widgetProperties_stateDisabled
+ _GeoAnalyticsStateConfig_widgetProperties_stateDisabled_Metadata
+ _GeoAnalyticsStateConfig_widgetProperties_stateDisabled_Metadata_block_invoke_71
+ _GeoAnalyticsStateConfig_widgetTimelineEntries_stateDisabled
+ _GeoAnalyticsStateConfig_widgetTimelineEntries_stateDisabled_Metadata
+ _GeoAnalyticsStateConfig_widgetTimelineEntries_stateDisabled_Metadata_block_invoke_72
+ _OBJC_CLASS_$_GEOAPEphemeralWidgetPropertiesStateStore
+ _OBJC_CLASS_$_GEOAPEphemeralWidgetTimelineEntriesStateStore
+ _OBJC_CLASS_$_GEOAPWidgetTimelineEntryInfo
+ _OBJC_CLASS_$_GEODisplaySize
+ _OBJC_CLASS_$_GEOLogMsgStateWidgetConfiguration
+ _OBJC_CLASS_$_GEOLogMsgStateWidgetProperties
+ _OBJC_CLASS_$_GEOLogMsgStateWidgetTimelineEntries
+ _OBJC_CLASS_$_GEOWidgetTimelineEntry
+ _OBJC_IVAR_$_GEOAPEphemeralWidgetPropertiesStateStore._displayHeight
+ _OBJC_IVAR_$_GEOAPEphemeralWidgetPropertiesStateStore._displayWidth
+ _OBJC_IVAR_$_GEOAPEphemeralWidgetPropertiesStateStore._family
+ _OBJC_IVAR_$_GEOAPEphemeralWidgetPropertiesStateStore._isPreview
+ _OBJC_IVAR_$_GEOAPEphemeralWidgetTimelineEntriesStateStore._entries
+ _OBJC_IVAR_$_GEOAPSharedStateData._widgetConfigurationStateIso
+ _OBJC_IVAR_$_GEOAPUserActionDataModelInfoProviders._widgetPropertiesProvider
+ _OBJC_IVAR_$_GEOAPUserActionDataModelInfoProviders._widgetTimelineEntriesProvider
+ _OBJC_IVAR_$_GEOAPWidgetTimelineEntryInfo._content
+ _OBJC_IVAR_$_GEOAPWidgetTimelineEntryInfo._hasRelevance
+ _OBJC_IVAR_$_GEOAPWidgetTimelineEntryInfo._relevance
+ _OBJC_METACLASS_$_GEOAPEphemeralWidgetPropertiesStateStore
+ _OBJC_METACLASS_$_GEOAPEphemeralWidgetTimelineEntriesStateStore
+ _OBJC_METACLASS_$_GEOAPWidgetTimelineEntryInfo
+ __OBJC_$_INSTANCE_METHODS_GEOAPEphemeralWidgetPropertiesStateStore
+ __OBJC_$_INSTANCE_METHODS_GEOAPEphemeralWidgetTimelineEntriesStateStore
+ __OBJC_$_INSTANCE_METHODS_GEOAPWidgetTimelineEntryInfo
+ __OBJC_$_INSTANCE_VARIABLES_GEOAPEphemeralWidgetPropertiesStateStore
+ __OBJC_$_INSTANCE_VARIABLES_GEOAPEphemeralWidgetTimelineEntriesStateStore
+ __OBJC_$_INSTANCE_VARIABLES_GEOAPWidgetTimelineEntryInfo
+ __OBJC_$_PROP_LIST_GEOAPEphemeralWidgetPropertiesStateStore
+ __OBJC_$_PROP_LIST_GEOAPEphemeralWidgetTimelineEntriesStateStore
+ __OBJC_$_PROP_LIST_GEOAPUserActionWidgetPropertiesDataModelProviding
+ __OBJC_$_PROP_LIST_GEOAPWidgetTimelineEntryInfo
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_GEOAPUserActionWidgetPropertiesDataModelProviding
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_GEOAPUserActionWidgetTimelineEntriesDataModelProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_GEOAPUserActionWidgetPropertiesDataModelProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_GEOAPUserActionWidgetTimelineEntriesDataModelProviding
+ __OBJC_$_PROTOCOL_REFS_GEOAPUserActionWidgetPropertiesDataModelProviding
+ __OBJC_$_PROTOCOL_REFS_GEOAPUserActionWidgetTimelineEntriesDataModelProviding
+ __OBJC_CLASS_PROTOCOLS_$_GEOAPEphemeralWidgetPropertiesStateStore
+ __OBJC_CLASS_PROTOCOLS_$_GEOAPEphemeralWidgetTimelineEntriesStateStore
+ __OBJC_CLASS_RO_$_GEOAPEphemeralWidgetPropertiesStateStore
+ __OBJC_CLASS_RO_$_GEOAPEphemeralWidgetTimelineEntriesStateStore
+ __OBJC_CLASS_RO_$_GEOAPWidgetTimelineEntryInfo
+ __OBJC_LABEL_PROTOCOL_$_GEOAPUserActionWidgetPropertiesDataModelProviding
+ __OBJC_LABEL_PROTOCOL_$_GEOAPUserActionWidgetTimelineEntriesDataModelProviding
+ __OBJC_METACLASS_RO_$_GEOAPEphemeralWidgetPropertiesStateStore
+ __OBJC_METACLASS_RO_$_GEOAPEphemeralWidgetTimelineEntriesStateStore
+ __OBJC_METACLASS_RO_$_GEOAPWidgetTimelineEntryInfo
+ __OBJC_PROTOCOL_$_GEOAPUserActionWidgetPropertiesDataModelProviding
+ __OBJC_PROTOCOL_$_GEOAPUserActionWidgetTimelineEntriesDataModelProviding
+ ___197+[GEOAPPortal capturePeriodicSettingsWithMapSettings:mapUiShown:mapsFeatures:mapsUserSettings:routingSettings:widgetConfiguration:additionalStates:providedDropRate:completionQueue:completionBlock:]_block_invoke
+ ___206+[GEOAPPortal captureShowcaseSuppressionWithBusinessId:localSearchProviderID:showcaseId:suppressionReason:adamId:multipleShowcaseMetadatas:additionalStates:providedDropRate:completionQueue:completionBlock:]_block_invoke
+ ___51-[GEOAPSharedStateData _consumeWidgetConfiguration]_block_invoke
+ ___57-[GEOAPSharedStateData performWidgetConfigurationUpdate:]_block_invoke
+ ___57-[GEOAPSharedStateData performWidgetConfigurationUpdate:]_block_invoke_2
+ ___77-[GEOAPUserActionDataModelInfoProviders(Internal) widgetTimelineEntriesState]_block_invoke
+ ___block_descriptor_44_e8_32s_e11_v16?0i8I12ls32l8
+ ___block_descriptor_48_e8_32s40r_e14_B20?0i8B12f16lr40l8s32l8
+ ___block_descriptor_52_e8_32s40bs_e5_v8?0ls40l8s32l8
- +[GEOAPPortal capturePeriodicSettingsWithMapSettings:mapUiShown:mapsFeatures:mapsUserSettings:routingSettings:]
- +[GEOAPPortal capturePeriodicSettingsWithMapSettings:mapUiShown:mapsFeatures:mapsUserSettings:routingSettings:additionalStates:providedDropRate:completionQueue:completionBlock:]
- +[GEOAPPortal captureShowcaseSuppressionWithBusinessId:localSearchProviderID:showcaseId:suppressionReason:adamId:]
- +[GEOAPPortal captureShowcaseSuppressionWithBusinessId:localSearchProviderID:showcaseId:suppressionReason:adamId:additionalStates:providedDropRate:completionQueue:completionBlock:]
- GCC_except_table1037
- GCC_except_table1042
- GCC_except_table1044
- GCC_except_table1156
- GCC_except_table1182
- GCC_except_table1184
- GCC_except_table1202
- GCC_except_table1206
- GCC_except_table1208
- GCC_except_table1421
- GCC_except_table1459
- GCC_except_table552
- GCC_except_table556
- GCC_except_table558
- GCC_except_table560
- GCC_except_table562
- GCC_except_table565
- GCC_except_table568
- GCC_except_table571
- GCC_except_table573
- GCC_except_table576
- GCC_except_table583
- GCC_except_table586
- GCC_except_table589
- GCC_except_table636
- GCC_except_table638
- GCC_except_table643
- GCC_except_table657
- GCC_except_table662
- GCC_except_table672
- _GeoAnalyticsConfig_AllowedCountriesForEnrichedResultsCount_Metadata_block_invoke_69
- _GeoAnalyticsConfig_B74FC90_enabled_Metadata_block_invoke_72
- _GeoAnalyticsConfig_GeoShifterObfuscationSeedIN_Metadata_block_invoke_71
- _GeoAnalyticsConfig_LastMetroAssetCatalogDownload_Metadata_block_invoke_77
- _GeoAnalyticsConfig_LocIntActiveBatchID_Metadata_block_invoke_73
- _GeoAnalyticsConfig_LocIntSeqNo_Metadata_block_invoke_74
- _GeoAnalyticsConfig_MetroAssetCatalogCheckInterval_Metadata_block_invoke_78
- _GeoAnalyticsConfig_TrafficShiftingINEnabled_Metadata_block_invoke_70
- _GeoAnalyticsConfig_UseriCloudAccountAvailable_Metadata_block_invoke_65
- _GeoAnalyticsConfig__debug_AlwaysUseExpensiveUpload_Metadata_block_invoke_66
- _GeoAnalyticsConfig__debug_CancelInflightUploads_Metadata_block_invoke_80
- _GeoAnalyticsConfig__debug_KeepUploadFiles_Metadata_block_invoke_67
- _GeoAnalyticsConfig__debug_NoMobileAssetPreloader_Metadata_block_invoke_81
- _GeoAnalyticsConfig__debug_NoUploader_Metadata_block_invoke_79
- _GeoAnalyticsConfig__debug_UploadCountersEnabled_Metadata_block_invoke_68
- _GeoAnalyticsConfig__debug_simulateFileWriteError_Metadata_block_invoke_76
- _GeoAnalyticsConfig__debug_simulateNoURLs_Metadata_block_invoke_75
- ___177+[GEOAPPortal capturePeriodicSettingsWithMapSettings:mapUiShown:mapsFeatures:mapsUserSettings:routingSettings:additionalStates:providedDropRate:completionQueue:completionBlock:]_block_invoke
- ___180+[GEOAPPortal captureShowcaseSuppressionWithBusinessId:localSearchProviderID:showcaseId:suppressionReason:adamId:additionalStates:providedDropRate:completionQueue:completionBlock:]_block_invoke
CStrings:
+ "B20@?0i8B12f16"
+ "DISPLAYED_VISITED_PLACES"
+ "MAP_VIEW_ACTIVATED"
+ "MAP_VIEW_FOREGROUNDED"
+ "MAP_VIEW_INSTANTIATED"
+ "SNAPSHOT"
+ "SNAPSHOTTER_USED"
+ "SWIPE_LEFT_SHOWCASE"
+ "SWIPE_RIGHT_SHOWCASE"
+ "TAP_ITEM_VISITED"
+ "TIMELINE"
+ "WIDGETKIT_CONTENT_REQUESTED"
+ "WidgetConfigurationMaxCountPerFamily"
+ "WidgetProperties"
+ "WidgetTimelineEntries"
+ "com.apple.GeoServices.Analytics.SharedState.widgetConfiguration"
+ "v16@?0i8I12"
+ "widgetProperties_stateDisabled"
+ "widgetTimelineEntries_stateDisabled"
```
