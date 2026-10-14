## com.apple.NeighborhoodActivityConduitService

> `/System/Library/PrivateFrameworks/NeighborhoodActivityConduit.framework/XPCServices/com.apple.NeighborhoodActivityConduitService.xpc/com.apple.NeighborhoodActivityConduitService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14caa0` | `0x17e4ec` | **`+0x31a4c`** |
| `__TEXT.__eh_frame` | `0xd8f0` | `0xf870` | **`+0x1f80`** |
| `__TEXT.__oslogstring` | `0x6fac` | `0x7f45` | **`+0xf99`** |
| `__DATA_CONST.__const` | `0x66b8` | `0x7440` | **`+0xd88`** |
| `__TEXT.__unwind_info` | `0x4210` | `0x4e60` | **`+0xc50`** |
| `__TEXT.__objc_methname` | `0x6d57` | `0x764b` | **`+0x8f4`** |
| `__TEXT.__swift5_capture` | `0x2bd8` | `0x333c` | **`+0x764`** |
| `__TEXT.__const` | `0x4998` | `0x50d8` | **`+0x740`** |
| `__DATA.__data` | `0x3870` | `0x3ea8` | **`+0x638`** |
| `__DATA.__objc_const` | `0x4398` | `0x49d0` | **`+0x638`** |
| `__TEXT.__auth_stubs` | `0x38c0` | `0x3d70` | **`+0x4b0`** |
| `__TEXT.__swift5_typeref` | `0x344a` | `0x38cf` | **`+0x485`** |
| `__TEXT.__objc_stubs` | `0x2fa0` | `0x33c0` | **`+0x420`** |
| `__TEXT.__cstring` | `0x1fc6` | `0x2386` | **`+0x3c0`** |
| `__TEXT.__constg_swiftt` | `0x1c48` | `0x1f84` | **`+0x33c`** |
| `__TEXT.__swift5_reflstr` | `0x1dc4` | `0x20d9` | **`+0x315`** |
| `__DATA.__objc_data` | `0x1130` | `0x13f8` | **`+0x2c8`** |
| `__TEXT.__swift_as_cont` | `0x1028` | `0x12a8` | **`+0x280`** |
| `__DATA_CONST.__auth_got` | `0x1c68` | `0x1ec0` | **`+0x258`** |
| `__TEXT.__objc_methlist` | `0x1624` | `0x186c` | **`+0x248`** |
| `__TEXT.__objc_classname` | `0xb9b` | `0xdbb` | **`+0x220`** |
| `__DATA.__objc_selrefs` | `0x1700` | `0x1908` | **`+0x208`** |
| `__TEXT.__swift5_fieldmd` | `0x13f8` | `0x15f4` | **`+0x1fc`** |
| `__DATA_CONST.__got` | `0xf20` | `0x10a8` | **`+0x188`** |
| `__DATA_CONST.__auth_ptr` | `0x7e0` | `0x908` | **`+0x128`** |
| `__DATA.__bss` | `0x2d30` | `0x2e30` | **`+0x100`** |
| `__TEXT.__objc_methtype` | `0x11a1` | `0x12a1` | **`+0x100`** |
| `__TEXT.__swift_as_entry` | `0x53c` | `0x614` | **`+0xd8`** |
| `__TEXT.__swift_as_ret` | `0x544` | `0x61c` | **`+0xd8`** |
| `__DATA_CONST.__objc_protolist` | `0x108` | `0x148` | **`+0x40`** |
| `__DATA_CONST.__objc_classlist` | `0xe0` | `0x100` | **`+0x20`** |
| `__DATA_CONST.__objc_protorefs` | `0x90` | `0xb0` | **`+0x20`** |
| `__TEXT.__swift5_types` | `0x120` | `0x13c` | **`+0x1c`** |
| `__DATA.__common` | `0x168` | `0x180` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x1ac` | `0x1c0` | **`+0x14`** |
| `__TEXT.__swift5_protos` | `0x44` | `0x50` | **`+0xc`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-1626.200.84.0.0
+1626.200.91.2.3

+  - /System/Library/Frameworks/LocalAuthentication.framework/LocalAuthentication

+  - /System/Library/PrivateFrameworks/AppProtection.framework/AppProtection

+  - /System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration
+  - /System/Library/PrivateFrameworks/MobileKeyBag.framework/MobileKeyBag

-  Functions: 3970
-  Symbols:   427
-  CStrings:  1648
+  Functions: 4484
+  Symbols:   439
+  CStrings:  1830
Symbols:
+ _CNContactCallAlertKey
+ _MKBGetDeviceLockState
+ _OBJC_CLASS_$_APApplication
+ _OBJC_CLASS_$_APSubject
+ _OBJC_CLASS_$_LAEnvironment
+ _OBJC_CLASS_$_LSApplicationWorkspace
+ _OBJC_CLASS_$_MCProfileConnection
+ _OBJC_CLASS_$_TUBusinessServicesMetadataDataProvider
+ _TUIsFaceTimeAppInstalled
+ _TUPrivacyRulesChangedNotification
+ _notify_cancel
+ _notify_register_dispatch
CStrings:
+ "@\"NSURL\"16@0:8"
+ "APSubjectMonitor"
+ "Allow Audible Ring: %{bool}d"
+ "Block List Updated, sending new state."
+ "Block and report %s"
+ "Blocked %s"
+ "Blocking %s"
+ "Couldn't observe %s: %u."
+ "Couldn't observe any lock notification - lock transitions won't end sessions."
+ "Device lock status changed - reevaluating."
+ "Ending %ld advertised nearby sessions."
+ "Ending home accessory session with %s."
+ "FaceTime is no longer available - ending all sessions."
+ "Home accessory sessions updated to %s"
+ "HomeAccessory17,1"
+ "HomeAccessory17,2"
+ "Initializing..."
+ "LAEnvironmentObserver"
+ "LSApplicationWorkspaceObserverProtocol"
+ "LocalAuthentication environment changed - reevaluating."
+ "Not allowing ring, device doesn't support audible ringtones."
+ "Reevaluated isFaceTimeInstalled: %{bool}d"
+ "Reevaluated isFaceTimeProtected: %{bool}d"
+ "Rejecting start laguna session because iOS device has deleted FaceTime App."
+ "Rejecting start laguna session because iOS device has protected FaceTime App."
+ "Rejecting start laguna session request because home device pairing is disabled by MDM."
+ "Remote requests would now be %s - device locked: %{bool}d, biometric lockout: %{bool}d."
+ "Report %s, model: %s"
+ "Suggestions not supported, skipping suggestion for device %@"
+ "T@\"NSString\",R,C,N"
+ "T@\"NSURL\",R,C,N"
+ "TUBusinessCallerItem"
+ "This device would refuse a remote request - ending all sessions."
+ "Unable to report, no spam call model info"
+ "Unblocked %s"
+ "Unblocking %s"
+ "Unknown block request type: %ld"
+ "Update Blocked State %ld for handles: %s"
+ "[AudioRoute] Failed to pick route %s immediately -- waiting for the route to appear. Current routes: %s"
+ "[AudioRoute] Failed to transfer audio route %s with error: %@"
+ "[AudioRoute] Picking route %s from known routes: %s"
+ "[AudioRoute] Rejecting request to transfer audio route because we're currently in an active session."
+ "[AudioRoute] Requesting to transfer audio route %s to device %s"
+ "[AudioRoute] Skipping audio route push - disabled"
+ "[AudioRoute] Skipping audio route push - no route picked"
+ "[AudioRoute] Skipping audio route push - picked route is not eligible for transfer: %s"
+ "[AudioRoute] Skipping audio route push because we're not handed off."
+ "[GetCallDisplayDetails] Rejecting request to brows contacts from a device with which we do not have a session: %s"
+ "[GetContactImage] Failed to fetch logo: missing logo URL."
+ "[GetContactImage] Failed to fetch logo: missing metadata provider."
+ "[GetContactImage] Fetching Business Logo for handle: %s."
+ "[GetContactImage] Returning Fetched Logo: %s"
+ "[GetRingtoneConfiguration] Rejecting request for ringtone configuration from a device with which we do not have a session: %s"
+ "[GetRingtoneConfiguration] allowRingtone=false"
+ "[GetRingtoneConfiguration] sending configuration for: %s"
+ "[GetRingtoneConfiguration] unable to find matching conversation for identifier: %s"
+ "[HandoffConversation] Failed to prepare for transfer with %s due to %@."
+ "[HandoffConversation] Sending prepare transfer request to %s."
+ "[HandoffConversation] Successfully prepared for transfer with %s."
+ "[Lookup Actor] (%s) Returning cached availability without waiting on a query"
+ "[SessionServer] Error sending onLinksDidChange event %@"
+ "[TransferActiveConversation] Continuity session doesn't exist for %s"
+ "[TransferActiveConversation] Failed to transfer %s to %s due to %@."
+ "[TransferActiveConversation] Initiating transfer of %s to %s."
+ "[TransferActiveConversation] Invalid conversation UUID: %s"
+ "[TransferActiveConversation] Successfully transferred %s to %s."
+ "[TransferContinuityCall] Continuity session doesn't exist for %s"
+ "[TransferContinuityCall] Requesting to pick route for %s..."
+ "[TransferContinuityCall] Successfully picked route for %s!"
+ "[TransferContinuityCall] Unable to find a route for %s"
+ "[UpdateBlockedState] Rejecting request for blocked caller update from device with which we do not have a laguna session %s."
+ "_TtC44com_apple_NeighborhoodActivityConduitService22AppAvailabilityManager"
+ "_TtC44com_apple_NeighborhoodActivityConduitService23BiometricLockoutMonitor"
+ "_TtC44com_apple_NeighborhoodActivityConduitServiceP33_9F80DC376766A8057667384B27267FA824DeviceLockStatusObserver"
+ "_TtC44com_apple_NeighborhoodActivityConduitServiceP33_9F80DC376766A8057667384B27267FA827BiometryEnvironmentObserver"
+ "_isFaceTimeInstalled"
+ "_isFaceTimeProtected"
+ "addMonitor:"
+ "addObserver:"
+ "appAvailabilityManager"
+ "appProtectionSubjectsChanged:forSubscription:"
+ "applicationIconDidChange:"
+ "applicationInstallsArePrioritized:arePaused:"
+ "applicationInstallsDidCancel:"
+ "applicationInstallsDidChange:"
+ "applicationInstallsDidPause:"
+ "applicationInstallsDidPrioritize:"
+ "applicationInstallsDidResume:"
+ "applicationInstallsDidStart:"
+ "applicationInstallsDidUpdateIcon:"
+ "applicationStateDidChange:"
+ "applicationsDidChangePersonas:"
+ "applicationsDidFailToInstall:"
+ "applicationsDidFailToUninstall:"
+ "applicationsDidInstall:"
+ "applicationsDidUninstall:"
+ "applicationsDidUpdateMetadata:"
+ "applicationsWillInstall:"
+ "applicationsWillUninstall:"
+ "biometricState"
+ "biometry"
+ "callAlert"
+ "callDirectoryIdentityType"
+ "callerIdSubStringForDisplay"
+ "callerNameForDisplay"
+ "com.apple.NeighborhoodActivityConduit.deviceLockStatus"
+ "com.apple.callservicesd.audioRouteTransfer"
+ "com.apple.callservicesd.blockListUpdated"
+ "com.apple.callservicesd.prepareTransfer"
+ "com.apple.callservicesd.requestCallDisplayDetails"
+ "com.apple.callservicesd.requestRingtoneConfiguration"
+ "com.apple.callservicesd.transferActiveConversation"
+ "com.apple.callservicesd.transferContinuityCall"
+ "com.apple.callservicesd.updateBlockedState"
+ "com.apple.mobile.keybagd.lock_status"
+ "com.apple.springboard.lockstate"
+ "com_apple_NeighborhoodActivityConduitService.BiometryEnvironmentObserver"
+ "currentBlockedState()"
+ "currentCalls"
+ "currentUser"
+ "databaseWasRebuilt"
+ "defaultWorkspace"
+ "deniesRemoteRequestsSubject"
+ "department"
+ "deviceLockState"
+ "deviceManagementPolicyDidChange:"
+ "environment:stateDidChangeFromOldState:"
+ "environmentObserver"
+ "fetchBusinessServiceInformationForHandleValue:completion:"
+ "getPickedRoute()"
+ "handleFromMessagingData:"
+ "helperPlaceholdersInstalled:"
+ "helperPlaceholdersUninstalled:"
+ "hiddenAppBundleIdentifiers"
+ "homeAccessorySessions"
+ "isBiometryLockedOutObserver"
+ "isBluetooth"
+ "isEnrolled"
+ "isFaceTimeAvailableObserver"
+ "isFaceTimeInstalledSubject"
+ "isFaceTimeProtectedSubject"
+ "isKeyAvailable:"
+ "isLockedOut"
+ "isPairingWithHomeDevicesAllowed"
+ "localParticipantUUID"
+ "lockStatusObserver"
+ "lockedAppBundleIdentifiers"
+ "logoURL"
+ "nearbyAvailableSessions"
+ "networkUsageChanged:"
+ "observeLaunchProhibitedApps"
+ "onGetCallDisplayDetailsRequest(_:sender:)"
+ "onGetRingtoneConfigurationRequest(_:sender:)"
+ "onRequestTransferContinuityCall(_:sender:)"
+ "onStateChange"
+ "pebbleAudibleRingtonesEnabled"
+ "pendingMembers"
+ "pickRoute(with:)"
+ "pickRouteWhenAvailableWithUniqueIdentifier:"
+ "pickedRoute"
+ "pluginsDidInstall:"
+ "pluginsDidUninstall:"
+ "pluginsWillUninstall:"
+ "providerForRecentCall:"
+ "providerManager"
+ "removeObserver:"
+ "senderIdentityForAccountUUID:"
+ "sound"
+ "stringFromContact:style:"
+ "subjectMonitorRegistry"
+ "tokens"
+ "uniqueId"
+ "v12@?0i8"
+ "v16@?0@\"<TUBusinessCallerItem>\"8"
+ "v24@0:8@\"NSArray\"16"
+ "v32@0:8@\"LAEnvironment\"16@\"LAEnvironmentState\"24"
+ "v32@0:8@\"NSArray\"16@\"<APSubjectMonitorSubscription>\"24"
+ "v32@0:8@\"NSArray\"16@\"NSArray\"24"
+ "v36@0:8@\"NSString\"16B24@?<v@?B@\"NSError\">28"
+ "v36@0:8@16B24@?28"
+ "validateGuestSessionInvitationFromIDSIdentifier:requireActiveConnection:completion:"
+ "voicemailSpamArbitrationEnabled"
```
