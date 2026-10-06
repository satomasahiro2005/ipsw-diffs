## MobileAssetDaemon

> `/System/Library/PrivateFrameworks/MobileAssetDaemon.framework/MobileAssetDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26284c` | `0x261884` | **`-0xfc8`** |
| `__TEXT.__cstring` | `0x3f3f6` | `0x3f146` | **`-0x2b0`** |
| `__DATA_CONST.__got` | `0x1070` | `0x1280` | **`+0x210`** |
| `__AUTH_CONST.__cfstring` | `0x329a0` | `0x32820` | **`-0x180`** |
| `__TEXT.__gcc_except_tab` | `0xdbf8` | `0xda84` | **`-0x174`** |
| `__TEXT.__oslogstring` | `0x5e2fd` | `0x5e40d` | **`+0x110`** |
| `__AUTH.__objc_data` | `0x940` | `0x878` | **`-0xc8`** |
| `__DATA_DIRTY.__objc_data` | `0x2468` | `0x2530` | **`+0xc8`** |
| `__AUTH_CONST.__objc_const` | `0x18e40` | `0x18ed0` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x12c84` | `0x12c04` | **`-0x80`** |
| `__TEXT.__unwind_info` | `0x4888` | `0x4818` | **`-0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0xaf28` | `0xaec0` | **`-0x68`** |
| `__DATA_DIRTY.__bss` | `0x560` | `0x5b0` | **`+0x50`** |
| `__DATA.__bss` | `0x598` | `0x550` | **`-0x48`** |
| `__DATA_DIRTY.__data` | `0x78` | `0xa8` | **`+0x30`** |
| `__AUTH.__data` | `0xe8` | `0xc0` | **`-0x28`** |
| `__DATA.__objc_ivar` | `0x1804` | `0x1810` | **`+0xc`** |
| `__DATA.__data` | `0x1120` | `0x1118` | **`-0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0xeb8` | `0xec0` | **`+0x8`** |

### Other Changes

```diff

-2215.0.4.0.0
+2215.0.13.0.0

