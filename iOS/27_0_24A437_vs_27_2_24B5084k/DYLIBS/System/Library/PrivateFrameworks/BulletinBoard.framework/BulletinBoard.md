## BulletinBoard

> `/System/Library/PrivateFrameworks/BulletinBoard.framework/BulletinBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x786f0` | `0x7dfc4` | **`+0x58d4`** |
| `__AUTH_CONST.__cfstring` | `0x6be0` | `0x79e0` | **`+0xe00`** |
| `__TEXT.__cstring` | `0x6426` | `0x6d92` | **`+0x96c`** |
| `__AUTH_CONST.__objc_const` | `0x107b8` | `0x10cc8` | **`+0x510`** |
| `__TEXT.__oslogstring` | `0x65f7` | `0x68a6` | **`+0x2af`** |
| `__TEXT.__objc_methlist` | `0x862c` | `0x87dc` | **`+0x1b0`** |
| `__DATA_CONST.__const` | `0x2038` | `0x21a0` | **`+0x168`** |
| `__DATA_CONST.__objc_selrefs` | `0x3fc0` | `0x40f0` | **`+0x130`** |
| `__DATA_CONST.__got` | `0x5b8` | `0x648` | **`+0x90`** |
| `__TEXT.__unwind_info` | `0x20b0` | `0x2128` | **`+0x78`** |
| `__AUTH_CONST.__const` | `0xae0` | `0xb40` | **`+0x60`** |
| `__DATA.__data` | `0xe00` | `0xe60` | **`+0x60`** |
| `__AUTH.__objc_data` | `—` | `0x50` | **`+0x50`** |
| `__TEXT.__const` | `0x188` | `0x1c0` | **`+0x38`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x18` | `0x48` | **`+0x30`** |
| `__AUTH_CONST.__objc_intobj` | `0xd8` | `0x108` | **`+0x30`** |
| `__DATA.__bss` | `0x88` | `0xa8` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x170` | `0x190` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x8c4` | `0x8d4` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x278` | `0x280` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x128` | `0x130` | **`+0x8`** |

### Other Changes

```diff

-955.0.0.0.0
+955.2.1.0.0

+  - /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics

