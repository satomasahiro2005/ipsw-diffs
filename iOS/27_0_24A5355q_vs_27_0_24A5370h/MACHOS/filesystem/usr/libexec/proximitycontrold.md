## proximitycontrold

> `/usr/libexec/proximitycontrold`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x266a70` | `0x265aec` | **`-0xf84`** |
| `__DATA.__objc_const` | `0x17ed0` | `0x18930` | **`+0xa60`** |
| `__TEXT.__eh_frame` | `0x6b44` | `0x6704` | **`-0x440`** |
| `__DATA.__data` | `0x17838` | `0x17c68` | **`+0x430`** |
| `__TEXT.__const` | `0x21328` | `0x21648` | **`+0x320`** |
| `__TEXT.__swift5_reflstr` | `0x9703` | `0x99b3` | **`+0x2b0`** |
| `__TEXT.__swift5_fieldmd` | `0x90f4` | `0x9360` | **`+0x26c`** |
| `__TEXT.__swift5_typeref` | `0xeef2` | `0xf156` | **`+0x264`** |
| `__TEXT.__objc_methname` | `0xdd19` | `0xdf29` | **`+0x210`** |
| `__TEXT.__constg_swiftt` | `0xd62c` | `0xd7e4` | **`+0x1b8`** |
| `__TEXT.__oslogstring` | `0x805e` | `0x7eae` | **`-0x1b0`** |
| `__DATA_CONST.__const` | `0x15328` | `0x15480` | **`+0x158`** |
| `__TEXT.__objc_classname` | `0x22c7` | `0x2407` | **`+0x140`** |
| `__DATA.__bss` | `0x2bb50` | `0x2bc60` | **`+0x110`** |
| `__DATA.__objc_data` | `0x3880` | `0x3910` | **`+0x90`** |
| `__TEXT.__objc_stubs` | `0x42a0` | `0x4220` | **`-0x80`** |
| `__TEXT.__cstring` | `0x7d49` | `0x7d99` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x34cc` | `0x347c` | **`-0x50`** |
| `__TEXT.__objc_methtype` | `0x36a2` | `0x36db` | **`+0x39`** |
| `__DATA.__objc_selrefs` | `0x1de0` | `0x1da8` | **`-0x38`** |
| `__DATA_CONST.__got` | `0xee0` | `0xea8` | **`-0x38`** |
| `__TEXT.__swift_as_cont` | `0x1fc` | `0x1cc` | **`-0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x1a38` | `0x1a60` | **`+0x28`** |
| `__DATA_CONST.__objc_classlist` | `0x450` | `0x478` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x480` | `0x460` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x3660` | `0x3640` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x6c50` | `0x6c30` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0x17bc` | `0x17d8` | **`+0x1c`** |
| `__TEXT.__swift5_types` | `0x8a4` | `0x8c0` | **`+0x1c`** |
| `__TEXT.__swift5_assocty` | `0xeb8` | `0xed0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x58c` | `0x5a0` | **`+0x14`** |
| `__TEXT.__swift5_protos` | `0x130` | `0x144` | **`+0x14`** |
| `__DATA_CONST.__auth_got` | `0x1b38` | `0x1b28` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x104` | `0xf4` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0xf4` | `0xe4` | **`-0x10`** |
| `__DATA.__common` | `0x8a0` | `0x8a8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-374.0.0.0.0
+376.0.6.0.0

+  - /System/Library/Frameworks/CoreMotion.framework/CoreMotion

-  Functions: 10306
-  Symbols:   1653
-  CStrings:  4151
+  Functions: 10340
+  Symbols:   1646
+  CStrings:  4184
Symbols:
+ _$sSo24OS_dispatch_source_timerP8DispatchE8schedule8deadline9repeating6leewayyAC0E4TimeV_AC0eJ8IntervalOAKtF
+ _$ss4Int8VMn
+ _CFPreferencesCopyAppValue
+ _OBJC_CLASS_$_CMMotionActivityManager
+ _OBJC_CLASS_$_NSOperationQueue
- _$s7Sharing26SFProximityHandoffUIClientC020registerForProximityC18InteractionUpdates10completionyys5Error_pSgXE_tF
- _$s7Sharing26SFProximityHandoffUIClientC19invalidationHandleryycSgvs
- _$s7Sharing26SFProximityHandoffUIClientC8activateyyKF
- _OBJC_CLASS_$_RBSAssertion
- _OBJC_CLASS_$_RBSAttribute
- _OBJC_CLASS_$_RBSDomainAttribute
- _OBJC_CLASS_$_RBSProcessHandle
- _OBJC_CLASS_$_RBSProcessPredicate
- _OBJC_CLASS_$_RBSTarget
- _OBJC_CLASS_$_UIMutableApplicationSceneClientSettings
- _UIHUDWindowLevel
- _swift_retain_x11
CStrings:
+ "### Already activated"
+ "%s: hasMappedDevices=%{bool}d, includesNewDevice=%{bool}d"
+ "Aggressive"
+ "AggressiveOld"
+ "Background"
+ "BackgroundOld"
+ "BluetoothProxyState_isHandoffCandidateNearby"
+ "BluetoothProxyState_isRangingCandidateNearby"
+ "High"
+ "HighNormal"
+ "HighOld"
+ "Invalid"
+ "Motion monitor start"
+ "Motion monitor stop"
+ "Normal"
+ "NormalOld"
+ "Pref BLE scan secs: %f → %f"
+ "Pref HighNormal: %{bool}d → %{bool}d"
+ "Resetting scan timer (external request)"
+ "Scan rate: %s → %s"
+ "Scan timer activate (%fs)"
+ "Scan timer fired"
+ "Scan timer invalidate"
+ "Screen: %s"
+ "Stationary: %{bool}d → %{bool}d"
+ "_TtC17proximitycontrold13CFPrefsSource"
+ "_TtC17proximitycontrold20RBSAssertionProvider"
+ "_TtC17proximitycontrold21CUSystemMonitorSource"
+ "_TtC17proximitycontrold23DispatchSourceScanTimer"
+ "_TtC17proximitycontrold31ProximityHandoffUIClientWrapper"
+ "_TtC17proximitycontrold32BluetoothProximityScanRatePolicy"
+ "_hasPrewarmedPrototypesCapableDevice"
+ "activeSceneIDs"
+ "assertionHeld"
+ "assertionProvider"
+ "bluetoothProxyState"
+ "changeHandler"
+ "clientFactory"
+ "com.apple.Sharing.prefsChanged"
+ "com.apple.sharing.airdropui"
+ "confidence"
+ "currentScanRate"
+ "discoveryFactory"
+ "hasInteractions"
+ "hasMappedDevices"
+ "invalidated"
+ "mainQueue"
+ "mappedDevicesChanged(hasMappedDevices:includesNewDevice:)"
+ "motionManager"
+ "motionStarted"
+ "policyFactory"
+ "prefHighNormal"
+ "prefs"
+ "prewarmDeactivateDelay"
+ "proximitycontrold.BluetoothProximityScanRatePolicy"
+ "qualifyingCBDeviceIdentifiers"
+ "scanRate"
+ "scanRateChangedHandler"
+ "scanRatePolicy"
+ "scanTimedOut"
+ "scanTimeoutInterval"
+ "scanTimer"
+ "screen"
+ "sessionFactory"
+ "somePrewarmedPrototypesCapableDeviceNearby"
+ "startActivityUpdatesToQueue:withHandler:"
+ "stationary"
+ "stopActivityUpdates"
+ "timerFactory"
+ "underlying"
+ "v16@?0@\"CMMotionActivity\"8"
- " receives ProximityHandoff-state-change messages"
- "### Failed to launch %s: %@"
- "### Failed to take assertion on %s ensuring it is active: %@"
- "### ProximityHandoffUIClient: activate failed: %@"
- "### ProximityHandoffUIClient: register failed: %@"
- "Ignoring non-communal device."
- "Invalidated assertion"
- "Not launching %s because ProximityHandoffUIClient already exists"
- "Not releasing assertion to ensure %s is active because no assertion exists"
- "Not taking assertion to ensure %s is active because assertion was already taken"
- "Not taking assertion to ensure %s is active because service is no longer active"
- "PCApplication"
- "ProximityHandoffUIClient: activate succeeded"
- "ProximityHandoffUIClient: invalidated"
- "ProximityHandoffUIClient: invalidated, reconnecting..."
- "ProximityHandoffUIClient: register succeeded"
- "Successfully acquired assertion"
- "[Internal] Please update the target device to a more recent build to continue using this feature."
- "_activeSceneIDs"
- "_isSystemUIService"
- "_systemUIServiceClientSettings"
- "_systemUIServiceIdentifier"
- "acquireWithError:"
- "attributeWithDomain:name:"
- "com.apple.Sharing.AirDropUI"
- "com.apple.sharing.airdrop"
- "ensureUIProcessIsActive()"
- "handleForPredicate:error:"
- "identity"
- "initWithExplanation:target:attributes:"
- "launchUIProcess(completion:)"
- "predicateMatchingBundleIdentifier:"
- "proximityHandoffInteractions updated: %ld interactions"
- "releaseUIProcessAssertion()"
- "setPreferredLevel:"
- "settings"
- "takeUIProcessAssertion()"
- "targetWithProcessIdentity:"
```
