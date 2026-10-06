## remindd

> `/usr/libexec/remindd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x820420` | `0x823e24` | **`+0x3a04`** |
| `__TEXT.__oslogstring` | `0x61cd0` | `0x621f0` | **`+0x520`** |
| `__DATA_CONST.__const` | `0x26530` | `0x266c0` | **`+0x190`** |
| `__TEXT.__objc_methname` | `0x28501` | `0x28611` | **`+0x110`** |
| `__TEXT.__cstring` | `0x18c97` | `0x18d97` | **`+0x100`** |
| `__TEXT.__const` | `0x29518` | `0x295b8` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x1453e` | `0x145d0` | **`+0x92`** |
| `__TEXT.__swift5_capture` | `0x63d0` | `0x6458` | **`+0x88`** |
| `__TEXT.__eh_frame` | `0x1fd08` | `0x1fd80` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0xabc8` | `0xac28` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x10528` | `0x10580` | **`+0x58`** |
| `__TEXT.__objc_stubs` | `0x1bc40` | `0x1bc80` | **`+0x40`** |
| `__DATA.__data` | `0x1f5a0` | `0x1f5d0` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x7cd8` | `0x7d00` | **`+0x28`** |
| `__DATA.__objc_const` | `0x1dfb0` | `0x1dfc8` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x28e0` | `0x28e8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x3598` | `0x35a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4076.0.0.0.0
+4077.0.0.0.0

-  Functions: 22812
-  Symbols:   4299
-  CStrings:  11829
+  Functions: 22842
+  Symbols:   4300
+  CStrings:  11855
Symbols:
+ _$s19ReminderKitInternal15REMFeatureFlagsO27ckDeleteZoneAccountRecoveryyA2CmFWC
CStrings:
+ "No CK account persistent store found"
+ "Primary CK store has no URL"
+ "RDGroceryCategorizer: maximumResponseTokens: %ld"
+ "REMReminderStorageCDIngestor:applyDueDateDeltaAlertChanges: Collapsed duplicate existing early alerts {before: %ld, after: %ld, ids: %{public}s}"
+ "ckDeleteZone recovery: account re-initialized successfully"
+ "ckDeleteZone recovery: accountUtils is nil, cannot re-initialize accounts"
+ "ckDeleteZone recovery: cloudContext is nil, skipping server change token reset — data may not re-appear"
+ "ckDeleteZone recovery: resetting all CK server change tokens <rdar://181242487>"
+ "ckDeleteZone recovery: scheduling updateAccountsAndFetchMigrationState <rdar://181242487>"
+ "ckDeleteZone recovery: updateAccountsAndFetchMigrationState failed: %{public}@"
+ "com.apple.RDStoreController.ckDeleteZone.simulate"
+ "recoverAfterSimulatedZoneDeletion:"
+ "recoverAfterSimulatedZoneDeletion: triggerAccountsUpdateAfterZoneDeletion dispatched"
+ "setMetadata:forPersistentStoreOfType:URL:options:error:"
+ "simulateAccountStoreMarkedForDeletion:"
+ "simulateAccountStoreMarkedForDeletion: Marked store at %s — kill remindd to reproduce rdar://181242487"
+ "simulateLocalZoneDeletion"
+ "simulateLocalZoneDeletion: could not fetch primary CK account in simulation context"
+ "simulateLocalZoneDeletion: deleted %ld objects, triggerAccountsUpdateAfterZoneDeletion dispatched"
+ "simulateLocalZoneDeletion: deleting %ld child objects"
+ "simulateLocalZoneDeletion: failed: %@"
+ "simulateLocalZoneDeletion: failed: %s"
+ "simulateLocalZoneDeletion: no primary active CK account found"
+ "simulateLocalZoneDeletionAndRecover:"
+ "triggerAccountsUpdateAfterZoneDeletion"
+ "v24@0:8@?<v@?q@\"NSError\">16"
```
