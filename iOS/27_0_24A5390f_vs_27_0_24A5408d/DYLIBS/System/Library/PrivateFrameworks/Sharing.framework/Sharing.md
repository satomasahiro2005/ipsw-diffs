## Sharing

> `/System/Library/PrivateFrameworks/Sharing.framework/Sharing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x391dd4` | `0x398790` | **`+0x69bc`** |
| `__DATA.__bss` | `0x3e720` | `0x3fba0` | **`+0x1480`** |
| `__TEXT.__const` | `0x24cc4` | `0x25634` | **`+0x970`** |
| `__AUTH_CONST.__const` | `0x1bbf8` | `0x1c288` | **`+0x690`** |
| `__TEXT.__eh_frame` | `0x10054` | `0x1033c` | **`+0x2e8`** |
| `__TEXT.__oslogstring` | `0xc093` | `0xc2d3` | **`+0x240`** |
| `__TEXT.__unwind_info` | `0xee78` | `0xf090` | **`+0x218`** |
| `__AUTH_CONST.__objc_const` | `0x3c608` | `0x3c810` | **`+0x208`** |
| `__TEXT.__swift5_fieldmd` | `0x7928` | `0x7b08` | **`+0x1e0`** |
| `__TEXT.__constg_swiftt` | `0x8008` | `0x81cc` | **`+0x1c4`** |
| `__TEXT.__swift5_typeref` | `0x9604` | `0x97bc` | **`+0x1b8`** |
| `__DATA.__data` | `0xd090` | `0xd210` | **`+0x180`** |
| `__TEXT.__cstring` | `0x3b2f5` | `0x3b465` | **`+0x170`** |
| `__AUTH.__objc_data` | `0x7818` | `0x7940` | **`+0x128`** |
| `__TEXT.__gcc_except_tab` | `0x34cc` | `0x35f0` | **`+0x124`** |
| `__TEXT.__objc_methlist` | `0x15114` | `0x151fc` | **`+0xe8`** |
| `__AUTH.__data` | `0x4e00` | `0x4ee0` | **`+0xe0`** |
| `__TEXT.__swift5_reflstr` | `0x4312` | `0x43e2` | **`+0xd0`** |
| `__AUTH_CONST.__cfstring` | `0x13480` | `0x13540` | **`+0xc0`** |
| `__TEXT.__swift5_proto` | `0x1ea0` | `0x1f44` | **`+0xa4`** |
| `__DATA_CONST.__const` | `0x78f8` | `0x7998` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x3280` | `0x32f8` | **`+0x78`** |
| `__TEXT.__swift5_assocty` | `0x1230` | `0x1280` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x9b38` | `0x9b80` | **`+0x48`** |
| `__TEXT.__swift5_types` | `0xa5c` | `0xa8c` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0xca8` | `0xcc8` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x21c` | `0x230` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x13e0` | `0x13f0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x9c0` | `0x9d0` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `0xc0` | `0xd0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2bf8` | `0x2c00` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x25ac` | `0x25b4` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x4b0` | `0x4b8` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x490` | `0x498` | **`+0x8`** |

### Other Changes

