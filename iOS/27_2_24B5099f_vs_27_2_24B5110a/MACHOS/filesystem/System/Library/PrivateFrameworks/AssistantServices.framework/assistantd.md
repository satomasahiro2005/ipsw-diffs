## assistantd

> `/System/Library/PrivateFrameworks/AssistantServices.framework/assistantd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x387534` | `0x38b6a8` | **`+0x4174`** |
| `__TEXT.__oslogstring` | `0x4b564` | `0x4c023` | **`+0xabf`** |
| `__TEXT.__cstring` | `0x5572e` | `0x55e98` | **`+0x76a`** |
| `__TEXT.__objc_methname` | `0x6435e` | `0x648b3` | **`+0x555`** |
| `__TEXT.__objc_stubs` | `0x48ac0` | `0x48e40` | **`+0x380`** |
| `__DATA_CONST.__cfstring` | `0x13040` | `0x13260` | **`+0x220`** |
| `__TEXT.__objc_methlist` | `0x24460` | `0x24570` | **`+0x110`** |
| `__DATA.__objc_selrefs` | `0x15c98` | `0x15da0` | **`+0x108`** |
| `__DATA_CONST.__const` | `0x14a30` | `0x14b10` | **`+0xe0`** |
| `__TEXT.__gcc_except_tab` | `0x3e48` | `0x3f08` | **`+0xc0`** |
| `__DATA.__objc_const` | `0x35e28` | `0x35ee0` | **`+0xb8`** |
| `__TEXT.__unwind_info` | `0xa978` | `0xaa00` | **`+0x88`** |
| `__DATA.__bss` | `0xea8` | `0xee8` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x3ec0` | `0x3ef0` | **`+0x30`** |
| `__DATA_CONST.__objc_intobj` | `0x8e8` | `0x918` | **`+0x30`** |
| `__DATA_CONST.__objc_arrayobj` | `0x1f8` | `0x210` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x10465` | `0x1047d` | **`+0x18`** |
| `__DATA.__data` | `0x5fa0` | `0x5fb0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x3930` | `0x3940` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x27d8` | `0x27e4` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x1ca8` | `0x1cb0` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x530` | `0x538` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-3605.30.1.1.1
+3605.31.1.11.2

-  Functions: 14975
-  Symbols:   3026
-  CStrings:  28727
+  Functions: 15015
+  Symbols:   3033
+  CStrings:  28845
Symbols:
+ _HMAccessoryCategoryTypeHomeAccessory
+ _MGGetBoolAnswer
+ _OBJC_CLASS_$_HMAccessoryNumberSetting
+ _OBJC_CLASS_$_TTSAsset
+ _OBJC_CLASS_$_TTSAssetTechnology
+ _OBJC_CLASS_$_TTSAssetType
+ _kVTPreferencesVTPhraseTypeDidChangeDarwinNotification
CStrings:
+ "%s #multi-user-atv Syncing %{private}@ to user profile companion."
+ "%s %@ setting does not exist on this Home device, no recovery needed"
+ "%s Accessory already in assistant access control, skipping update"
+ "%s Accessory not in assistant access control, skipping update"
+ "%s Adding companion IFP device capability (%{bool}d)"
+ "%s Adding companion Linwood device capability (%{bool}d)"
+ "%s Adding companion Siri availability (%{public}@)"
+ "%s Adding linwood capability"
+ "%s Adding voice '%@'"
+ "%s Cannot initialize Siri Phrase Options: currentHome is nil"
+ "%s Cannot sync VT state to HomeKit: currentHome is nil"
+ "%s Checking eligibility for additional voice subscription for '%@'"
+ "%s Companion IFP device capability record %{public}s (raw value %{public}@, resolved %{bool}d)"
+ "%s Companion Linwood device capability record %{public}s (raw value %{public}@, resolved %{bool}d)"
+ "%s Companion Siri availability is not serializable, so it cannot contribute to the identifiers anchor: %{public}@"
+ "%s Companion Siri availability record %{public}s (%{public}@)"
+ "%s Could not apply personal content setting with error %@"
+ "%s Deleting personal content setting record %@ from CloudKit"
+ "%s Failed to initialize Siri Phrase Options: %@"
+ "%s Failed to read VT phrase type: %@"
+ "%s Failed to read the always-recognized demo experience setting, error = %@"
+ "%s Failed to update Siri Phrase Options: %@"
+ "%s Failed to update personal content assistant access control with error %@"
+ "%s Found home for personal content update"
+ "%s Invalid type found for personal content record value"
+ "%s Invalid type found for the Linwood enablement setting"
+ "%s No accessories found for home with id %@"
+ "%s No companion Siri availability computed yet; leaving %{public}@ absent"
+ "%s No home unique identifier found in personal content record %@"
+ "%s No homes found"
+ "%s No personal content setting found in record %@"
+ "%s Not a secure demo device, error = %@"
+ "%s Object is not of the expected type HMAccessoryNumberSetting"
+ "%s Personal content record found: %@"
+ "%s Personal content setting delete operation completed with error %@"
+ "%s Posting Darwin notification that companion info changed for a shared user"
+ "%s Setting Me Linwood Enablement Status %@"
+ "%s Setting companion Linwood enablement (%{bool}d) and device capability (%{bool}d) on new deviceOwner"
+ "%s Siri Phrase Options is unset, initializing from local VT preference: %lu"
+ "%s Syncing Linwood enablement status of me device to cloud (%{private}d)"
+ "%s Syncing Siri Phrase Options to HomeKit: %ld"
+ "%s Unable to subscribe voice [%@], error: %@"
+ "%s Updated personal content assistant access control successfully"
+ "%s Updating companion IFP device capability (%{bool}d)"
+ "%s Updating companion Linwood device capability (%{bool}d)"
+ "%s Updating companion Siri availability (%{public}@)"
+ "%s Voices targeted for subscription '%@'"
+ "%s homeUniqueIdentifier: %{private}@, accessoryIdentifier: %{private}@, enabled: %d"
+ "-[ADCloudKitManager syncPersonalContentSetting:iCloudAltDSID:homeUniqueIdentifier:accessoryIdentifier:completion:]"
+ "-[ADCloudKitManager syncPersonalContentSetting:iCloudAltDSID:homeUniqueIdentifier:accessoryIdentifier:completion:]_block_invoke"
+ "-[ADCloudKitMultiUserSharedDataStore checkForMeLinwodSettingUpdate:]"
+ "-[ADCloudKitMultiUserSharedDataStore checkForPersonalContentSettingUpdate:]"
+ "-[ADCloudKitMultiUserSharedDataStore checkForPersonalContentSettingUpdate:]_block_invoke"
+ "-[ADHomeInfoManager isLinwoodEnabledOnAnyDeviceInHome:]"
+ "-[ADHomeInfoManager isLinwoodEnabledOnAnyHomeDevice:]"
+ "-[ADHomeInfoManager isLinwoodEnabledOnAnyHomeDevice:]_block_invoke"
+ "-[ADHomeInfoManager updateCurrentUserPersonalContentSettingForHome:accessoryIdentifier:enabled:completion:]"
+ "-[ADHomeInfoManager updateCurrentUserPersonalContentSettingForHome:accessoryIdentifier:enabled:completion:]_block_invoke"
+ "-[ADHomeInfoManager(VoiceActivation) syncVoiceTriggerStateToHomeKit]"
+ "-[ADHomeInfoManager(VoiceActivation) syncVoiceTriggerStateToHomeKit]_block_invoke"
+ "-[ADHomeInfoManager(VoiceActivation) updateVoiceTriggerPhrase:currentAccessoryInfo:]_block_invoke"
+ "-[ADMultiUserCloudKitSyncer capabilitiesDidChange]_block_invoke"
+ "/\n"
+ "/System/Library/PrivateFrameworks/MobileStoreDemoKit.framework/MobileStoreDemoKit"
+ "14"
+ "?3"
+ "ADCompanionSiriAvailabilityAnchorValue"
+ "ADIsAlwaysRecognizedStoreDemo"
+ "DeviceSupportsInstructionFollowingPruningModels"
+ "Failed to get assistant access control for user"
+ "Failed to get mutable assistant access control"
+ "Invalid accessoryIdentifier UUID"
+ "MSDKDemoState"
+ "MSDKManagedDevice"
+ "MobileAssistantDaemons-3605.31.1.11.2"
+ "No accessory found matching accessoryIdentifier"
+ "PressDemoMode"
+ "T@\"NSDictionary\",C,N,V_companionSiriAvailability"
+ "TB,N,V_companionIFPCapableDevice"
+ "TB,N,V_companionLinwoodCapableDevice"
+ "_companionIFPCapableDevice"
+ "_companionLinwoodCapableDevice"
+ "_companionSiriAvailability"
+ "_setLinwoodEnabledMeDevice:"
+ "accessoryDidUpdateSupportsAppleTVSiriSettings:"
+ "accessoryDidUpdateSupportsTopCapPlusAndMinus:"
+ "accessoryDidUpdateSupportsTopCapTouchAndHold:"
+ "addAccessory:"
+ "capabilitiesDidChange"
+ "checkForMeLinwodSettingUpdate:"
+ "checkForPersonalContentSettingUpdate:"
+ "companionIFPCapableDevice"
+ "companionLinwoodCapableDevice"
+ "companionSiriAvailability"
+ "createDictionaryExcludingBootSession"
+ "gryphonVoice"
+ "homeDidSetHasOwnerAcknowledgedHomePodSiriOnboarding:"
+ "homeUniqueIdentifier"
+ "ifpCapableDevice"
+ "initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:buildVersion:linwoodEnabled:linwoodCapableDevice:ifpCapableDevice:siriAvailability:"
+ "isAlwaysRecognizedDemoExperience"
+ "isAlwaysRecognizedDemoExperience:"
+ "isLinwoodEnabledOnAnyDeviceInHome:"
+ "isLinwoodEnabledOnAnyHomeDevice:"
+ "isReplyToSiriPrompt"
+ "isSecureDemoModeEnabled:"
+ "linwoodCapableDevice"
+ "listAssetsOfTypes:matching:"
+ "meDeviceIsIFPCapableDevice"
+ "meDeviceIsLinwoodCapableDevice"
+ "meDeviceSiriAvailability"
+ "meIsLinwoodEnabled"
+ "neural"
+ "personalContentTVSetting"
+ "personalContentTV_"
+ "removeAccessory:"
+ "root.siri.personalSiriEnabled"
+ "setCompanionIFPCapableDevice:"
+ "setCompanionLinwoodCapableDevice:"
+ "setCompanionSiriAvailability:"
+ "syncPersonalContentSetting:iCloudAltDSID:homeUniqueIdentifier:accessoryIdentifier:completion:"
+ "syncVoiceTriggerStateToHomeKit"
+ "updateAssistantAccessControl:forHome:completionHandler:"
+ "updateCurrentUserPersonalContentSettingForHome:accessoryIdentifier:enabled:completion:"
+ "v52@0:8B16@20@28@36@?44"
- "%s Setting companion Linwood enablement on new deviceOwner (%{bool}d)"
- "%s Unable to subscribe voice %@, error: %@"
- "/\t"
- "2"
- "?2"
- "MobileAssistantDaemons-3605.30.1.1.1"
- "initWithAssistantID:speechID:idsIdentifier:productPrefix:aceHost:syncMetadata:syncMetadataCapability:peerToPeerHandoffCapability:muxSupportCapability:meDevice:siriLanguage:companionName:buildVersion:linwoodEnabled:"
```
