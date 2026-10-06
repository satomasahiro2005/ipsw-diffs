## remotepairingdeviced

> `/usr/libexec/remotepairingdeviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x905c0` | `0x971b0` | **`+0x6bf0`** |
| `__TEXT.__oslogstring` | `0x3dbf` | `0x424f` | **`+0x490`** |
| `__DATA.__data` | `0x47a8` | `0x4b68` | **`+0x3c0`** |
| `__DATA.__objc_const` | `0x5558` | `0x5908` | **`+0x3b0`** |
| `__TEXT.__objc_methname` | `0x18d5` | `0x1c15` | **`+0x340`** |
| `__DATA_CONST.__const` | `0x5910` | `0x5bf0` | **`+0x2e0`** |
| `__TEXT.__cstring` | `0x53ac` | `0x565c` | **`+0x2b0`** |
| `__TEXT.__swift5_reflstr` | `0x1b03` | `0x1d93` | **`+0x290`** |
| `__TEXT.__objc_stubs` | `0x820` | `0xa40` | **`+0x220`** |
| `__TEXT.__const` | `0x3798` | `0x3968` | **`+0x1d0`** |
| `__TEXT.__constg_swiftt` | `0x1f40` | `0x20f8` | **`+0x1b8`** |
| `__TEXT.__swift5_fieldmd` | `0x1374` | `0x14b8` | **`+0x144`** |
| `__TEXT.__eh_frame` | `0x1ee0` | `0x2018` | **`+0x138`** |
| `__TEXT.__unwind_info` | `0x1ac8` | `0x1bf8` | **`+0x130`** |
| `__TEXT.__swift5_capture` | `0x1dbc` | `0x1eb8` | **`+0xfc`** |
| `__TEXT.__swift5_typeref` | `0x256c` | `0x264c` | **`+0xe0`** |
| `__TEXT.__auth_stubs` | `0x42e0` | `0x4380` | **`+0xa0`** |
| `__DATA.__bss` | `0x1f48` | `0x1fd0` | **`+0x88`** |
| `__DATA.__objc_selrefs` | `0x2b8` | `0x340` | **`+0x88`** |
| `__TEXT.__objc_classname` | `0x9c2` | `0xa32` | **`+0x70`** |
| `__TEXT.__objc_methtype` | `0x46b` | `0x4cb` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x2180` | `0x21d0` | **`+0x50`** |
| `__DATA_CONST.__auth_ptr` | `0xa08` | `0xa48` | **`+0x40`** |
| `__DATA_CONST.__got` | `0xc98` | `0xcd0` | **`+0x38`** |
| `__DATA_CONST.__objc_classlist` | `0x128` | `0x138` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x108` | `0x114` | **`+0xc`** |
| `__TEXT.__swift5_proto` | `0x134` | `0x138` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-280.0.0.0.0
+280.0.5.0.0

+  - /System/Library/Frameworks/UserNotifications.framework/UserNotifications

+  - /usr/lib/swift/libswiftCoreMIDI.dylib

