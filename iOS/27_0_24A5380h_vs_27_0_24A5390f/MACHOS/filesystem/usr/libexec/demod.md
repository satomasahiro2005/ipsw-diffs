## demod

> `/usr/libexec/demod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf43d4` | `0xf66fc` | **`+0x2328`** |
| `__TEXT.__objc_methname` | `0x20de1` | `0x21321` | **`+0x540`** |
| `__TEXT.__oslogstring` | `0x1c93c` | `0x1cc3c` | **`+0x300`** |
| `__TEXT.__objc_stubs` | `0x1b480` | `0x1b6c0` | **`+0x240`** |
| `__TEXT.__objc_methlist` | `0xd944` | `0xdb24` | **`+0x1e0`** |
| `__TEXT.__cstring` | `0x10bb2` | `0x10d22` | **`+0x170`** |
| `__DATA.__objc_selrefs` | `0x80c0` | `0x8200` | **`+0x140`** |
| `__DATA.__objc_const` | `0x19710` | `0x19828` | **`+0x118`** |
| `__TEXT.__eh_frame` | `0x310` | `0x3d0` | **`+0xc0`** |
| `__TEXT.__objc_methtype` | `0x3fdb` | `0x409b` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x31c0` | `0x3260` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x46bc` | `0x4750` | **`+0x94`** |
| `__TEXT.__unwind_info` | `0x3a28` | `0x3ab8` | **`+0x90`** |
| `__DATA.__data` | `0x2990` | `0x29f8` | **`+0x68`** |
| `__DATA_CONST.__cfstring` | `0xec40` | `0xeca0` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x20b0` | `0x2110` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x94` | `0xcc` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x1068` | `0x1098` | **`+0x30`** |
| `__TEXT.__const` | `0x510` | `0x530` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x186a` | `0x188a` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x180` | `0x190` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xf10` | `0xf20` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x20` | `0x2c` | **`+0xc`** |
| `__DATA_CONST.__objc_protolist` | `0x160` | `0x168` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xb34` | `0xb38` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x20` | `0x24` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x28` | `0x2c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1871.0.29.0.0
+1871.0.42.0.0

-  Functions: 6048
-  Symbols:   1048
-  CStrings:  10853
+  Functions: 6088
+  Symbols:   1056
+  CStrings:  10924
Symbols:
+ _$s16GenerativeModels0aB12AvailabilityV12enhancedSiriAC0C0OvgZ
+ _$s16GenerativeModels0aB12AvailabilityV19enhancedSiriChangesAC08EnhancedE14ChangeSequenceVvgZ
+ _$s16GenerativeModels0aB12AvailabilityV26EnhancedSiriChangeSequenceV17makeAsyncIteratorAE0J0VyF
+ _$s16GenerativeModels0aB12AvailabilityV26EnhancedSiriChangeSequenceV8IteratorVMa
+ _$s16GenerativeModels0aB12AvailabilityV26EnhancedSiriChangeSequenceV8IteratorVScIAAMc
+ _$s16GenerativeModels0aB12AvailabilityV26EnhancedSiriChangeSequenceVMa
+ _OBJC_CLASS_$_AFSiriAvailability
+ _dispatch_group_async
+ _swift_retain_x23
- _swift_retain_x19
CStrings:
+ "%s - %{bool}d"
+ "%s - Error reading availability from AFSiriAvailability"
+ "%s - Start waitForGMAvailability"
+ "%s was called. HS set to '%@'"
+ "+[MSDGreyMatterAvailabilityChecker waitForSiriAIAvailability]"
+ "+[MSDGreyMatterOpter isSiriAIOptedIn]"
+ "+[MSDGreyMatterOpter migrateOptInValue]"
+ "-[MSDHomeManager _handleHeySiriSetting:]"
+ "/private/var/mnt/com.apple.mobilestoredemo.storage/com.apple.mobilestoredemo.blob/Metadata/com.apple.MobileStoreDemo.homekitkeychain"
+ "Device is not eligible for Siri AI."
+ "Failed to load HomeKit pairing keychain info from demo volume."
+ "Failed to save HomeKit pairing keychain info to demo volume."
+ "HMHomeManagerDelegatePrivate"
+ "MSDKeychainSaver"
+ "No need to restore HomeKit pairing record."
+ "Not all Siri support apps downloaded in the given time interval"
+ "Refusing to lock home based on home unlock feature flag"
+ "Restoring HomeKit pairing information to keychain."
+ "Saving HomeKit pairing info stored in keychain."
+ "Siri AI is already available: %s"
+ "Siri AI is not available: %s Waiting for Siri AI availability."
+ "Siri AI is now available."
+ "Siri Support App(s) %@ failed to install"
+ "TB,V_siriOn"
+ "Timed out after %d minutes waiting for Siri AI availability."
+ "Toggled HS/JS for accessory with UUID %{public}@"
+ "_handleHeySiriSetting:"
+ "_siriOn"
+ "checkSiriAIAvailabilityWithCompletion:"
+ "com.apple.SiriApp"
+ "com.apple.hap.pairing"
+ "currentHome"
+ "desiredOrchestrationMode"
+ "fromPreferences"
+ "getAppleIntelligenceAppsToWaitFor"
+ "homeManager:didRemoveHomePermanently:"
+ "homeManager:didUpdateAccessAllowedWhenLocked:"
+ "homeManager:didUpdateDevices:"
+ "homeManager:didUpdateHH2MigrationAvailableState:"
+ "homeManager:didUpdateHH2MigrationInProgressState:"
+ "homeManager:didUpdateHH2State:"
+ "homeManager:didUpdateHomeSafetySecurityEnabled:"
+ "homeManager:didUpdateMultiUserStatus:reason:"
+ "homeManager:didUpdateResidentEnabledForThisDevice:"
+ "homeManager:didUpdateStateForIncomingInvitations:"
+ "homeManager:didUpdateStatus:"
+ "homeManager:didUpdateThisDeviceIsResidentCapable:"
+ "homeManager:residentProvisioningStatusChanged:"
+ "homeManagerDidEndBatchNotifications:"
+ "homeManagerDidRemoveCurrentAccessory:"
+ "homeManagerDidUpdateApplicationData:"
+ "homeManagerDidUpdateAssistantIdentifiers:"
+ "homeManagerDidUpdateCurrentHome:"
+ "homeManagerDidUpdateDataSyncInProgress:"
+ "homeManagerDidUpdateDataSyncState:"
+ "homeManagerWillStartBatchNotifications:"
+ "isEligibleForSiriAI"
+ "isSiriAIOptedIn"
+ "listenForSiri"
+ "preserveHomeKitPairingRecord"
+ "removeHomeKitPairingIfNeeded"
+ "restoreHomeKitPairingRecordIfNeeded"
+ "setAppleIntelligenceFallback:"
+ "setIsSiriAIOptedIn:"
+ "setSiriOn:"
+ "shouldRestoreHomeKitPairingRecord"
+ "siriOn"
+ "v28@0:8@\"HMHomeManager\"16B24"
+ "v32@0:8@\"HMHomeManager\"16@\"NSArray\"24"
+ "v32@0:8@\"HMHomeManager\"16@\"NSSet\"24"
+ "v32@0:8@\"HMHomeManager\"16@\"NSUUID\"24"
+ "v40@0:8@\"HMHomeManager\"16q24@\"NSString\"32"
+ "waitForAppleIntelligenceAvailability"
+ "waitForSiriAIAvailability"
- "Disabled HS/JS for accessory with UUID %{public}@"
- "Image Playground failed to install"
- "MSDContinuityHelper"
```
