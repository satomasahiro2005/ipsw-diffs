## remindd

> `/usr/libexec/remindd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80f7d0` | `0x820420` | **`+0x10c50`** |
| `__TEXT.__eh_frame` | `0x1f588` | `0x1fd08` | **`+0x780`** |
| `__DATA_CONST.__const` | `0x26068` | `0x26530` | **`+0x4c8`** |
| `__TEXT.__oslogstring` | `0x618f0` | `0x61cd0` | **`+0x3e0`** |
| `__DATA.__data` | `0x1f330` | `0x1f5a0` | **`+0x270`** |
| `__TEXT.__const` | `0x292b8` | `0x29518` | **`+0x260`** |
| `__TEXT.__unwind_info` | `0x10340` | `0x10528` | **`+0x1e8`** |
| `__DATA.__objc_const` | `0x1de08` | `0x1dfb0` | **`+0x1a8`** |
| `__DATA.__bss` | `0x236b0` | `0x23830` | **`+0x180`** |
| `__TEXT.__swift5_typeref` | `0x143ce` | `0x1453e` | **`+0x170`** |
| `__TEXT.__constg_swiftt` | `0xd118` | `0xd240` | **`+0x128`** |
| `__DATA.__objc_data` | `0x8708` | `0x87e8` | **`+0xe0`** |
| `__TEXT.__swift5_capture` | `0x6304` | `0x63d0` | **`+0xcc`** |
| `__TEXT.__swift5_fieldmd` | `0xa7e4` | `0xa8a4` | **`+0xc0`** |
| `__TEXT.__swift5_reflstr` | `0xc175` | `0xc225` | **`+0xb0`** |
| `__DATA_CONST.__cfstring` | `0x51a0` | `0x5220` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x8c60` | `0x8ce0` | **`+0x80`** |
| `__TEXT.__objc_classname` | `0x6396` | `0x6406` | **`+0x70`** |
| `__DATA_CONST.__got` | `0x3530` | `0x3598` | **`+0x68`** |
| `__TEXT.__swift_as_cont` | `0x410` | `0x46c` | **`+0x5c`** |
| `__TEXT.__cstring` | `0x18c47` | `0x18c97` | **`+0x50`** |
| `__DATA_CONST.__objc_arraydata` | `0x388` | `0x3d0` | **`+0x48`** |
| `__DATA_CONST.__objc_arrayobj` | `0x390` | `0x3d8` | **`+0x48`** |
| `__DATA_CONST.__auth_got` | `0x4640` | `0x4680` | **`+0x40`** |
| `__DATA_CONST.__auth_ptr` | `0x28a0` | `0x28e0` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x284c1` | `0x28501` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xab90` | `0xabc8` | **`+0x38`** |
| `__TEXT.__swift_as_ret` | `0x204` | `0x22c` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x43d7` | `0x43f7` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1bc60` | `0x1bc40` | **`-0x20`** |
| `__TEXT.__swift5_assocty` | `0x1ed0` | `0x1ee8` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x1914` | `0x192c` | **`+0x18`** |
| `__TEXT.__swift5_types` | `0xb40` | `0xb58` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x1cc` | `0x1e4` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0xc50` | `0xc60` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x7ce0` | `0x7cd8` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x48c` | `0x490` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-4046.11.0.0.0
+4076.0.0.0.0

-  Functions: 22663
-  Symbols:   4279
-  CStrings:  11817
+  Functions: 22812
+  Symbols:   4299
+  CStrings:  11829
Symbols:
+ _$s12FindMyLocate12ClientTargetVMa
+ _$s12FindMyLocate12ClientTargetVMn
+ _$s12FindMyLocate13RequestOriginV_12clientTargetAcA06ClientE0O_AA0hG0VSgtcfC
+ _$s19ReminderKitInternal14VoidParametersVMa
+ _$s19ReminderKitInternal14VoidParametersVSeAAMc
+ _$s19ReminderKitInternal15REMFeatureFlagsO20sceneDrivenKeepAliveyA2CmFWC
+ _$s19ReminderKitInternal15REMFeatureFlagsO29sceneDrivenKeepAlive_visionOSyA2CmFWC
+ _$s19ReminderKitInternal18REMGroceryCategoryOSHAAMc
+ _$s19ReminderKitInternal23REMAccountsListDataViewC03PerE16CountsInvocationC6ResultV08countsByE2IDAGSDyAA09REMObjectN8_CodableCAC0heI0VG_tcfC
+ _$s19ReminderKitInternal23REMAccountsListDataViewC03PerE16CountsInvocationC6ResultVMa
+ _$s19ReminderKitInternal23REMAccountsListDataViewC03PerE16CountsInvocationC6ResultVSEAAMc
+ _$s19ReminderKitInternal23REMAccountsListDataViewC03PerE16CountsInvocationCAA25REMSwiftInvocableProtocolAAMc
+ _$s19ReminderKitInternal23REMAccountsListDataViewC03PerE16CountsInvocationCMa
+ _$s19ReminderKitInternal23REMAccountsListDataViewC03PerE16CountsInvocationCMn
+ _$s19ReminderKitInternal23REMAccountsListDataViewC03PerE6CountsV10incomplete9completedAESi_SitcfC
+ _$s19ReminderKitInternal23REMAccountsListDataViewC03PerE6CountsVMa
+ _$s19ReminderKitInternal23REMAccountsListDataViewC03PerE6CountsVMn
+ _RDGrocerySectionCoalesceOperationAuthor
+ _RDStoreControllerCoalesceGrocerySectionsMigrationAuthor
+ _pthread_equal
+ _pthread_self
- _$s12FindMyLocate13RequestOriginVyAcA06ClientE0OcfC
CStrings:
+ "%{public}s: Failed to enqueue grocery section coalesce operation {listObjectID: %@, error: %s}"
+ "%{public}s: Inserted grocery section coalesce operation queue item {operationType: %{public}s, entityIdentifier: %{public}s}"
+ "A^{_opaque_pthread_t}"
+ "Building duplicate-canonical-name collapse (no locale policy) for grocery list fetch {listID: %{public}@, section_count: %{public}ld}"
+ "Grouped reminder count is missing its list. Skipping {row: %@}"
+ "RDAccountInitializer: removeInactivatedCalDavAccountIfNeeded: could not determine whether the inactivated CalDAV account is empty; skipping removal to avoid data loss and re-arming migrate signal {remObjectID: %{public}@, appleAccountIdentifier: %{public}s, error: %s}"
+ "RDAccountInitializer: removeInactivatedCalDavAccountIfNeeded: refusing to remove a non-empty inactivated CalDAV account before its data has been migrated; re-arming migrate signal {remObjectID: %{public}@, appleAccountIdentifier: %{public}s}"
+ "RDGrocerySectionCoalesceOperationQueue"
+ "RDGrocerySectionCoalesceOperationQueue is disabled because store controller does not support it"
+ "_TtC7remindd33RDGrocerySectionCoalesceOperation"
+ "_TtC7remindd49RDStoreControllerMigrator_CoalesceGrocerySections"
+ "_ivarLockOwnerDuringStoreMigrations"
+ "coalesceGrocerySections"
+ "grocerySectionCoalesceOperationQueue"
+ "\xa1"
- "RDFeedbackProvider: Survey is not enabled for non-seed builds."
- "enableGroceryFeedbackSurvey"
- "\x91"
```
