## BuddyMigrator

> `/System/Library/DataClassMigrators/BuddyMigrator.migrator/BuddyMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x267ec` | `0x284c0` | **`+0x1cd4`** |
| `__TEXT.__objc_methname` | `0x4155` | `0x4aad` | **`+0x958`** |
| `__TEXT.__objc_stubs` | `0x2ac0` | `0x2fe0` | **`+0x520`** |
| `__TEXT.__objc_methtype` | `0x884` | `0xc96` | **`+0x412`** |
| `__DATA.__objc_const` | `0x34b0` | `0x38b8` | **`+0x408`** |
| `__TEXT.__objc_methlist` | `0x17f8` | `0x1b08` | **`+0x310`** |
| `__DATA.__objc_selrefs` | `0xe98` | `0x10a8` | **`+0x210`** |
| `__TEXT.__oslogstring` | `0x2b11` | `0x2c8d` | **`+0x17c`** |
| `__DATA.__objc_data` | `0x1728` | `0x1828` | **`+0x100`** |
| `__DATA_CONST.__const` | `0xfe0` | `0x1078` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0xb48` | `0xbe0` | **`+0x98`** |
| `__DATA.__data` | `0x1038` | `0x10c0` | **`+0x88`** |
| `__TEXT.__objc_classname` | `0xd0b` | `0xd7a` | **`+0x6f`** |
| `__TEXT.__cstring` | `0xf85` | `0xfeb` | **`+0x66`** |
| `__TEXT.__auth_stubs` | `0x1070` | `0x10c0` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x438` | `0x480` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x9e0` | `0xa0c` | **`+0x2c`** |
| `__DATA.__objc_ivar` | `0xe8` | `0x110` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x848` | `0x870` | **`+0x28`** |
| `__TEXT.__const` | `0xd50` | `0xd78` | **`+0x28`** |
| `__DATA.__bss` | `0x630` | `0x650` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0xac0` | `0xae0` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0xb38` | `0xb4e` | **`+0x16`** |
| `__DATA_CONST.__objc_classlist` | `0x140` | `0x150` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2a8` | `0x2b8` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x5c8` | `0x5d8` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x4c6` | `0x4ba` | **`-0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x188` | `0x190` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x138` | `0x140` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x38` | `0x40` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x78` | `0x7c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5405.0.0.0.0
+5407.0.0.0.0

+  - /System/Library/Frameworks/CoreServices.framework/CoreServices
+  - /System/Library/Frameworks/CoreTelephony.framework/CoreTelephony

+  - /System/Library/PrivateFrameworks/MobileActivation.framework/MobileActivation

-  Functions: 860
-  Symbols:   403
-  CStrings:  1121
+  Functions: 918
+  Symbols:   416
+  CStrings:  1254
Symbols:
+ _CFNotificationCenterAddObserver
+ _CFNotificationCenterGetDarwinNotifyCenter
+ _LSUserApplicationType
+ _MAEGetActivationStateWithError
+ _OBJC_CLASS_$_BuddyActivationConfiguration
+ _OBJC_CLASS_$_CoreTelephonyClient
+ _OBJC_CLASS_$_LSApplicationIdentity
+ _OBJC_CLASS_$_LSApplicationRecord
+ _OBJC_CLASS_$_NSMutableSet
+ _OBJC_METACLASS_$_BuddyActivationConfiguration
+ _kMAActivationStateUnactivated
+ _objc_enumerationMutation
+ _swift_release_x28
CStrings:
+ "&"
+ "@\"CoreTelephonyClient\""
+ "@\"NSMutableSet\""
+ "Activation Configuration Delegates Queue"
+ "Activation State Queue"
+ "B24@0:8Q16"
+ "BuddyActivationConfiguration"
+ "BuddyMigrator: Persisting initial app state for partial-setup detection"
+ "CoreTelephonyClientDataDelegate"
+ "Failed to get activation state: %{public}@"
+ "Supports Cellular Activation: %d (method is %ld)"
+ "T@\"CoreTelephonyClient\",&,V_telephonyClient"
+ "T@\"NSMutableSet\",&,V_delegates"
+ "T@\"NSObject<OS_dispatch_queue>\",&,N,V_activationStateQueue"
+ "T@\"NSObject<OS_dispatch_queue>\",&,V_delegateQueue"
+ "T@\"NSObject<OS_dispatch_queue>\",&,V_telephonyQueue"
+ "TB,N,V_hasActivated"
+ "TB,N,V_initialActivationState"
+ "TB,R"
+ "TB,R,GisActivated"
+ "TB,V_activationMethodChanged"
+ "TQ,N,V_cellularActivationMethod"
+ "Telephony Queue"
+ "Unable to get availability status to see if cellular activation is supported: %{public}@"
+ "Unable to get bootstrap status to see if cellular activation is supported: %{public}@"
+ "Updating cellular activation method..."
+ "_TtC13BuddyMigrator20BuddyAppStateManager"
+ "_activationMethodChanged"
+ "_activationStateChanged"
+ "_activationStateQueue"
+ "_cellularActivationMethod"
+ "_delegateQueue"
+ "_delegates"
+ "_hasActivated"
+ "_initialActivationState"
+ "_registerForActivationStateNotification"
+ "_supportsCellularActivationForMethod:"
+ "_telephonyClient"
+ "_telephonyQueue"
+ "activated"
+ "activationConfigurationChanged:isActivated:"
+ "activationMethodChanged"
+ "activationStateQueue"
+ "addDelegate:"
+ "addObject:"
+ "anbrActivationState:enabled:"
+ "anbrBitrateRecommendation:bitrate:direction:"
+ "available"
+ "cellularActivationMethod"
+ "com.apple.mobile.lockdown.activation_state"
+ "connectionActivationError:connection:error:"
+ "connectionAvailability:availableConnections:"
+ "connectionStateChanged:connection:dataConnectionStatusInfo:"
+ "countByEnumeratingWithState:objects:count:"
+ "currentAppStates"
+ "currentDataServiceDescriptorChanged:"
+ "currentDataSimChanged:"
+ "dataRoamingSettingsChanged:status:"
+ "dataSettingsChanged:"
+ "dataStatus:dataStatusInfo:"
+ "delegateQueue"
+ "delegates"
+ "enumeratorWithOptions:"
+ "getConnectionAvailability:connectionType:error:"
+ "hasActivated"
+ "identities"
+ "identityString"
+ "initWithBuddyPreferencesExcludedFromBackup:"
+ "initWithQueue:"
+ "initialActivationState"
+ "internetConnectionActivationError:"
+ "internetConnectionAvailability:"
+ "internetConnectionStateChanged:"
+ "internetDataStatus:"
+ "internetDataStatusBasic:"
+ "isActivated"
+ "nextObject"
+ "notifyDelegatesConfigurationChanged:"
+ "notifyDelegatesConfigurationChanged:isActivated:"
+ "nrSliceAppStateChanged:status:trafficDescriptors:"
+ "nrSlicedRunningAppStateChanged:"
+ "persist:to:"
+ "preferredDataServiceDescriptorChanged:"
+ "preferredDataSimChanged:"
+ "pttSlicingCapabilityDidChange:"
+ "regDataModeChanged:dataMode:"
+ "removeDelegate:"
+ "removeObject:"
+ "serviceDisconnection:status:"
+ "servingNetworkChanged:"
+ "setActivationMethodChanged:"
+ "setActivationStateQueue:"
+ "setCellularActivationMethod:"
+ "setDelegateQueue:"
+ "setDelegates:"
+ "setHasActivated:"
+ "setInitialActivationState:"
+ "setTelephonyClient:"
+ "setTelephonyQueue:"
+ "supportsCellularActivation"
+ "telephonyClient"
+ "telephonyQueue"
+ "tetheringStatus:"
+ "tetheringStatus:connectionType:"
+ "typeForInstallMachinery"
+ "uniqueInstallIdentifier"
+ "usingBootstrapDataService:"
+ "v20@0:8i16"
+ "v24@0:8@\"CTDataConnectionStatus\"16"
+ "v24@0:8@\"CTDataSettings\"16"
+ "v24@0:8@\"CTDataStatus\"16"
+ "v24@0:8@\"CTDataStatusBasic\"16"
+ "v24@0:8@\"CTServiceDescriptor\"16"
+ "v24@0:8@\"CTSlicedRunningAppInfoContainer\"16"
+ "v24@0:8@\"CTTetheringStatus\"16"
+ "v24@0:8@\"CTXPCServiceSubscriptionContext\"16"
+ "v24@0:8@\"NSDictionary\"16"
+ "v24@0:8B16B20"
+ "v28@0:8@\"CTServiceDescriptor\"16B24"
+ "v28@0:8@\"CTTetheringStatus\"16i24"
+ "v28@0:8@\"CTXPCServiceSubscriptionContext\"16B24"
+ "v28@0:8@\"CTXPCServiceSubscriptionContext\"16i24"
+ "v28@0:8@16B24"
+ "v28@0:8@16i24"
+ "v32@0:8@\"CTXPCServiceSubscriptionContext\"16@\"CTDataStatus\"24"
+ "v32@0:8@\"CTXPCServiceSubscriptionContext\"16@\"CTServiceDisconnectionStatus\"24"
+ "v32@0:8@\"CTXPCServiceSubscriptionContext\"16@\"NSArray\"24"
+ "v32@0:8@\"CTXPCServiceSubscriptionContext\"16i24i28"
+ "v32@0:8@16@24"
+ "v32@0:8@16i24i28"
+ "v36@0:8@\"CTXPCServiceSubscriptionContext\"16@\"NSNumber\"24i32"
+ "v36@0:8@\"CTXPCServiceSubscriptionContext\"16i24@\"CTDataConnectionStatus\"28"
+ "v36@0:8@\"NSString\"16B24@\"CTTrafficDescriptorsContainer\"28"
+ "v36@0:8@16@24i32"
+ "v36@0:8@16B24@28"
+ "v36@0:8@16i24@28"
- "isNewMandatorySUFlowEnabled"
- "isNewMigrationSUFlowEnabled"
- "isNewRestoreSUFlowEnabled"
```
