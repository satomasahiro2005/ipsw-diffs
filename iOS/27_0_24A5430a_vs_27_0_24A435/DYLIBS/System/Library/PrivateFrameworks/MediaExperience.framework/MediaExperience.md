## MediaExperience

> `/System/Library/PrivateFrameworks/MediaExperience.framework/MediaExperience`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x252aec` | `0x254540` | **`+0x1a54`** |
| `__TEXT.__oslogstring` | `0x4fced` | `0x501a3` | **`+0x4b6`** |
| `__TEXT.__cstring` | `0x38bac` | `0x38f4b` | **`+0x39f`** |
| `__TEXT.__objc_methlist` | `0x8818` | `0x88c8` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x1bfe0` | `0x1c080` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x5448` | `0x54c0` | **`+0x78`** |
| `__AUTH_CONST.__objc_const` | `0xcec0` | `0xcf28` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x5f58` | `0x5f90` | **`+0x38`** |
| `__AUTH_CONST.__const` | `0x4968` | `0x4988` | **`+0x20`** |
| `__DATA.__bss` | `0x1370` | `0x1380` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xc70` | `0xc78` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xd08` | `0xd10` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 10075
-  Symbols:   13504
-  CStrings:  9868
+  Functions: 10094
+  Symbols:   13524
+  CStrings:  9897
Symbols:
+ -[MXCoreSession isAllowedToInterruptSecurePairing]
+ -[MXCoreSessionBase isAllowedToInterruptSecurePairing]
+ -[MXCoreSessionSecure isIsolatedAudioUseCaseIDSecurePairing]
+ -[MXSessionManager(Utilities) copyLocalizedApplicationNameForActiveSessionControllingRouting:]
+ -[MXSessionManager(Utilities) isAnySessionWhichInterruptsSecurePairingActive]
+ -[MXSessionManager(Utilities) showAudioRouteMovedToReceiverBannerForActiveSessionControllingRouting]
+ -[MXSessionManager(Utilities) showAudioRouteMovedToSpeakerBannerForActiveSessionControllingRouting]
+ -[MXSessionManagerSecure handleSecurePairingSessionPreActivation]
+ -[MXSessionManagerSecure interruptSecureSession:interruptorBundleID:interruptorName:fadeDuration:waitingToResume:]
+ -[MXSessionManagerSecure isSecurePairingInProgress]
+ -[MXSessionManagerSecure postInterruptionCommandNotification:interruptionCommand:interruptorName:interruptorBundleID:status:volumeChangeDuration:]
+ -[MXSessionManagerSecure postStopCommandToSecurePairingSession:waitingToResume:]
+ -[MXSessionManagerSecure setIsSecurePairingInProgress:]
+ -[MX_BannerManager showAudioMovedToReceiverBanner:]
+ -[MX_BannerManager showAudioMovedToSpeakerBanner:]
+ GCC_except_table142
+ _MX_FeatureFlags_IsSecurePairingEnabled
+ _MX_FeatureFlags_IsSecurePairingEnabled.onceToken
+ _MX_FeatureFlags_IsSecurePairingEnabled.sIsSecurePairingEnabled
+ _OBJC_IVAR_$_MXCoreSessionBase._isAllowedToInterruptSecurePairing
+ _OBJC_IVAR_$_MXSessionManagerSecure._isSecurePairingInProgress
+ __OBJC_$_PROP_LIST_MXSessionManagerSecure
+ ___146-[MXSessionManagerSecure postInterruptionCommandNotification:interruptionCommand:interruptorName:interruptorBundleID:status:volumeChangeDuration:]_block_invoke
+ ___MX_FeatureFlags_IsSecurePairingEnabled_block_invoke
- GCC_except_table138
- _OUTLINED_FUNCTION_163
- _OUTLINED_FUNCTION_164
- _OUTLINED_FUNCTION_165
CStrings:
+ "-CMSessionMgr- %s: Skipping  begin interruption for %{public}@ because it is trying to go active during secure airpod pairing"
+ "-MXSessionManagerSecure- %s: INTERRUPTING session '%{public}@' for secure airpod pairing"
+ "-MXSessionManagerSecure- %s: Interrupting secure pairing session for session %{public}@"
+ "-MXSessionManagerSecure- %s: MXSessionManagerSecure with interrupting session %{public}@ INTERRUPTING victim: %{public}@ with audioCategory %{public}@"
+ "-MXSessionManagerSecure- %s: No interruptor session provided!"
+ "-MXSessionManagerSecure- %s: Secure Pairing cannot go active while phone calls/emergency alerts are active"
+ "-MXSessionManagerSecure- %s: Unable to post interruption command for secure audio session"
+ "-MXSessionManagerSecure- %s: isSecurePairingInProgress has changed to %{public}@"
+ "-MXSessionManagerUtilities- %s: Firing moved to receiver banner"
+ "-MXSessionManagerUtilities- %s: Firing moved to speaker banner"
+ "-MXSessionManagerUtilities- %s: Going to show banner for session %{public}@"
+ "-MXSessionManagerUtilities- %s: Nil output param"
+ "-MXSessionManagerUtilities- %s: No active session to show banner for, skipping"
+ "-MX_FeatureFlags- %s: MediaExperience/SecurePairingEnabled feature is %{public}@"
+ "-[MXSessionManager(Utilities) copyLocalizedApplicationNameForActiveSessionControllingRouting:]"
+ "-[MXSessionManager(Utilities) showAudioRouteMovedToReceiverBannerForActiveSessionControllingRouting]"
+ "-[MXSessionManager(Utilities) showAudioRouteMovedToSpeakerBannerForActiveSessionControllingRouting]"
+ "-[MXSessionManagerSecure handleSecurePairingSessionPreActivation]"
+ "-[MXSessionManagerSecure interruptSecureSession:interruptorBundleID:interruptorName:fadeDuration:waitingToResume:]"
+ "-[MXSessionManagerSecure postInterruptionCommandNotification:interruptionCommand:interruptorName:interruptorBundleID:status:volumeChangeDuration:]"
+ "-[MXSessionManagerSecure postStopCommandToSecurePairingSession:waitingToResume:]"
+ "-[MXSessionManagerSecure setIsSecurePairingInProgress:]"
+ "15:48:22"
+ "Aug  8 2026"
+ "DeviceStateChange"
+ "MXSessionManagerSecure.m"
+ "MX_FeatureFlags_IsSecurePairingEnabled_block_invoke"
+ "SecurePairing"
+ "SecurePairingInput"
+ "SpeakerDriverOutput"
+ "SpeakerValidation"
- "00:52:54"
- "Aug 10 2026"
```
