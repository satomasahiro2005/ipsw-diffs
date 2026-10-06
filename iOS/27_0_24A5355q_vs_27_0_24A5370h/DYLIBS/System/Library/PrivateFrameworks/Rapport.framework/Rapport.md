## Rapport

> `/System/Library/PrivateFrameworks/Rapport.framework/Rapport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa263c` | `0xd9160` | **`+0x36b24`** |
| `__TEXT.__cstring` | `0x1647c` | `0x1463c` | **`-0x1e40`** |
| `__TEXT.__oslogstring` | `0x7fd` | `0x236d` | **`+0x1b70`** |
| `__AUTH_CONST.__const` | `0x1490` | `0x2610` | **`+0x1180`** |
| `__TEXT.__objc_methlist` | `0x9190` | `0x9ef0` | **`+0xd60`** |
| `__DATA_CONST.__objc_selrefs` | `0x3c38` | `0x44b0` | **`+0x878`** |
| `__AUTH.__objc_data` | `0x850` | `0x1000` | **`+0x7b0`** |
| `__TEXT.__swift5_capture` | `0x138` | `0x820` | **`+0x6e8`** |
| `__TEXT.__constg_swiftt` | `0x728` | `0xd94` | **`+0x66c`** |
| `__TEXT.__unwind_info` | `0x2820` | `0x2e68` | **`+0x648`** |
| `__TEXT.__swift5_reflstr` | `0x39c` | `0x91c` | **`+0x580`** |
| `__AUTH_CONST.__cfstring` | `0x6520` | `0x60c0` | **`-0x460`** |
| `__AUTH_CONST.__objc_const` | `0x10ec0` | `0x11268` | **`+0x3a8`** |
| `__DATA.__bss` | `0x2b10` | `0x2ea0` | **`+0x390`** |
| `__TEXT.__swift5_typeref` | `0x81f` | `0xb85` | **`+0x366`** |
| `__TEXT.__const` | `0x3c08` | `0x3f68` | **`+0x360`** |
| `__TEXT.__gcc_except_tab` | `0x1758` | `0x1444` | **`-0x314`** |
| `__TEXT.__swift5_fieldmd` | `0x828` | `0xb28` | **`+0x300`** |
| `__DATA.__data` | `0x1e70` | `0x20d8` | **`+0x268`** |
| `__AUTH_CONST.__auth_got` | `0xfa0` | `0x1150` | **`+0x1b0`** |
| `__TEXT.__eh_frame` | `0x8a8` | `0x960` | **`+0xb8`** |
| `__AUTH_CONST.__objc_intobj` | `0x2d0` | `0x240` | **`-0x90`** |
| `__DATA.__objc_ivar` | `0x1174` | `0x10e8` | **`-0x8c`** |
| `__DATA_CONST.__got` | `0x458` | `0x4b0` | **`+0x58`** |
| `__TEXT.__swift5_assocty` | `0x40` | `0x88` | **`+0x48`** |
| `__AUTH.__data` | `0x4e8` | `0x510` | **`+0x28`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x50` | **`+0x28`** |
| `__DATA.__common` | `0x48` | `0x68` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x27b0` | `0x2790` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0x128` | `0x144` | **`+0x1c`** |
| `__TEXT.__swift5_types` | `0x9c` | `0xb0` | **`+0x14`** |
| `__DATA_CONST.__objc_protolist` | `0x140` | `0x150` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x2c0` | `0x2c8` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0xd8` | `0xe0` | **`+0x8`** |

### Other Changes

```diff

-740.100.2.0.0
+743.100.4.0.0