```diff

-2126.10.4.0.0
+2131.10.1.2.7

+  - /System/Library/Frameworks/LocalAuthentication.framework/LocalAuthentication

-  Functions: 24670
-  Symbols:   20428
-  CStrings:  8935
+  Functions: 24860
+  Symbols:   20524
+  CStrings:  8954
Symbols:
+ +[SFAllowAccessTapEvent eventName]
+ +[SFCollaborationUtilities addItemAllowedForCollaborationItem:completionHandler:]
+ +[SFCollaborationUtilities fetchExistingShareForFileOrFolderURL:completionHandler:]
+ -[SFAllowAccessTapEvent .cxx_destruct]
+ -[SFAllowAccessTapEvent eventPayload]
+ -[SFAllowAccessTapEvent hostAppBundleID]
+ -[SFAllowAccessTapEvent setHostAppBundleID:]
+ -[SFAllowAccessTapEvent submitEvent]
+ -[SFAuthenticationManager _enableForType:withIDSDeviceID:passcodeRef:sessionID:]
+ -[SFAuthenticationManager _releasePairingContextForSessionID:]
+ -[SFAuthenticationManager pairingLAContexts]
+ -[SFCollaborationPerformer _isCurrentUserCoOwnerOfShare:]
+ GCC_except_table107
+ GCC_except_table112
+ GCC_except_table114
+ GCC_except_table116
+ GCC_except_table171
+ GCC_except_table178
+ GCC_except_table179
+ _OBJC_CLASS_$_LAContext
+ _OBJC_CLASS_$_SFAllowAccessTapEvent
+ _OBJC_CLASS_$__TtCO7Sharing20SFAirDropInvocations17ReportBoopOutcome
+ _OBJC_IVAR_$_SFAllowAccessTapEvent._hostAppBundleID
+ _OBJC_IVAR_$_SFAuthenticationManager._pairingLAContexts
+ _OBJC_METACLASS_$_SFAllowAccessTapEvent
+ _OBJC_METACLASS_$__TtCO7Sharing20SFAirDropInvocations17ReportBoopOutcome
+ __CLASS_METHODS__TtCO7Sharing20SFAirDropInvocations17ReportBoopOutcome
+ __CLASS_PROPERTIES__TtCO7Sharing20SFAirDropInvocations17ReportBoopOutcome
+ __DATA__TtCO7Sharing20SFAirDropInvocations17ReportBoopOutcome
+ __INSTANCE_METHODS__TtCO7Sharing20SFAirDropInvocations17ReportBoopOutcome
+ __METACLASS_DATA__TtCO7Sharing20SFAirDropInvocations17ReportBoopOutcome
+ __OBJC_$_CLASS_METHODS_SFAllowAccessTapEvent
+ __OBJC_$_CLASS_PROP_LIST_SFAllowAccessTapEvent
+ __OBJC_$_INSTANCE_METHODS_SFAllowAccessTapEvent
+ __OBJC_$_INSTANCE_VARIABLES_SFAllowAccessTapEvent
+ __OBJC_$_PROP_LIST_SFAllowAccessTapEvent
+ __OBJC_CLASS_PROTOCOLS_$_SFAllowAccessTapEvent
+ __OBJC_CLASS_RO_$_SFAllowAccessTapEvent
+ __OBJC_METACLASS_RO_$_SFAllowAccessTapEvent
+ ___57-[SFCollaborationPerformer _isCurrentUserCoOwnerOfShare:]_block_invoke
+ ___80-[SFAuthenticationManager _enableForType:withIDSDeviceID:passcodeRef:sessionID:]_block_invoke
+ ___80-[SFAuthenticationManager _enableForType:withIDSDeviceID:passcodeRef:sessionID:]_block_invoke_2
+ ___81+[SFCollaborationUtilities addItemAllowedForCollaborationItem:completionHandler:]_block_invoke
+ ___83+[SFCollaborationUtilities fetchExistingShareForFileOrFolderURL:completionHandler:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e39_v32?0"NSURL"8"CKShare"16"NSError"24ls32l8
+ ___block_descriptor_40_e8_32r_e14_v20?0B8B12B16lr32l8
+ ___block_descriptor_40_e8_32r_e27_v16?0"RTIDocumentTraits"8lr32l8
+ ___block_descriptor_49_e8_32w_e29_v24?0"CKShare"8"NSError"16lw32l8
+ ___flagsForRTISession_block_invoke
+ ___getCKPhotosSharedCollectionsShareTypeSymbolLoc_block_invoke
+ ___infoForRTISession_block_invoke
+ ___swift__destructor.431Tm
+ _associated conformance 7Sharing20SFAirDropInvocationsO17ReportBoopOutcomeCAA22SFXPCInvocableProtocolAA10ParametersAaFP_SE
+ _associated conformance 7Sharing20SFAirDropInvocationsO17ReportBoopOutcomeCAA22SFXPCInvocableProtocolAA10ParametersAaFP_Se
+ _associated conformance 7Sharing20SFAirDropInvocationsO17ReportBoopOutcomeCAA22SFXPCInvocableProtocolAA8ResponseAaFP_SE
+ _associated conformance 7Sharing20SFAirDropInvocationsO17ReportBoopOutcomeCAA22SFXPCInvocableProtocolAA8ResponseAaFP_Se
+ _associated conformance 7Sharing6SFBoopO11CancelStageOSHAASQ
+ _associated conformance 7Sharing6SFBoopO11FailureCodeOSHAASQ
+ _associated conformance 7Sharing6SFBoopO13OutcomeReportV10CodingKeys33_0B461A7249AF7F550805D115321262CALLOSHAASQ
+ _associated conformance 7Sharing6SFBoopO13OutcomeReportV10CodingKeys33_0B461A7249AF7F550805D115321262CALLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 7Sharing6SFBoopO13OutcomeReportV10CodingKeys33_0B461A7249AF7F550805D115321262CALLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 7Sharing6SFBoopO7OutcomeO10CodingKeys33_0B461A7249AF7F550805D115321262CALLOSHAASQ
+ _associated conformance 7Sharing6SFBoopO7OutcomeO10CodingKeys33_0B461A7249AF7F550805D115321262CALLOs0D3KeyAAs23CustomStringConvertible
+ _associated conformance 7Sharing6SFBoopO7OutcomeO10CodingKeys33_0B461A7249AF7F550805D115321262CALLOs0D3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 7Sharing6SFBoopO7OutcomeO16FailedCodingKeys33_0B461A7249AF7F550805D115321262CALLOSHAASQ
+ _associated conformance 7Sharing6SFBoopO7OutcomeO16FailedCodingKeys33_0B461A7249AF7F550805D115321262CALLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 7Sharing6SFBoopO7OutcomeO16FailedCodingKeys33_0B461A7249AF7F550805D115321262CALLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 7Sharing6SFBoopO7OutcomeO19CancelledCodingKeys33_0B461A7249AF7F550805D115321262CALLOSHAASQ
+ _associated conformance 7Sharing6SFBoopO7OutcomeO19CancelledCodingKeys33_0B461A7249AF7F550805D115321262CALLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 7Sharing6SFBoopO7OutcomeO19CancelledCodingKeys33_0B461A7249AF7F550805D115321262CALLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 7Sharing6SFBoopO7OutcomeO19CompletedCodingKeys33_0B461A7249AF7F550805D115321262CALLOs0E3KeyAAs23CustomStringConvertible
+ _associated conformance 7Sharing6SFBoopO7OutcomeO19CompletedCodingKeys33_0B461A7249AF7F550805D115321262CALLOs0E3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 7Sharing6SFBoopO7OutcomeO20BannerOnlyCodingKeys33_0B461A7249AF7F550805D115321262CALLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 7Sharing6SFBoopO7OutcomeO20BannerOnlyCodingKeys33_0B461A7249AF7F550805D115321262CALLOs0F3KeyAAs28CustomDebugStringConvertible
+ _getCKPhotosSharedCollectionsShareTypeSymbolLoc.ptr
+ _getCKShareTypeKey
+ _symbolic _____ 7Sharing20SFAirDropInvocationsO17ReportBoopOutcomeC
+ _symbolic _____ 7Sharing6SFBoopO
+ _symbolic _____ 7Sharing6SFBoopO11CancelStageO
+ _symbolic _____ 7Sharing6SFBoopO11FailureCodeO
+ _symbolic _____ 7Sharing6SFBoopO13OutcomeReportV
+ _symbolic _____ 7Sharing6SFBoopO13OutcomeReportV10CodingKeys33_0B461A7249AF7F550805D115321262CALLO
+ _symbolic _____ 7Sharing6SFBoopO7OutcomeO
+ _symbolic _____ 7Sharing6SFBoopO7OutcomeO10CodingKeys33_0B461A7249AF7F550805D115321262CALLO
+ _symbolic _____ 7Sharing6SFBoopO7OutcomeO16FailedCodingKeys33_0B461A7249AF7F550805D115321262CALLO
+ _symbolic _____ 7Sharing6SFBoopO7OutcomeO19CancelledCodingKeys33_0B461A7249AF7F550805D115321262CALLO
+ _symbolic _____ 7Sharing6SFBoopO7OutcomeO19CompletedCodingKeys33_0B461A7249AF7F550805D115321262CALLO
+ _symbolic _____ 7Sharing6SFBoopO7OutcomeO20BannerOnlyCodingKeys33_0B461A7249AF7F550805D115321262CALLO
+ _symbolic _____4code_t 7Sharing6SFBoopO11FailureCodeO
+ _symbolic _____5stage_t 7Sharing6SFBoopO11CancelStageO
+ _symbolic _____ySSSo11NSExtensionCG s18_DictionaryStorageC
+ _symbolic _____y_____G s22KeyedDecodingContainerV 7Sharing6SFBoopO13OutcomeReportV10CodingKeys33_0B461A7249AF7F550805D115321262CALLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 7Sharing6SFBoopO7OutcomeO10CodingKeys33_0B461A7249AF7F550805D115321262CALLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 7Sharing6SFBoopO7OutcomeO16FailedCodingKeys33_0B461A7249AF7F550805D115321262CALLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 7Sharing6SFBoopO7OutcomeO19CancelledCodingKeys33_0B461A7249AF7F550805D115321262CALLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 7Sharing6SFBoopO7OutcomeO19CompletedCodingKeys33_0B461A7249AF7F550805D115321262CALLO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 7Sharing6SFBoopO7OutcomeO20BannerOnlyCodingKeys33_0B461A7249AF7F550805D115321262CALLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7Sharing6SFBoopO13OutcomeReportV10CodingKeys33_0B461A7249AF7F550805D115321262CALLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7Sharing6SFBoopO7OutcomeO10CodingKeys33_0B461A7249AF7F550805D115321262CALLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7Sharing6SFBoopO7OutcomeO16FailedCodingKeys33_0B461A7249AF7F550805D115321262CALLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7Sharing6SFBoopO7OutcomeO19CancelledCodingKeys33_0B461A7249AF7F550805D115321262CALLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7Sharing6SFBoopO7OutcomeO19CompletedCodingKeys33_0B461A7249AF7F550805D115321262CALLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 7Sharing6SFBoopO7OutcomeO20BannerOnlyCodingKeys33_0B461A7249AF7F550805D115321262CALLO
- GCC_except_table111
- GCC_except_table113
- GCC_except_table169
- ___69-[SFAuthenticationManager enableForType:withIDSDeviceID:passcodeRef:]_block_invoke
- ___69-[SFAuthenticationManager enableForType:withIDSDeviceID:passcodeRef:]_block_invoke_2
- ___swift__destructor.362Tm
- _symbolic _____ySSSaySo11NSExtensionCGG s18_DictionaryStorageC
CStrings:
+ "### BTAccessoryManagerGetFeatureCapability modern software volume failed: %#m\n"
+ "CKPhotosSharedCollectionsShareType"
+ "Current user is a co-owner of the existing URL share, skipping transport warning alert"
+ "Current user is a co-owner of the loaded share, skipping transport warning alert"
+ "Current user is a co-owner of the share, skipping transport warning alert"
+ "Failed to externalize passcode as ACM context, falling back to raw passcode: %{public}@"
+ "Failed to load existing share for URL: %@"
+ "File is (or was) shared publicly but options changed, updating options (isPrivateShare: %d, publicPermission: %ld)"
+ "Mac16,10"
+ "Mac16,11"
+ "Mac16,2"
+ "Mac16,3"
+ "MacMini2024"
+ "NSString *getCKPhotosSharedCollectionsShareType(void)"
+ "Share is (or was) shared publicly but options changed, updating options (isPrivateShare: %d, publicPermission: %ld)"
+ "Successfully set warning flag (flagType: %ld) for existing URL share"
+ "Warning already shown for existing URL share (flagType: %ld), skipping alert"
+ "afterReceiveOnly"
+ "afterShare"
+ "com.apple.sharing.allowAccessTap"
+ "dismissed"
+ "v16@?0@\"RTIDocumentTraits\"8"
+ "v24@?0@\"CKShare\"8@\"NSError\"16"
- "Failed to get value for key: OSVersion"
- "File is shared publicly but options changed, updating options"
- "MockA2DPActivity"
- "Share is existing public share but options changed, updating options"
```
