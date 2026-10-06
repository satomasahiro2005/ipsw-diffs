## NewsCore

> `/System/Library/PrivateFrameworks/NewsCore.framework/NewsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e8098` | `0x3e7940` | **`-0x758`** |
| `__AUTH_CONST.__objc_const` | `0x79110` | `0x79310` | **`+0x200`** |
| `__AUTH.__data` | `0x910` | `0x9b0` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x18193` | `0x18233` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0xc850` | `0xc8d8` | **`+0x88`** |
| `__TEXT.__const` | `0xd5d8` | `0xd648` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x4082` | `0x40e0` | **`+0x5e`** |
| `__TEXT.__constg_swiftt` | `0x2d90` | `0x2dec` | **`+0x5c`** |
| `__AUTH.__objc_data` | `0x6a0` | `0x6f0` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x34ed0` | `0x34e80` | **`-0x50`** |
| `__DATA_CONST.__const` | `0x11400` | `0x113c8` | **`-0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x2c8c` | `0x2cb8` | **`+0x2c`** |
| `__DATA_CONST.__objc_selrefs` | `0x14a80` | `0x14aa8` | **`+0x28`** |
| `__DATA_DIRTY.__bss` | `0x3978` | `0x3958` | **`-0x20`** |
| `__TEXT.__cstring` | `0x54989` | `0x54969` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0xe18` | `0xe38` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xe678` | `0xe698` | **`+0x20`** |
| `__DATA.__data` | `0x7080` | `0x7090` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x4530` | `0x4540` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x1ca0` | `0x1cb0` | **`+0x10`** |
| `__DATA_DIRTY.__objc_ivar` | `0xfb4` | `0xfa4` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x20c0` | `0x20d0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2b20` | `0x2b28` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x15a0` | `0x15a8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x964` | `0x968` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x5c` | `0x60` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x3ec` | `0x3f0` | **`+0x4`** |

### Other Changes

