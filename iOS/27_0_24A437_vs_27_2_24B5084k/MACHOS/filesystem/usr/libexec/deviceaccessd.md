## deviceaccessd

> `/usr/libexec/deviceaccessd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x91f2c` | `0x95d2c` | **`+0x3e00`** |
| `__TEXT.__cstring` | `0x15394` | `0x16094` | **`+0xd00`** |
| `__TEXT.__objc_methname` | `0xa3e4` | `0xa864` | **`+0x480`** |
| `__TEXT.__objc_stubs` | `0x7f40` | `0x8360` | **`+0x420`** |
| `__TEXT.__gcc_except_tab` | `0x40c0` | `0x4300` | **`+0x240`** |
| `__DATA.__objc_selrefs` | `0x2750` | `0x2858` | **`+0x108`** |
| `__TEXT.__objc_methlist` | `0x2740` | `0x2808` | **`+0xc8`** |
| `__DATA_CONST.__const` | `0x2920` | `0x2998` | **`+0x78`** |
| `__DATA.__data` | `0x1378` | `0x13e8` | **`+0x70`** |
| `__TEXT.__objc_methtype` | `0x1b2a` | `0x1b9a` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x1ab0` | `0x1b00` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x2200` | `0x2240` | **`+0x40`** |
| `__DATA.__objc_const` | `0x3668` | `0x3698` | **`+0x30`** |
| `__DATA_CONST.__objc_intobj` | `0xd8` | `0xa8` | **`-0x30`** |
| `__TEXT.__objc_classname` | `0x3e5` | `0x3f5` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x8c8` | `0x8d0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2f4` | `0x2f8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2700.34.0.0.0
+2701.2.0.0.0

