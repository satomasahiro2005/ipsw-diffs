## installd

> `/usr/libexec/installd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6da34` | `0x70f48` | **`+0x3514`** |
| `__TEXT.__objc_methname` | `0xd133` | `0xd567` | **`+0x434`** |
| `__TEXT.__cstring` | `0x18303` | `0x18723` | **`+0x420`** |
| `__TEXT.__objc_stubs` | `0x8dc0` | `0x8fe0` | **`+0x220`** |
| `__DATA.__objc_const` | `0x6138` | `0x6348` | **`+0x210`** |
| `__TEXT.__objc_methlist` | `0x3774` | `0x390c` | **`+0x198`** |
| `__DATA_CONST.__cfstring` | `0xa520` | `0xa620` | **`+0x100`** |
| `__DATA.__objc_data` | `0xd60` | `0xe40` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x1430` | `0x14f8` | **`+0xc8`** |
| `__TEXT.__eh_frame` | `0x158` | `0x218` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x3b64` | `0x3c00` | **`+0x9c`** |
| `__DATA.__objc_selrefs` | `0x2840` | `0x28d8` | **`+0x98`** |
| `__DATA_CONST.__const` | `0x16d0` | `0x1638` | **`-0x98`** |
| `__TEXT.__objc_methtype` | `0x2375` | `0x2405` | **`+0x90`** |
| `__TEXT.__auth_stubs` | `0x16e0` | `0x1760` | **`+0x80`** |
| `__DATA.__data` | `0xb90` | `0xbf8` | **`+0x68`** |
| `__TEXT.__objc_classname` | `0x64f` | `0x69f` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0xb80` | `0xbc0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x14a7` | `0x14e7` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x54` | `0x28` | **`-0x2c`** |
| `__TEXT.__swift5_capture` | `0xa8` | `0x80` | **`-0x28`** |
| `__TEXT.__swift5_builtin` | `0x14` | `—` | **`-0x14`** |
| `__TEXT.__swift5_typeref` | `0xd2` | `0xe6` | **`+0x14`** |
| `__DATA.__bss` | `0x1e0` | `0x1f0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x150` | `0x160` | **`+0x10`** |
| `__DATA_CONST.__objc_catlist` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x8` | `0x4` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__swift5_fieldmd`

### Other Changes

