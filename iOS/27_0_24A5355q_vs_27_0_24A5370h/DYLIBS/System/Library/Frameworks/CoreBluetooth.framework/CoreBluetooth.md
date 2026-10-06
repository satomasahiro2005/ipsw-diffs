## CoreBluetooth

> `/System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xce6e8` | `0xd7634` | **`+0x8f4c`** |
| `__AUTH_CONST.__cfstring` | `0xfaa0` | `0x11100` | **`+0x1660`** |
| `__TEXT.__cstring` | `0x19b51` | `0x1adc5` | **`+0x1274`** |
| `__AUTH_CONST.__objc_const` | `0x1b2c8` | `0x1c470` | **`+0x11a8`** |
| `__TEXT.__objc_methlist` | `0xcc64` | `0xd654` | **`+0x9f0`** |
| `__TEXT.__oslogstring` | `0x2905` | `0x30f7` | **`+0x7f2`** |
| `__DATA_CONST.__objc_selrefs` | `0x5780` | `0x5cb0` | **`+0x530`** |
| `__DATA_CONST.__const` | `0x6440` | `0x68a0` | **`+0x460`** |
| `__AUTH.__objc_data` | `0x6e0` | `0xa00` | **`+0x320`** |
| `__TEXT.__gcc_except_tab` | `0x2338` | `0x25ec` | **`+0x2b4`** |
| `__TEXT.__unwind_info` | `0x2740` | `0x29d0` | **`+0x290`** |
| `__DATA.__objc_ivar` | `0x1280` | `0x136c` | **`+0xec`** |
| `__DATA_CONST.__objc_classlist` | `0x300` | `0x350` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x3e8` | `0x420` | **`+0x38`** |
| `__DATA_CONST.__objc_superrefs` | `0x168` | `0x1a0` | **`+0x38`** |
| `__AUTH_CONST.__objc_dictobj` | `0xf0` | `0x118` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x5a0` | `0x5c0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xa18` | `0xa30` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x130` | `0x140` | **`+0x10`** |
| `__TEXT.__const` | `0x2cf9` | `0x2d01` | **`+0x8`** |

### Other Changes

```diff

-2700.37.0.0.0
+2700.41.1.1.0

