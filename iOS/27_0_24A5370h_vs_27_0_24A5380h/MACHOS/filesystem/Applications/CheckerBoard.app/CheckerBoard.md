## CheckerBoard

> `/Applications/CheckerBoard.app/CheckerBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x1a94` | `0x1c14` | **`+0x180`** |
| `__TEXT.__text` | `0x600b0` | `0x6017c` | **`+0xcc`** |
| `__TEXT.__eh_frame` | `0x2a4` | `0x26c` | **`-0x38`** |
| `__DATA_CONST.__got` | `0xa28` | `0xa58` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x393d` | `0x396d` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x1ee8` | `0x1f08` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x15f0` | `0x1608` | **`+0x18`** |
| `__DATA.__bss` | `0xd88` | `0xd98` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1ed0` | `0x1ec0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0xf78` | `0xf70` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x2044` | `0x203e` | **`-0x6`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-282.0.0.0.0
+287.0.0.0.0

-  Functions: 2445
-  Symbols:   975
-  CStrings:  4095
+  Functions: 2449
+  Symbols:   971
+  CStrings:  4096
Symbols:
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "{?=\"itemIsEnabled\"[46B]\"timeString\"[64c]\"shortTimeString\"[64c]\"dateString\"[256c]\"gsmSignalStrengthRaw\"i\"secondaryGsmSignalStrengthRaw\"i\"gsmSignalStrengthBars\"i\"secondaryGsmSignalStrengthBars\"i\"serviceString\"[100c]\"secondaryServiceString\"[100c]\"serviceCrossfadeString\"[100c]\"secondaryServiceCrossfadeString\"[100c]\"serviceImages\"[2[100c]]\"operatorDirectory\"[1024c]\"serviceContentType\"I\"secondaryServiceContentType\"I\"cellLowDataModeActive\"b1\"secondaryCellLowDataModeActive\"b1\"wifiSignalStrengthRaw\"i\"wifiSignalStrengthBars\"i\"wifiLowDataModeActive\"b1\"dataNetworkType\"I\"secondaryDataNetworkType\"I\"batteryCapacity\"i\"batteryState\"I\"batteryDetailString\"[150c]\"bluetoothBatteryCapacity\"i\"thermalColor\"i\"thermalSunlightMode\"b1\"slowActivity\"b1\"syncActivity\"b1\"activityDisplayId\"[256c]\"bluetoothConnected\"b1\"displayRawGSMSignal\"b1\"displayRawWifiSignal\"b1\"locationIconType\"b2\"voiceControlIconType\"b2\"quietModeInactive\"b1\"tetheringConnectionCount\"I\"batterySaverModeActive\"b1\"deviceIsRTL\"b1\"lock\"b1\"breadcrumbTitle\"[256c]\"breadcrumbSecondaryTitle\"[256c]\"personName\"[100c]\"electronicTollCollectionAvailable\"b1\"radarAvailable\"b1\"announceNotificationsAvailable\"b1\"wifiLinkWarning\"b1\"wifiSearching\"b1\"backgroundActivityDisplayStartDate\"d\"shouldShowEmergencyOnlyStatus\"b1\"emergencyOnly\"b1\"secondaryCellularConfigured\"b1\"primaryServiceBadgeString\"[100c]\"secondaryServiceBadgeString\"[100c]\"quietModeImage\"[256c]\"quietModeName\"[256c]\"serviceSuffixString\"[100c]\"secondaryServiceSuffixString\"[100c]\"numberSharingState\"b2\"secondaryNumberSharingState\"b2\"localNetworkType\"I\"localNetworkName\"[100c]}"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xe8"
- "{?=\"itemIsEnabled\"[46B]\"timeString\"[64c]\"shortTimeString\"[64c]\"dateString\"[256c]\"gsmSignalStrengthRaw\"i\"secondaryGsmSignalStrengthRaw\"i\"gsmSignalStrengthBars\"i\"secondaryGsmSignalStrengthBars\"i\"serviceString\"[100c]\"secondaryServiceString\"[100c]\"serviceCrossfadeString\"[100c]\"secondaryServiceCrossfadeString\"[100c]\"serviceImages\"[2[100c]]\"operatorDirectory\"[1024c]\"serviceContentType\"I\"secondaryServiceContentType\"I\"cellLowDataModeActive\"b1\"secondaryCellLowDataModeActive\"b1\"wifiSignalStrengthRaw\"i\"wifiSignalStrengthBars\"i\"wifiLowDataModeActive\"b1\"dataNetworkType\"I\"secondaryDataNetworkType\"I\"batteryCapacity\"i\"batteryState\"I\"batteryDetailString\"[150c]\"bluetoothBatteryCapacity\"i\"thermalColor\"i\"thermalSunlightMode\"b1\"slowActivity\"b1\"syncActivity\"b1\"activityDisplayId\"[256c]\"bluetoothConnected\"b1\"displayRawGSMSignal\"b1\"displayRawWifiSignal\"b1\"locationIconType\"b2\"voiceControlIconType\"b2\"quietModeInactive\"b1\"tetheringConnectionCount\"I\"batterySaverModeActive\"b1\"deviceIsRTL\"b1\"lock\"b1\"breadcrumbTitle\"[256c]\"breadcrumbSecondaryTitle\"[256c]\"personName\"[100c]\"electronicTollCollectionAvailable\"b1\"radarAvailable\"b1\"announceNotificationsAvailable\"b1\"wifiLinkWarning\"b1\"wifiSearching\"b1\"backgroundActivityDisplayStartDate\"d\"shouldShowEmergencyOnlyStatus\"b1\"emergencyOnly\"b1\"secondaryCellularConfigured\"b1\"primaryServiceBadgeString\"[100c]\"secondaryServiceBadgeString\"[100c]\"quietModeImage\"[256c]\"quietModeName\"[256c]\"serviceSuffixString\"[100c]\"secondaryServiceSuffixString\"[100c]\"numberSharingState\"b2\"secondaryNumberSharingState\"b2}"
```
