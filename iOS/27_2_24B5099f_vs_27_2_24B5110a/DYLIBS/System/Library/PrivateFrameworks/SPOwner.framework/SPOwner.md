## SPOwner

> `/System/Library/PrivateFrameworks/SPOwner.framework/SPOwner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x78078` | `0x78eac` | **`+0xe34`** |
| `__AUTH_CONST.__objc_const` | `0x143d0` | `0x145e0` | **`+0x210`** |
| `__TEXT.__cstring` | `0x6b49` | `0x6ca9` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x8078` | `0x81d8` | **`+0x160`** |
| `__TEXT.__objc_methlist` | `0xbc24` | `0xbd54` | **`+0x130`** |
| `__AUTH_CONST.__cfstring` | `0x5f00` | `0x6020` | **`+0x120`** |
| `__DATA_CONST.__objc_selrefs` | `0x3df8` | `0x3e80` | **`+0x88`** |
| `__DATA.__bss` | `0x800` | `0x880` | **`+0x80`** |
| `__AUTH.__objc_data` | `0x98` | `0xe8` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x2780` | `0x27d0` | **`+0x50`** |
| `__TEXT.__const` | `0x5b8` | `0x5f8` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x21b8` | `0x21e0` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0xbd8` | `0xbf8` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x148` | `0x168` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0xf1c` | `0xf34` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__DATA.__data` | `0x15c0` | `0x15c8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x600` | `0x608` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x450` | `0x458` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x380` | `0x388` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x133` | `0x139` | **`+0x6`** |
| `__TEXT.__swift5_proto` | `0x40` | `0x44` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x1c` | `0x20` | **`+0x4`** |

### Other Changes

```diff

-449.31.6.16.25
+449.31.6.16.29

-  Functions: 4423
-  Symbols:   7366
-  CStrings:  1583
+  Functions: 4454
+  Symbols:   7410
+  CStrings:  1606
Symbols:
+ +[SPCommand disableBTCSReflectorWithBeaconUUID:]
+ +[SPCommand enableBTCSReflectorWithBeaconUUID:withOptions:]
+ +[SPFindingSessionEvent supportsSecureCoding]
+ -[SPBTFindingSession didUpdateAccessoryStateCallback]
+ -[SPBTFindingSession setDidUpdateAccessoryStateCallback:]
+ -[SPBTFindingSession startBTCSForBeacon:completion:]
+ -[SPBTFindingSession stopBTCSForBeacon:completion:]
+ -[SPBTFindingSession updateAccessoryEvent:]
+ -[SPCommand antennaSelectionOption]
+ -[SPCommand initWithBeaconUUID:type:expiration:duration:playSoundContext:playSoundOptions:handle:lostModeEmail:lostModeMessage:lostModePhoneNumber:obfuscatedIdentifier:identifier:enableLostMode:antennaSelectionOptions:lockModePasscode:emailUpdates:]
+ -[SPCommand setAntennaSelectionOption:]
+ -[SPFindingSessionEvent .cxx_destruct]
+ -[SPFindingSessionEvent beaconID]
+ -[SPFindingSessionEvent copyWithZone:]
+ -[SPFindingSessionEvent description]
+ -[SPFindingSessionEvent encodeWithCoder:]
+ -[SPFindingSessionEvent event]
+ -[SPFindingSessionEvent initWithBeaconID:event:peripheralID:motionState:]
+ -[SPFindingSessionEvent initWithCoder:]
+ -[SPFindingSessionEvent motionState]
+ -[SPFindingSessionEvent peripheralID]
+ _OBJC_CLASS_$_SPFindingSessionEvent
+ _OBJC_IVAR_$_SPBTFindingSession._didUpdateAccessoryStateCallback
+ _OBJC_IVAR_$_SPCommand._antennaSelectionOption
+ _OBJC_IVAR_$_SPFindingSessionEvent._beaconID
+ _OBJC_IVAR_$_SPFindingSessionEvent._event
+ _OBJC_IVAR_$_SPFindingSessionEvent._motionState
+ _OBJC_IVAR_$_SPFindingSessionEvent._peripheralID
+ _OBJC_METACLASS_$_SPFindingSessionEvent
+ _SPBeaconTaskNameBTChannelSounding
+ _SPBeaconTaskNameDisableBTCSReflector
+ _SPBeaconTaskNameEnableBTCSReflector
+ __OBJC_$_CLASS_METHODS_SPFindingSessionEvent
+ __OBJC_$_CLASS_PROP_LIST_SPFindingSessionEvent
+ __OBJC_$_INSTANCE_METHODS_SPFindingSessionEvent
+ __OBJC_$_INSTANCE_VARIABLES_SPFindingSessionEvent
+ __OBJC_$_PROP_LIST_SPFindingSessionEvent
+ __OBJC_CLASS_PROTOCOLS_$_SPFindingSessionEvent
+ __OBJC_CLASS_RO_$_SPFindingSessionEvent
+ __OBJC_METACLASS_RO_$_SPFindingSessionEvent
+ ___43-[SPBTFindingSession updateAccessoryEvent:]_block_invoke
+ ___51-[SPBTFindingSession stopBTCSForBeacon:completion:]_block_invoke
+ ___51-[SPBTFindingSession stopBTCSForBeacon:completion:]_block_invoke_2
+ ___52-[SPBTFindingSession startBTCSForBeacon:completion:]_block_invoke
+ ___52-[SPBTFindingSession startBTCSForBeacon:completion:]_block_invoke_2
+ _symbolic _____ So25SPFindingSessionEventTypeV
- -[SPCommand initWithBeaconUUID:type:expiration:duration:playSoundContext:playSoundOptions:handle:lostModeEmail:lostModeMessage:lostModePhoneNumber:obfuscatedIdentifier:identifier:enableLostMode:lockModePasscode:emailUpdates:]
- ___51-[SPOwnerSessionLocationFetch invalidationHandler:]_block_invoke_2
CStrings:
+ "\r"
+ "-[SPBTCSFindingSession start]"
+ "-[SPBTCSFindingSession start] completion"
+ "-[SPBTCSFindingSession start] completion. Error %{public}@"
+ "-[SPBTCSFindingSession stop]"
+ "-[SPBTCSFindingSession stop] completion)"
+ "-[SPBTCSFindingSession stop] completion. Error %{public}@"
+ ".accessoryConnectedToCompanion"
+ ".accessoryInitiatedDisconnect"
+ ".motionStateUpdated"
+ ".peripheralConnected"
+ "<%@ %p: event: %d>"
+ "SPBTCSFindingSession.start"
+ "SPBTCSFindingSession.stop"
+ "antennaSelectionOption"
+ "beaconID"
+ "com.apple.icloud.spowner.task.btChannelSounding"
+ "com.apple.icloud.spowner.task.disableBTCSReflector"
+ "com.apple.icloud.spowner.task.enableBTCSReflector"
+ "event"
+ "motionState"
+ "peripheralID"
+ "updateAccessoryEvent() called from daemon"
```
