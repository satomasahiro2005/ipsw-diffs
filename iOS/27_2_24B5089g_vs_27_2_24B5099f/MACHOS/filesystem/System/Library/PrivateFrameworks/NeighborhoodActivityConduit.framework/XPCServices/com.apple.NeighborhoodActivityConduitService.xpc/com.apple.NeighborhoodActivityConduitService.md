## com.apple.NeighborhoodActivityConduitService

> `/System/Library/PrivateFrameworks/NeighborhoodActivityConduit.framework/XPCServices/com.apple.NeighborhoodActivityConduitService.xpc/com.apple.NeighborhoodActivityConduitService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1423c0` | `0x14caa0` | **`+0xa6e0`** |
| `__TEXT.__eh_frame` | `0xd118` | `0xd8f0` | **`+0x7d8`** |
| `__TEXT.__oslogstring` | `0x6b3c` | `0x6fac` | **`+0x470`** |
| `__DATA_CONST.__const` | `0x6410` | `0x66b8` | **`+0x2a8`** |
| `__TEXT.__const` | `0x4708` | `0x4998` | **`+0x290`** |
| `__DATA.__data` | `0x35f0` | `0x3870` | **`+0x280`** |
| `__TEXT.__unwind_info` | `0x3fd0` | `0x4210` | **`+0x240`** |
| `__DATA.__objc_const` | `0x4190` | `0x4398` | **`+0x208`** |
| `__TEXT.__objc_methname` | `0x6b77` | `0x6d57` | **`+0x1e0`** |
| `__TEXT.__swift5_typeref` | `0x32b0` | `0x344a` | **`+0x19a`** |
| `__DATA.__objc_data` | `0xff0` | `0x1130` | **`+0x140`** |
| `__TEXT.__swift5_capture` | `0x2aa8` | `0x2bd8` | **`+0x130`** |
| `__TEXT.__swift5_reflstr` | `0x1cb4` | `0x1dc4` | **`+0x110`** |
| `__TEXT.__objc_classname` | `0xabb` | `0xb9b` | **`+0xe0`** |
| `__TEXT.__objc_stubs` | `0x2ec0` | `0x2fa0` | **`+0xe0`** |
| `__TEXT.__constg_swiftt` | `0x1b6c` | `0x1c48` | **`+0xdc`** |
| `__TEXT.__cstring` | `0x1ef6` | `0x1fc6` | **`+0xd0`** |
| `__TEXT.__auth_stubs` | `0x3810` | `0x38c0` | **`+0xb0`** |
| `__TEXT.__swift5_fieldmd` | `0x1350` | `0x13f8` | **`+0xa8`** |
| `__TEXT.__swift_as_cont` | `0xf8c` | `0x1028` | **`+0x9c`** |
| `__TEXT.__objc_methtype` | `0x111b` | `0x11a1` | **`+0x86`** |
| `__DATA_CONST.__auth_got` | `0x1c10` | `0x1c68` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x15d4` | `0x1624` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x16b8` | `0x1700` | **`+0x48`** |
| `__DATA_CONST.__got` | `0xee0` | `0xf20` | **`+0x40`** |
| `__TEXT.__swift_as_ret` | `0x510` | `0x544` | **`+0x34`** |
| `__TEXT.__swift_as_entry` | `0x518` | `0x53c` | **`+0x24`** |
| `__DATA_CONST.__objc_classlist` | `0xd0` | `0xe0` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0xf8` | `0x108` | **`+0x10`** |
| `__DATA.__common` | `0x160` | `0x168` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x7d8` | `0x7e0` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x88` | `0x90` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x118` | `0x120` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1a8` | `0x1ac` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x40` | `0x44` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-1626.200.65.0.0
+1626.200.84.0.0

+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

+  - /System/Library/PrivateFrameworks/LinkServices.framework/LinkServices

-  Functions: 3851
-  Symbols:   421
-  CStrings:  1606
+  Functions: 3970
+  Symbols:   427
+  CStrings:  1648
Symbols:
+ _LNConnectionErrorDomain
+ _LNConnectionLSRestrictionReasonUserInfoKey
+ _LNConnectionRestrictionInvalidationBundleIdentifierKey
+ _LNConnectionRestrictionStateDidChangeNotification
+ _OBJC_CLASS_$_LNMetadataProvider
+ _OBJC_CLASS_$_LSObserver
CStrings:
+ "Ending all continuity sessions!"
+ "FaceTime is now restricted by Screen Time - ending all sessions."
+ "Failed to tell %s that FaceTime restrictions changed to %{bool}d: %@."
+ "LSObserverDelegate"
+ "LaunchServices database changed - reevaluating."
+ "Rejecting start laguna session request because FaceTime is restricted by Screen Time."
+ "Restriction check failed outside LNConnectionErrorDomain: %@."
+ "Restriction check failed with unrecognized LNConnectionErrorCode %ld - treating as unrestricted."
+ "Restriction check for %s didn't complete: %@. Leaving restriction state at %{bool}d."
+ "Restriction state changed for %s - reevaluating."
+ "TUCompanionDeviceModel"
+ "[GetContacts] Error retrieving me card: %@"
+ "[MeCard] Attaching me card for local member handle %s."
+ "[MeCard] No me card available for local member handle %s."
+ "[Participants] Rejecting conversation participant: %s from %s because it is an anonym without a handle."
+ "[Participants] Rejecting conversation participant: %s from %s because it is an invalid handle."
+ "[Participants] Rejecting request because no session exists for %s."
+ "[SessionServer] parseProtoRecentsCallLinkItem skipping call duration scoped link"
+ "_TtC44com_apple_NeighborhoodActivityConduitService26FaceTimeRestrictionChecker"
+ "_TtC44com_apple_NeighborhoodActivityConduitServiceP33_46A0A6DFC42F5D1FC98DD7AFBBB80C5130LaunchServicesDatabaseObserver"
+ "_crossPlatformUnifiedMeContactWithKeysToFetch:error:"
+ "checkRestrictions(forBundleIdentifier: %s) reported no restriction."
+ "checkRestrictions(forBundleIdentifier: %s) threw %s code %ld userInfo %s."
+ "checkRestrictionsForBundleIdentifier:error:"
+ "checkTimeout"
+ "com.apple.callservicesd.faceTimeRestrictionsDidChange"
+ "com_apple_NeighborhoodActivityConduitService.LaunchServicesDatabaseObserver"
+ "conversationManager:debugSendInterpreterLink:toHandle:"
+ "databaseObserver"
+ "initWithOptions:"
+ "isFaceTimeRestrictedObserver"
+ "isFaceTimeRestrictedSubject"
+ "linkLifetimeScope"
+ "metadataProvider"
+ "observer"
+ "observerDidObserveDatabaseChange:"
+ "onDatabaseChange"
+ "queryLinkServices()"
+ "refreshRequestContinuation"
+ "setHandlesToAddAfterHandoff:"
+ "setName:"
+ "startObserving"
+ "v24@0:8@\"LSObserver\"16"
+ "v40@0:8@\"TUConversationManager\"16@\"NSString\"24@\"NSString\"32"
- "[AddParticipants] Rejecting request to add conversation participant: %s from %s because it is an anonym without a handle."
- "[AddParticipants] Rejecting request to add conversation participant: %s from %s because it is an invalid handle."
```
