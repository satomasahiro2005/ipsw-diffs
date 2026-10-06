## demod

> `/usr/libexec/demod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf3368` | `0xf43d4` | **`+0x106c`** |
| `__TEXT.__objc_methname` | `0x2037d` | `0x20de1` | **`+0xa64`** |
| `__TEXT.__oslogstring` | `0x1c58c` | `0x1c93c` | **`+0x3b0`** |
| `__TEXT.__objc_methlist` | `0xd5ac` | `0xd944` | **`+0x398`** |
| `__DATA.__objc_const` | `0x193e0` | `0x19710` | **`+0x330`** |
| `__TEXT.__objc_methtype` | `0x3d5b` | `0x3fdb` | **`+0x280`** |
| `__DATA.__objc_selrefs` | `0x7e88` | `0x80c0` | **`+0x238`** |
| `__DATA_CONST.__got` | `0xd90` | `0xf10` | **`+0x180`** |
| `__TEXT.__objc_stubs` | `0x1b360` | `0x1b480` | **`+0x120`** |
| `__TEXT.__cstring` | `0x10b22` | `0x10bb2` | **`+0x90`** |
| `__DATA.__data` | `0x2930` | `0x2990` | **`+0x60`** |
| `__DATA_CONST.__cfstring` | `0xebe0` | `0xec40` | **`+0x60`** |
| `__DATA.__objc_data` | `0x47b0` | `0x4800` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x4680` | `0x46bc` | **`+0x3c`** |
| `__TEXT.__unwind_info` | `0x39f0` | `0x3a28` | **`+0x38`** |
| `__TEXT.__objc_classname` | `0x184a` | `0x186a` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x20a0` | `0x20b0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xb28` | `0xb34` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x1060` | `0x1068` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x718` | `0x720` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x158` | `0x160` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1871.0.14.0.0
+1871.0.29.0.0

-  Functions: 6024
-  Symbols:   1047
-  CStrings:  10739
+  Functions: 6048
+  Symbols:   1048
+  CStrings:  10853
Symbols:
+ _dispatch_group_wait
CStrings:
+ "%s - New content detected; forcing full install of all manifest content."
+ "%s - New submanifest content requires a manifest reinstall to prevent data loss, but manifestInfo is nil (manifest was never received or persisted).  Submanifest content may overwrite previously installed manifest content."
+ "%s is called with SN %@."
+ "%s was called."
+ "-[MSDHomeManager _checkAndRepairPrimaryPreferredHubState]"
+ "-[MSDHomeManager setPrimaryPreferredHub:]"
+ "Failed to remove home '%{public}@'. Error code: %ld, description: %{public}@"
+ "ForceInstall"
+ "HMHomeDelegatePrivate"
+ "Home is in good state with primary preferred resident."
+ "Home is in odd state.  Intended primary preferred hub is not what DCOTA server is expecting.  Setting now to use %@ from previously %@..."
+ "Home is in odd state.  Intended resident (%@) is not the same as current resident (%@)."
+ "IntendedPrimaryPreferredHub"
+ "MSDScreenFacesRefresh"
+ "No homes present yet; waiting up to %dmin for homeManagerDidUpdateHomes."
+ "No homes to remove."
+ "No primary preferred hub set by server.  Home is in good state."
+ "Removing %lu home(s)."
+ "Successfully removed home '%{public}@'."
+ "T@\"NSDictionary\",&,V_dataStoreCache"
+ "TB,N,V_forceInstall"
+ "Timed out after %dmin waiting for homes to populate."
+ "Timed out after %dsec waiting for all homes to be removed."
+ "_checkAndRepairPrimaryPreferredHubState"
+ "_dataStoreCache"
+ "_forceInstall"
+ "_manifestVersionStringForSignedManifest:"
+ "checkAndRepairPrimaryPreferredHubState:"
+ "dataStoreCache"
+ "forceInstall"
+ "home:didAddAccessoryNetworkProtectionGroup:"
+ "home:didAddMediaSystem:"
+ "home:didAddResidentDevice:"
+ "home:didFailAccessorySetupWithError:"
+ "home:didRemoveAccessoryNetworkProtectionGroup:"
+ "home:didRemoveMediaSystem:"
+ "home:didRemoveResidentDevice:"
+ "home:didUpdateAccessControlForUser:"
+ "home:didUpdateAccessoryInvitationsForUser:"
+ "home:didUpdateAccessoryNetworkProtectionGroup:"
+ "home:didUpdateActionSet:isExecuting:"
+ "home:didUpdateApplicationDataForActionSet:"
+ "home:didUpdateApplicationDataForRoom:"
+ "home:didUpdateApplicationDataForServiceGroup:"
+ "home:didUpdateAreBulletinNotificationsSupported:"
+ "home:didUpdateAudioAnalysisClassifierOptions:"
+ "home:didUpdateAudioGroupsController:"
+ "home:didUpdateAutomaticSoftwareUpdateEnabled:"
+ "home:didUpdateAutomaticThirdPartyAccessorySoftwareUpdateEnabled:"
+ "home:didUpdateClipCaptionLocales:"
+ "home:didUpdateClipCaptioningEnabled:"
+ "home:didUpdateClipCaptioningEnabledCameras:"
+ "home:didUpdateDismissedWalletKeyUWBUnlockOnboarding:"
+ "home:didUpdateEventLogDuration:"
+ "home:didUpdateEventLogEnabled:"
+ "home:didUpdateHasOnboardedForWalletKey:"
+ "home:didUpdateHomeActivityState:isActivityStateHoldActive:activityStateHoldEndDate:transitionalStateEndDate:"
+ "home:didUpdateHomeActivityStateSchedule:"
+ "home:didUpdateLastExecutionDateForActionSet:"
+ "home:didUpdateLocation:"
+ "home:didUpdateMediaPassword:"
+ "home:didUpdateMediaPeerToPeerEnabled:"
+ "home:didUpdateMinimumMediaUserPrivilege:"
+ "home:didUpdateOnboardAudioAnalysis:"
+ "home:didUpdatePersonManagerSettings:"
+ "home:didUpdateReprovisionStateForAccessory:"
+ "home:didUpdateSiriPhraseOptions:"
+ "home:didUpdateStateForOutgoingInvitations:"
+ "home:didUpdateSupportsResidentActionSetStateEvaluation:"
+ "home:didUpdateTimeZone:"
+ "homeDidAddWalletKey:"
+ "homeDidEnableLocationServices:"
+ "homeDidEnableMultiUser:"
+ "homeDidOnboardLocationServices:"
+ "homeDidRemoveWalletKey:"
+ "homeDidSetEnableDoorbellChime:"
+ "homeDidSetHasAnyUserAcknowledgedCameraRecordingOnboarding:"
+ "homeDidSetHasOnboardedForAccessCode:"
+ "homeDidUpdateApplicationData:"
+ "homeDidUpdateAssistantIdentifiers:"
+ "homeDidUpdateAutoSelectedPreferredResident:"
+ "homeDidUpdateHomeLocationStatus:"
+ "homeDidUpdateNetworkRouterSupport:"
+ "homeDidUpdateOnboardedEventLog:"
+ "homeDidUpdatePrimaryResidentNetworkInfo:"
+ "homeDidUpdateProtectionMode:"
+ "homeDidUpdateSoundCheck:"
+ "homeDidUpdateSupportsResidentSelection:"
+ "homeDidUpdateToROAR:"
+ "homeDidUpdateUserSelectedPreferredResident:"
+ "mailto:"
+ "needsInstallation"
+ "normalizedUserID:"
+ "removeAllHomes"
+ "removeHome:completionHandler:"
+ "setDataStoreCache:"
+ "setForceInstall:"
+ "v28@0:8@\"HMHome\"16B24"
+ "v32@0:8@\"HMHome\"16@\"CLLocation\"24"
+ "v32@0:8@\"HMHome\"16@\"HMAccessoryNetworkProtectionGroup\"24"
+ "v32@0:8@\"HMHome\"16@\"HMHomeActivityStateSchedule\"24"
+ "v32@0:8@\"HMHome\"16@\"HMHomePersonManagerSettings\"24"
+ "v32@0:8@\"HMHome\"16@\"HMMediaGroupsController\"24"
+ "v32@0:8@\"HMHome\"16@\"HMMediaSystem\"24"
+ "v32@0:8@\"HMHome\"16@\"HMResidentDevice\"24"
+ "v32@0:8@\"HMHome\"16@\"NSArray\"24"
+ "v32@0:8@\"HMHome\"16@\"NSError\"24"
+ "v32@0:8@\"HMHome\"16@\"NSSet\"24"
+ "v32@0:8@\"HMHome\"16@\"NSString\"24"
+ "v32@0:8@\"HMHome\"16@\"NSTimeZone\"24"
+ "v32@0:8@\"HMHome\"16q24"
+ "v32@0:8@16q24"
+ "v36@0:8@\"HMHome\"16@\"HMActionSet\"24B32"
+ "v52@0:8@\"HMHome\"16Q24B32@\"NSDate\"36@\"NSDate\"44"
+ "v52@0:8@16Q24B32@36@44"
- "Device with serialNumber %{public}@ is already primary resident. Nothing to do."
```
