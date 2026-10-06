## TrustedPeersHelper

> `/System/Library/Frameworks/Security.framework/XPCServices/TrustedPeersHelper.xpc/TrustedPeersHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a43a4` | `0x2acff0` | **`+0x8c4c`** |
| `__TEXT.__oslogstring` | `0xd4a4` | `0xe064` | **`+0xbc0`** |
| `__DATA.__bss` | `0x12e20` | `0x13120` | **`+0x300`** |
| `__TEXT.__cstring` | `0x17ab7` | `0x17d47` | **`+0x290`** |
| `__TEXT.__const` | `0xd4c0` | `0xd700` | **`+0x240`** |
| `__TEXT.__auth_stubs` | `0x22e0` | `0x24c0` | **`+0x1e0`** |
| `__TEXT.__objc_methname` | `0x9141` | `0x92c1` | **`+0x180`** |
| `__DATA_CONST.__const` | `0x14e78` | `0x14fc8` | **`+0x150`** |
| `__TEXT.__objc_stubs` | `0x6080` | `0x61c0` | **`+0x140`** |
| `__DATA.__data` | `0x84a0` | `0x85c0` | **`+0x120`** |
| `__DATA.__objc_const` | `0x6e78` | `0x6f90` | **`+0x118`** |
| `__TEXT.__eh_frame` | `0x7ef0` | `0x7ff0` | **`+0x100`** |
| `__DATA_CONST.__auth_got` | `0x1180` | `0x1270` | **`+0xf0`** |
| `__TEXT.__swift5_typeref` | `0x3fc6` | `0x408a` | **`+0xc4`** |
| `__TEXT.__constg_swiftt` | `0x3c1c` | `0x3cc8` | **`+0xac`** |
| `__DATA_CONST.__auth_ptr` | `0x6f0` | `0x768` | **`+0x78`** |
| `__DATA_CONST.__got` | `0xa30` | `0xaa8` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0x4f90` | `0x5008` | **`+0x78`** |
| `__TEXT.__swift5_capture` | `0x51f4` | `0x5268` | **`+0x74`** |
| `__TEXT.__swift5_fieldmd` | `0x2b8c` | `0x2bf8` | **`+0x6c`** |
| `__TEXT.__swift5_reflstr` | `0x2677` | `0x26d7` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x1ec8` | `0x1f18` | **`+0x50`** |
| `__TEXT.__objc_classname` | `0x147b` | `0x14bb` | **`+0x40`** |
| `__TEXT.__swift5_assocty` | `0x420` | `0x450` | **`+0x30`** |
| `__TEXT.__swift5_proto` | `0x98c` | `0x9a8` | **`+0x1c`** |
| `__TEXT.__swift5_builtin` | `0xc8` | `0xdc` | **`+0x14`** |
| `__TEXT.__objc_methlist` | `0x2934` | `0x2944` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x29f0` | `0x2a00` | **`+0x10`** |
| `__DATA.__objc_data` | `0x2c90` | `0x2c98` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x268` | `0x270` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x2c8` | `0x2d0` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x18` | `0x1c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-62460.0.55.0.1
+62460.2.1.0.0

+  - /usr/lib/libsqlite3.dylib

-  Functions: 8907
-  Symbols:   576
-  CStrings:  3195
+  Functions: 8948
+  Symbols:   589
+  CStrings:  3259
Symbols:
+ _NSFileSize
+ _NSSQLiteStoreType
+ _OBJC_CLASS_$_NSFileHandle
+ _OBJC_CLASS_$_NSFileManager
+ _OBJC_CLASS_$_NSPersistentStoreCoordinator
+ _getegid
+ _geteuid
+ _kSecurityRTCEventNameRecoverRKTLKSharesResult
+ _sqlite3_close
+ _sqlite3_exec
+ _sqlite3_free
+ _sqlite3_open_v2
+ _sqlite3_wal_checkpoint_v2
CStrings:
+ ". TrustedPeersHelper cannot operate without the DataVault-backed store."
+ "Container.init: about to loadPersistentStores name=%{public}s path=%{public}s existsPre=%{bool,public}d sizePre=%{public}ld"
+ "Container.init: loadPersistentStores returned err=%{public}s existsPost=%{bool,public}d sizePost=%{public}ld"
+ "Container.init: retry loadPersistentStores succeeded"
+ "Container.init: store flagged as corrupt; destroying and retrying. domain=%{public}s code=%{public}ld"
+ "Could not find RK TLK for %s, skipping evaluation"
+ "PRAGMA journal_mode=DELETE;"
+ "PRAGMA journal_mode=WAL;"
+ "Protected System container has no resolved path"
+ "Protected System container resolution failed for "
+ "Sponsor (%s doesn't have any TLK Shares to prove ownership, skipping"
+ "StorageContainersPrivate.Container.Owned symbol not resolved: StorageContainersPrivate framework is weak-linked but was not found at runtime. TrustedPeersHelper cannot operate without the container manager library."
+ "StorageContainersProvider: constructed Container.Owned identifier=%{public}s"
+ "StorageContainersProvider: grantAccess failed: %{public}s"
+ "StorageContainersProvider: grantAccess succeeded for identifier=%{public}s"
+ "StorageContainersProvider: revokeAccess for identifier=%{public}s"
+ "TrustedPeersHelper/ContainerMap.swift"
+ "WAL checkpoint failed"
+ "_TtC18TrustedPeersHelper25StorageContainersProvider"
+ "accessGranted"
+ "attributesOfItemAtPath:error:"
+ "categoriesByView"
+ "closeAndReturnError:"
+ "errored while trying to get full peer only views"
+ "fileExistsAtPath:"
+ "fileHandleForReadingFromURL:error:"
+ "findOrCreate: opening store for container=%{public}s context=%{public}s persona=%{public}s"
+ "findOrCreate: persistent store URL=%{public}s"
+ "grantAccess failed: "
+ "initWithManagedObjectModel:"
+ "migrateLegacyStoreIfNeeded: %{public}s -> %{public}s"
+ "migrateLegacyStoreIfNeeded: %{public}s — quarantining and starting fresh"
+ "migrateLegacyStoreIfNeeded: %{public}s — starting fresh"
+ "migrateLegacyStoreIfNeeded: WAL checkpoint rc=%{public}d for %{public}s"
+ "migrateLegacyStoreIfNeeded: checkpoint open failed for %{public}s"
+ "migrateLegacyStoreIfNeeded: copy complete (atomic rename)"
+ "migrateLegacyStoreIfNeeded: destination already exists; skipping"
+ "migrateLegacyStoreIfNeeded: journal_mode=DELETE failed: %{public}s for %{public}s"
+ "migrateLegacyStoreIfNeeded: journal_mode=WAL failed: %{public}s for %{public}s"
+ "migrateLegacyStoreIfNeeded: legacy file still present (not removed): %{public}s"
+ "migrateLegacyStoreIfNeeded: migration complete"
+ "migrateLegacyStoreIfNeeded: restoreWALMode open failed for %{public}s"
+ "migrateLegacyStoreIfNeeded: source does not exist; nothing to migrate"
+ "migrateLegacyStoreIfNeeded: unexpected %{public}s sibling remains after checkpoint at %{public}s"
+ "moveItemAtURL:toURL:error:"
+ "owned"
+ "protectedSystemProviderFactory"
+ "quarantineCorruptStore: failed to move %{public}s aside: %{public}s"
+ "quarantineCorruptStore: quarantined %{public}s → %{public}s"
+ "readDataOfLength:"
+ "removeItemAtURL:error:"
+ "replacePersistentStore failed: "
+ "replacePersistentStoreAtURL:destinationOptions:withPersistentStoreFromURL:sourceOptions:storeType:error:"
+ "source is not a SQLite database"
+ "storageOwner"
+ "urlForPersistentStore: Protected System container URL=%{public}s"
+ "urlForPersistentStore: db at %{public}s exists=%{bool,public}d"
+ "urlForPersistentStore: db does not exist yet; checking legacy for migration"
+ "urlForPersistentStore: destination already existed; using it as-is"
+ "urlForPersistentStore: migration failed (%{public}s); CoreData will create fresh schema"
+ "urlForPersistentStore: migration succeeded"
+ "urlForPersistentStore: no legacy URL resolvable for %{public}s; skipping migration"
+ "urlForPersistentStore: no legacy store; CoreData will create fresh schema"
+ "urlForPersistentStore: resolving for filename=%{public}s persona=%{public}s"
+ "urlForPersistentStore: returning Protected System URL %{public}s"
- "Potential sponsor %s does not have a self-TLKShare for this view, skipping"
```
