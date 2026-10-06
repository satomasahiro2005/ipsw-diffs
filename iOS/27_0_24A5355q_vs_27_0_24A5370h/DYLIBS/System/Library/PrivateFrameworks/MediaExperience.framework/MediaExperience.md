## MediaExperience

> `/System/Library/PrivateFrameworks/MediaExperience.framework/MediaExperience`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2dc68c` | `0x2e5e5c` | **`+0x97d0`** |
| `__TEXT.__oslogstring` | `0x7639d` | `0x77b7f` | **`+0x17e2`** |
| `__TEXT.__cstring` | `0x4d092` | `0x4dfab` | **`+0xf19`** |
| `__TEXT.__gcc_except_tab` | `0x473c` | `0x518c` | **`+0xa50`** |
| `__TEXT.__unwind_info` | `0x6040` | `0x6318` | **`+0x2d8`** |
| `__TEXT.__objc_methlist` | `0x8420` | `0x8628` | **`+0x208`** |
| `__DATA_CONST.__objc_selrefs` | `0x5180` | `0x5328` | **`+0x1a8`** |
| `__AUTH_CONST.__objc_const` | `0xc9d0` | `0xcb60` | **`+0x190`** |
| `__AUTH_CONST.__objc_dictobj` | `0x208` | `0x118` | **`-0xf0`** |
| `__DATA_CONST.__objc_arraydata` | `0x1e8` | `0xf8` | **`-0xf0`** |
| `__AUTH_CONST.__cfstring` | `0x1c180` | `0x1c220` | **`+0xa0`** |
| `__AUTH_CONST.__objc_intobj` | `0x348` | `0x2d0` | **`-0x78`** |
| `__DATA_CONST.__const` | `0x7270` | `0x72d8` | **`+0x68`** |
| `__AUTH_CONST.__const` | `0x4888` | `0x48c8` | **`+0x40`** |
| `__TEXT.__const` | `0x1ca8` | `0x1cd8` | **`+0x30`** |
| `__DATA.__bss` | `0x1270` | `0x1298` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0xc1c` | `0xc40` | **`+0x24`** |
| `__DATA_CONST.__got` | `0xc20` | `0xc40` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x90` | `0x78` | **`-0x18`** |
| `__DATA.__common` | `0x678` | `0x680` | **`+0x8`** |
| `__DATA.__data` | `0x13f8` | `0x1400` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0xd90` | `0xd98` | **`+0x8`** |

### Other Changes

