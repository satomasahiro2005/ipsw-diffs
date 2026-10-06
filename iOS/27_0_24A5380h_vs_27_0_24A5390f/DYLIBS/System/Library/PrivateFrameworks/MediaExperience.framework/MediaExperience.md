## MediaExperience

> `/System/Library/PrivateFrameworks/MediaExperience.framework/MediaExperience`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e8944` | `0x2ebccc` | **`+0x3388`** |
| `__TEXT.__oslogstring` | `0x782da` | `0x790b0` | **`+0xdd6`** |
| `__TEXT.__cstring` | `0x4e3ed` | `0x4e827` | **`+0x43a`** |
| `__TEXT.__gcc_except_tab` | `0x51a8` | `0x5248` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x8748` | `0x87e8` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x6370` | `0x6410` | **`+0xa0`** |
| `__AUTH_CONST.__cfstring` | `0x1c360` | `0x1c3e0` | **`+0x80`** |
| `__DATA_CONST.__objc_selrefs` | `0x53a8` | `0x5420` | **`+0x78`** |
| `__AUTH_CONST.__objc_const` | `0xce50` | `0xcec0` | **`+0x70`** |
| `__AUTH_CONST.__const` | `0x48e8` | `0x4908` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x7330` | `0x7350` | **`+0x20`** |
| `__TEXT.__const` | `0x1cd8` | `0x1cf8` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0xc64` | `0xc70` | **`+0xc`** |
| `__DATA.__bss` | `0x12b0` | `0x12b8` | **`+0x8`** |

### Other Changes

```diff

-360.66.1.11.1
+360.70.2.0.0

