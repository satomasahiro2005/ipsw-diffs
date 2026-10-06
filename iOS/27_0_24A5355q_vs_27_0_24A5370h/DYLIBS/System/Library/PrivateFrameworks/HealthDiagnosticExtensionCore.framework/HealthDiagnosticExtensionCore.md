## HealthDiagnosticExtensionCore

> `/System/Library/PrivateFrameworks/HealthDiagnosticExtensionCore.framework/HealthDiagnosticExtensionCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbe44` | `0xbdd4` | **`-0x70`** |

### Other Changes

```diff

-7027.0.52.2.6
+7027.0.60.2.2
Functions:
~ -[HDCloudSyncDiagnosticOperation _reportCloudSyncErrors] : 360 -> 356
~ -[HDDatabaseDiagnosticOperation _captureUnprotectedDatabaseAtURL:protectedDatabaseAtURL:reason:] : 556 -> 552
~ -[HDFeatureStatusDiagnosticOperation _reportRequirementSatisfactionOverridesByFeature] : 880 -> 876
~ -[HDFeatureStatusDiagnosticOperation _reportFeatureStatusByFeature] : 320 -> 316
~ -[HDFeatureStatusDiagnosticOperation _reportCountryCodeSource] : 556 -> 552
~ -[HDFeatureStatusDiagnosticOperation _reportRegionAvailabilityByFeature] : 320 -> 316
~ -[HDNanoSyncDiagnosticOperation run] : 788 -> 780
~ -[HDNanoSyncDiagnosticOperation _reportSummaryWithDevices:] : 696 -> 692
~ -[HDNotificationSyncDiagnosticOperation _appendNotificationInstructions:] : 300 -> 296
~ -[HDSummarySharingDiagnosticOperation run] : 632 -> 628
~ -[HDSummarySharingDiagnosticOperation _reportHeaderWithProfileIdentifiers:] : 636 -> 632
~ ___75-[HDSummarySharingDiagnosticOperation _reportHeaderWithProfileIdentifiers:]_block_invoke : 400 -> 396
~ -[HDSummarySharingDiagnosticOperation _reportInvitationsForPrimaryProfile] : 1172 -> 1164
~ ___74-[HDSummarySharingDiagnosticOperation _reportInvitationsForPrimaryProfile]_block_invoke : 688 -> 684
~ -[HDSummarySharingDiagnosticOperation _reportSharedSummariesForProfileIdentifier:committedTransactions:] : 1196 -> 1192
~ ___104-[HDSummarySharingDiagnosticOperation _reportSharedSummariesForProfileIdentifier:committedTransactions:]_block_invoke : 548 -> 544
~ ___80-[HDWorkoutCondenserDiagnosticOperation _reportCondensedWorkoutsWithTaskClient:]_block_invoke : 460 -> 456
~ ___82-[HDWorkoutCondenserDiagnosticOperation _reportCondensableWorkoutsWithTaskClient:]_block_invoke : 460 -> 456
~ -[HDDiagnosticExtension attachmentsForParameters:] : 1716 -> 1704
~ -[HDDiagnosticExtension _loadOperationsFromPluginsWithAttachmentDirectoryURL:] : 596 -> 592
~ ___43-[HDDiagnosticOperation submitAttachments:]_block_invoke : 248 -> 244
~ -[HDDiagnosticOperation getFileStatisticsForDirectoryWithURL:earliestModificationDate:totalFileSize:maxFileSize:] : 652 -> 648
~ -[HDDiagnosticOperation checkSchemaVersionForDatabase:currentSchema:futureSchema:] : 800 -> 796
~ -[HDDiagnosticOperation reportCountsForDatabase:entityClasses:] : 272 -> 268
```