-  Functions: 3518
-  Symbols:   1697
-  CStrings:  945
+  Functions: 3696
+  Symbols:   1718
+  CStrings:  1008
Symbols:
+ _$s10Foundation14SortDescriptorV_5orderACyxGs7KeyPathCyxqd__SgG_AA0B5OrderOtcSLRd__lufC
+ _$s10Foundation3URLV19_bridgeToObjectiveCSo5NSURLCyF
+ _$s10Foundation3URLV6stringACSgSSh_tcfC
+ _$s19RemotePairingDevice0B15PolicyValidatorMp
+ _$s19RemotePairingDevice0B15PolicyValidatorP08validatebD004hostB7Options0G9Challenge10completionySDySSypGSg_10Foundation4DataVSgyAA0bD17ValidationOutcomeOctFTq
+ _$s19RemotePairingDevice0B23PolicyValidationOutcomeO17challengeRequiredyA2CmFWC
+ _$s19RemotePairingDevice0B23PolicyValidationOutcomeO7allowedyACSb_tcACmFWC
+ _$s19RemotePairingDevice0B23PolicyValidationOutcomeO8rejectedyACs5Error_pcACmFWC
+ _$s19RemotePairingDevice0B23PolicyValidationOutcomeOMa
+ _$s19RemotePairingDevice0B23PolicyValidationOutcomeOMn
+ _$s19RemotePairingDevice0aB5ErrorV21developerModeDisabledACvgZ
+ _$s19RemotePairingDevice19DeveloperModeStatusO23changedNotificationNameSSvgZ
+ _$s19RemotePairingDevice19DeveloperModeStatusO9isEnabledSbvgZ
+ _$s19RemotePairingDevice22AuditActivityAssertionC25NotificationConfigurationV10symbolNameSSvg
+ _$s19RemotePairingDevice22AuditActivityAssertionC25NotificationConfigurationV5titleSSvg
+ _$s19RemotePairingDevice22AuditActivityAssertionC25NotificationConfigurationV8subtitleSSvg
+ _$s19RemotePairingDevice23UserInteractionProviderP024collectConsentForPinlessB013withHostNamed10completionySSSg_yAA0bH17CollectionOutcomeOctFTq
+ _$s19RemotePairingDevice24ControlChannelConnectionC9transport5queue7options23maxReconnectionAttempts26pairingDataStorageProvider0M15PolicyValidator23peerWireProtocolVersionAcA0dE9Transport_p_So012OS_dispatch_H0CAC7OptionsOSiAA0bnoP0_pAA0bqR0_pAA0deftuV0CSgtcfc
+ _$sSaMa
+ _OBJC_CLASS_$_UNMutableNotificationContent
+ _OBJC_CLASS_$_UNNotificationIcon
+ _OBJC_CLASS_$_UNNotificationRequest
+ _OBJC_CLASS_$_UNNotificationSound
+ _OBJC_CLASS_$_UNTimeIntervalNotificationTrigger
+ _OBJC_CLASS_$_UNUserNotificationCenter
+ __swift_FORCE_LOAD_$_swiftCoreMIDI
+ _swift_release_x4
- _$s19RemotePairingDevice0B24ConsentCollectionOutcomeO17challengeRequiredyA2CmFWC
- _$s19RemotePairingDevice10AuditEventVSQAAMc
- _$s19RemotePairingDevice23UserInteractionProviderP024collectConsentForPinlessB013withHostNamed04hostB7Options0N9Challenge10completionySSSg_SDySSypGSg10Foundation4DataVSgyAA0bH17CollectionOutcomeOctFTq
- _$s19RemotePairingDevice24ControlChannelConnectionC9transport5queue7options23maxReconnectionAttempts26pairingDataStorageProvider23peerWireProtocolVersionAcA0dE9Transport_p_So012OS_dispatch_H0CAC7OptionsOSiAA0bnoP0_pAA0defrsT0CSgtcfc
- _strerror
- _swift_retain_x10
CStrings:
+ "$__lazy_storage_$_pairingPolicyValidator"
+ "%{public}s: Invalid state to handle pairing initiation request (current state: %{public}s, error: %{public}s)"
+ "%{public}s: Rejecting pair request because developer mode is not enabled"
+ "%{public}s: Unexpectedly received control channel invalidation for %s while in state %{public}s"
+ "Audit banners not supported on this platform"
+ "Collapsing pending banner for activity type: %{public}s"
+ "Current notification authorization status: %s"
+ "Device unlocked — invoking %ld next-unlock handler(s)"
+ "Device unlocked; delivering %ld pending audit banner(s)"
+ "Failed to mark notification presented for activity %{public}s: %{public}s"
+ "Failed to post audit banner for %{public}s: %{public}s"
+ "Failed to recover unpresented notifications: %{public}s"
+ "Failed to request notification authorization: %{public}s"
+ "Ignoring lock status change — device is not unlocked"
+ "Marked notification presented for activity: %{public}s"
+ "No stored record found for activity when marking notification presented: %{public}s"
+ "Notification authorization %s"
+ "Notification center not initialized; invoking completions without posting %ld pending banners"
+ "Pended banner for activity type: %{public}s (total pending: %ld)"
+ "Posted audit banner for activity type: %{public}s"
+ "Received next-unlock XPC event (lock status changed)"
+ "Recovering %ld unpresented notification(s) from previous session"
+ "Registered dynamic XPC event for next unlock detection"
+ "Registered next-unlock handler (total: %ld)"
+ "Started audit banner manager with section identifier: %{public}s"
+ "State dump: RSDService connection count = %ld"
+ "Unregistered dynamic XPC event for next unlock detection"
+ "UserNotifications not available on this platform; audit banners disabled"
+ "_TtC20remotepairingdeviced18AuditBannerManager"
+ "_TtC20remotepairingdeviced29DefaultPairingPolicyValidator"
+ "_completionQueue"
+ "_isDeveloperModeEnabled"
+ "_nextUnlockHandlers"
+ "_notificationCenter"
+ "_notificationPresented"
+ "_pairingPolicyValidator"
+ "_pendingBanners"
+ "_policyValidator"
+ "_registeredForNextUnlock"
+ "addNotificationRequest:withCompletionHandler:"
+ "auditActivityReportCategory"
+ "authorizationStatus"
+ "bannerManager"
+ "com.apple.RemotePairing.AuditActivityNotifications"
+ "com.apple.remotepairingdeviced.next_unlock"
+ "defaultSound"
+ "getNotificationSettingsWithCompletionHandler:"
+ "iconForSystemImageNamed:"
+ "initWithBundleIdentifier:"
+ "markNotificationPresented(id: "
+ "notificationPresented"
+ "notificationsEnabled"
+ "prefs:root=DEVELOPER_SETTINGS"
+ "prefs:root=DEVELOPER_SETTINGS&path=PAIRED_MACS/host/"
+ "recoverUnpresentedNotifications"
+ "remotepairingdeviced/DefaultPairingPolicyValidator.swift"
+ "requestAuthorizationWithOptions:completionHandler:"
+ "requestWithIdentifier:content:trigger:"
+ "setBody:"
+ "setCategoryIdentifier:"
+ "setDefaultActionURL:"
+ "setIcon:"
+ "setShouldAuthenticateDefaultAction:"
+ "setSound:"
+ "setTitle:"
+ "setWantsNotificationResponsesDelivered"
+ "triggerWithTimeInterval:repeats:"
+ "v16@?0@\"UNNotificationSettings\"8"
+ "v20@?0B8@\"NSError\"12"
- "%{public}s: Invalid state to handle pairing initiation request: %{public}s"
- "%{public}s: Unexpectedly received control channel invalidation for %s while in state unavailable"
- "Failed to fetch developer mode status: (%{public}s)"
- "State dump: NetworkPairingService connection count = %ld"
- "security.mac.amfi.developer_mode_status"
- "security.mac.amfi.developer_mode_status.changed"
```
