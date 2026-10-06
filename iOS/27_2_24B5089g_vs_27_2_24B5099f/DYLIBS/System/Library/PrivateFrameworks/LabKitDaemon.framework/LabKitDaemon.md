## LabKitDaemon

> `/System/Library/PrivateFrameworks/LabKitDaemon.framework/LabKitDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5b01c` | `0x61f8c` | **`+0x6f70`** |
| `__TEXT.__eh_frame` | `0x27e8` | `0x2b00` | **`+0x318`** |
| `__AUTH_CONST.__const` | `0x2fa8` | `0x3200` | **`+0x258`** |
| `__TEXT.__oslogstring` | `0x1888` | `0x1a98` | **`+0x210`** |
| `__TEXT.__unwind_info` | `0x10d0` | `0x11e8` | **`+0x118`** |
| `__AUTH_CONST.__objc_const` | `0xfb0` | `0x10b8` | **`+0x108`** |
| `__DATA.__data` | `0xba8` | `0xca8` | **`+0x100`** |
| `__TEXT.__swift5_capture` | `0xaac` | `0xb78` | **`+0xcc`** |
| `__TEXT.__cstring` | `0x1ed6` | `0x1f76` | **`+0xa0`** |
| `__TEXT.__const` | `0x1084` | `0x1114` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x514` | `0x5a4` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x960` | `0x9e8` | **`+0x88`** |
| `__TEXT.__objc_methlist` | `0xb2c` | `0xbb4` | **`+0x88`** |
| `__DATA_CONST.__got` | `0x410` | `0x468` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x57c` | `0x5b8` | **`+0x3c`** |
| `__TEXT.__swift5_typeref` | `0x7aa` | `0x7e0` | **`+0x36`** |
| `__AUTH_CONST.__auth_got` | `0xd98` | `0xdc8` | **`+0x30`** |
| `__AUTH.__objc_data` | `0x558` | `0x580` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x1fc` | `0x214` | **`+0x18`** |
| `__DATA.__bss` | `0xf10` | `0xf20` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x100` | `0x110` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0xb4` | `0xc4` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x80` | `0x8c` | **`+0xc`** |
| `__DATA_CONST.__objc_protorefs` | `0x88` | `0x90` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x4f8` | `0x500` | **`+0x8`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 1320
-  Symbols:   624
-  CStrings:  219
+  Functions: 1400
+  Symbols:   638
+  CStrings:  232
Symbols:
+ _HDClinicalAccountEntityPropertyIdentifier
+ _HDClinicalDeletedAccountEntityPropertySyncIdentifier
+ _OBJC_CLASS_$_HDClinicalDeletedAccountEntity
+ _OBJC_CLASS_$_HDNewMedicalRecordsCounts
+ _OBJC_CLASS_$_HKMedicalType
+ __OBJC_$_INSTANCE_METHODS__TtC12LabKitDaemon13LabSHLManager(LabKitDaemon|LabKitDaemon1|LabKitDaemon2)
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HDCloudSyncManagerObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HDCloudSyncManagerObserver
+ __OBJC_$_PROTOCOL_REFS_HDCloudSyncManagerObserver
+ __OBJC_CLASS_PROTOCOLS_$__TtC12LabKitDaemon13LabSHLManager(LabKitDaemon|LabKitDaemon1|LabKitDaemon2)
+ __OBJC_LABEL_PROTOCOL_$_HDCloudSyncManagerObserver
+ __OBJC_PROTOCOL_$_HDCloudSyncManagerObserver
+ ___swift_closure_destructor.14Tm
+ ___swift_closure_destructorTm
+ _symbolic Say_____G 10Foundation4UUIDV
+ _symbolic _____yShy_____GG 2os21OSAllocatedUnfairLockV 10Foundation4UUIDV
+ _symbolic _____yShy_____y_____SSGGG 2os21OSAllocatedUnfairLockV 15HealthUtilities15TypedIdentifierV 0E14RecordServices15LaboratoryOrderV
- __OBJC_$_INSTANCE_METHODS__TtC12LabKitDaemon13LabSHLManager(LabKitDaemon|LabKitDaemon1)
- __OBJC_CLASS_PROTOCOLS_$__TtC12LabKitDaemon13LabSHLManager(LabKitDaemon|LabKitDaemon1)
- ___swift_project_boxed_opaque_existential_0Tm
CStrings:
+ "AND sync_provenance = "
+ "Failed to fetch orders with unstored SHLs: %@"
+ "Failed to remove orders for deleted clinical accounts: %@"
+ "LabNotifyForNewMedicalRecords"
+ "LabRefreshOrdersMissingSHL"
+ "SELECT item_uuid FROM "
+ "Unable to find health records profile extension, skipping SHL storage for %ld unlinked order(s)"
+ "[%s]: Failed to fetch fulfilled orders missing an SHL: %@"
+ "[%s]: Failed to fetch lab orders for account %{public}s: %@"
+ "[%s]: Failed to post new medical records notification with error: %@"
+ "[%s]: Refreshing %{public}ld fulfilled order(s) missing an SHL"
+ "[%s]: Sending results ready notification"
+ "[%s]: account %{public}s is linked to lab order(s) %s"
+ "[%s]: didCreateNewMedicalRecordsFor account `%s` with %ld new and %ld updated record(s) across %ld medical record type(s)"
+ "[%s]: no lab order is linked to account %{public}s"
+ "com.apple.Health.Labs.ResultsReady"
- "[%s]: Failed to post new medical records notification for account %{public}s with error: %@"
- "[%s]: Sending notificaton for account %{public}s"
- "[%s]: didCreateNewMedicalRecordsForAccountIdentifier `%s` and healthLinkIdentifier `%s`"
```