-  Functions: 5295
-  Symbols:   7982
-  CStrings:  4835
+  Functions: 5524
+  Symbols:   8412
+  CStrings:  5104
Symbols:
+ -[CBCentralManager _handleLEAudioXpcEvents:]
+ -[CBCentralManager audioSessions]
+ -[CBCentralManager changeMicrophoneGainSettingForSession:forAudioInputType:withMicGain:withResponse:]
+ -[CBCentralManager changeVolumeForSession:withVolume:withResponse:]
+ -[CBCentralManager changeVolumeMuteStateForSession:withVolumeMuteState:withResponse:]
+ -[CBCentralManager changeVolumeOffsetForSession:toLocation:withVolumeOffSet:withResponse:]
+ -[CBCentralManager cisConnectEvent]
+ -[CBCentralManager cisDisconnectEvent]
+ -[CBCentralManager clearOtherDevices]
+ -[CBCentralManager connectCIS:]
+ -[CBCentralManager createSessionEvent:withMsg:]
+ -[CBCentralManager createXPCForLEAudio]
+ -[CBCentralManager disconnectCIS:]
+ -[CBCentralManager handleActivePresetUpdated:]
+ -[CBCentralManager handleConnectCISComplete:]
+ -[CBCentralManager handleConnectLEAudioComplete:]
+ -[CBCentralManager handleDisconnectCISComplete:]
+ -[CBCentralManager handleFeaturesUpdated:]
+ -[CBCentralManager handleLEAudioMsg:]
+ -[CBCentralManager handleLEAudioSessionEvents:]
+ -[CBCentralManager handleLEAudioXpcInterrupted]
+ -[CBCentralManager handleLEAudioXpcInvalid]
+ -[CBCentralManager handleMicrophoneGainUpdated:]
+ -[CBCentralManager handleMicrophoneInputDiscovered:]
+ -[CBCentralManager handleMicrophoneInputMuteUpdated:]
+ -[CBCentralManager handleMicrophoneInputStatusUpdated:]
+ -[CBCentralManager handleMicrophoneMuteUpdated:]
+ -[CBCentralManager handlePresetNameUpdated:]
+ -[CBCentralManager handlePresetsUpdated:]
+ -[CBCentralManager handleRemoveCIGComplete:]
+ -[CBCentralManager handleSessionCompleted:]
+ -[CBCentralManager handleSessionMicrophoneGainUpdated:]
+ -[CBCentralManager handleSessionMicrophoneMuteUpdated:]
+ -[CBCentralManager handleSessionVolumeMuteUpdated:]
+ -[CBCentralManager handleSessionVolumeOffsetUpdated:]
+ -[CBCentralManager handleSessionVolumeUpdated:]
+ -[CBCentralManager handleSetupCIGComplete:]
+ -[CBCentralManager handleVolumeInputDiscovered:]
+ -[CBCentralManager handleVolumeInputGainUpdated:]
+ -[CBCentralManager handleVolumeInputMuteUpdated:]
+ -[CBCentralManager handleVolumeInputStatusUpdated:]
+ -[CBCentralManager handleVolumeMuteUpdated:]
+ -[CBCentralManager handleVolumeOffsetUpdated:]
+ -[CBCentralManager handleVolumeUpdated:]
+ -[CBCentralManager initCISCentral]
+ -[CBCentralManager leAudioEventHandler]
+ -[CBCentralManager registerLEAudioClient]
+ -[CBCentralManager removeCIG:completion:]
+ -[CBCentralManager removeCIGCompletion]
+ -[CBCentralManager sendLEAudioMsg:args:completion:]
+ -[CBCentralManager setCisConnectEvent:]
+ -[CBCentralManager setCisDisconnectEvent:]
+ -[CBCentralManager setLeAudioEventHandler:]
+ -[CBCentralManager setMicrophoneMuteStateForSession:withMicMuteState:withResponse:]
+ -[CBCentralManager setRemoveCIGCompletion:]
+ -[CBCentralManager setSetupCIGCompletion:]
+ -[CBCentralManager setupCIG:completion:]
+ -[CBCentralManager setupCIGCompletion]
+ -[CBCentralManager startLEAudioXPC]
+ -[CBCentralManager updateScanForPeripheralsWithOptions:]
+ -[CBCoordinatedMemberInfo memberRank]
+ -[CBCoordinatedMemberInfo setMemberRank:]
+ -[CBCoordinatedSetInfo .cxx_destruct]
+ -[CBCoordinatedSetInfo connectedIdentifiers]
+ -[CBCoordinatedSetInfo copyWithZone:]
+ -[CBCoordinatedSetInfo initWithInfo:withSize:]
+ -[CBCoordinatedSetInfo setConnectedIdentifiers:]
+ -[CBCoordinatedSetInfo setName]
+ -[CBCoordinatedSetInfo setSetName:]
+ -[CBCoordinatedSetInfo setSetSize:]
+ -[CBCoordinatedSetInfo setSize]
+ -[CBDevice heySiriAuthTag]
+ -[CBDevice heySiriIdentityFlags]
+ -[CBDevice setHeySiriAuthTag:]
+ -[CBDevice setHeySiriIdentityFlags:]
+ -[CBDeviceHeySiriData .cxx_destruct]
+ -[CBDeviceHeySiriData heySiriAuthTag]
+ -[CBDeviceHeySiriData heySiriIdentityFlags]
+ -[CBDeviceHeySiriData setHeySiriAuthTag:]
+ -[CBDeviceHeySiriData setHeySiriIdentityFlags:]
+ -[CBDiscovery readBuffers]
+ -[CBISOReadRequest .cxx_destruct]
+ -[CBISOReadRequest completionHandler]
+ -[CBISOReadRequest data]
+ -[CBISOReadRequest error]
+ -[CBISOReadRequest missedReads]
+ -[CBISOReadRequest setCompletionHandler:]
+ -[CBISOReadRequest setData:]
+ -[CBISOReadRequest setError:]
+ -[CBISOReadRequest setMissedReads:]
+ -[CBISOWriteRequest .cxx_destruct]
+ -[CBISOWriteRequest completionHandler]
+ -[CBISOWriteRequest data]
+ -[CBISOWriteRequest error]
+ -[CBISOWriteRequest packetSequenceNumber]
+ -[CBISOWriteRequest setCompletionHandler:]
+ -[CBISOWriteRequest setData:]
+ -[CBISOWriteRequest setError:]
+ -[CBISOWriteRequest setPacketSequenceNumber:]
+ -[CBISOWriteRequest setStream:]
+ -[CBISOWriteRequest stream]
+ -[CBLEAudioHearingAidPreset .cxx_destruct]
+ -[CBLEAudioHearingAidPreset initWithValues:withProperty:withName:]
+ -[CBLEAudioHearingAidPreset isAvailable]
+ -[CBLEAudioHearingAidPreset isWritable]
+ -[CBLEAudioHearingAidPreset presetIndex]
+ -[CBLEAudioHearingAidPreset presetName]
+ -[CBLEAudioHearingAidUpdateEvent .cxx_destruct]
+ -[CBLEAudioHearingAidUpdateEvent activePreset]
+ -[CBLEAudioHearingAidUpdateEvent initWithEventType:]
+ -[CBLEAudioHearingAidUpdateEvent initWithValue:withValue:]
+ -[CBLEAudioHearingAidUpdateEvent presetResults]
+ -[CBLEAudioHearingAidUpdateEvent setActivePreset:]
+ -[CBLEAudioHearingAidUpdateEvent setPresetResults:]
+ -[CBLEAudioPeripheralInputGainDiscoveredEvent audioInputType]
+ -[CBLEAudioPeripheralInputGainDiscoveredEvent gainSettingMax]
+ -[CBLEAudioPeripheralInputGainDiscoveredEvent gainSettingMin]
+ -[CBLEAudioPeripheralInputGainDiscoveredEvent gainSettingUnit]
+ -[CBLEAudioPeripheralInputGainDiscoveredEvent initWithValue:withDescription:andInputType:]
+ -[CBLEAudioPeripheralInputGainDiscoveredEvent setAudioInputGainSettingInfo:withGainMin:withGainMax:]
+ -[CBLEAudioPeripheralUpdateEvent .cxx_destruct]
+ -[CBLEAudioPeripheralUpdateEvent error]
+ -[CBLEAudioPeripheralUpdateEvent eventType]
+ -[CBLEAudioPeripheralUpdateEvent includedServiceDescription]
+ -[CBLEAudioPeripheralUpdateEvent initWithError:withError:]
+ -[CBLEAudioPeripheralUpdateEvent initWithEventType:]
+ -[CBLEAudioPeripheralUpdateEvent initWithValue:withValue:]
+ -[CBLEAudioPeripheralUpdateEvent setOptionalIncludedServiceDescription:]
+ -[CBLEAudioPeripheralUpdateEvent updatedValue]
+ -[CBLEAudioSessionEvent .cxx_destruct]
+ -[CBLEAudioSessionEvent error]
+ -[CBLEAudioSessionEvent eventType]
+ -[CBLEAudioSessionEvent initWithEventType:withError:]
+ -[CBLEAudioSessionEvent sessionInfo]
+ -[CBLEAudioSessionEvent setError:]
+ -[CBLEAudioSessionEvent setSessionInfo:]
+ -[CBLEAudioSessionEvent setUpdatedValue:]
+ -[CBLEAudioSessionEvent updatedValue]
+ -[CBLEAudioSessionInfo .cxx_destruct]
+ -[CBLEAudioSessionInfo audioSessionIdentifier]
+ -[CBLEAudioSessionInfo connectedIdentifiers]
+ -[CBLEAudioSessionInfo coordinatedSetInfo]
+ -[CBLEAudioSessionInfo copyWithZone:]
+ -[CBLEAudioSessionInfo initWithInfo:withSessionId:withState:withCoordIds:withLocation:]
+ -[CBLEAudioSessionInfo initWithSession:]
+ -[CBLEAudioSessionInfo locations]
+ -[CBLEAudioSessionInfo retrieveConnectedLEAudioPeripheralIdentifiers]
+ -[CBLEAudioSessionInfo sessionState]
+ -[CBManager setTccAbort:]
+ -[CBManager tccAbort]
+ -[CBPeripheral deviceType]
+ -[CBPeripheral dynamicPresets]
+ -[CBPeripheral handleLEAudioActivePresetUpdated:]
+ -[CBPeripheral handleLEAudioConnected:]
+ -[CBPeripheral handleLEAudioEvents:]
+ -[CBPeripheral handleLEAudioHearingAidFeaturesUpdated:]
+ -[CBPeripheral handleLEAudioMicrophoneGainUpdated:]
+ -[CBPeripheral handleLEAudioMicrophoneInputDiscovered:]
+ -[CBPeripheral handleLEAudioMicrophoneInputMuteUpdated:]
+ -[CBPeripheral handleLEAudioMicrophoneInputStatusUpdated:]
+ -[CBPeripheral handleLEAudioMicrophoneMuteUpdated:]
+ -[CBPeripheral handleLEAudioMsg:args:]
+ -[CBPeripheral handleLEAudioPresetNameUpdated:]
+ -[CBPeripheral handleLEAudioPresetUpdated:]
+ -[CBPeripheral handleLEAudioVolumeGainUpdated:]
+ -[CBPeripheral handleLEAudioVolumeInputDiscovered:]
+ -[CBPeripheral handleLEAudioVolumeInputMuteUpdated:]
+ -[CBPeripheral handleLEAudioVolumeInputStatusUpdated:]
+ -[CBPeripheral handleLEAudioVolumeMuteUpdated:]
+ -[CBPeripheral handleLEAudioVolumeOffsetUpdated:]
+ -[CBPeripheral handleLEAudioVolumeUpdated:]
+ -[CBPeripheral hearingAidType]
+ -[CBPeripheral independentPresets]
+ -[CBPeripheral location]
+ -[CBPeripheral presetSyncSupported]
+ -[CBPeripheral readPresets:]
+ -[CBPeripheral sendLEAudioMsg:args:completion:]
+ -[CBPeripheral setActivePreset:OptionalPresetIndex:withResponse:]
+ -[CBPeripheral setLEAudioDeviceType:]
+ -[CBPeripheral setLEAudioLocation:]
+ -[CBPeripheral setMicrophoneMute:withResponse:]
+ -[CBPeripheral setUpdateHandler:]
+ -[CBPeripheral setVolume:withResponse:]
+ -[CBPeripheral setVolumeMute:withResponse:]
+ -[CBPeripheral setVolumeOffSet:withOffSetValue:withResponse:]
+ -[CBPeripheral updateHandler]
+ -[CBPeripheral writablePresets]
+ -[CBPeripheral writeMicrophoneAudioInput:forAudioInputType:withInputDescription:withOptionalGain:withResponse:]
+ -[CBPeripheral writePresetName:withName:withResponse:]
+ -[CBPeripheral writeVolumeAudioInput:forAudioInputType:withInputDescription:withOptionalGain:withResponse:]
+ -[CBPeripheralManager cisPeripheralConnectEvent]
+ -[CBPeripheralManager cisPeripheralDisconnectEvent]
+ -[CBPeripheralManager disconnectCISPeripheral:]
+ -[CBPeripheralManager handleConnectCISPeripheralComplete:]
+ -[CBPeripheralManager handleDisconnectCISPeripheralComplete:]
+ -[CBPeripheralManager handleIncomingCISConnectionRequest:]
+ -[CBPeripheralManager initCISPeripheral:completion:]
+ -[CBPeripheralManager respondToCISConnectionRequest:]
+ -[CBPeripheralManager setCisPeripheralConnectEvent:]
+ -[CBPeripheralManager setCisPeripheralDisconnectEvent:]
+ -[CBServer _reportError:]
+ -[CBServer errorHandler]
+ -[CBServer setErrorHandler:]
+ GCC_except_table105
+ GCC_except_table185
+ GCC_except_table187
+ GCC_except_table189
+ GCC_except_table190
+ GCC_except_table191
+ GCC_except_table192
+ GCC_except_table193
+ GCC_except_table31
+ GCC_except_table42
+ GCC_except_table521
+ GCC_except_table526
+ GCC_except_table541
+ GCC_except_table57
+ GCC_except_table58
+ GCC_except_table59
+ GCC_except_table604
+ GCC_except_table65
+ GCC_except_table66
+ GCC_except_table68
+ _CBUUIDActivePresetIndexCharacteristicString
+ _CBUUIDAudioInputControlPointCharacteristicString
+ _CBUUIDAudioInputControlServiceString
+ _CBUUIDAudioInputDescriptionCharacteristicString
+ _CBUUIDAudioInputStateCharacteristicString
+ _CBUUIDAudioInputStatusCharacteristicString
+ _CBUUIDAudioInputTypeCharacteristicString
+ _CBUUIDAudioLocationCharacteristicString
+ _CBUUIDAudioOutputDescriptionCharacteristicString
+ _CBUUIDBearerListCurrentCallsCharacteristicString
+ _CBUUIDBearerProviderNameCharacteristicString
+ _CBUUIDBearerSignalStrengthCharacteristicString
+ _CBUUIDBearerSignalStrengthReportingIntervalCharacteristicString
+ _CBUUIDBearerTechnologyCharacteristicString
+ _CBUUIDBearerUciCharacteristicString
+ _CBUUIDBearerUriSchemesSupportedListCharacteristicString
+ _CBUUIDCallControlPointCharacteristicString
+ _CBUUIDCallControlPointOptionalOpcodesCharacteristicString
+ _CBUUIDCallFriendlyNameCharacteristicString
+ _CBUUIDCallStateCharacteristicString
+ _CBUUIDContentControlIdCharacteristicString
+ _CBUUIDCoordinatedSetIdServiceString
+ _CBUUIDCoordinatedSetSizeCharacteristicString
+ _CBUUIDCurrentGroupObjectIDCharacteristicString
+ _CBUUIDCurrentTrackObjectIDCharacteristicString
+ _CBUUIDCurrentTrackSegmentsObjectIDCharacteristicString
+ _CBUUIDGainSettingPropertiesCharacteristicString
+ _CBUUIDGenericMediaControlServiceString
+ _CBUUIDGenericTelephoneBearerServiceString
+ _CBUUIDHearingAccessServiceString
+ _CBUUIDHearingAidFeaturesCharacteristicString
+ _CBUUIDHearingAidPresetControlPointCharacteristicString
+ _CBUUIDIncomingCallCharacteristicString
+ _CBUUIDIncomingCallTargetBearerUriCharacteristicString
+ _CBUUIDMediaControlPointCharacteristicString
+ _CBUUIDMediaControlPointOpcodesSupportedCharacteristicString
+ _CBUUIDMediaControlServiceString
+ _CBUUIDMediaPlayerIconObjectIDCharacteristicString
+ _CBUUIDMediaPlayerIconURLCharacteristicString
+ _CBUUIDMediaPlayerNameCharacteristicString
+ _CBUUIDMediaStateCharacteristicString
+ _CBUUIDMicrophoneControlServiceString
+ _CBUUIDMuteCharacteristicString
+ _CBUUIDNextTrackObjectIDCharacteristicString
+ _CBUUIDParentGroupObjectIDCharacteristicString
+ _CBUUIDPlaybackSpeedCharacteristicString
+ _CBUUIDPlayingOrderCharacteristicString
+ _CBUUIDPlayingOrdersSupportedCharacteristicString
+ _CBUUIDSearchControlPointCharacteristicString
+ _CBUUIDSearchResultsObjectIDCharacteristicString
+ _CBUUIDSeekingSpeedCharacteristicString
+ _CBUUIDSetIdResolvingKeyCharacteristicString
+ _CBUUIDSetMemberLockCharacteristicString
+ _CBUUIDSetMemberRankCharacteristicString
+ _CBUUIDStatusFlagsCharacteristicString
+ _CBUUIDTMAPRoleCharacteristicString
+ _CBUUIDTelephoneBearerServiceString
+ _CBUUIDTelephonyMediaAudioServiceString
+ _CBUUIDTerminationReasonCharacteristicString
+ _CBUUIDTrackChangedCharacteristicString
+ _CBUUIDTrackDurationCharacteristicString
+ _CBUUIDTrackPositionCharacteristicString
+ _CBUUIDTrackTitleCharacteristicString
+ _CBUUIDVolumeControlPointCharacteristicString
+ _CBUUIDVolumeControlServiceString
+ _CBUUIDVolumeFlagsCharacteristicString
+ _CBUUIDVolumeOffsetControlPointCharacteristicString
+ _CBUUIDVolumeOffsetControlServiceString
+ _CBUUIDVolumeOffsetStateCharacteristicString
+ _CBUUIDVolumeStateCharacteristicString
+ _OBJC_CLASS_$_CBCoordinatedMemberInfo
+ _OBJC_CLASS_$_CBCoordinatedSetInfo
+ _OBJC_CLASS_$_CBISOReadRequest
+ _OBJC_CLASS_$_CBISOWriteRequest
+ _OBJC_CLASS_$_CBLEAudioHearingAidPreset
+ _OBJC_CLASS_$_CBLEAudioHearingAidUpdateEvent
+ _OBJC_CLASS_$_CBLEAudioPeripheralInputGainDiscoveredEvent
+ _OBJC_CLASS_$_CBLEAudioPeripheralUpdateEvent
+ _OBJC_CLASS_$_CBLEAudioSessionEvent
+ _OBJC_CLASS_$_CBLEAudioSessionInfo
+ _OBJC_IVAR_$_CBCentralManager._audioSessions
+ _OBJC_IVAR_$_CBCentralManager._cisConnectEvent
+ _OBJC_IVAR_$_CBCentralManager._cisDisconnectEvent
+ _OBJC_IVAR_$_CBCentralManager._leAudioDevice
+ _OBJC_IVAR_$_CBCentralManager._leAudioEventHandler
+ _OBJC_IVAR_$_CBCentralManager._leAudioXpcConnection
+ _OBJC_IVAR_$_CBCentralManager._removeCIGCompletion
+ _OBJC_IVAR_$_CBCentralManager._setupCIGCompletion
+ _OBJC_IVAR_$_CBCentralManager._validLeAudioXpcCalled
+ _OBJC_IVAR_$_CBCoordinatedMemberInfo._memberRank
+ _OBJC_IVAR_$_CBCoordinatedSetInfo._connectedIdentifiers
+ _OBJC_IVAR_$_CBCoordinatedSetInfo._setName
+ _OBJC_IVAR_$_CBCoordinatedSetInfo._setSize
+ _OBJC_IVAR_$_CBDeviceHeySiriData._heySiriAuthTag
+ _OBJC_IVAR_$_CBDeviceHeySiriData._heySiriIdentityFlags
+ _OBJC_IVAR_$_CBISOReadRequest._completionHandler
+ _OBJC_IVAR_$_CBISOReadRequest._data
+ _OBJC_IVAR_$_CBISOReadRequest._error
+ _OBJC_IVAR_$_CBISOReadRequest._missedReads
+ _OBJC_IVAR_$_CBISOWriteRequest._completionHandler
+ _OBJC_IVAR_$_CBISOWriteRequest._data
+ _OBJC_IVAR_$_CBISOWriteRequest._error
+ _OBJC_IVAR_$_CBISOWriteRequest._packetSequenceNumber
+ _OBJC_IVAR_$_CBISOWriteRequest._stream
+ _OBJC_IVAR_$_CBLEAudioHearingAidPreset._isAvailable
+ _OBJC_IVAR_$_CBLEAudioHearingAidPreset._isWritable
+ _OBJC_IVAR_$_CBLEAudioHearingAidPreset._presetIndex
+ _OBJC_IVAR_$_CBLEAudioHearingAidPreset._presetName
+ _OBJC_IVAR_$_CBLEAudioHearingAidUpdateEvent._activePreset
+ _OBJC_IVAR_$_CBLEAudioHearingAidUpdateEvent._presetResults
+ _OBJC_IVAR_$_CBLEAudioPeripheralInputGainDiscoveredEvent._audioInputType
+ _OBJC_IVAR_$_CBLEAudioPeripheralInputGainDiscoveredEvent._gainSettingMax
+ _OBJC_IVAR_$_CBLEAudioPeripheralInputGainDiscoveredEvent._gainSettingMin
+ _OBJC_IVAR_$_CBLEAudioPeripheralInputGainDiscoveredEvent._gainSettingUnit
+ _OBJC_IVAR_$_CBLEAudioPeripheralUpdateEvent._error
+ _OBJC_IVAR_$_CBLEAudioPeripheralUpdateEvent._eventType
+ _OBJC_IVAR_$_CBLEAudioPeripheralUpdateEvent._includedServiceDescription
+ _OBJC_IVAR_$_CBLEAudioPeripheralUpdateEvent._updatedValue
+ _OBJC_IVAR_$_CBLEAudioSessionEvent._error
+ _OBJC_IVAR_$_CBLEAudioSessionEvent._eventType
+ _OBJC_IVAR_$_CBLEAudioSessionEvent._sessionInfo
+ _OBJC_IVAR_$_CBLEAudioSessionEvent._updatedValue
+ _OBJC_IVAR_$_CBLEAudioSessionInfo._audioSessionIdentifier
+ _OBJC_IVAR_$_CBLEAudioSessionInfo._connectedIdentifiers
+ _OBJC_IVAR_$_CBLEAudioSessionInfo._coordinatedSetInfo
+ _OBJC_IVAR_$_CBLEAudioSessionInfo._locations
+ _OBJC_IVAR_$_CBLEAudioSessionInfo._sessionState
+ _OBJC_IVAR_$_CBManager._tccAbort
+ _OBJC_IVAR_$_CBPeripheral._deviceType
+ _OBJC_IVAR_$_CBPeripheral._dynamicPresets
+ _OBJC_IVAR_$_CBPeripheral._hearingAidType
+ _OBJC_IVAR_$_CBPeripheral._independentPresets
+ _OBJC_IVAR_$_CBPeripheral._location
+ _OBJC_IVAR_$_CBPeripheral._presetSyncSupported
+ _OBJC_IVAR_$_CBPeripheral._updateHandler
+ _OBJC_IVAR_$_CBPeripheral._writablePresets
+ _OBJC_IVAR_$_CBPeripheralManager._cisPeripheralConnectEvent
+ _OBJC_IVAR_$_CBPeripheralManager._cisPeripheralDisconnectEvent
+ _OBJC_IVAR_$_CBServer._errorHandler
+ _OBJC_METACLASS_$_CBCoordinatedMemberInfo
+ _OBJC_METACLASS_$_CBCoordinatedSetInfo
+ _OBJC_METACLASS_$_CBISOReadRequest
+ _OBJC_METACLASS_$_CBISOWriteRequest
+ _OBJC_METACLASS_$_CBLEAudioHearingAidPreset
+ _OBJC_METACLASS_$_CBLEAudioHearingAidUpdateEvent
+ _OBJC_METACLASS_$_CBLEAudioPeripheralInputGainDiscoveredEvent
+ _OBJC_METACLASS_$_CBLEAudioPeripheralUpdateEvent
+ _OBJC_METACLASS_$_CBLEAudioSessionEvent
+ _OBJC_METACLASS_$_CBLEAudioSessionInfo
+ __OBJC_$_INSTANCE_METHODS_CBCoordinatedMemberInfo
+ __OBJC_$_INSTANCE_METHODS_CBCoordinatedSetInfo
+ __OBJC_$_INSTANCE_METHODS_CBISOReadRequest
+ __OBJC_$_INSTANCE_METHODS_CBISOWriteRequest
+ __OBJC_$_INSTANCE_METHODS_CBLEAudioHearingAidPreset
+ __OBJC_$_INSTANCE_METHODS_CBLEAudioHearingAidUpdateEvent
+ __OBJC_$_INSTANCE_METHODS_CBLEAudioPeripheralInputGainDiscoveredEvent
+ __OBJC_$_INSTANCE_METHODS_CBLEAudioPeripheralUpdateEvent
+ __OBJC_$_INSTANCE_METHODS_CBLEAudioSessionEvent
+ __OBJC_$_INSTANCE_METHODS_CBLEAudioSessionInfo
+ __OBJC_$_INSTANCE_VARIABLES_CBCoordinatedMemberInfo
+ __OBJC_$_INSTANCE_VARIABLES_CBCoordinatedSetInfo
+ __OBJC_$_INSTANCE_VARIABLES_CBISOReadRequest
+ __OBJC_$_INSTANCE_VARIABLES_CBISOWriteRequest
+ __OBJC_$_INSTANCE_VARIABLES_CBLEAudioHearingAidPreset
+ __OBJC_$_INSTANCE_VARIABLES_CBLEAudioHearingAidUpdateEvent
+ __OBJC_$_INSTANCE_VARIABLES_CBLEAudioPeripheralInputGainDiscoveredEvent
+ __OBJC_$_INSTANCE_VARIABLES_CBLEAudioPeripheralUpdateEvent
+ __OBJC_$_INSTANCE_VARIABLES_CBLEAudioSessionEvent
+ __OBJC_$_INSTANCE_VARIABLES_CBLEAudioSessionInfo
+ __OBJC_$_PROP_LIST_CBCoordinatedMemberInfo
+ __OBJC_$_PROP_LIST_CBCoordinatedSetInfo
+ __OBJC_$_PROP_LIST_CBISOReadRequest
+ __OBJC_$_PROP_LIST_CBISOWriteRequest
+ __OBJC_$_PROP_LIST_CBLEAudioHearingAidPreset
+ __OBJC_$_PROP_LIST_CBLEAudioHearingAidUpdateEvent
+ __OBJC_$_PROP_LIST_CBLEAudioPeripheralInputGainDiscoveredEvent
+ __OBJC_$_PROP_LIST_CBLEAudioPeripheralUpdateEvent
+ __OBJC_$_PROP_LIST_CBLEAudioSessionEvent
+ __OBJC_$_PROP_LIST_CBLEAudioSessionInfo
+ __OBJC_CLASS_RO_$_CBCoordinatedMemberInfo
+ __OBJC_CLASS_RO_$_CBCoordinatedSetInfo
+ __OBJC_CLASS_RO_$_CBISOReadRequest
+ __OBJC_CLASS_RO_$_CBISOWriteRequest
+ __OBJC_CLASS_RO_$_CBLEAudioHearingAidPreset
+ __OBJC_CLASS_RO_$_CBLEAudioHearingAidUpdateEvent
+ __OBJC_CLASS_RO_$_CBLEAudioPeripheralInputGainDiscoveredEvent
+ __OBJC_CLASS_RO_$_CBLEAudioPeripheralUpdateEvent
+ __OBJC_CLASS_RO_$_CBLEAudioSessionEvent
+ __OBJC_CLASS_RO_$_CBLEAudioSessionInfo
+ __OBJC_METACLASS_RO_$_CBCoordinatedMemberInfo
+ __OBJC_METACLASS_RO_$_CBCoordinatedSetInfo
+ __OBJC_METACLASS_RO_$_CBISOReadRequest
+ __OBJC_METACLASS_RO_$_CBISOWriteRequest
+ __OBJC_METACLASS_RO_$_CBLEAudioHearingAidPreset
+ __OBJC_METACLASS_RO_$_CBLEAudioHearingAidUpdateEvent
+ __OBJC_METACLASS_RO_$_CBLEAudioPeripheralInputGainDiscoveredEvent
+ __OBJC_METACLASS_RO_$_CBLEAudioPeripheralUpdateEvent
+ __OBJC_METACLASS_RO_$_CBLEAudioSessionEvent
+ __OBJC_METACLASS_RO_$_CBLEAudioSessionInfo
+ ___26-[CBDiscovery readBuffers]_block_invoke
+ ___35-[CBCentralManager startLEAudioXPC]_block_invoke
+ ___39-[CBCentralManager createXPCForLEAudio]_block_invoke
+ ___41-[CBCentralManager handlePresetsUpdated:]_block_invoke
+ ___41-[CBCentralManager handlePresetsUpdated:]_block_invoke_2
+ ___41-[CBCentralManager handlePresetsUpdated:]_block_invoke_3
+ ___41-[CBCentralManager registerLEAudioClient]_block_invoke
+ ___46-[CBCentralManager connectPeripheral:options:]_block_invoke_2
+ ___47-[CBCentralManager createSessionEvent:withMsg:]_block_invoke
+ ___51-[CBCentralManager sendLEAudioMsg:args:completion:]_block_invoke
+ ___CBFRAMEWORK_CRASHING_DUE_TO_PRIVACY_VIOLATION__
+ ___block_descriptor_32_e17_v16?0"NSError"8l
+ _dispatch_after
+ _xpc_dictionary_get_uuid
+ _xpc_uint64_create
- GCC_except_table15
- GCC_except_table17
- GCC_except_table517
- GCC_except_table522
- GCC_except_table537
- GCC_except_table55
- GCC_except_table600
CStrings:
+ "### Error: %@"
+ "### Read buffers after invalidate"
+ "### Read buffers before activation"
+ "### Read buffers no buffered types configured"
+ ", hsAT %@"
+ ", hsIF 0x%02X"
+ "-[CBDiscovery readBuffers]_block_invoke"
+ "-[CBServer _reportError:]"
+ "1843"
+ "1844"
+ "1845"
+ "1846"
+ "1848"
+ "1849"
+ "184B"
+ "184C"
+ "184D"
+ "1854"
+ "1855"
+ "2B51"
+ "2B77"
+ "2B78"
+ "2B79"
+ "2B7A"
+ "2B7B"
+ "2B7C"
+ "2B7D"
+ "2B7E"
+ "2B7F"
+ "2B80"
+ "2B81"
+ "2B82"
+ "2B83"
+ "2B84"
+ "2B85"
+ "2B86"
+ "2B87"
+ "2B93"
+ "2B94"
+ "2B95"
+ "2B96"
+ "2B97"
+ "2B98"
+ "2B99"
+ "2B9A"
+ "2B9B"
+ "2B9C"
+ "2B9D"
+ "2B9E"
+ "2B9F"
+ "2BA0"
+ "2BA1"
+ "2BA2"
+ "2BA3"
+ "2BA4"
+ "2BA5"
+ "2BA6"
+ "2BA7"
+ "2BB3"
+ "2BB4"
+ "2BB5"
+ "2BB6"
+ "2BB7"
+ "2BB8"
+ "2BB9"
+ "2BBA"
+ "2BBB"
+ "2BBC"
+ "2BBD"
+ "2BBE"
+ "2BBF"
+ "2BC0"
+ "2BC1"
+ "2BC2"
+ "2BC3"
+ "2BDA"
+ "2BDB"
+ "2BDC"
+ "Active Preset Index"
+ "Audio Input Control Point"
+ "Audio Input Control Service"
+ "Audio Input Description"
+ "Audio Input State"
+ "Audio Input Status"
+ "Audio Input Type"
+ "Audio Location"
+ "Audio Output Description"
+ "Bearer List Current Calls"
+ "Bearer Provider Name"
+ "Bearer Signal Strength"
+ "Bearer Signal Strength Reporting Interval"
+ "Bearer Technology"
+ "Bearer UCI"
+ "Bearer URI Schemes Supported List"
+ "CBMsgIdUpdateScan"
+ "Call Control Point"
+ "Call Control Point Optional Opcodes"
+ "Call Friendly Name"
+ "Call State"
+ "Calling LE audio event handler"
+ "Content Control Id"
+ "Coordinated Set Identification Service"
+ "Coordinated Set Size"
+ "Create LE audio XPC"
+ "Current Group Object ID"
+ "Current Track Object ID"
+ "Current Track Segments Object ID"
+ "DsRB"
+ "Failed to create LE audio XPC"
+ "Failed to send LE audio register message over XPC, %@"
+ "Gain Setting Properties"
+ "Generated event: %@"
+ "Generic Media Control Service"
+ "Generic Telephone Bearer Service"
+ "Hearing Access Service"
+ "Hearing Aid Features"
+ "Hearing Aid Preset Control Point"
+ "Incoming CIS Connection Request Received"
+ "Incoming Call"
+ "Incoming Call Target Bearer URI"
+ "LE audio XPC interrupted"
+ "LE audio XPC invalid"
+ "LE audio message is nil"
+ "LE audio unregistered"
+ "LECAHap"
+ "LECAHapLow"
+ "LECATmap"
+ "LECATmapLow"
+ "Media Control Point"
+ "Media Control Point Opcodes Supported"
+ "Media Control Service"
+ "Media Player Icon Object ID"
+ "Media Player Icon URL"
+ "Media Player Name"
+ "Media State"
+ "Microphone Control Service"
+ "MobileBluetooth-2700.41.1.1"
+ "Mute"
+ "Next Track Object ID"
+ "No LE audio event handher found"
+ "Not LE audio XPC allowed"
+ "Parent Group Object ID"
+ "Playback Speed"
+ "Playing Order"
+ "Playing Orders Supported"
+ "Q"
+ "Ready to use LE audio"
+ "Received XPC message for LE audio - %s: %@"
+ "Search Control Point"
+ "Search Results Object ID"
+ "Seeking Speed"
+ "Set Identity Resolving Key"
+ "Set LE Audio device type: %@"
+ "Set Member Lock"
+ "Set Member Rank"
+ "Status Flags"
+ "TCC available %d, req %d complete %d abort:%d"
+ "TMAP Role"
+ "Telephone Bearer Service"
+ "Telephony and Media Audio Service"
+ "Termination Reason"
+ "This app has crashed because it attempted to access privacy-sensitive data without a usage description. The app's Info.plist must contain an `NSBluetoothAlwaysUsageDescription` key with a string value explaining to the user how the app uses this data."
+ "Track Changed"
+ "Track Duration"
+ "Track Position"
+ "Track Title"
+ "Unexpected LE audio XPC error: %@"
+ "Unexpected LE audio XPC event: %@"
+ "Unhandled message: %d"
+ "Unsupported message for LE audio"
+ "Volume Control Point"
+ "Volume Control Service"
+ "Volume Flags"
+ "Volume Offset Control Point"
+ "Volume Offset Control Service"
+ "Volume Offset State"
+ "Volume State"
+ "WARNING: No LE audio event handler registered:%@"
+ "com.apple.bluetoothaudiod.cb"
+ "com.apple.bluetoothaudiod.leaudio-extension"
+ "connectPeripheral failed: peripheral %@ not found"
+ "connectPeripheral with AutoReconnect option requires delegate to implement centralManager:didDisconnectPeripheral:timestamp:isReconnecting:error: (peripheral %@)"
+ "handleLEAudioActivePresetUpdated, %@"
+ "handleLEAudioHearingAidFeaturesUpdated, %@"
+ "handleLEAudioMicrophoneGainUpdated, inputDescription: %@, gain: %@"
+ "handleLEAudioMicrophoneInputDiscovered, inputDescription: %@ inputType: %@"
+ "handleLEAudioMicrophoneInputMuteUpdated, inputDescription: %@, mute: %@"
+ "handleLEAudioMicrophoneInputMuteUpdated, inputDescription: %@, status: %@"
+ "handleLEAudioMicrophoneMuteUpdated, %@"
+ "handleLEAudioPresetUpdated, size:%d, %@, %@, %@"
+ "handleLEAudioVolumeGainUpdated, inputDescription: %@, gain: %@"
+ "handleLEAudioVolumeInputDiscovered, inputDescription: %@ inputType: %@"
+ "handleLEAudioVolumeInputMuteUpdated, inputDescription: %@, mute: %@"
+ "handleLEAudioVolumeInputStatusUpdated, inputDescription: %@, status: %@"
+ "handleLEAudioVolumeMuteUpdated, %@"
+ "handleLEAudioVolumeOffsetUpdated, %@"
+ "handleLEAudioVolumeUpdated, %@"
+ "handleSessionCompleted"
+ "handleSessionMicrophoneGainUpdated - %@"
+ "handleSessionMicrophoneMuteUpdated - %@"
+ "handleSessionVolumeMuteUpdated - %@"
+ "handleSessionVolumeOffsetUpdated - %@"
+ "handleSessionVolumeUpdated - %@"
+ "handleSetupCIGComplete"
+ "hsAT"
+ "hsIF"
+ "kCBMsgArgLEAudioAudioGainSettingMax"
+ "kCBMsgArgLEAudioAudioGainSettingMin"
+ "kCBMsgArgLEAudioAudioGainSettingUnit"
+ "kCBMsgArgLEAudioAudioInputDescription"
+ "kCBMsgArgLEAudioAudioInputOpcode"
+ "kCBMsgArgLEAudioAudioInputStatus"
+ "kCBMsgArgLEAudioAudioInputType"
+ "kCBMsgArgLEAudioClient"
+ "kCBMsgArgLEAudioCoordinatedSetIds"
+ "kCBMsgArgLEAudioCoordinatedSetSize"
+ "kCBMsgArgLEAudioDevicePresetIndexes"
+ "kCBMsgArgLEAudioDevicePresetNames"
+ "kCBMsgArgLEAudioDevicePresetProperties"
+ "kCBMsgArgLEAudioDeviceUUID"
+ "kCBMsgArgLEAudioHearingAidDynamic"
+ "kCBMsgArgLEAudioHearingAidIndependent"
+ "kCBMsgArgLEAudioHearingAidSyncSupported"
+ "kCBMsgArgLEAudioHearingAidType"
+ "kCBMsgArgLEAudioHearingAidWritable"
+ "kCBMsgArgLEAudioLocation"
+ "kCBMsgArgLEAudioMicrophoneGain"
+ "kCBMsgArgLEAudioMicrophoneMuteState"
+ "kCBMsgArgLEAudioPresetIndex"
+ "kCBMsgArgLEAudioPresetName"
+ "kCBMsgArgLEAudioPresetType"
+ "kCBMsgArgLEAudioServiceID"
+ "kCBMsgArgLEAudioSessionID"
+ "kCBMsgArgLEAudioVolume"
+ "kCBMsgArgLEAudioVolumeGain"
+ "kCBMsgArgLEAudioVolumeMuteState"
+ "kCBMsgArgLEAudioVolumeOffset"
+ "kCBMsgArgTCCAbortMissingUsageString"
+ "kCBMsgChangeSessionMicrophoneGain"
+ "kCBMsgChangeSessionMicrophoneMuteState"
+ "kCBMsgChangeSessionVolume"
+ "kCBMsgChangeSessionVolumeMuteState"
+ "kCBMsgChangeSessionVolumeOffset"
+ "kCBMsgLEAudioActivePresetUpdated"
+ "kCBMsgLEAudioHearingAidFeaturesUpdated"
+ "kCBMsgLEAudioMicrophoneInputDiscovered"
+ "kCBMsgLEAudioMicrophoneInputGainUpdated"
+ "kCBMsgLEAudioMicrophoneInputMuteUpdated"
+ "kCBMsgLEAudioMicrophoneInputStatusUpdated"
+ "kCBMsgLEAudioMicrophoneMuteUpdated"
+ "kCBMsgLEAudioPresetNameUpdated"
+ "kCBMsgLEAudioReadPresetUpdated"
+ "kCBMsgLEAudioRegister"
+ "kCBMsgLEAudioSessionCompleted"
+ "kCBMsgLEAudioSessionMicrophoneGainUpdated"
+ "kCBMsgLEAudioSessionMicrophoneMuteUpdated"
+ "kCBMsgLEAudioSessionVolumeMuteUpdated"
+ "kCBMsgLEAudioSessionVolumeOffsetUpdated"
+ "kCBMsgLEAudioSessionVolumeUpdated"
+ "kCBMsgLEAudioUnregistered"
+ "kCBMsgLEAudioVolumeInputDiscovered"
+ "kCBMsgLEAudioVolumeInputGainUpdated"
+ "kCBMsgLEAudioVolumeInputMuteUpdated"
+ "kCBMsgLEAudioVolumeInputStatusUpdated"
+ "kCBMsgLEAudioVolumeMuteUpdated"
+ "kCBMsgLEAudioVolumeOffsetUpdated"
+ "kCBMsgLEAudioVolumeUpdated"
+ "kCBMsgReadPresets"
+ "kCBMsgSetActivePreset"
+ "kCBMsgSetMicrophoneMute"
+ "kCBMsgSetVolume"
+ "kCBMsgSetVolumeMute"
+ "kCBMsgSetVolumeOffSet"
+ "kCBMsgWriteMicrophoneAudioInput"
+ "kCBMsgWritePresetName"
+ "kCBMsgWriteVolumeAudioInput"
+ "updateScanForPeripheralsWithOptions: rejected — no active scan to update; caller must use scanForPeripheralsWithServices:options: first"
+ "\xc1"
- "A"
- "LECA1"
- "LECA2"
- "LECA3"
- "LECA4"
- "MobileBluetooth-2700.37"
- "TCC available %d, req %d complete %d"
- "\xa1"
- "\xb5"
```
