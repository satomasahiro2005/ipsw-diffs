## AXUltronPluginService

> `/System/Library/AccessibilityBundles/AXUltronPluginService.axuiservice/AXUltronPluginService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x390c` | `0x43dc` | **`+0xad0`** |
| `__TEXT.__objc_methname` | `0xcaf` | `0x106e` | **`+0x3bf`** |
| `__TEXT.__objc_stubs` | `0x8e0` | `0xba0` | **`+0x2c0`** |
| `__TEXT.__oslogstring` | `0x545` | `0x74a` | **`+0x205`** |
| `__DATA.__objc_selrefs` | `0x390` | `0x480` | **`+0xf0`** |
| `__TEXT.__objc_methlist` | `0x42c` | `0x4fc` | **`+0xd0`** |
| `__DATA.__objc_const` | `0x4a0` | `0x568` | **`+0xc8`** |
| `__DATA_CONST.__cfstring` | `0xa0` | `0x120` | **`+0x80`** |
| `__DATA.__data` | `0x188` | `0x1e8` | **`+0x60`** |
| `__DATA_CONST.__got` | `0xd8` | `0x130` | **`+0x58`** |
| `__TEXT.__auth_stubs` | `0x5e0` | `0x630` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x10c` | `0x144` | **`+0x38`** |
| `__TEXT.__objc_methtype` | `0x3d9` | `0x404` | **`+0x2b`** |
| `__DATA_CONST.__auth_got` | `0x300` | `0x328` | **`+0x28`** |
| `__DATA_CONST.__objc_dictobj` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x198` | `0x1b8` | **`+0x20`** |
| `__TEXT.__cstring` | `0xd3` | `0xef` | **`+0x1c`** |
| `__TEXT.__objc_classname` | `0x81` | `0x95` | **`+0x14`** |
| `__DATA_CONST.__objc_arraydata` | `—` | `0x10` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x18` | `0x24` | **`+0xc`** |
| `__DATA_CONST.__objc_protolist` | `0x18` | `0x20` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
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

-  Functions: 94
-  Symbols:   143
-  CStrings:  224
+  Functions: 108
+  Symbols:   161
+  CStrings:  275
Symbols:
+ _AXIDSServiceDeviceNRIdentifierKey
+ _AXIDSServiceDeviceNearbyStatusKey
+ _AXIDSServiceMessageKey
+ _AXSDSoundDetectionGenerateUserNotificationForDetectionTypeFromSource
+ _AXSDSoundDetectionMessageKeyConfidence
+ _AXSDSoundDetectionMessageKeyType
+ _NRDevicePropertyHWModelString
+ _OBJC_CLASS_$_AXIDSServices
+ _OBJC_CLASS_$_NRPairedDeviceRegistry
+ _OBJC_CLASS_$_NSConstantDictionary
+ _OBJC_CLASS_$_NSMutableDictionary
+ _OBJC_CLASS_$_NSUUID
+ ___NSArray0__struct
+ ___kCFBooleanTrue
+ _objc_alloc
+ _objc_opt_isKindOfClass
+ _objc_retain_x23
+ _objc_unsafeClaimAutoreleasedReturnValue
CStrings:
+ "@\"NSMutableDictionary\""
+ "AXIDSServicesClient"
+ "IDS server connection interrupted — clearing stale wrist state"
+ "T@\"NSArray\",&,N,V_connectedDevices"
+ "T@\"NSMutableDictionary\",&,N,V_watchActiveWristState"
+ "TB,N,V_hasPendingWristStateRequest"
+ "UPDATING: _watchActiveWristState: %@, deviceID:%@"
+ "Watch SR: nearby supported watch found but wrist state unknown — requesting state, phone continues listening"
+ "WatchOS sound recognition forwarding changed"
+ "[%@]: Sound detection delegated to Watch — syncing all keys to companion"
+ "[%@]: Watch is actively listening — iPhone stopped with %lu enabled sounds synced"
+ "[%@]: iPhone should stop listening for watch forwarding."
+ "_connectedDevices"
+ "_hasConnectedWatchWithSoundRecognitionSupport"
+ "_hasPendingWristStateRequest"
+ "_requestWatchWristState"
+ "_shouldPhoneBeListening"
+ "_shouldStopSoundDetectionForWatchCoordination:"
+ "_watchActiveWristState"
+ "allowForwardingSoundRecognitionToSupportedWatch"
+ "boolValue"
+ "bridgeSettings"
+ "connectedDevices"
+ "connectedDevicesDidChange:"
+ "connectedDevicesDidChange: %@"
+ "deviceForBluetoothID:"
+ "dictionary"
+ "didReceiveIncomingData:"
+ "doubleValue"
+ "hasPendingWristStateRequest"
+ "hasPrefix:"
+ "initWithUUIDString:"
+ "lowercaseString"
+ "n237"
+ "n238"
+ "n240"
+ "objectForKeyedSubscript:"
+ "onWristState"
+ "overrideSupportWatchSoundRecognition"
+ "publishMessage:priority:requestingResponse:"
+ "registerForIncomingData:"
+ "removeAllObjects"
+ "serverConnectionWasInterrupted"
+ "setConnectedDevices:"
+ "setHasPendingWristStateRequest:"
+ "setObject:forKeyedSubscript:"
+ "setWatchActiveWristState:"
+ "syncAllKeysToCompanion"
+ "v24@0:8@\"NSArray\"16"
+ "valueForProperty:"
+ "watchActiveWristState"
```
