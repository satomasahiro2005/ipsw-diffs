## com.apple.siri.embeddedspeech

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/XPCServices/com.apple.siri.embeddedspeech.xpc/com.apple.siri.embeddedspeech`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33cdc` | `0x34ed4` | **`+0x11f8`** |
| `__TEXT.__objc_methname` | `0xa6dc` | `0xa859` | **`+0x17d`** |
| `__TEXT.__unwind_info` | `0x798` | `0x8c8` | **`+0x130`** |
| `__TEXT.__objc_stubs` | `0x8500` | `0x8600` | **`+0x100`** |
| `__TEXT.__cstring` | `0x4e7f` | `0x4f68` | **`+0xe9`** |
| `__DATA_CONST.__const` | `0xd00` | `0xde8` | **`+0xe8`** |
| `__TEXT.__gcc_except_tab` | `0x1b84` | `0x1aa4` | **`-0xe0`** |
| `__TEXT.__oslogstring` | `0x4b76` | `0x4c38` | **`+0xc2`** |
| `__TEXT.__const` | `0x100` | `0x150` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x2528` | `0x2568` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1cfc` | `0x1d2c` | **`+0x30`** |
| `__DATA.__objc_const` | `0x3260` | `0x3280` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x2e00` | `0x2e20` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x970` | `0x980` | **`+0x10`** |
| `__DATA.__bss` | `0x158` | `0x150` | **`-0x8`** |
| `__DATA.__common` | `—` | `0x8` | **`+0x8`** |
| `__DATA.__data` | `0x328` | `0x330` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x4c8` | `0x4d0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x868` | `0x870` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x304` | `0x308` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-3600.70.47.11.1
+3605.10.1.0.0

