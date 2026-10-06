## GeneralMapsWidget

> `/private/var/staged_system_apps/Maps.app/PlugIns/GeneralMapsWidget.appex/GeneralMapsWidget`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7d9f0` | `0x82360` | **`+0x4970`** |
| `__DATA_CONST.__const` | `0x1a1c0` | `0x1a6c0` | **`+0x500`** |
| `__DATA.__bss` | `0x2388` | `0x2808` | **`+0x480`** |
| `__DATA_CONST.__cfstring` | `0x82e0` | `0x86c0` | **`+0x3e0`** |
| `__TEXT.__const` | `0x4214` | `0x44e4` | **`+0x2d0`** |
| `__TEXT.__cstring` | `0xb4c0` | `0xb780` | **`+0x2c0`** |
| `__DATA.__data` | `0x4a90` | `0x4c48` | **`+0x1b8`** |
| `__TEXT.__oslogstring` | `0x4950` | `0x4b00` | **`+0x1b0`** |
| `__TEXT.__eh_frame` | `0x520` | `0x6a8` | **`+0x188`** |
| `__TEXT.__objc_stubs` | `0x2ec0` | `0x3040` | **`+0x180`** |
| `__TEXT.__swift5_fieldmd` | `0x1234` | `0x1330` | **`+0xfc`** |
| `__TEXT.__unwind_info` | `0x10a0` | `0x1198` | **`+0xf8`** |
| `__TEXT.__swift5_reflstr` | `0xe1e` | `0xefe` | **`+0xe0`** |
| `__TEXT.__constg_swiftt` | `0x1d90` | `0x1e50` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x7858` | `0x7912` | **`+0xba`** |
| `__TEXT.__objc_methname` | `0x898d` | `0x8a2d` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0x1928` | `0x1988` | **`+0x60`** |
| `__DATA_CONST.__auth_ptr` | `0x7b8` | `0x808` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x22a0` | `0x22f0` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x60c` | `0x658` | **`+0x4c`** |
| `__TEXT.__objc_methtype` | `0x2417` | `0x2447` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x1158` | `0x1180` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x868` | `0x890` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x13c` | `0x160` | **`+0x24`** |
| `__TEXT.__swift5_assocty` | `0x570` | `0x588` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0x18c` | `0x1a0` | **`+0x14`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2972.31.6.17.20
+2972.31.6.17.31

+  - /System/Library/PrivateFrameworks/AppPredictionClient.framework/AppPredictionClient

+  - /System/Library/PrivateFrameworks/ProactiveSuggestionClientModel.framework/ProactiveSuggestionClientModel

-  Functions: 2723
-  Symbols:   1353
-  CStrings:  2963
+  Functions: 2806
+  Symbols:   1361
+  CStrings:  3011
Symbols:
+ _CFDateGetAbsoluteTime
+ _MapsConfig_CustomPOIControllerSkipsHashCheck
+ _MapsConfig_DeferAuxiliaryTasksUntilForegrounded
+ _MapsConfig_ParkedCarDonationSeedRetryInterval
+ _MapsConfig_SearchHomeEnrichmentRequestGenerationBudget
+ _MapsConfig_SearchResultsEnrichmentRequestGenerationBudget
+ _OBJC_CLASS_$_ATXBiomeUIStream
+ _swift_bridgeObjectRetain_n
CStrings:
+ "AppAdded"
+ "AppRemoved"
+ "CustomPOIControllerSkipsHashCheck"
+ "DeferAuxiliaryTasksUntilForegrounded"
+ "DeviceLocked"
+ "DeviceUnlocked"
+ "HomeScreenDisappeared"
+ "HomeScreenPageShown"
+ "ParkedCarDonationSeedRetryInterval"
+ "PinnedWidgetAdded"
+ "PinnedWidgetDeleted"
+ "SearchHomeEnrichmentRequestGenerationBudget"
+ "SearchResultsEnrichmentRequestGenerationBudget"
+ "SpecialPageAppeared"
+ "SpecialPageDisappeared"
+ "StackChanged"
+ "StackCreated"
+ "StackDeleted"
+ "StackDisappeared"
+ "StackShown"
+ "StackVisibilityChanged"
+ "Unknown"
+ "UserStackConfigChanged"
+ "WIDGET_IMPRESSION_HOME_SCREEN"
+ "WIDGET_IMPRESSION_TODAY_PAGE"
+ "WIDGET_RENDER_TODAY_PAGE"
+ "WidgetAddedToStack"
+ "WidgetImpressionEventStore: read %{public}ld event(s)"
+ "WidgetImpressionEventStore: read failed: %{public}s"
+ "WidgetImpressionLastReported"
+ "WidgetImpressionReduction: %{public}ld event(s) in, %{public}ld used, %{public}ld before %{public}s, %{public}ld with no signal"
+ "WidgetImpressionReduction: %{public}ld event(s) in, 0 used, %{public}ld before %{public}s"
+ "WidgetImpressionReporter: reporting %{public}ld signal(s): %{public}s"
+ "WidgetLongLook"
+ "WidgetRemovedFromStack"
+ "WidgetTapped"
+ "WidgetUserFeedback"
+ "eventBody"
+ "eventTypeString"
+ "homeScreenEvent"
+ "publisherFromStartTime:"
+ "reportDailyUsageCountType:"
+ "sinkWithCompletion:receiveInput:"
+ "stackLocation"
+ "v16@?0@\"BPSCompletion\"8"
+ "v16@?0@8"
+ "widgetBundleId"
+ "widgetKind"
```
