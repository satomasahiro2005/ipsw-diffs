## HealthAppHealthDaemon

> `/System/Library/PrivateFrameworks/HealthAppHealthDaemon.framework/HealthAppHealthDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b9b8` | `0x45d8c` | **`+0xa3d4`** |
| `__TEXT.__eh_frame` | `0x1b50` | `0x2018` | **`+0x4c8`** |
| `__AUTH_CONST.__objc_const` | `0x2c80` | `0x3068` | **`+0x3e8`** |
| `__TEXT.__objc_methlist` | `0x1adc` | `0x1ddc` | **`+0x300`** |
| `__DATA.__bss` | `0x1c10` | `0x1e90` | **`+0x280`** |
| `__TEXT.__oslogstring` | `0x2193` | `0x23d4` | **`+0x241`** |
| `__TEXT.__unwind_info` | `0x11e0` | `0x13e8` | **`+0x208`** |
| `__AUTH_CONST.__const` | `0x1290` | `0x1488` | **`+0x1f8`** |
| `__TEXT.__const` | `0x1fd0` | `0x2180` | **`+0x1b0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1238` | `0x13d8` | **`+0x1a0`** |
| `__AUTH.__objc_data` | `0x320` | `0x470` | **`+0x150`** |
| `__TEXT.__cstring` | `0x1456` | `0x15a6` | **`+0x150`** |
| `__DATA.__data` | `0xff0` | `0x1100` | **`+0x110`** |
| `__AUTH_CONST.__auth_got` | `0xf10` | `0xfe0` | **`+0xd0`** |
| `__AUTH_CONST.__cfstring` | `0x840` | `0x900` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x89c` | `0x934` | **`+0x98`** |
| `__TEXT.__swift5_capture` | `0x104` | `0x14c` | **`+0x48`** |
| `__TEXT.__swift5_fieldmd` | `0x634` | `0x67c` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x7d6` | `0x814` | **`+0x3e`** |
| `__DATA_CONST.__got` | `0x720` | `0x758` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x566` | `0x598` | **`+0x32`** |
| `__DATA_DIRTY.__data` | `0x900` | `0x930` | **`+0x30`** |
| `__AUTH.__data` | `0xc0` | `0xe8` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0xf8` | `0x11c` | **`+0x24`** |
| `__DATA_CONST.__objc_classlist` | `0x108` | `0x120` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x198` | `0x1b0` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x160` | `0x174` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x648` | `0x638` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x70` | `0x80` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xb4` | `0xc0` | **`+0xc`** |
| `__DATA_CONST.__objc_protolist` | `0x140` | `0x148` | **`+0x8`** |

### Other Changes

```diff

-7027.0.64.0.0
+7027.0.67.2.1

+  - /System/Library/PrivateFrameworks/ProtocolBuffer.framework/ProtocolBuffer

