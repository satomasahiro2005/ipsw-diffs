## SocialLayer

> `/System/Library/PrivateFrameworks/SocialLayer.framework/SocialLayer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd855c` | `0xd862c` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x3530` | `0x3538` | **`+0x8`** |

### Other Changes

```diff

-212.100.1.0.0
+213.100.1.0.0
Functions:
~ ___57-[SLHighlightsCache _fetchAndUpdateHighlightsImmediately]_block_invoke : 524 -> 520
~ -[SLShareableContentActionHandler performActions:] : 244 -> 240
~ -[SLHighlight initWithPortraitHighlight:error:] : 972 -> 968
~ -[SLDCloudKitSyncWriter fetchAndProcessFreshHighlights] : 4048 -> 4036
~ -[RPCompanionLinkClient(DeviceFiltration) sl_phoneAndPadDevices] : 432 -> 428
~ -[SLHighlightCenter latestHighlightDate] : 328 -> 324
~ -[SLHighlightCenter highlightsRankingScore] : 344 -> 340
~ -[SLHighlightCenter fetchAttributionsForHighlight:] : 572 -> 568
~ -[SLHighlightCenter appProtectionSubjectsChanged:forSubscription:] : 332 -> 328
~ -[SLDCollaborationAttributionViewRenderer newSnowglobeImageWithCGImages:] : 596 -> 592
~ -[SLDCollaborationAttributionViewRenderer newAvatarImageForConversationDrawingMetadata:allowSnowglobe:allowMonogram:] : 824 -> 820
~ -[SLDCollaborationAttributionViewRenderer newAvatarImage] : 784 -> 780
~ -[SLAttributionView setHideMenuItemTitle:] : 476 -> 472
~ -[SLHighlight portraitHighlight] : 480 -> 476
~ -[SLHighlight initWithDictionary:] : 1192 -> 1188
~ -[SLHighlight dictionaryRepresentation] : 1360 -> 1356
~ -[SLAttribution initWithPortraitAttribution:error:] : 1556 -> 1552
~ -[SLAttribution portraitAttribution] : 676 -> 672
~ -[SLAttribution initWithDictionary:] : 1348 -> 1344
~ -[SLAttribution dictionaryRepresentation] : 1540 -> 1536
~ -[SLDHighlightPillRenderer _renderAvatarsInContext:] : 1860 -> 1856
~ -[SLDCloudDocsService generateURLToCollaborationHighlightCache] : 456 -> 452
~ -[SLSyndicationController _sendCurrentRemovalsToDaemonAndDisconnect] : 944 -> 940
~ ___54-[SLHighlightsCache didDeleteHighlightsOrAttributions]_block_invoke : 1204 -> 1192
~ -[SLHighlightsCache _notifyDelegatesWithNotificationType:withHighlights:] : 868 -> 856
~ -[SLDCollaborationHandshakeService _removeIdentities:fromMetadata:] : 404 -> 400
~ -[SLDCollaborationHandshakeService _doesMetadata:containAllOf:] : 340 -> 336
~ -[SLDCollaborationHandshakeService _doesMetadata:containAnyOf:] : 308 -> 304
~ -[SLDShareableContentService visibleApplications] : 788 -> 784
~ -[SLDShareableContentService visibleApplicationForSceneIdentifier:] : 356 -> 352
~ -[SLDFaceTimeService initiateTUConversationForAttributionIdentifier:videoEnabled:completion:] : 2468 -> 2464
~ -[SLDPillService _attributionsFromIDs:appID:] : 396 -> 392
~ -[SLHighlightPillView _attributionIdentifiers] : 520 -> 516
~ -[SLHighlightPillView refreshContextMenuItems] : 1096 -> 1092
~ -[SLDCloudKitSyncPersistence reset] : 328 -> 324
~ _SLDValidateSupplementaryData : 564 -> 560
~ ___55-[SLDCloudKitSyncWriter fetchAndProcessFreshHighlights]_block_invoke.547 -> ___55-[SLDCloudKitSyncWriter fetchAndProcessFreshHighlights]_block_invoke.562 : 1400 -> 1396
~ -[SLDCloudKitSyncWriter _recordIDsFromStrings:] : 504 -> 500
~ -[SLDCloudKitSyncWriter checkForAppChangesNow] : 680 -> 676
~ -[SLDCloudKitSyncReader updateServerAppsIfNecessary] : 1048 -> 1044
~ -[SLDCloudKitSyncReader garbageCollectNow] : 1412 -> 1396
~ -[SLDCloudKitSyncReader getHighlightsInternalForApplicationIdentifier:] : 3776 -> 3764
~ ___63-[SLDCloudKitSyncReader getHighlightsForApplicationIdentifier:]_block_invoke : 616 -> 612
~ -[SLDCollaborationAttributionViewSlotTag initWithTitle:attributions:placeholderGlyphConfiguration:maxWidth:variant:isPlaceholder:] : 872 -> 868
~ +[SLDCollaborationAttributionViewSlotTag conversationDrawingMetadataForAttributions:] : 1416 -> 1412
~ +[SLDCollaborationAttributionViewSlotTag _personOtherThanPerson:inArray:] : 312 -> 308
~ +[SLDCollaborationAttributionViewSlotTag displayNamesForPersons:] : 360 -> 356
~ +[SLDCollaborationAttributionViewSlotTag recipientsForAttribution:] : 448 -> 444
~ -[SLDCollaborationNoticeService _handlesForAttributionIdentifiers:appID:] : 568 -> 564
~ _SLPersonArrayContainsPerson : 284 -> 280
~ _SLURLMinusFragmentForCKURLs : 588 -> 584
~ -[SLDHighlightPillSlotTag _generateCollaborationSendersForSingleAttribution:maxSendersToDisplay:] : 1100 -> 1096
~ -[SLDHighlightPillSlotTag _generateCollaborationSendersForMultipleAttributions:maxSendersToDisplay:] : 1236 -> 1228
~ -[SLDHighlightPillSlotTag _generateSendersWithDisplayPolicyForAttributions:maxSendersToDisplay:] : 1128 -> 1120
~ -[SLDHighlightPillSlotTag _personOtherThanPerson:inArray:] : 312 -> 308
~ -[SLDRemoteRenderingService lostConnection:] : 368 -> 364
~ -[SLDRemoteRenderingService _connection:onlyNeedsViewWithIdentifier:] : 476 -> 472
~ -[SLDRemoteRenderingService _connectionTouchedView:] : 696 -> 692
~ -[SLShareableContentActionHandler sceneWithIdentifier:] : 488 -> 484
~ -[SLShareableContentActionHandler fulfillMetadataAction:itemProviders:linkMetadata:highlightURL:initiatorRequest:] : 732 -> 728
~ ___87-[NSArray(TransformUtilities) sl_mapAsynchronouslyOnQueue:transform:completionHandler:]_block_invoke_2 : 336 -> 332
~ -[SLDActiveCallService _lookupActiveTUConversation] : 336 -> 332
~ -[SLDisambiguationCollectionViewController viewDidLayoutSubviews] : 576 -> 572
~ ___68-[SLDisambiguationCollectionViewController updateDataSourceSnapshot]_block_invoke : 536 -> 532
~ -[SLDisambiguationCollectionViewController createAttributionMapWithHighlight:] : 412 -> 408
~ -[SLDCollaborationAttributionViewService _attributionsFromIDs:appID:] : 396 -> 392
~ -[NSItemProvider(SocialLayer) sl_representations] : 516 -> 512
~ _$ss11_StringGutsV16_deconstructUTF87scratchyXlSg5owner_xSi6lengthSb11usesScratchSb15allocatedMemorytSwSg_ts8_PointerRzlFSV_Tgq5 : 280 -> 276
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_ypTt0g5Tf4g_n : 256 -> 276
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSo11CFStringRefaSg_ypTt0g5Tf4g_n : 236 -> 256
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSo11CFStringRefaSg_ADTt0g5Tf4g_n : 240 -> 248
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSo21NSAttributedStringKeya_ypTt0g5Tf4g_n : 236 -> 256
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSo11CFStringRefa_SiTt0g5Tf4g_n : 232 -> 240
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_So16SWPersonIdentityCTt0g5Tf4g_n : 252 -> 276
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSo11CFStringRefa_ypTt0g5Tf4g_n : 236 -> 256
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSo11CFStringRefa_12CoreGraphics7CGFloatVTt0g5Tf4g_n : 232 -> 252
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSo11CFStringRefa_SDyADSgypGTt0g5Tf4g_nTm : 236 -> 244
~ _$ss5ErrorP11SocialLayerE17underlyingCKErrorsAA_pSgvg : 1308 -> 1316
~ _$ss17_NativeDictionaryV4copyyyF11SocialLayer38CloudKitCollaborationInitiationRequestC9RecipientO_AD0hI15ResponsePayloadVTg5Tm : 604 -> 600
~ _$ss17_NativeDictionaryV4copyyyFSS_So36CKDeviceToDeviceShareInvitationTokenCTg5Tm : 348 -> 340
~ _$sShyShyxGqd__nc7ElementQyd__RszSTRd__lufCSS_SaySSGTt0g5Tf4g_n : 152 -> 164
~ _$sShyShyxGqd__nc7ElementQyd__RszSTRd__lufC11SocialLayer38CloudKitCollaborationInitiationRequestC9RecipientO_SayAHGTt0g5Tf4g_n : 160 -> 176
~ _$sShyShyxGqd__nc7ElementQyd__RszSTRd__lufC11SocialLayer38CloudKitCollaborationInitiationRequestC8ResponseV9RecipientO_SayAJGTt0g5Tf4g_n : 400 -> 420
~ _$sShyShyxGqd__nc7ElementQyd__RszSTRd__lufC11SocialLayer42FileProviderCollaborationInitiationRequestC9RecipientO_SayAHGTt0g5Tf4g_n : 160 -> 176
~ _$sShyShyxGqd__nc7ElementQyd__RszSTRd__lufC11SocialLayer42FileProviderCollaborationInitiationRequestC8ResponseV9RecipientV_SayAJGTt0g5Tf4g_n : 400 -> 420
~ _$s11SocialLayer38CloudKitCollaborationInitiationRequestC8ResponseV28recipientPayloadsByRecipientSDyAC0L0OAA0efH7PayloadVGvg : 324 -> 328
~ _$s11SocialLayer38CloudKitCollaborationInitiationRequestC8ResponseV16invitationTokensSDySSSo36CKDeviceToDeviceShareInvitationTokenCGvg : 1528 -> 1548
~ _$s11SocialLayer38CloudKitCollaborationInitiationRequestC7handlesShySo8TUHandleCGvg : 352 -> 356
~ _$sSlsE3mapySayqd__Gqd__7ElementQzqd_0_YKXEqd_0_YKs5ErrorRd_0_r0_lFShySo8TUHandleCG_11SocialLayer38CloudKitCollaborationInitiationRequestC9RecipientOs5NeverOTg504$s11e7Layer38ghijk58C10recipients12shareOptions0I018containerSetupInfoACShySo8d70CG_So021_SWCollaborationShareJ0CSo7CKShareCSo011CKContainerlM0CtcfcAC9L8OAIXEfU_Tf1cn_n : 828 -> 820
~ _$s11SocialLayer38CloudKitCollaborationInitiationRequestC08initiateE6Legacy33_16144F4078A0F0A7F307CC106E3EAB76LLAC8ResponseVyYaKFTY0_ : 944 -> 948
~ _$s11SocialLayer38CloudKitCollaborationInitiationRequestC25addAllParticipantsAndSave33_16144F4078A0F0A7F307CC106E3EAB76LLyyYaKFTY0_ : 1320 -> 1328
~ _$s11SocialLayer38CloudKitCollaborationInitiationRequestC23buildResponseRecipients33_16144F4078A0F0A7F307CC106E3EAB76LLShyAC0I0V9RecipientOGyKF : 1580 -> 1584
~ _$s11SocialLayer38CloudKitCollaborationInitiationRequestC15currentResponseAC0I0VSgyF : 5108 -> 5196
~ _$s11SocialLayer38CloudKitCollaborationInitiationRequestC24buildResponseForShareURL33_16144F4078A0F0A7F307CC106E3EAB76LLAC0I0VyKF : 944 -> 948
~ _$sSh8_VariantV6insertySb8inserted_x17memberAfterInserttxnF11SocialLayer38CloudKitCollaborationInitiationRequestC9RecipientO_TB5Tm : 760 -> 752
~ _$ss10_NativeSetV4copyyyFSS_Tg5 : 344 -> 340
~ _$ss10_NativeSetV4copyyyF11SocialLayer38CloudKitCollaborationInitiationRequestC9RecipientO_Tg5Tm : 344 -> 340
~ ___swift_closure_destructorTm : 124 -> 132
~ _$s11SocialLayer28CollaborationAttributionViewC19renderRemoteContent03forB9ContextID5style5yieldySi_So12UISSlotStyleCSbSo0n3AnyH0_pctFyyScMYccfU_ : 2596 -> 2556
~ _$s11SocialLayer10MerkleTreeC14nodeIdentitiesACSayAA12NodeIdentityOG_tcfc : 460 -> 472
~ _$s11SocialLayer10MerkleTreeC6verify4nodeSay9CryptoKit12SHA256DigestVGSg_SiSgtAA12NodeIdentityO_tF : 1008 -> 992
~ _$s11SocialLayer10MerkleTreeC05buildD033_50F5DFBABDF0A8EA4479DF8532875D64LL5nodesAA0C4NodeCSgSayAHG_tF : 544 -> 576
~ _$sSa6append10contentsOfyqd__n_t7ElementQyd__RszSTRd__lF9CryptoKit12SHA256DigestV_SayAGGTg5Tm : 360 -> 364
~ _$s11SocialLayer18KeyQueryControllerC16publicKeysAndTPS3for18documentIdentifierSay9CryptoKit4P256O7SigningO06PublicC0VG4keys_10Foundation4DataV22trackingPreventionSalttSgSS_SStYaKFTY2_ : 1464 -> 1512
~ _$s11SocialLayer18KeyQueryControllerC011localPublicC09CryptoKit4P256O7SigningO0gC0VSgyYaKFTY2_ : 928 -> 932
~ _$ss21_arrayConditionalCastySayq_GSgSayxGr0_lF11SocialLayer8Endpoint_p_So11IDSEndpointCTg5 : 300 -> 308
~ _$sSo20IDSIDQueryControllerC11SocialLayerE19currentRemoteDevice3for7service5queueSayAC8Endpoint_pGSS_SSSo012OS_dispatch_J0CtYaFTY0_ : 1320 -> 1312
~ _$ss15_arrayForceCastySayq_GSayxGr0_lFSo11IDSEndpointC_11SocialLayer8Endpoint_pTg5 : 488 -> 496
~ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtF11SocialLayer38CloudKitCollaborationInitiationRequestC8ResponseV9RecipientO_Tg5Tm : 480 -> 484
~ _$s10Foundation4DataVyACxcSTRzs5UInt8V7ElementRtzlufcySwXEfU2_SS8UTF8ViewV_Tg5 : 692 -> 688
~ ___swift_closure_destructor : 224 -> 232
~ _$s11SocialLayer23PersonIdentityGeneratorC08generateC20IdentitiesForHandles7handles18documentIdentifierSDySSSo08SWPersonD0CGSaySSG_SStYaKFTY2_ : 1552 -> 1564
~ _$ss17_NativeDictionaryV7_delete2atys10_HashTableV6BucketV_tF11SocialLayer38CloudKitCollaborationInitiationRequestC9RecipientO_AI0lM15ResponsePayloadVTg5 : 556 -> 552
~ _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtF11SocialLayer12NodeIdentityO_Tg5Tm : 476 -> 480
~ _$s11SocialLayer23PersonIdentityGeneratorC23merkleTreeForPublicKeysyAA06MerkleG0CSay9CryptoKit4P256O7SigningO0I3KeyVGFTf4nd_n : 496 -> 508
~ _$s11SocialLayer34formattedDisplayNameListAndNOthers6prefix5names7nOthers12localizationSSAA21AttributionTextPrefixO_SaySSGSiSSSgtF : 4784 -> 4884
~ _$s11SocialLayer32attributedStringSplitByLineBreak02inD0SaySo012NSAttributedD0CGAE_tF : 440 -> 456
~ _$s11SocialLayer11PillMetricsC26fromSenderAttributedString33_00C2B47D0280335DFFDBB3BC8927527ALL3for7metrics9multilineSo012NSAttributedH0CSo09NSMutablegH0C09localizedH0_SaySo8_NSRangeVG20baseFontTargetRangesAP06sendervwX0t_AA09HighlightC13MetricVariantAELL_pSbtFZTf4nnnndd_g : 1452 -> 1464
~ _$s11SocialLayer11PillMetricsC35localizedFromSenderAttributedString3for6prefix9multiline03maxG5Names12localizationSo09NSMutablehI0C0eI0_SaySo8_NSRangeVG20baseFontTargetRangesAO06senderstU0tSo012SLDHighlightC7SlotTagC_AA21AttributionTextPrefixOSbSiSSSgtFZTf4nnnnnd_n : 2404 -> 2416
~ _$sSlsE3mapySayqd__Gqd__7ElementQzqd_0_YKXEqd_0_YKs5ErrorRd_0_r0_lFShySo8TUHandleCG_11SocialLayer42FileProviderCollaborationInitiationRequestC9RecipientOs5NeverOTg504$s11e7Layer42ghijk95C3url12shareOptions10recipients8metadataAC10Foundation3URLV_So021_SWCollaborationShareJ0CShySo8d23CGSo0O8MetadataCtcfcAC9L8OANXEfU_Tf1cn_n : 828 -> 820
~ _$s11SocialLayer42FileProviderCollaborationInitiationRequestC8ResponseV28recipientPayloadsByRecipientSDyAC0L0OAA0efH7PayloadVGvg : 1796 -> 1800
~ _$s11SocialLayer42FileProviderCollaborationInitiationRequestC13buildResponse33_4405377E1915922A7E90727A9BA79EBBLL4from8metadataAC0I0VSgSo7CKShareC_So23SWCollaborationMetadataCtF : 6104 -> 6176
~ _$s11SocialLayer42FileProviderCollaborationInitiationRequestC08initiateE20WithAnonymousSupport33_4405377E1915922A7E90727A9BA79EBBLLAC8ResponseVyYaKFTY0_ : 1632 -> 1648
~ _$s11SocialLayer42FileProviderCollaborationInitiationRequestC08initiateE20WithAnonymousSupport33_4405377E1915922A7E90727A9BA79EBBLLAC8ResponseVyYaKFTY2_ : 2788 -> 2784
~ _$s11SocialLayer42FileProviderCollaborationInitiationRequestC08initiateE6Legacy33_4405377E1915922A7E90727A9BA79EBBLLAC8ResponseVyYaKFTY0_ : 1212 -> 1216
~ _$s11SocialLayer42FileProviderCollaborationInitiationRequestC08initiateE6Legacy33_4405377E1915922A7E90727A9BA79EBBLLAC8ResponseVyYaKFTY2_ : 1672 -> 1660
~ _$s11SocialLayer42FileProviderCollaborationInitiationRequestC08initiateE6Legacy33_4405377E1915922A7E90727A9BA79EBBLLAC8ResponseVyYaKFTY6_ : 1264 -> 1268
~ _$s11SocialLayer42FileProviderCollaborationInitiationRequestC24initiateOTLCollaborationAC8ResponseVyYaKFTY0_ : 1748 -> 1752
~ _$s11SocialLayer42FileProviderCollaborationInitiationRequestC24initiateOTLCollaborationAC8ResponseVyYaKFTY4_ : 1468 -> 1452
~ _$s11SocialLayer42FileProviderCollaborationInitiationRequestC24initiateOTLCollaborationAC8ResponseVyYaKFTY6_ : 3204 -> 3092
~ ___swift_closure_destructorTm : 140 -> 148
```