-  Functions: 3365
-  Symbols:   5172
-  CStrings:  1431
+  Functions: 3415
+  Symbols:   5261
+  CStrings:  1545
Symbols:
+ +[BBSettingsAnalytics _appRowDimensionKeys]
+ +[BBSettingsAnalytics _appRowPayloadForSection:archetype:isDeliveredQuietly:]
+ +[BBSettingsAnalytics _categoryCountsWithSilenced:categoryIndexBySectionID:]
+ +[BBSettingsAnalytics _deviceSnapshotPayloadWithSectionInfo:rawSectionInfo:bulletinCountsBySectionID:globalSettings:]
+ +[BBSettingsAnalytics _explicitChoiceCountsWithRawSectionInfo:]
+ +[BBSettingsAnalytics _groupedAppRows:minimumAppsPerCell:]
+ +[BBSettingsAnalytics _sendSnapshotWithBasePayload:silencedBySectionID:appRowSectionIDs:appRowPayloads:topicRowSectionIDs:topicRowPayloads:deviceEventUsed:defaults:]
+ +[BBSettingsAnalytics _shouldSendSnapshotAtDate:lastSentDate:]
+ +[BBSettingsAnalytics _topicRowPayloadForTopic:parentAllowsNotifications:]
+ +[BBSettingsAnalytics _volumeBucketForCount:]
+ +[BBSettingsAnalytics isCollectingAnySettingsEvent]
+ +[BBSettingsAnalytics sendDeviceSnapshotIfNeededWithSectionInfo:rawSectionInfo:bulletinCountsBySectionID:globalSettings:defaults:]
+ +[BBSettingsAnalytics shouldSendDeviceSnapshotWithDefaults:]
+ -[BBSectionInfo _applyUserSettingsFromSectionInfo:]
+ -[BBSectionInfo _userSettingsCopyForSectionID:]
+ -[BBSectionInfo hasEverBeenUserChanged]
+ -[BBSectionInfo lastSettingChangeDate]
+ -[BBSectionInfo lastSettingSource]
+ -[BBSectionInfo setHasEverBeenUserChanged:]
+ -[BBSectionInfo setLastSettingChangeDate:]
+ -[BBSectionInfo setLastSettingSource:]
+ -[BBServer _copySectionSettingsFromSectionID:toSectionID:]
+ -[BBServer _inferredSettingSourceForCurrentConnection]
+ -[BBServer _queue_sendSettingsAnalyticsIfNeeded]
+ -[BBServer _setSectionInfo:forSectionID:source:]
+ -[BBServer _setSectionInfoNoteSettingsChanged:forSectionID:source:]
+ -[BBServer copySectionSettingsFromSectionID:toSectionID:withHandler:]
+ -[BBServer setSectionInfo:forSectionID:source:withHandler:]
+ -[BBSettingsGateway copySectionSettingsFromSectionID:toSectionID:withCompletion:]
+ -[BBSettingsGateway setSectionInfo:forSectionID:source:]
+ GCC_except_table104
+ GCC_except_table113
+ GCC_except_table122
+ GCC_except_table131
+ GCC_except_table140
+ GCC_except_table149
+ GCC_except_table161
+ GCC_except_table163
+ GCC_except_table165
+ GCC_except_table167
+ GCC_except_table169
+ GCC_except_table171
+ GCC_except_table173
+ GCC_except_table175
+ GCC_except_table177
+ GCC_except_table213
+ GCC_except_table214
+ GCC_except_table82
+ GCC_except_table91
+ GCC_except_table95
+ _AnalyticsIsEventUsed
+ _AnalyticsSendEvent
+ _BBSettingsAnalyticsArchetypeForSection
+ _BBSettingsAnalyticsCategoryFromIdentifier
+ _BBSettingsAnalyticsChangeWindowDays
+ _BBSettingsAnalyticsShouldCountSection
+ _CTCategoryIdentifierCreativity
+ _CTCategoryIdentifierEducation
+ _CTCategoryIdentifierEntertainment
+ _CTCategoryIdentifierGames
+ _CTCategoryIdentifierHealthAndFitness
+ _CTCategoryIdentifierOther
+ _CTCategoryIdentifierProductivity
+ _CTCategoryIdentifierReadingAndReference
+ _CTCategoryIdentifierShoppingAndFood
+ _CTCategoryIdentifierSocialNetworking
+ _CTCategoryIdentifierSystemBlockable
+ _CTCategoryIdentifierSystemHidden
+ _CTCategoryIdentifierSystemUnblockable
+ _CTCategoryIdentifierTravel
+ _CTCategoryIdentifierUtilities
+ _NSCalendarIdentifierGregorian
+ _OBJC_CLASS_$_BBSettingsAnalytics
+ _OBJC_CLASS_$_LSBundleRecord
+ _OBJC_IVAR_$_BBSectionInfo._hasEverBeenUserChanged
+ _OBJC_IVAR_$_BBSectionInfo._lastSettingChangeDate
+ _OBJC_IVAR_$_BBSectionInfo._lastSettingSource
+ _OBJC_IVAR_$_BBServer._bulletinCountsBySectionID
+ _OBJC_METACLASS_$_BBSettingsAnalytics
+ __OBJC_$_CLASS_METHODS_BBSettingsAnalytics
+ __OBJC_$_PROP_LIST_BBAnalyticsSnapshotGate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BBAnalyticsSnapshotGate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BBAnalyticsSnapshotGate
+ __OBJC_$_PROTOCOL_REFS_BBAnalyticsSnapshotGate
+ __OBJC_CLASS_PROTOCOLS_$_BBBulletinBoardDefaults
+ __OBJC_CLASS_RO_$_BBSettingsAnalytics
+ __OBJC_LABEL_PROTOCOL_$_BBAnalyticsSnapshotGate
+ __OBJC_METACLASS_RO_$_BBSettingsAnalytics
+ __OBJC_PROTOCOL_$_BBAnalyticsSnapshotGate
+ ___165+[BBSettingsAnalytics _sendSnapshotWithBasePayload:silencedBySectionID:appRowSectionIDs:appRowPayloads:topicRowSectionIDs:topicRowPayloads:deviceEventUsed:defaults:]_block_invoke
+ ___165+[BBSettingsAnalytics _sendSnapshotWithBasePayload:silencedBySectionID:appRowSectionIDs:appRowPayloads:topicRowSectionIDs:topicRowPayloads:deviceEventUsed:defaults:]_block_invoke_2
+ ___54-[BBServer _inferredSettingSourceForCurrentConnection]_block_invoke
+ ___56-[BBSettingsGateway setSectionInfo:forSectionID:source:]_block_invoke
+ ___59-[BBServer setSectionInfo:forSectionID:source:withHandler:]_block_invoke
+ ___62+[BBSettingsAnalytics _shouldSendSnapshotAtDate:lastSentDate:]_block_invoke
+ ___69-[BBServer copySectionSettingsFromSectionID:toSectionID:withHandler:]_block_invoke
+ ___81-[BBSettingsGateway copySectionSettingsFromSectionID:toSectionID:withCompletion:]_block_invoke
+ ___81-[BBSettingsGateway copySectionSettingsFromSectionID:toSectionID:withCompletion:]_block_invoke_2
+ ___block_descriptor_41_e8_32bs_e5_v8?0ls32l8
+ ___block_descriptor_48_e8_32s40bs_e8_v12?0B8ls40l8s32l8
+ ___block_descriptor_48_e8_32s40s_e36_v32?0"NSMutableDictionary"8Q16^B24ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48bs_e17_v16?0"NSError"8ls32l8s40l8s48l8
+ ___block_descriptor_56_e8_32s40s48bs_e8_v12?0B8ls32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56bs_e5_v8?0ls32l8s40l8s48l8s56l8
+ ___block_descriptor_89_e8_32s40s48s56s64s72s_e34_v24?0"NSDictionary"8"NSError"16ls32l8s40l8s48l8s56l8s64l8s72l8
+ ___block_descriptor_97_e8_32s40s48s56s64s72s80s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8
+ __inferredSettingSourceForCurrentConnection.onceToken
+ __inferredSettingSourceForCurrentConnection.userFacingClients
+ __shouldSendSnapshotAtDate:lastSentDate:.calendar
+ __shouldSendSnapshotAtDate:lastSentDate:.calendarOnce
- GCC_except_table106
- GCC_except_table115
- GCC_except_table124
- GCC_except_table133
- GCC_except_table142
- GCC_except_table151
- GCC_except_table156
- GCC_except_table160
- GCC_except_table162
- GCC_except_table164
- GCC_except_table166
- GCC_except_table168
- GCC_except_table170
- GCC_except_table172
- GCC_except_table203
- GCC_except_table209
- GCC_except_table75
- GCC_except_table86
- GCC_except_table88
- GCC_except_table97
- ___52-[BBServer setSectionInfo:forSectionID:withHandler:]_block_invoke
CStrings:
+ "%@=%@;"
+ "BBLastAnalyticsSnapshotDate"
+ "BBSettingsAnalytics: Category lookup failed, reporting without categories: %{public}@"
+ "BBSettingsAnalytics: Emitting daily notification settings snapshot"
+ "Communication"
+ "Copying section settings from %{public}@ to %{public}@"
+ "Leisure"
+ "Not copying section settings from %{public}@ to %{public}@, no saved section info for the source"
+ "Not copying section settings, invalid section IDs: '%{public}@' -> '%{public}@'"
+ "Other"
+ "System"
+ "Utility"
+ "[%{public}@] Copied section settings from %{public}@ [ success: %{BOOL}d ]"
+ "[%{public}@] Copying section settings from %{public}@"
+ "[%{public}@] Copying section settings from %{public}@ failed with error %{public}@"
+ "[%{public}@] Not applying user settings for subsection %{public}@, no matching subsection"
+ "archetype"
+ "category"
+ "com.apple."
+ "com.apple.NotificationsSettingsExtension"
+ "com.apple.Preferences"
+ "com.apple.usernotifications.settings.appConfiguration"
+ "com.apple.usernotifications.settings.deviceSnapshot"
+ "com.apple.usernotifications.settings.topicConfiguration"
+ "daysSinceLastSettingChangeBucket"
+ "effectiveGlobalHighlightsSetting"
+ "effectiveGlobalSummarizationSetting"
+ "hasEverBeenUserChanged"
+ "isDeliveredQuietly"
+ "isFirstParty"
+ "isSuppressedResidual"
+ "lastAnalyticsSnapshotDate"
+ "lastSettingChangeDate"
+ "lastSettingSource"
+ "numAlertsOff"
+ "numAlertsOffAmongAllowed"
+ "numAlertsSupportedAmongAllowed"
+ "numAllowed"
+ "numAnnounceOff"
+ "numApps"
+ "numAppsSuper"
+ "numArchetypeDeliveredQuietly"
+ "numArchetypeFullyOn"
+ "numArchetypeNeverAsked"
+ "numArchetypeNotificationsOff"
+ "numArchetypePartiallySuppressed"
+ "numArchetypeSummaryRouted"
+ "numAuthorized"
+ "numBadgesOff"
+ "numBadgesOffAmongAllowed"
+ "numBadgesSupportedAmongAllowed"
+ "numChangedLast%luDays"
+ "numCriticalAlertEnabled"
+ "numDeliveredQuietly"
+ "numDenied"
+ "numEverChangedByUser"
+ "numExplicitAnnounceOff"
+ "numExplicitInScheduledSummary"
+ "numExplicitPreviewsNever"
+ "numExplicitPrioritizationOff"
+ "numExplicitSummarizationOff"
+ "numGroupingOff"
+ "numHighVolumeApps"
+ "numInScheduledSummary"
+ "numLastChangedByRemote"
+ "numLastChangedBySystem"
+ "numLastChangedByUnknown"
+ "numLastChangedByUser"
+ "numLockScreenOff"
+ "numLockScreenOffAmongAllowed"
+ "numLockScreenSupportedAmongAllowed"
+ "numLowVolumeApps"
+ "numManaged"
+ "numNotDetermined"
+ "numNotificationCenterOff"
+ "numNotificationCenterOffAmongAllowed"
+ "numNotificationCenterSupportedAmongAllowed"
+ "numNotificationsOff"
+ "numOffAndLastChangedByUser"
+ "numPreviewsNever"
+ "numPrioritizationNotSupported"
+ "numPrioritizationOff"
+ "numProvisional"
+ "numRestricted"
+ "numScheduledDeliveryTimes"
+ "numSections"
+ "numSilencedAmongHighVolume"
+ "numSilencedAmongLowVolume"
+ "numSilencedSuper"
+ "numSoundsOff"
+ "numSoundsOffAmongAllowed"
+ "numSoundsSupportedAmongAllowed"
+ "numSubsections"
+ "numSubsectionsInheriting"
+ "numSubsectionsMutedExplicitly"
+ "numSummarizationNotSupported"
+ "numSummarizationOff"
+ "numSuppressedCells"
+ "numTemporary"
+ "numTimeSensitiveOff"
+ "numTimeSensitiveOffAmongAllowed"
+ "numTimeSensitiveSupportedAmongAllowed"
+ "numUserConfiguredTimeSensitive"
+ "numWithAnyExplicitChoice"
+ "numWithChangeDate"
+ "numWithSubsections"
+ "parentAllowsNotifications"
+ "parentCategory"
+ "storedContentPreviewSetting"
+ "storedPrioritizationSetting"
+ "storedScheduledDeliverySetting"
+ "storedSummarizationSetting"
+ "usesManagedSettings"
+ "v32@?0@\"NSMutableDictionary\"8Q16^B24"
```