-  Functions: 11549
-  Symbols:   13712
-  CStrings:  14173
+  Functions: 11574
+  Symbols:   13753
+  CStrings:  14222
Symbols:
+ -[MXCustomRoutingController currentSystemMirroringRoutes]
+ -[MXCustomRoutingSession releasePlaybackAssertion]
+ -[MXCustomRoutingSession takePlaybackAssertion]
+ -[MXNowPlayingAppManager canCurrentCustomRoutingSessionBeNowPlaying]
+ -[MXNowPlayingAppManager currentCustomRoutingSession]
+ -[MXNowPlayingAppManager customRoutingSessionPlaybackStateDidChangeCallback:]
+ -[MXNowPlayingAppManager doesCurrentCustomRoutingSessionEligibleForNowPlayingMatchPID:]
+ -[MXNowPlayingAppManager isCurrentCustomRoutingSessionNowPlaying]
+ -[MXNowPlayingAppManager routingSessionControllerCurrentSessionDidChangeCallback:]
+ -[MXNowPlayingAppManager setCurrentCustomRoutingSession:]
+ -[MXNowPlayingAppManager updateCurrentCustomRoutingSession]
+ -[MXSessionManager(Utilities) isVolumeScalableCategory:]
+ -[MXSessionManager(Utilities) synchronizeSessionVolumeWithMediaVolumeIfNeeded:mediaWasPlaying:route:]
+ -[MXSessionManager(Utilities) tryToTakeControlFlagsOnDefaultVAD:routingFlagIsNotControlled:]
+ -[MXSessionResumptionContext copyActiveRoutesOnContextCreationIfAwaitingActivation]
+ -[MXSessionResumptionContext updateActiveRoutesOnContextCreationIfChangedAfterActivationForSession:previousActiveRoutes:]
+ -[MXSystemCastingExtensionInstance handleForSelf]
+ GCC_except_table145
+ GCC_except_table89
+ _CMSUtility_GetVolumeScalingFactorForCategory
+ _CMSUtility_GetVolumeScalingFactorForCategory.onceToken
+ _CMSUtility_GetVolumeScalingFactorForCategory.sAlarmScalingFactors
+ _CMSUtility_GetVolumeScalingFactorForCategory.sVoiceOverScalingFactors
+ _CMSystemSoundMgrGetMaxVoiceOverVolumeOnSystemLocalVAD
+ _CMSystemSoundMgrIsJBLSystemSoundPlayingOverSystemLocalVAD
+ _FigXPCCommonServerTimeoutHandler
+ _MXCustomRoutingSessionControllerCurrentSessionDidChangeNotification
+ _MX_CoreServices_CopyLocalizedApplicationName
+ _OBJC_IVAR_$_MXCustomRoutingController.mSystemMirroringContext
+ _OBJC_IVAR_$_MXCustomRoutingSession.mLock
+ _OBJC_IVAR_$_MXCustomRoutingSession.mPlaybackAssertion
+ _OBJC_IVAR_$_MXNowPlayingAppManager._currentCustomRoutingSession
+ _OBJC_IVAR_$_MXNowPlayingAppManager.mCustomRoutingSessionController
+ _PVMGetRawVolumeForRouteFromVolume
+ ___77-[MXNowPlayingAppManager customRoutingSessionPlaybackStateDidChangeCallback:]_block_invoke
+ ___82-[MXNowPlayingAppManager routingSessionControllerCurrentSessionDidChangeCallback:]_block_invoke
+ ___CMSUtility_GetVolumeScalingFactorForCategory_block_invoke
+ ___customEndpoint_timeoutActivationIfWaitingForPort_block_invoke
+ _figXPC_ServerTimeout_EndpointUIAgent
+ _figXPC_ServerTimeout_FigSTS
+ _figXPC_ServerTimeout_FigSystemController
+ _figXPC_ServerTimeout_FigVolumeClient
+ _figXPC_ServerTimeout_FigVolumeController
+ _figXPC_ServerTimeout_RouteDiscoverer
+ _figXPC_ServerTimeout_RoutingContext
+ _figXPC_ServerTimeout_RoutingSessionManager
+ _figXPC_ServerTimeout_StarkModeController
+ _figXPC_ServerTimeout_SystemMediaCastingController
+ _gMDEDeviceTimerPolicy
+ _kFigEndpointUIAgentPromptInfo_FailureDetails_MediaAppName
+ _kMXSessionAudioCategory_HomeDeviceHourlyChime
+ _sCarPlayVideoBannerUUID
+ _updateControlFlagsAfterRouteChange:systemLocalVADState:musicVADState:.sIsUpdatingControlFlagsAfterRouteChange
+ _vaemSuppressVolumeForwardingOnVAD
- -[MXSessionManager(Utilities) isVolumeScalableSession:]
- -[MXSessionManager(Utilities) synchronizeSessionVolumeWithMediaVolumeIfNeeded:]
- -[MXSessionManager(Utilities) tryToTakeControlFlagsOnDefaultVAD:]
- GCC_except_table144
- GCC_except_table80
- GCC_except_table86
- _OBJC_IVAR_$_MXSystemCastingExtensionInstance.mProcessHandle
- _OBJC_IVAR_$_MXSystemCastingExtensionManager.mProcessHandle
- _OUTLINED_FUNCTION_422
- ___cmsutility_getScalingFactorForSessionCategory_block_invoke
- _cmsutility_getScalingFactorForSessionCategory.onceToken
- _cmsutility_getScalingFactorForSessionCategory.sAlarmScalingFactors
- _cmsutility_getScalingFactorForSessionCategory.sVoiceOverScalingFactors
CStrings:
+ "-CMSM_CoreServices- %s: Failed to find a localized name for %{public}@"
+ "-CMSUtilities- %s: Mixable voice assistant session interrupting CarPlay video session '%@'"
+ "-CMSessionManager_NowPlaying- %s: Current NowPlaying app is based on custom routing session, appDisplayID: %{public}@"
+ "-CMSessionMgr- %s: Not switching NowPlayingApp to %{public}@ because system media casting is active"
+ "-CMSessionMgr_MDE- %s: Audio policy: isSomeClientPlayingAudio = %{public}s, shouldStartTimer = %{public}s"
+ "-CMSessionMgr_MDE- %s: MDE idle timer fired (audio): isSomeClientPlayingAudio = %{public}s, stillIdle = %{public}s"
+ "-CMSessionMgr_MDE- %s: MDE idle timer fired (mirroring): screenIsBlanked = %{public}s, isSomeClientPlayingAudio = %{public}s, stillIdle = %{public}s"
+ "-CMSessionMgr_MDE- %s: Mirroring policy: screenIsBlanked = %{public}s, isSomeClientPlayingAudio = %{public}s, shouldStartTimer = %{public}s"
+ "-CMSessionMgr_MDE- %s: creating gCMSM.disconnectMDEDeviceTimer for policy %{public}d, timer delay = %{public}f"
+ "-CMSessionMgr_MDE- %s: gCMSM.disconnectMDEDeviceTimer already armed for policy %{public}d, leaving in place"
+ "-CMVAEndptMgr- %s: CMSMVAUtility_AudioObjectSetPropertyData(kVirtualAudioDevicePropertySuppressVolumeForwarding) failed with err = %d = %c%c%c%c"
+ "-CMVAEndptMgr- %s: Suppressing volume forwarding on VAD %u"
+ "-CMVAEndptMgr- %s: kVirtualAudioDevicePropertySuppressVolumeForwarding is not supported on VAD %u"
+ "-FigCustomEndpoint- %s: Port-publication timeout: deactivate completed result=%{private}@"
+ "-FigRoutingManagerContextUtilities- %s: Activation timeout - removing stale entry and posting EndedFailed for uuid=%{public}@"
+ "-FigRoutingManagerContextUtilities- %s: Posting coalesced notification for original SET operation (entryOptions=%{public}@)"
+ "-FigRoutingManagerContextUtilities- %s: picking timer fired for '%@' '%@' (pickingState=%u)"
+ "-MXCustomRoutingController- %s: Allow session with bundleID: %{public}@ to play using protocolID %{public}@ because we're currently mirroring."
+ "-MXCustomRoutingSession- %s: Failed to take playback assertion for pid %d bundleID %{public}@"
+ "-MXCustomRoutingSession- %s: Invalid pid %d, cannot take playback assertion for %{public}@"
+ "-MXCustomRoutingSession- %s: Releasing playback assertion %p for pid %d bundleID %{public}@"
+ "-MXCustomRoutingSession- %s: Took playback assertion %p for pid %d bundleID %{public}@"
+ "-MXNowPlayingAppManager- %s: \t-------------------------- Custom Routing Information --------------------------"
+ "-MXNowPlayingAppManager- %s: \tCustomRoutingAppPID = %{public}@, CustomRoutingAppDisplayID = %{public}@, CustomRoutingAppIsPlaying = %{BOOL}u, CustomRoutingAppCanBeNowPlaying = %{BOOL}u"
+ "-MXNowPlayingAppManager- %s: Current custom routing app is allowed to be NowPlaying; pid=%d, displayID=%{public}@"
+ "-MXNowPlayingAppManager- %s: CustomRoutingSession displayID=%{public}@, pid=%d, isPlaying=%{BOOL}u, canBeNowPlayingApp=%{BOOL}u, currentNowPlayingAppPID=%d"
+ "-MXNowPlayingAppManager- %s: INTERRUPTING '%{public}@' for system casting Now Playing app"
+ "-MXNowPlayingAppManager- %s: PID %d associated with playing custom routing session is the new playing app"
+ "-MXNowPlayingAppManager- %s: Previous customRoutingSession=%{public}@, displayID=%{public}@, pid=%d, isPlaying=%{BOOL}u; Current customRoutingSession=%{public}@, displayID=%{public}@, pid=%d, isPlaying=%{BOOL}u."
+ "-MXNowPlayingAppManager- %s: Received: %{public}@"
+ "-MXSessionContext- %s: Updating the resumption context current active routes for client %{public}@ as it changed after activation"
+ "-MXSessionManagerUtilities- %s: Resumption context diverged by interruptor but no interruptor session found"
+ "-MXSessionManagerUtilities- %s: Resumption context diverged due to low priority session, skip processing resumption context"
+ "-MXSessionManagerUtilities- %s: Sending resumption context diverged info for %{public}@ ReporterStarted = %{BOOL}u"
+ "-MXSessionManagerUtilities- %s: Skipping flag takeover for %{public}@ to prevent VSYL oscillation."
+ "-MXSessionManagerUtilities- %s: updateControlFlagsAfterRouteChange called re-entrantly; skipping to prevent VSYL oscillation."
+ "-MXSystemSounds- %s: VoiceOver system sounds on VSYL: base volume=%1.3f, scaling factor=%1.3f, scaled volume=%1.3f"
+ "-[MXCustomRoutingSession releasePlaybackAssertion]"
+ "-[MXCustomRoutingSession takePlaybackAssertion]"
+ "-[MXNowPlayingAppManager customRoutingSessionPlaybackStateDidChangeCallback:]"
+ "-[MXNowPlayingAppManager customRoutingSessionPlaybackStateDidChangeCallback:]_block_invoke"
+ "-[MXNowPlayingAppManager routingSessionControllerCurrentSessionDidChangeCallback:]"
+ "-[MXNowPlayingAppManager updateCurrentCustomRoutingSession]"
+ "-[MXSessionManager(Utilities) processSessionResumptionContextIfNeeded:]"
+ "-[MXSessionManager(Utilities) synchronizeSessionVolumeWithMediaVolumeIfNeeded:mediaWasPlaying:route:]"
+ "-[MXSessionManager(Utilities) tryToTakeControlFlagsOnDefaultVAD:routingFlagIsNotControlled:]"
+ "-[MXSessionManager(Utilities) updateControlFlagsAfterRouteChange:systemLocalVADState:musicVADState:]"
+ "-[MXSessionResumptionContext updateActiveRoutesOnContextCreationIfChangedAfterActivationForSession:previousActiveRoutes:]"
+ "-[MXSystemCastingExtensionInstance handleForSelf]"
+ "22:44:50"
+ "CMSMNP_GetNowPlayingAppIsPlaying"
+ "CMSystemSoundMgrGetMaxVoiceOverVolumeOnSystemLocalVAD"
+ "CustomRoutingSessionChanged"
+ "HomeDeviceHourlyChime"
+ "Jul 10 2026"
+ "MX_CoreServices_CopyLocalizedApplicationName"
+ "MediaAppName"
+ "MediaExperience.%d.\"%@\".customRoutingSessionPlaybackAssertion"
+ "PVMGetRawVolumeForRouteFromVolume"
+ "customEndpoint_timeoutActivationIfWaitingForPort_block_invoke"
+ "vaemSuppressVolumeForwardingOnVAD"
- "-CMSessionMgr_MDE- %s: MDE idle timer fired: screenIsBlanked = %{public}s, isSomeClientPlayingTo3PEndpoint = %{public}s, extensionIsMirroring = %{public}s"
- "-CMSessionMgr_MDE- %s: creating gCMSM.disconnectMDEDeviceTimer, timer delay = %{public}f"
- "-CMSessionMgr_MDE- %s: screenIsBlanked = %{public}s, isSomeClientPlayingTo3PEndpoint = %{public}s, extensionIsMirroring = %{public}s, shouldStartTimer = %{public}s"
- "-FigRoutingManagerContextUtilities- %s: picking timer fired for '%@' '%@'"
- "-MXSessionManagerUtilities- %s: Sending resumption context divereged info for %{public}@ ReporterStarted = %{BOOL}u"
- "-MXSystemMediaCastingController_Client- %s: Called"
- "-[MXSessionManager(Utilities) synchronizeSessionVolumeWithMediaVolumeIfNeeded:]"
- "-[MXSessionManager(Utilities) tryToTakeControlFlagsOnDefaultVAD:]"
- "-[MXSystemMediaCastingController_Client didReceiveMediaSourceUpdate:]"
- "21:27:17"
- "Jun 29 2026"
- "cmsmGetMaxVolumeForVoiceOverSystemSound"
```
