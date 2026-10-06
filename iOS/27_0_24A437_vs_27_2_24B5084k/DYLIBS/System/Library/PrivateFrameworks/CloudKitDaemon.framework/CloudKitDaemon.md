## CloudKitDaemon

> `/System/Library/PrivateFrameworks/CloudKitDaemon.framework/CloudKitDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3dceb4` | `0x3ec364` | **`+0xf4b0`** |
| `__TEXT.__eh_frame` | `0x3178` | `0x3ba8` | **`+0xa30`** |
| `__TEXT.__oslogstring` | `0x3275f` | `0x32f64` | **`+0x805`** |
| `__TEXT.__unwind_info` | `0xcf10` | `0xd1b8` | **`+0x2a8`** |
| `__TEXT.__swift5_typeref` | `0x1f5f` | `0x21a1` | **`+0x242`** |
| `__TEXT.__const` | `0x4c18` | `0x4e08` | **`+0x1f0`** |
| `__AUTH_CONST.__const` | `0x51e8` | `0x53a8` | **`+0x1c0`** |
| `__AUTH_CONST.__auth_got` | `0x2178` | `0x2310` | **`+0x198`** |
| `__DATA.__data` | `0x1dc8` | `0x1ef0` | **`+0x128`** |
| `__AUTH_CONST.__objc_const` | `0x4ad60` | `0x4ae60` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x316d4` | `0x3177c` | **`+0xa8`** |
| `__TEXT.__swift_as_cont` | `0x198` | `0x23c` | **`+0xa4`** |
| `__DATA.__bss` | `0x31a0` | `0x3220` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x8a4` | `0x918` | **`+0x74`** |
| `__AUTH.__objc_data` | `0x53a0` | `0x5410` | **`+0x70`** |
| `__TEXT.__swift_as_ret` | `0x108` | `0x16c` | **`+0x64`** |
| `__DATA_CONST.__got` | `0x2040` | `0x2090` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x130b0` | `0x13100` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x1248` | `0x1298` | **`+0x50`** |
| `__TEXT.__cstring` | `0x2b0d5` | `0x2b11e` | **`+0x49`** |
| `__TEXT.__constg_swiftt` | `0x1a80` | `0x1ac0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x99e8` | `0x9a18` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x1106` | `0x1136` | **`+0x30`** |
| `__TEXT.__swift_as_entry` | `0x138` | `0x164` | **`+0x2c`** |
| `__AUTH.__data` | `0x5b0` | `0x5d8` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0xc86c` | `0xc894` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x238c0` | `0x238e0` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x2268` | `0x2248` | **`-0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x14e8` | `0x14f0` | **`+0x8`** |
| `__DATA_DIRTY.__objc_ivar` | `0x1970` | `0x1978` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1a8c` | `0x1a90` | **`+0x4`** |
| `__TEXT.__swift5_proto` | `0x324` | `0x328` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x134` | `0x138` | **`+0x4`** |

### Other Changes

