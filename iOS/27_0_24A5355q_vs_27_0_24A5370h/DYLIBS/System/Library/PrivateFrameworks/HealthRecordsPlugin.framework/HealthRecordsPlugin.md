## HealthRecordsPlugin

> `/System/Library/PrivateFrameworks/HealthRecordsPlugin.framework/HealthRecordsPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb4380` | `0xb6100` | **`+0x1d80`** |
| `__TEXT.__oslogstring` | `0xfbd8` | `0xfdb7` | **`+0x1df`** |
| `__TEXT.__cstring` | `0x9604` | `0x97b4` | **`+0x1b0`** |
| `__TEXT.__gcc_except_tab` | `0x1a7c` | `0x1968` | **`-0x114`** |
| `__AUTH_CONST.__cfstring` | `0x6660` | `0x6740` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x7754` | `0x780c` | **`+0xb8`** |
| `__DATA_CONST.__objc_selrefs` | `0x5168` | `0x5218` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x2ef8` | `0x2f48` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0xb7e0` | `0xb820` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0xb78` | `0xba0` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x436` | `0x45d` | **`+0x27`** |
| `__TEXT.__const` | `0xa10` | `0xa30` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2a10` | `0x2a30` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x230` | `0x248` | **`+0x18`** |
| `__DATA_DIRTY.__data` | `0x3a8` | `0x3b8` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x173` | `0x183` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x9c` | `0xac` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xad8` | `0xae0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x11a0` | `0x11a8` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x324` | `0x328` | **`+0x4`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2

-  Functions: 3516
-  Symbols:   5482
-  CStrings:  1769
+  Functions: 3550
+  Symbols:   5511
+  CStrings:  1780
Symbols:
+ +[HDClinicalAccountEntity(HealthRecordsPlugin) resetAccountRowIDsAfterExtractionWithRulesVersion:identifier:profile:healthDatabase:error:]
+ +[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _checkForExistingDownloadableAttachment:database:error:]
+ +[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _checkForObsoleteDownloadableAttachmentsForMedicalRecord:extractedDownloadableAttachments:medicalObjectIdentifier:clinicalObjectIdentifier:transaction:profile:error:]
+ +[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _deleteAttachmentWithIdentifier:database:error:]
+ +[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _deleteAttachmentsWithMedicalRecordIdentifier:transaction:error:]
+ +[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _enumerateAttachmentsWithPredicate:database:error:enumerationHandler:]
+ +[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _markAvailableAndClearInlineDataForAttachmentWithIdentifier:attachmentIdentifier:database:error:]
+ +[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _processClinicalNotesType:medicalRecord:clinicalRecord:transaction:profile:error:]
+ +[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _updateAttachmentWithIdentifier:properties:database:error:bindingHandler:]
+ +[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _updateHKAttachmentIdentifierForAttachmentWithIdentifier:attachmentIdentifier:database:error:]
+ +[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _updateWithExistingAttachmentIfFoundForDownloadableAttachment:medicalRecord:clinicalRecord:transaction:profile:error:]
+ +[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) deleteAttachmentUsingJournalableOperationWithIdentifier:profile:error:]
+ +[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) insertOrUpdateUsingJournalableOperationAttachment:shouldReplace:profile:error:]
+ -[HDMedicalDownloadableAttachmentManager _downloadableAttachmentsWithoutHKAttachmentPredicate]
+ -[HDMedicalDownloadableAttachmentManager _downloadableAttachmentsWithoutHKAttachmentWithError:]
+ -[HDMedicalDownloadableAttachmentManager _findAttachmentObjectIdentifiersWithDuplicateHKAttachmentsWithProfile:error:]
+ -[HDMedicalDownloadableAttachmentManager _findAttachmentReferenceDupes:]
+ -[HDMedicalDownloadableAttachmentManager _findDupesForAttachmentReferences:]
+ -[HDMedicalDownloadableAttachmentManager _medicalRecordWithAttachmentObjectIdentifier:profile:error:]
+ -[HDMedicalDownloadableAttachmentManager _reconcileDownloadableAttachmentToHKAttachmentWithError:]
+ -[HDMedicalDownloadableAttachmentManager _reconcileDupesWithAttachmentObjectIdentifiers:profile:]
+ GCC_except_table189
+ GCC_except_table48
+ GCC_except_table67
+ _HDAttachmentReferencePredicateForSchemaIdentifier
+ _OBJC_CLASS_$_HDAttachmentEntity
+ _OBJC_CLASS_$_HDAttachmentReferenceEntity
+ ___115+[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) insertOrUpdateAttachment:shouldReplace:profile:error:]_block_invoke
+ ___117+[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _checkForExistingDownloadableAttachment:database:error:]_block_invoke
+ ___118-[HDMedicalDownloadableAttachmentManager _findAttachmentObjectIdentifiersWithDuplicateHKAttachmentsWithProfile:error:]_block_invoke
+ ___118-[HDMedicalDownloadableAttachmentManager _findAttachmentObjectIdentifiersWithDuplicateHKAttachmentsWithProfile:error:]_block_invoke_2
+ ___126+[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _deleteAttachmentsWithMedicalRecordIdentifier:transaction:error:]_block_invoke
+ ___131+[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _enumerateAttachmentsWithPredicate:database:error:enumerationHandler:]_block_invoke
+ ___135+[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _updateAttachmentWithIdentifier:properties:database:error:bindingHandler:]_block_invoke
+ ___138+[HDClinicalAccountEntity(HealthRecordsPlugin) resetAccountRowIDsAfterExtractionWithRulesVersion:identifier:profile:healthDatabase:error:]_block_invoke
+ ___155+[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _updateHKAttachmentIdentifierForAttachmentWithIdentifier:attachmentIdentifier:database:error:]_block_invoke
+ ___158+[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _markAvailableAndClearInlineDataForAttachmentWithIdentifier:attachmentIdentifier:database:error:]_block_invoke
+ ___167+[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _updateWithExistingAttachmentIfFoundForDownloadableAttachment:medicalRecord:clinicalRecord:profile:error:]_block_invoke
+ ___227+[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _checkForObsoleteDownloadableAttachmentsForMedicalRecord:extractedDownloadableAttachments:medicalObjectIdentifier:clinicalObjectIdentifier:transaction:profile:error:]_block_invoke
+ ___76-[HDMedicalDownloadableAttachmentManager _findDupesForAttachmentReferences:]_block_invoke
+ ___block_descriptor_40_e8_32s_e41_v32?0"NSString"8"NSMutableArray"16^B24ls32l8
+ ___block_descriptor_41_e8_32s_e35_B24?0"HDDatabaseTransaction"8^16ls32l8
+ ___block_descriptor_48_e8_32s40s_e45_B24?0"HKMedicalDownloadableAttachment"8^16ls32l8s40l8
+ ___block_descriptor_56_e8_32s40s48r_e35_B24?0"HDAttachmentReference"8^16ls32l8s40l8r48l8
+ _symbolic So21BGSystemTaskSchedulerC
+ _symbolic _____XDXMT 19HealthRecordsPlugin0aB26PeriodicIngestionSchedulerC
- +[HDClinicalAccountEntity(HealthRecordsPlugin) resetAccountRowIDsForRulesVersion:identifier:profile:healthDatabase:error:]
- +[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _checkForExistingDownloadableAttachment:profile:error:]
- +[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _checkForObsoleteDownloadableAttachmentsForMedicalRecord:extractedDownloadableAttachments:medicalObjectIdentifier:clinicalObjectIdentifier:profile:error:]
- +[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _processClinicalNotesType:medicalRecord:clinicalRecord:profile:error:]
- +[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _updateHKAttachmentIdentifierForAttachmentWithIdentifier:attachmentIdentifier:profile:error:]
- +[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) deleteAttachmentWithIdentifier:profile:error:]
- GCC_except_table191
- ___116+[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _checkForExistingDownloadableAttachment:profile:error:]_block_invoke
- ___118+[HDMedicalRecordEntity(HealthRecordsPlugin) processMedicalRecordsInExtractionResult:accountIdentifier:profile:error:]_block_invoke_2
- ___121+[HDClinicalRecordEntity(HealthRecordsPlugin) processClinicalRecordsInExtractionResult:clinicalExternalID:profile:error:]_block_invoke_2
- ___122+[HDClinicalAccountEntity(HealthRecordsPlugin) resetAccountRowIDsForRulesVersion:identifier:profile:healthDatabase:error:]_block_invoke
- ___122+[HDClinicalAccountEntity(HealthRecordsPlugin) resetAccountRowIDsForRulesVersion:identifier:profile:healthDatabase:error:]_block_invoke_2
- ___133+[HDClinicalAccountEntity(HealthRecordsPlugin) updateAccountLastExtractedRowID:rulesVersion:identifier:profile:healthDatabase:error:]_block_invoke_3
- ___154+[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _updateHKAttachmentIdentifierForAttachmentWithIdentifier:attachmentIdentifier:profile:error:]_block_invoke
- ___215+[HDMedicalDownloadableAttachmentEntity(HealthRecordsPlugin) _checkForObsoleteDownloadableAttachmentsForMedicalRecord:extractedDownloadableAttachments:medicalObjectIdentifier:clinicalObjectIdentifier:profile:error:]_block_invoke
- ___block_descriptor_40_e8_32r_e45_B24?0"HKMedicalDownloadableAttachment"8^16lr32l8
- ___block_descriptor_48_e8_32s40r_e45_B24?0"HKMedicalDownloadableAttachment"8^16ls32l8r40l8
CStrings:
+ "%@ cannot be used after profile extension has been released"
+ "%s cannot schedule — profile.daemon is nil; skipping"
+ "%s triggered on profile without a system scheduler, cannot schedule"
+ "%{public}@ account already exists for gateway %{public}@; returning existing account"
+ "%{public}@ journal entries are no longer supported, dropping %lu entr%{public}@"
+ "%{public}@: Failed _reconcileDownloadableAttachmentToHKAttachmentForMedicalRecordWithIdentifier. Error: %{public}@"
+ "%{public}@: Failed enumerating HDAttachmentReferenceEntity for ClinicalRecordSchema Error: %{public}@"
+ "%{public}@: Failed reading HDAttachmentEntity for identifier: %{public}@ Error: %{public}@"
+ "%{public}@: Failed to query medical downloadable attachments without HKAttachments. Error: %{public}@"
+ "%{public}@: No Metadata key found for WebURL or InlineDataChecksum for HKAttachment with identifier: %{public}@"
+ "%{public}@: Reconciled %lu medical records with duplicate HKAttachments"
+ "%{public}@: Reconciliation found no duplicates to reconcile"
+ "%{public}@: identifier is not a medical record  %@"
+ "%{public}@: reconcileDupesWithAttachmentObjectIdentifiers for HKMedicalRecord with 'UUID': %{public}@ failed with error %{public}@"
+ "%{public}@: reconcileDupesWithAttachmentObjectIdentifiers for attachmentObjectIdentifier: %{public}@ failed read medical record with error %{public}@"
+ "%{public}@: reconcileDupesWithAttachmentObjectIdentifiers with %lu records, attempted reconcile on %lu records and encountered %lu errors"
+ "HDClinicalAccountManager received HKFHIRCredentialRefreshResult without auth response nor error"
+ "Persisting an ephemeral account and updating the existing credential from auth response."
+ "ies"
+ "transaction failed without setting error-out"
+ "updateAccountCredentialFromAuthResponse claimed success but failed to update the credential"
+ "v32@?0@\"NSString\"8@\"NSMutableArray\"16^B24"
+ "y"
- "%{public}@ failed to process journaled clinical records: %{public}@"
- "%{public}@ failed to process journaled downloadable attachments: %{public}@"
- "%{public}@ failed to process journaled medical records: %{public}@"
- "%{public}@ failed to update journaled clinical account last extracted row ID: %{public}@"
- "%{public}@ inserted %@ clinical records from journal"
- "%{public}@ inserted %@ medical downloadable attachments from journal"
- "%{public}@ inserted %@ medical records from journal"
- "%{public}@ processing clinical records extraction journal entry for external ID %{public}@"
- "%{public}@ processing medical downloadable attachments in extraction journal entry for account %{public}@"
- "%{public}@ processing medical records extraction journal entry for account %{public}@"
- "%{public}@: Reconciliation %lu HKMedicalDownloadableAttachments"
- "HDClinicalAccountUpdateLastExtractedJournalEntry failed to update journaled clinical account last extracted row ID: %{public}@"
```
