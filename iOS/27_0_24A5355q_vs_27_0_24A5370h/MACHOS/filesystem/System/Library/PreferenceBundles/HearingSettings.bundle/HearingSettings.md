## HearingSettings

> `/System/Library/PreferenceBundles/HearingSettings.bundle/HearingSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3a060` | `0x39b28` | **`-0x538`** |
| `__TEXT.__objc_methname` | `0x908b` | `0x925c` | **`+0x1d1`** |
| `__TEXT.__oslogstring` | `0xedf` | `0x1058` | **`+0x179`** |
| `__DATA_CONST.__const` | `0x1128` | `0x1048` | **`-0xe0`** |
| `__DATA_CONST.__cfstring` | `0x3460` | `0x3520` | **`+0xc0`** |
| `__TEXT.__objc_stubs` | `0x7640` | `0x7700` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0xa28` | `0x96c` | **`-0xbc`** |
| `__TEXT.__cstring` | `0x327a` | `0x32fc` | **`+0x82`** |
| `__TEXT.__unwind_info` | `0xe48` | `0xe00` | **`-0x48`** |
| `__DATA.__objc_selrefs` | `0x2828` | `0x2860` | **`+0x38`** |
| `__DATA.__objc_const` | `0x3d78` | `0x3da8` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x668` | `0x660` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x2f1c` | `0x2f24` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x163f` | `0x1644` | **`+0x5`** |
| `__DATA.__objc_ivar` | `0x244` | `0x248` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-527.0.0.0.0
+530.0.0.0.0

-  Functions: 1209
-  Symbols:   513
-  CStrings:  2304
+  Functions: 1202
+  Symbols:   512
+  CStrings:  2323
Symbols:
- _OBJC_CLASS_$_NSLock
CStrings:
+ "@\"PSSpecifier\""
+ "HearingAidDetailViewController: LEA3 %@ - specifiers data %@"
+ "HearingAidViewController: Generated specifier for paired device %@"
+ "HearingAidViewController: Received Available Hearing Devices: %@"
+ "HearingAidViewController: Registering for available devices and properties updates %p"
+ "HearingAidViewController: Updating Paired device specifier \n old %@,\n new %@"
+ "HearingSliderValueCell: LeftMicrophoneInputGain value %@ for inputDescription %@"
+ "HearingSliderValueCell: LeftVolumeInputGain value %@ for inputDescription %@"
+ "HearingSliderValueCell: RightMicrophoneInputGain value %@ for inputDescription %@"
+ "HearingSliderValueCell: RightVolumeInputGain value %@ for inputDescription %@"
+ "Left%@"
+ "LeftMicrophoneInputGain"
+ "LeftVolumeInputGain"
+ "MicrophoneInputGain"
+ "PairHearingAidsTitle"
+ "Right%@"
+ "RightMicrophoneInputGain"
+ "RightVolumeInputGain"
+ "T@\"NSArray\",&,N,V_availableDevices"
+ "T@\"PSSpecifier\",&,N,V_pairedDeviceSpecifier"
+ "TB,N,V_isUpdatedAvailableDevices"
+ "VolumeInputGain"
+ "_isUpdatedAvailableDevices"
+ "_lea3MicrophoneInputSpecifiers"
+ "_lea3VolumeInputSpecifiers"
+ "_pairedDeviceSpecifier"
+ "_updateAvailabilityForPairedHearingDeviceIfNeeded"
+ "_updateSpecifiersForAvailableDevices:"
+ "insertHearingDevicesGroupToSpecifiers:"
+ "insertLoadingToSpecifiers:"
+ "isLEAudioEnabled"
+ "isUpdatedAvailableDevices"
+ "leftMicrophoneInputGain"
+ "leftMicrophoneInputGainValueForInputDescription:"
+ "leftVolumeInputGain"
+ "leftVolumeInputGainValueForInputDescription:"
+ "objectForKeyedSubscript:"
+ "pairedDeviceSpecifier"
+ "rightMicrophoneInputGain"
+ "rightMicrophoneInputGainValueForInputDescription:"
+ "rightVolumeInputGain"
+ "rightVolumeInputGainValueForInputDescription:"
+ "setIsUpdatedAvailableDevices:"
+ "setLeftVolumeInputGainValue:forInputDescription:"
+ "setObject:forKeyedSubscript:"
+ "setPairedDeviceSpecifier:"
+ "setRightVolumeInputGainValue:forInputDescription:"
+ "shortDescription"
+ "stringByReplacingOccurrencesOfString:withString:"
+ "v32@?0@\"NSString\"8@\"NSDictionary\"16^B24"
+ "v32@?0@\"NSString\"8@\"NSNumber\"16^B24"
- "@\"NSLock\""
- "B32@?0@\"PSSpecifier\"8Q16^B24"
- "HEARING_AID_RECOVER_BUTTON"
- "HearingAidViewController: Disconnecting other Hearing Aids\n%@"
- "HearingAidViewController: Generated specifier: %@"
- "HearingAidViewController: Regenerated specifier: %@"
- "HearingAidViewController: Registering for available devices and control messages %p"
- "HearingAidViewController: Updating specifier: %@"
- "PLACEHOLDER"
- "RSSI"
- "SearchingTitle"
- "T@\"NSLock\",&,N,VdeviceUpdateLock"
- "T@\"NSMutableArray\",&,N,V_availableDevices"
- "_shouldUpdateAvailableDeviceSpecifier:"
- "_updateAvailabilityIfNeededForSpecifier:"
- "_updateAvailableDevicesSpecifiersIfNeeded"
- "compare:"
- "containsPeripheralWithUUID:"
- "deviceUpdateLock"
- "disconnectAndUnpair:"
- "enumerateIndexesUsingBlock:"
- "indexesOfObjectsPassingTest:"
- "insertAvailableDevicesToSpecifiers:"
- "insertPlaceholderSpecifierIfNeeded"
- "insertSearchingToSpecifiers:"
- "q24@?0@8@16"
- "replaceObjectAtIndex:withObject:"
- "setArray:"
- "setDeviceUpdateLock:"
- "sortedArrayUsingComparator:"
- "specifierForDevice:"
- "v24@?0Q8^B16"
```
