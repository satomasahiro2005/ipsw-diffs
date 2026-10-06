## GameControllerSettings

> `/System/Library/PrivateFrameworks/GameControllerSettings.framework/GameControllerSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d52c` | `0x3d4a4` | **`-0x88`** |
| `__AUTH_CONST.__auth_got` | `0x5e8` | `0x5f0` | **`+0x8`** |

### Other Changes

```diff

-14.0.14.0.0
+14.0.17.0.0

-  Symbols:   3254
+  Symbols:   3255
Symbols:
+ _objc_retain_x9
Functions:
~ -[GCSGamesCollection gameWithBundleIdentifier:] : 336 -> 332
~ -[GCSGamesCollection updateGames:] : 796 -> 792
~ -[NSDictionary(GameControllerSettings) initWithJSONObject:] : 472 -> 468
~ -[NSDictionary(GameControllerSettings) jsonObject] : 440 -> 436
~ +[NSDictionary(GameControllerSettings) _gcs_jsonObjectForSerializableDictionary:] : 452 -> 448
~ +[NSDictionary(GameControllerSettings) _gcs_serializableDictionaryForJsonObject:withValuesOfClass:] : 552 -> 540
~ -[NSArray(GameControllerSettings) initWithJSONObject:] : 420 -> 416
~ -[NSArray(GameControllerSettings) jsonObject] : 376 -> 372
~ +[NSArray(GameControllerSettings) _gcs_jsonObjectForSerializableArray:] : 376 -> 372
~ +[NSArray(GameControllerSettings) _gcs_serializableArrayForJsonObject:withElementsOfClass:] : 424 -> 420
~ -[GCSCopilotFusedControllersCollection copilotFusedControllerForControllerIdentifier:] : 408 -> 404
~ -[GCSCopilotFusedControllersCollection copilotFusedControllerForFusedControllerIdentifier:] : 336 -> 332
~ -[GCSCopilotFusedControllersCollection copilotFusedControllerForPilotControllerIdentifier:] : 336 -> 332
~ -[GCSCopilotFusedControllersCollection copilotFusedControllerForCopilotControllerIdentifier:] : 336 -> 332
~ -[GCSCopilotFusedControllersCollection updateCopilotFusedControllers:] : 648 -> 644
~ -[GCSCopilotFusedControllersCollection _unitTest_saveCopilotFusedControllers:] : 448 -> 444
~ +[GCSProfile elementMappingsFrom:for:] : 704 -> 700
~ -[GCSProfile(GCSJSONSerializable) elementMappingsWithJSONDictionary:] : 480 -> 476
~ -[GCSControllersCollection controllerForPersistentIdentifier:] : 336 -> 332
~ -[GCSControllersCollection updateControllers:] : 648 -> 644
~ -[GCSElementMapping(NSSecureCoding) initWithCoder:] : 276 -> 296
~ -[GCSElementMapping(NSSecureCoding) encodeWithCoder:] : 188 -> 208
~ -[GCSProfilesCollection profileForIdentifier:] : 360 -> 356
~ -[GCSProfilesCollection updateProfiles:] : 704 -> 700
~ -[GCSDevicesCollection deviceForPersistentIdentifier:] : 336 -> 332
~ -[GCSDevicesCollection updateDevices:] : 648 -> 644
~ -[GCSTombstonesCollection tombstoneForIdentifier:] : 336 -> 332
~ -[GCSTombstonesCollection updateTombstones:] : 632 -> 628
~ -[GCSGame profileForController:profiles:] : 396 -> 392
~ -[GCSMouseProfilesCollection updateMouseProfiles:] : 400 -> 396
~ -[GCSMouseProfilesCollection mouseProfileForBundleIdentifier:] : 340 -> 336
~ _$s22GameControllerSettings21GCSSettingsSwiftStoreC29WriteJSONObjectsAndTombstones024_CFAA34E2C0D30440D64BFB4L7EAA132CLL2to3key5valueySo14GCUserDefaults_p_SSSayxG10collection_SaySo12GCSTombstoneCGSg10tombstonesttSo19GCSJSONSerializableRzlFZSo9GCSDeviceC_Tt3g5Tm : 872 -> 864
~ _$sSasSQRzlE2eeoiySbSayxG_ABtFZSo9GCSDeviceC_Tt1g5Tm : 580 -> 592
~ _$s22GameControllerSettings21GCSSettingsSwiftStoreC15ReadJSONObjects024_CFAA34E2C0D30440D64BFB4J7EAA132CLL4from3keySayxGSgSo14GCUserDefaults_p_SStSo19GCSJSONSerializableRzlFZSo15GCSMouseProfileC_Tt1g5 : 472 -> 476
~ _$s22GameControllerSettings21GCSSettingsSwiftStoreC16WriteJSONObjects024_CFAA34E2C0D30440D64BFB4J7EAA132CLL2to3key5valueySo14GCUserDefaults_p_SSSayxGtSo19GCSJSONSerializableRzlFZSo15GCSMouseProfileC_Tt2g5 : 396 -> 408
~ _$s22GameControllerSettings21GCSSettingsSwiftStoreC7SettingV8_Storage024_CFAA34E2C0D30440D64BFB4J7EAA132CLLCfD : 372 -> 368
~ _$s22GameControllerSettings21GCSSettingsSwiftStoreC7SettingV8_Storage024_CFAA34E2C0D30440D64BFB4J7EAA132CLLC12observeValue10forKeyPath2of6change7contextySSSg_ypSgSDySo05NSKeyq6ChangeS0aypGSgSvSgtF : 4376 -> 4372
~ _$ss11_StringGutsV16_deconstructUTF87scratchyXlSg5owner_xSi6lengthSb11usesScratchSb15allocatedMemorytSwSg_ts8_PointerRzlFSV_Tgq5 : 280 -> 276
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_SaySo13GCSJSONObject_pGTt0g5Tf4g_n : 252 -> 276
~ ___swift_closure_destructor : 144 -> 152
~ _$s22GameControllerSettings23GCSControllerParametersV10controllerSo0D0Cvg : 1260 -> 1228
~ _$s22GameControllerSettings23GCSControllerParametersV7buttonsSDySSAA010GCSElementE0VGvg : 644 -> 636
~ _$s22GameControllerSettings23GCSControllerParametersV5dpadsSDySSAA010GCSElementE0VGvg : 644 -> 636
~ _$s22GameControllerSettings23GCSControllerParametersV0E033_BA8096211BC287E3F2D26A89DD687E6DLLV10controllerAFSo0D0C_tcfC : 1172 -> 1148
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_22GameControllerSettings20GCSElementParametersVTt0gq5Tf4g_n : 308 -> 332
~ _$s22GameControllerSettings27GCSElementMappingParametersVwstTm : 148 -> 140
~ _$s22GameControllerSettings27GCSElementMappingParametersV0F033_4C1C2385A608CE9F94525AE429C0A7CCLLVwst : 84 -> 76
~ _$s22GameControllerSettings015GCSCopilotFusedB10ParametersVwstTm : 84 -> 80
~ _$s22GameControllerSettings19GCSDeviceParametersV0E033_F06E3BA60FC0FCD738E6BC20D1C1ED73LLV4hash4intoys6HasherVz_tF : 196 -> 204
~ _$s22GameControllerSettings19GCSDeviceParametersV6deviceSo0D0Cvg : 708 -> 700
~ _$s22GameControllerSettings19GCSDeviceParametersV13inputElementsSDySSAA0d12InputElementE0VGSgvg : 504 -> 496
~ _$sSasSQRzlE2eeoiySbSayxG_ABtFZSS_Tt1g5 : 136 -> 144
~ _$s22GameControllerSettings19GCSDeviceParametersV0E033_F06E3BA60FC0FCD738E6BC20D1C1ED73LLV6deviceAFSo0D0C_tcfCTf4nd_n : 684 -> 676
~ _$s22GameControllerSettings20GCSElementParametersVwstTm : 88 -> 84
~ _$s22GameControllerSettings30GCSControllerProfileParametersV7profileSo10GCSProfileCvg : 1012 -> 1004
~ _$s22GameControllerSettings30GCSControllerProfileParametersV15elementMappingsSDySSAA017GCSElementMappingF0VGvg : 576 -> 568
~ _$s22GameControllerSettings30GCSControllerProfileParametersV0F033_F88DE8798CBD6E72CFD31A17E101165DLLV7profileAFSo10GCSProfileC_tcfC : 1124 -> 1104
~ _$sSo30GCSGameControllerShortcutGrantVs25ExpressibleByArrayLiteralSCsACP05arrayH0x0gH7ElementQzd_tcfCTW : 172 -> 176
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_10Foundation4UUIDVTt0gq5Tf4g_n : 452 -> 448
~ _$sSD17dictionaryLiteralSDyxq_Gx_q_td_tcfCSS_So20GCSCompatibilityModeaTt0gq5Tf4g_n : 252 -> 276
```