-  Functions: 1450
-  Symbols:   1331
-  CStrings:  284
+  Functions: 1614
+  Symbols:   1442
+  CStrings:  302
Symbols:
+ +[HACodableUserInteractionSync interactionsType]
+ -[HACodableUserInteraction .cxx_destruct]
+ -[HACodableUserInteraction copyTo:]
+ -[HACodableUserInteraction copyWithZone:]
+ -[HACodableUserInteraction description]
+ -[HACodableUserInteraction dictionaryRepresentation]
+ -[HACodableUserInteraction expirationDate]
+ -[HACodableUserInteraction featureIdentifier]
+ -[HACodableUserInteraction hasExpirationDate]
+ -[HACodableUserInteraction hasFeatureIdentifier]
+ -[HACodableUserInteraction hasInteractionDate]
+ -[HACodableUserInteraction hasInteractionType]
+ -[HACodableUserInteraction hasItemIdentifier]
+ -[HACodableUserInteraction hasUuid]
+ -[HACodableUserInteraction hash]
+ -[HACodableUserInteraction interactionDate]
+ -[HACodableUserInteraction interactionType]
+ -[HACodableUserInteraction isEqual:]
+ -[HACodableUserInteraction itemIdentifier]
+ -[HACodableUserInteraction mergeFrom:]
+ -[HACodableUserInteraction readFrom:]
+ -[HACodableUserInteraction setExpirationDate:]
+ -[HACodableUserInteraction setFeatureIdentifier:]
+ -[HACodableUserInteraction setHasExpirationDate:]
+ -[HACodableUserInteraction setHasInteractionDate:]
+ -[HACodableUserInteraction setInteractionDate:]
+ -[HACodableUserInteraction setInteractionType:]
+ -[HACodableUserInteraction setItemIdentifier:]
+ -[HACodableUserInteraction setUuid:]
+ -[HACodableUserInteraction uuid]
+ -[HACodableUserInteraction writeTo:]
+ -[HACodableUserInteractionSync .cxx_destruct]
+ -[HACodableUserInteractionSync addInteractions:]
+ -[HACodableUserInteractionSync clearInteractions]
+ -[HACodableUserInteractionSync copyTo:]
+ -[HACodableUserInteractionSync copyWithZone:]
+ -[HACodableUserInteractionSync description]
+ -[HACodableUserInteractionSync dictionaryRepresentation]
+ -[HACodableUserInteractionSync hash]
+ -[HACodableUserInteractionSync interactionsAtIndex:]
+ -[HACodableUserInteractionSync interactionsCount]
+ -[HACodableUserInteractionSync interactions]
+ -[HACodableUserInteractionSync isEqual:]
+ -[HACodableUserInteractionSync mergeFrom:]
+ -[HACodableUserInteractionSync readFrom:]
+ -[HACodableUserInteractionSync setInteractions:]
+ -[HACodableUserInteractionSync writeTo:]
+ -[HDHealthAppDaemonExtension runUpdateSharingReminderScheduledAlarmCommand]
+ -[HDHealthAppSharingReminderRestorableAlarm _migrateLegacySyncedSharingReminderDateIfNeeded]
+ OBJC_IVAR_$_HACodableUserInteraction._expirationDate
+ OBJC_IVAR_$_HACodableUserInteraction._featureIdentifier
+ OBJC_IVAR_$_HACodableUserInteraction._has
+ OBJC_IVAR_$_HACodableUserInteraction._interactionDate
+ OBJC_IVAR_$_HACodableUserInteraction._interactionType
+ OBJC_IVAR_$_HACodableUserInteraction._itemIdentifier
+ OBJC_IVAR_$_HACodableUserInteraction._uuid
+ OBJC_IVAR_$_HACodableUserInteractionSync._interactions
+ _HACodableUserInteractionReadFrom
+ _HACodableUserInteractionSyncReadFrom
+ _IsOutgoingInvite
+ _OBJC_CLASS_$_HACodableUserInteraction
+ _OBJC_CLASS_$_HACodableUserInteractionSync
+ _OBJC_CLASS_$_HAHDUserInteractionStateSyncEntity
+ _OBJC_CLASS_$_PBCodable
+ _OBJC_IVAR_$_HDHealthAppSharingReminderRestorableAlarm._legacySyncedSharingKeyValueDomain
+ _OBJC_METACLASS_$_HACodableUserInteraction
+ _OBJC_METACLASS_$_HACodableUserInteractionSync
+ _OBJC_METACLASS_$_HAHDUserInteractionStateSyncEntity
+ _OBJC_METACLASS_$_PBCodable
+ _PBDataWriterWriteDataField
+ _PBDataWriterWriteDoubleField
+ _PBDataWriterWriteStringField
+ _PBDataWriterWriteSubmessage
+ _PBReaderPlaceMark
+ _PBReaderReadData
+ _PBReaderReadString
+ _PBReaderRecallMark
+ _PBReaderSkipValueWithTag
+ __CLASS_METHODS_HAHDUserInteractionStateSyncEntity
+ __CLASS_PROPERTIES_HAHDUserInteractionStateSyncEntity
+ __DATA_HAHDUserInteractionStateSyncEntity
+ __INSTANCE_METHODS_HAHDUserInteractionStateSyncEntity
+ __METACLASS_DATA_HAHDUserInteractionStateSyncEntity
+ __OBJC_$_CLASS_METHODS_HACodableUserInteractionSync
+ __OBJC_$_INSTANCE_METHODS_HACodableUserInteraction
+ __OBJC_$_INSTANCE_METHODS_HACodableUserInteractionSync
+ __OBJC_$_INSTANCE_METHODS_HDHealthAppDaemonExtension(HealthAppHealthDaemon)
+ __OBJC_$_INSTANCE_VARIABLES_HACodableUserInteraction
+ __OBJC_$_INSTANCE_VARIABLES_HACodableUserInteractionSync
+ __OBJC_$_PROP_LIST_HACodableUserInteraction
+ __OBJC_$_PROP_LIST_HACodableUserInteractionSync
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSCopying
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSCopying
+ __OBJC_CLASS_PROTOCOLS_$_HACodableUserInteraction
+ __OBJC_CLASS_PROTOCOLS_$_HACodableUserInteractionSync
+ __OBJC_CLASS_RO_$_HACodableUserInteraction
+ __OBJC_CLASS_RO_$_HACodableUserInteractionSync
+ __OBJC_LABEL_PROTOCOL_$_NSCopying
+ __OBJC_METACLASS_RO_$_HACodableUserInteraction
+ __OBJC_METACLASS_RO_$_HACodableUserInteractionSync
+ __OBJC_PROTOCOL_$_NSCopying
+ __PROTOCOLS_HAHDUserInteractionStateSyncEntity
+ ___75-[HDHealthAppDaemonExtension runUpdateSharingReminderScheduledAlarmCommand]_block_invoke
+ __swift_stdlib_bridgeErrorToNSError
+ _associated conformance 09HealthAppA6Daemon30UserInteractionStateSyncEntityC11DecodeErrorOSHAASQ
+ _swift_release_x12
+ _swift_unknownObjectWeakDestroy
+ _swift_unknownObjectWeakInit
+ _swift_unknownObjectWeakLoadStrong
+ _symbolic So26HDHealthAppDaemonExtensionCSgXw
+ _symbolic _____ 09HealthAppA6Daemon04WeakC9Extension33_DCA2C41A74E113AF13803D8BBA83189DLLV
+ _symbolic _____ 09HealthAppA6Daemon30UserInteractionStateSyncEntityC
+ _symbolic _____ 09HealthAppA6Daemon30UserInteractionStateSyncEntityC11DecodeErrorO
+ _type_layout_string 09HealthAppA6Daemon04WeakC9Extension33_DCA2C41A74E113AF13803D8BBA83189DLLV
- _HAHealthAppLegacySharingEntriesDomain
- _HAHealthAppLegacySharingReminderNotificationDateKey
- __OBJC_$_INSTANCE_METHODS_HDHealthAppDaemonExtension
CStrings:
+ " WHERE feature_identifier = ?"
+ "$"
+ "%@ %@"
+ "Re-run HDHealthAppDaemonExtension -updateSharingReminderScheduledAlarm"
+ "SELECT DISTINCT feature_identifier FROM HealthAppDatabaseSchema_user_interactions"
+ "[%s] Bulk updateData was called on a dynamic-key entity; per-key path expected"
+ "[%s] Encoded interaction record is %ld bytes; approaching CloudKit per-record limit"
+ "[%s] Failed to fetch distinct feature identifiers: %@"
+ "[%s] No user interaction store on profile for feature %s"
+ "[%s] State sync finished for feature %s with %s"
+ "[%{public}@] Could not migrate sharing reminder date to device-local store: %{public}@"
+ "[%{public}@] Could not read device-local sharing reminder date during migration: %{public}@"
+ "[%{public}@] Could not remove legacy synced sharing reminder date after migration: %{public}@"
+ "[%{public}@] Could not set sharing reminder anchor date: %{public}@. Will try again on handling alarm event."
+ "[%{public}@] Migrated sharing reminder date %{public}@ from legacy synced store to device-local store"
+ "[%{public}@] Set sharing reminder anchor date to: %{public}@"
+ "expirationDate"
+ "extension deallocated"
+ "featureIdentifier"
+ "health-sharing-reminder-notification-trigger"
+ "interactionDate"
+ "interactionType"
+ "interactions"
+ "itemIdentifier"
- "SharingReminderNotificationDate"
- "[%{public}@] Could not set sharing reminder date: %{public}@. Will try again on handling alarm event."
- "[%{public}@] No fallback date found, using current date as backup to the backup: %@"
- "[%{public}@] Set sharing reminder date to existing date: %{public}@"
- "[%{public}@] Set sharing reminder date to fallback date: %{public}@"
- "com.apple.Health.SharingEntries"
```
