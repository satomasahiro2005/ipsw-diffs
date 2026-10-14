## ProximityControl

> `/System/Library/PrivateFrameworks/ProximityControl.framework/ProximityControl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b1e0` | `0x1d118` | **`+0x1f38`** |
| `__DATA.__bss` | `0x38a0` | `0x3d20` | **`+0x480`** |
| `__AUTH_CONST.__cfstring` | `0x11e0` | `0x14c0` | **`+0x2e0`** |
| `__TEXT.__const` | `0x1f34` | `0x21a4` | **`+0x270`** |
| `__AUTH_CONST.__objc_const` | `0x2da0` | `0x2ff0` | **`+0x250`** |
| `__TEXT.__cstring` | `0x1a3b` | `0x1c4b` | **`+0x210`** |
| `__TEXT.__objc_methlist` | `0x149c` | `0x1634` | **`+0x198`** |
| `__AUTH.__objc_data` | `0x9c0` | `0xb30` | **`+0x170`** |
| `__DATA_CONST.__const` | `0x4a0` | `0x5c0` | **`+0x120`** |
| `__AUTH_CONST.__const` | `0x1090` | `0x11a0` | **`+0x110`** |
| `__TEXT.__constg_swiftt` | `0x950` | `0xa60` | **`+0x110`** |
| `__TEXT.__eh_frame` | `0xa30` | `0xb40` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0xb58` | `0xc18` | **`+0xc0`** |
| `__DATA_DIRTY.__objc_data` | `0x550` | `0x5f0` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x792` | `0x81e` | **`+0x8c`** |
| `__AUTH.__data` | `0x3c8` | `0x448` | **`+0x80`** |
| `__DATA.__data` | `0xc08` | `0xc78` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0xaa8` | `0xb10` | **`+0x68`** |
| `__TEXT.__swift5_fieldmd` | `0x524` | `0x57c` | **`+0x58`** |
| `__TEXT.__swift5_assocty` | `0x140` | `0x180` | **`+0x40`** |
| `__TEXT.__swift5_proto` | `0x1c4` | `0x1e8` | **`+0x24`** |
| `__DATA.__common` | `0xa0` | `0xc0` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x17e` | `0x19e` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x758` | `0x770` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x54` | `0x6c` | **`+0x18`** |
| `__DATA.__objc_stublist` | `0x50` | `0x60` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x310` | `0x320` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xc0` | `0xd0` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x90` | `0xa0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xb0` | `0xc0` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x1c` | `0x24` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x24` | `0x2c` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x124` | `0x128` | **`+0x4`** |

### Other Changes

