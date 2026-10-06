## MobileSlideShowSettings

> `/System/Library/PreferenceBundles/MobileSlideShowSettings.bundle/MobileSlideShowSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c958` | `0x1caf8` | **`+0x1a0`** |
| `__DATA_CONST.__cfstring` | `0x2de0` | `0x2ec0` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x34bc` | `0x352d` | **`+0x71`** |
| `__TEXT.__objc_stubs` | `0x4180` | `0x41e0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x495c` | `0x49ac` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x1498` | `0x14b0` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x740` | `0x758` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x13bd` | `0x13ca` | **`+0xd`** |
| `__DATA_CONST.__got` | `0x4e0` | `0x4e8` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x7ec` | `0x7f0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-910.33.102.0.0
+912.0.111.0.0

-  Symbols:   446
-  CStrings:  1365
+  Symbols:   447
+  CStrings:  1375
Symbols:
+ _PXZoomPhotosToFillEnabledKey
Functions:
~ sub_368c : 292 -> 348
~ sub_7734 -> sub_776c : 1868 -> 2064
~ sub_7e80 -> sub_7f7c : 5552 -> 5636
~ sub_155a4 -> sub_156f4 : 576 -> 604
~ sub_1732c -> sub_17498 : 2272 -> 2324
CStrings:
+ "+[SettingsBaseController filterAndConfigureSpecifiers:shownFromAccountSettings:cloudPhotosEnabled:sharedAlbumsEnabled:cplKeepOriginals:isCPLInExitMode:cplDaysUntilExit:shouldHideCPL:shouldHideTransferBehaviors:cloudPhotosPaused:canEnableSharedStreams:cplStatus:targetForActions:showPhotosDiagnoseButton:showPhotosRebuildButton:accountModificationAllowed:isOLEDDevice:wantsPhotosAppSpecificSettings:isLocationBeingOverridden:currentAuthenticationType:systemPolicyOptions:bundleIdentifier:transferBehaviorUserPreference:sharedLibraryInvitationSpecifiers:sharedLibrarySettingsSpecifiers:instanceLogInfo:featureDescriptionCellSupported:]"
+ "<%@> Turbo Sync row %@ — iCPL %@, Shared Albums %@"
+ "@168@0:8@16B24B28B32B36B40q44B52B56B60B64@68@76B84B88B92B96B100B104q108Q116@124q132@140@148@156B164"
+ "DefaultSharingPrivacySwitch"
+ "LemonadeSettingTurboSyncFooter_NoCellular"
+ "SharingGroup"
+ "cellular-data"
+ "deselectRowAtIndexPath:animated:"
+ "filterAndConfigureSpecifiers:shownFromAccountSettings:cloudPhotosEnabled:sharedAlbumsEnabled:cplKeepOriginals:isCPLInExitMode:cplDaysUntilExit:shouldHideCPL:shouldHideTransferBehaviors:cloudPhotosPaused:canEnableSharedStreams:cplStatus:targetForActions:showPhotosDiagnoseButton:showPhotosRebuildButton:accountModificationAllowed:isOLEDDevice:wantsPhotosAppSpecificSettings:isLocationBeingOverridden:currentAuthenticationType:systemPolicyOptions:bundleIdentifier:transferBehaviorUserPreference:sharedLibraryInvitationSpecifiers:sharedLibrarySettingsSpecifiers:instanceLogInfo:featureDescriptionCellSupported:"
+ "hidden"
+ "indexPathForSelectedRow"
+ "off"
+ "on"
+ "shown"
+ "table"
- "+[SettingsBaseController filterAndConfigureSpecifiers:shownFromAccountSettings:cloudPhotosEnabled:cplKeepOriginals:isCPLInExitMode:cplDaysUntilExit:shouldHideCPL:shouldHideTransferBehaviors:cloudPhotosPaused:canEnableSharedStreams:cplStatus:targetForActions:showPhotosDiagnoseButton:showPhotosRebuildButton:accountModificationAllowed:isOLEDDevice:wantsPhotosAppSpecificSettings:isLocationBeingOverridden:currentAuthenticationType:systemPolicyOptions:bundleIdentifier:transferBehaviorUserPreference:sharedLibraryInvitationSpecifiers:sharedLibrarySettingsSpecifiers:instanceLogInfo:featureDescriptionCellSupported:]"
- "<%@> Hiding iCPL conditional specifiers"
- "@164@0:8@16B24B28B32B36q40B48B52B56B60@64@72B80B84B88B92B96B100q104Q112@120q128@136@144@152B160"
- "ZoomPhotosToFillEnabled"
- "filterAndConfigureSpecifiers:shownFromAccountSettings:cloudPhotosEnabled:cplKeepOriginals:isCPLInExitMode:cplDaysUntilExit:shouldHideCPL:shouldHideTransferBehaviors:cloudPhotosPaused:canEnableSharedStreams:cplStatus:targetForActions:showPhotosDiagnoseButton:showPhotosRebuildButton:accountModificationAllowed:isOLEDDevice:wantsPhotosAppSpecificSettings:isLocationBeingOverridden:currentAuthenticationType:systemPolicyOptions:bundleIdentifier:transferBehaviorUserPreference:sharedLibraryInvitationSpecifiers:sharedLibrarySettingsSpecifiers:instanceLogInfo:featureDescriptionCellSupported:"
```