-  Functions: 2520
-  Symbols:   914
-  CStrings:  3973
+  Functions: 2554
+  Symbols:   915
+  CStrings:  4074
Symbols:
+ _OBJC_CLASS_$_NSMutableString
+ _OBJC_CLASS_$_NSSet
- _OBJC_CLASS_$_NSMutableOrderedSet
CStrings:
+ " %@"
+ " (%@)"
+ " (%@:%d)"
+ "### Activate failed, unknown type: %@"
+ "### Failed to start %@ extension for %@"
+ "### MigrateAppAccess %@ -> %@ finished, migrated %lu device(s)"
+ "### MigrateAppAccess %@ -> %@, %lu candidate device(s)"
+ "### MigrateAppAccess %@ already has access to %@, re-checking services"
+ "### MigrateAppAccess %@ declares no accessory support, reserving %lu device(s) for it"
+ "### MigrateAppAccess %@ still marked for migration: %@ has no access to %@, so removing %@ could unpair it"
+ "### MigrateAppAccess authorized %@ on %@ for %@, inherited %@, wifiAwarePairingID %llu"
+ "### MigrateAppAccess clearing the migration marker on %@ for %@ failed: %@"
+ "### MigrateAppAccess create reply failed"
+ "### MigrateAppAccess failed: %@ from %@"
+ "### MigrateAppAccess finished migrating %@ on %@%s"
+ "### MigrateAppAccess marked %@ on %@ for migration to %@"
+ "### MigrateAppAccess marking %@ on %@ for migration to %@ failed: %@"
+ "### MigrateAppAccess retagged service '%@' %@ -> %@ on %@"
+ "### MigrateAppAccess rollback of Wi-Fi Aware authorization failed: %@"
+ "### MigrateAppAccess skip %@, %@ holds no transport to migrate"
+ "### MigrateAppAccess skip %@, state %@ is still mid-setup, will retry later"
+ "### MigrateAppAccess skip service '%@' on %@, no authorization"
+ "### MigrateAppAccess skip, no access info for %@ on %@"
+ "### No %@ instance for CapFl %@ (%lu running)"
+ "### No extension point definition for %@ extension"
+ "### ResolvePendingAppMigrations %@"
+ "### ResolvePendingAppMigrations %@ -> %@ failed, will try again later: %@"
+ "### ResolvePendingAppMigrations %@ -> %@ migrated %lu device(s)"
+ "### ResolvePendingAppMigrations get devices failed: %@"
+ "### ResolvePendingAppMigrations unfinished, keeping the access of %@"
+ "### UpdateAppsAccess: %@ inherited access from %@ and declares %@, so keeping it on %@"
+ "### UpdateAppsAccess: %@ now declares %@, which it inherited on %@"
+ "### UpdateAppsAccess: %@ taking over access inherited from %@ on %@, %@ now, %@ later"
+ "### init failed with nil dispatch queue"
+ "### removeAppsAccess %@ is mid-migration, keeping its access to %@"
+ "%@ extension '%@' invalidated: %@"
+ ", source app gone so its record was dropped"
+ "-[DADaemonServer _saveDeviceAppAccessInfo:device:accessoryOptionsCap:error:]"
+ "-[DADaemonServer updateAppAccessInfo:accessoryDevice:removalType:accessoryOptionsCap:error:]"
+ "-[DADaemonServer updateAppAccessInfo:accessoryDevice:removalType:accessoryOptionsCap:error:]_block_invoke"
+ "-[DADaemonServer(AppMigration) _clearPendingMigrationForDevice:fromBundleID:]"
+ "-[DADaemonServer(AppMigration) _markPendingMigrationForDevices:fromBundleID:toBundleID:error:]"
+ "-[DADaemonServer(AppMigration) _migrateAccessoryServiceInfosForDevice:fromBundleID:toBundleID:error:]"
+ "-[DADaemonServer(AppMigration) _migrateAppAccessForDevice:fromBundleID:toBundleID:destinationOptions:outMigrated:error:]"
+ "-[DADaemonServer(AppMigration) _pendingAppMigrationPairs]"
+ "-[DADaemonServer(AppMigration) migrateAppAccessFromBundleID:toBundleID:migratedCount:error:]"
+ "-[DADaemonServer(AppMigration) resolvePendingAppMigrations]"
+ "-[DADaemonXPCConnection _xpcMigrateAppAccess:]"
+ "-[DADaemonXPCConnection _xpcMigrateAppAccess:]_block_invoke"
+ "-[DAExtensionCoordinator _activateExtension:capabilityFlags:]"
+ "-[DAExtensionCoordinator _executeCommandRuntimeAssertion:error:]"
+ "-[DAExtensionCoordinator _extensionEnsureStopped:]"
+ "-[DAExtensionCoordinator _extensionInvalidated:]"
+ "-[DAExtensionCoordinator _extensionWithType:capabilityFlags:]"
+ "-[DAExtensionCoordinator _handleEventLifecycle:]"
+ "-[DAExtensionCoordinator initWithDevice:bundleID:dispatchQueue:]"
+ "@32@0:8q16@24"
+ "@32@0:8q16Q24"
+ "@48@0:8@16@24Q32^@40"
+ "AppMigration"
+ "Authorize Wi-Fi Aware for %@ on %@ failed"
+ "B48@0:8@16@24^Q32^@40"
+ "B56@0:8@16@24q32Q40^@48"
+ "B64@0:8@16@24@32Q40^B48^@56"
+ "Capability %@ ended, %lu still running: %@"
+ "DAAppMigration"
+ "EnsureStopped: %@"
+ "FlushPending: transport %@ has not started its session, deferring message '%@'"
+ "Found extension point: %@"
+ "Marking %@ for migration failed"
+ "MgAA"
+ "MigrateAppAccess: %@ -> %@, from %@"
+ "No destination bundle ID"
+ "No source bundle ID"
+ "RuntimeAssertion: starting %@: CapFl %@"
+ "TB,N,V_mayHavePendingAppMigrations"
+ "_activateExtension:capabilityFlags:"
+ "_appAccessInfoFilenameForBundleID:"
+ "_clearPendingMigrationForDevice:fromBundleID:"
+ "_extensionArray"
+ "_extensionEnsureStopped:"
+ "_extensionInvalidated:"
+ "_extensionWithType:capabilityFlags:"
+ "_extensionWithType:sandboxName:"
+ "_extensionsWithType:"
+ "_markPendingMigrationForDevices:fromBundleID:toBundleID:error:"
+ "_mayHavePendingAppMigrations"
+ "_migrateAccessoryServiceInfosForDevice:fromBundleID:toBundleID:error:"
+ "_migrateAppAccessForDevice:fromBundleID:toBundleID:destinationOptions:outMigrated:error:"
+ "_pendingAppMigrationPairs"
+ "_removeExtension:"
+ "_saveDeviceAppAccessInfo:device:accessoryOptionsCap:error:"
+ "_xpcMigrateAppAccess:"
+ "appendFormat:"
+ "capability %@ is enrolled but not running, dropping event: %@"
+ "capability %@ is not enrolled, dropping event: %@"
+ "extensionFlags"
+ "extensionPointCapabilities"
+ "extensionPointForType:"
+ "extensionsWithType:"
+ "inheritedAccessoryOptions"
+ "initWithDevice:bundleID:dispatchQueue:"
+ "initWithName:authorizationLevel:bundleID:deviceID:"
+ "mayHavePendingAppMigrations"
+ "mgCnt"
+ "mgDst"
+ "mgSrc"
+ "migrateAppAccessFromBundleID:toBundleID:migratedCount:error:"
+ "missing extension with type %@, CapFl %@: %@"
+ "no capability declared for sessionID '%@': %@"
+ "pendingMigrationToBundleID"
+ "process not entitled for migration"
+ "resolvePendingAppMigrations"
+ "sandboxProfileName"
+ "sessionStarted"
+ "setExtensionFlags:"
+ "setExtensionPoint:"
+ "setInheritedAccessoryOptions:"
+ "setMayHavePendingAppMigrations:"
+ "setPendingMigrationTime:"
+ "setPendingMigrationToBundleID:"
+ "setSandboxProfileName:"
+ "setStateRestorationID:"
+ "setUnclaimedMigrationFromBundleID:"
+ "unclaimedMigrationFromBundleID"
+ "unsignedLongLongValue"
+ "updateAppAccessInfo:accessoryDevice:removalType:accessoryOptionsCap:error:"
+ "v32@?0@\"NSNumber\"8@\"NSMutableDictionary\"16^B24"
- "### Failed to start %@ extension, init returned nil"
- "%@ (%@:%d)"
- "%@ extension invalidated: %@"
- "-[DADaemonServer _saveDeviceAppAccessInfo:device:error:]"
- "-[DADaemonServer updateAppAccessInfo:accessoryDevice:removalType:error:]"
- "-[DADaemonServer updateAppAccessInfo:accessoryDevice:removalType:error:]_block_invoke"
- "-[DAExtensionCoordinator _executeCommandRuntimeAssertion:error:]_block_invoke_2"
- "-[DAExtensionCoordinator _extensionInvalidatedWithType:]"
- "-[DAExtensionCoordinator initWithDevice:bundleID:]"
- "FlushPending: transport %@ not yet running (state %d), deferring message '%@'"
- "Skip reporting to session, extension is not running: %@"
- "Skip reporting to session, no extension exists for %@"
- "_extensionEnsureStoppedWithType:"
- "_extensionInvalidatedWithType:"
- "_removeExtensionWithType:"
- "_saveDeviceAppAccessInfo:device:error:"
- "extensionInvalidatedWithType:"
- "extensionWithType:"
- "getExtensionPidByType:"
- "i24@0:8q16"
- "initWithDevice:bundleID:"
- "missing extension with type %@: %@"
- "no capability with sessionID for event: %@"
- "setCapabilityFlag:"
- "unable to get extension with type: %@, %@"
- "v16@?0q8"
- "v32@?0@\"NSString\"8@\"DAExtension\"16^B24"
```
