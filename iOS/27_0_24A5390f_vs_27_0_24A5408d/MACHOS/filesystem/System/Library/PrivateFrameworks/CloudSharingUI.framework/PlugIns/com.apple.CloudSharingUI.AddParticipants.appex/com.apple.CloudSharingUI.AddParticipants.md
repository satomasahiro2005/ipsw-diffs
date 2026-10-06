## com.apple.CloudSharingUI.AddParticipants

> `/System/Library/PrivateFrameworks/CloudSharingUI.framework/PlugIns/com.apple.CloudSharingUI.AddParticipants.appex/com.apple.CloudSharingUI.AddParticipants`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9fcd0` | `0xa441c` | **`+0x474c`** |
| `__TEXT.__cstring` | `0x224f` | `0x26df` | **`+0x490`** |
| `__TEXT.__oslogstring` | `0x3ac6` | `0x3e06` | **`+0x340`** |
| `__TEXT.__const` | `0x4372` | `0x4472` | **`+0x100`** |
| `__DATA.__data` | `0x1d38` | `0x1e30` | **`+0xf8`** |
| `__TEXT.__objc_methname` | `0x2f8d` | `0x3059` | **`+0xcc`** |
| `__DATA_CONST.__const` | `0x5af8` | `0x5bb0` | **`+0xb8`** |
| `__DATA.__objc_const` | `0x1460` | `0x1510` | **`+0xb0`** |
| `__TEXT.__objc_stubs` | `0x1800` | `0x18a0` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0x19c0` | `0x1a40` | **`+0x80`** |
| `__TEXT.__objc_classname` | `0x31d` | `0x39d` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x1cf0` | `0x1d60` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x1205` | `0x1275` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0xf60` | `0xfb8` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x1908` | `0x1960` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0x267a` | `0x26c6` | **`+0x4c`** |
| `__DATA_CONST.__auth_got` | `0xce8` | `0xd28` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x828` | `0x860` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0xdc8` | `0xdf4` | **`+0x2c`** |
| `__DATA.__bss` | `0x2c40` | `0x2c60` | **`+0x20`** |
| `__DATA.__objc_data` | `0x600` | `0x5e0` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x580` | `0x5a0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x5d0` | `0x5f0` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x4030` | `0x4040` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x116e` | `0x117e` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x478` | `0x484` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x6b0` | `0x6b8` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x48` | `0x50` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xc0` | `0xc4` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x104` | `0x100` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x164` | `0x160` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-236.0.0.0.0
+240.0.0.0.0

+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

-  Functions: 2369
-  Symbols:   306
-  CStrings:  903
+  Functions: 2403
+  Symbols:   310
+  CStrings:  941
Symbols:
+ _NSLocalizedDescriptionKey
+ _NSLocalizedFailureReasonErrorKey
+ _OBJC_CLASS_$_LSApplicationWorkspace
+ _swift_getObjCClassFromMetadata
CStrings:
+ "A software update is required to share this item. Update to the latest version of iOS to continue."
+ "B32@0:8@16@24"
+ "Can’t Share This Item Using Anyone with the Link"
+ "NSErrorContext constructed with nil error"
+ "Open Software Update"
+ "Share as %@ (%@)"
+ "Software Update Required"
+ "Supplementary text for add participants dialog"
+ "This option isn’t available in your country or region. You can still share with people you choose."
+ "To add access for people, enter their email addresses or choose from your Contacts list.\n\nAdding access doesn’t share a link. After adding, let these participants know they have access."
+ "To manage this shared album, go to Settings and sign in to your Apple Account, then try again."
+ "_TtC40com_apple_CloudSharingUI_AddParticipantsP33_2143FCE3BF1AB284C4F80F8404C460D129_ComplianceAlertBundleLocator"
+ "_displayedShareIsOwnRoot"
+ "aa_appleAccountWithAltDSID:"
+ "alert message when public sharing is blocked by compliance policy"
+ "alert message when public sharing requires a software update (iOS)"
+ "alert title when public sharing is blocked by compliance policy"
+ "alert title when public sharing requires a software update"
+ "altDSID"
+ "bundleForClass:"
+ "button title to open Software Update settings from the alert when public sharing requires a software update"
+ "com.apple.CloudSharing.AddByEmail"
+ "containerOverride.accountID"
+ "containerOverride.altDSID"
+ "defaultWorkspace"
+ "enableAnonymousPublicAccessIfNeeded set allowsAnonymousPublicAccess[doc], publicPermission: %{public}ld"
+ "fetchShare(forSharingURL:containerID:containerSetupInfo:accountIDOverride:)"
+ "fetchShareMetadataInfo dropping accountIDOverride %s; using containerSetupInfo (accountOverrideInfo.accountID: %s)"
+ "fetchShareMetadataInfo overriding container account: %s"
+ "fetchShareMetadataInfo returned incomplete data"
+ "isManagedAppleAccountOwner: %{bool}d (source: %s, accountResolved: %{bool}d)"
+ "isManagedAppleAccountOwner: false (source: containerOverride, no accountID or altDSID)"
+ "isManagedAppleAccountOwner: false (source: none, no owner handle or container override)"
+ "isManagedAppleAccountOwner: owner handle not resolvable on device; trying container override"
+ "isManagedAppleAccountOwnerForFileOrFolderURL:"
+ "isManagedAppleAccountOwnerForShare:containerSetupInfo:"
+ "message for not signed in alert when an album"
+ "openSensitiveURL:withOptions:"
+ "pendingAddByEmail"
+ "photos_sharedcollections"
+ "prefs:root=General&path=SOFTWARE_UPDATE_LINK"
+ "returning %s shareTypeRequiresOSUpgrade: %@"
+ "returning %s shareTypeUnsupported: %@"
+ "saveShareAndReportErrors got shareTypeRequiresOSUpgrade error"
+ "saveShareAndReportErrors got shareTypeUnsupported error"
+ "sharedAlbum"
+ "unexpected nil in "
- "Create a link by adding people who you’d like to collaborate with on this item."
- "Create a link by adding people who you’d like to collaborate with on “%@”."
- "Supplementary text when share doc is missing name"
- "Supplementary text with shared doc name"
- "You’ll share as %@"
- "You’ll share as %@ (%@)"
- "ckShare.allowsAnonymousPublicAccess[doc]: %{bool}d"
- "fetchShare(forSharingURL:containerSetupInfo:)"
- "sharedItemTitle"
```
