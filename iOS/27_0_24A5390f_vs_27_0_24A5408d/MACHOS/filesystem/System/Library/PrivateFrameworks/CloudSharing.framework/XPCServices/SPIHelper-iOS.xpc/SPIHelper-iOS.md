## SPIHelper-iOS

> `/System/Library/PrivateFrameworks/CloudSharing.framework/XPCServices/SPIHelper-iOS.xpc/SPIHelper-iOS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb5a68` | `0xbbad8` | **`+0x6070`** |
| `__TEXT.__cstring` | `0x3a28` | `0x3fe8` | **`+0x5c0`** |
| `__TEXT.__oslogstring` | `0x3e8b` | `0x408b` | **`+0x200`** |
| `__TEXT.__eh_frame` | `0x7b48` | `0x7c88` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x3890` | `0x3998` | **`+0x108`** |
| `__DATA.__data` | `0x2028` | `0x2108` | **`+0xe0`** |
| `__TEXT.__const` | `0x5098` | `0x5178` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x28bd` | `0x2999` | **`+0xdc`** |
| `__DATA.__objc_const` | `0x16d0` | `0x17a0` | **`+0xd0`** |
| `__TEXT.__auth_stubs` | `0x1a60` | `0x1b30` | **`+0xd0`** |
| `__TEXT.__swift5_capture` | `0x136c` | `0x1414` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0x2760` | `0x27f0` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x158c` | `0x160c` | **`+0x80`** |
| `__DATA_CONST.__auth_got` | `0xd38` | `0xda0` | **`+0x68`** |
| `__TEXT.__swift5_fieldmd` | `0x1190` | `0x11f4` | **`+0x64`** |
| `__TEXT.__objc_classname` | `0x282` | `0x2e2` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x15c0` | `0x1620` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x2746` | `0x279e` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0xdf0` | `0xe34` | **`+0x44`** |
| `__DATA.__bss` | `0x3df0` | `0x3e10` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x89c` | `0x8b8` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x798` | `0x7b0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x5d0` | `0x5e8` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x718` | `0x720` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xe8` | `0xec` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x198` | `0x194` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x264` | `0x268` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-236.0.0.0.0
+240.0.0.0.0

+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

-  Functions: 2456
-  Symbols:   320
-  CStrings:  1001
+  Functions: 2494
+  Symbols:   323
+  CStrings:  1037
Symbols:
+ _NSLocalizedFailureReasonErrorKey
+ _NSURLUbiquitousItemUploadingErrorKey
+ _OBJC_CLASS_$_LSApplicationWorkspace
CStrings:
+ "<html><br><br>Open my shared album:<br>%@</html>"
+ "A software update is required to share this item. Update to the latest version of iOS to continue."
+ "Can’t Share This Item Using Anyone with the Link"
+ "Failed to fetch ubiquitousItemUploadingError for %s: %s"
+ "NSErrorContext constructed with nil error"
+ "Open Software Update"
+ "Open my shared album: [rich link] '<br>' indicates blank line"
+ "Software Update Required"
+ "This option isn’t available in your country or region. You can still share with people you choose."
+ "To manage this shared album, go to Settings and sign in to your Apple Account, then try again."
+ "_TtC13SPIHelper_iOSP33_CFD04E7E85E3EC135C9ECF1F9C42FF4A29_ComplianceAlertBundleLocator"
+ "_displayedShareIsOwnRoot"
+ "alert message when public sharing is blocked by compliance policy"
+ "alert message when public sharing requires a software update (iOS)"
+ "alert title when public sharing is blocked by compliance policy"
+ "alert title when public sharing requires a software update"
+ "bundleForClass:"
+ "button title to open Software Update settings from the alert when public sharing requires a software update"
+ "cannotBeShared (upload failed: storage full)"
+ "com.apple.CloudSharing.AddByEmail"
+ "currentUser can't invite; returning existing share link without adding participants"
+ "defaultWorkspace"
+ "enableAnonymousPublicAccessIfNeeded set allowsAnonymousPublicAccess[doc], publicPermission: %{public}ld"
+ "fetchShare(forSharingURL:containerID:containerSetupInfo:accountIDOverride:)"
+ "fetchShareMetadataInfo dropping accountIDOverride %s; using containerSetupInfo (accountOverrideInfo.accountID: %s)"
+ "fetchShareMetadataInfo overriding container account: %s"
+ "fetchShareMetadataInfo returned incomplete data"
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
- "ckShare.allowsAnonymousPublicAccess[doc]: %{bool}d"
- "fetchShare(forSharingURL:containerSetupInfo:)"
```
