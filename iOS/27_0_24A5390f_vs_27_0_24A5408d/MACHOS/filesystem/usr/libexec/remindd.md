## remindd

> `/usr/libexec/remindd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x81486c` | `0x80f6c8` | **`-0x51a4`** |
| `__TEXT.__oslogstring` | `0x611e0` | `0x618b0` | **`+0x6d0`** |
| `__TEXT.__eh_frame` | `0x1f9f0` | `0x1f588` | **`-0x468`** |
| `__TEXT.__const` | `0x29548` | `0x292b8` | **`-0x290`** |
| `__TEXT.__cstring` | `0x18ed7` | `0x18c47` | **`-0x290`** |
| `__TEXT.__objc_methname` | `0x28361` | `0x284b1` | **`+0x150`** |
| `__TEXT.__swift5_capture` | `0x6454` | `0x6304` | **`-0x150`** |
| `__DATA.__data` | `0x1f460` | `0x1f330` | **`-0x130`** |
| `__DATA.__objc_data` | `0x8818` | `0x8708` | **`-0x110`** |
| `__DATA_CONST.__const` | `0x25f58` | `0x26068` | **`+0x110`** |
| `__TEXT.__swift5_typeref` | `0x142c2` | `0x143ce` | **`+0x10c`** |
| `__DATA.__objc_const` | `0x1dec8` | `0x1de08` | **`-0xc0`** |
| `__TEXT.__auth_stubs` | `0x8ba0` | `0x8c50` | **`+0xb0`** |
| `__TEXT.__objc_classname` | `0x6426` | `0x6396` | **`-0x90`** |
| `__DATA.__bss` | `0x23710` | `0x236b0` | **`-0x60`** |
| `__TEXT.__objc_stubs` | `0x1bbe0` | `0x1bc40` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x45e0` | `0x4638` | **`+0x58`** |
| `__DATA_CONST.__got` | `0x34e0` | `0x3530` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x460` | `0x410` | **`-0x50`** |
| `__TEXT.__constg_swiftt` | `0xd160` | `0xd118` | **`-0x48`** |
| `__TEXT.__objc_methlist` | `0xab50` | `0xab90` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x7ca0` | `0x7cd8` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0xc1a5` | `0xc175` | **`-0x30`** |
| `__TEXT.__swift5_fieldmd` | `0xa7c0` | `0xa7e4` | **`+0x24`** |
| `__TEXT.__swift_as_ret` | `0x228` | `0x204` | **`-0x24`** |
| `__DATA_CONST.__auth_ptr` | `0x28c0` | `0x28a0` | **`-0x20`** |
| `__DATA_CONST.__cfstring` | `0x5180` | `0x51a0` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x1eb8` | `0x1ed0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x10360` | `0x10348` | **`-0x18`** |
| `__TEXT.__swift5_proto` | `0x1904` | `0x1914` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x2d4` | `0x2e4` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xc58` | `0xc50` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0x20f8` | `0x20f0` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0xb38` | `0xb40` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x1c8` | `0x1cc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-4043.0.0.0.0
+4046.11.0.0.0

-  Functions: 22684
-  Symbols:   4259
-  CStrings:  11803
+  Functions: 22663
+  Symbols:   4278
+  CStrings:  11815
Symbols:
+ _$s16FoundationModels19SystemLanguageModelCMn
+ _$s19ReminderKitInternal22REMGroceryAvailabilityV19preferredCapability16localeIdentifierAA0dG0OSS_tF
+ _$s19ReminderKitInternal24REMRemindersListDataViewO13SectionsModelV8sections14remindersCount33hasIncompleteOrCompletedReminders010prefetchedQ00r3DueQ0031suggestedSectionCanonicalNameByA10IdentifierAESayAC0U4LiteVG_AC0lxP0VSgSbSgSayAA19REMReminder_CodableCGAUSDy10Foundation4UUIDVSSGtcfC
+ _$s19ReminderKitInternal27REMJSONDeserializationErrorO21unexpectedValueForKeyyACSScACmFWC
+ _$s19ReminderKitInternal30REMGrocerySuggestionInvocationC05ClearF0C10ParametersV11reminderIDsShyAA19REMObjectID_CodableCGvg
+ _$s19ReminderKitInternal30REMGrocerySuggestionInvocationC05ClearF0C10ParametersVMa
+ _$s19ReminderKitInternal30REMGrocerySuggestionInvocationC05ClearF0C10ParametersVSeAAMc
+ _$s19ReminderKitInternal30REMGrocerySuggestionInvocationC05ClearF0C6ResultVAGycfC
+ _$s19ReminderKitInternal30REMGrocerySuggestionInvocationC05ClearF0C6ResultVMa
+ _$s19ReminderKitInternal30REMGrocerySuggestionInvocationC05ClearF0C6ResultVSEAAMc
+ _$s19ReminderKitInternal30REMGrocerySuggestionInvocationC05ClearF0CAA25REMSwiftInvocableProtocolAAMc
+ _$s19ReminderKitInternal30REMGrocerySuggestionInvocationC05ClearF0CMa
+ _$s19ReminderKitInternal30REMGrocerySuggestionInvocationC05ClearF0CMn
+ _$sScTss5NeverORszABRs_rlE11isCancelledSbvgZ
+ _$ss15ContinuousClockV7InstantVs0C8ProtocolsMc
+ _$ss15ContinuousClockVs0B0sMc
+ _$ss15InstantProtocolP8advanced2byx8DurationQz_tFTj
+ _$ss5ClockP3now7InstantQzvgTj
+ _$ss5ClockP5sleep5until9tolerancey7InstantQz_8DurationQzSgtYaKFTj
+ _$ss5ClockP5sleep5until9tolerancey7InstantQz_8DurationQzSgtYaKFTjTu
+ _$ss5ClockPss010ContinuousA0VRszrlE10continuousADvgZ
+ _REMUnlocalizedDefaultListName
- _$s19ReminderKitInternal24REMRemindersListDataViewO13SectionsModelV8sections14remindersCount33hasIncompleteOrCompletedReminders010prefetchedQ00r3DueQ0AESayAC11SectionLiteVG_AC0l2ByP0VSgSbSgSayAA19REMReminder_CodableCGATtcfC
- _NSFileProtectionCompleteUntilFirstUserAuthentication
- _RDAutoCategorizationGroceryOperationAuthor
CStrings:
+ "%{public}s: Failed to decode '\\GroceryOperationQueueItem.configurationData' as 'RDAutoCategorizationOperationCategorizeRemindersInList.Configuration'. {operationQueueItem: %{public}s, error: %{public}s}"
+ "%{public}s: Selected grocery categorization backend {strategy: %{public}s}"
+ "Could not read ReminderKit CFBundleVersion; Spotlight rebuild-on-version-change disabled this launch"
+ "MERGE.LOCAL: ...REMCDList.existingLocalObjectToMerge found match by externalIdentifier {self: %{public}s, matched: %{public}s}"
+ "MERGE.LOCAL: ...appending CK-only reminders (added on another device during sign-out) {list: %{public}s, ckOnlyCount: %ld}"
+ "MERGE.LOCAL: ...reconstructed reminderIDs ordering from local list {list: %{public}s, count: %ld}"
+ "MERGE.LOCAL: ...reminderIDs ordering reconstruction yielded empty result, falling back to append-only {list: %{public}s}"
+ "MERGE.LOCAL: ...skipping reminderIDs ordering reconstruction — local list has no ordering data {list: %{public}s}"
+ "MERGE.LOCAL: ...skipping reminderIDs ordering reconstruction — nothing to merge or add {list: %{public}s}"
+ "MERGE.LOCAL: ...skipping stale entry in local ordering {localID: %{public}@, list: %{public}s}"
+ "MERGE.LOCAL: Error reconstructing reminderIDs ordering from local list {error: %{public}s}"
+ "Persisting spotlightIndexVersion=%{public}s after successful index wipe"
+ "Prewarming grocery categorization model"
+ "RDAutoCategorizationGroceryOperationCategorizeRemindersInList"
+ "RDAutoCategorizationOperationCategorizeRemindersInList"
+ "RDAutoCategorizationOperationDidEndNotification"
+ "RDGroceryCategorizer: LLM input items: %{private}s, tokenCount: %ld"
+ "RDGroceryCategorizer: start categorization"
+ "RDGroceryCategorizerModelCache: evicted cached grocery model after idle timeout"
+ "RDGroceryCategorizerModelCache: grocery categorization model warm"
+ "RDGroceryCategorizerPromptInputProcessor: input after processing nonEmptyTitlesCount: %ld"
+ "RDGroceryCategorizerPromptInputProcessor: input before processing reminderTitlesCount: %ld"
+ "RDGroceryCategorizerPromptInputProcessor: invalid input of non-empty titles"
+ "RDGroceryCategorizerPromptOutputProcessor: attributed sole prediction to the sole input title {predictedItem: %{private}s, inputTitle: %{private}s, section: %{public}s}"
+ "RDGroceryCorrectionCache: Recording {%{private}s): (from: %s, to: %s, locale: %s, version: %{public}s)} in list: %@"
+ "RDGroceryOperationCategorizeRemindersInGroceryList"
+ "Refusing to persist spotlightIndexVersion: target build version unreadable"
+ "Skipped inserting grocery operation queue item for downloading grocery model assets from Trial because preferred capability is not classic model."
+ "Skipped prewarming grocery categorization model because preferred capability is not the generative model."
+ "[Spotlight] Bundle index wipe complete; persisting version and activating {target: %{public}@}"
+ "[Spotlight] Bundle index wipe failed; activating without persisting version {error: %{public}@}"
+ "[Spotlight] Index version current; activating without wipe"
+ "[Spotlight] Index version outdated; deferring activation to wipe the bundle index first"
+ "[Spotlight] Index version outdated; wiping bundle index before activating {target: %{public}@}"
+ "[Spotlight] systemRequestExecutor not set — activating without _ivarLock"
+ "_TtC7remindd27RDGroceryCategorizerFactory"
+ "_TtC7remindd30RDGroceryCategorizerModelCache"
+ "activateCoreSpotlightDelegatesUnderLock"
+ "deleteAllRemindersSearchableItemsWithCompletionHandler:"
+ "deleteAllSearchableItemsForBundleID:completionHandler:"
+ "idleEvictionTask"
+ "infoDictionary"
+ "performBundleIndexWipeWithCompletionHandler:"
+ "requestPrewarmGroceryCategorizationModel"
+ "setSuggestedSectionsForRemindersAsData:"
+ "sharedRemindersSearchableIndex"
+ "strategy"
+ "suggestedSectionsForRemindersAsData"
+ "targetSpotlightIndexVersion"
+ "warmSession"
+ "wipeIndexThenActivateWithCompletionHandler:"
- "%{public}s: Failed to decode '\\GroceryOperationQueueItem.configurationData' as 'RDGroceryOperationCategorizeRemindersInGroceryList.Configuration'. {operationQueueItem: %{public}s, error: %{public}s}"
- "%{public}s: Inserted auto-categorization grocery operation queue item {operationType: %{public}s, entityIdentifier: %{public}s}"
- "%{public}s: Skipped auto-categorizing reminders because list should no longer categorize grocery items {listObjectID: %{public}@, reminderIDs: %{public}s}"
- "%{public}s: Start execution {listObjectID: %{public}@, reminderIDs: %{public}s}"
- "%{public}s: Updated unsaved auto-categorization grocery operation queue item {operationType: %s, entityIdentifier: %s}"
- "Persisting spotlightIndexVersion=%ld after successful reindex"
- "RDAutoCategorizationGroceryOperationQueue"
- "RDAutoCategorizationGroceryOperationQueue is disabled because store controller does not support it"
- "RDGroceryCategorizer: LLM input items: %{private}s"
- "RDGroceryCategorizer: input itemsCount: %ld, tokenCount: %ld"
- "RDGroceryCategorizer: prewarm finished, start categorization"
- "RDGroceryCategorizer: prewarm session"
- "RDGroceryCategorizerSession: {titles: %{private}s}"
- "RDGroceryCorrectionCache: Recording {%s: (from: %s, to: %s, locale: %s, version: %{public}s)} in list: %@"
- "Subclasses must override deploymentID()"
- "Subclasses must override osLog"
- "Subclasses must override postCategorizeSessionAnalytics(isListCategorization:inferenceTime:inputReminderCount:outputSectionCount:uncategorizedReminderCount:)"
- "Subclasses must override postLocalCorrectionsToCoreAnalytics(title:initialReminderMembership:initialSectionBySectionIdentifier:sectionIdentifier:localeID:deploymentID:)"
- "Subclasses must override postPredictionToCoreAnalytics(modelLocale:predictReason:predictedCategory:)"
- "Subclasses must override predictSectionName(forReminderTitles:list:existingSections:)"
- "Subclasses must override rdLog"
- "Subclasses must override shouldCategorizeList(_:)"
- "T@\"NSNumber\",N,R"
- "[Spotlight] Index version: current {persisted: %ld, target: %ld}"
- "[Spotlight] Index version: outdated {persisted: %ld, target: %ld}"
- "_TtC7remindd50RDGroceryOperationCategorizeRemindersInGroceryList"
- "_TtC7remindd58RDAutoCategorizationOperationCategorizeRemindersInListBase"
- "_TtC7remindd61RDAutoCategorizationGroceryOperationCategorizeRemindersInList"
- "autoCategorizationGroceryOperationQueue"
- "autoCategorizeGroceryRemindersInList"
- "autoCategorizerType"
- "classifierConfiguration"
- "l_activateCoreSpotlightDelegates"
- "rdFeedbackProvider"
- "rdLog"
- "reindexIfVersionOutdatedWithCompletionHandler:"
- "remindd/RDAutoCategorizationOperationCategorizeRemindersInListBase.swift"
- "supportsAutoCategorizationGroceryOperation"
- "targetSpotlightIndexVersionNumber"
```