```diff

-376.10.31.0.0
+376.11.1.0.0

-  Functions: 1139
-  Symbols:   1357
-  CStrings:  255
+  Functions: 1238
+  Symbols:   1442
+  CStrings:  279
Symbols:
+ -[PCAlarmActivity hash]
+ -[PCAnnouncementActivity hash]
+ -[PCMediaActivity hash]
+ -[PCTelephonyActivity hash]
+ -[PCTelephonyActivity sourceAppID]
+ -[PCTimerActivity hash]
+ -[PCTimerActivity timerID]
+ -[PCUserActivity .cxx_destruct]
+ -[PCUserActivity activityString]
+ -[PCUserActivity bundleIdentifier]
+ -[PCUserActivity description]
+ -[PCUserActivity hash]
+ -[PCUserActivity image]
+ -[PCUserActivity initWithActivity:]
+ -[PCUserActivity initWithUserActivity:]
+ -[PCUserActivity isEqual:]
+ -[PCUserActivity isValid]
+ -[PCUserActivity pcactivityType]
+ -[PCUserActivity userActivity]
+ -[PCWeblinkActivity activityString]
+ -[PCWeblinkActivity bundleIdentifier]
+ -[PCWeblinkActivity description]
+ -[PCWeblinkActivity hash]
+ -[PCWeblinkActivity image]
+ -[PCWeblinkActivity initWithActivity:]
+ -[PCWeblinkActivity initWithURL:webpageData:isPrivateBrowsing:isPresentingFullScreenMedia:]
+ -[PCWeblinkActivity isEqual:]
+ -[PCWeblinkActivity isPresentingFullScreenMedia]
+ -[PCWeblinkActivity isPrivateBrowsing]
+ -[PCWeblinkActivity isValid]
+ -[PCWeblinkActivity pcactivityType]
+ -[PCWeblinkActivity webpageData]
+ -[PCWeblinkActivity webpageURL]
+ _OBJC_CLASS_$_PCUserActivity
+ _OBJC_CLASS_$_PCWeblinkActivity
+ _OBJC_CLASS_$__TtCO16ProximityControl36PCProximityHandoffServiceInvocations34ContinueUserActivityOnTargetDevice
+ _OBJC_CLASS_$__TtCO16ProximityControl36PCProximityHandoffServiceInvocations36ContinueUserActivityFromTargetDevice
+ _OBJC_IVAR_$_PCUserActivity._userActivity
+ _OBJC_METACLASS_$_PCUserActivity
+ _OBJC_METACLASS_$_PCWeblinkActivity
+ _OBJC_METACLASS_$__TtCO16ProximityControl36PCProximityHandoffServiceInvocations34ContinueUserActivityOnTargetDevice
+ _OBJC_METACLASS_$__TtCO16ProximityControl36PCProximityHandoffServiceInvocations36ContinueUserActivityFromTargetDevice
+ __CLASS_METHODS__TtCO16ProximityControl36PCProximityHandoffServiceInvocations34ContinueUserActivityOnTargetDevice
+ __CLASS_METHODS__TtCO16ProximityControl36PCProximityHandoffServiceInvocations36ContinueUserActivityFromTargetDevice
+ __CLASS_PROPERTIES__TtCO16ProximityControl36PCProximityHandoffServiceInvocations34ContinueUserActivityOnTargetDevice
+ __CLASS_PROPERTIES__TtCO16ProximityControl36PCProximityHandoffServiceInvocations36ContinueUserActivityFromTargetDevice
+ __DATA__TtCO16ProximityControl36PCProximityHandoffServiceInvocations34ContinueUserActivityOnTargetDevice
+ __DATA__TtCO16ProximityControl36PCProximityHandoffServiceInvocations36ContinueUserActivityFromTargetDevice
+ __INSTANCE_METHODS__TtCO16ProximityControl36PCProximityHandoffServiceInvocations34ContinueUserActivityOnTargetDevice
+ __INSTANCE_METHODS__TtCO16ProximityControl36PCProximityHandoffServiceInvocations36ContinueUserActivityFromTargetDevice
+ __METACLASS_DATA__TtCO16ProximityControl36PCProximityHandoffServiceInvocations34ContinueUserActivityOnTargetDevice
+ __METACLASS_DATA__TtCO16ProximityControl36PCProximityHandoffServiceInvocations36ContinueUserActivityFromTargetDevice
+ __OBJC_$_INSTANCE_METHODS_PCUserActivity
+ __OBJC_$_INSTANCE_METHODS_PCWeblinkActivity
+ __OBJC_$_INSTANCE_VARIABLES_PCUserActivity
+ __OBJC_$_PROP_LIST_PCUserActivity
+ __OBJC_CLASS_PROTOCOLS_$_PCUserActivity
+ __OBJC_CLASS_PROTOCOLS_$_PCWeblinkActivity
+ __OBJC_CLASS_RO_$_PCUserActivity
+ __OBJC_CLASS_RO_$_PCWeblinkActivity
+ __OBJC_METACLASS_RO_$_PCUserActivity
+ __OBJC_METACLASS_RO_$_PCWeblinkActivity
+ _associated conformance 16ProximityControl36PCProximityHandoffServiceInvocationsO34ContinueUserActivityOnTargetDeviceC10ParametersV10CodingKeys33_F22E9965162684EDE950A02C9B95EC3CLLOSHAASQ
+ _associated conformance 16ProximityControl36PCProximityHandoffServiceInvocationsO34ContinueUserActivityOnTargetDeviceC10ParametersV10CodingKeys33_F22E9965162684EDE950A02C9B95EC3CLLOs0N3KeyAAs23CustomStringConvertible
+ _associated conformance 16ProximityControl36PCProximityHandoffServiceInvocationsO34ContinueUserActivityOnTargetDeviceC10ParametersV10CodingKeys33_F22E9965162684EDE950A02C9B95EC3CLLOs0N3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 16ProximityControl36PCProximityHandoffServiceInvocationsO34ContinueUserActivityOnTargetDeviceC7Sharing22SFXPCInvocableProtocolAA10ParametersAfGP_SE
+ _associated conformance 16ProximityControl36PCProximityHandoffServiceInvocationsO34ContinueUserActivityOnTargetDeviceC7Sharing22SFXPCInvocableProtocolAA10ParametersAfGP_Se
+ _associated conformance 16ProximityControl36PCProximityHandoffServiceInvocationsO34ContinueUserActivityOnTargetDeviceC7Sharing22SFXPCInvocableProtocolAA8ResponseAfGP_SE
+ _associated conformance 16ProximityControl36PCProximityHandoffServiceInvocationsO34ContinueUserActivityOnTargetDeviceC7Sharing22SFXPCInvocableProtocolAA8ResponseAfGP_Se
+ _associated conformance 16ProximityControl36PCProximityHandoffServiceInvocationsO36ContinueUserActivityFromTargetDeviceC7Sharing22SFXPCInvocableProtocolAA10ParametersAfGP_SE
+ _associated conformance 16ProximityControl36PCProximityHandoffServiceInvocationsO36ContinueUserActivityFromTargetDeviceC7Sharing22SFXPCInvocableProtocolAA10ParametersAfGP_Se
+ _associated conformance 16ProximityControl36PCProximityHandoffServiceInvocationsO36ContinueUserActivityFromTargetDeviceC7Sharing22SFXPCInvocableProtocolAA8ResponseAfGP_SE
+ _associated conformance 16ProximityControl36PCProximityHandoffServiceInvocationsO36ContinueUserActivityFromTargetDeviceC7Sharing22SFXPCInvocableProtocolAA8ResponseAfGP_Se
+ _kProximityControlUserActivityActivityType
+ _kProximityControlWeblinkActivityType
+ _objc_retain_x26
+ _objc_retain_x27
+ _objc_retain_x28
+ _roundedFireDateInterval
+ _symbolic _____ 16ProximityControl36PCProximityHandoffServiceInvocationsO34ContinueUserActivityOnTargetDeviceC
+ _symbolic _____ 16ProximityControl36PCProximityHandoffServiceInvocationsO34ContinueUserActivityOnTargetDeviceC10ParametersV
+ _symbolic _____ 16ProximityControl36PCProximityHandoffServiceInvocationsO34ContinueUserActivityOnTargetDeviceC10ParametersV10CodingKeys33_F22E9965162684EDE950A02C9B95EC3CLLO
+ _symbolic _____ 16ProximityControl36PCProximityHandoffServiceInvocationsO36ContinueUserActivityFromTargetDeviceC
+ _symbolic _____y_____G s22KeyedDecodingContainerV 16ProximityControl36PCProximityHandoffServiceInvocationsO34ContinueUserActivityOnTargetDeviceC10ParametersV10CodingKeys33_F22E9965162684EDE950A02C9B95EC3CLLO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 16ProximityControl36PCProximityHandoffServiceInvocationsO34ContinueUserActivityOnTargetDeviceC10ParametersV10CodingKeys33_F22E9965162684EDE950A02C9B95EC3CLLO
+ _type_layout_string 16ProximityControl36PCProximityHandoffServiceInvocationsO34ContinueUserActivityOnTargetDeviceC10ParametersV
- _type_layout_string 16ProximityControl36PCProximityHandoffServiceInvocationsO14PairWithDeviceC10ParametersV
CStrings:
+ "<none>"
+ "<url>"
+ "ERROR_ACCESS_DENIED"
+ "ERROR_ANOTHER_USER_IS_ACTIVE"
+ "ERROR_APP_NOT_AVAILABLE"
+ "ERROR_DEVICE_LOCKED"
+ "ERROR_JOIN_SAME_NETWORK"
+ "ERROR_SAFARI_EMPTY_TAB"
+ "ERROR_TELEPHONY_NOT_SUPPORTED"
+ "ERROR_USER_NOT_RECOGNIZED"
+ "Localizable-J490"
+ "OPEN_IN_APP"
+ "OPEN_ON_DEVICE"
+ "Unsupported for this activity type."
+ "WEBLINK"
+ "com.apple.ProximityControl.activity.useractivity"
+ "com.apple.ProximityControl.activity.webpageURL"
+ "com.apple.mobilesafari"
+ "isPresentingFullScreenMedia"
+ "isPrivateBrowsing"
+ "targetDevicePredicate"
+ "timerID"
+ "webpageData"
+ "webpageURL"
```
