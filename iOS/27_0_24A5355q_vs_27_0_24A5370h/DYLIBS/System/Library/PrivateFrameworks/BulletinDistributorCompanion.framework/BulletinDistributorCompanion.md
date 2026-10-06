## BulletinDistributorCompanion

> `/System/Library/PrivateFrameworks/BulletinDistributorCompanion.framework/BulletinDistributorCompanion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8d0e4` | `0x8cef8` | **`-0x1ec`** |

### Other Changes

```diff

-382.0.11.0.0
+382.0.12.0.0
Functions:
~ -[BLTRemoteObject _queueUpdateConnectionStatusWithResetDefaulteDevice:] : 420 -> 416
~ -[BLTRemoteObject service:account:identifier:didSendWithSuccess:error:] : 472 -> 468
~ ___65-[BLTPairedSyncCoordinator syncSessionObserver:didReceiveUpdate:]_block_invoke_2 : 264 -> 280
~ -[BLTObjectStore keys] : 824 -> 820
~ -[BBSectionInfo(imageData) blt_storeIconVariantsWithRootPath:] : 1364 -> 1356
~ -[BBSectionInfo(imageData) blt_removeIconVariantsWithRootPath:] : 896 -> 884
~ -[BLTHashCache _updateCacheWithItems:forSectionID:matchID:result:] : 1132 -> 1120
~ -[BLTPBBulletin dictionaryRepresentation] : 3844 -> 3836
~ -[BLTPBBulletin writeTo:] : 2932 -> 2916
~ -[BLTPBBulletin copyWithZone:] : 3492 -> 3476
~ -[BLTPBBulletin mergeFrom:] : 3064 -> 3048
~ ___61-[BLTWatchKitAppList _fetchWatchKitInfoWithForce:completion:]_block_invoke_2 : 748 -> 744
~ -[BLTPBSectionInfo(protobuf) requestWithKeypaths:] : 380 -> 376
~ -[BLTSectionInfoOverrideApplier applyOverrides:toSectionInfo:] : 1408 -> 1400
~ -[BBSectionInfo(PBConversions) applyKeypaths:from:] : 368 -> 364
~ -[BLTPBBulletinSummary dictionaryRepresentation] : 572 -> 568
~ -[BLTPBBulletinSummary writeTo:] : 404 -> 400
~ -[BLTPBBulletinSummary copyWithZone:] : 460 -> 456
~ -[BLTPBBulletinSummary mergeFrom:] : 388 -> 384
~ -[BLTSectionInfoListBBProvider applicationsDidInstall:] : 336 -> 332
~ -[BLTSectionConfigurationItem initWithDictionary:] : 1796 -> 1792
~ -[BLTSectionConfigurationInternal coordinationTypeForSectionID:subtype:category:] : 808 -> 804
~ ___116-[BLTSettingSyncSendQueue sendSectionSubtypeParameterIcons:sectionID:waitForAcknowledgement:spoolToFile:completion:]_block_invoke : 884 -> 880
~ ___58-[BLTPingHandlerHolder pingWithBulletin:notification:ack:]_block_invoke_4 : 116 -> 112
~ -[BLTPingSubscriber sendBulletinSummary:forBulletin:destinations:] : 668 -> 664
~ -[BLTPingSubscriberManager _loadPingSubscriberBundles:] : 644 -> 640
~ -[BLTSendQueueSerializer cleanup] : 696 -> 692
~ -[BLTSectionInfoListBridgeProvider _loadOverridesChangedSince:] : 1048 -> 1044
~ -[BLTSyncSupportedAppList init] : 1128 -> 1124
~ -[BLTSyncSupportedAppList supportedBundleIDsFromRecords:nonSyncSupportedBundleIDs:] : 692 -> 688
~ _BLTSyncSupportedBundleIDsFromProxies : 716 -> 712
~ +[NRDevice(VersionFactories) versionForString:] : 380 -> 396
~ +[BBBulletinRequest(protobuf) bulletinRequestFromProtobuf:] : 3964 -> 3956
~ -[BLTPBCommunicationContext dictionaryRepresentation] : 1176 -> 1172
~ -[BLTPBCommunicationContext writeTo:] : 804 -> 800
~ -[BLTPBCommunicationContext copyWithZone:] : 952 -> 948
~ -[BLTPBCommunicationContext mergeFrom:] : 848 -> 844
~ -[BLTSectionInfoListAccessorySettingsProvider _providerForSetting:] : 40 -> 36
~ -[BLTSectionInfoSyncCoordinator initWithAlertingSectionIDs:infoProvider:] : 636 -> 632
~ -[PBCodable(Redactor) _redact:] : 1024 -> 1016
~ -[BLTAlertStateTester willNanoPresentNotificationForSectionInfo:subsectionIDs:isWristDetectDisabled:hasSectionIDOptedOutOfCoordination:hasSectionIDOptedForwardOnly:ignoresDowntime:isCritical:] : 1048 -> 1044
~ -[BLTPBSectionBulletinList dictionaryRepresentation] : 440 -> 436
~ -[BLTPBSectionBulletinList writeTo:] : 308 -> 304
~ -[BLTPBSectionBulletinList copyWithZone:] : 356 -> 352
~ -[BLTPBSectionBulletinList mergeFrom:] : 308 -> 304
~ -[BLTBulletinSendQueueAttachmentSender sendAttachmentsWithSender:timeout:completion:] : 596 -> 592
~ ___76-[BLTBulletinSendQueue sendRequest:withTimeout:isTrafficRestricted:didSend:]_block_invoke : 680 -> 676
~ ___42-[BLTBulletinSendQueue _queue_performSend]_block_invoke_7 : 248 -> 244
~ ___42-[BLTBulletinSendQueue _queue_performSend]_block_invoke_8 : 316 -> 308
~ -[BLTRemotePingSubscriberService _connect] : 592 -> 588
~ -[BBCommunicationContext(protobuf) blt_protobuf] : 680 -> 676
~ -[BBSectionInfo(BLTSettingSyncLevel) bltApplyNotificationLevel:] : 392 -> 388
~ ___61-[BLTSectionInfoListDisableAllProvider reloadWithCompletion:]_block_invoke_2 : 448 -> 444
~ ___104-[BLTSectionInfoListDisableAllProvider sectionInfoObserver:updatedSectionInfoForSectionIDs:transaction:]_block_invoke : 428 -> 424
~ -[BLTPBFullBulletinList dictionaryRepresentation] : 404 -> 400
~ -[BLTPBFullBulletinList writeTo:] : 276 -> 272
~ -[BLTPBFullBulletinList copyWithZone:] : 316 -> 312
~ -[BLTPBFullBulletinList mergeFrom:] : 260 -> 256
~ -[BLTIDSService defaultPairedDevice] : 308 -> 304
~ ___77-[BLTSettingsSendSerializer sendNowWithSent:withAcknowledgement:withTimeout:]_block_invoke_2 : 312 -> 308
~ -[BLTPBMuteAssertion dictionaryRepresentation] : 484 -> 480
~ -[BLTPBMuteAssertion writeTo:] : 324 -> 320
~ -[BLTPBMuteAssertion copyWithZone:] : 372 -> 368
~ -[BLTPBMuteAssertion mergeFrom:] : 336 -> 332
~ -[BLTTestIDSService _callDelegateActionForProtobuf:delegate:identifier:type:isResponse:] : 356 -> 352
~ -[BLTPBSectionInfo dictionaryRepresentation] : 2732 -> 2728
~ -[BLTPBSectionInfo writeTo:] : 1616 -> 1612
~ -[BLTPBSectionInfo copyWithZone:] : 1936 -> 1932
~ -[BLTPBSectionInfo mergeFrom:] : 1844 -> 1840
~ ___43-[BLTSectionInfoList reloadWithCompletion:]_block_invoke_5 : 540 -> 536
~ -[BLTSectionInfoList updateSectionInfoForSectionIDs:transaction:] : 520 -> 516
~ -[BLTSectionInfoList overrides] : 372 -> 368
~ -[BLTSectionInfoList originalSettings] : 340 -> 336
~ -[BLTSectionInfoList overriddenSettings] : 368 -> 364
~ -[BLTSectionInfoList settingsDescriptionForSectionIDs:] : 624 -> 620
~ -[BBSectionInfoSettings(protobuf) applySectionInfoSettingsFromProtobuf:] : 724 -> 720
~ -[BBSectionInfoSettings(protobuf) blt_protobuf] : 744 -> 740
~ -[BLTBulletinDistributor _attachAttachment:attachmentType:toBulletin:] : 856 -> 852
~ ___48-[BLTBulletinDistributor handleAction:bulletin:]_block_invoke : 1912 -> 1908
~ ___98-[BLTBulletinDistributor willSendLightsAndSirensWithRecordID:inPhoneSection:systemApp:completion:]_block_invoke : 836 -> 832
~ -[BLTLightsAndSirensReplyInfoCache _firstReplyInfoWithNoDidPlayStateWithReplyToken:] : 340 -> 336
~ -[BLTLightsAndSirensReplyInfoCache _firstReplyInfoWithNoReplyWithReplyToken:] : 352 -> 348
~ -[BLTLightsAndSirensReplyInfoCache _checkCache] : 608 -> 604
~ ___60-[BLTSectionInfoListEnableAllProvider reloadWithCompletion:]_block_invoke_2 : 476 -> 472
~ ___103-[BLTSectionInfoListEnableAllProvider sectionInfoObserver:updatedSectionInfoForSectionIDs:transaction:]_block_invoke : 452 -> 448
~ -[BLTSettingSync _sendSyncSupportedAppListWithInstalled:removed:] : 1244 -> 1240
~ ___72-[BLTSettingSync sendSectionInfosWithSectionIDs:completion:spoolToFile:]_block_invoke : 1212 -> 1204
~ ___55-[BLTSettingSync _callReloadBBCompletionsForSectionID:]_block_invoke : 292 -> 288
~ +[BLTPBBulletin(BBBulletin) bulletinWithBBBulletin:sockPuppetAppBundleID:observer:feed:teamID:universalSectionID:shouldUseExpirationDate:replyToken:gizmoLegacyPublisherBulletinID:gizmoLegacyCategoryID:gizmoSectionID:gizmoSectionSubtype:useUserInfoForContext:removeSubtitleForOlderWatches:shouldRespectDNDStatus:] : 6548 -> 6524
~ ___108+[BLTPBBulletin(BBBulletin) _addAttachmentsFromBBBulletin:toBLTPBBulletin:observer:attachOption:completion:]_block_invoke : 964 -> 960
~ ___36-[BLTMuteSync _cleanMuteIdentifiers]_block_invoke : 360 -> 356
~ ___43-[BLTMuteSync _loadMutedSectionIdentifiers]_block_invoke : 592 -> 588
~ -[BLTMuteSync _queue_sync] : 592 -> 588
~ _BBSectionInfoFromBLTPBSectionInfo : 1396 -> 1392
~ _BBSectionIconFromBLTPBSectionIcon : 380 -> 376
~ _BLTPBSectionInfoFromBBSectionInfoForDeviceSize : 1576 -> 1572
~ _BLTPBSectionIconFromBBSectionIconForDeviceSize : 1256 -> 1264
~ -[NSString(hex) hex] : 188 -> 204
~ ___61-[BLTBulletinDistributorSubscriberList pingWithBulletin:ack:]_block_invoke : 252 -> 248
~ ___70-[BLTBulletinDistributorSubscriberList pingWithRecordID:forSectionID:]_block_invoke : 252 -> 248
~ ___60-[BLTBulletinDistributorSubscriberList subscribedSectionIDs]_block_invoke : 292 -> 288
~ ___67-[BLTBulletinDistributorSubscriberList hasSubscribersForSectionID:]_block_invoke : 304 -> 300
~ -[BLTBulletinDistributorSubscriberList _removeSubscribersWithMachServiceName:exceptFor:] : 408 -> 404
~ -[NSArray(BLTNSNullRemoval) objectWithNSNulls:] : 740 -> 732
~ -[BLTPBSectionIcon dictionaryRepresentation] : 404 -> 400
~ -[BLTPBSectionIcon writeTo:] : 276 -> 272
~ -[BLTPBSectionIcon copyWithZone:] : 316 -> 312
~ -[BLTPBSectionIcon mergeFrom:] : 260 -> 256
~ -[BLTPBSetSectionInfoRequest writeTo:] : 308 -> 304
~ -[BLTPBSetSectionInfoRequest copyWithZone:] : 356 -> 352
~ -[BLTPBSetSectionInfoRequest mergeFrom:] : 332 -> 328
~ -[BBSectionIcon(debugging) descriptionBuilderWithMultilinePrefix:] : 364 -> 360
~ sub_24f274e14 -> sub_25095cc34 : 248 -> 240
~ sub_24f277ec4 -> sub_25095fcdc : 280 -> 276
```