```diff

-360.58.1.0.0
+360.63.1.11.2

-  Functions: 11363
-  Symbols:   13541
-  CStrings:  13980
+  Functions: 11510
+  Symbols:   13648
+  CStrings:  14129
Symbols:
+ +[MDENetworkPolicyEngine newDefaultLANPolicy:]
+ +[MDENetworkPolicyEngine newPermissiveLANPolicy:]
+ +[MDENetworkPolicyEngine newPolicyFromCEndpoint:forProcess:]
+ +[MDENetworkPolicyEngine newPolicyWithNetworkCondition:process:order:result:restrictedTo:]
+ +[MDENetworkPolicyEngine newWANPolicy:restrictedTo:]
+ +[MXFrontBoardServices BLSBacklightStateToMXScreenState:]
+ -[AVSystemController setCameraAttributionInformation:]
+ -[MDENetworkPolicyAssertion lanPolicyID]
+ -[MDENetworkPolicyAssertion permissiveWANPolicyIDs]
+ -[MDENetworkPolicyAssertion receiverPolicyIDs]
+ -[MDENetworkPolicyAssertion setLanPolicyID:]
+ -[MDENetworkPolicyAssertion setPermissiveWANPolicyIDs:]
+ -[MDENetworkPolicyAssertion setReceiverPolicyIDs:]
+ -[MDENetworkPolicyAssertion setWanPolicyID:]
+ -[MDENetworkPolicyAssertion wanPolicyID]
+ -[MDENetworkPolicyEngine demoteAssertionFromPermissiveLANAccess:]
+ -[MDENetworkPolicyEngine newPermissiveWANPolicies:updatingAssertion:]
+ -[MDENetworkPolicyEngine promoteAssertion:toAccessNWEndpointsOverLAN:]
+ -[MDENetworkPolicyEngine promoteAssertionToPermissiveLANAccess:]
+ -[MDENetworkPolicyEngine revokeAssertions:accessToNWEndpointsOverLAN:]
+ -[MDENetworkPolicyEngine updateAssertion:withNewPolicy:oldPolicyID:]
+ -[MXCoreSessionBase getPreferredIOBufferFramesPointer]
+ -[MXCoreSessionBase preferredIOBufferDuration]
+ -[MXCoreSessionBase preferredIOBufferFrames]
+ -[MXCoreSessionBase preferredInputSampleRate]
+ -[MXCoreSessionBase preferredNumberOfInputChannels]
+ -[MXCoreSessionBase preferredNumberOfOutputChannels]
+ -[MXCoreSessionBase setPreferredIOBufferDuration:]
+ -[MXCoreSessionBase setPreferredIOBufferFrames:]
+ -[MXCoreSessionBase setPreferredInputSampleRate:]
+ -[MXCoreSessionBase setPreferredNumberOfInputChannels:]
+ -[MXCoreSessionBase setPreferredNumberOfOutputChannels:]
+ -[MXCoreSessionBase updatePreferredIOBufferDuration:]
+ -[MXCoreSessionBase updatePreferredIOBufferFrames:]
+ -[MXCoreSessionIndependentInputAudioResource populateAdditiveRoutingInfoWithOnDemandVADMetadata:]
+ -[MXCoreSessionIndependentInputAudioResource prefersLowPowerMicrophone]
+ -[MXCoreSessionIndependentInputAudioResource setPrefersLowPowerMicrophone:]
+ -[MXCoreSessionIndependentInputAudioResource setSampleRateAndBufferSizeOnVA]
+ -[MXCustomEndpointCache cascadeEmptyEntriesForNetwork:protocol:]
+ -[MXCustomEndpointCache devicesDictForNetwork:protocol:]
+ -[MXCustomEndpointCache evictStalestEntryFromDict:skipKey:]
+ -[MXCustomEndpointCache evictTTLEntriesFromDict:now:skipKey:]
+ -[MXCustomEndpointCache getOrCreateProtocolsDictForNetwork:]
+ -[MXCustomEndpointCache handleNetworkChange]
+ -[MXCustomEndpointCache handleUserDefaultsSizeLimitExceeded:]
+ -[MXCustomEndpointCache maxCacheDataSize]
+ -[MXCustomEndpointCache protocolsDictForNetwork:]
+ -[MXCustomEndpointCache recomputeLastSeenForEntry:fromChildren:]
+ -[MXCustomEndpointCache setMaxCacheDataSize:]
+ -[MXDeviceResolver _rebuildBonjourIndex]
+ -[MXDeviceResolver _scheduleBonjourIndexRebuild]
+ -[MXDeviceResolver resolutionForBonjourEndpoint:]
+ -[MXEndpointDescriptorCache deviceResolver]
+ -[MXFrontBoardServices dealloc]
+ -[MXFrontBoardServices updateLayoutScreenState:]
+ -[MXResolvedEndpoint ipv6String]
+ -[MXResolvedEndpoint setIpv6String:]
+ -[MXSessionManager cameraAttributionInformation]
+ -[MXSessionManager setCameraAttributionInformation:]
+ -[MXSessionManager(CameraAttributionInformationUtilities) copyInUseCameraInformationForActiveRecordingSessions]
+ -[MXSessionManager(CameraAttributionInformationUtilities) copyTranslatedCameraInfoDictionary:]
+ -[MXSessionManager(CameraAttributionInformationUtilities) isActiveInputSessionMatchingDisplayIDActiveOnDefaultVAD:]
+ -[MXSessionManager(CameraAttributionInformationUtilities) updateCameraAttributionInformation:]
+ -[MXSessionManager(CameraAttributionInformationUtilities) validateCameraInfo:]
+ -[MXSessionManager(Utilities) isCarPlayMainAudioBorrowedForVideoPlayback]
+ -[MXSessionManager(Utilities) isCarPlayVideoPlaybackBorrowActive]
+ -[MXSessionManager(Utilities) isSomeClientPlayingTo3PEndpoint]
+ -[MXSessionManager(Utilities) updateBufferSizeOnSystemLocalVADIfNeeded:]
+ -[MXSystemCastingExtensionInstance activateDeviceWithDescription:withNWEndpoints:isMirroring:completionHandler:]
+ -[MXSystemCastingExtensionInstance deactivateDeviceWithDescription:withNWEndpoints:completionHandler:]
+ -[MXSystemController applyCameraAttributionInformation:]
+ -[MXSystemMediaCastingController_Client notifyScreenCaptureStateChanged:]
+ GCC_except_table102
+ GCC_except_table107
+ GCC_except_table110
+ GCC_except_table111
+ GCC_except_table144
+ GCC_except_table33
+ GCC_except_table63
+ GCC_except_table94
+ GCC_except_table98
+ _CCHmac
+ _CMSMDeviceState_UpdateScreenIsBlanked
+ _CMSMDeviceState_UpdateScreenIsBlanked.sScreenStateInitialized
+ _CMSMMDE_HandleIdleEvent
+ _CMSMMDE_HandleScreenCaptureStateChanged
+ _CMSMMDE_StartDisconnectMDEDeviceTimer
+ _CMSMMDE_StopDisconnectMDEDeviceTimer
+ _CMSMVAUtility_SetMicrophoneAttributionForAuditToken
+ _FigEndpointCentralIsMainAudioBorrowedForVideoPlayback
+ _FigEndpointCentralIsVideoPlaybackBorrowActive
+ _FigEndpointUIAgentHelper_CleanupPromptWithReason
+ _FigStarkModeControllerGetAndClearVideoPlaybackBorrowerPreempted
+ _FigStarkModeControllerGetAndClearVideoPlaybackBorrowerRestored
+ _MXDeviceSubTypeFromModelIDForCustomProtocolDevice
+ _MXMDECacheHashNetworkBSSID
+ _NSUserDefaultsSizeLimitExceededNotification
+ _OBJC_CLASS_$_NSPropertyListSerialization
+ _OBJC_CLASS_$_NWEndpoint
+ _OBJC_IVAR_$_MDENetworkPolicyAssertion._lanPolicyID
+ _OBJC_IVAR_$_MDENetworkPolicyAssertion._permissiveWANPolicyIDs
+ _OBJC_IVAR_$_MDENetworkPolicyAssertion._receiverPolicyIDs
+ _OBJC_IVAR_$_MDENetworkPolicyAssertion._wanPolicyID
+ _OBJC_IVAR_$_MXCoreSessionBase._preferredIOBufferDuration
+ _OBJC_IVAR_$_MXCoreSessionBase._preferredIOBufferFrames
+ _OBJC_IVAR_$_MXCoreSessionBase._preferredInputSampleRate
+ _OBJC_IVAR_$_MXCoreSessionBase._preferredNumberOfInputChannels
+ _OBJC_IVAR_$_MXCoreSessionBase._preferredNumberOfOutputChannels
+ _OBJC_IVAR_$_MXCoreSessionIndependentInputAudioResource._prefersLowPowerMicrophone
+ _OBJC_IVAR_$_MXCustomEndpointCache._maxCacheDataSize
+ _OBJC_IVAR_$_MXDeviceResolver._bonjourIndex
+ _OBJC_IVAR_$_MXDeviceResolver._bonjourIndexLock
+ _OBJC_IVAR_$_MXDeviceResolver._bonjourIndexRebuildPending
+ _OBJC_IVAR_$_MXResolvedEndpoint._ipv6String
+ _OBJC_IVAR_$_MXSessionManager._cameraAttributionInformation
+ _SipHash
+ __OBJC_$_INSTANCE_METHODS_MXSessionManager(InterruptionActionMapper|DuckingUtilities|CameraAttributionInformationUtilities|MXSessionManagerContinuityScreenOutputPortUtilities|PickableRoutes|Common|VAUtilities|OnHeadBluetoothAccessoryPortUtilities|Utilities|ActivationUtilities)
+ __OBJC_$_PROP_LIST_MXCoreSessionIndependentInputAudioResource
+ __ZNSt12length_errorC1B9fqe220106EPKc
+ __ZNSt3__120__throw_length_errorB9fqe220106EPKc
+ __ZNSt3__16vectorI11VARouteInfoNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__16vectorI12CMSRouteInfoNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220106Ev
+ __ZNSt3__19allocatorI11VARouteInfoE17allocate_at_leastB9fqe220106Em
+ __ZNSt3__19allocatorI12CMSRouteInfoE17allocate_at_leastB9fqe220106Em
+ __ZSt28__throw_bad_array_new_lengthB9fqe220106v
+ ___102-[MXSystemCastingExtensionInstance deactivateDeviceWithDescription:withNWEndpoints:completionHandler:]_block_invoke
+ ___112-[MXSystemCastingExtensionInstance activateDeviceWithDescription:withNWEndpoints:isMirroring:completionHandler:]_block_invoke
+ ___48-[MXDeviceResolver _scheduleBonjourIndexRebuild]_block_invoke
+ ___61-[MXCustomEndpointCache handleUserDefaultsSizeLimitExceeded:]_block_invoke
+ ___CMSMMDE_HandleScreenCaptureStateChanged_block_invoke
+ ___CMSMMDE_StartDisconnectMDEDeviceTimer_block_invoke
+ ___FigEndpointCentralIsMainAudioBorrowedForVideoPlayback_block_invoke
+ ___FigEndpointCentralIsVideoPlaybackBorrowActive_block_invoke
+ ___FigRouteDiscoveryManagerAddAWDLDiscoveryClient_block_invoke
+ ___FigRouteDiscoveryManagerRefreshAWDLDiscoveryClient_block_invoke
+ ___FigRouteDiscoveryManagerRemoveAWDLDiscoveryClient_block_invoke
+ ___customEndpoint_cancelActivation_block_invoke
+ ___customEndpoint_handleActivationCompletionCallback_block_invoke
+ ___discoveryManager_getAWDLWorkQueue_block_invoke
+ __central_isVideoPlaybackBorrowIDMatch
+ _arc4random_buf
+ _cmsmmde_Is3PMirroringActive
+ _fsm_isCurrentBorrowerVideoPlayback
+ _gScreenCaptureState
+ _kAVSystemControllerCameraAttributionInformation_CameraDeviceType
+ _kAVSystemControllerCameraAttributionInformation_HostProcessAuditToken
+ _kFigEndpointAuthorizationType_None
+ _kFigStarkModeBorrowerDetails_BorrowID_AirPlayVideo
+ _kFigStarkModeBorrowerDetails_BorrowID_VideoPlayback
+ _kFigSystemControllerProperty_CameraAttributionInformation
+ _kMXCustomEndpointProperty_ShouldCache
+ _kMXSessionProperty_PrefersLowPowerMicrophone
+ _kMXSessionReporterIDLog_InterruptedSessionInfo
+ _kMXSessionVolumeChangeLog_CalculatedSynchronizedVolume
+ _kMXSystemControllerProperty_CameraAttributionInformation
+ _kMXSystemController_CameraAttributionInformation_CameraDeviceType
+ _kMXSystemController_CameraAttributionInformation_HostProcessAuditToken
+ _kMXSystemMediaCastingControllerMsgParam_ScreenCaptureState
+ _kVirtualAudioDeviceCameraType_CFString
+ _kVirtualAudioPlugInSessionDescriptionOnDemandVADPrefersLPMicKey_CFString
+ _manager_removeNonActivatedEndpoints
+ _sandbox_extension_issue_mach_to_process
+ _updateBufferSizeOnSystemLocalVADIfNeeded:.sLastSetBufferSize
+ _vaemSendInUseCameraInformationToVA
+ _vaemUpdateLongPullModeIfNeeded
- +[MDENetworkPolicyEngine allocDefaultLANPolicies:]
- +[MDENetworkPolicyEngine allocLANPolicies:order:result:]
- +[MDENetworkPolicyEngine allocPermissiveLANPolicies:]
- +[MDENetworkPolicyEngine allocRestrictedWANPolicies:restrictedTo:]
- +[MDENetworkPolicyEngine newPermissiveWANPolicy:]
- +[MDENetworkPolicyEngine newPolicyWithNetworkCondition:process:order:result:]
- -[MDENetworkPolicyAssertion lanPolicyIDs]
- -[MDENetworkPolicyAssertion setLanPolicyIDs:]
- -[MDENetworkPolicyAssertion setWanPolicyIDs:]
- -[MDENetworkPolicyAssertion wanPolicyIDs]
- -[MDENetworkPolicyEngine allocPolicyIDsByAddingPolicies:]
- -[MDENetworkPolicyEngine promoteAssertionToLANAccess:]
- -[MDENetworkPolicyEngine promoteAssertionToWANAccess:]
- -[MDENetworkPolicyEngine promoteAssertionToWanAccessWithPolicies:assertion:]
- -[MDENetworkPolicyEngine removePoliciesWithIDs:]
- -[MXCoreSession getPreferredIOBufferFramesPointer]
- -[MXCoreSession preferredIOBufferDuration]
- -[MXCoreSession preferredIOBufferFrames]
- -[MXCoreSession preferredInputSampleRate]
- -[MXCoreSession preferredNumberOfInputChannels]
- -[MXCoreSession preferredNumberOfOutputChannels]
- -[MXCoreSession setPreferredIOBufferDuration:]
- -[MXCoreSession setPreferredIOBufferFrames:]
- -[MXCoreSession setPreferredInputSampleRate:]
- -[MXCoreSession setPreferredNumberOfInputChannels:]
- -[MXCoreSession setPreferredNumberOfOutputChannels:]
- -[MXCoreSession updatePreferredIOBufferDuration:]
- -[MXCoreSession updatePreferredIOBufferFrames:]
- -[MXCustomEndpointCache handleNetworkChange:]
- -[MXCustomEndpointCache setTtl:]
- -[MXSystemCastingExtensionInstance activateDeviceWithDescription:completionHandler:isMirroring:]
- -[MXSystemCastingExtensionInstance deactivateDeviceWithDescription:completionHandler:]
- GCC_except_table113
- GCC_except_table142
- _OBJC_IVAR_$_MDENetworkPolicyAssertion._lanPolicyIDs
- _OBJC_IVAR_$_MDENetworkPolicyAssertion._wanPolicyIDs
- _OBJC_IVAR_$_MXCoreSession._preferredIOBufferDuration
- _OBJC_IVAR_$_MXCoreSession._preferredIOBufferFrames
- _OBJC_IVAR_$_MXCoreSession._preferredInputSampleRate
- _OBJC_IVAR_$_MXCoreSession._preferredNumberOfInputChannels
- _OBJC_IVAR_$_MXCoreSession._preferredNumberOfOutputChannels
- _OUTLINED_FUNCTION_423
- __OBJC_$_INSTANCE_METHODS_MXSessionManager(InterruptionActionMapper|DuckingUtilities|MXSessionManagerContinuityScreenOutputPortUtilities|PickableRoutes|Common|VAUtilities|OnHeadBluetoothAccessoryPortUtilities|Utilities|ActivationUtilities)
- __ZNSt12length_errorC1B9fqe220100EPKc
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorI11VARouteInfoEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__119__allocate_at_leastB9fqe220100INS_9allocatorI12CMSRouteInfoEENS_16allocator_traitsIS3_EEEENS_19__allocation_resultINT0_7pointerENS7_9size_typeEEERT_m
- __ZNSt3__120__throw_length_errorB9fqe220100EPKc
- __ZNSt3__16vectorI11VARouteInfoNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZNSt3__16vectorI12CMSRouteInfoNS_9allocatorIS1_EEE20__throw_length_errorB9fqe220100Ev
- __ZSt28__throw_bad_array_new_lengthB9fqe220100v
- ___86-[MXSystemCastingExtensionInstance deactivateDeviceWithDescription:completionHandler:]_block_invoke
- ___96-[MXSystemCastingExtensionInstance activateDeviceWithDescription:completionHandler:isMirroring:]_block_invoke
- ___cmsmdevicestate_RegisterForScreenIsBlankedNotification_block_invoke
- ___customEndpoint_Activate_block_invoke_2
- _cmsmdevicestate_ScreenIsBlanked
- _figEndpointDescriptorUtility_setNetworkEndpointsFromAirPlayProperties
- _kMXSessionReporterIDLog_InterruptedBundleIDs
- _xpc_copy_entitlement_for_self
CStrings:
+ "%016llx"
+ "%02x"
+ "+[MDENetworkPolicyEngine newDefaultLANPolicy:]"
+ "+[MDENetworkPolicyEngine newPermissiveLANPolicy:]"
+ "+[MDENetworkPolicyEngine newPolicyFromCEndpoint:forProcess:]"
+ "+[MDENetworkPolicyEngine newPolicyWithNetworkCondition:process:order:result:restrictedTo:]"
+ "+[MDENetworkPolicyEngine newWANPolicy:restrictedTo:]"
+ "-CMSMDevState- %s: Initial screenIsBlanked state: %{BOOL}u"
+ "-CMSMDevState- %s: redundant update"
+ "-CMSUtilities- %s: Not interrupting %{public}@, as CarSession is going active for AirPlay Video and mainAudio is borrowed for VideoPlayback"
+ "-CMSessionMgr- %s: Client VoiceOver and victim RingtonePreview/Alarm; not taking any flags; just mixing in."
+ "-CMSessionMgr_MDE- %s: Disconnecting MDE device - idle."
+ "-CMSessionMgr_MDE- %s: MDE idle timer fired: screenIsBlanked = %{public}s, isSomeClientPlayingTo3PEndpoint = %{public}s, extensionIsMirroring = %{public}s"
+ "-CMSessionMgr_MDE- %s: Screen capture state changed: %{public}u"
+ "-CMSessionMgr_MDE- %s: creating gCMSM.disconnectMDEDeviceTimer, timer delay = %{public}f"
+ "-CMSessionMgr_MDE- %s: releasing gCMSM.disconnectMDEDeviceTimer"
+ "-CMSessionMgr_MDE- %s: screenIsBlanked = %{public}s, isSomeClientPlayingTo3PEndpoint = %{public}s, extensionIsMirroring = %{public}s, shouldStartTimer = %{public}s"
+ "-CMVAEndptMgr- %s: Attempting to send %{public}@ active camera info to VA"
+ "-CMVAEndptUtl- %s: Error setting kVirtualAudioPlugInPropertyMicrophoneAttribution, err = '%c%c%c%c'"
+ "-CMVAEndptUtl- %s: Setting kVirtualAudioPlugInPropertyMicrophoneAttribution on VA with attributedBundleID:%{public}@"
+ "-FigCustomEndpoint- %s: %{public}s: deactivate completed result=%{private}@"
+ "-FigCustomEndpoint- %s: %{public}s: skipping cancelActivation — endpoint is not activating"
+ "-FigCustomEndpoint- %s: FigCustomEndpointAuthorizationRequested: dropping — auth was cancelled by user, endpoint=%{private}@"
+ "-FigCustomEndpointManager- %s: Removing endpoint %{private}@ from endpointIDToEndpointMap (shouldCache=false)"
+ "-FigCustomEndpointManager- %s: [%p] Cancelling respawn of extension"
+ "-FigCustomEndpointManager- %s: [%p] Cancelling respawn timer"
+ "-FigRouteDiscoveryManager- %s: AWDLServiceDiscoveryManager does not respond to addAWDLDiscoveryClient:forService:error:"
+ "-FigRouteDiscoveryManager- %s: clientName is NULL, nothing to add"
+ "-FigRouteDiscoveryManager- %s: clientName is NULL, nothing to remove"
+ "-MDENetworkPolicyEngine- %s: Failed to remove policy %{public}@ for UUID %{public}@"
+ "-MDENetworkPolicyEngine- %s: Failed when applying new policies!"
+ "-MDENetworkPolicyEngine- %s: Got unhandled endpointType of %u"
+ "-MDENetworkPolicyEngine- %s: Rollback: failed to apply policy session after removing orphan permissive WAN policies"
+ "-MDENetworkPolicyEngine- %s: Rollback: failed to apply policy session after removing orphan policies"
+ "-MDENetworkPolicyEngine- %s: Rollback: failed to remove orphan permissive WAN policy %{public}@"
+ "-MDENetworkPolicyEngine- %s: Rollback: failed to remove orphan policy %{public}@ for UUID %{public}@"
+ "-MDENetworkPolicyEngine- %s: Successfully promoted %{public}@ to permissive LAN"
+ "-MDENetworkPolicyEngine- %s: Successfully promoted assertion %{public}@ to WAN access with %lu domains"
+ "-MDENetworkPolicyEngine- %s: Unhandled address family type, %lu"
+ "-MXCoreSessionIndependentInputAudioResource- %s: Client %{public}@ [%p] setting %{public}@ to %{public}@"
+ "-MXCoreSessionIndependentInputAudioResource- %s: Client '%{public}@' setting buffer duration as %.3f"
+ "-MXCoreSessionIndependentInputAudioResource- %s: Client '%{public}@' setting buffer frames as %d"
+ "-MXCoreSessionIndependentInputAudioResource- %s: Independent input session %{public}@ is not routed to on-demand VAD, skip setting sample rate and buffer size"
+ "-MXCustomEndpointCache- %s: All devices evicted for protocol '%{public}@'; removing protocol entry"
+ "-MXCustomEndpointCache- %s: All devices expired for protocol '%{public}@'; removing protocol entry"
+ "-MXCustomEndpointCache- %s: All protocols evicted for network '%{private}@'; removing network entry"
+ "-MXCustomEndpointCache- %s: All protocols expired for network '%{private}@'; removing network entry"
+ "-MXCustomEndpointCache- %s: Cache still exceeds size limit after eviction attempts -- clearing"
+ "-MXCustomEndpointCache- %s: Corrupt cache on disk -- clearing"
+ "-MXCustomEndpointCache- %s: Failed to deserialize cache data: %{public}@"
+ "-MXCustomEndpointCache- %s: Failed to serialize cache: %{public}@"
+ "-MXCustomEndpointCache- %s: Initialized with ttl=%.1fs maxCacheDataSize=%lu"
+ "-MXCustomEndpointCache- %s: Invalid devices dict on disk -- clearing cache"
+ "-MXCustomEndpointCache- %s: Invalid network entry on disk -- clearing cache"
+ "-MXCustomEndpointCache- %s: Invalid network lastSeen on disk -- clearing cache"
+ "-MXCustomEndpointCache- %s: Invalid protocol entry on disk -- clearing cache"
+ "-MXCustomEndpointCache- %s: Invalid protocol lastSeen on disk -- clearing cache"
+ "-MXCustomEndpointCache- %s: Invalid protocols dict on disk -- clearing cache"
+ "-MXCustomEndpointCache- %s: NSUserDefaults size limit exceeded -- clearing entire MXCustomEndpointCache"
+ "-MXCustomEndpointCache- %s: Network changed: old='%{private}@' new='%{private}@'"
+ "-MXCustomEndpointCache- %s: Saved %lu endpoints to cache for network '%{private}@' protocol '%{public}@' (%lu provided)"
+ "-MXCustomEndpointCache- %s: Serialized cache size %lu exceeds limit %lu -- evicting stalest network (attempt %ld/%ld)"
+ "-MXCustomEndpointCache- %s: Size evicting '%{private}@' (lastSeen=%.1f)"
+ "-MXCustomEndpointCache- %s: Skipping cache save - no current network"
+ "-MXCustomEndpointCache- %s: TTL evicting '%{private}@' (lastSeen=%.1f, age=%.1fs)"
+ "-MXCustomEndpointCache- %s: Wrote %lu entries to disk (%lu bytes)"
+ "-MXDeviceResolver-"
+ "-MXDeviceResolver- %s: MXDeviceResolver: _resolveEndpoint — already have IP literal (ipv4: %{public}@, ipv6: %{public}@), returning early"
+ "-MXDeviceResolver- %s: MXDeviceResolver: _resolveEndpoint — deviceID: %{public}@, protocolType: %{public}@, bonjourName: %{public}@, bonjourServiceType: %{public}@, bonjourDomain: %{public}@, bonjourFullName: %{public}@, bonjourHostname: %{public}@, hostname: %{public}@, ipv4String: %{public}@, ipv6String: %{public}@, port: %u"
+ "-MXEndpointDescriptorCache- %s: endpoint or descriptor is NULL"
+ "-MXSessionManagerCameraAttributionInformationUtilities- %s: Audit token is not NSData"
+ "-MXSessionManagerCameraAttributionInformationUtilities- %s: Camera attribution info changed:"
+ "-MXSessionManagerCameraAttributionInformationUtilities- %s: Failed to copy displayID for pid %d"
+ "-MXSessionManagerCameraAttributionInformationUtilities- %s: Invalid audit token provided"
+ "-MXSessionManagerCameraAttributionInformationUtilities- %s: Missing required parameters in camera info dictionary"
+ "-MXSessionManagerCameraAttributionInformationUtilities- %s: No camera info in dictionary to translate"
+ "-MXSessionManagerCameraAttributionInformationUtilities- %s: No camera info passed to method"
+ "-MXSessionManagerUtilities- %s: %{public}@  is setting buffer size to %d frames on the System Local VAD"
+ "-MXSessionManagerUtilities- %s: No qualifying session on vsyl, resetting buffer size to default"
+ "-MXSystemController- %s: Applying camera attribution information"
+ "-MXSystemController- %s: Invalid entry in camera attribution info array"
+ "-MXSystemMediaCastingController_Client- %s: Failed to notify capture state changed, err: %{public}d"
+ "-MXSystemMediaCastingController_Server- %s: Received screen capture state changed: %{public}u"
+ "-MXVolumeClient- %s: MXDeviceSubTypeFromModelIDForCustomProtocolDevice: unrecognized modelID='%{public}@'"
+ "-MXVolumeClient- %s: populateDeviceTypeAndSubType: endpoint=%p is nil or not 3P casting type for MediaDeviceExtension route, setting routeSubtype to Standard"
+ "-MXVolumeClient- %s: populateDeviceTypeAndSubType: port=%u route=%{public}@ -> routeType=%ld routeSubtype=%ld routeName=%{public}@"
+ "-MX_FrontBoardServices- %s: Nil FBSDisplayLayout"
+ "-MX_FrontBoardServices- %s: Nil displayConfiguration identity, skip update"
+ "-MX_FrontBoardServices- %s: Unknown screen state, skip update"
+ "-MX_FrontBoardServices- %s: screenIsBlanked == %{BOOL}u"
+ "-[AVSystemController setCameraAttributionInformation:]"
+ "-[MDENetworkPolicyEngine demoteAssertionFromPermissiveLANAccess:]"
+ "-[MDENetworkPolicyEngine newPermissiveWANPolicies:updatingAssertion:]"
+ "-[MDENetworkPolicyEngine promoteAssertion:toAccessNWEndpointsOverLAN:]"
+ "-[MDENetworkPolicyEngine promoteAssertionToPermissiveLANAccess:]"
+ "-[MDENetworkPolicyEngine revokeAssertions:accessToNWEndpointsOverLAN:]"
+ "-[MDENetworkPolicyEngine updateAssertion:withNewPolicy:oldPolicyID:]"
+ "-[MXCoreSessionIndependentInputAudioResource setSampleRateAndBufferSizeOnVA]"
+ "-[MXCustomEndpointCache cascadeEmptyEntriesForNetwork:protocol:]"
+ "-[MXCustomEndpointCache evictStalestEntryFromDict:skipKey:]"
+ "-[MXCustomEndpointCache evictTTLEntriesFromDict:now:skipKey:]"
+ "-[MXCustomEndpointCache handleNetworkChange]"
+ "-[MXCustomEndpointCache handleUserDefaultsSizeLimitExceeded:]"
+ "-[MXDeviceResolver _scheduleBonjourIndexRebuild]"
+ "-[MXDeviceResolver removeRouteDescriptors:]"
+ "-[MXDeviceResolver resolutionForBonjourEndpoint:]"
+ "-[MXDeviceResolver updateWithRouteDescriptors:]"
+ "-[MXFrontBoardServices updateLayoutScreenState:]"
+ "-[MXSessionManager(CameraAttributionInformationUtilities) copyInUseCameraInformationForActiveRecordingSessions]"
+ "-[MXSessionManager(CameraAttributionInformationUtilities) copyTranslatedCameraInfoDictionary:]"
+ "-[MXSessionManager(CameraAttributionInformationUtilities) updateCameraAttributionInformation:]"
+ "-[MXSessionManager(CameraAttributionInformationUtilities) validateCameraInfo:]"
+ "-[MXSessionManager(Utilities) updateBufferSizeOnSystemLocalVADIfNeeded:]"
+ "-[MXSystemCastingExtensionInstance activateDeviceWithDescription:withNWEndpoints:isMirroring:completionHandler:]"
+ "-[MXSystemCastingExtensionInstance activateDeviceWithDescription:withNWEndpoints:isMirroring:completionHandler:]_block_invoke"
+ "-[MXSystemCastingExtensionInstance deactivateDeviceWithDescription:withNWEndpoints:completionHandler:]"
+ "-[MXSystemCastingExtensionInstance deactivateDeviceWithDescription:withNWEndpoints:completionHandler:]_block_invoke"
+ "-[MXSystemController applyCameraAttributionInformation:]"
+ "-[MXSystemMediaCastingController_Client notifyScreenCaptureStateChanged:]"
+ "-endpoint_central- %s: FigEndpointCentralIsMainAudioBorrowedForVideoPlayback = %s"
+ "-endpoint_central- %s: FigEndpointCentralIsVideoPlaybackBorrowActive = %s"
+ "-endpoint_central- %s: Stark mode change action is InterruptCarPlayVideoSession"
+ "-endpoint_central- %s: Stark mode change action is ResumeCarPlayVideoSession"
+ "-endpoint_central- %s: VideoPlayback borrower preempted on mainAudio - will interrupt CarPlay video session"
+ "-endpoint_central- %s: VideoPlayback borrower restored on mainAudio - will resume CarPlay video session"
+ "-endpoint_central- %s: starkModeController is NULL"
+ "21:51:30"
+ "<%@: %p deviceID=%@ bonjour=%@ hostname=%@ ipv4=%@ ipv6=%@ port=%u>"
+ "CMSMDeviceState_UpdateScreenIsBlanked"
+ "CMSMMDE_HandleIdleEvent"
+ "CMSMMDE_HandleScreenCaptureStateChanged"
+ "CMSMMDE_StartDisconnectMDEDeviceTimer"
+ "CMSMMDE_StopDisconnectMDEDeviceTimer"
+ "CMSMVAUtility_SetMicrophoneAttributionForAuditToken"
+ "CMSessionManager_MDE.m"
+ "CalculatedSynchronizedVolume"
+ "CameraAttributionInformation"
+ "CameraDeviceType"
+ "Endpoint provided not of bonjour type"
+ "Failed to add default WAN policy"
+ "Failed to alloc array for policies"
+ "Failed to allocate addedPolicyIDs"
+ "Failed to allocate iterCondition"
+ "Failed to allocate iterConditions"
+ "Failed to allocate policies array"
+ "Failed to allocate policy"
+ "Failed to apply LAN policy"
+ "Failed to apply default WAN policy"
+ "Failed to apply per-endpoint LAN policies"
+ "Failed to apply per-endpoint LAN revocation"
+ "Failed to build policy for endpoint"
+ "Failed to construct full name from DNSService"
+ "Failed to create any policies"
+ "Failed to find a resolved endpoint"
+ "Failed to get NSString representation of the URL"
+ "Failed to get NWAddressEndoint from cEndpoint"
+ "Failed to get a policy ID"
+ "Failed to get a policyID back"
+ "Failed to get a restrictive policy"
+ "Failed to get an NWAddressEndpoint back"
+ "Failed to get condition"
+ "Failed to get either IPV4 or IPV6 policy for bonjour based endpoint"
+ "Failed to get endpoint from cEndpoint"
+ "Failed to get lanPolicy"
+ "Failed to get new WAN policy"
+ "Failed to get new lanPolicyID"
+ "Failed to get new policy ID from policy session"
+ "Failed to get new policyID"
+ "Failed to get policies array"
+ "Failed to get port string"
+ "Failed to get the extension token, rejecting discovery start"
+ "Failed to get updated LAN policy"
+ "Failed to get wanPolicyID"
+ "Failed to remove old policy"
+ "Failed to remove old policy ID"
+ "Failed to remove the previous restrictive WAN policy"
+ "Failed to roll back per-endpoint LAN policies; session has leaked policy IDs"
+ "Failed to roll back permissive WAN policies; session has leaked policy IDs"
+ "Failed to set CameraAttributionInformation"
+ "FigEndpointCentralIsMainAudioBorrowedForVideoPlayback"
+ "FigEndpointCentralIsVideoPlaybackBorrowActive"
+ "FigEndpointUIAgentHelper_CleanupPromptWithReason"
+ "FigRouteDiscoveryManagerAddAWDLDiscoveryClient_block_invoke"
+ "FigRouteDiscoveryManagerRefreshAWDLDiscoveryClient_block_invoke"
+ "FigRouteDiscoveryManagerRemoveAWDLDiscoveryClient_block_invoke"
+ "Got invalid pid from assertion's audit token"
+ "HostProcessAuditToken"
+ "InterruptedSessionInfo"
+ "Invalid capture state value"
+ "Invalid platform to call SPI"
+ "Jun 16 2026"
+ "MXDeviceResolver.m"
+ "MXDeviceSubTypeFromModelIDForCustomProtocolDevice"
+ "MXEndpointDescriptorCacheSetDescriptorKey"
+ "MXSystemMediaCastingController_NotifyScreenCaptureStateChanged"
+ "MX_NWEndpoint doesn't have a domain"
+ "MX_NWEndpoint doesn't have a name"
+ "MX_NWEndpoint doesn't have a serviceType"
+ "No UUID"
+ "No assertion provided"
+ "No endpoint"
+ "No endpoint provided"
+ "No new policies provided"
+ "No new policy provided"
+ "No nwEndpoint provided"
+ "No prefix provided"
+ "No process condition provided"
+ "PreferredNumberOfInputChannelss can't be < 0"
+ "PrefersLowPowerMicrophone"
+ "Resolved endpoint doesn't have a hostname"
+ "Resolved endpoint doesn't have a port"
+ "ScreenCaptureState"
+ "Unhandled address family type"
+ "Unhandled endpointType provided"
+ "_central_isMainAudioBorrowedForVideoPlayback"
+ "_central_isVideoPlaybackBorrowActive"
+ "auth-cancel"
+ "camera type"
+ "cmsmmde_DisconnectMDEDeviceIfIdle"
+ "com.apple.media-device-extension.bleDiscovery"
+ "com.apple.mediaexperience.AWDLDiscoveryWork"
+ "com.apple.server.bluetooth.le.att.xpc"
+ "correlationID %{public}@"
+ "correlationID: %{public}@"
+ "customEndpoint_cancelActivation"
+ "customEndpoint_cancelActivation_block_invoke"
+ "fullName couldn't be fetched"
+ "kMXCustomEndpointCacheInfo_deviceDescription"
+ "kMXCustomEndpointCacheInfo_isCached"
+ "kMXCustomEndpointCache_deviceInfo"
+ "kMXCustomEndpointCache_devices"
+ "kMXCustomEndpointCache_lastSeen"
+ "kMXCustomEndpointCache_protocols"
+ "manager_saveCache"
+ "non-number PreferredAudioHardwareIOBufferDuration"
+ "non-number PreferredAudioHardwareIOBufferFrames"
+ "non-number PreferredInputSampleRate"
+ "non-number PreferredNumberOfInputChannels"
+ "non-number prefersLowPowerMicrophone"
+ "nwEndpoints not provided"
+ "on-demand VAD prefers LP mic"
+ "replayd"
+ "resumable.videoPlaybackBorrowerRestored"
+ "shouldCache"
+ "vaemSendInUseCameraInformationToVA"
+ "\xf0\xf0\xf0\xf0\xb1"
- "+[MDENetworkPolicyEngine allocDefaultLANPolicies:]"
- "+[MDENetworkPolicyEngine allocLANPolicies:order:result:]"
- "+[MDENetworkPolicyEngine allocPermissiveLANPolicies:]"
- "+[MDENetworkPolicyEngine allocRestrictedWANPolicies:restrictedTo:]"
- "+[MDENetworkPolicyEngine newPermissiveWANPolicy:]"
- "+[MDENetworkPolicyEngine newPolicyWithNetworkCondition:process:order:result:]"
- "-CMSMDevState- %s: screenIsBlanked == %s"
- "-CMSUtilities- %s: Not interrupting %{public}@, as CarSession is going active for AirPlay Video"
- "-CMSessionMgr- %s: client VoiceOver and victim RingtonePreview; not taking any flags; just mixing in."
- "-MDENetworkPolicyEngine- %s: Failed to allocate %lu WAN policies, failing the init"
- "-MDENetworkPolicyEngine- %s: Failed to allocate %lu policies, failing the init"
- "-MDENetworkPolicyEngine- %s: Failed to allocate conditions for domain %{public}@"
- "-MDENetworkPolicyEngine- %s: Failed to allocate conditions for subnet %{public}@"
- "-MDENetworkPolicyEngine- %s: Failed to create condition for domain %{public}@"
- "-MDENetworkPolicyEngine- %s: Failed to create condition for subnet %{public}@"
- "-MDENetworkPolicyEngine- %s: Failed to create endpoint for subnet %{public}@"
- "-MDENetworkPolicyEngine- %s: Failed to create policy for domain %{public}@"
- "-MDENetworkPolicyEngine- %s: Failed to create policy for subnet %{public}@"
- "-MDENetworkPolicyEngine- %s: Failed to get subnet prefix for %{public}@"
- "-MXCustomEndpointCache- %s: Initialized with ttl=%.1fs"
- "-MXCustomEndpointCache- %s: Network changed from %{private}@ to %{private}@"
- "-MXCustomEndpointCache- %s: Saved %lu endpoints to cache for network '%{private}@' protocol '%{public}@'"
- "-MXCustomEndpointCache- %s: Skipping cache save - public network or no network"
- "-MXCustomEndpointCache- %s: Wrote %lu entries to disk"
- "-MXDeviceResolver- %s: MXDeviceResolver: _resolveEndpoint — already have ipv4String, returning early"
- "-MXDeviceResolver- %s: MXDeviceResolver: _resolveEndpoint — deviceID: %{public}@, protocolType: %{public}@, bonjourName: %{public}@, bonjourServiceType: %{public}@, bonjourDomain: %{public}@, bonjourFullName: %{public}@, bonjourHostname: %{public}@, hostname: %{public}@, ipv4String: %{public}@, port: %u"
- "-MXSystemMediaCasting- %s: Failed to demote %{public}@ from WAN access"
- "-MXSystemMediaCasting- %s: MDE Network policies disabled via defaults write!"
- "-MXSystemMediaCasting- %s: OSEligibility check has been disabled via defaults write!"
- "-MXSystemMediaCasting- %s: Will manage container deletion"
- "-MXSystemMediaCasting- %s: Will manage process termination"
- "-[MDENetworkPolicyEngine allocPolicyIDsByAddingPolicies:]"
- "-[MDENetworkPolicyEngine promoteAssertionToLANAccess:]"
- "-[MDENetworkPolicyEngine promoteAssertionToWANAccess:]"
- "-[MDENetworkPolicyEngine promoteAssertionToWanAccessWithPolicies:assertion:]"
- "-[MXCustomEndpointCache handleNetworkChange:]"
- "-[MXSystemCastingExtensionInstance activateDeviceWithDescription:completionHandler:isMirroring:]"
- "-[MXSystemCastingExtensionInstance activateDeviceWithDescription:completionHandler:isMirroring:]_block_invoke"
- "-[MXSystemCastingExtensionInstance deactivateDeviceWithDescription:completionHandler:]"
- "-[MXSystemCastingExtensionInstance deactivateDeviceWithDescription:completionHandler:]_block_invoke"
- "-[MXSystemCastingExtensionManager _configureManagementPolicies]"
- "10.0.0.0"
- "169.254.0.0"
- "172.16.0.0"
- "192.168.0.0"
- "23:32:14"
- "<%@: %p deviceID=%@ bonjour=%@ hostname=%@ ipv4=%@ port=%u>"
- "Didn't get assertion"
- "Didn't get new policies"
- "Failed to add LAN policies"
- "Failed to add LAN policies to session"
- "Failed to add WAN policies to session"
- "Failed to add WAN policy"
- "Failed to add WAN policy to session"
- "Failed to alloc default LAN policies"
- "Failed to alloc permissive LAN policies"
- "Failed to allocate LAN policies array"
- "Failed to allocate WAN policies array"
- "Failed to allocate policy IDs array"
- "Failed to allocate policy conditions"
- "Failed to apply WAN policies"
- "Failed to apply network policy"
- "Failed to apply new LAN policies"
- "Failed to apply new policies"
- "Failed to demote assertion from WAN access"
- "Failed to demote extensions network policy"
- "Failed to get WAN drop for restricted policies"
- "Failed to get a policy"
- "Failed to get lanPolicies"
- "Failed to get permissive WAN policy"
- "Failed to get updated LAN policies"
- "Failed to get updated WAN policies"
- "Failed to promote extension to WAN access"
- "Failed to promote network policy to permissive LAN"
- "Failed to remove old LAN policies"
- "Failed to remove old policies"
- "FigEndpointUIAgentHelper_CleanupPrompt"
- "InterruptedBundleIDs"
- "MXCustomEndpointCache_deviceDescription"
- "MXCustomEndpointCache_lastSeen"
- "May 22 2026"
- "addr"
- "cmsmdevicestate_ScreenIsBlanked"
- "cmsmdevicestate_ScreenIsBlankedChangedCallback"
- "com.apple.private.InstallCoordination.allowed"
- "com.apple.private.InstallCoordination.refreshContainerTypes"
- "com.apple.runningboard.terminateprocess"
- "com.apple.springboard.hasBlankedScreen"
- "correlationID %@"
- "correlationID: %@"
- "disableNetworkPolicies"
- "enableMDEEligibilityCheck"
- "fc00::"
- "fe80::"
- "isCached"
- "prefix"
- "\xf0\xf0\xf0\xf0\xe1"
```