```diff

-1663.0.0.0.1
+1673.0.0.0.0

-  Functions: 1534
-  Symbols:   532
-  CStrings:  3869
+  Functions: 1593
+  Symbols:   538
+  CStrings:  3915
Symbols:
+ _$sSa10FoundationE19_bridgeToObjectiveCSo7NSArrayCyF
+ _$sSa10FoundationE36_unconditionallyBridgeFromObjectiveCySayxGSo7NSArrayCSgFZ
+ _$sSh10FoundationE36_unconditionallyBridgeFromObjectiveCyShyxGSo5NSSetCSgFZ
+ _$sSh11descriptionSSvg
+ _$sSh9hashValueSivg
+ _$sSo17OS_dispatch_queueC8DispatchE4sync7executexxyKXE_tKlF
+ _$ss11_SetStorageC8allocate8capacityAByxGSi_tFZ
+ _$ss12_ArrayBufferV19_getElementSlowPathyyXlSiFyXl_Ts5
+ _$ss18_CocoaArrayWrapperV8endIndexSivg
+ _$sytN
+ _sandbox_extension_release
+ _swift_initStackObject
+ _swift_setDeallocating
- _$sBi64_WV
- _$ss5ErrorWS
- _$ss6ResultOMn
- _swift_errorRetain
- _swift_getForeignTypeMetadata
- _swift_release_x27
- _swift_willThrowTypedImpl
CStrings:
+ "%s: Failed to release sandbox token %lld for %@ : %s"
+ "+[MIPersonaAssociationManager _replacePersona:withPersona:inExistingPersonaSet:forApp:defaultPersona:personasChanged:error:]"
+ "-[MIPersonaAssociationManager _addPersona:toApp:inDomain:ignoreUninstalledApp:lsPersonaUpdate:error:]"
+ "-[MIPersonaAssociationManager _setPersonas:forApp:inDomain:saveMapping:tellLS:lsPersonaUpdate:error:]"
+ "-[MIPersonaAssociationManager removePersona:fromApp:inDomain:lsPersonaUpdate:error:]"
+ "-[MIPersonaAssociationManager replaceAssociatedPersona:withPersona:forApp:inDomain:lsPersonaUpdate:error:]"
+ "-[MIUserManagement(DaemonUtilities) daemonContainerForPersonaUniqueString:personaVolumeMount:personaVolumeUUID:extensionTokenHandle:error:]"
+ "@56@0:8@16@24^@32^q40^@48"
+ "@56@0:8@16Q24@32Q40^@48"
+ "@72@0:8@16@24@32@40@48^B56^@64"
+ "Attempt to replace persona %@ on %@ but that persona is not currently associated"
+ "B16@?0@\"<MIBundleMetadataProvider>\"8"
+ "B32@?0@\"<MIBundleMetadataProvider>\"8@\"MIBundleMetadata\"16@\"NSSet\"24"
+ "B56@0:8@16@24Q32^@40^@48"
+ "B60@0:8@16@24Q32B40^@44^@52"
+ "B64@0:8@16@24@32Q40^@48^@56"
+ "B64@0:8@16@24Q32B40B44^@48^@56"
+ "DaemonUtilities"
+ "Failed to determine volume UUID for daemon container for persona %@ at %@"
+ "Failed to determine volume UUID for persona volume mount %@"
+ "Failed to get daemon container URL from %@"
+ "Failed to get daemon container for persona %@"
+ "Failed to get sandbox extension for daemon container for persona %@ at %@"
+ "Failed to release sandbox token %lld for %@ : %s"
+ "Got daemon container at %@ for data separated persona %@ that was not on persona mount %@"
+ "MILSPersonaUpdateOperation"
+ "MIPendingLSPersonaUpdate"
+ "T#,R,N"
+ "T@\"NSArray\",N,R"
+ "T@\"NSSet\",N,R"
+ "TB,N"
+ "TQ,N,R,Vdomain"
+ "__ObjC.MILSPersonaUpdateOperation"
+ "__ObjC.MIPendingLSPersonaUpdate"
+ "_addPersona:toApp:inDomain:ignoreUninstalledApp:lsPersonaUpdate:error:"
+ "_makeLSPersonaUpdateOperationWithPendingUpdates:"
+ "_onQueue_replaceAssociatedPersona:withPersona:forBuiltInApp:personasChanged:error:"
+ "_replaceAssociatedPersona:withPersona:forAppInBundleContainer:personasChanged:error:"
+ "_replacePersona:withPersona:inExistingPersonaSet:forApp:defaultPersona:personasChanged:error:"
+ "_setPersonas:forApp:inDomain:saveMapping:tellLS:lsPersonaUpdate:error:"
+ "_userManagement"
+ "addPersona:toApp:inDomain:lsPersonaUpdate:error:"
+ "applyWithError:"
+ "bundleMetadataProviderClass"
+ "daemonContainerForPersona:error:"
+ "daemonContainerForPersonaUniqueString:personaVolumeMount:personaVolumeUUID:extensionTokenHandle:error:"
+ "enumerateAppBundleContainersInDomain:forPersona:isTransient:usingBundleMetadataProviderBlock:"
+ "initWithPendingUpdate:"
+ "initWithPendingUpdates:"
+ "initWithPersona:bundleID:domain:"
+ "initWithPersona:bundleIDs:domain:"
+ "initWithPersonas:bundleID:domain:"
+ "initWithPersonas:bundleIDs:domain:"
+ "onLSRegistrationQueueApplyWithError:"
+ "pendingUpdates"
+ "removePersona:fromApp:inDomain:lsPersonaUpdate:error:"
+ "replaceAssociatedPersona:withPersona:forApp:inDomain:lsPersonaUpdate:error:"
+ "setPersonas:forApp:inDomain:lsPersonaUpdate:error:"
+ "transferOwnershipOfSandboxExtensionToCaller"
+ "volumeUUIDForURL:error:"
- "-[MIPersonaAssociationManager _addPersona:toApp:inDomain:ignoreUninstalledApp:error:]"
- "-[MIPersonaAssociationManager _setPersonas:forApp:inDomain:saveMapping:tellLS:error:]"
- "-[MIPersonaAssociationManager removePersona:fromApp:inDomain:error:]"
- "B32@?0@\"MIBundleContainer\"8@\"MIBundleMetadata\"16@\"NSSet\"24"
- "B52@0:8@16@24Q32B40^@44"
- "B56@0:8@16@24Q32B40B44^@48"
- "B56@0:8@16Q24@32Q40^@48"
- "_addPersona:toApp:inDomain:ignoreUninstalledApp:error:"
- "_setPersona:viaLaunchServicesForApps:inDomain:error:"
- "_setPersonas:forApp:inDomain:saveMapping:tellLS:error:"
- "_setPersonas:viaLaunchServicesForApp:inDomain:error:"
- "addPersona:toApp:inDomain:error:"
- "removePersona:fromApp:inDomain:error:"
- "setPersonas:forApp:inDomain:error:"
```