```diff

-5934.3.0.0.0
+5960.0.0.0.0

-  Symbols:   37509
-  CStrings:  10468
+  Symbols:   37533
+  CStrings:  10470
Symbols:
+ +[FCPublisherGroupEngagement supportsSecureCoding]
+ -[FCMutableTodayPrivateData setPublisherGroupEngagement:]
+ -[FCNewsAppConfig todayWidgetComputationalGraphBestOfEnabled]
+ -[FCPublisherGroupEngagement curatedClicks]
+ -[FCPublisherGroupEngagement curatedImpressions]
+ -[FCPublisherGroupEngagement encodeWithCoder:]
+ -[FCPublisherGroupEngagement initWithCoder:]
+ -[FCPublisherGroupEngagement initWithCuratedClicks:curatedImpressions:personalizedClicks:personalizedImpressions:]
+ -[FCPublisherGroupEngagement init]
+ -[FCPublisherGroupEngagement personalizedClicks]
+ -[FCPublisherGroupEngagement personalizedImpressions]
+ -[FCPublisherGroupEngagement setCuratedClicks:]
+ -[FCPublisherGroupEngagement setCuratedImpressions:]
+ -[FCPublisherGroupEngagement setPersonalizedClicks:]
+ -[FCPublisherGroupEngagement setPersonalizedImpressions:]
+ -[FCTodayPrivateData publisherGroupEngagement]
+ _FCWidgetComputationalGraphBestOfEnabledSharedPreferenceKey
+ _OBJC_CLASS_$_FCPublisherGroupEngagement
+ _OBJC_IVAR_$_FCPublisherGroupEngagement._curatedClicks
+ _OBJC_IVAR_$_FCPublisherGroupEngagement._curatedImpressions
+ _OBJC_IVAR_$_FCPublisherGroupEngagement._personalizedClicks
+ _OBJC_IVAR_$_FCPublisherGroupEngagement._personalizedImpressions
+ _OBJC_METACLASS_$_FCPublisherGroupEngagement
+ __DATA__TtC8NewsCore31DropboxPublisherGroupEngagement
+ __IVARS__TtC8NewsCore31DropboxPublisherGroupEngagement
+ __METACLASS_DATA__TtC8NewsCore31DropboxPublisherGroupEngagement
+ __OBJC_$_CLASS_METHODS_FCPublisherGroupEngagement
+ __OBJC_$_CLASS_PROP_LIST_FCPublisherGroupEngagement
+ __OBJC_$_INSTANCE_METHODS_FCPublisherGroupEngagement
+ __OBJC_$_INSTANCE_METHODS_NSMutableArray(FCAdditions|FCAdditions_NSString)
+ __OBJC_$_INSTANCE_VARIABLES_FCPublisherGroupEngagement
+ __OBJC_$_PROP_LIST_FCPublisherGroupEngagement
+ __OBJC_CATEGORY_PROTOCOLS_$_NSMutableArray_$_FCAdditions
+ __OBJC_CLASS_PROTOCOLS_$_FCPublisherGroupEngagement
+ __OBJC_CLASS_RO_$_FCPublisherGroupEngagement
+ __OBJC_METACLASS_RO_$_FCPublisherGroupEngagement
+ _symbolic $s8NewsCore33PublisherGroupEngagementProvidingP
+ _symbolic SDySSSo26FCPublisherGroupEngagementCGSg
+ _symbolic _____ 8NewsCore31DropboxPublisherGroupEngagementC
- -[FCArticleRecordSource setArticleTagMetadataRecordKeys:]
- -[FCArticleRecordSource setTopicFlagsRecordKeys:]
- -[FCNewsAppConfig userSegmentationInWidgetAllowed]
- -[FCNewsTabiFeedPersonalizationConfiguration nonMtBundleOutputConfiguration]
- -[FCNewsTabiFeedPersonalizationConfiguration nonMtNonBundleOutputConfiguration]
- -[FCNewsTabiFeedPersonalizationConfiguration setNonMtBundleOutputConfiguration:]
- -[FCNewsTabiFeedPersonalizationConfiguration setNonMtNonBundleOutputConfiguration:]
- _FCUserSegmentationEnableWidgetConfigSharedPreferenceKey
- __OBJC_$_INSTANCE_METHODS_NSMutableArray(FCAdditions|FCAdditions_NSString|FCAdditions|FCAdditions_NSString)
- __OBJC_CLASS_PROTOCOLS_$_NSMutableArray(FCAdditions|FCAdditions_NSString|FCAdditions|FCAdditions_NSString)
- ___45-[FCArticleRecordSource topicFlagsRecordKeys]_block_invoke_2
- ___53-[FCArticleRecordSource articleTagMetadataRecordKeys]_block_invoke_2
- ___block_descriptor_56_e8_32s40s48s_e14_"NSArray"8?0ls32l8s40l8s48l8
- _kFCNewsTabiFeedPersonalizationConfigurationNonMTBundleOutputConfigurationKey
- _kFCNewsTabiFeedPersonalizationConfigurationNonMTNonBundleOutputConfigurationKey
CStrings:
+ "FCTodayWidgetDropboxDataPublisherGroupEngagementDataDictionaryKey"
+ "curatedClicks"
+ "curatedImpressions"
+ "failed to decode persisted content archive, archivePath=%{public}@, error=%{public}@"
+ "persisted content archive is missing or unreadable, archivePath=%{public}@"
+ "personalizedClicks"
+ "personalizedImpressions"
+ "todayWidgetComputationalGraphBestOfEnabled"
+ "widget_computational_graph_best_of_enabled"
- "\n\tnonMtBundleOutputConfiguration: %@"
- "\n\tnonMtNonBundleOutputConfiguration: %@"
- "articleLinkBehaviorImprovementsEnabledLevel"
- "enable_widget_config_user_segmentation"
- "nonMtBundleOutputConfiguration"
- "nonMtNonBundleOutputConfiguration"
- "userSegmentationInWidgetAllowed"
```