```diff

-2710.120.0.0.0
+2720.14.0.0.0

+  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

+  - /System/Library/PrivateFrameworks/ShareReporting.framework/ShareReporting

+  - /usr/lib/swift/libswiftOSLog.dylib

-  Functions: 20667
-  Symbols:   2949
-  CStrings:  8475
+  Functions: 20972
+  Symbols:   3030
+  CStrings:  8514
Symbols:
+ _$s10Foundation3URLV14absoluteStringSSvg
+ _$s10Foundation3URLVs23CustomStringConvertibleAAMc
+ _$s10Foundation4DataV19base64EncodedString7optionsSSSo27NSDataBase64EncodingOptionsV_tF
+ _$s10Foundation4DateV21timeIntervalSince1970Sdvg
+ _$s12FeatureFlags02isA7EnabledySbAA0aB3Key_pF
+ _$s12FeatureFlags0aB3KeyMp
+ _$s12FeatureFlags0aB3KeyP6domains12StaticStringVvgTq
+ _$s12FeatureFlags0aB3KeyP7features12StaticStringVvgTq
+ _$s14ShareReporting18SRReportingServiceC010SRCloudKitA0V21dataAvailabilityStage9urlParsed15metadataFetched13shareAccepted0G4SyncAeC016SRJunkReportDatahI0O_AC011SRURLParsedS0VSgAC010SRMetadatamS0VSgAC07SRShareoS0VSgAC06SRDatapS0VSgtcfC
+ _$s14ShareReporting18SRReportingServiceC010SRCloudKitA0VMa
+ _$s14ShareReporting18SRReportingServiceC010SRCloudKitA10JunkReportV5shareAeC0efA0V_tcfC
+ _$s14ShareReporting18SRReportingServiceC010SRCloudKitA10JunkReportVMa
+ _$s14ShareReporting18SRReportingServiceC12SRLookupInfoV12emailAddress11phoneNumber12userRecordIDAESSSg_A2ItcfC
+ _$s14ShareReporting18SRReportingServiceC12SRLookupInfoVMa
+ _$s14ShareReporting18SRReportingServiceC12shouldReport3forSbAC21SRRegistrationContextV_tYaKFTjTu
+ _$s14ShareReporting18SRReportingServiceC13SRParticipantV12userIdentity13participantID4role16acceptanceStatus10permission19isApprovedRequester011dateAddedToA0AeC06SRUserG0V_SSS3iSbSdtcfC
+ _$s14ShareReporting18SRReportingServiceC13SRParticipantVMa
+ _$s14ShareReporting18SRReportingServiceC13SRParticipantVMn
+ _$s14ShareReporting18SRReportingServiceC14SRDataSyncDataV5zonesAESDySSAC6SRZoneVG_tcfC
+ _$s14ShareReporting18SRReportingServiceC14SRDataSyncDataVMa
+ _$s14ShareReporting18SRReportingServiceC14SRDataSyncDataVMn
+ _$s14ShareReporting18SRReportingServiceC14SRUserIdentityV10lookupInfoAeC08SRLookupH0V_tcfC
+ _$s14ShareReporting18SRReportingServiceC14SRUserIdentityVMa
+ _$s14ShareReporting18SRReportingServiceC15SRURLParsedDataV8shareURLAESS_tcfC
+ _$s14ShareReporting18SRReportingServiceC15SRURLParsedDataVMa
+ _$s14ShareReporting18SRReportingServiceC15SRURLParsedDataVMn
+ _$s14ShareReporting18SRReportingServiceC19SRShareAcceptedDataV10recordName6zoneID12creationDate012modificationM016publicPermission12participants15flattenedFieldsAESS_SSS2dSiSayAC13SRParticipantVGSayAC7SRFieldVGtcfC
+ _$s14ShareReporting18SRReportingServiceC19SRShareAcceptedDataVMa
+ _$s14ShareReporting18SRReportingServiceC19SRShareAcceptedDataVMn
+ _$s14ShareReporting18SRReportingServiceC20hasAnyRegisteredURLsSbyYaKFTjTu
+ _$s14ShareReporting18SRReportingServiceC21SRMetadataFetchedDataVMa
+ _$s14ShareReporting18SRReportingServiceC21SRMetadataFetchedDataVMn
+ _$s14ShareReporting18SRReportingServiceC21SRRegistrationContextV5shareAE10Foundation3URLV_tcfC
+ _$s14ShareReporting18SRReportingServiceC21SRRegistrationContextVMa
+ _$s14ShareReporting18SRReportingServiceC33SRJunkReportDataAvailabilityStageO13shareAcceptedyA2EmFWC
+ _$s14ShareReporting18SRReportingServiceC33SRJunkReportDataAvailabilityStageO8dataSyncyA2EmFWC
+ _$s14ShareReporting18SRReportingServiceC33SRJunkReportDataAvailabilityStageOMa
+ _$s14ShareReporting18SRReportingServiceC6SRZoneV16zoneCapabilities12parentZoneID7recordsAESiSg_SSSgSayAC8SRRecordVGtcfC
+ _$s14ShareReporting18SRReportingServiceC6SRZoneVMa
+ _$s14ShareReporting18SRReportingServiceC6SRZoneVMn
+ _$s14ShareReporting18SRReportingServiceC6report3for3andyAC010SRCloudKitA10JunkReportV_AC21SRRegistrationContextVtYaKFTjTu
+ _$s14ShareReporting18SRReportingServiceC7SRAssetV16assetWrappingKey0F18ReferenceSignature0fJ0AE10Foundation4DataV_AKSgALtcfC
+ _$s14ShareReporting18SRReportingServiceC7SRAssetVMa
+ _$s14ShareReporting18SRReportingServiceC7SRAssetVMn
+ _$s14ShareReporting18SRReportingServiceC7SRFieldV8fieldKey11isEncrypted9valueType0J05assetAESS_SbS2SSgAC7SRAssetVSgtcfC
+ _$s14ShareReporting18SRReportingServiceC7SRFieldVMa
+ _$s14ShareReporting18SRReportingServiceC7SRFieldVMn
+ _$s14ShareReporting18SRReportingServiceC8SRRecordV10recordName012parentRecordG012creationDate012modificationK0011creatorUserI2ID012lastModifiedniO015flattenedFieldsAESS_SSSgS2dS2SSayAC7SRFieldVGtcfC
+ _$s14ShareReporting18SRReportingServiceC8SRRecordVMa
+ _$s14ShareReporting18SRReportingServiceC8SRRecordVMn
+ _$s14ShareReporting18SRReportingServiceCACycfC
+ _$s14ShareReporting18SRReportingServiceCMa
+ _$s14ShareReporting18SRReportingServiceCMn
+ _$s8CloudKit15CKLogReportJunk2os6LoggerVvg
+ _$sSd5write2toyxz_ts16TextOutputStreamRzlF
+ _$sSo18CKShareParticipantC8CloudKitE13participantIDSSvg
+ _$sSo20CKDReportJunkServiceC14CloudKitDaemonEABycfC
+ _$sSo20CKDReportJunkServiceC14CloudKitDaemonEABycfc
+ _$sSo20CKDReportJunkServiceCMa
+ _$sSo8CKRecordC8CloudKitE7allKeysSaySSGyF
+ _$sSo8CKRecordC8CloudKitEySo0A5Value_pSgSScig
+ _$sSo8NSObjectC10ObjectiveCE13_rawHashValue4seedS2i_tF
+ _$sSo8NSObjectC10ObjectiveCE2eeoiySbAB_ABtFZ
+ _$ss10_HashTableV8nextHole9atOrAfterAB6BucketVAF_tF
+ _$ss10__CocoaSetV12makeIteratorAB0D0CyF
+ _$ss10__CocoaSetV5countSivg
+ _$ss10__CocoaSetV6member3foryXlSgyXl_tF
+ _$ss10__CocoaSetV8IteratorC4nextyXlSgyF
+ _$ss10__CocoaSetV8containsySbyXlF
+ _$ss11_SetStorageC4copy8originalAByxGs05__RawaB0C_tFZ
+ _$ss11_SetStorageC6resize8original8capacity4moveAByxGs05__RawaB0C_SiSbtFZ
+ _$ss11_SetStorageC7convert_8capacityAByxGs07__CocoaA0V_SitFZ
+ _$ss11_SetStorageCMn
+ _$ss12StaticStringVMn
+ _$ss50ELEMENT_TYPE_OF_SET_VIOLATES_HASHABLE_REQUIREMENTSys5NeverOypXpF
+ _OBJC_CLASS_$_CKDRecordPCSData
+ _OBJC_CLASS_$_CKDReportJunkService
+ _OBJC_METACLASS_$_CKDRecordPCSData
+ _OBJC_METACLASS_$_CKDReportJunkService
+ __swiftEmptySetSingleton
+ __swift_FORCE_LOAD_$_swiftOSLog
CStrings:
+ "Account status: %{public}@, id: %{public}@, email: %{private}@"
+ "Asset doesn't have unwrapped key"
+ "Checking if record should be reported - record ID: %@"
+ "Checking if share should be reported - record ID: %@"
+ "CloudKitDaemon_Private.__CKDReportJunkService"
+ "Detected cycle in record hierarchy at %@"
+ "Detected cycle in zone hierarchy at %@"
+ "Error checking if share(%s) should be reported: %@"
+ "Error fetching PCS data found for record %@: %@"
+ "Error fetching PCS data found for share %@: %@"
+ "Error fetching PCS data found for zone %@: %@"
+ "Error obtaining a sharing identity from the public PCS for share %@, error: %@"
+ "Failed to generate shareURL for share after decrypting the share %@"
+ "Failed to get the shortToken for %@"
+ "Failed to report junk for record %@: %@"
+ "Failed to report junk for share %@: %@"
+ "Found a reportable share URL: %s"
+ "Found direct share for record %@"
+ "Found direct zone share for zone %@"
+ "Found share in record hierarchy at parent %@"
+ "Junk reporting is disabled for manatee containers"
+ "No PCS data found for record %@"
+ "No share URLs are registered with ShareReporting. Skipping junk reporting for record %@"
+ "No share URLs are registered with ShareReporting. Skipping junk reporting for share %@"
+ "No share URLs found in PCS data for record %@"
+ "No shares found for record %@"
+ "No zone PCS data found for zone %@"
+ "None of the shares are flagged for junk reporting"
+ "Parent record PCS data not found for %@"
+ "Parent zone PCS data not found for %@"
+ "Public PCS is empty in both, share and the share PCS data for share %@"
+ "Report Junk Service: Failed to report share acceptance for %@: %@"
+ "Report Junk Service: Reporting share with ID: %@ and share URL: %s"
+ "Report Junk Service: ✅ Successfully reported share acceptance for %@ at %s"
+ "Reporting junk for record with ID: %@ and share URL: %s"
+ "Share URL is not reportable: %s"
+ "ShareReportJunk"
+ "ShareURL"
+ "Successfully reported record %@ for share %s"
+ "You cannot get the URL of a share until it's been saved to the server"
- "Account status: %{public}@, id: %{public}@, email: %{public}@"
```