-  Functions: 4733
-  Symbols:   6585
-  CStrings:  3113
+  Functions: 5734
+  Symbols:   6737
+  CStrings:  3017
Symbols:
+ +[RPConnection _makeIdentityWithPublicKey:identifier:type:]
+ +[RPConnection _sepPrivateKeyOfPairingIdentity:]
+ +[RPConnection _setPairingIdentity:sepPrivateKey:]
+ +[RPConnection _updateIdentity:withSEPPrivateKey:]
+ +[RPConnection _updateIdentity:withSecretKey:]
+ -[RPClient launchListenerForService:completion:]
+ -[RPCompanionLinkClient _reregisterAdvertisesPublicBluetoothAddress]
+ -[RPCompanionLinkClient setAdvertisesPublicBluetoothAddress:completion:]
+ -[RPCompanionLinkDevice publicBluetoothAddress]
+ -[RPCompanionLinkDevice setPublicBluetoothAddress:]
+ -[RPConnection _addInUseProcess:]
+ -[RPConnection _addSelfIdentityInfoToMessage:flags:]
+ -[RPConnection _addSharedHomeIdentityWithMessage:]
+ -[RPConnection _bonjourFlagsFromLocalDeviceFlags]
+ -[RPConnection _btPipeHighPriorityConnected]
+ -[RPConnection _btPipeHighPriorityRequestable]
+ -[RPConnection _btPipeSelfIdentifier]
+ -[RPConnection _buildFrameHeaderData:length:]
+ -[RPConnection _callAuthCompletionHandler:]
+ -[RPConnection _callPairVerifyCompletion:]
+ -[RPConnection _canPeerDecode128bit:major:minor:patch:]
+ -[RPConnection _cloudDaemonIDSDeviceIDSelf]
+ -[RPConnection _cloudDaemonOSVersionForID:]
+ -[RPConnection _companionLinkFlagsString]
+ -[RPConnection _companionLinkFlagsSyncedMask]
+ -[RPConnection _completeRequestMetricsInOptions:responseSize:replyTime:hasReplyTime:]
+ -[RPConnection _completeSendMetrics:error:]
+ -[RPConnection _controlFlagsString]
+ -[RPConnection _controlFlagsSyncedMask]
+ -[RPConnection _createBleConnectTimer]
+ -[RPConnection _createCBConnectionForClient]
+ -[RPConnection _createOneShotTimer:handler:]
+ -[RPConnection _createRetryTimerWithDelay:]
+ -[RPConnection _createServerStartTimer]
+ -[RPConnection _createStartTimer]
+ -[RPConnection _decodeNSError:]
+ -[RPConnection _deviceCapabilitiesFlagsSyncedMask]
+ -[RPConnection _disableResolvedIdentityForSeconds:]
+ -[RPConnection _encodeNSError:intoDict:]
+ -[RPConnection _eventIDIsChatty:]
+ -[RPConnection _forgetBleConnectTimer]
+ -[RPConnection _forgetRetryTimer]
+ -[RPConnection _forgetStartTimer]
+ -[RPConnection _generatePeerIdentifierIfNeeded]
+ -[RPConnection _gestaltDeviceClassForModel:]
+ -[RPConnection _gestaltUserAssignedDeviceName]
+ -[RPConnection _getCanDecode128bit]
+ -[RPConnection _getCompanionLinkFlags]
+ -[RPConnection _getPeerStatusFlags]
+ -[RPConnection _getStatusFlags]
+ -[RPConnection _hasBtPipeHighPriority]
+ -[RPConnection _hasBtPipe]
+ -[RPConnection _hasIdentityDaemon]
+ -[RPConnection _homeKitIdentityIdentifierFromDaemon]
+ -[RPConnection _identityDaemonAddSessionPairedIdentity:]
+ -[RPConnection _identityDaemonIdentitiesOfType:error:]
+ -[RPConnection _identityDaemonIdentityOfSelfAndReturnError:]
+ -[RPConnection _identityDaemonResolveIdentityForSignature:data:typeFlags:error:]
+ -[RPConnection _identityDaemonSessionPairingIdentifier]
+ -[RPConnection _inUseProcessesToString]
+ -[RPConnection _insertBits32:newBits:mask:]
+ -[RPConnection _insertBits64:newBits:mask:]
+ -[RPConnection _isLocalDeviceCommunal]
+ -[RPConnection _linkTypeString]
+ -[RPConnection _localDeviceInfoPassword]
+ -[RPConnection _logRequestMetricsOnLinkType:length:rtt:]
+ -[RPConnection _logSendMetricsForLength:]
+ -[RPConnection _osVersionToString:]
+ -[RPConnection _pairingAppFlagsString:]
+ -[RPConnection _peerDeviceInfoSetTransportFlag:]
+ -[RPConnection _reportLargeSendContext:process:length:]
+ -[RPConnection _requestIDLogLevel:chatty:]
+ -[RPConnection _saveIdentityWithIDSDeviceID:message:]
+ -[RPConnection _scrubPskData]
+ -[RPConnection _sendFrameType:bodyObject:]
+ -[RPConnection _sendFrameType:dictionaryObject:]
+ -[RPConnection _setAppInfoPeer:]
+ -[RPConnection _setCanDecode128bit:]
+ -[RPConnection _setCompanionLinkFlags:]
+ -[RPConnection _setIsCBConnection:]
+ -[RPConnection _setPeerAccountAltDSID:]
+ -[RPConnection _setPeerAccountID:]
+ -[RPConnection _setPeerActiveUserAltDSID:]
+ -[RPConnection _setPeerActivityLevel:]
+ -[RPConnection _setPeerCompanionLinkFlags:]
+ -[RPConnection _setPeerDeviceCapabilityFlags:]
+ -[RPConnection _setPeerDeviceColor:]
+ -[RPConnection _setPeerHomeKitIdentifier:]
+ -[RPConnection _setPeerIDSCorrelationIdentifier:]
+ -[RPConnection _setPeerIDSDeviceIdentifier:]
+ -[RPConnection _setPeerListeningPort:]
+ -[RPConnection _setPeerMediaRemoteIdentifier:]
+ -[RPConnection _setPeerMediaRouteIdentifier:]
+ -[RPConnection _setPeerMediaSystemIdentifier:]
+ -[RPConnection _setPeerMediaSystemName:]
+ -[RPConnection _setPeerMediaSystemRole:]
+ -[RPConnection _setPeerMediaSystemState:]
+ -[RPConnection _setPeerModel:]
+ -[RPConnection _setPeerName:]
+ -[RPConnection _setPeerOperatingSystemVersion:]
+ -[RPConnection _setPeerPublicIdentifier:]
+ -[RPConnection _setPeerRole:]
+ -[RPConnection _setPeerRoomName:]
+ -[RPConnection _setPeerServiceTypes:]
+ -[RPConnection _setPeerSessionPairingIdentifier:]
+ -[RPConnection _setPeerSiriInfo:]
+ -[RPConnection _setPeerSourceVersion:]
+ -[RPConnection _setPeerStatusFlags:]
+ -[RPConnection _setPeerVerifiedIdentity:]
+ -[RPConnection _setRequestableToCBConnection]
+ -[RPConnection _setStatusFlags:]
+ -[RPConnection _signpostBeginClientResponse:requestID:]
+ -[RPConnection _signpostBeginSendRequest:requestID:length:linkType:highPriority:]
+ -[RPConnection _signpostEndClientResponse:length:linkType:highPriority:]
+ -[RPConnection _signpostEndSendRequest:rtt:requestSize:responseSize:]
+ -[RPConnection _signpostEndSendRequestTimeout:]
+ -[RPConnection _sourceVersionString]
+ -[RPConnection _startEventMessageMetrics:length:]
+ -[RPConnection _startReceivingFramesCB]
+ -[RPConnection _startReceivingFrames]
+ -[RPConnection _startRequestMessageMetrics:length:]
+ -[RPConnection _startResponseMessageMetrics:]
+ -[RPConnection _statusFlagsAccessFlagsMask]
+ -[RPConnection _statusFlagsAuthenticatedMask]
+ -[RPConnection _statusFlagsMeDeviceIsMe]
+ -[RPConnection _statusFlagsString]
+ -[RPConnection _statusFlagsSyncedMask]
+ -[RPConnection _stringToOSVersion:]
+ -[RPConnection _submitEventMetrics:length:]
+ -[RPConnection _updateBonjourFlagsOnPeerDevice:]
+ -[RPConnection _updateSessionPairedIdentityWithVerifiedIdentity:model:name:]
+ -[RPConnection isGuest]
+ -[RPConnection setValue:forUndefinedKey:]
+ -[RPConnection valueForUndefinedKey:]
+ GCC_except_table145
+ _OBJC_CLASS_$_OS_dispatch_source
+ _OBJC_CLASS_$__TtC7Rapport16RPConnectionCore
+ _OBJC_IVAR_$_RPCompanionLinkClient._advertisesPublicBluetoothAddress
+ _OBJC_IVAR_$_RPCompanionLinkDevice._publicBluetoothAddress
+ _OBJC_IVAR_$_RPConnection._core
+ _OBJC_METACLASS_$__TtC7Rapport16RPConnectionCore
+ _OPACKDecodeNSData
+ _OPACKEncoderCreateNSData
+ _RPAuthenticationTypeToString
+ _RPPasswordTypeToString
+ __DATA__TtC7Rapport16RPConnectionCore
+ __INSTANCE_METHODS__TtC7Rapport16RPConnectionCore
+ __IVARS__TtC7Rapport16RPConnectionCore
+ __METACLASS_DATA__TtC7Rapport16RPConnectionCore
+ __OBJC_$_CLASS_METHODS_RPConnection
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CUReadWriteRequestable
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CUReadWriteRequestable
+ __OBJC_LABEL_PROTOCOL_$_CUReadWriteRequestable
+ __OBJC_PROTOCOL_$_CUReadWriteRequestable
+ __PROPERTIES__TtC7Rapport16RPConnectionCore
+ ___33-[RPConnection _createStartTimer]_block_invoke
+ ___38-[RPConnection _createBleConnectTimer]_block_invoke
+ ___39-[RPConnection _createServerStartTimer]_block_invoke
+ ___43-[RPConnection _createRetryTimerWithDelay:]_block_invoke
+ ___48-[RPClient launchListenerForService:completion:]_block_invoke
+ ___48-[RPClient launchListenerForService:completion:]_block_invoke_2
+ ___48-[RPClient launchListenerForService:completion:]_block_invoke_3
+ ___72-[RPCompanionLinkClient setAdvertisesPublicBluetoothAddress:completion:]_block_invoke
+ ___72-[RPCompanionLinkClient setAdvertisesPublicBluetoothAddress:completion:]_block_invoke_2
+ ___72-[RPCompanionLinkClient setAdvertisesPublicBluetoothAddress:completion:]_block_invoke_3
+ ___swift__destructor
+ ___swift_allocate_boxed_opaque_existential_0
+ ___swift_assign_boxed_opaque_existential_0
+ ___swift_closure_destructor.145Tm
+ ___swift_closure_destructor.177Tm
+ ___swift_closure_destructor.238Tm
+ ___swift_closure_destructor.251Tm
+ ___swift_closure_destructorTm
+ ___swift_destroy_boxed_opaque_existential_0
+ _associated conformance 7Rapport25RPConnectionInternalStateOSHAASQ
+ _bzero
+ _flat unique So22CUReadWriteRequestable_p
+ _swift_bridgeObjectRelease_n
+ _swift_dynamicCastClass
+ _swift_getErrorValue
+ _swift_isEscapingClosureAtFileLocation
+ _swift_release_n
+ _swift_release_x19
+ _swift_release_x21
+ _swift_release_x24
+ _swift_release_x27
+ _swift_retain_n
+ _swift_retain_x19
+ _swift_retain_x21
+ _swift_retain_x22
+ _swift_retain_x23
+ _swift_retain_x24
+ _swift_retain_x25
+ _swift_retain_x26
+ _swift_retain_x27
+ _swift_retain_x8
+ _swift_unknownObjectRelease_n
+ _swift_unknownObjectRetain_n
+ _swift_unknownObjectUnownedDestroy
+ _swift_unknownObjectUnownedInit
+ _swift_unknownObjectUnownedLoadStrong
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
+ _symbolic $sSY
+ _symbolic SDy_____ypG s11AnyHashableV
+ _symbolic SDy_____ypGSg s11AnyHashableV
+ _symbolic Say_____G 10Foundation4UUIDV
+ _symbolic Sd
+ _symbolic Si
+ _symbolic So10RPIdentityCSg
+ _symbolic So11RPSendEntryC
+ _symbolic So12CBConnectionCSg
+ _symbolic So12NSDictionaryCSgACSo7NSErrorCSgIeyByyy_
+ _symbolic So12RPConnectionC
+ _symbolic So12RPConnectionCXo
+ _symbolic So14CUWriteRequestC
+ _symbolic So14CUWriteRequestCIegg_
+ _symbolic So14NSMutableArrayC
+ _symbolic So14RPRequestEntryC
+ _symbolic So15CUBLEConnectionC
+ _symbolic So15CUPairingStreamCSg
+ _symbolic So15CUTCPConnectionC
+ _symbolic So16CUPairingSessionCSg
+ _symbolic So19NSMutableDictionaryCSg
+ _symbolic So7NSErrorC
+ _symbolic So7NSErrorCSg
+ _symbolic So7NSErrorCSgIegg_
+ _symbolic So7NSErrorCSgIeyBy_
+ _symbolic So8NSNumberC
+ _symbolic _____ 7Rapport16RPConnectionCoreC
+ _symbolic _____ 7Rapport21RPConnectionConstantsO
+ _symbolic _____ 7Rapport25RPConnectionInternalStateO
+ _symbolic _____ So14RPIdentityTypeV
+ _symbolic _____ So20RPAuthenticationTypeV
+ _symbolic _____ s5Int32V
+ _symbolic _____ s6UInt32V
+ _symbolic _____Iegy_Sg s6UInt32V
+ _symbolic _____IeyBy_ s6UInt32V
+ _symbolic _____SSIegyg_Sg s6UInt32V
+ _symbolic _____Sg 10Foundation4UUIDV
+ _symbolic _____SgXw 7Rapport16RPConnectionCoreC
+ _symbolic _____SgXwz_Xx 7Rapport16RPConnectionCoreC
+ _symbolic _____Sg_ABt 10Foundation4UUIDV
+ _symbolic _____So8NSStringCIeyByy_ s6UInt32V
+ _symbolic _____XDXMT 7Rapport16RPConnectionCoreC
+ _symbolic __________Iegyy_ s6UInt32V s5Int32V
+ _symbolic __________IeyByy_ s6UInt32V s5Int32V
+ _symbolic ______pSg So22CUReadWriteRequestableP
+ _symbolic ______pSg s5ErrorP
+ _symbolic ______pSgIegg_Sg s5ErrorP
+ _symbolic ______ypt s11AnyHashableV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation4DataV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation4UUIDV
+ _symbolic _____y______yptG s23_ContiguousArrayStorageC s11AnyHashableV
+ _symbolic _____y_____ypG s18_DictionaryStorageC s11AnyHashableV
+ _symbolic _____yyp_yptG s23_ContiguousArrayStorageC
+ _symbolic yXlSg
+ _symbolic yXlSgz_Xx
+ _symbolic ypSg
+ _symbolic ypypSpy_____GIgnny_ 10ObjectiveC8ObjCBoolV
- -[RPConnection _isEligibleToSendWithOptions:]
- GCC_except_table140
- GCC_except_table142
- GCC_except_table149
- GCC_except_table153
- _OBJC_IVAR_$_RPConnection._activateCalled
- _OBJC_IVAR_$_RPConnection._activatedTicks
- _OBJC_IVAR_$_RPConnection._highPriorityAuthTagLength
- _OBJC_IVAR_$_RPConnection._highPriorityStream
- _OBJC_IVAR_$_RPConnection._homeKitIdentityIdentifier
- _OBJC_IVAR_$_RPConnection._homeKitIdentitySignature
- _OBJC_IVAR_$_RPConnection._identityKeyData
- _OBJC_IVAR_$_RPConnection._identitySignature
- _OBJC_IVAR_$_RPConnection._initiator
- _OBJC_IVAR_$_RPConnection._internalState
- _OBJC_IVAR_$_RPConnection._invalidateCalled
- _OBJC_IVAR_$_RPConnection._invalidateDone
- _OBJC_IVAR_$_RPConnection._mainAuthTagLength
- _OBJC_IVAR_$_RPConnection._mainStream
- _OBJC_IVAR_$_RPConnection._pairSetupAuthType
- _OBJC_IVAR_$_RPConnection._pairSetupSession
- _OBJC_IVAR_$_RPConnection._pairVerifyAuthType
- _OBJC_IVAR_$_RPConnection._pairVerifyCompleted
- _OBJC_IVAR_$_RPConnection._pairVerifyFailed
- _OBJC_IVAR_$_RPConnection._pairVerifyIdentityType
- _OBJC_IVAR_$_RPConnection._pairVerifySession
- _OBJC_IVAR_$_RPConnection._pairVerifyUsedIdentity
- _OBJC_IVAR_$_RPConnection._peerAddrString
- _OBJC_IVAR_$_RPConnection._peerHomeKitUserIdentifier
- _OBJC_IVAR_$_RPConnection._receivedFrameCountCurrent
- _OBJC_IVAR_$_RPConnection._receivedFrameCountLast
- _OBJC_IVAR_$_RPConnection._requestable
- _OBJC_IVAR_$_RPConnection._requests
- _OBJC_IVAR_$_RPConnection._retryCount
- _OBJC_IVAR_$_RPConnection._retryFired
- _OBJC_IVAR_$_RPConnection._retryTicks
- _OBJC_IVAR_$_RPConnection._selfAddrString
- _OBJC_IVAR_$_RPConnection._sendArray
- _OBJC_IVAR_$_RPConnection._showPasswordCalled
- _OBJC_IVAR_$_RPConnection._startTimeoutSeconds
- _OBJC_IVAR_$_RPConnection._stepDone
- _OBJC_IVAR_$_RPConnection._stepError
- _OBJC_IVAR_$_RPConnection._xidLast
- _RPFrameTypeToString
- __StateToString
- ___104-[RPConnection _sendEncryptedResponse:options:error:xid:requestID:highPriority:isChatty:replyStartTime:]_block_invoke
- ___29-[RPConnection _serverAccept]_block_invoke
- ___32-[RPConnection _serverAcceptBLE]_block_invoke
- ___32-[RPConnection _serverAcceptBLE]_block_invoke_2
- ___32-[RPConnection _serverAcceptTCP]_block_invoke
- ___32-[RPConnection _serverAcceptTCP]_block_invoke_2
- ___32-[RPConnection _serverAcceptTCP]_block_invoke_3
- ___33-[RPConnection _clientRetryStart]_block_invoke
- ___34-[RPConnection _startCBConnection]_block_invoke
- ___34-[RPConnection _startCBConnection]_block_invoke_2
- ___34-[RPConnection _startCBConnection]_block_invoke_3
- ___34-[RPConnection _startCBConnection]_block_invoke_4
- ___34-[RPConnection _startCBConnection]_block_invoke_5
- ___35-[RPConnection _clientStartSession]_block_invoke
- ___37-[RPConnection _clientPairSetupStart]_block_invoke
- ___37-[RPConnection _clientPairSetupStart]_block_invoke_2
- ___37-[RPConnection _clientPairSetupStart]_block_invoke_3
- ___37-[RPConnection _receivedRequest:ctx:]_block_invoke
- ___38-[RPConnection _clientConnectStartBLE]_block_invoke
- ___38-[RPConnection _clientConnectStartBLE]_block_invoke_2
- ___38-[RPConnection _clientConnectStartBLE]_block_invoke_3
- ___38-[RPConnection _clientConnectStartBLE]_block_invoke_4
- ___38-[RPConnection _clientConnectStartTCP]_block_invoke
- ___38-[RPConnection _clientConnectStartTCP]_block_invoke_2
- ___38-[RPConnection _clientConnectStartTCP]_block_invoke_3
- ___38-[RPConnection _clientConnectStartTCP]_block_invoke_4
- ___38-[RPConnection _clientPairVerifyStart]_block_invoke
- ___38-[RPConnection _clientPairVerifyStart]_block_invoke_2
- ___38-[RPConnection _clientPairVerifyStart]_block_invoke_3
- ___38-[RPConnection _clientPairVerifyStart]_block_invoke_4
- ___40-[RPConnection _abortRequestsWithError:]_block_invoke
- ___40-[RPConnection _clientConnectCompleted:]_block_invoke
- ___40-[RPConnection _receivedSystemInfo:xid:]_block_invoke
- ___41-[RPConnection _clientConnectStartBTPipe]_block_invoke
- ___44-[RPConnection _configureForSessionPairing:]_block_invoke
- ___44-[RPConnection _configureForSessionPairing:]_block_invoke_2
- ___44-[RPConnection _configureForSessionPairing:]_block_invoke_3
- ___47-[RPConnection _serverPairSetupWithData:start:]_block_invoke
- ___47-[RPConnection _serverPairSetupWithData:start:]_block_invoke_2
- ___47-[RPConnection _serverPairSetupWithData:start:]_block_invoke_3
- ___47-[RPConnection _serverPairSetupWithData:start:]_block_invoke_4
- ___48-[RPConnection _serverPairVerifyWithData:start:]_block_invoke
- ___48-[RPConnection _serverPairVerifyWithData:start:]_block_invoke_2
- ___48-[RPConnection _serverPairVerifyWithData:start:]_block_invoke_3
- ___48-[RPConnection _serverPairVerifyWithData:start:]_block_invoke_4
- ___66-[RPConnection _sendEncryptedEventID:data:xid:options:completion:]_block_invoke
- ___66-[RPConnection _sendEncryptedEventID:data:xid:options:completion:]_block_invoke_2
- ___77-[RPConnection sendEncryptedRequestID:request:xpcID:options:responseHandler:]_block_invoke
- ___88-[RPConnection _sendEncryptedRequestID:request:xpcID:options:sendEntry:responseHandler:]_block_invoke
- ___block_descriptor_40_e8_32s_e19_v20?0I8"NSData"12ls32l8
- ___block_descriptor_40_e8_32s_e21_v20?0I8"NSString"12ls32l8
- ___block_descriptor_40_e8_32s_e31_"NSData"28?0I8"NSData"12^20ls32l8
- ___block_descriptor_40_e8_32s_e34_B36?0I8"NSData"12"NSData"20^28ls32l8
- ___block_descriptor_44_e8_32s_e19_v20?0I8"NSData"12ls32l8
- ___block_descriptor_48_e8_32bs40r_e17_v16?0"NSError"8lr40l8s32l8
- ___block_descriptor_48_e8_32s40bs_e11_v16?0I8i12ls32l8s40l8
- ___block_descriptor_48_e8_32s40s_e29_B32?0"CUPairedPeer"8Q16^24ls32l8s40l8
- ___block_descriptor_48_e8_32s40s_e31_"CUPairingIdentity"24?0Q8^16ls32l8s40l8
- ___block_descriptor_48_e8_32s40s_e41_v32?0"NSNumber"8"RPRequestEntry"16^B24ls32l8s40l8
- ___block_descriptor_48_e8_32s40s_e43_"CUPairedPeer"32?0"CUPairedPeer"8Q16^24ls32l8s40l8
- ___block_descriptor_60_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
- ___block_descriptor_66_e8_32s40s48s56s_e51_v32?0"NSDictionary"8"NSDictionary"16"NSError"24ls32l8s40l8s48l8s56l8
- _objc_release_x3
- _symbolic _____yypG s23_ContiguousArrayStorageC
CStrings:
+ "### Abort queued ID '%{public}s': %{public}@"
+ "### Abort request XID 0x%{public}s: %{public}@"
+ "### Client error: %{public}@"
+ "### Connect failed: %{public}@"
+ "### Failed to get self identity: %{public}@"
+ "### Failed to set advertisesPublicBluetoothAddress: %{error}\n"
+ "### Ignoring call to send event ID '%{public}s' when invalidating"
+ "### Ignoring received PreAuthResponse when not expected: %@"
+ "### Ignoring response to requestID '%{public}s' after invalidation"
+ "### Ignoring send request ID '%{public}s' when invalidating"
+ "### PSK prepare failed: %{public}@"
+ "### PairSetup client completion failed: %{public}@"
+ "### PairSetup server completion failed: %{public}@"
+ "### PairSetup server receive failed: %{public}@"
+ "### PairVerify client completion failed: %{public}@"
+ "### PairVerify client failed: %{public}@"
+ "### PairVerify server completion failed: %{public}s, %{public}@"
+ "### PairVerify server receive failed: %{public}@"
+ "### PairVerifyVerify failed: %{public}@"
+ "### PreAuthRequest decode failed"
+ "### PreAuthRequest failed, unexpected state"
+ "### PreAuthResponse decode failed: %{public}d"
+ "### Process unsupported request"
+ "### Received event with no ID from %s"
+ "### Received event with no content from %s"
+ "### Received request XID 0x%{public}s with no ID from %s"
+ "### Received request with no XID from %s"
+ "### Received requestID '%{public}s', XID 0x%{public}s with no content from %s"
+ "### Received requestID '%{public}s', XID 0x%{public}s, from %s with no handler"
+ "### Received response XID 0x%{public}s with no content from %s"
+ "### Received response XID 0x%{public}s with no request from %s"
+ "### Received response XID 0x%{public}s, error %{public}@, from %s, %{public}llu ms"
+ "### Received response with no XID from %s"
+ "### Request timeout '%{public}s' not found, %{public}f seconds"
+ "### Request timeout '%{public}s', %{public}f seconds"
+ "### Request timeout XID 0x%{public}s, %{public}f seconds"
+ "### Send encrypted data (%{public}ld bytes) failed: '%{public}s', %{public}@"
+ "### Send encrypted requestID '%{public}s' failed: %{public}@"
+ "### Send encrypted response XID 0x%{public}s failed: %{public}@"
+ "### Send frame 0x%{public}s encode failed: %{public}d"
+ "### Send frame type 0x%{public}s failed: %{public}@"
+ "### Sending response XID 0x%{public}s, error: %{public}@"
+ "### Server error: %{public}@"
+ "### Set advertisesPublicBluetoothAddress XPC error: %{error}\n"
+ "### Set advertisesPublicBluetoothAddress error: %{error}\n"
+ "### Timeout for XID 0x%{public}s with no request"
+ "### Unknown message type: %{public}d"
+ "### Unsupported send attempt"
+ "%#ll{flags}"
+ "%#{flags}"
+ "%s dateDay %ld"
+ "%s dateWeekOfYear %ld"
+ "%s dayOfYear %lld"
+ "%s weekOfYear %lld"
+ ", PBA "
+ "-[RPClient launchListenerForService:completion:]"
+ "-[RPCompanionLinkClient _reregisterAdvertisesPublicBluetoothAddress]"
+ "-[RPCompanionLinkClient setAdvertisesPublicBluetoothAddress:completion:]_block_invoke"
+ "-[RPCompanionLinkClient setAdvertisesPublicBluetoothAddress:completion:]_block_invoke_2"
+ "-[RPCompanionLinkClient setAdvertisesPublicBluetoothAddress:completion:]_block_invoke_3"
+ "-[RPConnection _startReceivingFrames]"
+ "AirPlay restrictions ignored"
+ "BLE CB connection interrupted."
+ "BLE CB connection invalidated."
+ "BLE client connection invalidated"
+ "BLE client connection with bundleID: %s and clientUseCase: %{public}ld"
+ "BLE server connection invalidated"
+ "Backwards compatibility authType -> sessionPaired"
+ "Backwards compatibility change authType sessionPaired -> rpIdentity"
+ "Client PairSetup retry"
+ "Client connect start: %@"
+ "Client immediate non-RPIdentity retry"
+ "Client state: %{public}s -> %{public}s"
+ "Configuring for session pairing"
+ "External state changed: %{public}s -> %{public}s"
+ "Failed to open main stream"
+ "Find paired peer handler for peer %@ options %llu"
+ "In use processes updated to: %{public}s"
+ "LECAHap"
+ "LECAHapLow"
+ "LECATmap"
+ "LECATmapLow"
+ "Large Frame: Send frame 0x%{public}s, (%{public}ld bytes)"
+ "Large Frame: Send request ID '%{public}s', XID 0x%{public}s, (%{public}ld bytes) on link type %{public}s"
+ "Large Frame: Send response XID 0x%{public}s, (%{public}ld bytes) on link type %{public}s"
+ "Large Frame: SendEventID '%{public}s', XID 0x%{public}s, (%{public}ld bytes) on link type %{public}s"
+ "Launch of listener for service '%@' requested\n"
+ "OnDemand connection failed, invalidating"
+ "PairSetup completed client."
+ "PairSetup next (%ld bytes)"
+ "PairSetup response error: '"
+ "PairSetup server rejecting when not allowed"
+ "PairSetup server rejecting when not allowing non-Home devices"
+ "PairVerify completed client %{public}s, %{public}s, %{public}s, RPI %@"
+ "PairVerify completed server: %{public}s, %{public}s, %{public}s, RPI %@"
+ "PairVerify next (%ld bytes)"
+ "PairVerify start client: AT %{public}s, CF %{public}s, FL %{public}s, PWT %{public}s"
+ "PairVerifySign success: CF %{public}s, AF %{public}s"
+ "PairVerifySign: Not using RPI"
+ "PairVerifySign: Not using RPI: CF %{public}s, AF %{public}s"
+ "PairVerifyVerify resolve identity failed"
+ "PairVerifyVerify success: %{public}d, CF %{public}s, AF %{public}s"
+ "PairVerifyVerify: Not using RPI"
+ "PairVerifyVerify: Not using RPI: CF %{public}s, AF %{public}s"
+ "Peer appears missing, invalidating"
+ "Peer appears present, retrying"
+ "Peer is blocking access, invalidating"
+ "Peer may be unreachable, sending reachability probe (%{public}s)"
+ "Peer missing after retry timer, invalidating"
+ "Queuing send event ID '%{public}s', XID 0x%{public}s (%{public}ld send(s) pending)"
+ "Queuing send request ID '%{public}s' (%{public}ld send(s) pending)"
+ "Rapport.RPConnectionCore"
+ "Re-registering advertisesPublicBluetoothAddress\n"
+ "Received PreAuthRequest"
+ "Received PreAuthResponse: %@"
+ "Received SharedHome identity: ID '%s'"
+ "Received client service type %{public}s"
+ "Received event ID '%{public}s', XID 0x%{public}s, %{public}ld keys, from %s"
+ "Received identity from IDS '%s'"
+ "Received requestID '%{public}s', XID 0x%{public}s, %{public}ld keys, from %s"
+ "Received response XID 0x%{public}s, %{public}ld keys, from %s, %{public}llu ms request size %{public}ld response size %{public}llu"
+ "Rejected in unexpected state"
+ "Retrying delayed: %.*f seconds"
+ "Retrying immediately: %lds since last retry"
+ "Retrying immediately: first retry"
+ "Retrying setup of CBConnection after error, attempt: %{public}d"
+ "Save paired peer handler for peer %@ options %llu"
+ "Send PreAuthRequest: %@"
+ "Send PreAuthResponse"
+ "Send SharedHome identity"
+ "Send encrypted event failed: '%{public}s', %{public}@"
+ "Send encrypted requestID '%{public}s' failed: %{public}@"
+ "Send frame 0x%{public}s, (%{public}ld bytes)"
+ "Send identity"
+ "Send request ID '%{public}s', XID 0x%{public}s, (%{public}ld bytes) on link type %{public}s %{public}s"
+ "Send response XID 0x%{public}s, (%{public}ld bytes) on link type %{public}s%{public}s"
+ "SendEventID '%{public}s', XID 0x%{public}s, (%{public}ld bytes) on link type %{public}s %{public}s"
+ "Sending client service type %{public}s"
+ "Server state: %{public}s -> %{public}s"
+ "Setting advertisesPublicBluetoothAddress to %d for local device with ID `%@`\n"
+ "TCP client connection invalidated"
+ "TCP server connection invalidated"
+ "Too many retries, invalidating: retries %d, %@"
+ "Transferring event ID %{public}s to connection %{public}s"
+ "Transferring request ID %{public}s to connection %{public}s with timeout %{public}f"
+ "Unsupported password type or auth type"
+ "Using AdHocPaired identifier for connection: %s"
+ "_activateCalled"
+ "_highPriorityStream"
+ "_initiator"
+ "_internalState"
+ "_invalidateCalled"
+ "_invalidateDone"
+ "_mainStream"
+ "_pairSetupSession"
+ "_pairVerifyCompleted"
+ "_pairVerifyFailed"
+ "_pairVerifySession"
+ "_requests"
+ "_retryCount"
+ "_sendArray"
+ "_showPasswordCalled"
+ "_startTimeoutSeconds"
+ "_stepDone"
+ "_stepError"
+ "_xidLast"
+ "pubBA"
+ "rpPBA"
- " dateWeekOfYear "
- "### Abort queued ID '%@': %{error}\n"
- "### Abort request XID 0x%X: %{error}\n"
- "### Client error: %{error}\n"
- "### Connect failed: %{error}\n"
- "### Failed to get self identity: %@\n."
- "### Ignoring call to send event ID '%@' when invalidating\n"
- "### Ignoring received PreAuthResponse when not expected: %##@\n"
- "### Ignoring response to requestID '%@' from %@ after invalidation\n"
- "### Ignoring send request ID '%@' when invalidating\n"
- "### PSK prepare failed: %{error}\n"
- "### PairSetup client completion failed: %{error}\n"
- "### PairSetup client receive failed: %{error}\n"
- "### PairSetup server completion failed: %s, %{error}\n"
- "### PairSetup server receive failed: %{error}\n"
- "### PairVerify client completion failed: %{error}\n"
- "### PairVerify client failed: %{error}\n"
- "### PairVerify client receive failed: %{error}\n"
- "### PairVerify server completion failed: %s, %{error}\n"
- "### PairVerify server receive failed: %{error}\n"
- "### PairVerifySign failed: %{error}\n"
- "### PairVerifySign get self identity failed: %{error}\n"
- "### PairVerifyVerify failed: %{error}\n"
- "### PreAuthRequest bad type\n"
- "### PreAuthRequest decode failed: %#m\n"
- "### PreAuthResponse bad type\n"
- "### PreAuthResponse decode failed: %#m\n"
- "### Process unsupported request\n"
- "### Received event with no ID from %@: %#m\n"
- "### Received event with no content from %@: %#m\n"
- "### Received request XID 0x%X with no ID from %@: %#m\n"
- "### Received request with no XID from %@: %#m\n"
- "### Received requestID '%@', XID 0x%X with no content from %@: %#m\n"
- "### Received requestID '%@', XID 0x%X, from %@ with no handler\n"
- "### Received response XID 0x%X with no content from %@: %#m\n"
- "### Received response XID 0x%X with no request from %@\n"
- "### Received response XID 0x%X, error %{error}, from %@, %llu ms\n"
- "### Received response with no XID from %@: %#m\n"
- "### Request timeout '%@' not found, %.3f seconds\n"
- "### Request timeout '%@', %.3f seconds\n"
- "### Request timeout XID 0x%X, %.3f seconds\n"
- "### Send %s encode failed: %#m\n"
- "### Send encrypted data (%zu bytes) failed: '%@', %{error}\n"
- "### Send encrypted requestID '%@' failed: %{error}\n"
- "### Send encrypted response XID 0x%X failed: %{error}\n"
- "### Send frame type 0x%X failed: %{error}\n"
- "### Sending response XID 0x%X, error: %{error}\n"
- "### Server error: %{error}\n"
- "### Timeout for XID 0x%X with no request\n"
- "### Unknown message type: %d\n"
- "### Unsupported send attempt\n"
- "(HK)"
- "(RPI-?)"
- "(RPI-AdHocPaired)"
- "(RPI-Family)"
- "(RPI-Friend)"
- "(RPI-Owner)"
- "(RPI-SessionPaired)"
- "(RPI-SharedTVUser)"
- "-[RPConnection _abortRequestsWithError:]_block_invoke"
- "-[RPConnection _abortSendEntry:withError:]"
- "-[RPConnection _clientConnectCompleted:]"
- "-[RPConnection _clientConnectStartBLE]"
- "-[RPConnection _clientConnectStartBLE]_block_invoke_2"
- "-[RPConnection _clientConnectStartTCP]_block_invoke_3"
- "-[RPConnection _clientConnectStart]"
- "-[RPConnection _clientError:]"
- "-[RPConnection _clientPairSetupCompleted:]"
- "-[RPConnection _clientPairSetupStart]"
- "-[RPConnection _clientPairSetupWithData:]"
- "-[RPConnection _clientPairVerifyCompleted:]"
- "-[RPConnection _clientPairVerifyStart]"
- "-[RPConnection _clientPairVerifyWithData:]"
- "-[RPConnection _clientPreAuthResponseWithData:]"
- "-[RPConnection _clientPreAuthStart]"
- "-[RPConnection _clientRetryFired]"
- "-[RPConnection _clientRetryStart]"
- "-[RPConnection _clientRun]"
- "-[RPConnection _clientStartSession]"
- "-[RPConnection _configureForSessionPairing:]"
- "-[RPConnection _configureForSessionPairing:]_block_invoke"
- "-[RPConnection _configureForSessionPairing:]_block_invoke_2"
- "-[RPConnection _configureForSessionPairing:]_block_invoke_3"
- "-[RPConnection _pairVerifySignData:flags:error:]"
- "-[RPConnection _pairVerifyVerifySignature:data:flags:error:]"
- "-[RPConnection _processSends]"
- "-[RPConnection _pskPrepare:]"
- "-[RPConnection _receivedEvent:ctx:]"
- "-[RPConnection _receivedObject:ctx:]"
- "-[RPConnection _receivedRequest:ctx:]"
- "-[RPConnection _receivedRequest:ctx:]_block_invoke"
- "-[RPConnection _receivedResponse:ctx:]"
- "-[RPConnection _receivedSystemInfo:xid:]"
- "-[RPConnection _receivedSystemInfo:xid:]_block_invoke"
- "-[RPConnection _sendEncryptedEventID:data:xid:options:completion:]"
- "-[RPConnection _sendEncryptedRequestID:request:xpcID:options:sendEntry:responseHandler:]"
- "-[RPConnection _sendEncryptedResponse:options:error:xid:requestID:highPriority:isChatty:replyStartTime:]"
- "-[RPConnection _sendFrameType:body:]"
- "-[RPConnection _sendFrameType:unencryptedObject:]"
- "-[RPConnection _serverAcceptBLE]_block_invoke_2"
- "-[RPConnection _serverAcceptBTPipe]"
- "-[RPConnection _serverAcceptTCP]_block_invoke_3"
- "-[RPConnection _serverError:]"
- "-[RPConnection _serverPairSetupCompleted:]"
- "-[RPConnection _serverPairSetupWithData:start:]"
- "-[RPConnection _serverPairVerifyCompleted:]"
- "-[RPConnection _serverPairVerifyWithData:start:]"
- "-[RPConnection _serverPreAuthRequestWithData:]"
- "-[RPConnection _serverRun]"
- "-[RPConnection _startCBConnection]_block_invoke_2"
- "-[RPConnection _startCBConnection]_block_invoke_3"
- "-[RPConnection _systeminfo]"
- "-[RPConnection _timeoutForSendEntry:]"
- "-[RPConnection _timeoutForXID:]"
- "-[RPConnection _updateExternalState]"
- "-[RPConnection processSendsUsingConnection:]"
- "-[RPConnection sendEncryptedEventID:data:xid:options:completion:]"
- "-[RPConnection sendEncryptedRequestID:request:xpcID:options:responseHandler:]"
- "-[RPConnection sendReachabilityProbe:]"
- "@\"CUPairedPeer\"32@?0@\"CUPairedPeer\"8Q16^@24"
- "@\"CUPairingIdentity\"24@?0Q8^@16"
- "@\"NSData\"28@?0I8@\"NSData\"12^@20"
- "AirPlay restrictions ignored\n"
- "B32@?0@\"CUPairedPeer\"8Q16^@24"
- "B36@?0I8@\"NSData\"12@\"NSData\"20^@28"
- "BLE CB connection interrupted.\n"
- "BLE CB connection invalidated.\n"
- "BLE client connection invalidated\n"
- "BLE client connection with bundleID: %@ and clientUseCase: %@\n"
- "BLE server connection invalidated\n"
- "Backwards compatibility authType (%s) -> (%s)"
- "Backwards compatibility change authType (%s) -> (%s)"
- "Bad PairSetup request object type %@"
- "Bad PairVerify request object type %@"
- "Client PairSetup retry\n"
- "Client connect start: %@\n"
- "Client error"
- "Client immediate non-RPIdentity retry\n"
- "Client state: %s -> %s\n"
- "Configuring for session pairing\n"
- "Connect failed"
- "Enabling FitnessPairing \n"
- "External state changed: %s -> %s\n"
- "Find paired peer handler for peer %@ options %lu\n"
- "Frame too big (%zu vs %u)"
- "In use processes updated to: %@\n"
- "LECA1"
- "LECA2"
- "LECA3"
- "LECA4"
- "Large Frame: Send frame 0x%02X (%s), <%.16@> (%zu bytes)\n"
- "Large Frame: Send request ID '%@', XID 0x%X, <%.16@> (%zu bytes) on link type %s\n"
- "Large Frame: Send response XID 0x%X, <%.16@> (%zu bytes) on link type %s, %#m\n"
- "Large Frame: SendEventID '%@', XID 0x%X, <%.16@> (%zu bytes) on link type %s\n"
- "No PairSetup client session"
- "No PairVerify client session"
- "OnDemand connection failed, invalidating\n"
- "PairSetup completed client.\n"
- "PairSetup completed server: %s\n"
- "PairSetup next (%d bytes)\n"
- "PairSetup response error: '%@'"
- "PairSetup server rejecting when not allowed\n"
- "PairSetup server rejecting when not allowing non-Home devices\n"
- "PairVerify completed client %s, %#{flags}, %#ll{flags}, RPI %@\n"
- "PairVerify completed server: %s, %#{flags}, %#ll{flags}, RPI %@\n"
- "PairVerify next (%d bytes)\n"
- "PairVerify start client: AT %s, CF %#ll{flags}, FL %#{flags}, PWT %s\n"
- "PairVerifySign success: CF %#ll{flags}, AF %#ll{flags}\n"
- "PairVerifySign: Not using RPI: CF %#ll{flags}, AF %#ll{flags}\n"
- "PairVerifyVerify success: %s, CF %#ll{flags}, AF %#ll{flags}\n"
- "PairVerifyVerify: Not using RPI: CF %#ll{flags}, AF %#ll{flags}\n"
- "Peer appears missing, invalidating\n"
- "Peer appears present, retrying\n"
- "Peer is blocking access, invalidating\n"
- "Peer may be unreachable, sending reachability probe (%s)\n"
- "Peer missing after retry timer, invalidating\n"
- "Queuing send event ID '%@', XID 0x%X (%d send(s) pending)\n"
- "Queuing send request ID '%@' (%d send(s) pending)\n"
- "Received PreAuthRequest: %##@\n"
- "Received PreAuthResponse: %##@\n"
- "Received SharedHome identity: ID '%.8@'\n"
- "Received client service type %@\n"
- "Received event ID '%@', XID 0x%X, %d keys, from %@\n"
- "Received identity from IDS '%.8@'\n"
- "Received requestID '%@', XID 0x%X, %d keys, from %@\n"
- "Received response XID 0x%X, %d keys, from %@, %llu ms request size %llu response size %llu\n"
- "Requested password type: %s auth type: %s\n"
- "Retrying delayed: %.3f seconds\n"
- "Retrying immediately: %{dur} since last retry\n"
- "Retrying immediately: first retry\n"
- "Retrying setup of CBConnection after error, attempt: %d"
- "Save paired peer handler for peer %@ options %lu\n"
- "Send PreAuthRequest: %##@\n"
- "Send PreAuthResponse: %##@\n"
- "Send SharedHome identity\n"
- "Send encrypted event failed: '%@', %{error}\n"
- "Send encrypted requestID '%@' failed: %{error}\n"
- "Send frame 0x%02X (%s), <%.16@> (%zu bytes)\n"
- "Send identity\n"
- "Send request ID '%@', XID 0x%X, <%.16@> (%zu bytes) on link type %s %s\n"
- "Send response XID 0x%X, <%.16@> (%zu bytes) on link type %s%s, %#m\n"
- "SendEventID '%@', XID 0x%X, <%.16@> (%zu bytes) on link type %s %s\n"
- "Sending client service type %@\n"
- "Server state: %s -> %s\n"
- "SystemInfo"
- "TCP client connection invalidated\n"
- "TCP server connection invalidated\n"
- "Too many retries, invalidating: retries %d, %@\n"
- "Transferring event ID %@ to connection %@"
- "Transferring request ID %@ to connection %@ with timeout %f\n"
- "Using AdHocPaired identifier for connection: %@"
- "_aaltDSID"
- "_accAltDSID"
- "_accID"
- "_actLvl"
- "_appID"
- "_appInfo"
- "_auTy"
- "_bf"
- "_btHP"
- "_c"
- "_cf"
- "_cht"
- "_clFl"
- "_clSrv"
- "_dC"
- "_dCapF"
- "_forcedRole"
- "_hkID"
- "_hkUID"
- "_idsCID"
- "_inUseProc"
- "_lP"
- "_mRtID"
- "_mrID"
- "_msId"
- "_msNm"
- "_msRo"
- "_msSt"
- "_osV"
- "_pd"
- "_ping"
- "_pubID"
- "_pwTy"
- "_rP"
- "_rT"
- "_roomName"
- "_sf"
- "_siriInfo"
- "_spID"
- "_stA"
- "_sv"
- "_t"
- "_x"
- "com.apple.admin"
- "hipri"
- "ids-message"
- "main"
- "public"
- "sendFrameType"
- "v16@?0I8i12"
- "v20@?0I8@\"NSData\"12"
- "v20@?0I8@\"NSString\"12"
- "v32@?0@\"NSNumber\"8@\"RPRequestEntry\"16^B24"
```