-  Functions: 7278
-  Symbols:   11420
-  CStrings:  10965
+  Functions: 7268
+  Symbols:   11412
+  CStrings:  10947
Symbols:
+ +[MADAnalyticsBiomeEventPayload biomePayloadPSUSComplete:]
+ +[MADAutoAssetControlManager preferenceStagerInjectAvailableAlreadyDownloaded]
+ +[MADAutoAssetSecure dedupAssetSelectors:dedupingSelectors:]
+ +[MADAutoAssetSecure doesPersonalizationErrorIndicateServerUnreachable:]
+ +[SecureMobileAssetBundle doesPersonalizationErrorIndicateServerUnreachable:]
+ -[MADAutoAssetControlManager _checkAndEmitPSUSCompletionIfNeeded]
+ -[MADAutoAssetControlManager _emitPSUSCompletionBiomeEvent]
+ -[MADAutoAssetControlManager assetPersonalizatonAttemptCompletePostEvent:withControlParam:justEncounteredError:]
+ -[MADAutoAssetControlManager preferenceStagerInjectAvailableAlreadyDownloaded]
+ -[MADAutoAssetControlManager psusCompletionEventEmitted]
+ -[MADAutoAssetControlManager setPreferenceStagerInjectAvailableAlreadyDownloaded:]
+ -[MADAutoAssetControlManager setPsusCompletionEventEmitted:]
+ -[MADAutoAssetJob addToPrePersonalizedSelectors:addingAssetSelector:]
+ -[MADAutoAssetJob nextSetAtomicEntryToDownload]
+ -[MADAutoAssetJob refreshOnFilesystemFromManagerPromotingIfStaged:promotingIfStaged:]
+ -[MADAutoAssetJob setAtomicEntriesToDownload]
+ -[MADAutoAssetJob setNextSetAtomicEntryToDownload:]
+ -[MADAutoAssetJob setSetAtomicEntriesToDownload:]
+ -[MADAutoAssetStager injectAvailableAlreadyDownloaded:]
+ GCC_except_table154
+ GCC_except_table306
+ GCC_except_table314
+ GCC_except_table316
+ GCC_except_table318
+ GCC_except_table322
+ GCC_except_table324
+ GCC_except_table326
+ GCC_except_table327
+ GCC_except_table347
+ GCC_except_table348
+ GCC_except_table349
+ GCC_except_table353
+ GCC_except_table362
+ GCC_except_table365
+ GCC_except_table366
+ GCC_except_table370
+ GCC_except_table398
+ GCC_except_table401
+ GCC_except_table431
+ GCC_except_table437
+ GCC_except_table439
+ GCC_except_table440
+ GCC_except_table441
+ GCC_except_table442
+ GCC_except_table519
+ GCC_except_table521
+ GCC_except_table578
+ GCC_except_table579
+ GCC_except_table619
+ GCC_except_table621
+ GCC_except_table627
+ GCC_except_table642
+ GCC_except_table671
+ GCC_except_table805
+ GCC_except_table806
+ GCC_except_table807
+ GCC_except_table808
+ _OBJC_IVAR_$_MADAutoAssetControlManager._preferenceStagerInjectAvailableAlreadyDownloaded
+ _OBJC_IVAR_$_MADAutoAssetControlManager._psusCompletionEventEmitted
+ _OBJC_IVAR_$_MADAutoAssetJob._nextSetAtomicEntryToDownload
+ _OBJC_IVAR_$_MADAutoAssetJob._setAtomicEntriesToDownload
+ _OUTLINED_FUNCTION_48
+ _OUTLINED_FUNCTION_73
+ _OUTLINED_FUNCTION_75
+ _kMobileAssetPreferencesAutoAssetStagerInjectAvailableAlreadyDownloaded
- +[MADActivityManager transferOwnership:toOwner:reason:]
- +[MADAutoAssetStager migrateMismatchedPersistedSetPromotionVersion:forEntryID:withMismatchedState:]
- -[DownloadManager getBackoffParametersForError:base:max:]
- -[DownloadManager retryDelayForDownloadError:retryCount:]
- -[MADAutoAssetControlManager assetPersonalizatonAttemptCompletePostEvent:withControlParam:]
- -[MADAutoAssetControlManager doesSetDescriptor:coverAllForAtomicInstanceEntries:]
- -[MADAutoAssetControlManager findAtomicEntryForAssetType:forAssetSpecifier:representedByLookupResult:]
- -[MADAutoAssetControlManager findAtomicEntryForAssetType:forAssetSpecifier:representedByStatus:]
- -[MADAutoAssetControlManager findSetEntryForAssetType:forAssetSpecifier:representedByConfiguration:]
- -[MADAutoAssetControlManager locateSetDescriptorActiveJobPreferringByAtomicInstance:elseByClientDomain:forAssetSetIdentifier:]
- -[MADAutoAssetControlManager notifyLockerAsIndicatedByJob:]
- -[MADAutoAssetControlManager osTransactionNamePreviouslyInFlightJob:]
- -[MADAutoAssetJob action_RemoveClient:error:]
- -[MADAutoAssetJob action_SetLookupNoneContinue:error:]
- -[MADAutoAssetJob appendUniqueSelectorForDescriptor:toArray:]
- -[MADAutoAssetJob assetSetEntryForAssetMetadata:]
- -[MADAutoAssetJob nextSetSpecifierToDownload]
- -[MADAutoAssetJob refreshOnFilesystemFromManagerPromotingIfStaged:]
- -[MADAutoAssetJob setEntryBeingDownloaded]
- -[MADAutoAssetJob setNextSetSpecifierToDownload:]
- -[MADAutoAssetStager action_AddToStagedDecideMoreAvailable:error:]
- -[MADAutoAssetStager action_AlteredInvalAllAvailable:error:]
- -[MADAutoAssetStager action_AlteredInvalAllAvailableCancelActiveJob:error:]
- -[MADAutoAssetStager action_ClientAcceptEraseCancelActiveJob:error:]
- -[MADAutoAssetStager action_ClientNewerReplyEmptyDetermine:error:]
- -[MADAutoAssetStager action_DecideMoreAvailable:error:]
- -[MADAutoAssetStager action_ReplyNothingStagedEraseAll:error:]
- -[MADAutoAssetStager action_SetTargetInvalAllAvailable:error:]
- -[MADAutoAssetStager action_SetTargetInvalAllAvailableCancelActiveJob:error:]
- -[MADAutoAssetStager purgeAlreadyStagedNotApplicableForRequiredByTarget:andNotApplicableForOptionalByTarget:]
- GCC_except_table141
- GCC_except_table156
- GCC_except_table313
- GCC_except_table333
- GCC_except_table334
- GCC_except_table342
- GCC_except_table344
- GCC_except_table345
- GCC_except_table346
- GCC_except_table355
- GCC_except_table356
- GCC_except_table369
- GCC_except_table372
- GCC_except_table373
- GCC_except_table374
- GCC_except_table375
- GCC_except_table377
- GCC_except_table378
- GCC_except_table405
- GCC_except_table408
- GCC_except_table444
- GCC_except_table445
- GCC_except_table446
- GCC_except_table447
- GCC_except_table448
- GCC_except_table449
- GCC_except_table526
- GCC_except_table528
- GCC_except_table585
- GCC_except_table586
- GCC_except_table624
- GCC_except_table626
- GCC_except_table632
- GCC_except_table647
- GCC_except_table676
- GCC_except_table809
- GCC_except_table810
- GCC_except_table812
- GCC_except_table815
- _OBJC_IVAR_$_MADAutoAssetJob._nextSetSpecifierToDownload
- _OUTLINED_FUNCTION_47
- _OUTLINED_FUNCTION_72
- _OUTLINED_FUNCTION_74
CStrings:
+ "%@:_setCalculateDownloadSpace"
+ "%@:newStagingInfoWithGroupsAvailableForStaging"
+ "%@:refreshOnFilesystemFromManagerPromotingIfStaged"
+ "%{public}@ | {%{public}@} auto-control-manager known descriptor count:%ld | specifierSelector:%{public}@, versionSelector:%{public}@"
+ "%{public}@ | {%{public}@} isOnFilesystem:%{public}@ | assetVersion:%{public}@ | candidate:%{public}@"
+ "%{public}@ | {remainingSetDescriptorToBeDownloaded} about to advance | nextSetAtomicEntryToDownload:%ld | totalEntriesToDownload:%ld"
+ "%{public}@ | {remainingSetDescriptorToBeDownloaded} done advancing | remaingToBeDownloaded:%@"
+ "%{public}@ | {remainingSetDescriptorToBeDownloaded} no newer to download | skipping nextEntryToDownload:%{public}@ | nextSetAtomicEntryToDownload:%ld"
+ "Loaded built-in MobileAssetDaemon_Framework Jun 27 2026 04:21:22"
+ "MAAIRB_NOTIF_PSUS_COMPLETE"
+ "PSUS_ALL_WORK_COMPLETE     "
+ "[PSUS-COMPLETE] all PSUS promotion work complete"
+ "[overall]instance:%@,selector:%@,UUID:%@,tasks:%lu,requests:%ld,table:%@,FSM:%@,sched:%@,NWFail:%@|beingCancled:%@|[earlier]sched:%@,NWFail:%@|bonded:%@|[active]instance:%@,desire:%@(awaitDownload:%@,checkAwait:%@),found:%@,end:%@,listen:%@,jobInfo:%@|[aggregated]policy:%@,clientRequested:%@|firstClientName:%@,triggeringLayer:%@|onFilesystemByVersion:%ld|[check]Base:%@,UUID:%@,lookupGrant:%@,rampFG:%@,rampLatch:%@,options:%@|[asset]base:%@,patch:%@,full:%@,newer:%@,downloading:%@,scheduler:%@,lookupRsp:%@(forConfig:%@),user:%@,boosting:%@,checking:%@,determining:%@,locking:%@,patched:%@|[installed]:version:%@,build:%@|[status]current:%@,progress:%@,lastPatch:%@|[results]selector:%@,instance:%@,found:%@,end:%@,listen:%@,[set]aggregatedPolicy:%@,descriptor:%@,setToDownload:%ld,next:%ld,found:%@,discardRampled:%@"
+ "com.apple.eligibilityd"
+ "invalid nextSetAtomicEntryToDownload value"
+ "nil prePersonalizedSelector provided to addToPrePersonalizedSelectors"
+ "no next to place | nextSetAtomicEntryToDownload:%ld, autoAssetEntries:%ld"
+ "psusCompletionEmitted"
+ "{%@} failed to build attributes/expected-bytes | groupName:%@"
+ "{%{public}@:injectAvailableAlreadyDownloaded} injecting already-downloaded auto-asset-descriptor | autoAssetDescriptor:%{public}@"
+ "{%{public}@} (%{public}@)\n[SET-DECIDE-FOUND] filtering of assets to be downloaded | assetType:%{public}@\n>>> AlreadyPersonalized:%{public}@\n>>> RequiresPersonalization:%{public}@\n>>> toBeDownloaded:%{public}@"
+ "{%{public}@} (%{public}@)\n[SET-DECIDE-FOUND] potential full selector | potentialDescriptor:%{public}@ | latestOnFilesystem:%{public}@"
+ "{%{public}@} deduped array of asset-selectors | toBeDedupedSelectors:%ld | duplicated:\n%{public}@"
+ "{%{public}@} prior to deduping available-for-staging that includes already-downloaded | indicateHaveAvailable:%{public}@ | targetLookupKey:%{public}@ | availableForStagingByTarget:%ld"
+ "{%{public}@} stripped out already-downloaded | indicateHaveAvailable:%{public}@ | targetLookupKey:%{public}@ | availableForStagingByTarget:%ld"
+ "{freshnessChangeNewLatestToVendClientDomainNames} __freshnessClientDomainNames:\n%{public}@"
- "%{public}@\n[AUTO-STAGER] {AddToStagedDecideMoreAvailable} asset-descriptor ALREADY-DOWNLOADED | self.activeJobDescriptor:%{public}@"
- "%{public}@\n[AUTO-STAGER] {ClientNewerReplyEmptyDetermine} [STAGING-CLIENT-REQUEST(DETERMINE)] when committed to other operation | [NO-CANDIDATES]"
- "%{public}@ %{public}@ OWNER %{public}@=>%{public}@ | %{public}@"
- "%{public}@ | {refreshOnFilesystemFromManagerPromotingIfStaged} auto-control-manager known descriptor count:%ld | specifierSelector:%{public}@, versionSelector:%{public}@"
- "%{public}@ | {refreshOnFilesystemFromManagerPromotingIfStaged} isOnFilesystem:%{public}@ | assetVersion:%{public}@ | candidate:%{public}@"
- "%{public}@ | {remainingSetDescriptorToBeDownloaded} no newer to download | skipping nextEntryToDownload:%{public}@"
- "(%{public}@)\n[SET-DECIDE-FOUND] potential full selector: %{public}@:potentialDescriptor:%{public}@,onFS:%{public}@"
- "AddToStagedDecideMoreAvailable"
- "AlteredInvalAllAvailable"
- "AlteredInvalAllAvailableCancelActiveJob"
- "ClientAcceptEraseCancelActiveJob"
- "ClientNewerReplyEmptyDetermine"
- "DecideMoreAvailable"
- "Loaded built-in MobileAssetDaemon_Framework Jun 16 2026 00:19:07"
- "MADJob:RemoveClient"
- "MADJob:SetLookupNoneContinue"
- "MADStager:AddToStagedDecideMoreAvailable"
- "MADStager:AlteredInvalAllAvailable"
- "MADStager:AlteredInvalAllAvailableCancelActiveJob"
- "MADStager:ClientAcceptEraseCancelActiveJob"
- "MADStager:ClientNewerReplyEmptyDetermine"
- "MADStager:DecideMoreAvailable"
- "MADStager:ReplyNothingStagedEraseAll"
- "MADStager:SetTargetInvalAllAvailable"
- "MADStager:SetTargetInvalAllAvailableCancelActiveJob"
- "ReplyNothingStagedEraseAll"
- "SetLookupNoneContinue"
- "SetTargetInvalAllAvailable"
- "SetTargetInvalAllAvailableCancelActiveJob"
- "[AUTO-ASSET] [LOCAL-CONTENT-URL] {notifyLockerAsIndicatedByJob} %{public}@"
- "[NOTIFY-LOCKER] found auto-asset without localContentURL and/or assetAttributes in response message"
- "[NOTIFY-LOCKER] no indication of found auto-asset in response message"
- "[overall]instance:%@,selector:%@,UUID:%@,tasks:%lu,requests:%ld,table:%@,FSM:%@,sched:%@,NWFail:%@|beingCancled:%@|[earlier]sched:%@,NWFail:%@|bonded:%@|[active]instance:%@,desire:%@(awaitDownload:%@,checkAwait:%@),found:%@,end:%@,listen:%@,jobInfo:%@|[aggregated]policy:%@,clientRequested:%@|firstClientName:%@,triggeringLayer:%@|onFilesystemByVersion:%ld|[check]Base:%@,UUID:%@,lookupGrant:%@,rampFG:%@,rampLatch:%@,options:%@|[asset]base:%@,patch:%@,full:%@,newer:%@,downloading:%@,scheduler:%@,lookupRsp:%@(forConfig:%@),user:%@,boosting:%@,checking:%@,determining:%@,locking:%@,patched:%@|[installed]:version:%@,build:%@|[status]current:%@,progress:%@,lastPatch:%@|[results]selector:%@,instance:%@,found:%@,end:%@,listen:%@,[set]aggregatedPolicy:%@,descriptor:%@,next:%ld,found:%@,discardRampled:%@"
- "auto-asset-job failed without providing operationError"
- "auto-asset-job has indicated failure to downloaded content"
- "com.apple.MobileAsset.AutoControlManager.Job.PreviouslyInFlight"
- "found by job yet no local content URL | found:%@"
- "invalid nextSetSpecifierToDownload value"
- "no next to place | nextSetSpecifierToDownload:%ld, autoAssetEntries:%ld"
- "notifyLockerAsIndicatedByJob"
- "purgeAlreadyStagedNotApplicableForRequiredByTarget"
- "{%@:newStagingInfoWithGroupsAvailableForStaging} failed to build attributes/expected-bytes | groupName:%@"
- "{notifyLockerAsIndicatedByJob} [NOTIFY-LOCKER] client lock request without desire for eventInfo:%@"
- "{notifyLockerAsIndicatedByJob} [NOTIFY-LOCKER] should never be called for set-job"
```
