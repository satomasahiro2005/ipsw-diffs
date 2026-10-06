## MessageProtection

> `/System/Library/PrivateFrameworks/MessageProtection.framework/MessageProtection`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7a5c8` | `0x7a658` | **`+0x90`** |

### Other Changes

```diff
Symbols:
+ _objc_retain_x9
- _swift_release_x27
Functions:
~ -[NGMFullDeviceIdentity(Signing) batchSign:forType:error:] : 404 -> 400
~ +[NGMFullDeviceIdentity identityWithDataRepresentation:error:] : 724 -> 720
~ -[NGMFullDeviceIdentity unsealMessageAndAttributes:signedByPublicIdentity:decryptionBlock:] : 2508 -> 2520
~ -[NGMFullDeviceIdentity eraseFromKeyChain:] : 260 -> 256
~ -[NGMFullDeviceIdentity updateWithRegisteredTicket:error:] : 448 -> 444
~ -[NGMReplayManager pruneDuplicates:tag:moc:] : 336 -> 332
~ -[NGMPBFullDeviceIdentity dictionaryRepresentation] : 460 -> 456
~ -[NGMPBFullDeviceIdentity writeTo:] : 308 -> 304
~ -[NGMPBFullDeviceIdentity copyWithZone:] : 356 -> 352
~ -[NGMPBFullDeviceIdentity mergeFrom:] : 332 -> 328
~ _$s17MessageProtection8TetraAPIC4open7message17authenticatedData4guid10sendingURI0J9PushToken09receivingK00nlM013theirIdentity8signedBy12tetraVersion10ourPrekeys0U37SigningPublicKeyCompactRepresentation15decryptionBlocky10Foundation0H0V_ATS2SSo6NSDataCSSAVSo015NGMPublicDeviceP0CSgSo0cxwY7WrapperCs6UInt32VSaySo13NGMFullPrekeyCGAVyATSg_SDys11AnyHashableVypGSgs5Error_pSgSbSAySo7NSErrorCSgGSgcSgtXEtFZ0106$sSo6NSDataCSgSo12NSDictionaryCSgSo7NSErrorCSgSAyAIGSg10ObjectiveC8ObjCBoolVIeyByd_SgIyByyyy_10Foundation4H59VSgSDys11AnyHashableVypGSgs5Error_pSgAKSbIegyd_SgIeggggg_TRAVSgSo12NSDictionaryCSgA14_A16_10ObjectiveC8ObjCBoolVIeyByd_SgIyByyyy_Tf1nnnnnnnnnnnncn_n : 10092 -> 10004
~ _$s17MessageProtection8TetraAPIC4open7message17authenticatedData4guid10sendingURI0J9PushToken09receivingK00nlM013theirIdentity8signedBy12tetraVersion10ourPrekeys0U37SigningPublicKeyCompactRepresentation15decryptionBlocky10Foundation0H0V_ATS2SSo6NSDataCSSAVSo015NGMPublicDeviceP0CSgSo0cxwY7WrapperCs6UInt32VSaySo13NGMFullPrekeyCGAVyATSg_SDys11AnyHashableVypGSgs5Error_pSgSbSAySo7NSErrorCSgGSgcSgtXEtFZ : 9764 -> 9928
~ _$s17MessageProtection17TetraRatchetStateV04openA0_10sessionDST03didD0AA0c5InnerA0Vx_10Foundation4DataVSbXESbztKAA0c5OuterA0RzlFAA0c2NodmA0V_Tg5Tm : 1824 -> 1832
~ _$ss11_StringGutsV16_deconstructUTF87scratchyXlSg5owner_xSi6lengthSb11usesScratchSb15allocatedMemorytSwSg_ts8_PointerRzlFSV_Tgq5 : 280 -> 276
~ _$ss17_NativeDictionaryV20_copyOrMoveAndResize8capacity12moveElementsySi_SbtFSS_10Foundation4DataVTg5 : 704 -> 696
~ _$ss17_NativeDictionaryV8setValue_6forKey8isUniqueyq_n_xSbtFSS_10Foundation4DataVTg5 : 388 -> 384
~ _$ss20_ArrayBufferProtocolPsE15replaceSubrange_4with10elementsOfySnySiG_Siqd__ntSlRd__7ElementQyd__AGRtzlFs01_aB0Vy17MessageProtection17TetraSessionStateVG_s15EmptyCollectionVyANGTg5Tf4nndn_n : 348 -> 344
~ _$s17MessageProtection8TetraAPIC16conversationInfo10sendingURI0G9PushToken36senderPublicKeyCompactRepresentation09receivingH00piJ00plmnO010Foundation4DataVSbcSS_So6NSDataCAMSSAoMtFZTf4nnnnnnd_n : 2076 -> 2108
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSo11CFStringRefa_yXlTt0g5Tf4g_n : 244 -> 252
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSo11CFStringRefa_ypTt0g5Tf4g_n : 236 -> 256
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_ypTt0g5Tf4g_n : 256 -> 276
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_yXlTt0g5Tf4g_n : 252 -> 276
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCs11AnyHashableV_ypTt0g5Tf4g_n : 256 -> 264
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_10Foundation4DataVTt0g5Tf4g_n : 272 -> 284
~ _$s17MessageProtection26GLTKeyDiversificationSwiftC9diversify9publicKey22trackingPreventionSalt5docIdAA014GLTDiversifiedH0CSo03SecH3Refa_10Foundation4DataVSgSStKFZTf4nnnd_n : 2300 -> 2304
~ _$s17MessageProtection26GLTKeyDiversificationSwiftC9diversify10privateKey5docId22trackingPreventionSaltSo03SecH3RefaAI_SS10Foundation4DataVtKFZTf4nnnd_n : 1504 -> 1520
~ _$s17MessageProtection16SymmetricRatchetV4data4stepAC10Foundation4DataV_AA0cD4Step_ptKcfC : 1692 -> 1704
~ _$ss12_ArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtF17MessageProtection17TetraSessionStateV_Tg5Tm : 480 -> 484
~ _$s17MessageProtection22MPPB_SKIncomingRatchetV17_protobuf_nameMap_WZ : 528 -> 516
~ _$s17MessageProtection22MPPB_SKOutgoingRatchetV17_protobuf_nameMap_WZ : 588 -> 572
~ _$sSasSQRzlE2eeoiySbSayxG_ABtFZ17MessageProtection16MPPB_KeyAndIndexV_Tt1g5 : 592 -> 608
~ _$ss22_ContiguousArrayBufferV20_consumeAndCreateNew14bufferIsUnique15minimumCapacity13growForAppendAByxGSb_SiSbtF17MessageProtection17TetraSessionStateV_Tg5Tm : 476 -> 480
~ _$s17MessageProtection16MPPB_LiteRatchetV17_protobuf_nameMap_WZ : 528 -> 516
~ _$s17MessageProtection17SKIncomingRatchetC4dataAC10Foundation4DataV_tKcfc : 2148 -> 2160
~ _$ss17_NativeDictionaryV4copyyyFSS_10Foundation4DataVTg5 : 388 -> 384
~ _$s10Foundation4DataVyACxcSTRzs5UInt8V7ElementRtzlufCs14PrefixSequenceVy9CryptoKit12SHA384DigestVG_Tt0g5 : 832 -> 824
~ _$s10Foundation4DataVyACxcSTRzs5UInt8V7ElementRtzlufcySwXEfU2_SS8UTF8ViewV_Tg5 : 692 -> 688
~ _$s17MessageProtection23TetraPB_KyberPrivateKeyV17_protobuf_nameMap_WZ : 528 -> 516
~ _$s17MessageProtection08TetraPB_cA0V17_protobuf_nameMap_WZ : 956 -> 948
~ _$s17MessageProtection028TetraPB_PaddyKeyDistributionA0V17_protobuf_nameMap_WZ : 528 -> 516
~ _$s17MessageProtection14MPPB_DARatchetV17_protobuf_nameMap_WZ : 524 -> 512
~ _$sSmsE1poiyxx_qd__tSmRd__7ElementQyd__ABRtzlFZ10Foundation4DataV_AGTt2g5 : 528 -> 532
~ _$s10Foundation4DataV6append10contentsOfyx_tSTRzs5UInt8V7ElementRtzlFSo6NSDataC_Tg5 : 1740 -> 1736
~ _$s17MessageProtection18TetraSessionStatesV07discarda5KeyOndE0019ephemeralECDHPublicG012messageIndexSb9CryptoKit4P256O0G9AgreementO06PublicG0V_s6UInt64VtF : 1728 -> 1740
~ _$s17MessageProtection18TetraSessionStatesV04openA0_11prekeysHash10sessionDST05theirC7Version10didRatchetAA0c5InnerA0VAA0cn5OuterA0V_10Foundation4DataVSgAOSbXEs6UInt32VSbztKF : 1664 -> 1688
~ _$s17MessageProtection18TetraSessionStatesV11makeDefaultyyAA0cD5StateVF : 2652 -> 2672
~ _$s17MessageProtection18TetraSessionStatesV03hasD21WithCompatibleVersionSbyF : 980 -> 972
~ _$s17MessageProtection8TetraAPIC13openNoRatchet010tetraOuterA010sessionDST4guid17authenticatedData10ourPrekeys13theirIdentity0H7Version8signedBy15decryptionBlockyAA0cfgiA0V_10Foundation0N0VSbXESSARSaySo13NGMFullPrekeyCGSo015NGMPublicDeviceR0Cs6UInt32VSo0C23PublicSigningKeyWrapperCyARSg_SDys11AnyHashableVypGSgs5Error_pSgSbSAySo7NSErrorCSgGSgcSgtXEtFZTf4nnndnnnnnd_n : 3796 -> 3772
~ _$sSa6append10contentsOfyqd__n_t7ElementQyd__RszSTRd__lF17MessageProtection17TetraSessionStateV_SayAGGTg5 : 312 -> 316
~ _$sSa6append10contentsOfyqd__n_t7ElementQyd__RszSTRd__lFs5UInt8V_10Foundation4DataVTg5 : 720 -> 716
~ _$s17MessageProtection5I2OSP5value15outputByteCount10Foundation4DataVSi_SitF : 1180 -> 1168
```
