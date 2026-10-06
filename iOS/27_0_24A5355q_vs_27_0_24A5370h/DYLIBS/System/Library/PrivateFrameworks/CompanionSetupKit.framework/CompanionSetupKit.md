## CompanionSetupKit

> `/System/Library/PrivateFrameworks/CompanionSetupKit.framework/CompanionSetupKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d2d7c` | `0x3f2b18` | **`+0x1fd9c`** |
| `__TEXT.__eh_frame` | `0x324e8` | `0x34300` | **`+0x1e18`** |
| `__TEXT.__unwind_info` | `0x11220` | `0x12808` | **`+0x15e8`** |
| `__DATA.__bss` | `0x438f0` | `0x44df0` | **`+0x1500`** |
| `__TEXT.__const` | `0x2be60` | `0x2cbe0` | **`+0xd80`** |
| `__AUTH_CONST.__const` | `0x17d98` | `0x18608` | **`+0x870`** |
| `__TEXT.__cstring` | `0xaf1d` | `0xb6dd` | **`+0x7c0`** |
| `__TEXT.__swift5_typeref` | `0x92b8` | `0x972c` | **`+0x474`** |
| `__TEXT.__oslogstring` | `0x81b5` | `0x8505` | **`+0x350`** |
| `__TEXT.__swift5_reflstr` | `0x773e` | `0x7a4e` | **`+0x310`** |
| `__TEXT.__swift5_fieldmd` | `0x8cac` | `0x8f50` | **`+0x2a4`** |
| `__DATA.__data` | `0x8718` | `0x8990` | **`+0x278`** |
| `__TEXT.__swift_as_cont` | `0x3250` | `0x34bc` | **`+0x26c`** |
| `__TEXT.__swift5_capture` | `0x341c` | `0x3634` | **`+0x218`** |
| `__AUTH_CONST.__objc_const` | `0x6e58` | `0x7018` | **`+0x1c0`** |
| `__TEXT.__constg_swiftt` | `0x6780` | `0x68a8` | **`+0x128`** |
| `__AUTH.__data` | `0x5348` | `0x5450` | **`+0x108`** |
| `__TEXT.__swift_as_ret` | `0x13c0` | `0x14c0` | **`+0x100`** |
| `__TEXT.__swift_as_entry` | `0xf8c` | `0x1044` | **`+0xb8`** |
| `__TEXT.__swift5_proto` | `0x21c0` | `0x2268` | **`+0xa8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1790` | `0x1820` | **`+0x90`** |
| `__TEXT.__swift5_assocty` | `0x1468` | `0x14e0` | **`+0x78`** |
| `__AUTH_CONST.__auth_got` | `0x24a0` | `0x2510` | **`+0x70`** |
| `__TEXT.__swift5_types` | `0xa58` | `0xa78` | **`+0x20`** |
| `__DATA.__common` | `0x3b0` | `0x3c8` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x11a0` | `0x11b8` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x280` | `0x294` | **`+0x14`** |
| `__AUTH.__objc_data` | `0x1c88` | `0x1c90` | **`+0x8`** |

### Other Changes

