## demod

> `/usr/libexec/demod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf6b3c` | `0xf9684` | **`+0x2b48`** |
| `__TEXT.__oslogstring` | `0x1cd8c` | `0x1d56c` | **`+0x7e0`** |
| `__TEXT.__cstring` | `0x10ed2` | `0x11542` | **`+0x670`** |
| `__TEXT.__objc_stubs` | `0x1b6a0` | `0x1ba40` | **`+0x3a0`** |
| `__TEXT.__objc_methname` | `0x2130c` | `0x21696` | **`+0x38a`** |
| `__DATA.__objc_const` | `0x19828` | `0x19a60` | **`+0x238`** |
| `__DATA_CONST.__cfstring` | `0xed80` | `0xef00` | **`+0x180`** |
| `__TEXT.__objc_methlist` | `0xdb24` | `0xdc5c` | **`+0x138`** |
| `__DATA.__objc_selrefs` | `0x81f8` | `0x82f8` | **`+0x100`** |
| `__DATA.__objc_data` | `0x4800` | `0x48f0` | **`+0xf0`** |
| `__TEXT.__unwind_info` | `0x3ab8` | `0x3b40` | **`+0x88`** |
| `__TEXT.__gcc_except_tab` | `0x4790` | `0x47f8` | **`+0x68`** |
| `__TEXT.__objc_classname` | `0x188a` | `0x18ea` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x2110` | `0x2150` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x1098` | `0x10b8` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x3260` | `0x3280` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x409b` | `0x40bb` | **`+0x20`** |
| `__DATA_CONST.__objc_arrayobj` | `0x468` | `0x480` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x720` | `0x738` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xf20` | `0xf30` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x418` | `0x428` | **`+0x10`** |
| `__DATA.__data` | `0x29f8` | `0x2a00` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xb38` | `0xb40` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x190` | `0x198` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x938` | `0x940` | **`+0x8`** |
| `__TEXT.__const` | `0x530` | `0x538` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x112` | `0x11a` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1871.2.1.0.0
+1871.40.45.0.0

-  - /usr/lib/swift/libswiftSpriteKit.dylib

-  Functions: 6092
-  Symbols:   1056
-  CStrings:  10934
+  Functions: 6139
+  Symbols:   1061
+  CStrings:  11047
Symbols:
+ _$s12FindMyLocate12ClientTargetVMa
+ _$s12FindMyLocate12ClientTargetVMn
+ _$s12FindMyLocate13RequestOriginV_12clientTargetAcA06ClientE0O_AA0hG0VSgtcfC
+ _OBJC_CLASS_$_NEPathRule
+ _dispatch_assert_queue_not$V2
+ _getuid
+ _mbr_uid_to_uuid
- _$s12FindMyLocate13RequestOriginVyAcA06ClientE0OcfC
- __swift_FORCE_LOAD_$_swiftSpriteKit
CStrings:
+ "\t\t%{public}@"
+ "\tapplication: %{public}@"
+ "\tapplicationIdentifier: %{public}@"
+ "\tapplicationName: %{public}@"
+ "\tdefaultPathRule: %{bool}d"
+ "\tdenyAll: %{bool}d"
+ "\tdenyMulticast: %{bool}d"
+ "\tgrade: %ld"
+ "\tidentifier: %{public}@"
+ "\tisIdentifierExternal: %{bool}d"
+ "\tmatchDomains:"
+ "\tmatchPath: %{public}@"
+ "\tmatchSigningIdentifier: %{public}@"
+ "\tmulticastPreferenceSet: %{bool}d"
+ "\tname: %{public}@"
+ "%s - %{public}@ network privacy configuration."
+ "%s - Failed to convert NSUUID to UUIDString."
+ "%s - Failed to create new rule for bundle: %{public}@ with grant: %{bool}d."
+ "%s - Failed to find privacy configuration for uuid: %{public}@"
+ "%s - Failed to get LSApplicationProxy for app: %@"
+ "%s - Failed to load privacy configuration"
+ "%s - Failed to load privacy configuration."
+ "%s - Failed to save privacy configuration - Error: %{public}@"
+ "%s - Found matching rule for bundle ID: %{public}@"
+ "%s - Found matching rule for bundle: %{public}@"
+ "%s - Found network access permission: %{bool}d for bundleID: %{public}@"
+ "%s - Found network privacy configuration for uuid: %{public}@"
+ "%s - Found system container backup: %{public}@"
+ "%s - Getting network privacy configuration timed out after 5 seconds."
+ "%s - Matching rule not found for bundle ID %{public}@ - Create new rule:"
+ "%s - Missing bundleURL in LSApplicationProxy for bundle: %{public}@"
+ "%s - Missing pathController from privacyConfiguration for uid: %{public}@"
+ "%s - No change in denyMulticast needed."
+ "%s - Saving network privacy configuration timed out after 5 seconds."
+ "%s - Successfully %{public}@ network permission for bundle ID: %{public}@"
+ "%s - allow: %{bool}d - bundleID: %{public}@"
+ "%s - allowed: %{bool}d"
+ "%s - bundleID: %{public}@"
+ "%s - bundleID: %{public}@ - bundleURL: %{public}@"
+ "%s - configuration:"
+ "%s - grant: %{bool}d - bundleID: %{public}@"
+ "%s - loadConfigurationsWithCompletionQueue failed - Error: %{public}@"
+ "%s - networkAccessPermission: %{public}@"
+ "%s - resourceName: %{public}@ - rval: %{bool}d"
+ "%s - uuidStr: %{public}@"
+ "-[MSDEmbeddedNetworkPermissionsHelper _getNetworkPrivacyConfiguration]"
+ "-[MSDEmbeddedNetworkPermissionsHelper getNetworkAccessPermissionForBundleID:]"
+ "-[MSDEmbeddedNetworkPermissionsHelper grantNetworkPermission:toBundleID:]"
+ "-[MSDEmbeddedNetworkPermissionsHelper revokeNetworkPermissionForBundleID:]"
+ "-[MSDHomeManager setDeviceAsLocationDevice]_block_invoke"
+ "-[MSDMacNetworkPermissionsHelper _createPathRuleForAppWithBundleID:andMulticastPermission:]"
+ "-[MSDMacNetworkPermissionsHelper _getNetworkPrivacyConfiguration]"
+ "-[MSDMacNetworkPermissionsHelper _getNetworkPrivacyConfiguration]_block_invoke"
+ "-[MSDMacNetworkPermissionsHelper _grantOrRevokeNetworkPermission:toBundleID:]"
+ "-[MSDMacNetworkPermissionsHelper getNetworkAccessPermissionForBundleID:]"
+ "-[MSDMacNetworkPermissionsHelper grantNetworkPermission:toBundleID:]"
+ "-[MSDMacNetworkPermissionsHelper init]"
+ "-[MSDMacNetworkPermissionsHelper revokeNetworkPermissionForBundleID:]"
+ "-[MSDNetworkPermissionsHelper _saveNetworkPrivacyConfiguration:]"
+ "-[MSDNetworkPermissionsHelper _saveNetworkPrivacyConfiguration:]_block_invoke"
+ "-[MSDNetworkPermissionsHelper isNetworkOwnedResource:]"
+ "-[MSDSignedManifestV7 mergedBackupManifest:]"
+ "-[MSDTargetDevice setPasscodeModificationAllowed:]"
+ "/var/containers/Shared/SystemGroup/systemgroup.com.apple.configurationprofiles"
+ "/var/mobile/Library/BulletinBoard/VersionedSectionInfo.plist"
+ "/var/mobile/Library/Preferences/com.apple.AppStore.plist"
+ "/var/mobile/Library/Preferences/com.apple.NanoHomeScreen.PrivacyDefaults.plist"
+ "/var/mobile/Library/Preferences/com.apple.RelevancePlatform.AudioUnderstanding.plist"
+ "/var/mobile/Library/Preferences/com.apple.compass.plist"
+ "/var/mobile/Library/Preferences/com.apple.health.shared.plist"
+ "/var/mobile/Library/Preferences/com.apple.private.health.respiratory.plist"
+ "@\"MSDNetworkPermissionsHelper\""
+ "Failed to save"
+ "Failed to set device as the me device."
+ "GRANTED"
+ "HighlightSecretGestureView"
+ "MSDEmbeddedNetworkPermissionsHelper"
+ "MSDMacNetworkPermissionsHelper"
+ "MSDNetworkPermissionsHelper"
+ "Network privacy configuration:"
+ "Network privacy path rule:"
+ "Path controller enabled: %{bool}d"
+ "REVOKED"
+ "Ran into an error while updating siri phrase option: %@"
+ "Successfully saved"
+ "Successfully set device as me device"
+ "System container backup only allowed on Watch, TV or Ha devices."
+ "T@\"MSDNetworkPermissionsHelper\",&,V_networkPermissionHelper"
+ "T@\"NSArray\",&,N,V_networkOwnedResources"
+ "T@\"NSString\",&,N,V_uuidStr"
+ "This method %@ must be implemented by a sub-class."
+ "Timed out after %dsec setting device as the me device..."
+ "_createPathRuleForAppWithBundleID:andMulticastPermission:"
+ "_getNetworkPrivacyConfiguration"
+ "_grantOrRevokeNetworkPermission:toBundleID:"
+ "_networkPermissionHelper"
+ "_printNetworkPrivacyConfiguration:"
+ "_printPathController:"
+ "_printPathRule:"
+ "_saveNetworkPrivacyConfiguration:"
+ "_setHeySiriAndJustSiri"
+ "_uuidStr"
+ "application"
+ "applicationName"
+ "arrayByAddingObject:"
+ "denyAll"
+ "grade"
+ "highlightSecretGestureView"
+ "homeManager:didRemoveCurrentAccessoryWithRegulatoryEraseRequired:"
+ "initWithSigningIdentifier:"
+ "initWithUUIDBytes:"
+ "isDefaultPathRule"
+ "isIdentifierExternal"
+ "matchDomains"
+ "matchPath"
+ "multicastPreferenceSet"
+ "networkPermissionHelper"
+ "raise:format:"
+ "reconcileSiriStateAfterFullScreenUI"
+ "reconcileSiriStateWithFeatureFlag"
+ "reconcileVoiceTriggerWithSiriOn:"
+ "setAllowEmptyDesignatedRequirement:"
+ "setBoolValue:forSetting:"
+ "setDeviceAsMeDeviceWithCompletionHandler:"
+ "setMatchPath:"
+ "setNetworkPermissionHelper:"
+ "setPathRules:"
+ "setUuidStr:"
+ "set_recoveryMethodAvailable:"
+ "siriPhraseOptions"
+ "updateSiriPhraseOptions:completion:"
+ "uuidStr"
- "%s - Failed to save privacy configuration: %{public}@"
- "-[MSDAppPrivacyPermissionsHelper grantNetworkPermission:toBundleID:]"
- "-[MSDAppPrivacyPermissionsHelper saveNetworkPrivacyConfiguration:]_block_invoke"
- "-[MSDHomeManager(HomeUpdate) setDeviceAsLocationDevice]_block_invoke"
- "Failed to load privacy configuration"
- "Found network access permission: %d for bundleID: %{public}@"
- "Library/Safari/SafariTabs.db-shm"
- "Library/Safari/SafariTabs.db-wal"
- "System container backup only allowed on Watch or Ha devices."
- "T@\"NSSet\",&,V_networkOwnedResources"
- "TB,V_siriOn"
- "Unable to find the appropriate privacy rule."
- "_siriOn"
- "getNetworkOwnedResources"
- "getNetworkPrivacyConfiguration"
- "meDeviceSetAsThisDeviceWithCompletionHandler:"
- "saveNetworkPrivacyConfiguration:"
- "setSiriOn:"
- "siriOn"
```