-  Functions: 611
-  Symbols:   428
-  CStrings:  2564
+  Functions: 836
+  Symbols:   512
+  CStrings:  2579
Symbols:
+ _ESLogContext
+ _ESLogInitIfNeeded
+ _ESModelInfoQuasarModelPathKey
+ _ESModelInfoTypeKey
+ _ESUserDataAppContactFirstKey
+ _ESUserDataAppContactLastKey
+ _ESUserDataAppContactMiddleKey
+ _ESUserDataAppContactPersonFullNameFirstKey
+ _ESUserDataAppContactSMSGroupNameFirstKey
+ _ESUserDataComponentsKey
+ _ESUserDataContactCompanyKey
+ _ESUserDataContactCompanyPhoneticKey
+ _ESUserDataContactFirstKey
+ _ESUserDataContactFirstPhoneticKey
+ _ESUserDataContactFirstPronunciationKey
+ _ESUserDataContactLastKey
+ _ESUserDataContactLastPhoneticKey
+ _ESUserDataContactLastPronunciationKey
+ _ESUserDataContactMiddleKey
+ _ESUserDataContactMiddlePhoneticKey
+ _ESUserDataContactNicknameKey
+ _ESUserDataFrequencyKey
+ _ESUserDataOrthographyKey
+ _ESUserDataPronunciationsKey
+ _ESUserDataUserAccountIdentityFirstKey
+ _OBJC_CLASS_$_ESAlignmentState
+ _OBJC_CLASS_$_ESAppEntityItemProcessor
+ _OBJC_CLASS_$_ESAssetManager
+ _OBJC_CLASS_$_ESAudioPacket
+ _OBJC_CLASS_$_ESAudioPacketTimestamps
+ _OBJC_CLASS_$_ESBiomeAsrRecord
+ _OBJC_CLASS_$_ESBiomeRecord
+ _OBJC_CLASS_$_ESConnection
+ _OBJC_CLASS_$_ESContactItemProcessor
+ _OBJC_CLASS_$_ESContextualData
+ _OBJC_CLASS_$_ESEntityBudget
+ _OBJC_CLASS_$_ESEuclidDatabaseAttributes
+ _OBJC_CLASS_$_ESItemProcessor
+ _OBJC_CLASS_$_ESListenerDelegate
+ _OBJC_CLASS_$_ESProfiler
+ _OBJC_CLASS_$_ESRadioItemProcessor
+ _OBJC_CLASS_$_ESSelfHelper
+ _OBJC_CLASS_$_ESSelfPreheatWithPowerContainer
+ _OBJC_CLASS_$_ESSpeechProfileBuilderConnection
+ _OBJC_CLASS_$_ESStoreAudioData
+ _OBJC_CLASS_$_ESUaapLm
+ _OBJC_CLASS_$_ESUserData
+ _OBJC_CLASS_$_ESUserDataContactWord
+ _OBJC_CLASS_$_ESUserDataUtilities
+ _OBJC_CLASS_$_ESUserDataWriter
+ _OBJC_METACLASS_$_ESAlignmentState
+ _OBJC_METACLASS_$_ESAppEntityItemProcessor
+ _OBJC_METACLASS_$_ESAssetManager
+ _OBJC_METACLASS_$_ESAudioPacket
+ _OBJC_METACLASS_$_ESAudioPacketTimestamps
+ _OBJC_METACLASS_$_ESBiomeAsrRecord
+ _OBJC_METACLASS_$_ESBiomeRecord
+ _OBJC_METACLASS_$_ESConnection
+ _OBJC_METACLASS_$_ESContactItemProcessor
+ _OBJC_METACLASS_$_ESContextualData
+ _OBJC_METACLASS_$_ESEntityBudget
+ _OBJC_METACLASS_$_ESEuclidDatabaseAttributes
+ _OBJC_METACLASS_$_ESItemProcessor
+ _OBJC_METACLASS_$_ESListenerDelegate
+ _OBJC_METACLASS_$_ESProfiler
+ _OBJC_METACLASS_$_ESRadioItemProcessor
+ _OBJC_METACLASS_$_ESSelfHelper
+ _OBJC_METACLASS_$_ESSelfPreheatWithPowerContainer
+ _OBJC_METACLASS_$_ESSpeechProfileBuilderConnection
+ _OBJC_METACLASS_$_ESStoreAudioData
+ _OBJC_METACLASS_$_ESUaapLm
+ _OBJC_METACLASS_$_ESUserData
+ _OBJC_METACLASS_$_ESUserDataContactWord
+ _OBJC_METACLASS_$_ESUserDataUtilities
+ _OBJC_METACLASS_$_ESUserDataWriter
+ _aneModelInitializationContextFileNameKey
+ _aneModelInitializationContextTimestampKey
+ _com_apple_siri_embeddedspeechVersionNumber
+ _com_apple_siri_embeddedspeechVersionString
+ _kCESREntityTaggerCategoryPersonalName
+ _kESEuclidDatabaseSchemaVersion
+ _kESLogContext
+ _kTimestampKey
+ _objc_release_x10
CStrings:
+ "%s (%@) %lu/%lu identifier(s) for this update are already stored."
+ "%s (%@) Failed to look up identifiers, error: %@"
+ "%s (%@) Failed to re-initialize after removing database: %@"
+ "%s (%@) Failed to recreate CESREuclidVectorDB after update failure: %@"
+ "%s (%@) Recreating CESREuclidVectorDB to resolve potential schema mismatch."
+ "%s (%@) Version file already exists, skipping write"
+ "%s Cleaning up unused asset subscriptions."
+ "%s Retaining asset subscriptions for the active Dictation languages: %@"
+ "%s Retaining the asset subscription for the active Siri language: %@"
+ "-[ESAssetManager cleanupUnusedAssetSubscriptions]"
+ "-[ESSpeechProfileBuilderConnection _alreadyEmbeddedAssetIdentifiersForUpdate:]"
+ "-[ESSpeechProfileBuilderConnection _buildAndWriteProfileError:]"
+ "-[ESSpeechProfileBuilderConnection _buildAndWriteProfileError:]_block_invoke"
+ "-[ESSpeechProfileBuilderConnection _insertEmbeddingsFromEuclidProfileInsertionsByAssetIdentifier:error:]"
+ "-[ESSpeechProfileBuilderConnection _insertEmbeddingsFromEuclidProfileInsertionsByAssetIdentifier:error:]_block_invoke"
+ "-[ESSpeechProfileBuilderConnection _recreateDatabaseIfNeeded]"
+ "-[ESSpeechProfileBuilderConnection _wipeAndRecreateDatabase:]"
+ "-[ESSpeechProfileBuilderConnection _writeDatabaseVersionIfNeeded:error:]"
+ "\\sharedPlaylist-first"
+ "_alreadyEmbeddedAssetIdentifiersForUpdate:"
+ "_buildAndWriteProfileError:"
+ "_hasAttemptedSchemaRecoveryThisConnection"
+ "_insertEmbeddingsFromEuclidProfileInsertionsByAssetIdentifier:error:"
+ "_recreateDatabaseIfNeeded"
+ "_resolveFilteredInsertionsForUpdate:error:"
+ "_wipeAndRecreateDatabase:"
+ "_writeDatabaseVersionIfNeeded:error:"
+ "cleanupUnusedAssetSubscriptions"
+ "currentSiriLanguageCode"
+ "extractedEntityLmeAssignmentMapForParentEntity:extractionLmeAssignments:"
+ "handlePostInstallAssetSubscriptions"
+ "isAssistantEnabled"
+ "isDictationEnabled"
+ "stringIdentifiedAssetsWithIdentifiers:attributeFilters:pagination:includeVectors:error:"
+ "stringIdentifier"
- "\t-"
- "%s (%@) Failed to delete items from CESREuclidVectorDB, error: %@"
- "%s (%@) Failed to get database size, attempting drop and recreate: %@"
- "%s (%@) Failed to insert items into CESREuclidVectorDB, error: %@"
- "%s (%@) Failed to re-initialize after removing corrupt database: %@"
- "%s (%@) VSK drop failed, removing database directory: %@"
- "%s Cleaning up unused subscriptions."
- "-[ESAssetManager cleanupUnusedSubscriptions]"
- "-[ESSpeechProfileBuilderConnection _dropOrRecreateDatabase:]"
- "-[ESSpeechProfileBuilderConnection _insertEmbeddingsFromEuclidProfileInsertionsForAssetIdentifiers:error:]"
- "-[ESSpeechProfileBuilderConnection _insertEmbeddingsFromEuclidProfileInsertionsForAssetIdentifiers:error:]_block_invoke"
- "-[ESSpeechProfileBuilderConnection finishAndSaveProfile:completion:]"
- "-[ESSpeechProfileBuilderConnection finishAndSaveProfile:completion:]_block_invoke"
- "PersonalName"
- "_dropOrRecreateDatabase:"
- "_insertEmbeddingsFromEuclidProfileInsertionsForAssetIdentifiers:error:"
- "_isNonTier1Message:"
- "cleanupUnusedSubscriptions"
- "handlePostInstallSubscriptions"
- "performEntityExtraction:extractionLmeAssignments:"
```