```diff

-520.0.0.0.0
+524.0.16.0.0

+  - /System/Library/Frameworks/CloudKit.framework/CloudKit

-  Functions: 17278
-  Symbols:   4805
-  CStrings:  2213
+  Functions: 17750
+  Symbols:   4900
+  CStrings:  2284
Symbols:
+ _CFPreferencesAppSynchronize
+ _CKCurrentUserDefaultName
+ _CKErrorDomain
+ _OBJC_CLASS_$_CKContainer
+ _OBJC_CLASS_$_CKContainerID
+ _OBJC_CLASS_$_CKContainerOptions
+ _OBJC_CLASS_$_CKFetchRecordZonesOperation
+ _OBJC_CLASS_$_CKOperationConfiguration
+ _OBJC_CLASS_$_CKRecordZoneID
+ _OBJC_CLASS_$_IDSDevice
+ ___swift_closure_destructor.132Tm
+ ___swift_closure_destructor.194Tm
+ ___swift_closure_destructor.293Tm
+ ___swift_closure_destructor.313Tm
+ ___swift_closure_destructor.325Tm
+ ___swift_closure_destructor.348Tm
+ ___swift_closure_destructor.371Tm
+ ___swift_closure_destructor.38Tm
+ ___swift_closure_destructor.423Tm
+ ___swift_closure_destructor.696Tm
+ ___swift_closure_destructor.89Tm
+ ___swift_memcpy3_1
+ ___swift_memcpy65_8
+ ___unnamed_59
+ _associated conformance 17CompanionSetupKit11CSKStepMiscC7CommandO26TimeZoneSelectedCodingKeys33_F4ACDF69DF259FE441766389F8BE5133LLOSHAASQ
+ _associated conformance 17CompanionSetupKit11CSKStepMiscC7CommandO26TimeZoneSelectedCodingKeys33_F4ACDF69DF259FE441766389F8BE5133LLOs0J3KeyAAs23CustomStringConvertible
+ _associated conformance 17CompanionSetupKit11CSKStepMiscC7CommandO26TimeZoneSelectedCodingKeys33_F4ACDF69DF259FE441766389F8BE5133LLOs0J3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 17CompanionSetupKit21CSKSetupAppleTVClientC7CommandO18OsUpdateCodingKeys33_3C267E0A714BB497C52E44E1E98B05B0LLOSHAASQ
+ _associated conformance 17CompanionSetupKit21CSKSetupAppleTVClientC7CommandO18OsUpdateCodingKeys33_3C267E0A714BB497C52E44E1E98B05B0LLOs0J3KeyAAs23CustomStringConvertible
+ _associated conformance 17CompanionSetupKit21CSKSetupAppleTVClientC7CommandO18OsUpdateCodingKeys33_3C267E0A714BB497C52E44E1E98B05B0LLOs0J3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 17CompanionSetupKit21CSKSetupAppleTVServerC7CommandO18OsUpdateCodingKeys33_D80D7C23C92088CF46EDAF3CD79D0C6DLLOSHAASQ
+ _associated conformance 17CompanionSetupKit21CSKSetupAppleTVServerC7CommandO18OsUpdateCodingKeys33_D80D7C23C92088CF46EDAF3CD79D0C6DLLOs0J3KeyAAs23CustomStringConvertible
+ _associated conformance 17CompanionSetupKit21CSKSetupAppleTVServerC7CommandO18OsUpdateCodingKeys33_D80D7C23C92088CF46EDAF3CD79D0C6DLLOs0J3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 17CompanionSetupKit21CSKStepOSUpdateClientCAA19CSKCommandPerformerAA7CommandAaDP_SE
+ _associated conformance 17CompanionSetupKit21CSKStepOSUpdateClientCAA19CSKCommandPerformerAA7CommandAaDP_Se
+ _associated conformance 17CompanionSetupKit21CSKStepOSUpdateClientCAA19CSKCommandPerformerAA7CommandAaDP_s23CustomStringConvertible
+ _associated conformance 17CompanionSetupKit21CSKStepOSUpdateServerC7CommandO10CodingKeys33_FB139EFB838DBEE703D14346C465A503LLOSHAASQ
+ _associated conformance 17CompanionSetupKit21CSKStepOSUpdateServerC7CommandO10CodingKeys33_FB139EFB838DBEE703D14346C465A503LLOs0H3KeyAAs23CustomStringConvertible
+ _associated conformance 17CompanionSetupKit21CSKStepOSUpdateServerC7CommandO10CodingKeys33_FB139EFB838DBEE703D14346C465A503LLOs0H3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 17CompanionSetupKit21CSKStepOSUpdateServerC7CommandO24UpdateAnsweredCodingKeys33_FB139EFB838DBEE703D14346C465A503LLOSHAASQ
+ _associated conformance 17CompanionSetupKit21CSKStepOSUpdateServerC7CommandO24UpdateAnsweredCodingKeys33_FB139EFB838DBEE703D14346C465A503LLOs0J3KeyAAs23CustomStringConvertible
+ _associated conformance 17CompanionSetupKit21CSKStepOSUpdateServerC7CommandO24UpdateAnsweredCodingKeys33_FB139EFB838DBEE703D14346C465A503LLOs0J3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 17CompanionSetupKit21CSKStepOSUpdateServerCAA19CSKCommandPerformerAA7CommandAaDP_SE
+ _associated conformance 17CompanionSetupKit21CSKStepOSUpdateServerCAA19CSKCommandPerformerAA7CommandAaDP_Se
+ _associated conformance 17CompanionSetupKit21CSKStepOSUpdateServerCAA19CSKCommandPerformerAA7CommandAaDP_s23CustomStringConvertible
+ _associated conformance SC11CKErrorCodeLeV10Foundation13CustomNSErrorSCs5Error
+ _associated conformance SC11CKErrorCodeLeV10Foundation21_BridgedStoredNSErrorSC0B0AcDP_8RawValueSYs17FixedWidthInteger
+ _associated conformance SC11CKErrorCodeLeV10Foundation21_BridgedStoredNSErrorSC0B0AcDP_AC06_ErrorB8Protocol
+ _associated conformance SC11CKErrorCodeLeV10Foundation21_BridgedStoredNSErrorSC0B0AcDP_SY
+ _associated conformance SC11CKErrorCodeLeV10Foundation21_BridgedStoredNSErrorSCAC06CustomF0
+ _associated conformance SC11CKErrorCodeLeV10Foundation21_BridgedStoredNSErrorSCAC26_ObjectiveCBridgeableError
+ _associated conformance SC11CKErrorCodeLeV10Foundation21_BridgedStoredNSErrorSCSH
+ _associated conformance SC11CKErrorCodeLeV10Foundation26_ObjectiveCBridgeableErrorSCs0F0
+ _associated conformance SC11CKErrorCodeLeVSHSCSQ
+ _associated conformance So11CKErrorCodeV10Foundation06_ErrorB8ProtocolSC01_D4TypeAcDP_AC21_BridgedStoredNSError
+ _associated conformance So11CKErrorCodeV10Foundation06_ErrorB8ProtocolSCSQ
+ _keypath_get.101Tm
+ _keypath_set.71Tm
+ _swift_getTupleTypeMetadata
+ _symbolic $s10Foundation18_ErrorCodeProtocolP
+ _symbolic $s10Foundation21_BridgedStoredNSErrorP
+ _symbolic SS10deviceName_SSSg5modelt
+ _symbolic SS18timeZoneIdentifier_SS04cityC0t
+ _symbolic Say_____G_AASg20previouslyChosenRoomSb15showsBackButtonSb19homeWasAutoselectedt 17CompanionSetupKit011CSKStepHomeC4RoomV
+ _symbolic Sbz_Xx
+ _symbolic ScCySS18timeZoneIdentifier_SS04cityC0t______pG s5ErrorP
+ _symbolic ScCySS18timeZoneIdentifier_SS04cityC0t______pGSg s5ErrorP
+ _symbolic So15CUSystemMonitorCSgXw
+ _symbolic So15CUSystemMonitorCSgXwz_Xx
+ _symbolic So7NSErrorC
+ _symbolic _____ 14CoreUtilsSwift16CUAsyncSemaphoreC
+ _symbolic _____ 14CoreUtilsSwift7CUClockV
+ _symbolic _____ 17CompanionSetupKit11CSKStepMiscC7CommandO26TimeZoneSelectedCodingKeys33_F4ACDF69DF259FE441766389F8BE5133LLO
+ _symbolic _____ 17CompanionSetupKit21CSKSetupAppleTVClientC7CommandO18OsUpdateCodingKeys33_3C267E0A714BB497C52E44E1E98B05B0LLO
+ _symbolic _____ 17CompanionSetupKit21CSKSetupAppleTVServerC7CommandO18OsUpdateCodingKeys33_D80D7C23C92088CF46EDAF3CD79D0C6DLLO
+ _symbolic _____ 17CompanionSetupKit21CSKStepOSUpdateServerC7CommandO
+ _symbolic _____ 17CompanionSetupKit21CSKStepOSUpdateServerC7CommandO10CodingKeys33_FB139EFB838DBEE703D14346C465A503LLO
+ _symbolic _____ 17CompanionSetupKit21CSKStepOSUpdateServerC7CommandO24UpdateAnsweredCodingKeys33_FB139EFB838DBEE703D14346C465A503LLO
+ _symbolic _____ SC11CKErrorCodeLeV
+ _symbolic _____ So11CKErrorCodeV
+ _symbolic _____ s8DurationV
+ _symbolic _____Sg 17CompanionSetupKit21CSKStepOSUpdateServerC
+ _symbolic _____SgXw 17CompanionSetupKit21CSKStepOSUpdateClientC
+ _symbolic ______AAt 17CompanionSetupKit16CSKStepPreflightC5EventO
+ _symbolic ______SSSg18currentNetworkNamet 17CompanionSetupKit14CSKWiFiScannerC18ScanUpdatedDetailsV
+ _symbolic ________________pIeghHgnzo_ 17CompanionSetupKit21CSKStepOSUpdateClientC AA0D9DirectionO s5ErrorP
+ _symbolic ________________pIeghHgnzo_ 17CompanionSetupKit21CSKStepOSUpdateServerC AA0D9DirectionO s5ErrorP
+ _symbolic ___________pIeghHozo_ 17CompanionSetupKit21CSKStepOSUpdateClientC s5ErrorP
+ _symbolic ___________pIeghHozo_ 17CompanionSetupKit21CSKStepOSUpdateServerC s5ErrorP
+ _symbolic ______pSgz_Xx s5ErrorP
+ _symbolic _____m 17CompanionSetupKit21CSKStepOSUpdateClientC
+ _symbolic _____m 17CompanionSetupKit21CSKStepOSUpdateServerC
+ _symbolic _____ySiG s11_SetStorageC
+ _symbolic _____y_____G 17CompanionSetupKit30CSKExternalCommandNotificationV AA21CSKStepOSUpdateClientC0E0O
+ _symbolic _____y_____G 17CompanionSetupKit30CSKExternalCommandNotificationV AA21CSKStepOSUpdateServerC0E0O
+ _symbolic _____y_____G s11_SetStorageC 17CompanionSetupKit25CSKSetupAppleTVClientStepO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 17CompanionSetupKit11CSKStepMiscC7CommandO26TimeZoneSelectedCodingKeys33_F4ACDF69DF259FE441766389F8BE5133LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 17CompanionSetupKit21CSKSetupAppleTVClientC7CommandO18OsUpdateCodingKeys33_3C267E0A714BB497C52E44E1E98B05B0LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 17CompanionSetupKit21CSKSetupAppleTVServerC7CommandO18OsUpdateCodingKeys33_D80D7C23C92088CF46EDAF3CD79D0C6DLLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 17CompanionSetupKit21CSKStepOSUpdateServerC7CommandO10CodingKeys33_FB139EFB838DBEE703D14346C465A503LLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 17CompanionSetupKit21CSKStepOSUpdateServerC7CommandO24UpdateAnsweredCodingKeys33_FB139EFB838DBEE703D14346C465A503LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 17CompanionSetupKit11CSKStepMiscC7CommandO26TimeZoneSelectedCodingKeys33_F4ACDF69DF259FE441766389F8BE5133LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 17CompanionSetupKit21CSKSetupAppleTVClientC7CommandO18OsUpdateCodingKeys33_3C267E0A714BB497C52E44E1E98B05B0LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 17CompanionSetupKit21CSKSetupAppleTVServerC7CommandO18OsUpdateCodingKeys33_D80D7C23C92088CF46EDAF3CD79D0C6DLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 17CompanionSetupKit21CSKStepOSUpdateServerC7CommandO10CodingKeys33_FB139EFB838DBEE703D14346C465A503LLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 17CompanionSetupKit21CSKStepOSUpdateServerC7CommandO24UpdateAnsweredCodingKeys33_FB139EFB838DBEE703D14346C465A503LLO
+ _symbolic _____y_____y_____GG 14CoreUtilsSwift32CUDistributedNotificationHandlerC 17CompanionSetupKit018CSKExternalCommandE0V AD21CSKStepOSUpdateClientC0K0O
+ _symbolic _____y_____y_____GG 14CoreUtilsSwift32CUDistributedNotificationHandlerC 17CompanionSetupKit018CSKExternalCommandE0V AD21CSKStepOSUpdateServerC0K0O
+ _type_layout_string SC11CKErrorCodeLeV
- ___swift_closure_destructor.131Tm
- ___swift_closure_destructor.187Tm
- ___swift_closure_destructor.280Tm
- ___swift_closure_destructor.302Tm
- ___swift_closure_destructor.316Tm
- ___swift_closure_destructor.355Tm
- ___swift_closure_destructor.374Tm
- ___swift_closure_destructor.37Tm
- ___swift_closure_destructor.417Tm
- ___swift_closure_destructor.572Tm
- ___swift_closure_destructor.88Tm
- ___unnamed_61
- _keypath_get.100Tm
- _keypath_set.70Tm
CStrings:
+ " currentNetworkName "
+ " previouslyChosenRoom showsBackButton homeWasAutoselected "
+ "### OS update check failed: %@"
+ "### OS update error: %@"
+ "### WiFi connect timeout"
+ "### bluetooth connection timeout: %s"
+ "### failed to change time zone to %s: error=%d"
+ "### one home screen cloud data check failed: %@"
+ "%s manual flow: no user choice, %s dictation"
+ ", cityIdentifier="
+ ", currentNetworkName="
+ ", homeWasAutoselected="
+ "/private/var/mobile/tmp/SyncKeyBoardData-"
+ "Actor type mismatch: expected CSKStepOSUpdateClient"
+ "Actor type mismatch: expected CSKStepOSUpdateServer"
+ "CSKOneHomeScreenCloudDataExists(firstName:lastName:timeout:)"
+ "CSKStepMisc-userTimeZonePicker"
+ "Captive network not supported"
+ "Case 'switchMeDevice' cannot be encoded because it is not defined in CodingKeys."
+ "CompanionSetupKit/CSKStepOSUpdateServer.swift"
+ "Failed to open HeadBoard defaults"
+ "KeepAppleTVInSync: cloudDataExists=%{bool}d"
+ "KeepAppleTVInSync: no existing cloud data, enabling silently"
+ "KeepAppleTVInSync: querying CloudKit for existing data"
+ "KeepAppleTVInSync: undetermined, skipping (sync off)"
+ "LECAHap"
+ "LECAHapLow"
+ "LECATmap"
+ "LECATmapLow"
+ "Location Services enabled; time zone is set automatically"
+ "No OS update needed"
+ "OS update check failed"
+ "OS update disabled"
+ "OS update preCheck not supported by peer"
+ "OS update prepare skip"
+ "OS update prepare start"
+ "OS update server not started"
+ "OS update started: progress=%s"
+ "OS update step disabled"
+ "OS update step disabled via osUpdateStepEnabled default"
+ "OSUpdateTV"
+ "OS_UPDATE_DOWNLOADING"
+ "OS_UPDATE_PREPARING"
+ "OS_UPDATE_REQUESTED"
+ "OS_UPDATE_RESTARTING"
+ "OS_UPDATE_UPDATING"
+ "OS_UPDATE_VERIFYING"
+ "OneHomeScreen_V2"
+ "Setting time zone to %s for city ID %s"
+ "SiriMicTest"
+ "Superseded by new ask"
+ "WiFi connect wait"
+ "WiFi connected"
+ "_meDeviceCheck()"
+ "authenticationPreconfigured=true"
+ "chooseRoomEx: rooms=["
+ "com.apple.container.HeadBoard"
+ "com.apple.purplebuddy"
+ "dictationAskServer canRun=%{bool}d siriSupported=%{bool}d"
+ "dictationStepCompleted"
+ "dictationSupported dictationAllowed=%{bool}d, preferredLanguageSupported=%{bool}d"
+ "enabled silently"
+ "flow ended early...needs restart"
+ "homeWasAutoselected="
+ "keepAppleTVInSyncAsk(cloudDataExists:)"
+ "oneHomeScreenDataExists"
+ "osUpdate"
+ "osUpdateAskAny"
+ "osUpdatePreCheck"
+ "osUpdateProgress"
+ "osUpdateProgress: "
+ "remote tour: connected remote is not a Silver Siri Remote"
+ "skipPreConnectSteps="
+ "switchMeDeviceAsk: deviceName="
+ "timeZoneIdentifier"
+ "timeZonePicker"
+ "timeZonePickerAsk"
+ "timeZonePickerAskServer()"
+ "timeZoneSelected"
+ "timeZoneSelected: timeZoneIdentifier="
+ "updateAsk(updateInfo:)"
+ "userTimeZonePicker"
- "LECA1"
- "LECA2"
- "LECA3"
- "LECA4"
- "OSUpdateCheckRequired"
- "QuickStartAdvertise"
- "SiriSetup"
- "SyncKeyBoardData-"
- "dictationAskServer canRun=%{bool}d dictationAllowed=%{bool}d, preferredLanguageSupported=%{bool}d, siriSupported=%{bool}d"
- "keepAppleTVInSyncAsk()"
- "proximityService"
```
