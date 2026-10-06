## findmydeviced

> `/usr/libexec/findmydeviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4d2500` | `0x4cd1a8` | **`-0x5358`** |
| `__DATA.__bss` | `0x26960` | `0x281a0` | **`+0x1840`** |
| `__TEXT.__const` | `0x45586` | `0x45f46` | **`+0x9c0`** |
| `__DATA_CONST.__const` | `0x1ce50` | `0x1d550` | **`+0x700`** |
| `__TEXT.__eh_frame` | `0x2587c` | `0x25428` | **`-0x454`** |
| `__TEXT.__oslogstring` | `0x1c339` | `0x1c689` | **`+0x350`** |
| `__TEXT.__swift5_fieldmd` | `0x686c` | `0x6b88` | **`+0x31c`** |
| `__TEXT.__constg_swiftt` | `0x563c` | `0x5860` | **`+0x224`** |
| `__TEXT.__auth_stubs` | `0x4e50` | `0x4c50` | **`-0x200`** |
| `__DATA.__data` | `0xaa60` | `0xabd0` | **`+0x170`** |
| `__TEXT.__swift5_reflstr` | `0x54ae` | `0x55de` | **`+0x130`** |
| `__DATA_CONST.__auth_got` | `0x2738` | `0x2638` | **`-0x100`** |
| `__TEXT.__swift5_proto` | `0x1310` | `0x13cc` | **`+0xbc`** |
| `__DATA_CONST.__got` | `0x1aa0` | `0x1b20` | **`+0x80`** |
| `__TEXT.__cstring` | `0xdd9e` | `0xddfe` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x4c72` | `0x4cce` | **`+0x5c`** |
| `__DATA_CONST.__auth_ptr` | `0x1e28` | `0x1dd8` | **`-0x50`** |
| `__TEXT.__swift5_assocty` | `0xc08` | `0xc58` | **`+0x50`** |
| `__TEXT.__swift5_types` | `0x7b4` | `0x7f4` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x13c0` | `0x1384` | **`-0x3c`** |
| `__TEXT.__swift_as_cont` | `0x1f84` | `0x1f54` | **`-0x30`** |
| `__DATA.__objc_const` | `0x1e760` | `0x1e780` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x203c9` | `0x203e9` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0xd30` | `0xd14` | **`-0x1c`** |
| `__TEXT.__swift5_acfuncs` | `0x104` | `0xf0` | **`-0x14`** |
| `__TEXT.__swift5_builtin` | `0x1e0` | `0x1f4` | **`+0x14`** |
| `__TEXT.__swift5_capture` | `0x1d58` | `0x1d48` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xf410` | `0xf400` | **`-0x10`** |
| `__TEXT.__swift5_mpenum` | `0x11c` | `0x124` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-481.30.6.7.1
+482.30.6.14.2

-  Functions: 16055
-  Symbols:   2719
-  CStrings:  10279
+  Functions: 16109
+  Symbols:   2671
+  CStrings:  10295
Symbols:
+ _$s10Foundation13__DataStorageC12_deallocatorySv_SitcSgvg
+ _$s12FindMyCrypto9PublicKeyVMn
+ _$s19FindMyDaemonSupport0C0C10identifier7profile18registerAlarmEvent0G18NotificationEvents8servicesACSS_SSS2bSayAA20ActorServiceProtocol_pGyYaYbctYaKcfC
+ _$s19FindMyDaemonSupport0C0C10identifier7profile18registerAlarmEvent0G18NotificationEvents8servicesACSS_SSS2bSayAA20ActorServiceProtocol_pGyYaYbctYaKcfCTu
+ _$s23FindMyDeviceAccessories22LocalFindableAccessoryV06SharedefG0V10identifier12serialNumber13systemVersion8vendorId07productO018connectionMaterial0Q3KeyAE10Foundation4UUIDV_S2SS2iAC010ConnectionR0VAM4DataVSgtcfC
+ _$s23FindMyDeviceAccessories22LocalFindableAccessoryV06SharedefG0VMa
+ _$s23FindMyDeviceAccessories22LocalFindableAccessoryV06SharedefG0VMn
+ _$s23FindMyDeviceAccessories22LocalFindableAccessoryV06SharedefG0VSEAAMc
+ _$s23FindMyDeviceAccessories22LocalFindableAccessoryV06SharedefG0VSeAAMc
+ _$s23FindMyDeviceAccessories22LocalFindableAccessoryV10identifier5model13systemVersion21accessorySerialNumber09alternatemN05fmnId06vendorQ007productQ012pairingEpoch18connectionMaterial10privateKey09symmetricY00t7PrivateY012sharedSecretAC10Foundation4UUIDV_S2SAC0mN0VAVSgATS2is5Int64VAC010ConnectionW0VAR4DataVA1_A1_SgA2_tcfC
+ _$s23FindMyDeviceAccessories40LocalFindableAccessoryServerXPCInterfaceP06sharedD0SayAA0efG0V06SharedefG0VGyYaKFTq
+ _$s23FindMyDeviceAccessories40LocalFindableAccessoryServerXPCInterfaceP06sharedD0SayAA0efG0V06SharedefG0VGyYaKFTqTE
+ _$s23FindMyDeviceAccessories40LocalFindableAccessoryServerXPCInterfaceP06sharedG010identifierAA0efG0V06SharedefG0V10Foundation4UUIDV_tYaKFTq
+ _$s23FindMyDeviceAccessories40LocalFindableAccessoryServerXPCInterfaceP06sharedG010identifierAA0efG0V06SharedefG0V10Foundation4UUIDV_tYaKFTqTE
+ _$sSaMa
+ _$ss22KeyedDecodingContainerV6decode_6forKeys6UInt64VAFm_xtKF
+ _$ss22KeyedEncodingContainerV6encode_6forKeyys6UInt64V_xtKF
- _$s10Foundation11JSONDecoderC20DateDecodingStrategyO6customyAeA0C0Vs7Decoder_pKccAEmFWC
- _$s10Foundation11JSONDecoderC20DateDecodingStrategyOMa
- _$s10Foundation11JSONDecoderC20dateDecodingStrategyAC04DatedE0OvsTj
- _$s10Foundation4DataV15_RepresentationO15reserveCapacityyySiF
- _$s10Foundation4DateV10FindMyBaseE5epochACs5Int64V_tcfC
- _$s12FindMyCrypto0C5ErrorO16invalidSignatureyA2CmFWC
- _$s12FindMyCrypto0C5ErrorOMa
- _$s12FindMyCrypto0C5ErrorOs0D0AAMc
- _$s12FindMyCrypto13P256PublicKeyVAA0F12RepresentingAAMc
- _$s12FindMyCrypto13P256PublicKeyVMa
- _$s12FindMyCrypto14P256PrivateKeyV06publicF0AA0d6PublicF0Vvg
- _$s19FindMyDaemonSupport0C0C10identifier7profile18registerAlarmEvent8servicesACSS_SSSbSayAA20ActorServiceProtocol_pGyYaYbctYaKcfC
- _$s19FindMyDaemonSupport0C0C10identifier7profile18registerAlarmEvent8servicesACSS_SSSbSayAA20ActorServiceProtocol_pGyYaYbctYaKcfCTu
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C17EventFetchPayloadV6SourceO7unknownyA2GmFWC
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C17EventFetchPayloadV6SourceO8rawValueAGSgs6UInt32V_tcfC
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C17EventFetchPayloadV6SourceOMa
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C17EventFetchPayloadV6SourceOMn
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C17EventFetchPayloadV6source8location9timestamp010attachedToC10IdentifierA2E6SourceO_AE8LocationV10Foundation4DateVAN4UUIDVSgtcfC
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C17EventFetchPayloadV8LocationV8latitude9longitude18horizontalAccuracy9timestampAGSd_S2d10Foundation4DateVtcfC
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C17EventFetchPayloadV8LocationVMa
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C17EventFetchPayloadVMa
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C17EventFetchPayloadVMn
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C17EventFetchPayloadVSEAAMc
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C17EventFetchPayloadVSeAAMc
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C19EventPublishPayloadV12LocationInfoV8location0M2TsAG10Foundation4DataV_AJ4DateVtcfC
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C19EventPublishPayloadV12LocationInfoVMa
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C19EventPublishPayloadV12LocationInfoVMn
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C19EventPublishPayloadV2id7keyType4mode12locationInfoAE10Foundation4DataV_s5UInt8VSSSayAE08LocationP0VGtcfC
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C19EventPublishPayloadVMa
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C19EventPublishPayloadVMn
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C19EventPublishPayloadVSEAAMc
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV0C19EventPublishPayloadVSeAAMc
- _$s23FindMyDeviceAccessories22LocalFindableAccessoryV10identifier5model13systemVersion21accessorySerialNumber09alternatemN05fmnId06vendorQ007productQ012pairingEpoch18connectionMaterial10privateKey09symmetricY0AC10Foundation4UUIDV_S2SAC0mN0VATSgARS2is5Int64VAC010ConnectionW0VAP4DataVA_tcfC
- _$s23FindMyDeviceAccessories51LocalFindableAccessorySearchPartyServerXPCInterfaceP019acknowlegePublishOfC6Events11publishDatey10Foundation0Q0V_tYaKFTq
- _$s23FindMyDeviceAccessories51LocalFindableAccessorySearchPartyServerXPCInterfaceP019acknowlegePublishOfC6Events11publishDatey10Foundation0Q0V_tYaKFTqTE
- _$s23FindMyDeviceAccessories51LocalFindableAccessorySearchPartyServerXPCInterfaceP05fetchc9EventsForG11IdentifiersySDy10Foundation4UUIDVAA0efG0V0C17EventFetchPayloadVGSayAGGYaKFTq
- _$s23FindMyDeviceAccessories51LocalFindableAccessorySearchPartyServerXPCInterfaceP05fetchc9EventsForG11IdentifiersySDy10Foundation4UUIDVAA0efG0V0C17EventFetchPayloadVGSayAGGYaKFTqTE
- _$s23FindMyDeviceAccessories51LocalFindableAccessorySearchPartyServerXPCInterfaceP19unpublishedPayloads5sinceSayAA0efG0V0C19EventPublishPayloadVG10Foundation4DateV_tYaKFTq
- _$s23FindMyDeviceAccessories51LocalFindableAccessorySearchPartyServerXPCInterfaceP19unpublishedPayloads5sinceSayAA0efG0V0C19EventPublishPayloadVG10Foundation4DateV_tYaKFTqTE
- _$s23FindMyServerInteraction15ResponseHeadersVMa
- _$s23FindMyServerInteraction15ResponseHeadersVySSSgSScig
- _$s23FindMyServerInteraction8ResponseV6headerAA0E7HeadersVvg
- _$s9CryptoKit3AESO3GCMO4open_5using10Foundation4DataVAE9SealedBoxV_AA12SymmetricKeyVtKFZ
- _$s9CryptoKit3AESO3GCMO4seal_5using5nonceAE9SealedBoxVx_AA12SymmetricKeyVAE5NonceVSgtK10Foundation12DataProtocolRzlFZ
- _$s9CryptoKit3AESO3GCMO5NonceV10Foundation15ContiguousBytesAAMc
- _$s9CryptoKit3AESO3GCMO5NonceV4dataAGx_tKc10Foundation12DataProtocolRzlufC
- _$s9CryptoKit3AESO3GCMO5NonceVMa
- _$s9CryptoKit3AESO3GCMO5NonceVMn
- _$s9CryptoKit3AESO3GCMO5NonceVSTAAMc
- _$s9CryptoKit3AESO3GCMO9SealedBoxV10ciphertext10Foundation4DataVvg
- _$s9CryptoKit3AESO3GCMO9SealedBoxV3tag10Foundation4DataVvg
- _$s9CryptoKit3AESO3GCMO9SealedBoxV5nonce10ciphertext3tagAgE5NonceV_xq_tKc10Foundation12DataProtocolRzAmNR_r0_lufC
- _$s9CryptoKit3AESO3GCMO9SealedBoxV5nonceAE5NonceVvg
- _$s9CryptoKit3AESO3GCMO9SealedBoxVMa
- _$s9CryptoKit4P256O7SigningO10PrivateKeyV17rawRepresentationAGx_tKc10Foundation15ContiguousBytesRzlufC
- _$s9CryptoKit4P256O7SigningO10PrivateKeyV9signature3forAE14ECDSASignatureVx_tK10Foundation12DataProtocolRzlF
- _$s9CryptoKit4P256O7SigningO10PrivateKeyVMa
- _$s9CryptoKit4P256O7SigningO14ECDSASignatureV17rawRepresentation10Foundation4DataVvg
- _$sSDyxq_GSesSeRzSeR_rlMc
- _$sST19underestimatedCountSivgTj
- _$sST32withContiguousStorageIfAvailableyqd__Sgqd__SRy7ElementQzGKXEKlFTj
- _$ss15ContiguousArrayV28_allocateBufferUninitialized15minimumCapacitys01_abD0VyxGSi_tFZ
- _$ss22_minimumMergeRunLengthyS2iF
- _$ss28SingleValueDecodingContainerP6decodeys5Int64VAEmKFTj
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "%s Key rotation failed with status %{public}s"
+ "%{public}s failed to verify FMNID, error: %@"
+ "%{public}s pairing unavailable after verify FMNID, returning result: %s"
+ "%{public}s verify FMNID result: %s"
+ "Accessory %{private,mask.hash}s is already on the expected index"
+ "BluetoothAccessoryPairing: User opted out of pairing accessory: %{public}s"
+ "Error building shared accessory record for %{public}s: %{public}@"
+ "Error fetching shared accessories: %@"
+ "Error fetching shared accessory using identifier %s: %@"
+ "Failure fetching product information for %s, error: %@. Returning cached information: %s"
+ "Fetching fresh product information for product %s succeeded. Response %s."
+ "Getting all shared accessories from %{public}ld shared beacons"
+ "Increasing expected key index to %s, current key index %s, for accessory %{private,mask.hash}s"
+ "Key rotation completed successfully for %{private,mask.hash}s"
+ "Key rotation failed with invalid index %{private,mask.hash}s Current index from accesory: %llu"
+ "Key rotation on the accessory completed successfully for %{private,mask.hash}s"
+ "Missing key in package from getShare response"
+ "Missing key packages in getShare response"
+ "PencilAutoPairing: User has not opted in of pairing accessory: %{public}s"
+ "PencilAutoPairing: Verify FMNID result: %s"
+ "Received keyAlignmentConfigResponse status: %{public}s primaryIndex: %{public}llu. Beacon %{private,mask.hash}s Command %{public}s."
+ "Received keyAlignmentResponse: %s"
+ "Shared accessory %{public}s has invalid IRK %s"
+ "deviceEventFinderKey"
+ "deviceEventKeyCache"
+ "localFindable"
+ "sharedAccessories()"
+ "sharedAccessory(identifier:)"
+ "symmetricKey privateKey "
- "Acknowledging publish of %{public}ld device events with publish date %{public}s"
- "Duplicate values for key: '"
- "Error acknowledging publish of device events with publish date %{public}s: %@"
- "Error fetching device events with identifiers %{public}s: %@"
- "Error obtaining unpublished payloads since %{public}s: %@"
- "Failed creating payload for device event, error: %{public}@"
- "Failed decryption of device event, error: %@"
- "Failed obtaining encryption keys for device event, error: %{public}@"
- "Invalid device identifier %{public}s when getting device event encryption keys"
- "No accessory record found for device identifier %{public}s"
- "PencilAutoPairing: User opted out of pairing accessory: %{public}s"
- "Swift/NativeDictionary.swift"
- "Unrecognized accessory identifier in location payload: %s"
```
